# Assignment #2 - Edit the prototype
The wizard template that you have selected in assignment #1 is used to guide a user through a serie of steps. In this assignment you will edit the steps of the template. First you will delete some of the template content that is not needed and after that you will add some controls that you do need.

#### Edit the prototype

To start editing the prototype, go to the UI Editor by clicking the Wizard Page.

![Edit wizard page](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype1.png)

1. Delete controls

   In the outline (bottom left corner), select “Wizard Step Product type”. This is the first step on the wizard page. Delete all its children (Message Strip, Text and Horizontal Box). You can do this either on the properties section (right side of the screen) or just remove them directly from the outline by selecting the controls, right clicking and pressing delete.

![Delete children of wizard step](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype2.png)

2. Add new control

   Now that you have an empty wizard step, we can add some new content. In the controls section (upper left corner), search for the “Form” control and either drag it in the UI editor, or you can drag it into the outline.

![Add new content to wizard step](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype3.png)

3. Delete one title and two rows

   We don’t need two titles for this step so lets remove the "Title Form Title" from the Form control. We also won't be needing the bottom two Form Rows so lets delete those as well.

![Delete form title](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype4.png)

![Delete form rows](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype5.png)

4. Change the remaining title

   Change the title of the wizard step to: “Enter your information”. You can again do this by selecting the Wizard Step in the outline and then go to properties of the Wizard Step (right side of the screen) then locate the "Title" input field to edit the title there. Or you can select it in the UI Editor and edit the title there directly.

![Edit title](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype6.png)

5. Change the labels

   Now lets change the labels of the remaining two Form Rows to "Zip Code" and "House Number". Again you can do this in the outline or by double clicking on the label in the UI editor.

![Edit labels](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype7.png)

6. Swap out the dropdown list for an input field

   As you can see, you now have an input field on the first Form Row and a dropdown list on the second Form Row. We have to change out the Dropdown List in the second Form Row for another Input field. Go into the outline or UI editor and delete the Dropdown List control. Then head back over to the control menu and replace it with a new Input control. You will probably notice that it is much easier to drag & drop the input field onto the outline than it is to drag & drop it onto the canvas.

![Add input field](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype8.png)

7. Change width

   Great, we have our two input fields in place now. They are just a bit too wide. Lets go to their properties and adjust the first input field to 20%, and the second input field to 10%.

![Change input field width](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/editThePrototype9.png)

Since we are making a prototype and unfortunately there is no way to use real API's in Build at the moment, we will have to hard code some values in order to make our prototype appear like it works! You can do this by selecting the input fields either in the UI editor or Outline. Then navigate to it's properties and enter an Zip Code and House Number in the Value fields.

![Edit Values](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/Edit%20Input%20Values.png)

# Continue to assignment #3
[Assignment 3](https://github.com/Innov8ion-developer/SAP_Build_Assignmentss/tree/3_)
