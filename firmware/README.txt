Files: Code for esp
       Code for mcu

Include the program code written for micro controllers in code file inside, used pin GPIO0 to give out the signal. One of the above two micocontrollers can be used based on the varation you select as ESP01 s flash size might not be enough to upload the certificate.

The data file inside should include the certificate generated, that connect to the MQTT broker hosted on HiveMQ.

Initially,
	Generate certtificate from following the documentation given by HiveMQ
	Upload that certificate to the micro controller using ESP8299 LittleFS Data Upload(to the flash memory)
	Then only upload code 

