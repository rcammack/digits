<img src="doc/landing.png">
 
Digits is an application that allows users to: 
<ul>
<li>Register an account</li>
<li>Create and manage a set of contacts</li>
<li>Add timestamped notes regarding their interactions with each contact</li>
</ul>

<h2>Installation</h2>

In order to install this application, follow these steps:
<ol>
<li><a href="https://www.meteor.com/install">Install Meteor</a></li>
<li>Request permission from the author to gain access to the Digits repo (Digits is a private repo)</li>
<li>Download a copy of Digits</li>
<li>cd into the app directory within digits</li>
<li>Run the following commands:
<ul>
  <li>$ meteor npm install</li>
  <li>$ meteor npm run start</li>
</ul>
Note that the first time you run the app, it will create some default users and data. 
Also, you can ignore any bycrypt warning.  
</li>
<li>Open a new tab in a browser window and navigate to <a href="http://localhost:3000">http://localhost:3000</a></li>
<li>Login to an account using the credentials in settings.development.json, or register a new account</li>
<li>Lastly, you can run ESLint over the code in the imports/ directory with the command: meteor npm run lint</li>
</ol>

<h2>Digits Walkthrough</h2>

<h3>Landing Page</h3>

When starting your application, you will see the landing page which provides an overview of the capabilities of Digits.

<img src="doc/landing.png">

<h3>Register</h3>

You can register a new account by clicking on “Login” then “Sign Up”.

<img src="doc/register.png">

<h3>Sign in</h3>

Or you can sign into an existing account by clicking on "Login" then "Sign in".

<img src="doc/signin.png">

<h3>Home Page</h3>

Once logged in, the system takes you to the user's home page.  This is nearly identical to the landing page, but the NavBar contains links to List Contacts and Add Contact pages.

<img src="doc/userHome.png">

<h3>List Contacts</h3>

Clicking on the List Contacts link in the NavBar will bring up a page that lists all of the contacts associated with the logged in user.

<img src="doc/listContacts.png">

On this page, you can add timestamped notes to any of your contacts.  

<img src="doc/note.png">

<h3>Edit Contact</h3>

From the List Contacts page, you can edit the information associated with a contact by clicking on the “Edit” link for that contact.

<img src="doc/editContact.png">

<h3>Admin User</h3>

Initially, one default admin user is created; however, there can by more than one users with the admin role.  Admin users have access to a special NavBar link "Admin" that retrieves a page listing all contacts associated with all users.  

<img src="doc/admin.png">
