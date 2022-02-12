python fakeAP.py
Create a fake access point with the ESSID of 'Free Wifi' on channel 6 without encryption that responds to all broadcast probes

python fakeAP.py -t
-t, Sniff the air for all access points in range, Ctrl-C to select one and use its ESSID and channel in the creation of your fake AP

python fakeAP.py -c 1 -e 'New SSID' -w
-c, Start the access point on channel 1

-e, Set the broadcast ESSID as 'New SSID'

-w, Set the fake access point to use WPA2 flagged beacon frames and save handshakes to fakeAPlog.cap


****COPY FROM https://hub.fastgit.org/DanMcInerney/fakeAP****
