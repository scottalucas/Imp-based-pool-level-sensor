# Imp-based-pool-level-sensor
This is some code for an electric imp-based pool level sensor. It integrates with a home automation controller from Universal Devices to automatically refill the pool when water levels are low. I'll post a link to the instructable for the sensor when I've finished the document. The sensor and its code are working alpha-level solutions.

A few years ago we moved into a house with a nice little pool. It's an old one, built some time in the '70s. I replaced the pumps and upgraded the pool controller but keeping the pool at the right level was, well, hit and miss. And with all the money I'd spent on the new pumps, I cringed every time the level was too low and the pumps ran dry. Since the refill valve was manual, we also overfilled the pool a couple of times when we forgot the water was on.

The sensor automatically detects low water levels and turns on the pool refill valve to keep it full without accidentally overfilling. It has a waterproof temperature sensor too. I used the Electric Imp IoT platform because it works with WiFi and doesn't require an on-site controller. I can check the pool level from anywhere by logging in to the sensor's Imp agent in the cloud.

I've integrated the probe with a home automation system based on the Universal Devices ISY controller, but I'm not going to spend too much time on that part of the project. I'll focus on the build of the sensor itself, which could also be useful to monitor water levels in pools, fountains, fish tanks, water storage tanks, or whatever you need to track.

