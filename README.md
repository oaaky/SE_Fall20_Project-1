# CodeTime - A time tracking plugin for text editors [G23 Project 1]
[![GitHub license](https://img.shields.io/github/license/oaaky/SE_Fall20_Project-1)](https://github.com/oaaky/SE_Fall20_Project-1/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/oaaky/SE_Fall20_Project-1.svg?branch=master)](https://travis-ci.org/oaaky/SE_Fall20_Project-1)
![GitHub](https://img.shields.io/badge/language-python-blue.svg)
![GitHub issues](https://img.shields.io/github/issues/oaaky/SE_Fall20_Project-1)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/oaaky/SE_Fall20_Project-1)
![YouTube Video Views](https://img.shields.io/youtube/views/CL5W7C9Jw_c?style=social)


### Promo Video
[![CodeTime Promo Video](https://img.youtube.com/vi/CL5W7C9Jw_c/0.jpg)](https://www.youtube.com/watch?v=CL5W7C9Jw_c)

### What is the product?

In a nutshell, this is an extension for text editors which would let developers analyze the time it takes for them to write code in various languages broken down by projects and files they are working on. The primary purpose of such an extension is to allow developers to see the tasks that took more time for them to build and plan accordingly in the future.

### How to setup this plugin?

- Open sublime text.
- Go to preferrences -> Browse packages.
- A new window containing Sublime packages will open up. Let's call this folder `SublimePackagesFolder`.
- Open terminal and go to `SublimePackagesFolder`.
- Clone this repository inside `SublimePackagesFolder`. (This makes sure that Sublime recongnizes our plugin package to execute)

### How to check if the plugin is working?

- Once the repository is cloned in `SublimePackagesFolder`, Open sublime text.
- Open a project/file the you wish to work on.
- Go to `View` -> `Show Console`.
- Now at every action (open, save, switching file), you should be able to see corresponding log entries in console.