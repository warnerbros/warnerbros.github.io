# Overview
NextGen Extras is a whole new way to watch media. Users can experience synced features, get exclusive content,  discover scene locations, share clips with friends, and more. This library facilitates the deployment of the NextGen Extras in an implementor's iOS & Android app.

## Cross Platform Extras
http://movielabs.com/cpe/index.html 

# CPE Manifest

## XML Files
A CPE package consists of manifest file(s) which power the Cross Platform Extras (aka NextGen Extras) experience. Each CPE enabled title has 3 associated XML files which are based on the following MovieLabs specs:

- http://www.movielabs.com/cpe/manifest/
    - This provides the data for the overall experience including the timed events.  
- http://www.movielabs.com/cpe/appdata/
    - This essentially is a catch-all when adding features outside CPE Manifest's default support. It's currently mainly being used for scene location data.

- http://www.movielabs.com/cpe/appearance/
    - This configures experience UI elements including safe zones, colors, etc. 


The library will take a valid CPE Manifest v1.5 IP1 file and will render the CPE/NextGen Extras interface. 
 

## Open-Source Mobile Libraries
We also have an open-source library which helps power this experience. The library is released under an Apache 2.0 license.


### iOS:
- [Native data binding object generator from the CPE manifest spec](https://github.com/warnerbros/cpe-manifest-ios-data)
- [iOS Swift codebase which runs the CPE Experience](https://github.com/warnerbros/cpe-manifest-ios-experience)


### Android:
- [Android codebase](https://github.com/warnerbros/cpe-manifest-android-experience)
 
