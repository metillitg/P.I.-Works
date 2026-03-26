**P.I. Works Technical Questionnaire - Question 5 User Controlling System - Efe Metilli**

**Design Goal**

- Allow client to register new users
- Allow client to enable/disable users
- Allow client to filter the users by ID, User Name, E-Mail or Enabled status
- Allow client to display user data
- Allow client to change the user data

**Scope**

Registering new users

Changing user data

Having a user list

Displaying users by filters

**Design Notes and Functionality**

**Header**

- Background color is light gray(#f5f5f5).
- On the very left side there will be a blue button with '+ New User' written in white, button color is blue(#007cba). When the '+ New User' button is clicked, open a new form as 'New User' in body next to user list.
- Next to '+ New User' button, there will be a check-box for 'Hide Disabled Users' which is not checked as default. Check-box color is blue(#0072ff) when it is clicked with white check mark. When clicked hide the disabled users in user list.
- On the very right side of header, there will be a 'Save User' button. Button's color will be light blue(#56a7cf). If there are no changes in user, it can not be clicked on. It can be clicked after one of the user's data has been changed, and it will update the user's data in the user list. When the button is clickable, color of the button will turn into blue(#007cba).

**Body**

- Background color is white.
- When body is divided from the middle, left side is for user list as table. On top of the list, there are fields. Users are listed as rows.
- Fields in user list will include ID, User Name, Email, Enabled. ID is automatically assigned when the user is created. Enabled status is either true or false. User Name and Email is directly themselves. Field color will be blue(#007cba).
- In each field of the list, field name comes first, up and down arrows comes later and lastly filter button comes. All of these are white.
- Arrows change as you click on them depending the filtering type as A-Z or Z-A or smallest ID - biggest ID etc.
- When filter button is clicked, there can be a pop-up box for filtering.
- In order to have a better view, first row(user)'s background color is white, text is black. Second row's color is light blue(#b9d9e8). Text is black and bold. This goes on like this.
- When a user is clicked, related data is shown in the right side of the body. The data is shown with a list similar to 'New User' form. Instead 'New User', there is 'Display Name' of user. Data can be changed from here and saved with the 'Save' button.
- Fields in New User is respectively Username, Display Name, Phone, Email, User Roles, Enabled as rows.

- Until User Roles, next to fields, there are text boxes.

- In 'User Roles''s text box Select user roles… is written by default. When the text box is clicked, drop-down list appears. Choices are respectively Guest, Admin, SuperAdmin. As default, these choices have white background and black text. When mouse is on one of these choices, background color turns into blue(#428bca) and text turns into white.
- Next to Enabled, there is a check-box. At first it is blank. When it is clicked on, check appears. Colors are the same with 'Hide Disabled User' check-box.
