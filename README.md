# large-drive
Commands to handle large drives using https://github.com/odeke-em/drive

# TODO
* make sure the input to diff is sorted
* try out printing the exit code onerror to see why the path is being added to the done list
* convert meta into large_drive prefix
* use an sqlite database instead of a file
* use different columns to indicate the date at which each path was listed/pulled/pushed
* cronjob that constantly checks the status of all files
* report table that shows differences between the remot and the local
* this report table could have a column indicating what action is expected to be done with the given path
* the .driveignore could be generated out of a table.
* there could be a web interface that shows options to use all these tables