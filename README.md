# Welcome to StackEdit!

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.


# Files

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
<h1 align="center">Hi. I'm Mateus Nogueira! :man_technologist::brazil:</h1>
<h3 align="center">Welcome to my GitHub profile</h3><br>
<div align="right">
<img src="https://media.giphy.com/media/PaB0GTtttzn2ch0vdT/giphy.gif" width="230" height="230">
<p align="left">
🔭 I'm a Jr. Full Stack Java Developer graduating at <a href="https://brazil.generation.org/" target="_blank">Generation Brasil</a>.<br>
🌱 I’m currently learning Java, Spring Boot and other cool stuff!<br>
😄 Pronouns: Ele/He<br>
<img src="https://www.emojiall.com/images/60/emojitwo/269b.png?ezimgfmt=rs:60x60/rscb2/ng:webp/ngcb2" width="14" height="14"> “A program is never less than 90% complete, and never more than 95% complete.” - Terry Baker<br>
I remember every day <em>"A repetição, leva à maestria."</em>
</p>
</div>



![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=Linux&logoColor=white&color=7d00ff)![](https://img.shields.io/badge/Tools-Spring_Boot-informational?style=flat&logo=SpringBoot&logoColor=white&color=7d00ff)![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=GNUBash&logoColor=white&color=7d00ff)![](https://img.shields.io/badge/Editor-Vim-informational?style=flat&logo=Vim&logoColor=white&color=7d00ff)
</div><br><br>

## :rocket: Languages & Tools:
<br><br>
<div align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original-wordmark.svg" width="70" height="70">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original-wordmark.svg" width="70" height="70">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" width="70" height="70">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="70" height="70">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original-wordmark.svg" width="70" height="70">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" height="70" height="70">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="65" height="65">
&nbsp;
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" width="70" height="70">
<br><br><br><br>

<img align="center" width="53%" src="https://github-readme-stats.vercel.app/api/?username=nogran&theme=swift&repo=github-readme-stats" />
&nbsp;
<img align="center" width="44%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nogran&theme=swift&layout=compact&hide=jupyter%20notebook">


</div></br><br>

------------------

<br>

```java
class Quotes {

    public static void main(String[] args) {

        System.out.println("author: Albert Einstein");
        System.out.println("text: I have no special talent. I am only passionately curious.");
    }
}
```
<br>

------------------

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?width=650&height=100&lines=Thanks+for+visiting+my+profile%2C+see+you+next+time!;Let's+get+connected)](https://git.io/typing-svg)

<!-- ## :heart: Let's get connected: <img align="top" src="https://media.giphy.com/media/CVgswLRgV3nqw/giphy.gif" height= "30" width="30"/> -->

[![](https://img.shields.io/badge/-mateusnog95@gmail.com-red?style=flat-square&logo=Gmail&logoColor=white&color=ea4335&labelColor=ea4335)](mailto:mateusnog95@gmail.com?subject=Hello%20World)
[![](https://img.shields.io/badge/LinkedIn-/mateusnog95-blue?style=flat-square&logo=LinkedIn&logoColor=white&color=0a66c2&labelColor=0a66c2)](https://www.linkedin.com/in/mateusnog95/)

</div>