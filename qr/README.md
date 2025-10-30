# Entanglement QR Code Demo

Another demo by Aaron to visualize the latency and connectiveness with Solace Cloud MQTT (or any MQTT service, really!).


## https://sg.solace.com/qr

![](https://github.com/aaron-613/demo-qr-entanglement/blob/master/gfx/qr_screenshot.png "Screenshot")


## Premise

[Click here](https://sg.solace.com/qr) load up the page. It will generate a QR code to scan with a phone. Once the phone connects and entagles, you can control the cube from either device either via rotational/accelerometer data (doesn't work on iPhones anymore), or via swipe gestures.


## Instructions to deploy

1. Clone/copy to some webserver somewhere, e.g.: `https://yourserver.com/qr/`
1. Edit the index.html file:
   1. Update the URL variable `URL_WHERE_DEPLOYED` near the top to match your webserver URL
   1. Add any additional MQTT server connections to the connections section (around halfway through the file).  Feel free to sign up for Solace Cloud: https://cloud.solace.com
1. Run it, and scan it!



## Licences

Check the LICENSE file
