# Team Toubus

## Project Structure
```
PROJECT/
|
|_ src
|		|_ assets/                       # CDN hosted assets
|		|		|
|		|		|_ vid/
|		|		|		|_ *.mp4
|		|		|		|_ *.webm
|		|		|_ img/
|		|		|		|_ *.jpg
|		|		|		|_ *.png
|		|		|		|_ *.svg
|		|		|
|		|		|_ data/
|		|
|		|_ components/
|		|		|_ about-header/
|		|		|   |_ about-header.jade
|		|		|   |_ about-header.sass
|		|		|   |_ about-header.js
|		|		|
|		|		|_ about/      
|		|		|   |_ about-content.jade
|		|		|   |_ about-content.sass
|		|		|   |_ about-content.js
|		|
|		|_ global/
|		|		|
|		|		|_ css/
|		|		|   |_ base
|		|		|		|   |_ _helper.sass
|		|		|		|   |_ _reset.sass
|		|		|		|
|		|		|   |_ dependency
|		|		|		|   |_ _mixin.sass
|		|		|		|   |_ _var.sass
|		|		|
|		|		|_ jade/
|		|		|   |_ base
|		|		|		|   |_ base.sass
|		|		|		|   |_ base-header.sass
|		|		|		|   |_ base-footer.sass
|		|		|		|
|		|		|   |_ dependency
|		|		|		|   |_ mixin.jade
|		|
|		|_ pages/
|		|		|
|		|		|_ about/
|		|		|   |_ about.jade
|		|		|   |_ about.sass
|		|		|   |_ about.js
|		|		|
|		|		|_ index/
|		|		|   |_ index.jade
|		|		|   |_ index.sass
|		|		|   |_ index.js
|		|		|
|		|		|_ episodeArchive/
|		|		|   |_ episodeArchive.jade
|		|		|   |_ episodeArchive.sass
|		|		|   |_ episodeArchive.js
|		|
|		|_ template/
|		|		|
|		|		|_ template1/
|		|		|   |_ template1.jade
|		|		|   |_ template1.sass
|		|		|   |_ template1.js
|		|		|
|		|		|_ template2/
|		|		|   |_ template2.jade
|		|		|   |_ template2.sass
|		|		|   |_ template2.js
|
`_ Gruntfile.js
`_ package.json
`_ bower.json
`_ README.md
`_ node_modules/
`_ deploy/
```


## Usage
- npm install
- bower install
- run 'grunt' in command line to develop