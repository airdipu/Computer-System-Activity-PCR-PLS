## Computer-system-activity-PCR
Predict a computer system activity from system performance measures using Principal Component Regression (PCR).

Compactiv dataset

Description:

The Computer Activity dataset is a collection of computer systems activity measures. The data was collected from a Sun Sparcstation 20/712 with 128 Mbytes of memory running in a multi-user university department. The task is to predict de variable usr, the portion of time that cpus run in user mode.


Type 			      Regression    ||    Origin 			    Real_world     ||   Instances 		    8192    ||    Features 	      21            ||    Missing_values 	No


Header:

@relation compactiv


      @attribute Lread real[0.0,1845.0]     ||    @attribute Lwrite real[0.0,575.0]      ||    @attribute Scall real[109.0,12493.0]

      @attribute Sread real[6.0,5318.0]     ||    @attribute Swrite real[7.0,5456.0]     ||    @attribute Fork real[0.0,20.120001]
                      
      @attribute Exec real[0.0,59.560001]   ||    @attribute Rchar real[278.0,2526649.0] ||    @attribute Wchar real[1498.0,1801623.0]
                      
      @attribute Pgout real[0.0,81.440002]  ||    @attribute ppgout real[0.0,184.2]      ||    @attribute Pgfree real[0.0,523.0]
                      
      @attribute Pgscan real[0.0,1237.0]    ||    @attribute Atch real[0.0,211.580002]   ||    @attribute Pgin real[0.0,141.199997]
                      
      @attribute Ppgin real[0.0,292.609985] ||    @attribute Pflt real[0.0,899.799988]   ||    @attribute Vflt real[0.2,1365.0]
                      
      @attribute Runqsz real[1.0,2823.0]    ||    @attribute Freemem real[55.0,12027.0]  ||    @attribute Freeswap real[2.0,2243187.0]
                      
      @attribute Usr real[0.0,99.0] 

@inputs Lread, Lwrite, Scall, Sread, Swrite, Fork, Exec, Rchar, Wchar, Pgout, Ppgout, Pgfree, Pgscan, Atch, Pgin, Ppgin, Pflt, Vflt, Runqsz, Freemem, Freeswap

@outputs Usr
