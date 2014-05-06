# Team Toubus

## Project Structure
```
PROJECT/
|
|-- src
|  |-- assets/
|  |  |
|  |  |-- vid/
|  |  |  |-- *.mp4
|  |  |  |-- *.webm
|  |  |-- img/
|  |  |  |-- *.jpg
|  |  |  |-- *.png
|  |  |  |-- *.svg
|  |  |-- data/
|  |  |  |-- *.json
|  |
|  |-- components/
|  |  |-- about--header/
|  |  |  |-- about-header.jade
|  |  |  |-- about-header.sass
|  |  |  |-- about-header.js
|  |  |
|  |  |-- about/
|  |  |  |-- about-content.jade
|  |  |  |-- about-content.sass
|  |  |  |-- about-content.js
|  |
|  |-- global/
|  |  |
|  |  |-- css/
|  |  |  |-- base
|  |  |  |  |-- _helper.sass
|  |  |  |  |-- _reset.sass
|  |  |  |
|  |  |  |-- dependency
|  |  |  |  |-- _mixin.sass
|  |  |  |  |-- _var.sass
|  |  |
|  |  |-- jade/
|  |  |  |-- base
|  |  |  |  |-- base.sass
|  |  |  |  |-- base-header.sass
|  |  |  |  |-- base-footer.sass
|  |  |  |
|  |  |  |-- dependency
|  |  |  |  |-- mixin.jade
|  |
|  |-- pages/
|  |  |
|  |  |-- about/
|  |  |  |-- about.jade
|  |  |  |-- about.sass
|  |  |  |-- about.js
|  |  |
|  |  |-- index/
|  |  |  |-- index.jade
|  |  |  |-- index.sass
|  |  |  |-- index.js
|  |  |
|  |  |-- episodeArchive/
|  |  |  |-- episodeArchive.jade
|  |  |  |-- episodeArchive.sass
|  |  |  |-- episodeArchive.js
|  |
|  |-- template/
|  |  |
|  |  |-- template1/
|  |  |  |-- template1.jade
|  |  |  |-- template1.sass
|  |  |  |-- template1.js
|  |  |
|  |  |-- template2/
|  |  |  |-- template2.jade
|  |  |  |-- template2.sass
|  |  |  |-- template2.js
|
`-- Gruntfile.js
`-- package.json
`-- bower.json
`-- README.md
`-- node-modules/
`-- deploy/
```


## Usage
- npm install
- bower install
- run 'grunt' in command line to develop