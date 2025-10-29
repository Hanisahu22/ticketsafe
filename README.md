# ticketsafe

## Project Description
ticketsafe is a minimal smart contract for creating events, selling capped-supply tickets, and transferring them on-chain. It focuses on simplicity, verifiability, and a small surface area: just three core functions to handle the essentials.

## Project Vision
Enable transparent, tamper-resistant, and portable event access so organizers and attendees can rely on open, verifiable logic instead of opaque ticketing systems.

- Trust through code, not intermediaries
- Simple, composable primitives for ticketing
- On-chain provenance and ownership

## Key Features
- Host creates events with:
  - Name
  - Ticket price (in wei)
  - Max supply (cap)
- Attendees can:
  - Buy tickets (exact-price enforced, supply-checked)
  - Transfer tickets to other addresses
- On-chain verifiability:
  - Public getters for events and tickets
  - Emitted events for indexing (EventCreated, TicketIssued, TicketTransferred)
- Minimal surface area:
  - 3 core functions: `createEvent`, `buyTicket`, `transferTicket`
  - <img width="1817" height="779" alt="image" src="https://github.com/user-attachments/assets/900b24a0-2cc9-4145-9c40-f5f265a6ec25" />
