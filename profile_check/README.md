# Checking Steam profile status of participants

## Summary:
* Goal is to automatically post and examine Steam profiles and determine if they are banned or in Private mode.

## profile_check.ipynb:
* Reads in csv file as Pandas Dataframe
* Posts each profile and examines the returned webpage
* Profiles which are banned or in Private mode are then saved to a csv file

## Notes:
* Profile to post is determined during code execution
* Function exists to determine NRIC validity but is currently not in use
* Data in csv file to examine has been modified due to confidential information