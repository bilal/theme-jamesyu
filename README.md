theme-jamesyu
=============

[Jekyll-Bootstrap](http://jekyllbootstrap.com/) theme version of [James Yu's jekyll template](https://github.com/jamesyu/jamesyu_jekyll_template).

Example: [jamesyu.org](http://jamesyu.org).

A nice feature of the theme is the [about page](http://www.jamesyu.org/about/), which can be used to list your projects.

Quick Setup
-----------

* Install [Jekyll](https://github.com/mojombo/jekyll): 

  `$ gem install jekyll`
  
* Get Jekyll-Bootstrap:

  ```
  $ git clone https://github.com/plusjade/jekyll-bootstrap.git 
  $ cd jekyll-bootstrap
  ```
* Install the theme:

  ```
  $ rake theme:install git="git://github.com/bilal/theme-jamesyu.git"
  ```
* Copy `about.html` from theme:

  ```
  $ cp _includes/themes/jamesyu/about.html .
  ```
* Start Jekyll locally:

  ```
  jekyll --server
  ```
  
  Check it out at [http://localhost:4000](http://localhost:4000)
  
