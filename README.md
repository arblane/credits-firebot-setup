# credits-firebot-setup

# Description
Firebot setup for playing credits at the end of stream.

# Compatibility
- Firebot 5.58.0+

# Install
+ Download
  + Credits.firebotsetup
  + credits.html
  + credit_marquee.css
  + bits.txt
  + communitygiftsubs.txt
  + follows.txt
  + giftsubs.txt
  + hostsraids.txt
  + mods.txt
  + subs.txt
+ Import the downloaded firebotsetup file
  + Customize
    + You will need to edit the preset effect to change the location of the html and text files.
    + Location, color, etc of the marquee

# Usage

## Overlay
+ This firebotsetup makes use of a scene in OBS

## Requirements for Chat
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
