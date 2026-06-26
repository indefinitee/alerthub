# Product Vision

Companies receive many events from different systems, but not all events require attention.

AlertHub solves this problem by:

- accepting events from external sources;
- matching events against watchlists and rules;
- creating alerts only for relevant events;
- reducing duplicates and noise;
- assigning alerts to users;
- tracking alert status;
- storing audit history.

## Core flow

External source sends event

- AlertHub validates and stores event
- AlertHub checks watchlist matches
- AlertHub creates alert
- User reviews alert
- User acknowledges or resolves alert
- System writes audit log
