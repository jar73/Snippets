Openhab

## Clear cache
Stop OH if it is running.

Delete the /var/lib/openhab2/cache and /var/lib/openhab2/tmp folders. For manual installations these folders are in your OH home folder under userdata.

Start OH.

Watch openhab.log for errors, test if the problems persist. If so, search the forum and post a new thread if you do not find a solution. Log into the karaf console and enable debug logging to get more information about the errors.


