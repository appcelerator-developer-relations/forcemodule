# salesforce Module

## Description

Access and use the Salesforce REST API
http://www.salesforce.com/us/developer/docs/api_rest/index.htm

## Accessing the salesforce Module

To access this module from JavaScript, you would do the following:

	var salesforce = require("com.salesforce");

The salesforce variable is a reference to the Module object.	

## Reference

### ForceOAuth (property)
This property/namespace holds the API calls for the module

### ForceOAuth.resources() (method)
Lists available resources for the specified API version, including resource name and URI.

### ForceOAuth.versions() (method)
Lists summary information about each Salesforce.com version currently available, including the version, label, and a link to each version's root.

### ForceOAuth.refreshAccessToken() (method)

### ForceOAuth.setRefreshToken() (method)

### ForceOAuth.describeGlobal() (method)
Lists the available objects and their metadata for your organization's data.

### ForceOAuth.metadata() (method)
Describes the individual metadata for the specified object. For example, this can be used to retrieve the metadata for the Account object or post a new Account object.

### ForceOAuth.describe() (method)
Completely describes the individual metadata at all levels for the specified object. For example, this can be used to retrieve the fields, URLs, and child relationships for the Account object.

### ForceOAuth.create() (method)
Creates new records.

### ForceOAuth.retrieve() (method)
Retrieves records based on values of the record.

### ForceOAuth.update() (method)
Updates existing records (upserts records) based on the value of a specified external ID field. 

### ForceOAuth.del() (method)
Deletes records.

### ForceOAuth.query() (method)
Execute a SOQL query that returns all the results in a single response, or if needed, returns part of the results and an identifier used to retrieve the remaining results.

### ForceOAuth.search() (method)
Execute the specified SOSL search. The search string, in this example {test}, must be URL-encoded.

### ForceOAuth.recordFeed() (method)
The feed of the specified record, which could be a group, person, object or file.

### ForceOAuth.newsFeed() (method)
The news feed of the current user. Includes feed items from all groups the current user either owns or is a member of, as well as all files, records, and all users the current user follows. You can also use this resource to add feed-items. 

### ForceOAuth.profileFeed() (method)
Feed of all actions by the current, logged-in user on all records that can be tracked in a feed. This is different than the news feed, which returns everything in a user's feed, including posts, status updates, group updates, and record updates. Also used to add feed items.

## Author

TODO: Enter your author name, email and other contact
details you want to share here. 

## License

See LICENSE file for details
