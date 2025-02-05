
# Budget Buddy

Bijou Budget is a simple finance tracking application featuring an intuitive user interface.

Watch a demo here: https://drive.google.com/file/d/1MH4dTxG_pKboG04MVrIlyNr2kw2L3EKm/view?usp=sharing

How to use the app:  
* Register a user via the **`Register`** button (note: usernames and passwords are case sensitive)
* There are 4 main buttons on the homepage
* User may start by using the **`Add Expense`** button to add their monthly expenses  
* User may update the amount spent on any expense by using the **`Add Transaction`** button  
* User may edit an expense name and/or its allocated budget using the **`Edit Expense`** button  
* User may view all their transactions by using the **`Show Transactions`** button
* User may sign out via the **`Sign Out`** button on the top right of the home page  
* Other features include filtering by month, year, and expense for an enhanced user experience





## Installation

To run the front-end, run these commands in the 'react' directory:

```bash
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.5/install.sh | bash
  nvm install 16
  source ~/.bashrc # you may not be using bash, but the goal is to refresh your terminal
  nvm use 16
  npm start
```

To run the back-end, open the 'neobudgettracker' directory:

* Ensure you're using Java 17
* Create yourself database with the information found in `application.properties`
* Run: ```mvn spring-boot:run```
    
