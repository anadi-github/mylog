# Requirements

This app is designed for diabetics to log and review three main elements of control:
* Diet - specially calories
* Exercise - specially calories
* Medication

## Login
Uses google connect and permission to store the data in users Google Drive

## Main Menu Page
On launching the app, user is shown the Main Menu Page. From this page, the user can transition to diet, exercise or medication log page. A forth icon on this page takes the user to history page. A fifth icon on this page takes you to set up the medication setup page

## Diet Log Page
This page shows following controls:
* Timestamp - populated to current, but changeable using date and time selector
* Meal - DD of Breakfast, Lunch, Dinner & Snack
* Description - Free text field of 100 Chars
* Calories - can be left empty. Numeric or null

## Exercise Log Page
This page shows the follwoing controls:
* Timestamp - populated to current, but changeable using date and time selector
* Exercise Name - free text fields, shows past values as unique options as DD too, but new values typable
* Calories - can be left empty. Numeric or null
* Description - free text fields

## Medication Log Page
* Timestamp - populated to current, but changeable using date and time selector
* Medicin name - Free text field, shows past values as unique options as DD too, but new values typable

## Bio Log Page
This page shows key and value page (For example, weight or blood glucose or pressure):
* Timestamp - populated to current, but changeable using date and time selector
* Name - Free text field, shows past values as unique options as DD too, but new values are typable.Expectation is that the user will type in the unit too.
* Metric - A numeric field for the metric like weight, BGL etc.


## Medication Setup Page
The page shows a list of medicine names. User can add or delete from these. These names are collected uniquely from the log. This is data management for the Medication Log page.

## Metric Setup Page
The page shows a list of metric names, similar to Medication Setup, for Metric setup.

## History Page
TODO: write spec

## Notification Setup Page
TODO: write spec
