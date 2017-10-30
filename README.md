# Node Contact Form
Contact form build with UIkit and Nodemailer

### Installation
Install the dependencies and start the server.
```
$ git clone https://github.com/rezkyfm/nodejs-contact-form.git
$ cd nodejs-contact-form
$ npm install && npm start
```

### Configuration
Open config.js
```javascript
/* 
config.js
*/
module.exports = {
  //Theme
  theme: "lightBlue",

  //Email Account
  host: "smtp.mailtrap.io", //Change to your email smtp
  port: "465", //Change to your email port
  user: "user", //Change to your email username
  pass: "password", //Change to your email password

  //Email Message
  from: '"Contact Me" <noreply@example.com>', // Sender address
  to: 'youremail@example.com', // List of receivers
  subject: 'Contact Us', // Subject
};
```
### Screenshot
[![N|Solid](https://rezkyfm.com/images/portofolios/nodejs-contact-form.png)](https://github.com/rezkyfm/nodejs-contact-form)
