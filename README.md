# Sass Workshop

> Enjoy!

## 1. Introduction

This is a Sass Workshop intented to give you an overview on how to use it in your everyday projects along with Compass.
In order to make it even more epic, this workshop contains a challenge for you to test your knowledge.


## 2. Resources

1. Open and read the [slides](http://www.juandavidherrera.com/sass/slides), I made them with love, plus they are full of relevant links like my social accounts.
2. Check the [challenge](http://juandavidherrera.com/sass/challenge). This is what you are supposed to build using Sass and Compass.
3. The solution of the challenge is availabe in the [challenge](https://github.com/jdjuan/sass-workshop/tree/master/challenge) folder.


## 3. Requirements

1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/#rubyinstaller) and then run `$ ruby -v`

2. Install [Sass](http://sass-lang.com/install) and then run `$ sass -v`

3. Install [Compass](http://compass-style.org/install/) and then run `$ compass -v`


## 4. Set up

1. Open the terminal and create a Compass Project using: 
 
	`$ compass create MyProject`

	You should see something like this:	

	![alt text](https://github.com/jdjuan/sass-workshop/blob/master/slides/images/readme-image2.png "Tree Structure")

2. Create an **index.html** file and import the stylesheets links that were output in the console:
![alt text](https://github.com/jdjuan/sass-workshop/blob/master/slides/images/readme-image.png "Console Links")

3. Make Compass update your files every time they change by typing in the console:

	`$ cd ..`<br>

	`$ compass watch MyProject`

5. Create a file called **style.scss** within the sass folder and import it into your html file.

6. Your final project tree should look like this:<br>
![alt text](https://github.com/jdjuan/sass-workshop/blob/master/slides/images/readme-image3.png "Final Tree Structure")


7. And your final html file should look like this:

```HTML
<html>
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=0" />
	<title>Challenge</title>
	<link href="stylesheets/screen.css" media="screen, projection" rel="stylesheet" type="text/css" />
	<link href="stylesheets/print.css" media="print" rel="stylesheet" type="text/css" />
	<!--[if IE]><link href="/stylesheets/ie.css" media="screen, projection" rel="stylesheet" type="text/css" /><![endif]-->
	<link href="stylesheets/style.css" rel="stylesheet" type="text/css" />
</head>
<body>
</body>
</html>
```

####That's it!, you are ready to get started with the challenge.
