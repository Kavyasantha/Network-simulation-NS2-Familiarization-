KAVYA SANTHA KUMAR

BOYU LI

------------------------------------------------------------------------------------------------------------------------
Description:

We need to build the following

      a) Two routers (R1, R2) connected with a 1 Mbps link and 5ms of latency.
   
      b) Two senders (src1, src2) connected to R1 with 10 Mbps links.
   
      c) Two receivers (rcv1, rcv2) connected to R2 with 10 Mbps links.
   
      d) Application sender is FTP over TCP.

cases:

Case 1:

      a) src1-R1 and R2-rcv1 end-2-end delay = 5 ms
   
      b) src2-R1 and R2-rcv2 end-2-end delay = 12.5 ms
   
Case 2:

      a) src1-R1 and R2-rcv1 end-2-end delay = 5 ms
   
      b) src2-R1 and R2-rcv2 end-2-end delay = 20 ms
   
Case 3:

      a) src1-R1 and R2-rcv1 end-2-end delay = 5 ms
   
      b) src2-R1 and R2-rcv2 end-2-end delay = 27.5 ms

--------------------------------------------------------------------------------------------------------------------------

Directory Structure:

      ns.tcl - TCL Script

--------------------------------------------------------------------------------------------------------------------------

Run the file:

      ns ns.tcl <TCP_flavor> <case_no>
      E.g.
            ns ns.tcl SACK 1
            ns ns.tcl VEGAS 2
      
