# Version Control {#vs}

A [great book](http://happygitwithr.com/) on Git and Github that should cover all your needs.

## Introduction

Few software engineers would embark on a new project without using some sort of [version control software](https://en.wikipedia.org/wiki/Version_control). Version control software allows us to track the three Ws: Who made Which change, and Why?. Tools like [git](https://git-scm.com/) can be used to track files of any type, but are particularly useful for code in text files for example R or Python code.

Whilst git can be used locally on a single machine, or many networked machines, git can also be hooked up to free cloud services such as GitHub, GitLab, or Bitbucket. Each of these services provides hosting for your version control repository, and makes the code open and easy to share. The entire project we are working on with DCMS can be seen on [GitHub](https://github.com/ukgovdatascience/eesectors).

Obviously this won’t be appropriate for all Government projects (and solutions do exist to allow these services to be run within secure systems), but in our work with DCMS, we were able to publish all of our code openly. You can use our code to run an example based on the 2016 publication, but producing the entire publication from end to end would require access to data which is not published openly. Below is a screenshot from the commit history showing collaboration between data scientists in DCMS and GDS. The full page can be seen on GitHub.

Using a service like GitHub allows us to formalise the system of quality assurance (QA) in an auditable way. We can configure GitHub to require a code review by another person before the update to the code (this is called a pull request) is accepted into the main workstream of the project. You can see this in the screenshot below which relates to a pull request which fixed a minor bug in the prototype. The work to fix it was done by a data scientist at DCMS, and reviewed by a data scientist from GDS.

<a href="https://gdsdata.blog.gov.uk/2017/03/27/reproducible-analytical-pipeline/" target="_blank"><img src="images/pull_request.png" style="display: block; margin: auto;" /></a>