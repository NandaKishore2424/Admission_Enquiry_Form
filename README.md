# Admission_Enquiry_Form
## Nanda Kishore R - 212222060157
## Date: 07-07-2025

### See here - https://nandakishore2424.github.io/Admission_Enquiry_Form/
## Objective:
To design a simple Admission Enquiry Form using basic HTML that collects student details such as name, contact, program of interest, and a message for further communication.

## Tasks:
#### 1. Set Up the HTML Structure:
Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document structure.
Set the ```<title>``` as "Admission Enquiry Form".

#### 2. Add a Page Heading:
Use ```<h1>``` to title the page as “Admission Enquiry”.

#### 3. Create the Form Layout:
Use the ```<form>``` tag to wrap all input elements. Set method="post" for structure.

#### 4. Add Input Fields:
Include the following fields using appropriate HTML elements:

Full Name

Email Address

Phone Number 

Program of Interest 

Message

#### 5. Add Submit and Reset Buttons:
Use submit and reset at the bottom of the form.

#### 6. Use HTML-only:
No CSS or JavaScript is to be included. Focus on structure and accessibility.

## HTML Code:

```
<!DOCTYPE html>
<html>
<head>
    <title>College Admission Form</title>
</head>
<body>
    <h1>Admission Enquiry Form</h1>
    <h2>Saveetha Engineering College</h2>
    
    <form>
        Full Name: <input type="text" name="name"><br>
        Email: <input type="email" name="email"><br>
        Phone Number: <input type="number" name="phone"><br>
        
        Gender: <input type="radio" name="gender" value="male"> Male <input type="radio" name="gender" value="female"> Female<br>
        
        Date of Birth: <input type="date" name="birthday"><br>
        
        Department <select name="dept">
            <option>Computer Science</option>
            <option>Electronics</option>
            <option>Mechanical</option>
            <option>Civil Engineering</option>
            <option>Biotechnology</option>
        </select><br>
        Academic Qualification: <textarea name="education" rows="3" cols="30"></textarea><br>
        Your Address: <textarea name="address" rows="4" cols="30"></textarea><br>
        Preferred Mode of Contact <input type="checkbox" name="contact" value="email"> Email me <input type="checkbox" name="contact" value="phone"> Call me<br>
        <button type="submit">Submit Form</button>
    </form>
</body>
</html>

```


## Output:


![image](https://github.com/user-attachments/assets/fbe81083-6cd5-4dd8-ae60-d3a97d816e4a)


## Result:
An Admission Enquiry Form using HTML that collects student details and message for institutional follow-up is successfully created using semantic and readable HTML.
