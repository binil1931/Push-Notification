Push-Notification
=================

GCM Push Notification


 Instruction for GCM Push Notification
  
  1)Register your application in Google console "https://console.developers.google.com/"
  <br>
                1.1)  Go to API , enable "Google Cloud Messaging for Android"
            <br>
	  1.2)  Go to credential , click "Create New key" . Then click "server key"
	    <br>
	  1.3) add  Example: 000.000.0.0, then create Api key (This process is for white listing your url)
	    <br>
	  1.4) use the genrated API KEY in the config file 
	    <br>
	  1.5) we will get a sender id from url , paste it to GCMConstant.java file
	   <br> 
  2) upload all the php  file into the serevr
    <br>
  3) Run the application
    <br>
  4) Enjoy  
