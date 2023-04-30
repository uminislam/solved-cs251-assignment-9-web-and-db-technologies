Download Link: https://assignmentchef.com/product/solved-cs251-assignment-9-web-and-db-technologies
<br>
<strong>                              </strong>

<strong>Q1. </strong>​Create your homepage at ​<u>www.cse.iitk.ac.in</u>




Steps:

<ol>

 <li>Login to turing.cse.iitk.ac.in</li>

 <li>Change directory into /homepages/global/&lt;your cse ldap&gt;/</li>

 <li>Create your homepage Sample page:</li>

</ol>

<u>https://www.cse.iitk.ac.in/users/dhanajit/</u>




<strong>Q2. </strong>​Create an web application to automate the process of registration for an event organized by students of CS251 named as “Lets build stuff!”. You are required to use html, php and SQLite to build the site.




The registration workflow is as follows.




<ol>

 <li>Registration page containing text boxes asking for name, address, email, mobile number, bank account number and bank password and a submit button. You should write javascript to validate the user input as per the following specifications.

  <ol>

   <li>name : Maximum 20 characters with only english alphabets and space</li>

   <li>address: Maximum 100 characters</li>

   <li>email should be of the form “​<u><a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="bdced2d0d8d2d3d8fdc5c4c793ded2d0">[email protected]</a></u><u>​</u>” where leftside may contain english alphabets only and rightside must end with a “.com” domain name</li>

   <li>Mobile number is a 10-digit numeric value</li>

   <li>Bank account number is a 5-digit numeric value</li>

   <li>Bank password can be maximum 20 alphanumeric characters and should not be displayed when entered in the textbox.</li>

  </ol></li>

 <li>Once submitted, you should perform the following checks in a separate php file and display “Registration Successful” only if registration is successful (see the conditions below).

  <ol>

   <li>If the same email already exists in the list of registrations (maintained in SQLite DB) the registration fails with a message “Already registered”.</li>

   <li>You should check the account balance (maintained in a separate table) against the provided input and deduct registration fees (1000) from the account. Display “Insufficient Balance” if the account balance is less than 1000 and “Invalid Account/Password” if the account number and passwords do not match.</li>

  </ol></li>

 <li>In the registration page, a link to “See all registrations” takes the browser to a new page which asks for admin login and password. Once submitted and verified from by queries the “admin” table, all the registrations (so far) should be displayed in a tabular form with all inputs provided in the registration page except for the password.  There should be a link named “Another Registration” for all of the pages except the main registration page.</li>

</ol>

You can get started by installing necessary softwares on your laptop.  If anyone need access to a development setup, do let me know as soon as possible.