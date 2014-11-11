# Exe Buildpack #

This buildpack executes "run.bat" from the root of your application.

## Environment Variables ##

The following are a list of useful environment variables available in the context of your start script.

- TEMP=**[absolute path to your temp folder]**
- TMP=**[same as TEMP]**
- HOME=**[absolute path to your app directory]**
- VCAP_APPLICATION=**[JSON with info about your application - read more [here](http://docs.cloudfoundry.com/docs/using/deploying-apps/environment-variable.html#VCAP_APPLICATION)]**
- VCAP_SERVICES=**[JSON with info about services bound to your app - read more [here](http://docs.cloudfoundry.com/docs/using/deploying-apps/environment-variable.html#VCAP_SERVICES)]]**
- VCAP_APP_HOST=**[IP address of the host machine]**
- VCAP_APP_PORT=**[the port you have to start the webserver on]**
- PORT=**[same as VCAP_APP_PORT]**
- VCAP_WINDOWS_USER=**[name of the windows user running the app]**
- VCAP_WINDOWS_USER_PASSWORD=**[password of the windows user]**
 
