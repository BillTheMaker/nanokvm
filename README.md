# nanokvm
OS for nano as kvm


This will be my attempt to use the Nvidia Jetson line as a client USB device HID manager for externalizing the processing of AI with Human interface devices.

features I hope to include:

'Smart keyboard' - Looking up something on the internet with a gui and cutting and pasting in a prompt is all possible without your actual pc ever leaving the terminal. 

Network agnostic KVM - USB to one PC, SSH to another, Bluetooth to a third, all handled with the Nano.

intelligent multi-monitor kvm switching - gaze tracking to switch active windows, active desktop, where you look is where you type

User view intelligent actions - computer vision can copy link, table from any monitor or device without USB/TCP/IP connection. 

It is my hope that I can create a feature rich environment that allows for high level prototyping of human interface devices with capacity for AI to distinguish the difference between intentional and unintentional input. 

This is intended to be compatible with installed software that will interact with OS window managers and compositors.  

questions to resolve as of 1/10/2022
    - options and ways2 operate as "slave" or "client" to multiple devices. Software or virtual machine options are preferred, additional hardware is the back-up.
