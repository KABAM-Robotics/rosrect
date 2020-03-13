# Documentation Template

- [Description](#description)
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Syntax](#syntax)
- [Example-Application](#example-application)
    * [Display "Hello World" using command line](#display-"hello-world"-using-command-line)
    * [Display "Hello World" using Display App](#display-"hello-world"-using-Display-App)
- [Related-Pages](#related-pages)

## Description
This article explains how to document a feature/api.

## Overview
This article shows how to document a feature/api with template examples. By the end of this, you will be able to reuse this template to document any feature/api in your stack.

## Prerequisites
In this section, you can include the prerequisite knowledge required to understand this document. Not to be confused with prerequisites for the software itself.

## Installation
Show users how to get access to the software quickly. This should also include any prerequisite installation required and not just the software package in question. Make sure users understand OS requirements as well. Any additional compilation required by the user should go here as well. Example below: 

This example works only on Linux. If you are interested in Windows or MacOS, please vote for the feature in the feautre list so we can prioritize it! For Linux, follow the instructions below:

Install the dependencies and prerequisite packages:
```
$ sudo apt-get update
.
.
.
```

Clone the repo:
```git
$ git clone <repo>
```

Run the python file in `python3` to check if installation succeeded:
```python
$ python3 check_dummy_installation.py
```

Compilation instructions are as follows:
```
$ catkin_make
```

## Syntax
Include specifics of how to call the particular api or open a UI interface/app. For e.g. 

To use the display feature in a terminal, issue the `echo` command with the desired string.
```
$ echo <desired-string>
```

To do the same thing interactively, open the `Display App` as follows:
```
$ ./DisplayApp
```
This opens the UI:

![alt text][App]

[App]: https://s3.amazonaws.com/assets.mockflow.com/app/wireframepro/company/Cbbff1171fd07caff3fb391f44c1ae0b1/projects/Me41b5b74dc1c953b10d9717e622c78b91582512100884/pages/d94b069c3cbf4218bed2defad89159e0/image/d94b069c3cbf4218bed2defad89159e0.png "Display App"


Note that we are not providing examples on how to use the feature/app. We are just providing the basic interface for users to get started fast without having to go through an example and know their way around the package. For examples, we go to the next section.

## Example Application
Here we include actual examples that the users can run "out of the box". This means, if there are supporting files that the user needs to run the examples, consider providing them as a part of the package installation itself. This is also a good place to link to other doc pages to get them started as part of this set up. For example, suppose the user needs to be running a simulation in parallel to the application to test it out, point to the doc page that shows how to get started for that instead of including all information in this page.

In our example scenario, we can have 2 examples as follows:

### Display "Hello World" using command line
To display "Hello World" using command line, issue the `echo` command as follows:
```
$ echo Hello World
```

### Display "Hello World" using Display App
To display "Hello World" using the app, 

First, start the app:
```
$ ./DisplayApp
```
This shows the Display App:

![alt text][App]

Next, click on the text box for `Text` that needs to be displayed and enter "Hello World". After that, click the `Display!` button to view the text:

![alt text][Example]

[Example]: https://s3.amazonaws.com/assets.mockflow.com/app/wireframepro/company/Cbbff1171fd07caff3fb391f44c1ae0b1/projects/Me41b5b74dc1c953b10d9717e622c78b91582512100884/pages/Dfb76bfa1ef5ff0c3a533264d3c643d73/image/Dfb76bfa1ef5ff0c3a533264d3c643d73.png "Example"


## Related Pages
For more related information, refer to:
* [Markdown Cheatsheet][2]
* [Generating Markdown ToC][3]
* [Example of good documentation from MATLAB][4] 
* [External Reference for Documentation][5]

[2]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[3]: https://gist.github.com/jonschlinkert/ac5d8122bfaaa394f896#heading
[4]: https://www.mathworks.com/help/matlab/ref/mldivide.html
[5]: https://plan.io/blog/technical-documentation/