## Hosting Your Resume Online

### Purpose

GitHub is a widely used software for collaborating with scalable projects.
After graduation, you must communicate your skills using a resume to prove
you are a credible candidate for the position you wish to apply for.
Hosting your resume online through GitHub Pages is a relevant way to show your 
competence in new technology and range of skill set in the understanding how the technology works. 
This README will guide you through the steps on how to host your resume, and
what practices you should follow to maximize communication of your skills.

### Prerequisites

* A resume written in markdown
* A GitHub account (Create one for free!)
* A text editor (optional but recommended)

Please see the [More Resources](#More Resources) section for more sources to complete these steps.

Note that it is recommended to use a Markdown editor.
The benefits of a Markdown editor include, seeing output in real-time, text highlighting for visual feedback,
and natural separation of the content through the language.
In addition, editors such as Visual Studio allow for Git commands to be executed directly from its terminal for 
commiting directly to Github after editting documents.

### Instructions

##### Steps to Host your Resume

![Instruction Video](https://github.com/h-connor/h-connor.github.io/blob/main/Recording.gif)

1. Create an online repository
    1. Goto the 'Repositories' section on your GitHub profile
    2. Create a new repository named: "**my_profile_name.github.io**".
    - For example, my repository is named: h-connor.github.io
2. Select a theme
    1. Go to the 'settings' section in the repository
    2. Select 'change theme' under GitHub Pages
    3. Choose a theme that you would like to have when displaying your resume
3. Upload your resume to the repository
4. Change the title of your page
    1. Edit the _config.yml file
    2. Add the line of code: "**title: my_name's Resume**"
5. See your resume at "http://my_profile_name.github.io"

###### Protocols to Follow - Learning About Each Step

A GitHub repository is an online storage space for a project. Using your profile name with a github.io extension as the name of your repository
will create a static website hosted by GitHub Pages. Static websites provide many benefits including; simplicity, portability, and security,
and as such, use static websites whenever possible. For hosting on GitHub Pages, No further work is required to create the website, and 
any further changes will regenerate the site. In all projects, you should keep publish frequently and allow members to contribute easily.
With respect to a resume, you must keep documentation up to date and modifiable through relevant information for the position you will apply for.
GitHub supports frequent publishment and easy contributions by offering direct method of updating a repository by overriting files with same name and
creating new files that are uploaded, as well as providing a history of the published work for collaboration.

GitHub Pages offers a selection of themes using Jekyll to style your hosted webpage. Tools such as Jekyll are an important aspect for styling
documentation in a way that appeals to your audience. Select a theme that displays important text by breaking similarity in constrast,
not only to be visually noticeable but for a direct coorelation for the audience to know what you want them to know. This will assure necessary
content is both discoverable and aethetically pleasing.

Arguably the single most important aspect of technical writing is to define your audience. In step 4, use a title that is relevant to who will see your work,
and describes what work they will expect to see. When writing any piece of documentation, your writing will make assumptions on the level of knowledge
of the reader based on your use of language. How descriptive you are, what you write, and your choice of words should be influenced by _who_ is reading. 
In addition, you should understand only what your audience _needs_ to know, so you as a writer can keep a central focus without false assumptions about the audience.

###### More Resources

If you are unfamiliar with markdown, you can find a great resource [here](https://www.markdownguide.org/getting-started).

If you are unfamiliar with the syntax of markdown, a great tutorial can be found [here](https://helloacm.com/markdown-markup-language-quick-tutorial/).

Learn more about [Jekyll](https://jekyllrb.com/tutorials/video-walkthroughs/).

Learn [Git](https://learngitbranching.js.org/).

This README references [Etter's book](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).

### Authors and Acknowledgements

### FAQs

**Why use Markdown?**

Using a lightweight markup language is a solution to avoiding heavy written languages such as XML or Javascript.
For simple designs where you want to focus on giving information out rather than a system for consumers, a lightweight
language will save you time with its simplicity of syntax. In addition, XML-based languages hinders contributions
by other developers as they are more word and learn intensive in raw text. Markdown is the most widely used markup language in the world 
[(Etter, Pg 22)](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
As a result of its popularity and simplicity, Markdown is supported in merely all modern browsers, contains text editor support, and 
can be learned quickly regardless of skills. 

In addition to the above, markdowns clean syntax biases towards positive styling techniques of good documentation. Markdown provides a simple syntax for
lists, images, tables, and headers, which all help break down the structure of a document to make it more scannable.

**Why is my resume not showing up?**

Potential solutions to try:
* Your repository is correctly named my_profile_name.github.io
* Assure your Resume.md is uploaded on the master branch. While I have not discussed branches, you should see a tab with "main" above the uploaded files.
* Check _config.yml for any errors. Assure the syntax "title: my_title" is used.
* Wait for a few minutes. The static website generated by GitHub Pages may take a moment before appearing.

If all else fails, please review the [Instructions](#Instructions) section, and after continued failure
contact me at hryhoru3@myumanitoba.ca, providing a link to the GitHub repository.