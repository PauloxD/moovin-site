---
layout: page
title: What's New
include_in_header: true
---

# Changelog
These are the moves that I have been making. From the first days of building, to moving-in day.

### `Release`

# **1.0.2**
It's been a little while since I posted an update. This update includes the following changes and improvements

#### What's new
- You can now export any home move to PDF as a checklist. This could come in useful if you are going old school.

#### What's changed
- Performance improvements attached to image loading.
- Fixed a small loophole that allowed you to add items with no name.
- macOS. Fleshed out the Help section. Just in case you get stuck. 
- macOS. Added a way report any bugs you discover, that need squishing.


# **1.0.1**
Been quite a ride getting to this point. This update provides a few features that I felt were required, and a few that are nice to haves.

#### What's Changed:
- When adding a new box, you can pick from locations that you have already added into to the app. Meaning quicker input
- You can move items between different boxes.
- Filter your boxes by whether they contain heavy or fragile objects.
- Protected Boxes. You can now provide protection to your boxes. I mean, not literally. Your phone isn't going to suddenly turn into Arnie. But, you can hide items contained in a box from others using biometrics.
- Attachments. You can take a picture of the items in the box for ease when trying to find what you're looking for.
- Fixed a bug on iPad that meant that the description of an item, would cause the whole screen to have a fit.
- Localisation improvements
- MacOS has some improvements to the way in which a user can interact with the app. Drag and drop boxes into different locations, or items to different boxes.

# **1.0**
We're on the store!

#### What's new
- macOS. Localization has been finished.
- macOS. Drag items from one box to another
- macOS. Item Detail View. With support for dragging an image into the placeholder.


# **1.0 RC (6)**
We're getting there. A few more things have been completed. A couple of things have changed (some for the better, some because of neccessity).

#### What's new
- iOS. You can now move an item between boxes.
- iOS. Add a picture from your gallery or from the camera.
- iOS. Added some characteristics when creating a box. You can select whether the box is heavy or contains fragile items.
- Added Localisation for French, Spanish, Romanian, and Japanese.

#### Changed
- Had to remove the falling animation for items, when creating a new box. This may return in the future, but it meant that I couldn't add the characteristics portion.

# **1.0 RC (5)**
We're at the Release Candidate stage! Most of the usability stuff in the app has been completed. Functionality seems to be working. There are a few things left to do; App Screenshots; Unit Tests; Localisation; Tidy up.

#### What's new
- iOS. Bug Reporting. You can now send feedback from within the app.
- iOS. Siri Integration. You can now ask Siri to "Find an item".
- [Updated Privacy Policy](moovin-site/privacy)

### `Beta`

# **0.9(5)**
In build 5

#### What's new
- iOS. Added some sorting options for boxes
- iOS. Empty State View for a new box.

# **0.9(4)**
Build 4 of version 0.9 fixes a few issues. It also adds a few tweaks and life improvements

#### What's new
- macOS. Nice little animation for the AppIcon. Not really required, but looks cool.
- Updated Licence Agreements.
- Added some UITests to the app. Hopefully it helps to ensure the product always works
- Added some Accessibility items. A long way to go, but it's better than nothing.

#### Bug Fixes
- iOS. Tapping close on the camera immediately after scanning a code would cause a crash.
- iOS. Improved Bounding Box detection for codes. It's not perfect, but it will do, for now.

# **0.9(3)**
Build 3 of version 0.9 fixes a few issues. They are listed below.
#### Bug Fixes
- macOS. Not having a home move, means that clicking the plus button wouldn't work. Now it will show a create your first move screen.
- iOS. Code Recognition improvements.
- WelcomeSheet for some reason would not dismiss. This has been fixed.

# **0.9**
Version 0.9 has been submitted for Beta testing on iOS and macOS. The iOS version was **approved** almost immediately, and the macOS version needing some fixes, which are detailed below.

#### Bug Fixes
- macOS sidebar size was hiding the 2 main buttons, increasing the minium width of the sidebar seems to have resolved this.
- macOS. Not having a home move, means that clicking the plus button wouldn't work. Now it will show a create your first move screen.


<br>

### `Alpha`
# **0.9**
Massive jump I know. But I've been busy, and not keeping track on the incremental changes that have been made along the way, so thought I'd just put them all in one section. Here goes

#### What's New
- Cross Device syncing is working
- Refactored a lot of code to handle multiple devices
- Added a cool (well I think so) animation as a backdrop for when adding a new box
- Added Menu bar actions to the macOS version
- Confirmation checks to the mac version when deleting a box or erasing all the content from the app.
- You can now add multiple items to a box at once
- Welcome Sheet on iOS and macOS
- About Screen for macOS and iOS


# **0.1**
Finally got box scanning to work, there are a load of problems with orientation changes. Need to look into.

#### What's New
- Can scan a box
- Can search manually based on items, or box codes
- [Changes to Privacy Policy](moovin-site/privacypolicy)

#### Known Bugs
- Fix orientation issues with the camera

<br>
