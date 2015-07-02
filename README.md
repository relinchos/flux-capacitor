![Flux-capacitor Logo](http://relinchos.com/app/assets/img/brand_logo/flux_capacitor.svg)



 Flux-capacitor is a time saver. It is an scaffolding for webapps that contains a client side admin app made in AngularJS and a server side app made in Strongloop's Loopback framework (express + nodeJS). 

## DISCLAIMER

#### The project is not even in alpha version by the moment so we don't recommend it for production ussage. We've already made some real life tests in small projects with it and it worked fine, but nevermind, right now the code is too messy and not well maintanable and worst of all we haven't started yet to make a proper documentation.  



## THE APP(S)

As we told you flux-capacitor consists in two separate apps:

###The adminApp
This is administrative app for managing users, roles, data models, etc.

Github Repo:
- https://github.com/relinchos/flux-capacitor-adminapp


###The serverApp

Github Repo:
- https://github.com/relinchos/flux-capacitor-serverapp


**Demo at heroku:**
- https://flux-capacitor-adminapp.herokuapp.com/


> **Be patience:** Please notice that both demo apps, client and server side, are hosted in free heroku tiers so if you enter it will take a little time to start the dynos. Furthermore, the mongodb connected to the backend is hosted in a free sandbox at compose.io which is is horrible slow too. 


## GOALS

We are trying to bring together a team of collaborators and make an schedule to start a serious developemnet road. Our main goal is to tide up the messy code we have now in both apps to start them in alpha version.


 Some goals we will be persuing then are:
 
 - Creating a YEOMAN GENERATOR CLI for both apps that wraps and group the different clis form the different compoennets used under a common set of commands.
 - Start documentation!
 - Tidying up the form automatization tool.
 - Analize File storage strategies.
 - Some improvements to the loopback framework itself.
 - Finish and connect some cool front-end directives we've made and that are sitting there but half baked :(
 
