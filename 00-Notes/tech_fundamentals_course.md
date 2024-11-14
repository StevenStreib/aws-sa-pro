# Cantrill Tech Fundamentals Course

## OSI 7-Layer Networking Model

- Layer 1-3 are Media Layers
  1. Physical
  2. Data Link
  3. Network
- Layer 4-7 are Host Layers
  4. Transport
  5. Session
  6. Presentation
  7. Application

## Other Networking

- VLANs
  - Create separate isolated L2 network segments
  - 802.1Q are VLANs
  - 802.1AD are nested QinQ VLANs
- BGP
  - Edge routers are referred to as an Autonomous System
  - Autonomous System Numbers (ASN) are the unique IDs in the system
  - a path-vector protocol that exchanges the best path to a destination between peers
    - called the ASPATH
  - AS Path Prepending
    - Artificially make a bad path longer to make BGP choose the longer but better path
