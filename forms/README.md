## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
    `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer
1. What is the purpose of the _action_ attribute in the _form_ tag?
The action attribute of the form tag specifies the URL to which the form data will be sent when the form is submitted. This is the script or endpoint on the server that will receive and process the form data.
2. What is the purpose of the _method_ attribute in the _form_ tag?
The method attribute of the form tag determines how the form data is sent to the server. The two most common values are GET and POST. GET appends the form data to the URL, in name/value pairs. POST sends the form data as an HTTP post transaction.
3. What is the purpose of the _name_ attribute in the _input_ tag?
The name attribute in an input tag specifies the name of the input, which is used to reference form data after it's submitted, or to reference the input element in scripts. When the form is submitted, the data sent to the server includes the name of the input and its current value.
4. What is the purpose of the _type_ attrbute in the _input_ tag?
The type attribute in the input tag defines the type of control to display. For example, type="text" displays a single-line text input, type="radio" displays a radio button, and type="submit" displays a button that, when clicked, will submit the form.
5. What is the purpose of the _label_ tag?
The label tag is used to define a label for several form elements (like input, select, textarea). The primary purpose of a label is to improve the user experience by providing additional context for an input field, and by allowing the user to click on the label to focus/select the associated input element.
6. What is the purpose of the _required_ attribute?
The required attribute is a boolean attribute that, when present, indicates that an input field must be filled out before submitting the form. It is used for form validation, ensuring that important fields are not left empty by the user.



