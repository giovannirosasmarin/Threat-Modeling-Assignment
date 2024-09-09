# Threat-Modeling-Assignment
Topic-4 assignment

Consider a sample web application that does the following:

Presents the user with a login page (username and password)
Uses an open source component to authenticate the user credentials against a database
If the username and password presented exist in the database, present the user with a message-of-the-day stored in the database
Allow the user to comment on the message-of-the-day (comments will be stored in the database)

Use ThreatDragon to create a threat model of the web application that was just architected:

Authenticate to ThreatDragon through your GitHub account
Select "Create a completely new, empty threat model"
Select the newly created repo
Use the main/master branch as prompted
Title should be "Initial Threat Model"
Owner, Reviewer, and Description fields are optional (using "test" for all values is fine)
Click to add a new diagram titled "Initial Threat Model Diagram"
Create a simple data flow diagram to model the web application, showing boundaries and flows between the user's web browser, the application, and the database
Use the sample threat model, main request data Flow, located in the topic Resources, as an example
Click on an element in the diagram and then click on Edit Threats
Add a new threat using the STRIDE model. Consider all threats open (not mitigated)
![Initial Threat Model Diagram](https://github.com/user-attachments/assets/37c45664-b6ee-460f-b26c-d9e518131bcc)

Write a 750- to 1,000-word overview of the threats identified in the threat model and include a screenshot of the completed data flow diagram. Describe the impact of the open source authentication component toward possible threats. Select one of the threats identified in the model and explain the best choice of action to address the risk from the following:

Do Nothing
Inform
Mitigate
Accept
Transfer
The diagram needs to include elements representing the client, the open source authentication component, the application, and the database. Data flows should be shown to represent the authentication request, message of the day retrieval and display, and comment submission. All of these elements will need to be represented by the store, data flow, process, and actor icons, and a trust boundary should be provided.

Identify 5 threats to the system and describe what could be negatively affected in the system if exploited, referring to the threat type using the STRIDE model. The threats identified should cover at least 4 parts of the STRIDE model, and at least one should involve the open source authentication component.
