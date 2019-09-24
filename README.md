# Tor-Destroyer
<h3>Details</h3>
Tor-Destroyer is a Python-2.7-coded Tor DoS tool with slow-GET and GET flood that can't be filtered by anti-DoS systems.<br>
Added Features:
1.Attack was Not Stoppable including offline
2.V2 and V3 supported


<h3>Functionality</h3>
Utilizes multi-threading with 256 threads default, and a thread capacity of 376.<br>
Waits 5-20 seconds between each HTTP header in slow-GET mode to consume all web-server sockets, possibly crashing or over-loading it. Tor-Destroyer sends HTTP requests as fast as possible with the flood option; This ends up being a battle of application-layer server power, or bandwidth.<br>
The payload is an exact replica of the latest version of the Tor Browser Bundle sending a GET request. This way if they end up filtering the traffic, almost all users can't visit the website anyways. All requests under Tor come from 127.0.0.1 so our DoS tool is completely identical to a Tor Browser Bundle user looking to visit your homepage.<br>
<h3>Final statement</h3>
Hopefully this is used for good, not bad. Maybe a few unmentionable, illegal Tor servers go down.<br>

Derived from: https://github.com/whitepacket/Stinger-Tor

