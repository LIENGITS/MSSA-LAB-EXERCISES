Project Use Cases
LIEN ZHANG
Use Case 1

    Name: Create Account

    Actors: Business Owner
    Precondition: Business Owner exists, application exists

    Triggers: User wants to create invoices for clients using a mobile application

Good Flow:

    User downloads application
    User enters valid login data
    User has created an account

Alternate Flow:

    User enters a username that is already taken
    User enters an invalid password
    User makes a typo

Use Case 2

    Name: Edit Account Info

    Actors: Application users/ database

    Precondition: User wants to edit/ update account info

    Triggers: User realizes they entered information incorrectly. User wants to update info.

Good Flow:

    User goes to the edit account tab on the application home page
    User makes necessary changes
    Changes are noted and updated in the database

Alternate Flow:

    User enters an invalid email address
    User enters an invalid territory in the United States
    Data is not updated on the database

