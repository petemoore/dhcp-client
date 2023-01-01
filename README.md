# dhcp-client

This program emulates the network traffic of a Raspberry Pi 400 when it
attempts to PXE boot.

I am emulating the network activity in order to inspect server responses from
my PXE boot server, in order that I can implement my own PXE boot server.

Another way to do this would have been to use a network hub or a managed switch
to capture the packets passing through them, but I don't have either of those.
:D

I'm studying the PXE boot server responses so that I can implement my own
(simple) PXE boot server for my SAM Coupe using the Trinity Interface, in order
to be able to develop a bare metal OS for the Raspberry Pi 400 directly on the
SAM Coupe, and serve it over the LAN to the booting Pi.
