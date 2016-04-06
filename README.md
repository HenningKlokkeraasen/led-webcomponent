# led-webcomponent
A Web Component atom for skeuomorphic LEDs

<!--Non-blinking variants-->
<led-atom></led-atom>
<led-atom color="Green" label="Status"></led-atom>
<led-atom color="YELLOW" label="Wait"></led-atom>
<led-atom color="red" label="On Air"></led-atom>
<led-atom color="blue" label="Cool"></led-atom>

<!--Blinking variants-->
<led-atom blinkrate="1" label="Clock"></led-atom>
<led-atom color="green" label="Slow" blinkrate="2"></led-atom>
<led-atom color="yellow" label="Warning" blinkRate="0.5"></led-atom>
<led-atom color="red" label="LFO Rate" BLINKRATE="0.1"></led-atom>
<led-atom color="blue" label="Really Slow" BlinkRate="5"></led-atom>

<!--Alignment-->
<led-atom alignment="center"></led-atom><!--Aligns the LED in the center above the label-->

<!--Tooltip-->
<led-atom tooltip="Text for screenreaders and an indication of what the LED indicates"></led-atom>

See samples.html for usage
