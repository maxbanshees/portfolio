# banshees.net

Selected works portfolio made with [Jekyll](https://jekyllrb.com/), and hosted on GitHub Pages.

[Max Banshees' sketchbook](https://maxbanshees.com) is hosted on Neocities.

## About Jekyll + GitHub/Neocities Hosting

This site runs on Jekyll, an opensource static site generating platform.

[Mike Dane's Jekyll tutorial series](https://www.youtube.com/watch?v=T1itpPvFWHI&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=1) has more in depth information on Jekyll, as well as hosting through GitHub Pages.

The [GitHub Desktop](https://desktop.github.com/) app can be used to navigate around some issues with uploading to GitHub through the terminal.

Two lines in the _config.yml file may also have to be changed:
```
baseurl: /PROJECT
url: http://USERNAME.github.io
``` 

The [Neocities Command Line Interface](https://neocities.org/cli) can be used if hosting on Neocities.

## Setup

- Clone or download a zip of this project to your computer and navigate to the
  project directory in your terminal
  
- Make sure Ruby is installed, to check if it is, run:
  ```
  ruby -v
  ``` 
  For more information about installing Ruby, refer to the [Ruby installation ](https://www.ruby-lang.org/en/documentation/installation/).

- Install the Jekyll and bundler [gems](https://jekyllrb.com/docs/ruby-101/#gems) from the commandline:
  ```
  gem install jekyll bundler
  ```
  For more information about installing Jekyll, refer to the [Jekyll quickstart guide](https://jekyllrb.com/docs/quickstart/)


- Install Gem dependencies for the project by running:
  ```
  bundle install
  ```
  
- To run the server in your local environment run:
  ```
  bundle exec jekyll serve
  ```
  
- Go to http://localhost:4000/ in your browser

## General information

- Static website
- Uses the Jekyll Feed plugin, as well as (James Fisher's Tag Generator Plugin)[https://jameshfisher.com/2019/05/05/how-can-i-add-tags-to-a-jekyll-blog/]
- Uses gallery, post, and page as the three main layouts

## Licenses

### Underlying source code

Under the [GNU General Public License v3.0](LICENSE), you can adapt and use the source code of this site (but not it's content, i.e: images, videoes, and text) for personal and commercial use, so long as you retain the same license for your own project. See a quick breakdown of what you can and cant do [here.](https://tldrlegal.com/license/gnu-lesser-general-public-license-v3-(lgpl-3))

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)
