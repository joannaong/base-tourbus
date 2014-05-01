# Team Toubus: web structure

PROJECT/
|
|-- src
|		|--	assets/								# CDN hosted assets
|		|		|
|		|		|-- vid/
|		|		|		|-- *.mp4
|		|		|		|-- *.webm
|		|		|-- img/
|		|		|		|-- *.jpg
|		|		|		|-- *.png
|		|		|		|-- *.svg
|		|
|		|--	components/						# components
|		|		|
|		|		|-- button/      
|		|		|   |-- button.jade
|		|		|   |-- button.sass
|		|		|   |-- button.js
|		|		|
|		|		|-- menu/             
|		|		|   |-- menu.jade
|		|		|   |-- menu.sass
|		|		|   |-- menu.js
|		|
|		|--	pages/
|		|		|
|		|		|-- index/
|		|		|		|-- index.jade
|		|		|		|-- index.sass
|		|		|		|-- index.js
|		|		|
|		|		|-- about/
|		|		|		|-- about.jade
|		|		|		|-- about.sass
|		|		|		|-- about.js
|		|
|		|--	core/
|		|		|
|		|		|--
|
`-- Gruntfile.js
`-- package.json
`-- bower.json
`-- README.md


## Usage
- npm install
- bower install
- run 'grunt' in command line to develop
