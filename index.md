---
layout: page
title: Simulating Robots! 
---

A project activity for [Girls Into Coding](https://www.girlsintocoding.com/) using a online version of the free open source [Webots](https://www.cyberbotics.com/) robot simulator.

This session is designed to be fun! The idea is that we can follow it together online, but that we can be free to move at our own pace.

# Contents
Here is an overview of this webpage!:

* Resources
* What is a robot simulator?
* Why is simulating robots important?
* First steps using the robot simulator
* Making a robot move

# Resources
There's some things that are going to help us with this session, and here's the links to them below. You don't need to click them now! But they might help us as we go along!

* Python cheatsheet
* Webots documentation

# What is a robot simulator?

<div id="qp_all3045813" style="width:100%;max-width:600px;"><link href='//fonts.googleapis.com/css?family=Roboto:400,300,700' rel='stylesheet' type='text/css'><link href='//maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css' rel='stylesheet' type='text/css'><STYLE>#qp_main3045813 .qp_a > SPAN INPUT {display:none;} #qp_main3045813[results='0'] .qp_a > SPAN:before {content:"\f1db"; position:absolute;width:2em;margin-left:-2em;display:block;color:inherit;font-family:'FontAwesome';text-align:center;box-sizing:border-box;border-left:1px solid transparent} #qp_main3045813[results='0'] .qp_a[sel='1'] > SPAN:before {content:"\f192"; color:inherit;} #qp_main3045813 .qp_btna:hover input {background-color:#da69abe6!important;color:#FFF} #qp_main3045813[results='0'] .qp_a:hover {color:#FFF!important;background-color:#d864ad!important} #qp_main3045813[results='0'] .qp_a[sel='1'] {background-color:#da69abe6!important;color:#FFF!important}#qp_all3045813 {max-width:820px; margin:0 auto;}</STYLE><div id="qp_main3045813" fp='d39b44D8-94' results=0 style="padding: 15px;                        text-align: left;                        background: url(//cdn.poll-maker.com/ThemeBG/starsky.jpg) 100% 100% / cover no-repeat;                        background-color: #292062;                        box-sizing: border-box;                        width: 100%;                        overflow: auto;                        font-size: 12px;                        text-align: left;                        background-repeat: no-repeat;                        background-attachment: local;                        background-position: bottom right;                        margin: 0 auto;                        max-width: 820px;                        color:white;                        box-sizing: border-box;                        order: initial;                        -webkit-background-size: cover;                        -moz-background-size: cover;                        -o-background-size: cover;                        background-size: cover"><div style="color: #FFF;                        font-size: 2.0em;                        font-family: 'Roboto',sans-serif,Arial;                        margin-bottom: 0.8em"><div style="padding:0;display:table-cell;vertical-align:middle;text-align:left;line-height:1.3em">What kind of robot</div></div><form id="qp_form3045813" action="//www.poll-maker.com/results3045813xd39b44D8-94" method="post" target="_blank" style="display:inline;margin:0px;padding:0px"><div style="padding:0px"><input type=hidden name="qp_d3045813" value="44043.2311342573-44043.2311257832"><div style="clear: both;                        padding: 20px 5px;                        margin-bottom: 0.8em;                        display: block;                        background:#ffffff1f;                        color: #FFF;                        font-family: 'Roboto',sans-serif;                        font-size: 1.3em;                        line-height: 1;                        box-shadow: 0 1px 2px rgba(0,0,0,.3)" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="padding-left:2em;display:inline-block;cursor:inherit"><input style="float:left;width:20px;height:20px;padding:0px;margin-left:-25px;margin-top:2px;line-height:2em;-webkit-appearance:radio;" name="qp_v3045813" type="radio" value="1" />flying</span></div><div style="clear: both;                        padding: 20px 5px;                        margin-bottom: 0.8em;                        display: block;                        background:#ffffff1f;                        color: #FFF;                        font-family: 'Roboto',sans-serif;                        font-size: 1.3em;                        line-height: 1;                        box-shadow: 0 1px 2px rgba(0,0,0,.3)" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="padding-left:2em;display:inline-block;cursor:inherit"><input style="float:left;width:20px;height:20px;padding:0px;margin-left:-25px;margin-top:2px;line-height:2em;-webkit-appearance:radio;" name="qp_v3045813" type="radio" value="2" />walking</span></div><div style="clear: both;                        padding: 20px 5px;                        margin-bottom: 0.8em;                        display: block;                        background:#ffffff1f;                        color: #FFF;                        font-family: 'Roboto',sans-serif;                        font-size: 1.3em;                        line-height: 1;                        box-shadow: 0 1px 2px rgba(0,0,0,.3)" class="qp_a" onClick="var c=this.getElementsByTagName('INPUT')[0]; if((!event.target?event.srcElement:event.target).tagName!='INPUT'){c.checked=(c.type=='radio'?true:!c.checked)};var i=this.parentNode.parentNode.parentNode.getElementsByTagName('INPUT');for(var k=0;k!=i.length;k=k+1){i[k].parentNode.parentNode.setAttribute('sel',i[k].checked?1:0)}"><span style="padding-left:2em;display:inline-block;cursor:inherit"><input style="float:left;width:20px;height:20px;padding:0px;margin-left:-25px;margin-top:2px;line-height:2em;-webkit-appearance:radio;" name="qp_v3045813" type="radio" value="3" />swiming</span></div></div><div style="clear: both;                                                        padding-left: 0px;                                                        text-align: left;                                                        margin: 0.8em 0 0.8em 0"><a style="display:inline-block;padding-right:0px;box-sizing:border-box;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;-ms-box-sizing:border-box;-o-box-sizing:border-box;text-decoration:none;width:100%" class="qp_btna" href="#"><input name="qp_b3045813" style="border: .08em solid rgba(0,0,0,.1);                         background:#da82b5e6;                        color: #FFF;                        font-family:'Roboto',sans-serif,Arial;font-size:1.4em;cursor:pointer;cursor:hand;-webkit-appearance:none;box-shadow:0 1px 2px rgba(0,0,0,.2);                        width: 100%;                        padding: 20px 5px;                        box-sizing: border-box;                        line-height: 1" type="submit" btype="v" value="Vote" /></a><a style="padding:0px;box-sizing:border-box;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;-ms-box-sizing:border-box;-o-box-sizing:border-box;text-decoration:nonewidth: 100%;margin-top:15px;display: none" class="qp_btna" href="#"><input name="qp_b3045813" style="border: .08em solid rgba(0,0,0,.1);                         background:#da82b5e6;                        color: #FFF;                        font-family:'Roboto',sans-serif,Arial;font-size:1.4em;cursor:pointer;cursor:hand;-webkit-appearance:none;box-shadow:0 1px 2px rgba(0,0,0,.2);                        width: 100%;                        padding: 20px 5px;                        box-sizing: border-box;                        line-height: 1" type="submit" btype="r" value="Results" /></a></div></form><div style="display:none"><div id="qp_rp3045813" style="position:absolute;right:5px;width:5ex;height:2.5em;font-size:1em;text-align:right;overflow:hidden;line-height:2.5em"></div><div id="qp_rv3045813" style="width:0%;padding-right:3px;color:#F4F4F4;font-size: .9em;line-height:2.5em;text-align:right;box-sizing:border-box"></div><div id="qp_rb3045813" style="margin-top:2.5em;display:block;color:#FFFFFF;font-size:0.9em;line-height:1.5em"></div><div id="qp_rva3045813" style="background-color:#da69abe6;line-height: 44px;margin-bottom:-15px;margin-top:-0px"></div><div id="qp_rvb3045813" style="background-color:#da69abe6;line-height: 44px;margin-bottom:-15px;margin-top:-0px"></div><div id="qp_rvc3045813" style="background-color:#da69abe6;line-height: 44px;margin-bottom:-15px;margin-top:-0px"></div></div></div><div style='text-align:center; margin:5px;'><a id="qp_foot3045813" href="https://linkto.run/e/0DLS2NDR">Create Polls</a> with PollMaker</div></div><script src="//scripts.poll-maker.com/3012/scpolls.js" language="javascript"></script>



A [Bootstrap 4](https://getbootstrap.com/) start up project for [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

* A full Bootstrap 4 theme usable both on Github Pages and with a standalone Jekyll.
* Recompiles Bootstrap from SCSS files, which allows to customize Bootstrap's variables and use Bootstrap themes.
* Full support of Bootstrap's JavaScript plugins.
* Supports all features of Github Pages and Jekyll.

## Setup Guide

### Fork this repository

[Go to this repository page on Github](https://github.com/nicolas-van/bootstrap-4-github-pages) and click the `Fork` button on the top right of the page.

### Rename your forked repository

Here we have two possibilities:

* **You want a user or organization website**

  In this case your website's URL will be `http://<your username>.github.io` where `<your username>` is your Github user name.

  Go in the `Settings` page of your repository and rename it to `<your username>.github.io`.

* **You want a project website**

  In this case your website's URL will be `http://<your username>.github.io/<whatever you want>` where `<whatever you want>` can be any valid name for a Github repository.

  Go in the `Settings` page of your repository and rename it to `<whatever you want>`.

### Activate Github Pages on your repository

Go in the `Settings` page of your repository, in the `Github Pages`, under the `Source` parameter, choose `master branch` then `Save`.

### That's it

Your Github Pages website with customizable Bootstrap 4 is now up and running, you can access it using the URL displayed by Github in the `Github Pages` settings.

## Customization Guide

### Modify the configuration

You should at least edit the `_config.yml` file to edit your website's metadata, like the title, description and repository URL.

### Change your theme

This website uses the [Minty](https://bootswatch.com/minty/) Bootstrap theme by default. And you don't want to use the same theme everyone else uses do you?

You can of course modify anything in the `_includes`, `_layouts` and `_sass` folders to customize both the HTML or CSS of your website, possibly referring to the [Bootstrap documentation](https://getbootstrap.com/) or the [Jekyll documentation](https://jekyllrb.com/) when needed. This is a normal part of web development and it is outside the scope of this guide.

But if you don't know where to start I can recommend you to import a theme from [Bootswatch](https://bootswatch.com/).

* Go on [Bootswatch](https://bootswatch.com/) and choose a theme that you like.
* Using the top bar, download its `_variables.scss` and `_bootswatch.scss` files.
* Copy the content of `_variables.scss` in `_sass/_variables.scss`.
* Copy the content of `_bootswatch.scss` in `_sass/_bootstrap_customization.scss`.

That's it, you now have a totally different appearance for you website.

### Modify the content

You probably don't want the present guide to be the front page of your website, so you should edit the `index.md` file. You probably also want to edit or delete the `CONTRIBUTING.md`, `README.md` and `LICENSE.md` files.

Aside from that you can of course create new pages and posts like with any Jekyll website by refering to the [Jekyll documentation](https://jekyllrb.com/).

### Run Jekyll on your computer to speed up testing

Editing your website's content or theme directly on Github is completely possible but, due to the time Github Pages takes to update your website, it will probably be much more effective to work using a local Jekyll installation.

To do so:

* Install the [requirements for Jekyll](https://jekyllrb.com/docs/installation/).
* Type `bundle install` at the root of your project to install the necessary Ruby dependencies.
* Type `bundle exec jekyll serve` to launch the test Jekyll web server that will re-compile your work if you edit it.
* You can then open `http://localhost:4000` in your web browser to see your work-in-progress website.

Please note that, to ensure maximum compatibility with Github Pages, the `Gemfile` of this project references the `github-pages` gem, not Jekyll directly. This implies some differences in behavior compared to the official documentation of Jekyll.

## Known issues

* Bootstrap 4 should normally be post-processed using [Autoprefixer](https://github.com/postcss/autoprefixer). Even if it is possible to use autoprefixer with Jekyll, it is not possible with a classic Github Pages installation without adding some kind of pre-processing before publication. Since this project mostly aims compatibility with Github Pages I prefer to keep it that way. The consequences of this choice is that some Bootstrap features could not work as expected on older browsers.

## How to contribute

Like this project ? [Consider adding a star on Github](https://github.com/nicolas-van/bootstrap-4-github-pages).

[You can also see the contribution guide](https://github.com/nicolas-van/bootstrap-4-github-pages/blob/master/CONTRIBUTING.md).

## Websites using Bootstrap 4 Github Pages

* [My personal blog](https://nicolas-van.github.io/)
* [the wavelet's profile](https://thewavelet.github.io/)
* [roseblood.github.io](https://roseleblood.github.io/)
* [colemannick.github.io](https://colemannick.github.io/)
* [Betty and the Blushtones](http://bettyandtheblushtones.co.uk/)
* [borislouis.github.io](https://borislouis.github.io/)
* [dariusnwadike.github.io](https://dariusnwadike.github.io/)

## Other Github Pages related projects

I'm a fan of Github Pages for the possibilities it offers to anyone to publish a website for free. I have multiple projects that could be of interest if that's your case too:

* [Easy Markdown to Github Pages](https://nicolas-van.github.io/easy-markdown-to-github-pages/)
* [Parcel Github Pages Boilerplate](https://github.com/nicolas-van/parcel-github-pages-boilerplate)

