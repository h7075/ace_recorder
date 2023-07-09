# ace_recorder
Records directly from the Allen Heath iLive iDR ACE port to a .wav file
To use this you need: A PC(running Linux), an EthernetCable and any Mixrack. If there is no free ACE Port on the iDR plug the Surface into the normal network port(youre loosing PAFL and the Surface's IO by doing so).
Compile with GCC only requirement is dr_wav.h(https://github.com/mackron/dr_libs).
Use run.sh for running with realtime priority to avoid clicks in the recording. 

Reverse Engineering can be found here:
https://github.com/PatrLind/ah_ace_protocol

For GigaACE/SLink take a look here:
https://github.com/niklasarnitz/slink-recorder
