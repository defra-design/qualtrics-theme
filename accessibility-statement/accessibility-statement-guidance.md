# Add an accessibility statement
Each form needs to link to an accessibility statement to comply with the law.
You can use a single statement for a set of forms if:

* they all have the same legal body as owner (eg Environment Agency)
* you are sure that a single statement will be correct for all the forms

Use the Defra Qualtrics accessibility statement HTML template to form the basis of your own statement.

To do this, create a new project.
1. On the ‘Create a project’ screen, select ‘Survey’ to create a new survey from scratch.
2. Name the survey: ‘NAME OF YOUR SERVICE accessibility statement’, replacing the placeholder text with the name of your service or services.
3. Change the default question to be a ‘Text/Graphic’ question type.
4. Select the question to write the question text and then navigate to the ‘HTML view’ that will appear just above the box you have selected.
5. Copy the Qualtrics generic accessibility statement code and paste it into the HTML view.
6. Once pasted, navigate to the ‘Rich Content Editor’ view, again this is situated before the question itself, close to the HTML view.
7. From here, go through the statement and add the details that are relevant to your form. If you are aware of any extra defects in your form, add those. 
8. Go to ‘Look and feel’ and then ‘Style’
9. Add the following code to the ‘Custom CSS’ field.
  a. #NextButton{display:none!important}
10. Select the ‘Apply’ button.

You are legally responsible for the content of the statement. If you are unsure, ask you legal team to check and sign off.

Once complete, select the ‘Publish’ button - located back in the ‘Builder’ view. Be sure to copy the link that Qualtrics provides you with.

Navigate back to the form that you are working on to add your accessibility statement.
1. Go to ‘Look and feel’ and then ‘General’
2. In the text field labelled ‘Footer’, insert the following code
  * `<a href="LINK YOU COPIED EARLIER"  target="_blank">Accessibility Statement (opens in a new tab)</a>`
3. Replace the placeholder text with the link that you copied when publishing the accessibility statement.
4. Select the ‘Apply’ button.