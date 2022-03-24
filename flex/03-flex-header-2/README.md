# Another common header style

We're starting to sneak in a little more CSS that you haven't seen yet. Don't worry about this for now; we just want things to look a little bit prettier, and this CSS will not interfere with your task.

For this one you will probably need to edit the HTML a little bit. Often with flexbox you need to add containers around things to make them go where you need them to go. In this case, you probably want to separate the items that go on the left and right of the header.

This is also the first example where you'll be nesting flex containers inside each other.

## Desired outcome
As with the last example, this one needs to be flexible in the middle, with items pushed to the left and right.

![png](./desired-outcome.png)

![gif](./desired-outcome.gif)

===========================
Not everything but the containers that contain the things you want to move
[8:32 PM]
For that exercise you only need one header, and you cloud use a left-margin auto, on the notification div
[8:32 PM]
So it gets push to the right
[8:33 PM]
You can do that with te example that one of the links at the end of "alligment" lesson gives you
===========================

### Self Check
^ Everything is centered vertically inside the header.
- There is 8px space between everything and the edge of the header.
- Items are arranged horizontally as seen in the outcome image.
- There is 16px between each item on both sides of the header.
- flex is used to arrange everything.