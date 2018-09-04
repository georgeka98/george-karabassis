# georgeka98.github.io

### The problem

This is a test website to demonstrate an issue I am facing with using the Pinterest API to allow visotors to share photos
from my webpage to their profiles. However, Pinterest includes images including the **data-pin-nopin** attribute on their tag
which it shouldn't.

### How to see the issue?

To check the issue, click on the Pinterest button on [this](https://georgeka98.github.io/) example webpage and look at the
Images Pinterest chooses. Now, go back to the webpage and right click on one of those images and select "inspect element".
Look at the tag, it has the **data-pin-nopin** attribute.

### What was I expecting?

Pinterest should only selected one image (the one with the burned cars) and ignore the rest.
