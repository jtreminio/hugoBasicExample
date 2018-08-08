hugoBasicExample
==========

This is an example site for [Hugo](https://gohugo.io/).

It is intended to be used in conjunction with my blog post,
[Setting Up a Static Site with Hugo and Push to Deploy](https://jtreminio.com/blog/setting-up-a-static-site-with-hugo-and-push-to-deploy/)

# Using

Clone this repo:

    git clone git@github.com:jtreminio/hugoBasicExample.git
    cd hugoBasicExample

Clone the starter template repo:

    git clone git@github.com:nanxiaobei/hugo-paper.git themes/git@github.com:nanxiaobei/hugo-paper.git

Start the Hugo server:

    ./bin/hugo-server

Open http://localhost:1313/

# Other tools

To publish static files:

    ./bin/hugo-publish
    
Files are generated into `/public`

To minify CSS/HTML/JS files in `/public` (after publish):

    ./bin/minify
    
To run an nginx container from files in `/public` (after publish):

    ./bin/nginx
