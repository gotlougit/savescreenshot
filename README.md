Auto Save Screenshot
===============

Based off of [this project](https://github.com/M-Reimer/savescreenshot) by [Manuel Reimer](https://github.com/M-Reimer), this is a small Firefox extension to take screenshots of certain tabs every x seconds or so. 

WARNING: This is currently in development. IT IS NOT, AND I REPEAT, IS NOT FINISHED RIGHT NOW. USE AT YOUR OWN RISK.

## Features

Dumps a whole bunch of screenshots in your Downloads folder. You can then use some other tool to take all these screenshots and create a PDF out of them.

## Installation

Right now you can only do a [temporary install](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Temporary_Installation_in_Firefox), which works well enough really. The only annoying thing is to reload it again and again, so obviously I'll publish it to addons.mozilla.org once I get the UX down.

## Usage

Install extension, go to your Google Meet meeting, click on the camera, and select any option. It does seem to wait 1-2 minutes before taking the first screenshot but after that you will consistently get screenshots of your meeting in your Downloads folder, spaced 1 minute apart. To stop it from taking screenshots, close the window.

Reloading the extension in ```about:debugging``` also stops it, so you may find that easier.

## Bugs

Check GitHub issues for the bugs

## Roadmap

- Custom timings for taking screenshots

- Make the menu selection relevant

- Select an element of the webpage to take screenshots of (like say, someone's screenshare)

This is kind of inspired by how Firefox's native screenshot utility works

- Better default settings
