# What is this?
I built this page while running through the 'Web Development 101' course at [The Odin Project](https://www.theodinproject.com/courses/web-development-101/lessons/html-css), which I highly recommend. The end result as it currently stands can be viewed at https://mikaelmahsudjan.github.io/google-homepage

It is meant to be an (almost) exact visual copy of the Google Homepage, as viewed in a desktop browser from Estonia. And yes, that last bit is actually important. If you want to see how different the Google homepage (and especially its search results) can look when viewed from different countries, I suggest you try [OpenVPN](https://openvpn.net/community/). 

I had a very basic knowledge of HTML & CSS before, with practically zero experience.

## What I learned while working on this project

### HTML

* How to apply [HTML 5 semantic elements](https://www.w3schools.com/html/html5_semantic_elements.asp) such as main, header, footer, nav. 
* How to [make a favicon appear](https://stackoverflow.com/questions/4888377/how-to-add-a-browser-tab-icon-favicon-for-a-website/35625707) in the page's title tab:

	```html
	<head>
  		...
  		<link rel="shortcut icon" type="image/x-icon" href="./images/favicon.ico" />
  		<title>Google search</title>
	</head>
	``` 
* How to convert an image to `.ico` format: <https://icoconvert.com/> allows editing (i.e., add a border or a round badge in the background) before conversion.
* How to put the [focus on a textfield](https://www.w3schools.com/tags/att_input_autofocus.asp) when the page first loads: 

	```html
	<input type="text" autofocus />
	```

### CSS

* How to [center elements on the page](https://css-tricks.com/centering-css-complete-guide/) in all directions and under all circumstances. For this page, only horizontal centering was relevant.
	
* How to [make the footer stick](https://css-tricks.com/couple-takes-sticky-footer/) to the bottom of the page. 

* How to correctly use [float, clear and overflow](https://www.w3schools.com/Css/css_float.asp) to create horizontal lists of elements.

* How to render a form field (the search box) with [rounded corners](www.askdavetaylor.com/round-edges-text-input-element-web-form/) and [shadow effects](https://www.w3schools.com/css/css3_shadows.asp) on focus and/or hover: 


	

### Git

* How to install git and use `git init, git add, git commit -m` from the terminal on my local machine.
* How to create a new repository and clone my local git repository to it on [Github](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line). 
* How to make the rendered output of my code visible to outsiders using [Github Pages](https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages).




 
