﻿
# Word to Markdown converter

## What is this?

This is a small utility that I built to convert the MS word (.docx,
.doc) files to Markdown documents to upload to Git repository with some
additional customizations that I required. The markdown files are
actually converted using the Pandoc utility.

Since Pandoc is a commandline utility and doesn't have a frontend, it is
not that intuitive. Furthermore, I required my markdown files to use
HTML tags in place of regular markdown links along with some other
flexibilities.

before creating this utility, I had to manually edit all markdown files
to replace HTML tags, add additional tags for page navigation, fix image
alignment, resize problems etc... Now, everything is automated. The
utility scans the document and replaces tags as required.

## How it works?

-   Create the word file as you normally would to prepare documentation.

<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/caf93aea1331d6c3ec934a417912385f4fa9fd2a.png">
</p>

<br/>
<br/>

-   Run the script *(pass to import: 123456).*


<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/23c0bcd40bd3680a3e17ad9602f1672713bbfdca.png">
</p>

<br/>
<br/>

1.  Select the document (.docx or .doc)

2.  Leave format to **Markdown**

3.  **Extract media** will create a separate folder where images from
    the document will be placed.

4.  **Media folder** will be the name of the folder where the images
    will be extracted

5.  **Target filename:** Filename of the converted markdown file.

6.  **Image format:** Select the markdown format in which images will be
    presented.


<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/356fd088a83d5faec54d436573981754782b7282.png">
</p>

<p align="Center"><i> Standard markdown format </i></p>

<br/>
<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/f278c6701164adfd22e6d4599fc2208fda27e86c.png">
</p>

<p align="Center"><i> Custom HTML tag format </i></p>

<br/>
<br/>




7.  **Image alignment:** Select the image alignment *(only if HTML Tags
    selected)*

8.  **Image width, Image height:** Set the image's width and height
    *(only if HTML Tags selected, 0 means Default resolution)*

9.  **Add navigation buttons:** Whether to add HTML code for navigation
    buttons *(usable if document is going to be a wiki page.)*


<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/a420c465b514eb3077ec5e1760b1a7c87e2f7de2.png">
</p>

<br/>
<br/>

10. Click convert and wait for notification.


<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/010642e6cfe8e8b6ce0f539f5efe098f91af2dd0.png">
</p>

<br/>
<br/>


<br/>

<p align="Center">
  <img src="https://raw.githubusercontent.com/wiki/CuriousLad1000/Robot-Process-Automation/images/9f7e9a2b570b681db1eeade6f7281a0afeb877b9.png">
</p>

<br/>
<br/>

