
![Puzzle ITC Logo](lib/img/puzzle_tagline_bg_rgb.svg)
<!-- .slide: class="master01" -->

<!-- section -->
#Meteor
<!-- .slide: class="master04" -->

<!-- section -->
#Inhalt
Meteor?

Demo

Where to go from here?

<!-- slide class="master05"-->

<!-- section -->
#Meteor?
Meteor is a complete open source <b>platform</b>
for building web and mobile apps
in pure JavaScript. (https://www.meteor.com/)

<!-- slide -->
## Architektur  
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

<!-- slide -->
## Application Outline
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
## Creating a Collection
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
## Add new Pizzas

Full Stack Reactivity

Latency Compensation

<!-- slide -->
## Add User Authentication

Simplicity Equals Productivity

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
#Where to go from here?

<!-- slide -->
##There's much more to know on...
Sessions

Reactive Datasources and Variables

Meteor Methods

Packages (https://atmospherejs.com/)

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

Discover Meteor (https://www.discovermeteor.com  http://de.discovermeteor.com/)
Meteor in Action (EAP)

<!-- slide -->
##Merci viu mau!


 <!-- section -->
 #Structure with tags
 Manage your sections (horizontal) <br>and slides (vertical) with tags:


 ```
 <@!-- section -->
 # First section, first slide (horizontal)
 <@!-- slide -->
 ## First section, second slide (vertical)

 <@!-- section -->
 # Second section, first slide (horizontal)
 ```
 <small>(remove the @)</small>

 <!-- slide -->
 ##Make it prettier with classes
 Give your slide a background color by adding a css class:

 * master01: dark blue
 * master02: blue
 * master03: light blue
 * master04: turquoise
 * master05: green

 <!-- slide -->
 Just add this tag under your slides:
 ```
 <@!-- section -->
 # First section, first slide with blue background
 <@!-- .slide: class="master01" -->
 ```
 <small>(remove the @)</small>
