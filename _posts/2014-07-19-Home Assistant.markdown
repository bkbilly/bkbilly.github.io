---
layout: default
modal-id: homeassistant
img: homeassistant.png
alt: image-alt
category: Automation
description: "Using Home-Assistant with various devices that interact with it through MQTT or the device specific API. Most of the notifications and automations are working without a need of internet connection.
<br>
<h3>Notification Systems</h3>
<ul class='leftul'>
	<li>Email</li>
	<li>Pushbullet</li>
	<li>TTS (Speaker, Google home)</li>
	<li>Screen (chromecast, Kodi)</li>
</ul>
<h3>Devices</h3>
<ul class='leftul'>
	<li>Wifi Relay with ESPHome firmware (Sonoff Dual R2, Sonoff Basic)</li>
	<li>Computer (Ubuntu server, Raspberry PI)</li>
	<li>Zigbee HUB (CC2531 USB stick)</li>
	<li>Zigbee Devices (Xiaomi Cube, Xiaomi Aqara Switch, Xiaomi contact & motion sensor)</li>
	<li>Smart Bulbs (Yeelight, Xiaomi Philips)</li>
	<li>IR Remote (Broadlink RM mini 3)</li>
	<li>Speaker/Microphone</li>
	<li>USB TV Tuner (Crypto ReDi PC 50 A)</li>
	<li>Smart TV (Chromecast)</li>
	<li>Smart Speaker (Google Home, Echo Dot)</li>
	<li>Cameras (Hikvision, etc…)</li>
	<li>Electric Water Valve</li>
	<li>VoIP Analog FXO (Linksys SPA3102, Grandstream HT503)</li>
	<li>UPS (APC Back-UPS 950VA, 18650 Battery Shield)</li>
	<li>Router (Asus RT-AC56U)</li>
	<li>NFC Tags</li>
	<li>Temperature/Humidity sensors (DHT11 module)</li>
</ul>
<h3>How devices are controlled</h3>
<ul class='leftul'>
	<li>Voice Commands through Snips or Google assistant</li>
	<li>Sonsors/Switches from AlarmPI or Zigbee or Camera Image Processing</li>
	<li>WebUI through Home-Assistant Lovelace interface</li>
	<li>Automations based on events like time of the day</li>
</ul>
<h3>Automations Honorable Mentions</h3>
<ul class='leftul'>
	<li>Easily activate/deactivate the alarm with the phone through NFC tags that are outside and inside the home. This way the security cannot be breached because the authentication is done on the phone side.</li>
	<li>Create a switch for the living room which disables all automations there in case we need to watch a movie or sleep. This requires the use of the condition on each automation.</li>
	<li>Using a Sonoff Dual the window cover can be controlled. It closes before the sun shines in the morning.</li>
	<li>Turn on the AC when the door or window is closed and the room temperature is above 29°.</li>
	<li>The lights are turned on when specific sensors are triggered and stay on until they close.</li>
	<li>Scan the network for new devices and notify when they appear. Also checks for specific devices if they are online or not.</li>
	<li>By pressing a specific button on my switch, I can turn on/off my PC, IR speakers, light, AC and window cover.</li>
	<li>When the camera linecrossing is triggered, the image of the event is displayed on the TV.</li>
	<li>Turns off the water heater after a specified time. It uses a Sonoff device with a high-current load contactor.</li>
	<li>Scripts in the UI for checking the status of system services which can be disabled/enabled. Also there are scripts for updating specific services.</li>
</ul>
<h3>Security</h3>
<ul class='leftul'>
	<li>Expose the least required services to the internet</li>
	<li>Use of 2 Factor Authentication when possible</li>
	<li>Use Fail2Ban to block connections with multiple wrong authentication requests</li>
	<li>Block internet access to non trusted devices</li>
	<li>Access internal network from the internet through VPN</li>
</ul>

"


---
