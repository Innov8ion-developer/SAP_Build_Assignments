# Assignment #4 - Edit the prototype step 2

In this step we want to display the search result from step 1. We will display an image of the address we searched for, as well as some information about how suitable our address is for solar panels. In our prototype we would like to display that horizontally so lets navigate to the controls menu and search for: "horizontal box". You can read more about what the control does by hovering over it in the control menu.
![Step 2 Delete](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/Horizontalbox.jpg)


Then you can drag the Horizontal Box into the UI editor or the Outline:
![Step 2 Delete In Properties](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/Drag%20Horizontal%20Box.jpg)

Great, now we have that in place we can delete it's children because we won't be needing them. You can select multiple controls, but you can only delete them one by one.:
![Step 2 Edit Wizard Step Title]()

Next lets add some new controls. In the Horizontal Box properties bottom right of the screen select a Formatted Text control and press the add button. Repeat these steps for an Image control:
![Assignment4 HBoxChildren]()

Now since we are still editing our Horizontal Box properties, lets go ahead and change its Item Alignment property to Center, its Justify Content property to SpaceAround and its Margins to Medium. This will much like the property names suggest align the children/items to the Horizontal Box's center, space them around evenly and add a medium sized margin.
![Assignment4 HBox Properties]()



Now lets edit the Formatted Text control in our Horizontal Box. This Text will display our results form our search in step 1. Select the Text control in the UI Editor or the Outline. Then in it's Text property lets paste the following HTML:
<ul><li>3 kWp</li><li>10 Panels</li><li>3.087 kWh Energy Yield</li><li>3.450 Euro Installation Costs</li></ul>

Great, now for our Image control lets go ahead and prepare an image we want to display in our prototype. Click the following link, then rightclick and save the image to your desktop or somewhere you can easily find it:
[Image]()

Next lets head on over to the Images tab in Build. Then locate your Boteyken 323.jpg and upload it.
![Assignment4 UploadFiles]()

Then we can select our Image Control and navigate to the Library button in its properties:
![Assignment4 ImgLib]()

Here we can select our freshly uploaded Boteyken 323.jpg:
![Assignment4 SelectImg](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/SelectImage.jpg)



# Continue to step #5
[Step 3](https://github.com/Innov8ion-developer/SAP_Build_Assignmentss/tree/3_)

