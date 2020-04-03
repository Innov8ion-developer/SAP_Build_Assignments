# Assignment #3 - Add controls to wizard step 1
With an empty wizard template to start with, you will be adding controls for wizard step 1 in this assignment.

#### Add controls to wizard step 1

1. Add new control

   In the controls section, search for the Form control and drag it in the UI editor.

![Add new content](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep1.png)

2. Delete one Title and two Form Rows from Form control

   The "Form" control has its own title. We don’t need two titles so lets remove the "Title Form Title" from the Form control.

![Delete form title](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep2.png)

   We also won't be needing the bottom two Form Rows so lets delete those as well.

![Delete form rows](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep3.png)

3. Change the labels

   Now lets change the labels of the remaining two Form Rows to "Zip Code" and "House Number". You can do this in the properties section or by double clicking on the label in the UI editor.

![Edit labels](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep4.png)

4. Swap out the dropdown list for an input field

   As you can see, there is now have an input field on the first Form Row and a dropdown list on the second Form Row. We have to change out the Dropdown List in the second Form Row for another Input field. Go into the outline or UI editor and delete the Dropdown List control. Then head back over to the control section and replace it with a new Input control. You will probably notice that it is much easier to drag & drop the input field onto the outline than it is to drag & drop it onto the canvas.

![Add input field](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep5.png)

5. Change width of input fields

   Great, we have our two input fields in place now. They are just a bit too wide. Lets go to their properties and adjust the first input field to 20%, and the second input field to 10%.

![Change input field width](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep6.png)

6. Change values of input fields

   Since we are making a prototype, we will have to hard code some values in order to make our prototype appear like it works! You can do this by selecting the input fields either in the UI editor or Outline. Then navigate to it's properties and enter a Zip Code (3454 PE) and House Number (323) in the Value fields.

![Edit Values](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep7.png)

7. Result

   You should end up with a finished first wizard step after this assignment. It should look similar to the results below.
   
![Result](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/master/img/addControlsToFirstStep8.png)

# Continue to assignment #4
[Assignment 4](https://github.com/Innov8ion-developer/SAP_Build_Assignments/blob/3_Edit_the_template_step2/README.md)
