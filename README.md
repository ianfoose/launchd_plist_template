# launchd_plist_template

A plist template for getting started with launchd jobs.  This template provides a skelton structure for a launchd job.  

## Setup

Save your file in the ```/Library/LaunchAgents``` directory.  

## Installing

Type the follwing into terminal

### To Load

```launchctl load ~/Library/LaunchAgents/<name_of_plist>```

### To Unload

```launchctl load ~/Library/LaunchAgents/<name_of_plist>```

## Running

Type the follwing into terminal
 
The ```<service_name>``` is the name of the plist except for the file extension, so exclude '.plist'. 

### To Start

```launchctl start <service_name>```

### To Stop

```launchctl stop <service_name>```

## More Info

More info can be found at https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/CreatingLaunchdJobs.html
