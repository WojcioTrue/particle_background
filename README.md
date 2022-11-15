#  Particle_background plugin.

### <a href="https://htmlpreview.github.io/?https://github.com/WojcioTrue/particle_background/blob/457ecf75108137aa90e335ad350091938274fd84/index.html" target="_blank">Click me for live preview</a>

**Description:**

Simple animation with hexagon shaped elements that move in background of  element.

**How to add Particle_background to project?** 

1. Download folders from 'dist' folder.
2. Copy them to your website project.
3. Paste css href in "head" element e.g.

	`<link rel="stylesheet" href="dist/css/style.css">`

4. Add script and initiate e.g.

	`<script src ="dist/js/particles.js"></script>`

	`<script>practiceInit();</script>`


### How use it in project?

After download and adding to your website, you need to chose which element should have this background.

after you choosed element, just ad id="animation".

e.g.

	<div id="animation"></div>

### Changing default values.

There are some values for plugin that you can change. All these values (except data-el-color), are interpreted as pixel values.

#### data-left-margin-start (default value=50):
If nothing set, element will be generated in the left side of window, with left margin set between 0 and 50 px (value generated randomly).


#### data-min-dimension (default value=5):
Minimal width and height of particle.

#### data-max-dimension (default value=20):
Maximum width and height of particle.

Size of particle is generated randomly between this two values.

#### data-el-color (default value="undefined", will return black).

e.g.

	<div 
	 id="animation"

	 data-left-margin-start="100" 

	 data-min-dimension="4"

	 data-max-dimension="15" 

	 data-el-color="gold">

	</div>