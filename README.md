# credits-firebot-setup

# Description
Firebot setup for playing credits at the end of stream.

# Compatibility
- Firebot 5.61.2+

# Install
+ Download
  + Credits.firebotsetup
  + credit_marquee.css
+ Import the downloaded firebotsetup file
  + Customize
    + You will need to edit the preset effect to change the location of where you want to store the html and text files. This will be handled via an import question.
    + Location, color, etc of the marquee

# Usage

## Overlay
+ This firebotsetup makes use of the Firebot overlay

## Requirements for Chat
+ When any of the following events is triggered for the first time, the user's name will be stored in a text file matching the event category.
  + bits - Must cheer at least one bit
  + communitygiftsubs - Must gift at least one sub to the community.
  + follows - Must be a new follower
  + giftsubs - Must gift at least one sub.
  + hostsraids - Must raid into stream. Hosts are deprecated.
  + mods - Must be a mod of the channel and must have typed in chat.
  + subs - Must subscribe or resubscribe to the channel.

## Streamer Info
+ Commands
    + !clearcredits
      + clears the txt files, can be added to a startup event
    + !rollcredits
      + roll the credits, can be connected to a touch portal/stream deck button

# Credits
+ Adapted from setup by: cavemobster
