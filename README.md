*Considerations*

* Custom criteria entities (rows) can contain up to 1,000 recommended items (columns).

* Custom criteria updates are by default “cumulative.” New key-value pairs specified in the CSV upload file overwrite existing key-value pairs. Existing key-value pairs that do not have keys specified in the CSV upload are still available for delivery and expire in 31 days from the time they are last uploaded as part of the CSV file.

* Contact Client Care to enable the setting to discard the existing results that are not included in the next CSV upload. If this setting is enabled, only the keys present in the custom CSV feed file are available for delivery. This setting applies to all custom criteria.

* Custom criteria feeds update once every 24 hours.

* You can see the upload and sync status of your custom criteria upload for each criteria on the Recommendations > Criteria page. You can also see the status in the Edit dialog box when editing custom criteria.

* The flow for an error-free upload should be Scheduled > Downloading Feed File > Importing > Successful.

*The following are possible error messages you might receive if Target encounters a problem with the upload:*

* Unknown Error: Indicates an internal technical error.
* Parsing Error: There is likely an issue with the feed file format. Correct the file format and re-save the algorithm, which restarts the file download process.
* Server Not Found: Provide an IP or Host Name that is visible on the internet.
* Credentials Error: Provide a valid user and password for an active account on the server.
* Directory Not Found: Provide a directory that exists on the server.
* File Not Found: Provide the name of a file that exists on the server in the directory indicated.
