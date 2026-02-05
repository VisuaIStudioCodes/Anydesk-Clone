/workspace/Anydesk-Clone$ /bin/bash -lc git status -sb
## work
 M README.md
/workspace/Anydesk-Clone$ /bin/bash -lc git add README.md
[work ca81387] Expand README overview
 1 file changed, 34 insertions(+), 1 deletion(-)
/workspace/Anydesk-Clone$ /bin/bash -lc nl -ba README.md
1	# Anydesk-Clone
     2	
     3	A lightweight clone of the AnyDesk-style remote desktop experience. This repository is a starter
     4	project intended for learning, prototyping, and extending with your own features.
     5	
     6	## Overview
     7	
     8	Anydesk-Clone aims to provide the foundations for:
     9	
    10	- Session initiation between a host and a client
    11	- Secure connection negotiation (placeholder for future TLS/DTLS work)
    12	- Input forwarding (keyboard/mouse) and basic screen streaming
    13	
    14	## Getting Started
    15	
    16	1. Clone the repository.
    17	2. Install dependencies (to be added as the project evolves).
    18	3. Run the application (startup scripts will be added once the runtime stack is defined).
    19	
    20	## Roadmap
    21	
    22	- [ ] Define runtime stack and dependencies
    23	- [ ] Add build/run scripts
    24	- [ ] Implement signaling and session lifecycle
    25	- [ ] Add authentication and encryption
    26	- [ ] Build a minimal UI for host/client roles
    27	
    28	## Contributing
    29	
    30	Issues and pull requests are welcome. Please describe the problem and proposed solution clearly.
    31	
    32	## License
    33	
    34	This project does not yet define a license. Add one if you plan to distribute the code.
