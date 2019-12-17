
# CSCI 4800 Web Application Devlopment Assignment 2
## This is the first step toward designing a Mini Twitter Website.
In this assignment, we learn to design the UI page for a sign-up form

### Our goal is to
#### (I) design UI interface of Sign-up page of our MiniTwitter Project
#### (II) add necessary Javascript validation functions

Our objective is to practice the following concepts:
HTML5, CSS3, Javascript
This assignment includes 11 Steps.

#### Step 0: Create Project
Create a new Web App Project in NetBeans
Call it MiniTwitter

#### Step 1: UI Design
##### Add a sign-up form to index.html 
Hint: method=get, action = registration
##### All fields have labels: <label …></label>
##### Fields
Fullname: required
Username: required
Email: Required, Hint: use “email” type
Password: Required, Hint: use “password” type
Confirm Password: Required
Date-of-birth: Required, Hint: use “date” type
Security question: Required
A combo box with three different questions: Your first pet, your first car, your first school
Input for security question response
Submit button
##### Use HTML5 + Div tags (along with float and clear properties) to set the layout of your webpage

##### Step 1: Adding Error Div 
###### Add a error div to the top of the form
Hint:
```html
<form ….>
<div id=“errorMessage” class=“notVisible”></div>
….
</form>
```
Hint: In main.css define class “notVisible” with the following attribute:
Display: none;

#### Step 1: Adding Error Spans
Add error spans for all inputs
Hint: add a 
```html
<span id=“<inputid>_error” class=“notVisible”> *</span> 
```
at the right side of all inputs
All error spans must be hidden at first.
Hint: Class=‘notVisible’

#### Step 1: Adding Input Validation Function to Form
##### Add a “onsubmit” event to the form
Onsubmit = “return validateForm()”
This function will be implemented in this project.	
