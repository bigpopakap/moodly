Moodly
-----------------

[Moodly]([touchy-feel-production-url]) is an website that lets you quickly log your mood. When you have thoughts or feelings to log, just quickly jot them down. You can then analyze trends and process your general mood. More information can be found on [the  website][touchy-feel-production-url].

# Development

Moodly is developed in a git monorepo so all client, server and storage changes can move in lock-step. The repo is stored on Github, under the project name [bigpopakap/moodly][git-url].

For more information about these three components, refer to each README:
* [Client][client-readme]
* [Server][server-readme]
* [Storage][storage-readme]

# Deployment

Moodly is deployed with Heroku, under the project name [bigpopakap/moodly][heroku-url].

The app runs in a staging and production environment:
* [Staging][staging-url]
* [Production][production-url]

Staging is deployed automatically with all merged code. Production is deployed manually, but must pass CI and be deployed to staging first.

# Tests and CI



# Running and testing locally






[staging-url]: http://some.link
[production-url]: http://some.link
[git-url]: http://some.link
[heroku-url]: http://some.link

[client-readme]: ./client/README.md
[server-readme]: ./server/README.md
[storage-readme]: ./storage/README.md