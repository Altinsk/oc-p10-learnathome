# projet P10 - Parcours Front-end

- [Kanban](https://github.com/users/Altinsk/projects/1)


|As a [type of user]|I want to [perform some task]|So that I can [acheive a result]|
|:---|:---|:---|
|Student or Tutor| I want to connect to my account or create a new user account| 1- On the connection page a form will be be showing where I can enter my email and password and click connect to go to my account or click on create new account to create a new user account <br /> 2- If I am new user I will fill in a form with my email, password and username|
|Student or Tutor| I want to create a new account| 1- I fill in the information requested in the form (email, password, user name)<br /> 2- I click on create new user, the form information is will be verified (valide email and doesn't exist in the database) (password is at least 8 characters containing 1 uppercase character, 1 lowercase character, 1 special character) (the password and confrimation passwords matches)<br /> 3- If there is an error filling in the form then send an error and focus on the wrong locations<br /> 4- if the form is valide then show and confirmation message that the user account is created and send the user to their DashBoard page|
|Student or Tutor| I want to connect to my account| 1- I fill in the information requested in the form (email, password)<br /> 2- I click on connect, the form information is will be verified (valide email found in the database) (password is correct and matching the password in the database)<br /> 3- If there is an error filling in the form then send an error and focus on the wrong locations<br /> 4- if the form is valide  send the user to their DashBoard page|
|Student or Tutor| I forgot my password| 1- I fill in the information requested in the form (email)<br /> 2- I click on send me a link by mail, the form information is will be verified (valide email found in the database)<br /> 3- If there is an error filling in the form then send an error and focus on the wrong locations<br /> 4- if the form is valide the user will receive a link by mail to access a new password form<br /> 5- The user will put a new password and confirm the new password<br /> 6- A verification will be done on the new password that it was not an old password used before by the user, new password is at least 8 characters containing 1 uppercase character, 1 lowercase character, 1 special character, the new password and the confirmation one are matching<br /> 7- The user's data is retreived from the database 8- the user is sent the DashBoard page with all his data|
|Student or Tutor| I am connected to DashBoard page| 1- I will find link to my messages page with a number of not read messages highlighted<br /> 2- Show my To-Do list in the week<br /> 3- Show my calendar events in this week<br /> 4- Can navigate to any pages (Messages, To-Do and Calendar)|
|Student or Tutor| I am connected to Messages page| 1- I can show existing conversation<br /> 2- I can reply to an existing conversation<br /> 3- I can consult my contacts in my contact list<br /> 4- I can add a new contact to my contact list<br /> 5- I can remove an existing contact<br /> 6- I can remove an existing conversation<br /> 7- I can create a new conversation by adding an existing or new contact, write my message and send it|
|Student or Tutor| I am connected to To-Do page| 1- I can show my To-Do list by date<br /> 2- I can modify an existing task (Name, Date, Tag or Category)<br /> 3- I can Create a new task filling in Name, Tage, Category and Date<br /> 4- Verification is done if there is an error a error message will show and focus no locations<br /> 5- If the data is valid the task is created |
|Student or Tutor| I am connected to Calendar page| 1- I can show my events list by date<br /> 2- I can modify an existing event (Name, Date, Tag or Category)<br /> 3- I can Create a new event filling in Name, Tage, Category and Date<br /> 4- Verification is done if there is an error a error message will show and focus no locations<br /> 5- If the data is valid the event is created |

