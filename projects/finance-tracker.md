---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Plaid x Google Sheets API Finance Tracker"
date: 8/29/2023
published: true
labels:
  - Javascript
  - NodeJS
  - Google Cloud API
  - Plaid API
  - GitHub
summary: "Automatically imports bank transactions and balance data from Plaid into a Google Sheet. Customize your Google Sheet and Create your own Intuit Mint today!"
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

After trying many different finance tracking methods such as Intuit Mint, YNAB, Rocket Money, Notion, and writing it out on paper every month I realized most are either time consuming to use and track finances, or offer no flexability. I found Excel/Google Sheets to be the best in terms of flexibility, however entering every tranaction manually is time consuming and annoying. Because of this I decided to create a tool to automatically sync your bank transactions and balances into Google Sheets. This way you have all the data Fiannce tracking apps such as Mint have access to, but you can customize your Google sheet to include or exclude data in a format that works for you.

<hr>

### The technical details
To Build this application I used NodeJS as the main technology. This is becuase for the two API's I used Javascript had the most documention. The application makes use of Google Sheets API. Google Sheets is a free alternative to Microsoft Excel that is entirely hosted online. The API is provided from Googles Cloud console. It allowed me to login any Google account and update different sheet data through code. Secondly Plaid's transactions and balance API was used. Plaid is a fintech company that speciflices in retriving data from thousands of banks. They offer free access to 100 connected accounts. With these technologies I was able to build Javascript scripts. The first one called "server.js" initializes the Plaid client and hostes the login screen for plaid on localhost:3000. Once the user goes to the page and logs into their bank through plaid the access key to their account is logged into the console and it is stored into a .env file. With this information "DailyUpdate.js" can be ran whenever I or someone wants to update the transactions and balance data in Google Sheets. On the first run it will ask you to sign into your google account to get access to the Google sheet. With "DailyUpdate.js" it can be set on a cron job either on a local machine or online through circle.ci or other services to run at a set time daily. The Javascript file makes an API call to get all your banks transactions and balance data, it then inserts this data into the specificed Google Sheet.

look
The room is a picture of decay with only a faded number identifying it as room-4. The bed you were
 lying on is stained with what looks like dried blood. Could it be your blood? No - it is not. The
 only way out of the room aside from the door to the corridor is a window that is boarded shut. It
 looks like it has been like that for decades. There is a door going west from here. You see a candle
 on the floor. You see a match on the floor.

pickup candle
- you are now carrying the candle -

pickup match
- you are now carrying the match -

light match candle

The candle is now lit. It illuminates everything in the room.

walk west
The corridor is lit with the candle. It is so long that you cannot see to the end. You notice that
 there are words written on the wall. There is a door going east from here. There is a way going north
 from here. There is a door going south from here.
</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
