# pentaglobal-web

The Penta Global Blockchain Foundation website built with Hugo, NodeJS and Gulp

# Introduction / Getting Started

'Penta' or 'PNT', short for Penta Network, is a next generation blockchain platform for both public and private projects. With an emphasis on contributing to the real economy, Penta is building the world’s most inclusive, equitable, and decentralized blockchain community.These instructions will get you a copy of the website project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Prerequisites and Overview
For development and to build the Penta website, you will need [Hugo](https://gohugo.io/), [Node](http://nodejs.org/) and [Gulp](https://github.com/gulpjs/gulp) installed on your environement. What follows are installation notes from the respective readme's.

### What is NodeJS?
Node.js® is a JavaScript runtime built on [Chrome's V8 JavaScript engine](https://developers.google.com/v8/). As an asynchronous event driven JavaScript runtime, Node is designed to build scalable network applications.

### What is Gulp?  
- *Automation* - gulp is a toolkit that helps you automate painful or time-consuming tasks in your development workflow.
- *Platform-agnostic* - Integrations are built into all major IDEs and people are using gulp with PHP, .NET, Node.js, Java, and other platforms.
- *Strong Ecosystem* - Use npm modules to do anything you want + over 2000 curated plugins for streaming file transformations
- *Simple* - By providing only a minimal API surface, gulp is easy to learn and simple to use

### What is Hugo?
Hugo is a static HTML and CSS website generator written in Go. It is optimized for speed, ease of use, and configurability. Hugo takes a directory with content and templates and renders them into a full HTML website.

Hugo relies on Markdown files with front matter for metadata, and you can run Hugo from any directory. This works well for shared hosts and other systems where you don’t have a privileged account.

Hugo renders a typical website of moderate size in a fraction of a second. A good rule of thumb is that each piece of content renders in around 1 millisecond.

Hugo is designed to work well for any kind of website including blogs, tumbles, and docs.

Why Hugo? Good question, and one that is answered in this [article](https://code.tutsplus.com/tutorials/make-creating-websites-fun-again-with-hugo-the-static-website-generator-written-in-go--cms-27319). The upshot is that for many websites, including for Penta, a database backed system, or one hosted by a service like WordPress is too much technology for the job at hand. For our site we wanted to:

- deliver our message of what Penta Global is building for blockchain in a clear way
- provide an up to date blog of our activities and announcements that is easy to manage
- separate site maintenance and content so our teams around the world could contribute without expertise with the underlying html (separation of concerns)
- host a very fast loading site on any device, our users should be happy reading about Penta and not 'bloated'


# Installation
## Node

Node is easy to install and includes [NPM](https://npmjs.org/).
You should be able to run the following terminal command after the installation procedure
below.

    $ node --version
    v0.10.24

    $ npm --version
    1.3.21

#### Node installation on OS X

You will need to use a Terminal. On OS X, you can find the default terminal in
`/Applications/Utilities/Terminal.app`.

Please install [Homebrew](http://brew.sh/) if it's not already done with the following command.

    $ ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"

If everything when fine, you should run

    brew install node

#### Node installation on Linux

    sudo apt-get install python-software-properties
    sudo add-apt-repository ppa:chris-lea/node.js
    sudo apt-get update
    sudo apt-get install nodejs

#### Node installation on Windows

Just go on [official Node.js website](http://nodejs.org/) & grab the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it.

    $ git clone https://github.com/ORG/PROJECT.git
    $ cd PROJECT
    $ npm install
---
## Gulp
There are a few ways to install:
* gulp v4.0.0 - `npm install gulp@next`
* gulp v4.0.0-alpha.3 - `npm install gulpjs/gulp#v4.0.0-alpha.3`
* gulp v3.9.1 - `npm install gulp`
---
## Hugo

To use Hugo as your site generator, simply install the Hugo binaries.
They have no external dependencies.

To contribute to the Hugo source code or documentation, you should [fork the Hugo GitHub project](https://github.com/gohugoio/hugo#fork-destination-box) and clone it to your local machine.

Finally, you can install the Hugo source code with `go`, build the binaries yourself, and run Hugo that way.
Building the binaries is an easy task for an experienced `go` getter.

### Install Hugo as Your Site Generator (Binary Install)

Use the [installation instructions in the Hugo documentation](https://gohugo.io/overview/installing/).

### Build and Install the Binaries from Source (Advanced Install)

#### Prerequisite Tools

* [Git](https://git-scm.com/)
* [Go (at least Go 1.11)](https://golang.org/dl/)

#### Fetch from GitHub

Since Hugo 0.48, Hugo uses the Go Modules support built into Go 1.11 to build. The easiest is is to clone Hugo in a directory outside of `GOPATH`, as in the following example:

```bash
mkdir $HOME/src
cd $HOME/src
git clone https://github.com/gohugoio/hugo.git
cd hugo
go install
```
*If you are a Windows user, substitute the $HOME environment variable above with %USERPROFILE%.*



# Building

Before anything else, the required nodejs dependencies need to be installed using the [npm](https://www.npmjs.com/) package manager:
```
$ sudo npm install
```
The [Hugo documentation](https://gohugo.io/getting-started/) has everything you need for working with the generator. A single terminal command rebuilds the Penta site from source (without optimization):

```
$ hugo
```
If you are feeling unstatisfied and really feel it should take longer than a couple of seconds to generate the complete Penta website, here is an [article](https://opensource.com/article/18/3/start-blog-30-minutes-hugo) about Hugo that can help fill in some time with reading. But, if you are like us, we want to quickly get you on your way to building awesome blockchain DAPPS using the Penta platform.

Gulp tasks are used to post-process the website build for optimization and deployment. The default task to optimize everything:
```
$ gulp
```

# Local Preview and Testing
A live-reloading local webserver on port 8000 is available for local testing and site preview with a gulp task:
```
$ gulp server
```
It is recommended that one terminal session is used for site rebuilds and a second session to launch the webserver.

# TODO: (finish documentation from here :)
# Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


