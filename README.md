# SID Translator

### Purpose
Ever had a windows SID you needed translated?  Ever spend hours trying to figure who that account belongs too?  I found a handly powershell script that will easily poll and return that information.  I want to create a small tool where you copy and paste the sid's and display the information for you to use for trouble shooting or information gathering.

### Versions

1.0 - Should be a working applications for user SID's.  You simply copy and paste in the SIDs and the rest will be done for you.

2.0 - I was thinking this could be handly for looking up application SIDs.  I can't count how many times I see a sid in the event log and have no idea of that application is important to my present investigation or if its just some random event showing up in the logs.

### Other thoughts
Since it is no secure I a Citrix engineer at this time.  I use and deploy WEM all the time and sometimes I find some of the features of this app useful when working with in the store information in the DB.  I could write a tool using this application that could dump the DB to do a migration or an import.  Especially if an upgrade fails and you have to copy the information by hand.

### Supported OS's
* Windows 10
* Server 2012 +
