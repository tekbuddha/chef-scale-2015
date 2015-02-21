# Introduction to Chef

Chef is an automation platform that transforms infrastructure into code. This is a hands-on tutorial that will cover the basics that everyone needs to know about how to use Chef for system and infrastructure management.

### Who should attend:
Anyone responsible for managing infrastructure especially those who are interested in automating the provisioning and management of said infrastructure using state-of-the-art tools and practices.

### Take back to work:
A working code base that includes samples for building out testable infrastructure components.

Topics include:
* Introduction to Chef
* Test-driven Development (TDD)
* unit testing - ChefSpec
* integration testing - ServerSpec

### Student Workstations

IP Addresses for each student can be found in [this gist](https://gist.github.com/tekbuddha/).

### Materials

This repository will include the slides for the class in both PowerPoint and PDF.  This repository will also include all code generated as part of this class.

### Prerequisites

* Watch [Overview of Chef](http://learn.getchef.com/fundamentals-series/week-1/) (45 minutes) on learnchef.com.
* Complete the Workstation Requirements, listed below
* Comfort with a command-line text editor such as [vim](http://www.openvim.com/tutorial.html), [emacs](http://www.gnu.org/software/emacs/tour/), or [nano](http://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/).

#### Nice to haves

These prerequisites aren’t actually required but will be helpful in making the class experience delightful:

* a working knowledge of Git
* an account on GitHub

#### Workstation Requirements

You should bring a wifi-enabled laptop to the workshop. The following operating systems have been tested as workstation systems with the hands on exercises:

A wifi-enabled laptop to the workshop, either

* Ubuntu 12.04+
* Mac OS X 10.8+
* Windows 7+

#### Required software to be installed before class

You should install the following required software before the workshop starts.

* [ChefDK](http://downloads.getchef.com/chef-dk) 0.3.5+
* SSH/SCP (OpenSSH, puTTY/WinSCP or equivalent)
* Programmer’s text editor ([Atom](https://atom.io/), Vi/Vim, Emacs, [Sublime Text](http://www.sublimetext.com/), or equivalent)

#### Note for Ruby Developers

If you’re currently using rvm, rbenv, chruby, or some other Ruby version manager, you may need to disable that to have ChefDK work as expected during class. See the [Using ChefDK as Your Primary Development Environment](https://github.com/opscode/chef-dk#using-chefdk-as-your-primary-development-environment) section of the ChefDK README for more information.

#### Nice to haves

Though we might not make use of these in the class, you’ll probably want them afterwards

* Vagrant
* Virtual Box

#### Serverspec Documentation
ServerSpec recently went through a revision change. Here's a link to the most recent documentation of available resource types with ServerSpec: [ServerSpec Resource Types](http://burtlo.github.io/serverspec.github.io/resource_types.html)