# How to Host a Resume on Github Pages

## Purpose 
This README describes how to host a resume on Github pages using the strategies mentioned in Andrew Etter's book [**Modern Technical Writing**](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). The book emphasized on helping people create documentation in a sensible way which can increase reader's knowledge. 

## Prerequisites
You will need the following resources before starting:
* A resume for a prospective employer in your field of work. It should be formatted in [Markdown](https://www.markdownguide.org/basic-syntax/) and named 'index.md'
* A [GitHub](https://github.com/) account.
* A Markdown [editor](https://code.visualstudio.com/docs/languages/markdown) and some of its [basics](https://www.markdownguide.org/basic-syntax) to start with.

## Instructions
### Pick a Markdown editor
Markdown editors are tools to convert text to HTML and allows developers and technical writers to design documents easily. I used Microsoft's [Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown) to format the resume because it comes with various extensions which supports shortcuts, style checking, and markdown linting. List of other editors are provided in [Additional Resources](https://github.com/hasan-umanitoba/hasan-umanitoba.github.io/#more-resources). 

### Formatting the resume
I used markdown as a lightweight markup language because I found it easier to learn, read and convert to visually appealing resume. It's also a new standard for text that will be published online. By providing content for simple static sites, it works well with learning management systems and large content management systems. Andrew Etter also describes in their book that it has the cleanest syntax and markdown flavor such as 'GitHub Flavored Markdown' is a popular choice for simple web-based help systems. Using Github's flavored markdown language I formatted my resume to properly my resume into multiple sections such as :
* Personal Information
* Education
* Technical Skills
* Work Experience
* Projects
* Extracurricular Activities

It's also important to ensure we are following a proper style while building our resume. I made sure the writing style was consistent by using abbreviations consistently after introducing them. Also, most of the descriptions in the resume included an ordered list which showcased different responsibilities or tasks performed. I also used inline styles to highlight important portions of the resume and to catch reader's attention. This way they are better able to navigate and find information they need. There are links to more information about Github flavored Markdown under the [additional resources](#additional-resources) section.

### HOSTING ON GITHUB

#### What is GitHub and why do we use it?
GitHub provides internet hosting for software development and version control using Git. It offers distributed version control and source coude functionality so others can collaborate easily. It's free for users and it allows us to maintain useful lists of documents which keeps them in an organized manner. Andrew Etter recommends such distributed version control to audience as it is widely accepted by the community of developers. As a result, documentations and branches stay in sync whereas developers are more likely to contribute when they dont need to clone a separate new repository.

#### Using GitHub Pages
Github pages is a static site hosting service which can take files straight from your repository and run them through a build process, and publish a website. It publishes any static site we push to our repository.You can create your own static sites or using a static site generator such as Jekyll. By default, Github pages will use jekyll to build. Andrew Etter displays their love for the static sites by saying :
> I love them. I love their speed, simplicity, portability, and security..

The author also recommends to use Github pages to host static site. More about [Jekyll and Github Pages](#additional-resources).

#### Setup your GitHub account
* You can [join](https://github.com/join) GitHub by filling in the username, email address, and password
on their signup page.

#### Create a repository
GitHub allows uers to build own site from scratch or generate one for our project. Andrew Etter recommends to configure our production server as remote repository and push the finished static site to it. This process adds new files, updates exisiting files and delete stale files. We can follow the process by first initiating a Github repository through the following steps :
* Head over to GitHub [homepage](https://github.com/) screen.
* Click on the '+' dropdown menu on the top right corner and select new repository.
* Name the repository as username.github.io, where username is your (or organization name) username on Github
* Select repository as Public so anyone can see this repository.
* Click on the 'Create repository' button at the bottom of the page
* Ensure that the sourch branch is set to main.

#### Add Files
Github and lightweight markup languages are also compatible. Etter describes in their book that lightweight markup format makes it easirer to produce well-formed XML. XML is later used in order to build websites. Adding and updating files on Github repository is an easy and quick process described below :
* Navigate to your homepage and click on the repository that you created
* Click on **Add File** drop down menu and select an option based on your choice.
  * **Create new file** to make a new file.
  * **Upload files** to upload exisiting files from your workstation.
* After selecting 'index.md' as your file, click on commit new file button at the bottom. 
* Following the same process, add a 'README.md' file the repository. 

#### Updating Theme
It is essential to have a theme of website which follow design principles. A site which is easier to understand and navigate helps the users to find required information easily. Users will be comfortable in visiting this kind of site multiple times. As Etter recommends to customize the theme by focusing on it's navigation and approachability. Special attention must be given to the colors, font sizes, page width, and spacing. This kind of customization helps to differentiate our content. Jekyll provides some built-in templates that we can use. To include a theme, follow these steps:
* navigate to the repository and click on **settings** button represented by a gear icon.
* Click on **Pages** in the left pane.
* Under the theme chooser section, click on **Change Theme** button.
* Select a theme which is appropriate for the content and press **Select Theme** button.

#### Viewing your resume
To ensure and view that your site is working correctly :
* Go to **Settings**
* Click on **GitHub Pages** in the left pane.
* Click on the URL where your site is published at in the format : https://username.github.io/ .

![Preview of resume](resume.gif)

## Additional Resources

### Andrew Etter's book
* To read more about Andrew Etter's Book *Modern Technical Writing* Click [here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
### Markdown
* To get started with markdown syntax click [here](https://www.markdownguide.org/basic-syntax) 
* To practice markdown using tutorials, click [here](https://www.markdowntutorial.com/)
### GitHub Pages
* Quickstart for GitHub pages, click [here](https://docs.github.com/en/pages/quickstart)
* To learn more about static site generation and GitHub pages, click [here](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
### Jekyll
* To learn more about Jekyll, click [here](https://jekyllrb.com/).
* Playlist on creating and hosting a static site. Click [here](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB).

## Authors and Acknowledgements

**Hasan Saleem** is the author.   
I appreciate my course intructor Stewart Wilcox for providing the README template.Thank you to Andrew Etter for writing [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS]) and introducing the concepts described here.
Thank you to Abu Yasin Sabik, Abdullah Al Noman, Muhammad Hasan Saleem, and Long Vu for peer editing.  

## FAQs
