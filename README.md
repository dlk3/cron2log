# cron2log
This is a python utility script that writes the output and error messages from a commend into a log file.  By default it creates a new cop of the log file exevry time it is run.  It has an option to append the output to the log file instead.  It also has an option that will cause it to simply log any errors that occur and hide them from the entity that called it (crontab, for example.)
