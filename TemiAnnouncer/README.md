<img src="megaphone.png" align="right" height="150"/>

# Temi Announcer
Temi Announcer is a versatile application that announces customised speeches upon arrival at a location.

Routes can be created in Temi Announcer with selected locations, and they can be configured to announce speeches upon 
arrival at each location.

If you prefer to announce the same speech at specific locations (and do this repeatedly), Temi Announcer offers Patrol Routes
as a solution.

## Why should I use Temi Announcer?

Perhaps you are a business owner and you would like to offer visitors who enter your physical store/facility a service that can bring them
to a location of their choice? Temi Announcer allows you to add a description and an image to a location saved in temi, so that
visitors have a better idea of where to go, and they can select that location for temi to escort them there.

Perhaps you manage a hospital, and you would like the nurses to go to specific wards/beds to inform patients on something. 
Temi Announcer allows you to create Patrol Routes, which can announce the same message at selected locations, and optionally do
this task repeatedly.

## Is there anything I need to do before using Temi Announcer?
1. Turn off the screen that appears when temi travels to a location
   > Settings > General Settings > Fullscreen navigation notification > OFF

2. Turn off temi's "Tracking User" setting
   > Settings > General Settings > Tracking User > OFF  

3. Turn off the green label that appears at the top when temi is navigating (Optional)
   > Settings > General Settings > Navigation status label > OFF
   
4. Refrain from navigating around the app using the back button on the left/right of Temi's bottom toolbar.


<div style="page-break-after: always;"></div>


# Overview

## "Sign In" screen
The Google account selected will be added to Temi Announcer, where you can import images from.<br>
![](signin.jpg)

## "Locations" screen
This screen is where all the locations in Temi Announcer resides. Each location on this screen displays their image (if present)
as well as their description. Clicking on a location will make Temi navigate to the selected location<br>
![](locations.jpg)<br>

"Location items" in the screen can be shown in 1 row (default) or 2 rows, which can be set in the "Configuration" screen. <br>
These items can be reordered for your convenience. To do that, make sure the "Sort by alphabet" button is not selected **(Selected - Green, Not Selected - White)**.
Long press on the item you want to reorder until the item becomes partially transparent, and drag it to where you would like its new position to be, and release your finger
to drop the item in its new position.<br>

**Tip**: Dragging and dropping the "location items" **does NOT swap** the items, but rather it places all other items that it has displaced either in front or behind
the dragged item.

Selecting the "Sort by Alphabet" button will sort the location items by their location name alphabetically. If the items are presented in 2 rows, the order
in which the items are presented are in the fashion illustrated below:
![](locationsOrder.jpg)<br>

