## PSD-to-HTML: Engine Labs Contact page
Technologies/skills used: HTML, CSS  

### Task
> Download assets from here: 

+ Turn the **blank** contact.html file into the site's contact us page.
+ Look at the mockups PNG in the root directory: `enging_labs_contact.png` 
+ You will notice that there are several different mockups of the top section of this page. 
+ Once you have finished the layout of the page, you can get to work turning this into a functional contact form/Twitter/Instagram feed. 
+ Feel free to use any transition effect you like between sections. Also, do not worry about the contact form working, but you should update that section to simulate confirmation of the mail sending when someone submits the form.

### Structure
* **Sections**   
  * spans the width of the page (100%)
  * have a more narrow (960px), centered subsection where the content goes
* **Images** 
  * Design assets are all saved in the `img` folder.
  * The small design assets you will need are in `sprite.png`.
  * The background and logo files are also in the folder.
* **Font** is Google's [Source Sans Pro](http://www.google.com/fonts/specimen/Source+Sans+Pro). It should already be listed in the header of your document. Take a look at all the weight and style options.
* **Colors**:  
  * dark blue `#003047`
  * light gray `#EDEDED`
  * medium blue `#01527D`
  * white `#FFFFFF`
  * black `#000000`

### Tips
* If you completed the `index.html` or `about.html` files, start off by copying the entire file from your last project into the contact.html. 
* Go through and remove sections that aren't relevant to the contact page. See if there are any sections in the new page design that use a similar structure to existing pieces of the old page, and leave those sections of the old HTML in place.
* Don't forget to declare your site's CSS and any additional required resources in the header of the document

#### Keep it simple
* Try this without using a grid framework like Skeleton or Bootstrap.
* Once you feel confident hand-coding, investigate a grid framework and see how much time it saves you.

#### Create structure systematically
* Work top to bottom
* Break the page into vertically-stacking sections  
_for example, create header, hero image, quote, features, etc_

#### Use classes effectively
* Name classes by function of a particular element rather than content inside it
* Lets you style elements quickly when they need to serve a common purpose.  
_For instance, for a div that needs to be noticable, naming it `.callout` rather than `.side-of-story-color-background-designer-quote` means you don't have to restrict the content inside to quotations from designers--and you can easily use the class name elsewhere in the site._
* Want to use SCSS rather than CSS? Using [SASS](http://sass-lang.com/documentation/index.html) with this assignment is pretty easy. With a single file, go to the folder where you're saving your style files. Create a scss and css files with the same name (ie, `style.css` and `style.scss`. In the terminal `sass --watch style.scss:style.css`. More help `sass --help`

### Resources
* [A grid system with nice demos](http://960.gs/)
* Great resource for how to work with [sprite styles](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/CSS_Image_Sprites): [Sprite Cow](http://www.spritecow.com/)
* Great resource for CSS tutorials and guidelines: `http://css-tricks.com/`
* Great resource for web stuff in general, including CSS and HTML: `http://www.html5rocks.com/en/`
* [Absolute positioning](https://developer.mozilla.org/en-US/docs/Web/CSS/position) and [floats](http://css-tricks.com/all-about-floats/).
* Reseting styles: Use a `reset.css` for cross-browser harmony. [Skeleton](http://www.getskeleton.com/), [Bootstrap](http://getbootstrap.com/css/), [HTML5Boilerplate](https://github.com/h5bp/html5-boilerplate/blob/master/doc/TOC.md) and [YUI](http://yui.yahooapis.com/3.10.1/build/cssreset/cssreset-min.css) have reset files/components.

### Tutorails
* More tutorials: [GA Dash](https://dash.generalassemb.ly/)
