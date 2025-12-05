14030621 - config file 
14030627 - display
14030627 - interrupt added - the interrupt vaues stored in variables press
14030627 - separate get and send data as individual files
14030708 - wifi, wifi manager, littleFS, web server, all aded as individual files.
14030713 - JSON send data
14030714 - save data to SD




 targets 14030718->
1- adding display shows for different situations - create list of errors

	wifi not connected: error 1
	wifi connected but ntp not connected: error 2
	wifi connected bu internet not connected: error 3
	wifi connected but thingsboard not connected: error 4

	wifi connected, ntp success, net ok and data send successfully -> first show wifi ip and then show the current time

2- add a button when pushed for 7 secs, device go to access mode and get new Wifi ssid and pass
3- optimize WiFi
4- WD

bug: 1- when net is disconnected, it takes time to show publish successful in the serial monitor
     2- when net is disconnected, the clock locks and no error shown on display.