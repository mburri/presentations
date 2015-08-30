
![Puzzle ITC Logo](lib/img/puzzle_tagline_bg_rgb.svg)
<!-- .slide: class="master01" -->

<!-- section -->
#Introduction to Meteor
<!-- .slide: class="master04" -->

<!-- section -->
#Agenda
Meteor?

Demo

Additional Information

Conclusion

Learning Resources

<!-- .slide: class="master01" -->

<!-- section -->
#Meteor
<!-- .slide: class="master01" -->
<!-- slide -->
##Meteor?
Meteor is a complete open source <b>platform</b>
for building web and mobile apps
in pure JavaScript. (https://www.meteor.com/)

<!-- slide -->
## Architecture  
![](/assets/meteor-platform.png)

<!-- slide -->
## The seven principles
Data on the Wire <br/>
One Language<br/>
Database Everywhere<br/>
Latency Compensation<br/>
Full Stack Reactivity<br/>
Embrace the Ecosystem<br/>
<b>Simplicity Equals Productivity</b>

<!-- slide -->
## Simplicity Equals Productivity
Installation

Development (& Testing)

CI & CD (Web and Mobile)

Updates in Production

<!-- section -->
#Demo
<!-- .slide: class="master01" -->

<!-- slide -->
## frontend-pizza-voter
Add your Favorite Pizza

Vote for Pizzas

<!-- slide -->
## Installation & Project Creation

Simplicity Equals Productivity

```
curl https://install.meteor.com/ | sh

meteor create frontend-pizza
cd frontend-pizza
meteor
```

<!-- slide -->
## Database setup
Data on the Wire

Database Everywhere

```
Pizzas = new Mongo.Collection('pizzas');
```

<!-- slide -->
## Display Pizzas
Embrace the Ecosystem

One Language

<!-- slide -->
## Add and vote for Pizzas

Full Stack Reactivity

Latency Compensation

<!-- slide -->
## Build and Deploy

Simplicity Equals Productivity

```
meteor deploy frontend-pizza.meteor.com
```

<!-- slide -->
## Going Mobile!

```
meteor install-sdk android
meteor add-platform android
-- simulator
meteor run android
-- device (usb connection)
meteor run android-device  
```

<!-- section -->
#Additional Information
<!-- .slide: class="master01" -->

<!-- slide -->
## Package Management

* https://atmospherejs.com/

```
meteor add <package-name>
meteor remove <package-name>
```

<!-- slide -->
## Some notable Packages
* iron-router
* accounts (core packages)
* email
* moment
* ...

<!-- slide -->
## Security

remove packages:

* autopublish
* insecure

<!-- section -->
# Conclusion
<!-- .slide: class="master01" -->

<!-- slide -->
## Good for...
* Rapid Application Prototyping
* Front-End Developers
* Collaborative Realtime Applications

<!-- slide -->
## Key features
* Full Stack Reactivity
* Simplicity

<!-- slide -->
## Production ready

?


<!-- section -->
#Learning Ressources
<!-- .slide: class="master01" -->

<!-- slide -->
##There's much more to know about...
* Sessions
* Reactive Datasources and Variables
* Meteor Methods

<!-- slide -->
##Official Documentation:

http://docs.meteor.com/#/basic/
http://docs.meteor.com/#/full/

<!-- slide -->
##Tutorials & Blogs

http://info.meteor.com/blog
https://www.discovermeteor.com/blog

http://meteortips.com/first-meteor-tutorial/
http://www.webtempest.com/meteorjs-fromscratch-1

<!-- slide -->
##Books

Discover Meteor

https://www.discovermeteor.com  

http://de.discovermeteor.com

Meteor in Action (EAP)

<!-- slide -->
##This Presentation

Reveal.js Presentation: https://github.com/mburri/presentations/tree/frontend-pizza

Application:
https://github.com/mburri/frontend-pizza-voter


<!-- slide -->
##Merci viu mau!
