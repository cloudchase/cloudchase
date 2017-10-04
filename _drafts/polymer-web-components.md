---
layout: post
title:  "Polymer web-components"
date:   2017-01-05 12:00:00 +0000
catagories: Dev
Tags: [web components fed]
addPostCSS: true
---

## Polymer web-components

### What are web-components
Just what you have been looking for from the moment you created your first HTML template whether it was moustache, handlebars, kit, angular, react, riot or even your own custom system (oh yes you did, well at least I did).

So perhaps your first port of call if you have never heard of web-components or created on might be http://webcomponents.org/. Here you will find not only the specs but some much more human friendly articles on the four pilars of web-components.

- Custom elements - http://webcomponents.org/articles/introduction-to-shadow-dom/
- HTML Imports - http://webcomponents.org/articles/introduction-to-html-imports/
- Templates - http://webcomponents.org/articles/introduction-to-template-element/
- Shadow DOM (or Local DOM) - http://webcomponents.org/articles/introduction-to-shadow-dom/

The spec has eveloved and http://webcomponents.org/articles/custom-elements-v1/ is essential if you are looking at a new project / polymer 1.7 or 2.

As well as these resoruces you will also find useful information on browser support and libraries. It is also the owner of the webcomponents.js the polyfill used to allow you to use web components today.

### What is Polymer
Polymer is a layer on top of web-components that allows you to make go beyond creating re-usable HTML fragments. It adds data binding and other useful facilities to allow you to turn your web-components into something closer to a native element.

### Polymer 1

#### Polymer Example Component
Polymer has a nice example <iron-toggle> https://www.polymer-project.org/1.0/start/first-element/intro which will help you build your first element. I'm gonig to press on and assume that you have done that already. If not hop to it or grab the completed source.

#### Polymer Example Compoent - Remove dependency on Iron Icon

#### POlymer Example Component - What they didn't tell you

#### Polymer Example App

Includes library use

#### Polymer Example App - Reduced Dependency


# Questions to answer
How do I deploy a library
How do I deploy an app
How do I reduce html requests? Vulcanize.
Lifecycle



# Polyserve
## Good
Can use canonical path when developing your components.

## Vulcanize
Use to build your apps, but not your components?

## Bad
No source map support https://github.com/PolymerLabs/polybuild/issues/26
