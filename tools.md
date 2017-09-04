# Software Tools

This document will explain some of the software tools I used during the IP Dev rotation. These are short high level explanations of the tools. For information about them, I'll be providing URL's that will take you to additional documentation.

### Containers

Containers are a method of operating system virtualization that allow you to run an application and its dependencies in resource-isolated processes. Containers allow you to easily package an application's code, configurations, and dependencies into easy to use building blocks that deliver environmental consistency, operational efficiency, developer productivity, and version control. Containers can help ensure that applications deploy quickly, reliably, and consistently regardless of deployment environment. Containers also give you more granular control over resources giving your infrastructure improved efficiency.

This decoupling allows container-based applications to be deployed easily and consistently, regardless of whether the target environment is a private data center, the public cloud, or even a developer’s personal laptop. Containerization provides a clean separation of concerns, as developers focus on their application logic and dependencies, while IT operations teams can focus on deployment and management without bothering with application details such as specific software versions and configurations specific to the app.

![VM v. Containers](https://techglimpse.com/wp-content/uploads/2016/03/Container-vs-VMs.jpg)

___
##### Docker

Operators use Docker to run and manage apps side-by-side in isolated containers to get better compute density. Enterprises use Docker to build agile software delivery pipelines to ship new features faster, more securely and with confidence for both Linux, Windows Server, and Linux-on-mainframe apps.

https://www.docker.com/what-docker

##### Kubernetes

Kubernetes is an open-source platform designed to automate deploying, scaling, and operating application containers.

With Kubernetes, you are able to quickly and efficiently respond to customer demand:
  * Deploy your applications quickly and predictably.
  * Scale your applications on the fly.
  * Roll out new features seamlessly.
  * Limit hardware usage to required resources only.

Our goal is to foster an ecosystem of components and tools that relieve the burden of running applications in public and private clouds.

Kubernetes is:
  * __Portable__: public, private, hybrid, multi-cloud
  * __Extensible__: modular, pluggable, hookable, composable
  * __Self-healing__: auto-placement, auto-restart, auto-replication, auto-scaling

Google started the Kubernetes project in 2014. Kubernetes builds upon a decade and a half of experience that Google has with running production workloads at scale, combined with best-of-breed ideas and practices from the community.

https://kubernetes.io/docs/concepts/overview/what-is-kubernetes/

### Databases

A database is a collection of information that is organized so that it can easily by accesses, managed, and updated. A great video for an introduction to relational, graph, document, etc. databases can be found below.

[Martin Fowler Database Presentation](https://www.youtube.com/watch?v=qI_g07C_Q5I)
___
##### PostgreSQL

PostgreSQL is a powerful, open source object-relational database system.

In addition to downloading PostgreSQL, I would also get PGAdmin. It's a nice GUI tool to work with your databases.

https://www.postgresql.org/

##### MongoDB

MongoDB is a free and open-source cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with schemas

MongoDB is used as the database for Eve.

The installation process for mongo is a little confusing. Be sure to use the 'community server' version.

https://www.mongodb.com/

### API's

An Application Programming Interface (API) is a set of subroutine, protocols, and tools for building software applications. An API expresses a software component in terms of operations, inputs, outputs, and underlying types. An API defines functionalities that are independent of respective implementations, which allows definitions and implementations to vary without compromising each other.

In layman's terms, an API is the messenger that takes requests and tells the system what to. Then it will return the response back to you.

![How an API Looks](http://2.bp.blogspot.com/-wdWWtRc-6XY/U9xyb1QH8-I/AAAAAAAADo4/bM_dpi3YKFg/s1600/api+testing+in+postman+tricky+tech+3.jpg)

___
##### Eve Python REST API Framework

Even is an open source Python REST API framework designed for human beings. It allows to effortlessly build and deploy highly customizable, full featured RESTful Web Services.

http://python-eve.org/

##### Postman

Postman is a powerful GUI platform to make API development faster & easier, from building API requests through testing, documentation, and sharing.

https://www.getpostman.com/

### Project Management & Version Control
___
##### Jira

Jira is used for issue tracking and project management. With Jira you can do the following:
  * Clarified view into project state
  * Improved efficiency
  * Detailed status through dashboards and reports
  * Source of truth/ record of accountability
  * Document issues within accounts

https://www.atlassian.com/software/jira

##### GitHub

GitHub is a development platform used to host and review code, manage projects, and build software alongside a community of millions of other developers.

https://github.com/

### Text Editors

Text editors are all about preferences. These are two I use frequently use and would recommend. Other editors used in the academy rotation include Visual Studio Code, Notepad++, and vi/vim.
___
##### Sublime Text Editor

Sublime is my favorite text editor because it's extremely lightweight, very customizable, and in general very easy to use.

The only downside is that you have to pay for the full version. Don't worry, the unpaid one is still great.

https://www.sublimetext.com/

##### Atom

Atom is an open source text editor that's modern, approachable, yet hackable to the core--a tool you can customize to do anything but also use productively without messing with config files.

I'd recommend looking at the marketplace for some a useful plugins. I personally installed the console emulator.

I utilized Atom mainly for markdown files because of the awesome preview feature.

https://atom.io/
___

### Programming Languages

Don't worry if you've never coded before. This portion of the rotation is just an introduction to Python and no previous knowledge is required.

If you're familiar with coding, use it to your advantage to develop a cool project!

##### Python

Python is a high-level programming language used for general-purpose programming. Python is designed with emphasis on code readability and a syntax that allows programmers to express concepts in fewer lines of code than C++ or Java.

Python features a dynamic type system and automatic memory management and supports multiple programming paradigms including, Object-Oriented, imperative, functional, and procedural styles.

I'd recommend working with Python 3.x and higher since Python 2.7 will be coming to EOL in April 2020.

https://www.python.org/

##### Jupyter Notebooks

The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text. Uses include: data cleaning and transformation, numerical simulation, statistical modeling, machine learning and much more.

https://jupyter.org
___

### Additional Resources

##### Slack

Slack is a cloud based team collaboration tool. It brings all your team's communication together, giving everyone a shared space where conversations are organized and accessible

https://slack.com/

##### The Phoenix Project

The Phoenix Project is a novel about IT, DevOps, and helping your business win. It's a quick read and will help you introduce you to the DevOps methodology. The end of the book has some fantastic information and showcases DevOps in use at large companies.

Kevin will give you an electronic copy of the book on Amazon.
___

If you have any additional questions or comments about this document, please don't hesitate to submit an issue through GitHub or contact me at: rtalukder@forsythe.com
