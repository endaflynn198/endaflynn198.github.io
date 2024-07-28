---
layout: post
title: Shiny App for HDI Indicators
date: 2024-07-28 00:00:00
description: Building a Shiny App to analyse UN Human Development Indicators
toc: 
  sidebar: true 
  toc_sticky: true 
  # add toc levels
  toc_float:
    collapsed: false
tags: update
categories: code r shiny
featured: false
---

# Introduction to Shiny
Shiny is an R package that makes it easy to build interactive web apps straight from R. You can host standalone apps on a webpage or embed them in R Markdown documents, Quarto documents, or build dashboards. You can also extend your Shiny apps with CSS themes, htmlwidgets, and JavaScript actions.

There is an excellent [gallery](https://shiny.posit.co/r/gallery/) demonstrating the capabilities of Shiny which I highly recommend checking out.

# The App
The app is designed to be simple and easy to use, with a clean and modern design.

Feel free to check out the code and make modifications for your own Shiny apps. I have also included a video demonstration of the app below so you can see it in action and get a sense of the functionality Shiny provides.

<div class="row mt-1">
    <div class="col-sm mt-1 mt-md-0">
        <video class="img-fluid rounded z-depth-1" controls>
            <source src="{{ site.baseurl }}/assets/video/2024-07-26 11-51-20.mkv" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Note the array of options available to the user in the sidebar, and the use of toggles, lists, and select inputs to make the app more user-friendly and reactive.
</div>

## Code
As usual, I have created a [GitHub repository](https://github.com/endaflynn198/hdi_shiny_app) for this project. The app is designed to allow the user to select a country and analyse their Human Development Indicators data. The app is built using the `shiny` package and the `HDI_summary` package I developed previously.

# An Issue with Shiny - Samey Aesthetics
Shiny has options for theming (the application demonstrated in the video makes use of the `sandstone` theme from `shinythemes`) , but despite this many applications end up looking very similar. You likely noticed this immediately if you visited the gallery. 

This is because Shiny is built on Bootstrap, which is a very popular CSS framework. This means that many Shiny apps look like Bootstrap apps, which is not a bad thing, but it does mean that they can look a bit generic and outdated.

## Alternatives for More Attractive Shiny Apps
If you want to make your Shiny apps look more modern and unique, you have a few options:
- `shiny.fluent`: This is a package that provides a fluent design theme for Shiny apps. Fluent design is a design language developed by Microsoft that is used in Windows 10 and other Microsoft products. It is a modern, clean, and attractive design that can make your Shiny apps look more professional.

- `shiny.semantic`: This is a package that provides a semantic UI theme for Shiny apps. Semantic UI is a popular CSS framework that is known for its clean, modern design. It is a good choice if you want to make your Shiny apps look more modern and unique.

There are also other options for theming Shiny apps which are worth exploring, but due to the fact that they add additional dependencies and complexity, I would advise picking one that you like and sticking with it to build familiarity with the syntax and options available.

