RTCM is an acronym for Radio Technical Commission for Maritime. This governmental body came up with a way to communicate positions for boats and other vessels many decades ago. Technically, RTCM is just a protocol. We, however, will be using the term RTCM to mean the bytes of correction data related to GPS timing anomalies.

https://learn.sparkfun.com/tutorials/what-is-gps-rtk
http://www.unavco.org/instrumentation/networks/status/all/realtime
https://igs.bkg.bund.de/root_ftp/NTRIP/streams/streamlist_world-wide.htm
http://www.epncb.oma.be/_networkdata/data_access/real_time/map.php

You'll need a GPS receiver capable of receiving and incorporating the RTCM correction data into its location solution. You’ll also need a source of RTCM correction data. This usually comes from an internet connection or a long distance radio capable of approximately 500 bytes per second. LoRa and LTE-CAT M1 are superb choices for this backhaul.

Once it's all setup and working, the rover GPS module will output normal NMEA sentences but with really accurate lat and long. To be clear, it’s not 1cm precision; it's 1cm accuracy. The precision is 0.1mm!

1 cm accuracy is possible with lower cost receivers (such as the NEO-M8T) by capturing raw streams from the GPS satellites and then post processing the logs with an open source program called RTKLIB. This is handy for applications like aerial photography and agricultural inspection were alignment is important after the fact. It's also possible to tether a lower cost receiver (such as the NEO-M8T) to a laptop and run RTKLIB in unison and achieve real time solutions but this is a rather large, power hungry setup that is not ideal for embedded mobile applications. In these tutorials we will be focusing on real time (RTK) capable receivers.