About
=====

This is a demo for a short talk about agile development and tools for agile development.

The slides will be available soon.


Usage
=====

Building the pages
------------------

The vagrant box is configured to install nginx and serve a static site generated by jekyll.

To generate the pages you need to have jekyll installed

```
sudo apt-get install rubygems
sudo gem install jekyll
```

Then you can generate the pages running

```
cd site
jekyll build
```


Runnig the server
-----------------

You will need to have a recent version of [Vagrant](http://www.vagrantup.com)

```
cd server
vagrant up
```

Once the server has booted, you can see the page in `http://localhost:8080`