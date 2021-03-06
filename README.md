# Tableau Worksheets

## Introduction
Now that you have learned of the many features of Tableau, it is time to put that knowledge to work and create your first worksheet. To begin this lesson, you should have already downloaded and installed a version of Tableau Public (or Desktop if you choose). You will follow the instructions in this lesson using your version of Tableau to create and publish a basic worksheet.

## Objectives
You will be able to: 
* Load a data set into Tableau
* Create a basic worksheet
* Change the style of visualization
* Add title and descriptive information to the visualization
* Save and publish the worksheet to Tableau Public


## Loading Data

Before you begin this lesson, you will need to download the dataset from the lesson repository. Click on the link below to download the file, and you will be taken to the GitHub repository where a download dialogue box will open. In this dialogue box navigate to the __My Tableau Repository__ directory which was created during the Tableau installation. From this directory choose where you would like to save the file and complete the download.
<a href="https://github.com/learn-co-curriculum/dsc-tableau-worksheets-lab/raw/main/data/sample_superstore.xls" download target="_blank" download="sample_superstore.xls">Superstore Excel File</a>  
> This data set is avaliable for download directly through Tableau Public, but it is updated frequently, so to ensure you are able to follow along with the lesson, you should be using the file linked above.

We will begin this lesson by opening your version of Tableau on your desktop. Tableau should open in the __Start Page__ where you will find the __Connect Pane__. To load a dataset, you will need to click on the type of data source you wish to access, in our case it is __Microsoft Excel__. Select the __Microsoft Excel__ link and find the file you previously downloaded, __sample_superstore.xls__.

This file contains three sheets, but for now we will only be working with one. Drag the __orders__ sheet to the workspace so it will be added to the workbook. This will create a new sheet called __sheet1__ in the bottom tabs and it will be highlighted in orange like this: <a style="background-color:orange">Sheet1</a>. You can also see some information about the data you added to the workspace, this will allow you to understand what your data looks like, how many features and how many entries. Open up the worksheet by clicking on <a style="background-color:orange">Sheet1</a> in the bottom tabs.

## Your First Visualization

Now we will get a look at what Tableau can do. Suppose you are working for big box store, and you have been tasked with visulizing some data from this dataset. For your first task, you simply need to create a bar chart which displays the _Profit_ earned by _Sub-Category_. A good first step here is to add _Sub-Category_ which is a __Dimension__ to the _Columns_ shelf and _Profit_, which is a __Measure__ to the _Rows_ shelf. Once you have these two elements in place, you should see a default graph shown for this data which turns out to be the bar chart you were tasked with creating. 

<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/tableau/bar_chart.png" alt="Image of a bar chart with sub-category as the column names and the profit for those as the height of the bars" height=400px>

This is what you were looking for, but it is a little difficult to read the sub-categories at the bottom of the chart. One simple fix for this instance would be to swap the axes so the sub-categories become the rows and the profit becomes the columns. Find the swap-axis button and click it to see how it affects the visualization.

That's a bit better, but now it looks really cramped. Tableau provides a menu option to change how the visualizations fit in the workspace. You can find this __Fit__ option in the top tool bar where it will display the _Standard_ view option.  Click on the drop down menu and select _Entire View_ to stretch the visualization to fit the entire screen view.

Great! Now that we have a good looking bar chart, we can make it a little more informative. For instance, we would likely want the profit sorted so that it is easier to quickly find the highest or lowest profit earning sub-categories. Fortunately, Tableau has a tool for this! Find the descending sort button and apply it to the bar chart. And, just like that, we have a graph that helps us to find the information we are looking for.

With so many sub-categories, it may be a bit difficult to connect the sub-category with the cooresponding value, to fix this we can add some additional information to the graph. From the __Data Pane__ drag _Sub-Category_ and _Profit_ one at a time and drop them on the _Label_ icon in the __Marks Card__. Now you have a visualization that is useful for finding the information you were tasked with finding.

You can change the type of visualization that is rendered with the __Show Me__ menu in the upper right hand corner.  If you click on this menu (if it is not already visibile) you will see a selection of visualizations that are avaliable. The specific visualizations which can be rendered with the data you have dragged into the workspace will be highlighted and the others will be diffused in color. You will also notice at the bottom of the show me menu, there are tips for which data types would be necessary to generate the selected graph. Try changing the data that you have placed in the workspace and look at the different types of graphs avaliable for the different data types. Once you change the visualization, you will need to adjust the display options such as the _Labels_.

## Customizing Your Worksheet
Having a visualization is great, but we want to make it look professional and make it convey the information that is being shared by the visualizations. In order to do this, we will give the worksheet a meaningful title. The default name of the worksheet is the default name of the tab you are working in, but we can customize this. If you right-click or double-click on the title of the visualization, which at the moment should be _Sheet1_, you will be able to change it. In the dialogue box that appears, you can see that the name of the worksheet is forced as the _&lt;Sheet Name&gt;_. You can change the name by simply replacing this function with the desired title text.  You can also add color, and change the size and font. Name it what you like, make any color or font changes, and click _apply_ and _OK_ to save the changes. You can also add a boarder and shading if you _right-click_ the title and select the _Format Title..._ option. This will allow you to make the worksheet more eye appealing.

## Publishing
Now that you have a basic visualization, you will want to share it with your stakeholders so they can see the work you have done. To do this, simply click on the _save_ icon in the top tool bar and follow the prompts. If you have not connected your Tableau Public account yet, you will be prompted to sign in. After authentication, you will be prompted for a name for the workbook, and once you enter a name, your workbook will be saved and uploaded to Tableau Public for sharing.

## Summary
Great!! In this lesson you were able to load a dataset, create a basic visualization, and do a little customization to refine your visualization. You finished the lesson by publishing the worksheet to Tableau Public for your first shared worksheet! In the coming lessons we will dive deeper into the more advanced features that Tableau has to offer.
