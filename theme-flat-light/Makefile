include ../.makerc
# run `make hello` to see the output 
ThemeName=za-dark-kai
hello: 
	echo "Hello, world!"
# run `make watch` to watch the file and compile it
watch: 
	sass --watch main.scss ${PathToTyporaThemes}${ThemeName}.css
# run `make build` to compile the file
build:	
	sass --no-source-map=none main.scss ${PathToTyporaThemes}${ThemeName}.css