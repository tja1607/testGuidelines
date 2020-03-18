# Forms
<nav>

* [Design Best Practices](#design-best-practices)
* [Input Container](#input-Container)

</nav>

## Design Best Practices
#### Aim To 
- Prevent the user to make mistakes (Use Input-types, disable inserting characters that are not allowed etc. etc.)
- Keep your submit button disabled until all required fields are filled out - Validate your forms “onPress” even though the button is disabled.
- Give specific feedback, eg. “Skal indeholde 8 tal”
- (If possible) Validate errors in context (inline) as the form is filled out rather than at the end. (Eg. Copy/Pasting an invalid character ends with an inline error)
- Mask the input if possible to make it easier to read and recognize (eg. “24 32 34 42”)
- Order fields from easiest to hardest to fill out.
- Keep your forms to be required most of the time - If you have to have optional fields, be explicit about it (Label - Valgfrit)
- Align the size of a field with how much text the user is expected to enter. 
- Keep the same structure as in real world examples (Make it easy for people to copy/paste) - Eg. Name & Surname should not be separated into 2 fields but be the same 

#### Avoid
- Don’t validate empty fields before submitting the form (eg. Leaving the form without any text on a required field shouldn’t be validated)
- Don’t write the same placeholder text as the label, eg. “Emne & Indtast emne” - If you need to show a hint text make an example (“eg. 12/23/2020”) - Try not to have a placeholder text
- Don’t overuse putting forms side by side - Try to do it only if it supports the normal way you input it.


___
![Icon dont](https://github.com/tja1607/testGuidelines/blob/master/Forms/dont.svg) Don’t overuse putting forms side by sid | ![Icon do](https://github.com/tja1607/testGuidelines/blob/master/Forms/do.svg) Keep the same structure as in real world examples and make it easy for people to copy/paste
-------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------
![Don't do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDont.svg) | ![Pleas do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDo.svg)
 We're living the future so the present is our past                                   | We're living the future so the present is our past

**Don’t overuse putting forms side by side**

![Don't do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDont.svg)

> We're living the future so the present is our past

**Keep the same structure as in real world examples and make it easy for people to copy/paste**

![Pleas do](https://github.com/tja1607/testGuidelines/blob/master/Forms/inputDo.svg)

> We're living the future so

## Input Container

Input Container provides layout and styling of inputs within it as well as styling for:

- the input label
- input description,
- a tag (often used for things like (optional) next to the form label)
- a slot to hold a tooltip or other information pinned to the top right of the container

> ![Pleas do](https://github.com/tja1607/testGuidelines/blob/master/Forms/do.svg) We're living the future so