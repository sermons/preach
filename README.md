# Acts 28:23-31, "The Fragrant Gospel"

[![Travis-CI build status](https://travis-ci.org/seanho00/fragrant-gospel.svg)](https://travis-ci.org/seanho00/fragrant-gospel)
[![Node dependencies](https://david-dm.org/seanho00/fragrant-gospel.svg)](https://david-dm.org/seanho00/fragrant-gospel)
[![Node dev status](https://david-dm.org/seanho00/fragrant-gospel/dev-status.svg)](https://david-dm.org/seanho00/fragrant-gospel#info=devDependencies)

Template presentation using Reveal.js

First draft generated by Yeoman and
[generator-reveal](https://github.com/slara/generator-reveal)

I tweaked done Reveal.js options, added style sheet, etc., and a Travis config to deploy to Github Pages.

## Usage
* Fork this project
* Use your own deploy key:
	* ssh-keygen
* Slide content goes in `slides`, in particular, `slides/index.md`.
* Static assets (CSS, JS, images, etc) go in `static`, the grunt task will copy this dir as-is to the deploy directory.
