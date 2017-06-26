# Project Codename: an OpenWhisk Alexa Skill

This is a simple Alexa skill to show how a simple javascript function can be packaged with its dependencies and deployed to openwhisk.  To use it, deploy the action (there's a build script to help) and then set its web endpoint to be the "HTTPS" option in the Alexa Developer Console configuration for your action.

This optionally uses Redis, add a parameter called `redisURL`.  The `deploy.sh` script expects a file called `params.js` which must contain a valid object even if the redisURL isn't configured

## Further Reading

I wrote a blog post about this skill which has more information and links:  https://lornajane.net/posts/2017/alexa-project-name-generator-on-openwhisk
