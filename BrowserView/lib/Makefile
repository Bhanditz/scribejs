../js/scribejs.js : bridge.js nicknames.js page.js schema.js
	browserify page.js bridge.js > ../js/scribejs.js
	terser ../js/scribejs.js > ../js/scribejs.min.js
