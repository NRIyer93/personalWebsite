# My Personal Website

After three days of learning HTML and CSS, I was given the task of producing a personal website with a function of my choosing using the Bootstrap framework. Due to ease, I chose to design a basic blog consisting of a navigation bar, general content page and a footer containing contact info with varying colours as the viewer scrolls down. This project is responsive to mobile and desktop viewing.

## Prerequisites

* Text editor
* HTML document
* CSS document
* [Bootstrap framework folder] (http://getbootstrap.com)

As well as the above, a basic understanding of HTML and CSS is required.

## Design and Development

### Wireframe

Below is a rough draft of the intended final product.
![The opening view of the webpage](../desktop/readmephotos/websiteOpening.png)

Scrolling down the page, the viewer will see the first section, "**About**".

![First section viewpoint](../desktop/readmephotos/aboutMe.png)

Using the above frame, the row was divided into two sections. The profile photo would take up three segments of the row and the text would use the remaining nine.

![Photos section viewpoint](../desktop/readmephotos/photosSec.png)

The next section consisted of a photo album and as you can see from above, the same position exists for all section titles. For the photos section, however, the content was divided in to three sections with each photo and its corresponding text taking up four segments each. 

Ideally, for the mobile version, a section such as this one would be contained in an expandable box in order to save time when scrolling.

![Last sectiion](../desktop/readmephotos/lastSec.png)

The final section consisted of two titles:

* Interests 
* Contact




<!-- INSERT WIREFRAME IMAGE HERE-->

### Development

Using the wireframe as a starting point, the HTML file was set up along with a sister CSS file which was linked to the HTML file along with the **"bootstrap.min.css"** file. 

The first step was to set out the HTML file with the appropriate sections e.g About, Contact, etc. The "Welcome" page was created using a Jumbotron (a component of the Bootstrap framework) inside the header section of the HTML file which gave the name of the blog, followed by an image. Using CSS, the background of the jumbotron was set to a custom image.

Once this was completed, I began to divide up the file using containers, giving each section in the scrolling webpage it's own container in which to position it's contents using the row structure. The syntax for the structure of a row can be seen below:


		            <div class="row"> 
		            	
		            		<div class="col-md-3">
		            			<!-- content here -->
		            	    </div>
		            		
		            		<div class="col-md-9">
		            			<!-- content here --> 
		            		</div> 


Using this template, I structured my sections using different sizes of segments. 



## Final Product 

#### Mobile Version

Screenshots of the final product of the **mobile** version can be seen below in order of content that appears as the user scrolls down:

![First image](../desktop/readmephotos/first.png)
![Second image](../desktop/readmephotos/second.png)
![Third image](../desktop/readmephotos/third.png)
![Fourth image](../desktop/readmephotos/fourth.png)
![Fifth image](../desktop/readmephotos/fifth.png)
![Sixth image](../desktop/readmephotos/sixth.png)

#### Desktop Version

Screenshots of the final **desktop** version can be seen below:

![Desktop1](../desktop/readmephotos/desktopwebsite1.png)
![Desktop2](../desktop/readmephotos/desktopwebsite2.png)
![Desktop3](../desktop/readmephotos/desktopwebsite3.png)
![Desktop4](../desktop/readmephotos/desktopwebsite4.png)







 

## Built With

* Sublime Text
* Bootstrap version 3.3.7


## Author/s

Naren Richard Iyer

## Aknowledgements


