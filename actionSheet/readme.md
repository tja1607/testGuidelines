# ActionSheet

#### CONTENTS

[Go to Real Cool Heading section](#Buttons)
* Usage
* Properties
* Events
* Methods
* CSS Custom Properties

>“Action sheets are used as an overflow menu, and is a specific style of alert
that appears in response to a control or action, and presents a set of two or more choices
 related to the current context.“


An Action Sheet is a dialog that displays a set of options. It appears on top of the app's content, and must be manually dismissed by the user before they can resume interaction with the app. Destructive options are made obvious in ios mode. There are multiple ways to dismiss the action sheet, including tapping the backdrop or hitting the escape key on desktop.

# Buttons
A button's role property can either be destructive or cancel. Buttons without a role property will have the default look for the platform. Buttons with the cancel role will always load as the bottom button, no matter where they are in the array. All other buttons will be displayed in the order they have been added to the buttons array. Note: We recommend that destructive buttons are always the first button in the array, making them the top button. Additionally, if the action sheet is dismissed by tapping the backdrop, then it will fire the handler from the button with the cancel role.






Spec:
- Comes with a backdrop on small screens and loose that after 720dp.
- Comes with a “close” button under the sheet <720dp
- Has same “behavior” as a FabSheet on desktop, it just comes from
 below an action most of the time. 
- Max width of 311dp and until that 32dp margin to the sides