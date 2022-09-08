# Windows Command line infos
* This repo contains tricks usefull commands for windows cmd
## Tip 1
    driverquery
   
   to view the list of drivers
## Tip 2
    powercfg /batteryreport
  
   run as administrator required,
   to generate battery report
## Tip 3
    sfc /scannow
  
  run as administrator required,
  if computer facing an issue use this
## Tip 4

    "insert txt">"filename.txt"
  
  inserting text directly to new txtfile
  
## Tip 5
    type textfile.txt
   
   to display contents of text file without opening it
## Tip 6
	
   to get wifi password of connected network

   step 1: **netsh wlan show profile**
   
   step 2: **netsh wlan show profile Wi-Fi name key=clear**

   step 3: **look for key content that is the pass word**

## Tip 7
    dir *.txt
   
   to list directory of specific files
## Tip 8
    explorer .	
   to open current directory

## tip 9
     systeminfo
     
   to get system information
## Tip 10
     netsh wlan show network
     
   gives detail about current wifi network
## Tip 11
      net user
   to get user of the computer
## Tip 12
      netsh wlan show all 
      
   gives details about port and other stuff including wifi adapter details and connected network.	
## Tip 13
	taskmgr
    
   open taskmanager
## Tip 14
	find window product key
 	
    wmic path softwarelicensingservice get OA3xOriginalProductKey
