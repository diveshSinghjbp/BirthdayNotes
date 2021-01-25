# BirthdayNotes 

This code  will allow you to store friend names with DOB. So that we can get notifications and add to the calendar as well.

CRUD Funtionlity with frined List:

1. We can add frined notes
2. we can popuplate those names in the list
3. We can delete those name from the list by right swipe as table has default UI for delete.
4. we can select any existing frind name and can update.

Notification:
We used local notification to check the name of birtday guys


Sync with calendar
When we save or update, it will add into calendar. that you can check with default calendar iOS app.



We Used MVVM Design Pattern to make this application so that we can write modular code.

This app supports both mode landscape and portrait.

Assumtion:
1. Date of birth will sync to the calendar using EventKit.
2. Local notification will fire on the day at 10am. (10am is fixed for the notification) we can change the time for fire notification.
3. Budge number will show on the icon.

Notes : App name is not appropriate with the functionality of the application. I made it due to some restrictions.







