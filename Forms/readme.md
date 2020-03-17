# Forms

#### Index

[Design Best Practices](#Design Best Practices)


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