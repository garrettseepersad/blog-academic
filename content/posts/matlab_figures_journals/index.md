---
title: Plotting MATLAB figures for journals
subtitle: 
summary: 
authors:
- admin
tags: []
categories: []
date: "2013-12-25T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

One of the most frustrating tasks I encountered while using MATLAB was to output and store figures that were high resolution and the font size would be legible when copied into double column journals. Copying the figures directly (Edit -> Copy figure) works well but I always preferred to have my scripts run and have the files stored automatically to an assigned folder. The attached code is what I currently used. While the coding is very simple, it took quiet a while to assimilate those few lines to generate the quality of figure I was looking for.

```c
%% Plot figure 
grid on;
ylabel('y-axis label [units]','fontsize',18); %Label y-axis with a font value of 18
xlabel('x-axis label [units]','fontsize',18); %Label x-axis with a font value of 18
set(gca, 'FontSize' ,18) ;                     %Set font size of x and y axis values
set(gcf, 'Position', [   1           1        960        540] );  %Set dimension of figure
set(gcf, 'Color', 'w');                       %Change background of figure from grey to white
set(gca,'GridLineStyle','- -')                %Define grid line pattern (optional)
ti = get(gca,'TightInset')                    %Remove extra spacing around figure
set(gca, 'LooseInset', [0,0,0,0.01]);         %Depending on the figure, you may need to add extra spacing [left bottom width height])
 
print( '-dtiff',  ['figures\' filename ], '-r600');              %Change "-r600" to the required DPI
```
Another issue I have also encountered with outputting the images to file is the dimensions of the stored image may not match the image on screen. The following script re-sizes the output page to the dimensions of the on screen image. You would be required to change the pixels to inches.

```c
% Use the following site to convert pixels to inches: http://pixelyzer.com/image_size_calculator.html

width = 12.8;  % 960 pixels converted to inches
height = 7.2;  % 540 pixels converted to inches

set(f, 'PaperUnits', 'inches','PaperPosition',[0 0 width height]);% Remember to set "f=figure"
print( '-dtiff',  ['figures\' filename ], '-r600');
```