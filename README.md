# Logwatch script for Dante SOCKS server

## Install

Put it to **/etc/logwatch**

## Sample run

	$ /usr/sbin/logwatch --service dante
	 
	 ################### Logwatch 7.4.0 (03/01/11) #################### 
	        Processing Initiated: Fri Jan 18 16:27:17 2019
	        Date Range Processed: yesterday
	                              ( 2019-Jan-17 )
	                              Period is day.
	        Detail Level of Output: 0
	        Type of Output/Format: stdout / text
	        Logfiles for Host: xxx.xx.xx
	 ################################################################## 
	 
	 --------------------- Dante Begin ------------------------ 
	
	 Connections Blocked: 1527
	 Connections Passed: 156
	 Connections Timeouted: 174
	 
	 Users Passed:
	    user: 105 Time(s)
	    (anonymous): 3 Time(s)
	    guest: 48 Time(s)
	 
	 ---------------------- Dante End ------------------------- 
	
	 
	 ###################### Logwatch End ######################### 
	
	$