Clicking on a "location item" will cause Temi to navigate to the mapped location saved under the same name. (Please see Temi's "Locations" option if unsure)

## "Routes" screen
This screen is where all the routes in Temi Announcer resides. Patrol routes are indicated with their light blue border, and
clicking their drop down button allows users to see more details of the patrol route. Clicking on a route executes that route.
![](routes.jpg) <br>

"Route items" in the screen can be shown in 1 column (default) or 2 columns, which can be set in the "Configuration" screen.<br>
These items can be reordered for your convenience. To do that, make sure the "Sort by alphabet" button is not selected **(Selected - Green, Not Selected - White)**.
Long press on the item you want to reorder until the item becomes partially transparent, and drag it to where you would like its new position to be, and release your finger
to drop the item in its new position.<br>

**Tip**: Dragging and dropping the "route items" **does NOT swap** the items, but rather it places all other items that it has displaced either in front or behind
the dragged item.

Selecting the "Sort by Alphabet" button will sort the route items by their titles(name) alphabetically. If the items are presented in 2 columns, the order
in which the items are presented are in the fashion illustrated below:
![](routesOrder.jpg)<br>

Clicking on a "route item" will cause Temi to execute the clicked route.

## "Configuration" screen
This screen is where all configuration in Temi Announcer is done. Click the Temi Announcer logo **3** times in any of the non-configuration screens
after signing in, and enter the configuration password to access the screen
![](configuration.jpg)

## "Middle" screen
This screen is shown right after signing in successfully at the "Sign In" screen. From here, you can go to one of three screens: "Routes",
"Locations", "Configuration".<br>
![](middle.jpg)

### Default Configuration Password
The default configuration password is "**Robosolutions**".<br> To change the password, please see [this](#changing-configuration-password).

<div style="page-break-after: always;"></div>

# User Guide - Locations
* [Creating/Deleting locations](#creatingdeleting-locations)
* [Adding an image to a location](#adding-an-image-to-a-location)
* [Adding speech/description to a location](#adding-speechdescription-to-a-location)
* [Reorder locations in screen](#reorder-locations-in-screen)

# User Guide - Routes
* [Creating routes](#creating-routes)
* [Creating patrol routes](#creating-patrol-routes)
* [Adding on-screen dialogs upon reaching a location in the route](#adding-on-screen-dialogs-upon-reaching-a-location-in-the-route)
* [Editing/Deleting a route (patrol/non-patrol)](#editingdeleting-a-route-patrolnon-patrol)
* [Reorder routes in screen](#reorder-routes-in-screen)
* [Creating many (patrol) routes with the same dialog message/patrol speech](#creating-many-patrol-routes-with-the-same-dialog-messagepatrol-speech)


# User Guide - Configuration
* [Saving images into the app](#save-images-into-the-app)
* [Show more locations in the "Locations" screen](#show-more-locations-in-the-locations-screen)
* [Show more routes in the "Routes" screen](#show-more-routes-in-the-routes-screen)
* [Modifying time taken before temi moves to next location in route](#modifying-time-taken-before-temi-moves-to-next-location-in-route)
* [Changing configuration password](#changing-configuration-password)

<div style="page-break-after: always;"></div>

# FAQ
* [What is a route?](#what-is-a-route)
* [What is a patrol route? How is it different from a normal route?](#what-is-a-patrol-route-how-is-it-different-from-a-normal-route)
* [What is the difference between a speech and description for a location in the app?](#what-is-the-difference-between-a-speech-and-description-for-a-location-in-the-app)
* [What is a "dialog message" of a route?](#what-is-a-dialog-message-of-a-route)
* [How do I stop execution of a continuous(indefinite) patrol route?](#how-do-i-stop-execution-of-a-continuousindefinite-patrol-route)
* [Can Temi Announcer (not) announce the speech of a location upon arrival? How do I do that?](#can-temi-announcer-not-announce-the-speech-of-a-location-upon-arrival-how-do-i-do-that)
* [Can Temi Announcer (not) announce the description of a location, not just the speech of a location? How do I do that?](#can-temi-announcer-not-announce-the-description-of-a-location-not-just-the-speech-of-a-location-how-do-i-do-that)

<div style="page-break-after: always;"></div>


## Creating/Deleting locations
Locations in the app reflect the locations saved in temi. As such, adding/deleting locations in the app can be done only
by adding/deleting locations stored in temi respectively. Once you have re-entered the app after creating/deleting a location,
changes should be reflected in the "Locations" screen. If not, press the refresh button at the top-left corner of the "Locations" screen

## Adding an image to a location
In the "Configuration" screen, click the desired location that you wish to edit at the top, and then click the **"Edit"** button under the **"Image of Location"** 
section. If the screen (dialog) that opens does not show any images/you will have to [save images into the app](#save-images-into-the-app).<br>
![](add_image_to_loc_1st.jpg)<br>
![](add_image_to_loc_2nd.jpg)<br>
![](add_image_to_loc_3rd.jpg)<br>

## Adding speech/description to a location
In the "Configuration" screen, click the desired location that you wish to edit at the top, and then click the **"Edit"** button under the appropriate section.


## Reorder locations in screen
In the "Locations" screen, you can drag and drop a location item to reorder them as you like. Press the desired location item until it turns more transparent,
drag it to the location item you would like to switch with, and release your finger from the screen. Learn more [here](#locations-screen).

<div style="page-break-after: always;"></div>

## Creating routes
In the "Routes" screen, click the red button with an addition symbol on the bottom right. Enter the configuration password to proceed.<br>
![](add_route_1st.jpg)<br>
Fill in the new route's title at the top. To create a patrol route, see [this](#creating-patrol-routes).<br>

Under the "Saved Locations" section, click the desired location to add them into the route that you want to create.
To remove a location from the route that you are building, click on that location under the "Routes" section instead of the "Saved Locations" section.<br>
![](add_route_2nd.jpg)


## Creating patrol routes
Under the screen to [add a new route](#creating-routes), toggle the switch under **"Is this route a patrolling route"** to the **"Yes"** option. <br>
![](add_patrol_route.jpg)<br>

Patrol Count refers to the number of times the route you specify will be repeated. If you want this route to be patrolled indefinitely, toggle the checkbox 
"Is patrol continuous?" to "Yes". Temi will return to home base when its battery gets low (15%). <br>

If you want to add an image to be shown throughout the patrol route, but the screen(dialog) that appears shows no images to select from, you have to first
[save an image into the app](#save-images-into-the-app).<br>

To add a screen(dialog) that pauses execution of the route before moving to the next location (after it has reached a location), with a configurable message on the
screen, please see [this](#adding-on-screen-dialogs-upon-reaching-a-location-in-the-route). If not, leave the "Dialog message before moving to next destination" 
section empty.<br>

If you are unsure of how to select the locations in the route, please see the ["Creating Routes"](#creating-routes) section.


## Adding on-screen dialogs upon reaching a location in the route
Under the screen to [add a new route](#creating-routes), fill in the section under **"Dialog message before moving to next destination"**. This message will be
shown on a dialog that appears once temi arrives at any location (except for the last location, but not true for patrol routes) in a route.<br>

The dialog will appear for a [configurable amount of time](#modifying-time-taken-before-temi-moves-to-next-location-in-route), before temi proceeds to the next
location. There is also an "OK" button in the dialog which users can press to proceed to go to the next location without having to wait for the 
configurable amount of time to pass.

## Editing/Deleting a route (patrol/non-patrol)
Under the "Configuration" screen, select the "Routes" tab on the left, and all of the existing routes will be shown on the right. <br>
![](edit_route_1st.jpg)<br>
Click the desired route at the top, then click the "Edit" button at the bottom to proceed to the screen to edit the desired route, or the "Delete" button
to delete the desired route.<br>
![](edit_route_2nd.jpg)<br>
![](edit_route_3rd.jpg)<br>


## Reorder routes in screen
In the "Routes" screen, you can drag and drop a route item to reorder them as you like. Press the desired route item until it turns more transparent,
drag it to the route item you would like to switch with, and release your finger from the screen. Learn more [here](#routes-screen).

## Creating many (patrol) routes with the same dialog message/patrol speech
To do this, take advantage of the copy and paste feature when editing a route.<br>

If you would like to create many (patrol) routes with the same dialog message, especially if the dialog message is lengthy, **create these routes but leave
their dialog message empty**. Under the "Routes" tab in the "Configuration" screen, you can then edit one of these routes, add the dialog message to that route,
save, and then click "Yes" when asked to copy the dialog message to other routes. A dialog will appear that allows you to select all the routes that you 
wish to copy the dialog message to.<br>
![](copy_dialog_msg.jpg)<br>
![](copy_dialog_msg_screen.jpg)<br>

If you would like to create many patrol routes with the same patrol speech, especially if its lengthy, the procedure is similar to the previous paragraph, but for the
patrol speech instead. When asked to copy the **dialog message** to other routes, click "No", and then you will be asked to copy the **patrol speech** to other patrol
routes, to which you should click "Yes". A dialog will appear that allows you to select all the patrol routes that you wish to copy the patrol speech to.<br>
![](copy_patrol_speech.jpg)<br>
![](copy_patrol_speech_screen.jpg)<br>

<div style="page-break-after: always;"></div>

## Save images into the app
Under the "Configuration" screen, select the "Resources" tab on the left.<br>
![](save_image_app_1st.jpg)<br>
Click the green button at the center top, and a dialog will appear. From there, you can choose where to import your images (into the app) from. <br>

## Show more locations in the "Locations" screen
The app allows showing 2 rows instead of 1 row (default) of locations in the "Locations" screen. <br>
Under the "Configuration" screen, select the "Settings" tab on the left, then under "Locations", change the "Number of rows in Locations screen" option.<br>
![](show_more_loc.jpg)

## Show more routes in the "Routes" screen
The app allows showing 2 columns instead of 1 column (default) of routes in the "Routes" screen <br>
Under the "Configuration" screen, select the "Settings" tab on the left, then under "Routes", change the "Number of columns in Routes screen" option.<br>
![](show_more_routes.jpg)

## Modifying time taken before temi moves to next location in route
Under the "Configuration" screen, select the "Settings" tab on the left, then under "Routes", change the "Number of seconds that temi will wait before continuing
to next destination" option. The default option is 30 seconds.<br>
![](time_taken.jpg)

## Changing configuration password
Under the "Configuration" screen, select the "Settings" tab on the left, then under "Others", click the "Edit" button of the "Configuration Password" section to be
brought to a dialog to change your password.<br>
![](config_pw.jpg)

<div style="page-break-after: always;"></div>


# FAQ

## What is a route?
A route is a sequence of locations saved in the app. Configuring the locations on the route (setting a location's image, speech on arrival, and its description),
affects execution of the route (i.e temi going to each location on the route).

## What is a patrol route? How is it different from a normal route?
A patrol route differs from the normal route in a few ways:
1. **Speech on arrival at a location**: Upon arrival at each location, it announces the same speech. This is independent of the individual locations' speech.
2. **Description of location**: Regardless of the announcing configuration settings, the description of a location will never be announced upon arrival.
3. **Repetition**: A patrol route can have its patrol count configured to repeatedly execute the route. Continuous patrol is an option that allows temi to execute the route
indefinitely until its battery runs low
4. **Image of location**: Similar to the 1st point, all locations on the patrol route share an image independent of their individually configured images, that will be displayed
throughout route execution.

## What is the difference between a speech and description for a location in the app?
Both speech and description for a location can be announced, but only the description for a location will be shown in the locations
screen. If both speech and description are to be announced, the speech will be announced before the description. 

## What is a "dialog message" of a route?
It is a message that appears in a dialog upon arriving at any of the locations (except the last one) in a normal route. This is similar for patrol routes, except that the 
last location in the **last repetition** of the patrol will not show the dialog with the message upon arrival.<br>
The dialog will pause navigation to the next location in the route for the duration of the dialog, unless a user presses the "Ok" button in the dialog, which would cause
Temi to proceed to the next location in the route. Learn how to change the duration of the dialog [here](#modifying-time-taken-before-temi-moves-to-next-location-in-route).<br>
If you don't need to pause further execution of the route for **specific** routes, you can just leave the dialog message option empty when adding/editing these routes.<br>
If you don't need to pause further execution of the route for **all** routes, under the "Settings" tab of the "Configuration" screen, find the option called "Show dialog 
before moving to next destination" under the Routes section, and uncheck it.

## How do I stop execution of a continuous(indefinite) patrol route?
The best way to stop execution is to touch the interaction button on the top of temi's screen. Performing any other action may result in unintended behaviour of Temi
Announcer.


## Can Temi Announcer (not) announce the speech of a location upon arrival? How do I do that?
The speech of a location upon arrival at the location (using the "Locations" screen) is turned **on** by default.<br>
When Temi arrives at a location when navigating a **normal** route (using the "Routes screen), the speech of the location **will NOT** be announced
by default.<br>

Changing either situation is similar to changing the announcing of the description of a location. Please find the [similar, appropriate option](#can-temi-announcer-not-announce-the-description-of-a-location-not-just-the-speech-of-a-location-how-do-i-do-that) 
under the "Configuration" screen.

## Can Temi Announcer (not) announce the description of a location, not just the speech of a location? How do I do that?
The description of a location upon arrival at the location (using the "Locations" screen) is turned **off** by default.<br> 
When Temi arrives at a location when navigating a **normal** route (using the "Routes" screen), the description of the location **will** be announced 
by default.<br>

To change the former (navigating to a location using "Locations" screen), go to the "Configuration" screen, and under the "Settings" tab, find and tweak
the option "Announce description upon arrival at a location...". under the Locations section.<br>
To change the latter (navigating to a location in a normal route using "Routes" screen), go to the "Configuration" screen, and under the "Settings" tab,
find and tweak the option "Announce description upon arrival at a location..." under the Routes section.<br>

<div style="page-break-after: always;"></div>


## Issues
* App might exit when touching its interaction button when trying to stop its execution of a route. This might happen only when doing such an action for the
first time after installing the app, but it will not happen again.
* Deleting a route might cause the app to crash. The route will still be deleted. When the crash dialog/message appears, close Temi Announcer in the background
and open the app again.

## Acknowledgements
### Icons
<div>Icons made by <a href="" title="wanicon">wanicon</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
<div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>
