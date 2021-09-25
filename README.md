# Salto-Exercise-Lety
This is the repository for documenting the exercise for the Salto recruitment process for the CSM position

This exercise includes the following steps in the Salesforce Development environment:

1. Creation a developer Salesforce account and log in
2. Creation a token in the SF environment by going to Username>Settings>Reset My Security Token, and click on 'Reset My Security Token' button
3. Saving the token where you can then access it
4. Creation of two new queue types via the Setup>Users>Queue and selecting the 'New' button.
- All Hot Leads
- All Cold Leads
5. Creation of a new custon field (type integer) for Queues, named 'Score'. The score is used for assignation rules for assigning the new leads to either the Hot or Cold Leads queue.
6. Creation of a new assignment rule:
- If the score is below 10, the lead is a Cold Lead.
- If the score is 10 or above, the lead is a Hot Lead. The salto workspace is also created, however the fetch instruction is missing a variable
7. Creation of the Salto environment for code control of all the SF changes
8. Addition of the files to git repository (Salto-Exercise-Lety) with a branch for each change
