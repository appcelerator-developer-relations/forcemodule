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
Creates new records or updates existing records (upserts records) based on the value of a specified external ID field. 

### ForceOAuth.retrieve() (method)

### ForceOAuth.update() (method)

### ForceOAuth.del() (method)

### ForceOAuth.query() (method)

### ForceOAuth.search() (method)

### ForceOAuth.recordFeed() (method)

### ForceOAuth.newsFeed() (method)

### ForceOAuth.profileFeed() (method)


## Author

TODO: Enter your author name, email and other contact
details you want to share here. 

## License

See LICENSE file for details
