# formio
You can read the user Manual [FormIO Manual.docx](https://github.com/ahmadzia307-dev/formio/files/11981588/FormIO.Manual.docx)


E Forms Manual
Create E Form

Step - 1:
Click on the ‘Create a new Form’ on the top right corner of home page (Super Admin). You’ll be taken to the Form builder screen.

Creating new E-forms:
To add form elements, simply drag them from the left-hand panel and drop them onto the canvas. You can choose from a variety of form elements, including text fields, checkboxes, radio buttons, and more.
For this example, we'll create a simple form with three fields: "Name", "Email", and "Message". To do this, drag a "Text Field" element onto the canvas and enter "Name" as the label. Repeat this process for the "Email" and "Message" fields.
Example screenshots:

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/cd1b85aa-b777-4d4e-abd8-d9947caca621)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/abbc890e-243c-42e3-9e55-17ab8d9d7671)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/09aea357-1638-4e4f-bca9-d4e9fbce00ed)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/fe71684e-3614-4f76-be61-2c0cbae74522)


Customize Form Elements:
Once you've added your form elements, you can customize them to suit your needs. For example, you can change the label text, add placeholder text, or set validation rules.
To customize a form element, simply click on it to select it, and then use the options panel on the right-hand side of the screen to make changes. For example, you might want to set the "Email" field to require a valid email address by selecting the "Validation" tab and checking the "Email" checkbox.
Example screenshots:

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/c865479d-71a3-47f3-a6e3-8a91099c9bd2)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/585268a7-3319-442b-bfe2-2a47c81e68ff)


Basic components:
Text field:
A Text Field can be used for short and general text input. There are options to define input masks and validations.

Text Area:
A Text Area is a multi-line input field that allows for longer text.
Number:
Use a Number field whenever a field should be limited to a number value type. There are options to set thousands of separators, decimal places, and decimal requirements.
Password:
The password field has the same options as a text field component. It differs from a text field in that its HTML <input> type will be password instead of text. This will cause the field to display hidden input symbols instead of the entered value.

Checkbox:
A check box can be used for Boolean value input field. It can either be checked (true) or unchecked (false). 
Select Box:
This multi-valued component allows users to select one or more options in checkbox style format. Set your values within the Data tab of the settings. Apply unique settings such as value shortcuts and min/max value validation.

Select: 
The Select component displays a list of values in a dropdown list where users can select one of the values. This component has flexibility on where the data source originates from. There is also a large offering of settings providing different ways of filtering, querying, and loading data values. 

Radio: 
The radio component is a field that allows users to select a single option from a list of options displayed in radio-style format.

Button:
Buttons can be added to perform various actions within the form. The most obvious function of the Button component is the Submission action. However, you can also utilize the Button component to trigger events associated with workflow logic, reset field data, authenticate to an OAuth provider, and more. 

Advanced Component:
Email:
The Email component is a string field that carries special input validation ensuring the entered data is in a valid email format. A valid email address consists of an email prefix and an email domain, both in acceptable formats. 

Phone Number:
The Phone Number field carries an input mask to force the user to enter the field data in Phone Number format.

Date & Time:
The Date/Time component is a powerful and flexible component that offers many options for validation and date ranges.

Day:
The Day component is used to enter values for the Day, Month, and Year using a number or select type of field.

Time:
A stand-alone time field for manual input or a time selector widget. 

Currency:
Use the Currency component when a field should display currency amounts on the field. This component holds a numeric input mask that allows two decimal values and automatically adds commas as a user inputs a currency amount. The type of currency can also be selected which will change the prefix currency symbol.

Signature:
This is used to draw signature on signature canvas and will be saved as Image.

Layout Components:

HTML Element:
An HTML Element component may be added to a form to display a single HTML Element. This is useful if you wish to quickly insert and configure some HTML in your form.

Content:
Its just like rich text editor where you can add text/paragraph and style it.

Columns:
This component can be used for grouping other components, like Text Field, Text Area, Checkbox etc., into configurable columns. Use Columns if you want to display more than one component in one line or to save vertical space on your form. 

Field Set:
A Field Set can be used to create a title for an area of the form or grouping of components. This is useful to put inside Layout components or in between lots of related components. 

Panel:
A Panel is used to wrap groups of fields with a title and styling. Use the Panel to organize your components and create a more appealing UI.

Table:
Create a Table with columns and rows that allow adding additional components within it.

Data:
Container:
A Container is a wrapper around a set of fields, similar to a Field Set. What makes the Container unique is the way the data is stored. The fields inside the Container are put into an object with the container key. This is useful for creating more complex objects and data sets within your form.

Data Grid:
Data Grids allow users to add a grouping of components on a line item grid. Users can then add multiple rows of the component grouping inside the Data Grid. Additionally, any number of grids can be added within a form, which is especially useful when needing the ability to add or duplicate multiple fieldsets.

Custom components:
Human skeleton:
This is a custom component which is designed to mark the injuries of human body parts.



Examples:
1-In Below image, I’m creating a container which can hold/group different field

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/d3a92c11-82f6-4f18-ae1b-6b8528997cc4)

2-Text Field:
You can customize label by adding Label title, position and placeholder text, you can also disable or hide the component, There’s an option “Is Enable for Admin”, If its checked then only admin can edit this field.
There’re also many validations which include the min/max length, make the field required or optional, Show label title when there’s some error. 
![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/d644ff36-ab08-42fd-ab2a-2921a09a0030)

3- You can add the default values of fields. Field text case can also be selected.
e.g. Selecting upper case will convert the value in uppercase
![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/807fbdac-0445-4cee-82d1-fc5914f3101f)

4-You can Preview the form by selecting Preview option on bottom right corner

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/d0d89c17-3373-4d5a-a595-9a3a0a131202)

5-This is the output of preview.

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/2cff8fe6-758c-42c7-bb1b-d0cd102f7074)

6-You can add Select/Dropdown menu and its values can be added in advanced tab as shown below.

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/9a1d5bf2-898b-46b9-b172-025fa2928527)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/2abe3a97-040e-481e-a922-c01b0f6b76bd)

7-Custom CSS classes can also be added to containers like shown in below example.
![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/51c79c86-db45-488f-9bdb-117d8d9dda6d)

8-URL can also be used as data source which will show the response data.

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/bc46cbfd-60ef-4c54-8223-dfe81a190c85)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/2fe0ed20-f2dc-4234-ade2-f79beef683ba)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/afbaa4f1-6459-42cf-8281-c5edcf79adf9)

9-Here I’m doing custom calculations to evaluate the results of fields.

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/64ba5dae-58bf-4f5a-8d66-14fa43d29bd1)

10-Custom validations can also be added. Here I’ve added a regular expression to validate email.

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/7330fb50-993f-45a7-a840-f3c0eaaed7fc)

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/5d873570-a1b2-4e5a-9a18-c7a3dd3230d9)

11-Using data grid we can add fields dynamically on the run as shown in below image.

![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/df8bb09e-5e20-409b-a626-64c43efbd2fc)

12- At the end after creating the form we will save it for further operations.
![image](https://github.com/ahmadzia307-dev/formio/assets/78743784/3a05b835-38fe-4101-802d-1c4b26c2cebe)

Conclusion: 
Using Form.Io’s drag-and-drop form builder, you can quickly and easily create custom forms without any coding.
