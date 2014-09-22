ConduitOS
=========

ConduitOS is an application conduit. It enhances existing web applications by presenting them through a unified UI, and exposing several cross-application communication APIs to them.

The implementation details are still being ironed out, however I know that the project is feasible and have tested a proof of concept for how it will work code-wise.

How it will work:

- ConduitOS adds a unified toolbar across all applications added to it
- Toolbar will enable quick access to unified notifications, search, and contacts across all applications
- ConduitOS will provide unified login to any supported application by acting as an oauth provider
- Applications can either be hosted by a 3rd party on an external domain/datacenter, or hosted internally on a subdomain

Future plans:

- Application manager allowing easy distributed hosting of applications with docker containers. It would fully integrate as an application inside of ConduitOS as well
- Triggers so events in applications could trigger events in other applications (could be cool when combined with home automation)
- Device capability unification: applications can use capabilities from any registered device (eg location/notifications/sensors)
- Possibly service autodiscovery of some kind?
