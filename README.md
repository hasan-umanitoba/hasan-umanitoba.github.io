# How to Host a Resume on Github Pages

## Purpose 
This README describes how to host a resume on Github pages using the strategies mentioned in Andrew Etter's book [**Modern Technical Writing**](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS). The book emphasized helping people create documentation in a sensible way which can increase the reader's knowledge. 

## Prerequisites
You will need the following resources before starting:
* A resume for a prospective employer in your field of work. It should be formatted in [Markdown](https://www.markdownguide.org/basic-syntax/) and named 'index.md'
* A [GitHub](https://github.com/) account.
* A Markdown [editor](https://code.visualstudio.com/docs/languages/markdown) and some of its [basics](https://www.markdownguide.org/basic-syntax) to start with.

## Instructions
### Pick a Markdown editor
Markdown editors are tools to convert text to HTML and allow developers and technical writers to design documents easily. I used Microsoft's [Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown) to format the resume because it comes with various extensions which support shortcuts, style checking, and markdown linting. A list of other editors is provided in [Additional Resources](https://github.com/hasan-umanitoba/hasan-umanitoba.github.io/#more-resources). 

### Formatting the resume
I used markdown as a lightweight markup language because I found it easier to learn, read and convert to a visually appealing resume. It's also a new standard for the text that will be published online. Providing content for simple static sites works well with learning management systems and large content management systems. Andrew Etter also describes in their book that it has the cleanest syntax and markdown flavor, such as 'GitHub Flavored Markdown' is a popular choice for simple web-based help systems. Using Github's flavored markdown language, I formatted my resume into multiple sections such as :
1. Personal Information
2. Education
3. Technical Skills
4. Work Experience
5. Projects
6. Extracurricular Activities

It's also vital to ensure we are following a proper style while building our resumes. I made sure the writing style was consistent by using abbreviations consistently after introducing them. Also, most of the descriptions in the resume included an ordered list that showcased different responsibilities or tasks performed. I also used inline styles to highlight significant portions of the resume and to catch the reader's attention. This way, they are better able to navigate and find the information they need. There are links to more details about Github flavored Markdown under the [additional resources](#additional-resources) section.

### Hosting on GitHub

#### What is GitHub and why do we use it?
GitHub provides internet hosting for software development and version control using Git. It offers distributed version control and source code functionality so others can collaborate easily. It's free for users and it allows us to maintain useful lists of documents that keep them organized. Andrew Etter recommends such distributed version control to the audience as the community of developers widely accepts it. As a result, documentations and branches stay in sync, whereas developers are more likely to contribute when they don't need to clone a separate new repository.

#### Using GitHub Pages
Github Pages is a static site hosting service that can take files straight from your repository and, run them through a build process, and publish a website. It publishes any static site we push to our repository. You can create your own static sites or use a static site generator such as Jekyll. By default, Github pages will use Jekyll to build. Andrew Etter displays their love for the static sites by saying :
> I love them. I love their speed, simplicity, portability, and security..

The author also recommends to use Github pages to host static site. More about [Jekyll and Github Pages](#additional-resources).

#### Set up your GitHub account
* You can [join](https://github.com/join) GitHub by filling in the username, email address, and password
on their signup page.

#### Create a repository
GitHub allows users to build their site from scratch or generate one for our project. Andrew Etter recommends  configuring our production server as a remote repository and pushing the finished static site to it. This process adds new files, updates exisiting files and deletes stale files. We can follow the process by first initiating a Github repository through the following steps :
1. Head over to the GitHub [homepage](https://github.com/) screen.
2. Click on the '+' dropdown menu on the top right corner and select the new repository.
3. Name the repository as username.github.io, where username is your (or organization name) username on Github
4. Select repository as Public so anyone can see this repository.
5. Click on the 'Create repository' button at the bottom of the page
6. Ensure that the source branch is set to main.

#### Add Files
Github and lightweight markup languages are also compatible. Etter describes in their book that a lightweight markup format makes it easier to produce well-formed XML. XML is later used to build websites. Adding and updating files on the Github repository is an easy and quick process described below :
1. Navigate to your homepage and click on the repository that you created
2. Click on **Add File** drop-down menu and select an option based on your choice.
  * **Create new file** to make a new file.
  * **Upload files** to upload existing files from your workstation.
3. After selecting 'index.md' as your file, click on the commit new file button at the bottom. 
4. Following the same process, add a 'README.md' file to the repository. 

#### Updating Theme
It is essential to have a theme of the website which follows design principles. A site that is easier to understand and navigate helps the users to find the required information easily. Users will be comfortable  visiting this kind of site multiple times. As Etter recommends to customize the theme by focusing on its navigation and approachability. Special attention must be given to the colors, font sizes, page width, and spacing. This kind of customization helps to differentiate our content. Jekyll provides some built-in templates that we can use. To include a theme, follow these steps:
1. navigate to the repository and click on the **settings** button represented by a gear icon.
2. Click on **Pages** in the left pane.
3. Under the theme chooser section, click on the **Change Theme** button.
4. Select a theme that is appropriate for the content and press the **Select Theme** button.

#### Viewing your resume
To ensure and view that your site is working correctly :
1. Go to **Settings**
2. Click on **GitHub Pages** in the left pane.
3. Click on the URL where your site is published at in the format : https://username.github.io/ .

![Preview of resume](resume.gif)

## Additional Resources

### Andrew Etter's book
* To read more about Andrew Etter's Book *Modern Technical Writing* Click [here](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
### Markdown
* To get started with markdown syntax, click [here](https://www.markdownguide.org/basic-syntax).
* To practice markdown using tutorials, click [here](https://www.markdowntutorial.com/).
### GitHub Pages
* Quickstart for GitHub pages, click [here](https://docs.github.com/en/pages/quickstart)
* To learn more about static site generation and GitHub pages, click [here](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
### Jekyll
* To learn more about Jekyll, click [here](https://jekyllrb.com/).
* Playlist on creating and hosting a static site. Click [here](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB).

## Authors and Acknowledgements

**Hasan Saleem** is the author.   
I appreciate my course instructor Stewart Wilcox for providing the README template and guiding the format for this assignment. Thank you to Andrew Etter for writing [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS]) and introducing the strategies described.
Thank you to Abdullah Al Noman, Jaden Down, and Long Vu, Abu Yasin Sabik for peer editing and valuable feedback throughout this course. 

## FAQs

### Why is Markdown better than a word processor?
Markdown files can be easily kept in version control, whereas Word's DOCS file format, a collection of compressed XML files, actively opposes this. Markdown is simpler and easier to convert. Markdown is also easier to understand since it's in plain text format, and its compatibility with version control allows better collaboration among individuals.

### Why is my resume not showing up?
To find out why your resume is not being hosted, run the following checks:
* Make sure that **index.md** file is in your repository's main branch.
* Verify the **username** of your repository matches your GitHub account's username and is in the format username.github.io .
* Navigate to the settings of the repository and then click on pages on left pane. Ensure that Github says your site is **published** in the following format : 
>  Your site is published at https://username.github.io/ ...


