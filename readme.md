# esp8266_deauther_frontend

This is a new user friendly frontend based on esp8266_deauther.

## Feature/task list:
1. [ ] Have list of known users - save to EEPROM.
2. [ ] Assign MAC address to known users - save to EEPROM.
3. [ ] Have button to deauthenticate known users wifi connections.
4. [ ] Have button to allow known users wifi connections.

## Instructions

Clone https://github.com/spacehuhn/esp8266_deauther.git for the original code, then:

**1** Use a minifier (e.g. http://htmlcompressor.com/compressor/) to get your files as small as possible  
**2** Open converter.html  
**3** Paste the code in the left textfield  
**4** Press Convert  
**5** Copy the results from the right textfield  
**6** Go to data.h and replace the array of the changed file with the copied bytes  

**Now compile and upload the new sketch**
