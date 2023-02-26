### 2023-02-26: RNS Presentations 0.1.0

This release aims to make the `Part 1 - Introduction` presentation more concise and to clarify a few things. It also adds the slides `Programming Languages` and `API`.

**Changes**
- Slide 10 `Terminology`
  - Simplified to only explain Peer and Node
- Slide 11 `Hardware`
  - Moved from 22 to 11
  - Introduces the term RNode which is used in the next slide
- Slide 12 `Software`
  - Moved from 21 to 12
  - Simplified
- Slide 18 `Goodbye Internet Stack`
  - Tries to show more clearly that Reticulum only needs the raw bit stream of the Physical Layer to be functional
  - Tries to show that only the Physical Layer part of e.g. Ethernet, Wifi and Bluetooth are needed for Reticulum to work. There is no need for MAC addresses that reside on the Network Layer part of these standards.
- Slide 23 `Reference Node Setup`
  - Simplified 
  - Programming Languages are now on a separate slide
- Slide 23 `Reference Client Setup`
  - Simplified
  - Programming Languages are now on a separate slide
- Slide `Programming Languages`
  - Added to show the programming languages used more clearly
  - Fix: The RNode Firmware is written in C not im Python
- Slide `API`
  - Added to point out the developer friendly API.