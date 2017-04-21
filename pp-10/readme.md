# Production Problem 10: A/B Testing on the Cheap

## The Problem

Locate an interface component on a website that you use frequently that you think could be improved. The improvement should be minor.

Take a screenshot of the interface on both a mobile and desktop device. Then, sketch or illustrate your alternate/"b" test. Finally, describe modification and the HTML, CSS, and JavaScript that you would need to write in order to conduct the test.

## Deliverables

* Screenshots of the interface component on mobile and desktop, placed in this directory (`pp-10/`)

* Sketch or illustrate (e.g., in Photoshop) your alternate/"b" test, placed in this directory (`pp-10/`)

* A text description of the modification, and a description of the HTML, CSS, and JavaScript that you would need to write for the test (you do *not* have to write the actual HTML, CSS, and JavaScript, however)

Modifications:
Laptop: Instead of putting "make an online payment", "manage my account login" etc on the right hand corner, they could be placed in the empty space below the them. It makes the page look more filled with content and even spaced which makes it easier for user to interact with. Also, there's redundancies of "make an online payment" and "manage my account login". They both have the same link so I would prefer if they just said "Manage my account or Log in."

Mobile: The text is a bit hard to see and the nav bars are too small to be clicked on. The "Authorizing payment" paragraph isn't needed. I would say they could have a login form instead of unnecessary text. 

HTML: Instead of "make an online payment", it'll just read "login" and it'll be inside a form which will ask for username and password, and a login button. Increase the font size for mobile view and delete unnecessary text.

CSS: The form will have a border and background color, different color for the submit button when a mouse is hovered it and also for the "not yet registered? sign up now."

JavaScript: This will validate the username typed and the password. It will also display error message if there's an incorrect username or password.