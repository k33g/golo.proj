golo.proj
=========

Golo.proj is a **Golo** template project


##Install It

###First way (simplest way)

	git clone --q --depth 0 git@github.com:k33g/golo.proj.git <your project directory>

###Second way

	mkdir <your project directory>
	cd <your project directory>
	golio golo.proj

Then :

	chmod a+x gol
	chmod a+x golj

>>*You need golio : [https://github.com/k33g/golio](https://github.com/k33g/golio)*

###Optional dependencies

You need maven if you want to compile your own java library

##Use it

It's simple :

- save your main program to root of `<your project directory>`
- save other golo files to `<your project directory>\libs`
- if you need external jars, put them to `<your project directory>\jars`

Run your project : `./gol <main_file.golo>`

That's all!

##Compile your java files ... (make you own library)

- save java source files to `<your project directory>\java.src`
- compile library : `./golj`


