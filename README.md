# Employee-Review-System
A full stack, app used for reviewing employee.
Hoisted Link : 


### Description

A full stack app, in which the admin, can assign the employees, to review each other on the basic of there work. The admin has special power, to make any other employee
as the new admin. Admin can also make the new employee, and they can also assing, the reviewer and revieweee. The admin can see the current employee, and according to the
review, the admin can remove the employee. The review given to the employee, is always going to be store in the database.


### Tech Stack

Node , Express, Mongodb , EJS , javaScript , html, css

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````

#### If you want to make an employee as admin then use the secret key : priya.

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;
  
  
  # HomePage / Admin View
  
  ![admin](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/c3271826-93ee-4caf-a486-3b51010cb290)

  # Home page / Employee view
  
  ![employee](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/19cb1d0d-a705-444c-a90d-f6201ce495b8)

  # Sign-Up
![sign-up](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/1e26a02b-cc6d-46ec-a0b2-87c6d7685b65)


  # Sign-In
  
![sign-in](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/c6fea3ad-20eb-48db-b6e6-3407a67458ad)

  # Forget Password
  
  ![forget-password](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/d2964f76-05eb-4512-bbe6-8233fe844fb5)

  # Assign Task
  
![assign-work](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/de8418fc-9f3f-425c-9065-4e3f2bcc2a09)

  # Employee List


  ![employee-list](https://github.com/priyaakumari/employeeReviewSystemPro/assets/46952823/9742ef7c-5b12-43ef-a834-7600a212b1ff)


### Folder Structure

```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
