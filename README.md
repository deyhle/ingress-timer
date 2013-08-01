Ingress Timer
=============

Notifies Ingress Players when it's time to hack a portal (again) using the HTML5 notifications API

## How to use it

It's a single html file with embedded Javascript that works in any modern browser (that supports the notifications API).

1. Click on „Activate Notifications!“ and allow the page to send notifications when your browser asks.
2. Specify the countdown time in Seconds. Default is 300 (= 5 minutes, the time a default Ingress Portal needs to cool down after a hack)
2. Click on „Start Countdown!“
3. After the specified time, a notification will pop up. The tab has to stay open for that, but can be in the background.
4. If you click on the notification, the timer will restart with the same time.
5. If you close the notification, the timer will not restart.

