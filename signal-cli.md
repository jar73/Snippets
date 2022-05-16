## Register number
    signal-cli -u +41xxx register 
Captcha requested, paste data, repeat register command add --captch <captacha redirekt data>

## Verify register
signal-cli -u +41xxx verify <SMS code>

## Message to other phone
signal-cli -u +41xxx send -m "Text" +41xxx --attachment /tmp/img.jpg

## Create a group, add a number and get groups ID in return:

signal-cli -u +41xxx updateGroup -n "JoPe's Smarthome" -m +41yyyy +41zzz
      
      
