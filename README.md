# Salto-Exercise-Lety

This exercise includes the following steps in the Salesforce Development environment:
1. Creation a developer Salesforce account and log in
2. Creation a token in the SF environment by going to Username>Settings>Reset My Security Token, and click on 'Reset My Security Token' button
3. Saving the token where you can then access it
4. Creation of twon new queue types via the Setup>Users>Queue and selecting the 'New' button.
    - Hot Leads
    - Cold Leads 
 5. Creation of a new custon field (type integer) for Queues, named 'Score'.
    The score is used for assignation rules for assigning the new leads to either the Hot or Cold Leads queue.
 6. Creation of a new assignment rule:
    - If the score is below 10, the lead is a Cold Lead.
    - If the score is 10 or above, the lead is a Hot Lead.
The salto workspace is also created, however the fetch instruction is missing a variable
