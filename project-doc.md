# Project Title

## Brief about project
Project brief shouldn't be longer than 150 - 200 words (~ 3 to 4 liners).

## Modules 

### 1. Module 1

#### 1.1 Brief
brief shouldn't be longer than 150 - 200 words (~ 3 to 4 liners).
#### 1.2 UAT 
User Acceptance Test cases 

# Example

# Custom CMS

## Brief
Client want to build a CMS (Content management system) to manage his blogs and want option to have two types of users to restrict permissions. 

## Modules

### 1. Authentication Module

**Brief**
In this module we are going to cover login, forgot password and we will also get checklist for developers.

### 1.1  Login Module
Here we are going to ask username & password form customer and a checkbox option for remember me. After successfully creating this module. This login form should pass following checklist (UAT).

**UAT**
1. If user are entering valid username and password, then system must show "Login successfully" and then redirect to admin panel dashboard"
2. If user is entering invalid username password, then system must show "Wrong username & password".
3. It should be protected with SQL inejection. To check this try following username passwords.
   username - Valid username
   password ' or 1=1'
4. If someone already loggedIn and try to access login page, then they should be automatically redirected to dahsboard.   


### Users Module


### Post Module