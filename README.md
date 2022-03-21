# Mind Professionals codebase

Services should not really know about each, except for the services that need to use the database service.

The only services that should know about each other are any service and the database service, and the api gateway service and any service.

Services that need to cross-reference are most likely wrongly planned. For example, the authentication service should not know about the profile service and any of it's processes. In retrieving a profile, the authentication service only needs to know whether a certain user can view a profile, and if so, it should alert the api gateway about this and allow the api gateway to handle the rest of the process.
