# Service

A Service in this system refers to a smaller, internal application which
communicates with the API server to perform tasks & process incoming events
from a gateay.

## Notes

- Connect to the API as per notes 3 & 4 from
  [api.md](./api.md).

- Provide their own functionality, separated from everything else, but can
  depend on other services to run.
  - i.e. Staff Applications service can depend on the Punishments service.

- Connect to the API server by some sort of token, so requests have to be
  authorized and permitted by the API.


