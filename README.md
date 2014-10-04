ConduitOS
=========

ConduitOS is an application conduit. It enhances existing web applications by presenting them through a unified UI, and exposing several cross-application communication APIs to them.

General vision
--------------

The long-term goal is to create a rich platform that can make smart decisions relating to your daily life. The platform would be flexible enough to accomidate applications for connected devices (internet-of-things), communication, transportation, and more. ConduitOS-enabled applications will be far more inteligent than they would be on their own, and ConduitOS increases the utility of all applications in the system.

ConduitOS doesn't force you to write applications differently. Think of adding ConduitOS integration analagous to adding Facebook or Twitter integration to an existing web application; you can still write your application using whatever framework or libraries you want, and it can still work in isolation from the platform.

From a privacy standpoint, it's important that something like this isn't controlled by a single company and can be easily audited and installed by anybody.

How it will work
----------------

- The first 1.0 release will focus on building infrastructure to expose APIs to applications, and the UI
- ConduitOS adds a unified toolbar across all applications added to it
- Toolbar will enable quick access to unified notifications, search, and contacts across all applications
- ConduitOS will provide unified login to any supported application by acting as an oauth provider
- Applications can either be hosted by a 3rd party on an external domain/datacenter, or hosted internally on a subdomain

Future plans
------------

- Application manager allowing easy distributed hosting of applications with docker containers
  - This application manager would fully integrate as an application inside of ConduitOS as well, allowing you to administrate applications from a web interface
- Triggers so events in applications could trigger events in other applications (could be cool when combined with home automation)
- Device capability unification: applications can use capabilities from any registered device (eg location/notifications/sensors)
- Possibly service autodiscovery of some kind?
