Import Stationf Meeting room to Google
--------------------------------------

# Purpose

When creating an event in google agenda, you can select the meeting room you booked with hal.

This will allow you to see where the meeting room is (block number and level) directly in your calendar.

![Building detail](example.png?raw=true "Title")

# How to import into gCal

1 - Import building 

- go to the resource category in your google admin interface. Usually found here : https://admin.google.com/u/1/ac/calendarresources/buildings
    - if the link doesn't work: admin console > Applications > G suite > Select Google Calendar > Ressources > Buildings
- import `building.csv` using the `Bulk upload buildings` button

2 - Import conference rooms

- go to https://admin.google.com/ac/calendarresources/resources
- import `conference_rooms_create_zone.csv` using the `Bulk upload ressources` button

:warning: It seems it can take up to 1 or 2 days to appear in Google Calendar in the **Room** tab.

brought to you by Nomalab and Craft AI. (you can visit us and give :beer: block 6 Street/Medialab TF1, OR Microsoft Mezzanine for craft)


