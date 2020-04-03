# Assignment #5 - Edit wizard step 3
In wizard step 3, the user should be able to select the type of solar panel he wants to order. He should be able to do this by selecting the solar panel of his choice from a table. The data to populate this table is supplied as an excel file in this assignment. The Build tool allows you to upload this excel file and use it as a data source for a table.

#### Edit wizard step 3
1. Search for the Table control in the controls section. Drag & drop it onto wizard step 3.

![Add Table control](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addSolarPanelsTable1.png)

2. Select the table (highlighted in green) on the canvas by clicking on it. Change the Mode property of the table to "Single Select Left" in the properties section. This will change the behaviour of selecting an item in the table.

![Change Table mode](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addSolarPanelsTable2.png)

3. Select the table (highlighted in green) on the canvas by clicking on it. Add a column to the table by scrolling down in the properties section. At the Children part, expand the Columns entry and press the ADD button.

![Add a column](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addSolarPanelsTable3.png)

4. Select a cell of the column you just added. In the properties section, expand the Content line. In the dropdown menu, search for Text and press the ADD button.

![Add cell content](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addSolarPanelsTable5.png)

5. Change the column headers to "Brand", "Type", "Capacity" and "Price" by selecting them on the canvas and editing the fields.

![Change column header](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addSolarPanelsTable4.png)

6. Now we want to show some solar panel data in this table. To do so we can import data from an excel file. You can download the SolarPanels.xlsx [here](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/data/SolarPanels.xlsx). In Build head on over to the Data tab and click on import a file. Select the SolarPanels.xlsx you just downloaded:

![Import Data](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/ImportData.jpg)

7. As you can see it imported data with a default name: "Table1". Lets edit the name by clicking on the Data Editor button:

![Data Editor](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/DataEditor.jpg)

In the Data Editor you can browse and edit your data's properties. You can also create and graphically view relations but that's not the focus of this tutorial. For now we are just interested in changing our data name from Table1 to SolarPanels:

![Change Name](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/ChangeDataName.png)

8. Now head back using the button in the left upper corner. Now we can select our Table control and in its properties we can select our freshly imported SolarPanels data:

![ChangeTableData](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/ChangeTableData.jpg)

# Continue to assignment #6
[Assignment 6](https://github.com/Innov8ion-developer/SAP_Build_Assignmentss/tree/3_)

