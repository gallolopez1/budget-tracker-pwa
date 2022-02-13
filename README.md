# Challenge 19: Progressive Web Applications (PWA) - Budget Tracker

## Activity Instructions:

Update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online.

## Links

* 🌎 [Heroku](https://sleepy-citadel-98771.herokuapp.com/)
* 💾 [Repo](https://github.com/gallolopez1/budget-tracker-pwa)

## User Story

```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

## Acceptance Criteria

```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```
## References:
https://nodejs.org/api/fs.html

https://www.npmjs.com/package/express

https://www.npmjs.com/package/mongoose

https://www.mongodb.com/
