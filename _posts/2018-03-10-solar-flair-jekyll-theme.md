---
layout: post
title: "Solar Flair | Jekyll Theme Gem"
date: "2018-03-10 14:17:07 -0400"
---

Off and on throughout the last few months I've put time into developing a highly optmized jekyll theme where the styles are bound to config variables. 

Using SCSS, Bootstrap 4, and Jekyll I've setup [Solar Flair](https://github.com/ndkline/solar-flair). At [Solar Innovations](https://solarinnovations.com){:target="_blank"}, I did my first iteration of testing the theme in a live environment on [Greenhouse Planning](https://greenhouse.planning.solar){:target="_blank"} and [Planning Solar](https://planning.solar){:target="_blank"}. This being a success, I started converting the theme into a [Ruby Gem](https://rubygems.org/gems/solar-flair).

A user can specify whether the whole site, or specified pages, are rendered using a branded color. For example, Solar Innovations uses orange with its line of glass structures. Therefore, glass structure pages can be specified to render using orange instead of the brand's primary green color. 

Future iterations of this project will support custom colors through `_config.yml` settings but for now it only support green, orange, blue, purple, and grey. 