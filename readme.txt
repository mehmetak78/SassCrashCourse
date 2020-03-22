
- In index.html
     <link rel="stylesheet" href="css/style.css"/>

- % sudo npm install -g sass

- Use File Watchers in Webstorm
	◦ Install SASS plugin in Webstorm in preferences/Plugins
	◦ Preferences / Tools / File Watchers
		‣ Make SCSS checked
		‣ Double click SCSS to change settings (leave default)

		    Arguments : $FileName$:../css/$FileNameWithoutExtension$.css
		    Output Paths : ../css/$FileNameWithoutExtension$.css:../css/$FileNameWithoutExtension$.css.map

• Or in the terminal
	◦ Sass --watch scss/style.scss css/style.css.  (making to a different folder called css)
	◦ As long as it is running it will check for the changes in sass file and compiles them into css file.

• Compress CSS file
	◦ % sudo npm install -g yuicompressor
	◦ Add File Watcher
		‣ Yui Compressor CSS
