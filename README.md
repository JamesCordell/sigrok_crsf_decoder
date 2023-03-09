# sigrok_crsf_decoder
A decoder for the crossfire protocol.

Channels packed and link status has been implimented only. Needs more testing with other modes. I tested with mode 4.

This decoder is stacked on uart so select uart in Pulseview.

To install and use this decoder put the ./crsf/ directory in 

` /usr/share/libsigrokdecode/decoders/`

or where ever your operating system keeps its sigrock decoders. 
