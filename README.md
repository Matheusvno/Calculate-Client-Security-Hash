# Calculate Client Security Hash

Calculate Client Security Hash Dispacher and Performer for UiPath Course.

Steps performed by the Robot:

<ol>
<li>
Open the ACME System 1 Web Application.
</li>
<li>
Log in to System 1. Required input data: email and password.<br>
</li>
<li>
Access the Dashboard - the central location, where the user can pick a specific menu item.<br>
</li>
<li>
Access the Work Items listing to view all the available tasks to be performed (Output data: Work Items).<br>
</li>
<li>
For each activity of the WI5 type, perform the following steps:
</li>
</ol>
  <ul>
  <li>
  Open the Details page of the selected activity to retrieve the Client Information Details.
  </li>
  <li>
  Open the SHA1 Online webpage - http://www.sha1-online.com/, and provide the following input: [ClientID]-
  [ClientName]-[ClientCountry]. Replace all the variables with the corresponding values. Use dashes between items, 
  as shown above.
  </li>
  <li>
  Retrieve the Client Security Hash value from the webpage.
  </li>
  <li>
  Go back to Work Item Details and open Update Work Item.
  </li>
  <li>
  Set the status to “Completed”. Add a comment with the obtained [SecurityHash].
  </li><br>
  </ul>
 <ol>
