# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

## Potentially dealbreaking downsides:
* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

## What we really want is:
a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server. Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.

The article discuss: 
1. A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5
2. INTRODUCING HTML5 STORAGE
3. USING HTML5 STORAGE
4. HTML5 STORAGE IN ACTION
5. BEYOND NAMED KEY-VALUE PAIRS: COMPETING VISIONS

the article also recommend futrther readings in :
* HTML5 storage
* Early work by Brad Neuberg et. al. (pre-HTML5)
* Web SQL Database
* IndexedDB