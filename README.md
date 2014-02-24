This is a simple app that receives a message and displays it in a feed.

# How to send an event to the queue:
curl -X POST -H "Content-Type: application/json" -d '{"event": {"msg":"xyz","type":"test"}}' http://localhost:3002/event

# TODO
** Should have sounds for events
*** Sounds for events should be event-specific