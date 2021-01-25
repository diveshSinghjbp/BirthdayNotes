# BirthdayNotes 

This code  will allow you to store friend names with DOB. So that we can get notifications and add to the calendar as well.

CRUD Functionality with friend List:

1. We can add friend notes
2. we can populate those names in the list.
3. We can delete those names from the list by right swipe as the table has a default UI for delete.
4. We can select any existing frind name and can update.

Notification:

1. We used local notification to check the name of birthday guys

2. Sync with the calendar When we save or update, it will add into the calendar. that you can check with the default calendar iOS app.


We Used MVVM Design Pattern to make this application so that we can write modular code.This app supports both mode landscape and portrait.

Assumtion:

1. Date of birth will sync to the calendar using EventKit.
2. Local notification will fire on the day at 10am. (10am is fixed for the notification) we can change the time for fire notification.
3. The Budge number will show on the icon.

Notes : App name is not appropriate with the functionality of the application. I made it due to some restrictions.
