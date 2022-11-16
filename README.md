# Particle_background
>Simple animation with hexagon shaped elements that move in background of element.

> Live demo [_here_](https://htmlpreview.github.io/?https://github.com/WojcioTrue/particle_background/blob/457ecf75108137aa90e335ad350091938274fd84/index.html).

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Screenshots](#screenshots)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Acknowledgements](#acknowledgements)


## General Information
- Smooth animation for background particles.
- Getting better understanding how many elements can be generated, animated and modified.



## Technologies Used
- JavaScript
- HTML
- CSS3
- Gulp


## Features
There are some values for plugin that you can change. All these values (except data-el-color), are interpreted as pixel values.
- **Setting left margin of element**

`data-left-margin-start="20" (default value=50)`

If nothing set, element will be generated in the left side of window, with left margin set between 0 to 50px (value generated randomly).
- **setting maximum size of element**

`data-min-dimension="5" (default value=5)`

Minimal width and height of particle.
- **setting minimum size of element**

`data-max-dimension="5" (default value=5)`

Maximum width and height of particle.
- **setting color of element**

`data-el-color="gold", (no value will return black)`

- **mobile friendly**
- **RWD**



## Screenshot
![alt text](/src/img/screen_shot.png)

## Setup
**How to install**
Download folders from 'dist' folder.
Copy them to your website project.
Paste css href in "head" element e.g.

    <link rel="stylesheet" href="dist/css/style.css">
Add script before </body> tag and initiate e.g.

    <script src ="dist/js/particles.js"></script>
    <script>practiceInit();</script>

## Usage
After download and adding to your website, you need to choose which element should have this animated background.
When you choosed element, just ad `id="animation"`.

**e.g.**

	<div id="animation"></div>
**e.g. with changed default values**

Here element will be generated with:
- margin-left with value between 0px and 100px
- minimal height of 4px
- maximum height of 15px
- color of element will be set to "gold"
<br/>

	<div id="animation" 
		data-left-margin-start="100" 
		data-min-dimension="4"       
		data-max-dimension="15" 
		data-el-color="gold">
	</div>

## Project Status
Project is: _in progress_


## Room for Improvement

Room for improvement:
- make particles float from different sides(top to bottom, left to right etc.)
- change shape of particle
- add feature to change z-index of particles


## Acknowledgements

- This project was inspired by select menu in game 'apex legends'




