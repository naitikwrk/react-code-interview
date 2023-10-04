# React Code Interview

Please go through all the instructions carefully before beginning to write code.

## Info

- You will be given 45 minutes to complete the code exercise. There are no marks/points system for this code exercise. Do not worry if you are unable to implement all the features. If you get stuck at any point, move on to another feature. Your code evaluation will be largely based on:

  - How well you write your code
  - Your understanding of React and Javascript concepts

- You are free to use google, stackoverflow, etc. anytime to look up ideas/solutions.

- If you prefer to use any 3<sup>rd</sup> party npm package/library to help you with any task, feel free to use them.

## Environment setup

Right click and open below link in new tab (**do not use incognito** mode as it does not seem to work). The below link will set up your React coding environment.

[https://stackblitz.com/fork/react](https://stackblitz.com/fork/react)

## Implementation

Below are the features to be implemented. Feel free to switch between features in case you get stuck anywhere.

#### 1) Render user table
Make an api call to `https://jsonplaceholder.typicode.com/users`, which will return a list of users. Display **Name**, **Email**, and **Phone** details of all users in a table. The columns should be configured in a way that it is possible to add or remove columns without having to update the html layout code.

#### 2) Add a user
Create 3 text inputs for **Name**, **Email**, and **Phone** respectively, and add an `Add` button. Clicking the Add button should insert a new row with the user details and thereafter all input fields should be reset. The Add button should be disabled by default and it should only be enabled when the below criteria are met:

- Name: Only alphabets (uppercase or lowercase) and space allowed.
- Email: Only email ids ending with @gmail.com allowed.
- Phone: Only 10 digit numeric value allowed.

#### 3) Delete a user
Render a `Delete` button in every row. Clicking the Delete button should remove the user row from the table.

#### 4) Display last modified timestamp
Display a timestamp below the table which indicates when the table was last modified i.e. when a user was added or deleted. Default value should be set to "Never".

## Example

<img src="assets/react-code-interview-sample.gif" width="560">
