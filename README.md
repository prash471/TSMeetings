# Motivation
COVID19 has caused all the workfroce to go online. It doesn't matter whether they are new to it or not, they have to work online without much physical interactions. This has created two major problems in working environment
1. Less interaction among team members
2. Working alone for longer time without much outside interaction burns you out and lower your productivity.

# TSMeetings on rescue
TSMeeting is a slack bot, that will not let you remain untouched from your team even if whole team doesn't meet for months. It's a wrapper over ZOOM's API to increase connectivity among team members. In the mean time you may get a chance to interact with more of those colleagues in your office with whom you never met. Currently following commands are supported

  - `/tsmeet` - to organize instant meetings
    USAGE: 
    1. `/tsmeet <username1> <usernmame2> .... Agenda` - this will create a meeting with mentioned users and send them notification to join
    2. `/tsmeet <username1> ... <channel> ... Agenda` - this will create a meeting with users and channel users and send notification to users and channels
  - `/tslunch` - to organinze instant online lunch/ tea sessions
   USAGE:
    1.  /tslunch - this is a fun way of organizing online lunch sessions. Once this command is run inside a channel, it will send a message that someone from particular department/ office wants to host online lunch session. **The identity of host is not shared inside channel**. Only the one who joins him for lunch will know the identity. In order to join, attendee need to get permission of host (wait zone). The message inside channel will be auto deleted after 30 minutes. 

# ScreenShots
