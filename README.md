# Fauna Labs

This repository contains unofficial patterns, sample code, or tools to help developers build more effectively with [Fauna][fauna]. All [Fauna Labs][fauna-labs] repositories are provided “as-is” and without support. By using this repository or its contents, you agree that this repository may never be officially supported and moved to the [Fauna organization][fauna-organization].

## Set up the project

...

### Set up the database

To set up the project, go to the [FaunaDB Dashboard](https://dashboard.fauna.com/) and sign up. 

<img src="readme/sign_up.png?raw=true" width="600">

Once you are in the dashboard, click on New Database, fill in a name, select your region group, click Save.

> Remember the Region Group value for later; connections to the database need to be configured with the corresponding endpoint.  If this is a child database, the Region Group will already be set to match the parent database.  

<img src="readme/new_database.png?raw=true" width="600">
<img src="readme/new_database2a.png?raw=true" width="600">
<img src="readme/new_database2b.png?raw=true" width="600">

You should now be on the "Overview" page of your new database.

...

### Configure the connection for your Region Group
When you created your database, you specified a Region Group for it to hosted on.  

Refer to the [Region Groups](https://docs.fauna.com/fauna/current/api/fql/region_groups#how-to-use-region-groups) documentation to obtain the correct endpoint for your Region Group.

Reference the [Connections](https://docs.fauna.com/fauna/current/drivers/connections.html) documentation for how to correctly set the endpoint for your specific driver.


[fauna]: https://www.fauna.com/
[fauna-labs]: https://github.com/fauna-labs
[fauna-organization]: https://github.com/fauna

