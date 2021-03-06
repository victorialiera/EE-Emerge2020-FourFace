# EE-Emerge 2020: Four Face

Provide an introductory paragraph, describing:

* What your project does
* Link to project home page

## Table of Contents

1. [About the Project](#about-the-project)
1. [Project Status](#project-status)
1. [Getting Started](#getting-started)
    1. [Dependencies](#dependencies)
    1. [Building](#building)
    1. [Installation](#installation)
    1. [Usage](#usage)
1. [Release Process](#release-process)
    1. [Versioning](#versioning)
    1. [Payload](#payload)
1. [How to Get Help](#how-to-get-help)
1. [Further Reading](#further-reading)
1. [Contributing](#contributing)
1. [Authors](#authors)
1. [Acknowledgements](#acknowledgements)

# About the Project

Here you can provide more details about the project
* What features does your project provide?
* Short motivation for the project? (Don't be too long winded)
* Links to the project site

```
Show some example code to describe what your project does
Show some of your APIs
```

**[Back to top](#table-of-contents)**

# Project Status

Show the build status if you have a CI server:

[![Build Status](http://your-server:12345/job/badge/icon)](http://your-server:12345/job/http://your-server:12345/job/badge/icon/)

Describe the current release and any notes about the current state of the project. Examples: currently compiles on your host machine, but is not cross-compiling for ARM, APIs are not set, feature not implemented, etc.

**[Back to top](#table-of-contents)**

# Getting Started

This section should provide instructions for other developers to

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## Dependencies

### Required 
In order to build the firmware, [TI Code Composer](https://software-dl.ti.com/ccs/esd/documents/ccs_downloads.html) should be installed. When prompted select to add support for MSP430 and MSP432 microcontrollers. 

### Optional
Segger J-Link support can be added for MSP432, but is not required.

## Getting the Source

This project is [hosted on GitHub](hhttps://github.com/oceanofthelost/EE-Emerge2020-FourFace). You can clone this project directly using this command:

```
git clone https://github.com/oceanofthelost/EE-Emerge2020-FourFace
```

This will create a new root folder "EE-Emerge2020-FourFace" that will contain all projects for Four Face.

## Installation

1. Open Code Composer Studio
1. Create a new workspace 
    * File -> Switch Workspace -> Other
1. Browse to where the project repository was closed. 
1. Press launch
1. Import projects
    1. Project -> Import CCS Projects
    1. Press Browse
    1. Select root folder that was cloned.
    1. Press OK 
    1. Checkmark all projects
    1. Press Finish
1. Build each project one by one

## Building

Instructions for how to build your project

```
Examples should be included
```
## Flashing

If you have formatting checks, coding style checks, or static analysis tests that must pass before changes will be considered, add a section for those and provide instructions



**[Back to top](#table-of-contents)**

# How to Get Help

For help please contact one of the project [authors](#release-process).

**[Back to top](#table-of-contents)**

# Authors

* Patrick Mackle
* Anthony Pham
* Sophie Bolotin
* Noah Tarr
* Vanessa Liera
* Victoria Liera
* Michelle Acoba
* Christian Gonzalez
* Sean Alling

**[Back to top](#table-of-contents)**

# Acknowledgments

UC Davis
Texas Instruments

**[Back to top](#table-of-contents)**
