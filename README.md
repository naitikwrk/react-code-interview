# React Code Interview

Please go through all the instructions carefully before beginning to write code.

## Some pointers

1) You will be given 45 minutes to complete the code exercise. There are no marks/points system for this code exercise. Do not worry if you are unable to implement all the features. If you get stuck at any point, move on to another feature. Your code evaluation will have more weightage on how well you write your code and your understanding of React and Javascript concepts.

2) You are free to use google, stackoverflow, etc. anytime to look up ideas/solutions.

3) You are free to use any 3rd party npm package/library for the implementation.

## Environment setup

Open below link in your browser (**Do not use incognito** mode as it does not seem to work). This will setup your React coding environment.

[https://stackblitz.com/fork/react](https://stackblitz.com/fork/react)

## Implementation

Below are the features to be implemented. Feel free to switch between features if you get stuck.

#### 1) Render user table
Make an api call to [https://jsonplaceholder.typicode.com/users](https://jsonplaceholder.typicode.com/users) which will return a list of users. Display **Name**, **Email**, and **Phone** details of all users in a table. The columns should be configured in a manner where it is possible to add or remove columns without having to update the html code.

#### 2) Add a user
Create 3 text inputs respectively for **Name**, **Email**, and **Phone**, and an **Add** button. Clicking the Add button should insert a new row with the user details and also all input fields should be reset. The Add button should be disabled by default and it should only be enabled when the below criteria are met:

- Name: Only alphabets (uppercase or lowercase) and space allowed.
- Email: Only email ids ending with @gmail.com allowed.
- Phone: Only 10 digit numeric value allowed.

#### 3) Delete a user
Render a **Delete** button in every row. On clicking the Delete button, it should remove that user row from the table.

#### 4) Display last modified timestamp
Display a timestamp below the table which indicates when the table was last modified i.e. when a user is added or deleted. Default value should be set to "Never".

## Example

<img src="assets/react-code-interview-sample.gif" width="560">
