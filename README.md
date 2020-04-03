# Assignment #4 - Edit step 2: displaying search results

In this step we want to display the address search result from step 1. We will display a Google Maps image of the address we searched for, as well as some information about how suitable the roof is for solar panels. 

#### Edit step 2: displaying search results

1. In the prototype we would like to display the search results in a horizontal layout. Go to the controls section and search for Horizontal Box. You can read more about what the control does by hovering over it in the control menu.

![Assignment4](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/Hbox%20Search.jpg)

2. Drag & drop the Horizontal Box onto the UI editor or the Outline.

![Assignment4 Hbox](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/DragHBox.jpg)

3. Now we have that in place we can delete it's children because we won't be needing them. You can select multiple controls, but you can only delete them one by one.

![Assignment4 DeleteHboxChildren](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/DeleteHboxChildren.jpg)

4. Next lets add some new controls. In the Horizontal Box properties section expand the Content line, select a Formatted Text control and press the ADD button. Repeat the same steps to also add an Image control.

![Assignment4 HBoxChildren](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/AddChildrenToHbox.png)

5. Since we are still editing our Horizontal Box properties, lets go ahead and change its Item Alignment property to Center, its Justify Content property to SpaceAround and its Margins to Medium. This will much like the property names suggest align the children/items to the Horizontal Box's center, space them around evenly and add a medium sized margin.

![Assignment4 HBox Properties](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/ChangeHboxProperties.png)

6. Now lets edit the Formatted Text control in our Horizontal Box. This Text will display our results form our search in step 1. Select the Text control in the UI Editor or the Outline. Then in it's Text property lets paste the following HTML:
&lt;ul&gt;&lt;li&gt;3 kWp&lt;/li&gt;&lt;li&gt;10 Panels&lt;/li&gt;&lt;li&gt;3.087 kWh Energy Yield&lt;/li&gt;&lt;li&gt;3.450 Euro Installation Costs&lt;/li&gt;&lt;/ul&gt;

Lets also edit its Margins property to give it a small margin while we are here.

![Assignment4 FormattedText](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/Paste%20Formatted%20Text.jpg)

7. For the Image control lets go ahead and prepare an image we want to display in our prototype. Click the following link: [Image](https://raw.githubusercontent.com/Innov8ion-developer/SAP_Build_Assignments/master/img/Boteyken%20323.jpg), then right click and save the image to your desktop or somewhere you can easily find it.

Next lets head on over to the Images tab in Build. Then locate your Boteyken 323.jpg and upload it.

![Assignment4 UploadFiles](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/ImagesTab.jpg)

8. Select the Image Control and navigate to the Library button in the properties section.

![Assignment4 ImgLib](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/LibraryImage.jpg)

Here we can select our freshly uploaded Boteyken 323.jpg

![Assignment4 SelectImg](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/SelectImage.jpg)

Great there is an image of our roof. Now lets edit the image size to about 290px (leave the lock icon locked to keep the image scaling correct)

![Assignment4 EditImgSize](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/EditImgSize.jpg)

Also while we are in the Image control properties lets also edit its Margins property to give it a small margin.

![Assignment4 EditImgMargins](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/Edit%20Image%20Margins.png)

# Continue to assignment #5
[Assignment 5](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/5_Edit_Step_3/README.md)

