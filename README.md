# ANTTOOL-and-RTKLIB
Hello,

I am a beginner in using GNSS devices and I am trying to evaluate some low-cost GNSS for applications in precision farming. I have some problems 
when using RTKLIB 2.4.3 b33 and ANTTOOL 2.1 when post-processing raw data logged from GNSS receivers as below.

1) The output when converting RTCM3 raw data of base station to RINEX by RTKLIB/RTKCONV, is only .obs file, no nav file. 
The output has both obs and nav file for ubx raw data.
2) when I run the command "testant" of ANTTOOL in Matlab "2019b with obs+nav data of rover (converted to RINEX 2.12 from ubx raw data) and 
obs data of base station (converted to RINEX 2.1 from RTMC3 raw data), "reference antenna position error" occurred.
3) I do not know how to measure signal strength of GNSS receiver by RTKLIB
4) I do not know how to measure "time to first fix" by RTKNAVI or RNX2RTKP
 if any one master in RTKLIB and experienced similar problems, plase advise me how to solve them. 
 
 Many thanks.
