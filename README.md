# Week-3-Homework

The purpose of this homework is to leverage animations and gestures to implement more sophisticated interactions. We're going to use the techniques from this week to implement the Mailbox interactions.

Time spent: `10`

### Features

#### Required

- [X] On dragging the message left:
  - [X] Initially, the revealed background color should be gray.
  - [X] As the reschedule icon is revealed, it should start semi-transparent and become fully opaque. If released at this point, the message should return to its initial position.
  - [X] After 60 pts, the later icon should start moving with the translation and the background should change to yellow.
    - [X] Upon release, the message should continue to reveal the yellow background. When the animation it complete, it should show the reschedule options.
  - [X] After 260 pts, the icon should change to the list icon and the background color should change to brown.
    - [X] Upon release, the message should continue to reveal the brown background. When the animation it complete, it should show the list options.

- [X] User can tap to dismiss the reschedule or list options. After the reschedule or list options are dismissed, you should see the message finish the hide animation.
- [X] On dragging the message right:
  - [X] Initially, the revealed background color should be gray.
  - [X] As the archive icon is revealed, it should start semi-transparent and become fully opaque. If released at this point, the message should return to its initial position.
  - [X] After 60 pts, the archive icon should start moving with the translation and the background should change to green.
    - [X] Upon release, the message should continue to reveal the green background. When the animation it complete, it should hide the message.
  - [X] After 260 pts, the icon should change to the delete icon and the background color should change to red.
    - [X] Upon release, the message should continue to reveal the red background. When the animation it complete, it should hide the message.


#### Optional

- [ ] Panning from the edge should reveal the menu.
  - [ ] If the menu is being revealed when the user lifts their finger, it should continue revealing.
  - [ ] If the menu is being hidden when the user lifts their finger, it should continue hiding.
- [ ] Tapping on compose should animate to reveal the compose view.
- [ ] Tapping the segmented control in the title should swipe views in from the left or right.
- [ ] Shake to undo.

### Video Walkthrough 

Here's a walkthrough of implemented user stories:

![Week 3 homework](https://github.com/nvisanji/Week-3-Homework/blob/master/week3_homework.gif?raw=true)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

This one was a doozy. Took a lot of effort to figure out how to move the elements around and then to move elements together. Once I figured it out it went a lot faster.

* Any libraries or borrowed content.
