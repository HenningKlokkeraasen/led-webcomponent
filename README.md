# led-webcomponent
A Web Component atom for skeuomorphic LEDs

LOOK! http://henningklokkeraasen.github.io/led-webcomponent/samples.html

##Usage
Add this to the importing document to load the web component:
 - ` <link rel="import" href="led-atom.html">`

Use the web component:
 - `<led-atom></led-atom>`

Properties:
 - color: white | green | yellow | red | blue
 - label: [text] - rendered below the LED
 - tooltip: [text]
 - blinkrate: [int] - blinks the provided number of times per second - leave the property out to have a constant, non-blinking light

Examples:
 - Default: `<led-atom></led-atom>`
 - Green with label: `<led-atom color="green" label="All systems OK"></led-atom>`
 - Red, blinking: `<led-atom color="red" label="LFO Rate" BLINKRATE="0.1"></led-atom>`
 - Center the LED above the label, set a tooltip: `<led-atom alignment="center" tooltip="Text for screenreaders and an indication of what the LED indicates"></led-atom>`

See samples.html for more
