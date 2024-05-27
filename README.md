# Project README

## Description
This project contains a React Native application with a simple interface displaying a text component. The text component displays the phrase "My name is YourName", where "YourName" is replaced with the user's name Theodore Abbey. Additionally, the background color of the app is customized to the colour light Black.

## Instructions

### Editing App.js
In the `App.js` file in my project, you can make the following changes:

1. **Change the background color of the View component:** Open `App.js` and locate the `container` style within the `styles` constant. Modify the `backgroundColor` property to change the background color of the View component.

2. **Edit the Text component to display "My name is YourName":** Find the `<Text>` component inside the `return` statement of the `App` function. Replace the text within the `<Text>` component with "My name is YourName".

3. **Increase the font size of the text to 24:** In the `styles` constant, locate the `text` style. Modify the `fontSize` property to set the font size to 24.

4. **Make the name "YourName" bold:** Update the text inside the `<Text>` component to include your name and wrap it with a `<Text>` component. Within this nested `<Text>` component, apply the `fontWeight: 'bold'` style to make your name bold.

#### Example
```javascript
<Text style={styles.text}>My name is <Text style={{fontWeight: 'bold'}}>Theodore Abbey</Text></Text>


# User Information

- **Name:** Theodore Abbey
- **ID:** 11343393
