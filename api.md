# API Server

The API server can be considered a control plane in this system, as it will
handle the sending and receiving of events from gateways to services.

## Notes

- REST for ease of use.
- Event system potentially.

- Services register into the API with what events they want
  to handle.
- Services only get events they have subscribed to.
  

