# pi-k8s-fitches/node-event-daemon
Listens for a button push and publish the event to a Redis channel on a node

Creates a daemon on any pi-k8s noddoe with the label `button=enabled`

Uses GPIO port (pin 4) and 3.3V supply (pin 1), connect those two (with a butten or whatever) to trigger an event and push it to Redis.
