

**Table of Contents**  

- [Contribution Guidelines](#contribution-guidelines)
    - [How To Contribute](#how-to-contribute)
    - [File Heirachy](#file-heirachy)
        - [GettingKorora](#gettingkorora)
        - [UsingKorora](#usingkorora)
        - [GettingHelp](#gettinghelp)
    - [File Naming Conventions](#file-naming-conventions)
    - [Image Naming Conventions](#image-naming-conventions)



<a name="contribution-guidelines"></a>
# Contribution Guidelines

**Guidelines for those that wish to contribute to the Korora Documentation.**

> We welcome all contributions to the Korora Documentation but please follow these guidelines.

<a name="how-to-contribute"></a>
## How To Contribute

If you wish to contribute to the Korora Docs via GitHub, first you must create a GitHub account if you have not already done so.

You must then  fork the repo ( you will find the button at the top of the page).

![](img/Contibution-Guidelines-Fork.png)

You must then submit a pull request for any new documentation you may add, which will then be subject to review before inclusion. Korora documentation uses the [same syntax for formatting](https://kororaproject.org/support/engage/syntax) as Engage. For both new documents and improvements / updates to existing documents please create one pull request for each document.


<a name="file-hierarchy"></a>
## File Hierarchy


<a name="gettingkorora"></a>
### GettingKorora
This folder includes installation, creating bootable media, choosing a desktop Etc.

<a name="usingkorora"></a>
### UsingKorora
This folder includes genral use, desktop specific guides, upgrading / updating, GRUB, Bootloader Etc

<a name="gettinghelp"></a>
### GettingHelp
This folder includes how to get support, using Engage Etc

<a name="file-naming-conventions"></a>
## File Naming Conventions
When adding new files, please follow the following file naming guidlines:
1. File name must relate to the topic
2. Must be in English and start with a capital letter
3. All files must be in markdown format (`.md`)
4. If using multiple words in the file name, use CamelCase and seperate each word with a hyphen (eg: `Using-Korora.md`)


<a name="image-naming-conventions"></a>
## Image Naming Conventions
All images are to be placed in the `img `folder.

When naming your images please name them using the name of your file and if multiple images, further name them with a number or heading for which they are under, for example: `Contribution-Guidelines-Fork.png`.

For images that are hosted in the repo to appear in documents on the Korora website they require the full path with `?raw=true` appended e.g.
```
![Contribution-Guidelines-Fork](https://github.com/kororaproject/kp-documentation/blob/master/img/Contribution-Guidelines-Fork.png?raw=true)
```


Anyone with any questions or unable to contribute in this format please contact us at **team@kororaproject.org**.
