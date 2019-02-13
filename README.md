#Single page feature list (Progressive Web Applications-1)
This repository is part of my series while learning Progressive Web Applications(PWAs).

It renders a single page containing features of progressive web apps viewable in no network.
However, the resources were already codes as part of basic task and just registration of service worker was done.

Learnings : 

Addition of the code mentioned below in app.js helped to register Service Workers included in the sw.js file and run even in no Network mode. Initially, the page would display no network connection in offline state.

`navigator.serviceWorker.register("sw.js");` 

Google Chrome Developer tools (Cmd + Option + I for mac) was used for testing visibility in Offline mode.
Testing of registration of service worker is viewable under Applications > Service Workers.
Test for offline mode is viewable under Application > Service Workers > Offline > Reloding page or under Network > Offline and reloading page.
