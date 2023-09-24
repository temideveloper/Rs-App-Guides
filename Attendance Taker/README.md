# Temi Attendance Taker 
Temi Attendance Taker is an application used for attendance taking purposes. It allows user to capture their attendance using Temi's built in face recognition system or a V-Card QR Code. 

When captured by temi, temi does not store any location locally but uploads the data to a google sheet. This is an extendable application and can be easily integrated with different APIs for storing data on servers. 


## Why should I use TemiWayFinderV2?

Perhaps you are organising an impromptu event and you would like to manage the attendance of the guests during the event. Or maybe you are a principal of a student care and would like an interactive way to use temi to track your student's attendance. There are different use-cases, and set-up is very simple. 


## Is there anything I need to do before using TemiWayFinderV2?
1. Ensure that face recognition pissions is given to temi through the temi settings page. 

<div style="page-break-after: always;"></div>


# Overview

## "Welcome" screen
There are two buttons on this screen, representing the different modes of recognition available. Temi contacts for face recognition(can be set up in temi center), or qr code scanner mode. 

Click on the mode that you desire to bring you to the corresponding scanner screen. 

## Temi Contacts "Scanner" screen 
There is a preview 


## QR Code "Scanner" screen

## "Settings" screen
You can access the settings screen by pressing the settings icon in either of the scanner screen. 

You will be prompted for a password before being able to enter the screen. 

### Default Settings Password
The default settings password is "**Robosolutions**".<br> To change the password, please see [this](#changing-settings-password).

# User Guide - Modes
* [Creating QR Codes](#creatingvcard-cdoes)
* [Training temi to recognise a person](#adding-an-image-to-temi-center)


# User Guide - settings
* [Changing settings password](#changing-settings-password)
* [Securing QR Codes](#securing-qr-codes)

<div style="page-break-after: always;"></div>

# FAQ


## Creating QR Codes
QR codes can be generated easily using a free vcard generator website such as https://www.qr-code-generator.com/solutions/vcard-qr-code/ . 


## Ensuring QR Code security 
To ensure that the code generated is unique only to your company, the application checks for the company field in the qr code. Make sure the value that you enter for that field matches the password value stored in the app settings. 

## Changing settings password
Under the "settings" screen, select the "Settings" tab on the left, then under "Others", click the "Edit" button of the "settings Password" section to be
brought to a dialog to change your password.<br>
![](documentation/settingsSettings.png)

<div style="page-break-after: always;"></div>