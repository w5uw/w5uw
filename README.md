## Hi, I'm Red Brungardt, W5UW

Ham radio operator for 54 years, LISP programmer for 40, U.S. Navy veteran and retired structural engineer.

### Latest release: QMX+ Configurator v0.2.6 (November 23, 2026)

[QMX+ Configurator](https://github.com/w5uw/QMX-Configurator) is a Windows program for viewing and editing every menu setting on the QRP Labs QMX+ transceiver over USB, with no PuTTY needed. Edits are staged, reviewed, and read back from the radio to confirm each one.

What's new in v0.2.6:

- Number settings use the real range the radio reports (for example, USB Audio Gain and Monitor are 0 to 99) instead of 0 to 255.
- A clearer Messages table, with resizable columns, pending edits shown in orange, and values refreshed from the radio after Apply.
- Read-back no longer stops a batch because of letter case ("cq" stored as "CQ") or leading zeros.
- Set time is handled as the radio's running clock, entered as HHMM.
- A stopped Apply no longer forces a full re-read before you can edit again.

Tested on a QMX+ running firmware 1_04_010.

**[Download v0.2.6](https://github.com/w5uw/QMX-Configurator/releases/tag/v0.2.6)**

73, Red W5UW
