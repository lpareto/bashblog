bashblog
========

A Bash script that handles blog posting

You can read [the initial blog post](http://mmb.pcb.ub.es/~carlesfe/blog/creating-a-simple-blog-system-with-a-500-line-bash-script.html) for more information.

Usage
-----

Download bb.sh into a public folder of yours and run it:

    ./bb.sh

This will show the available commands

To create your first post, just do:

    ./bb.sh post

When you're done, access the public URL for that folder and you should see the index
file and a new page for that post!

Features
--------

- Simple creation and edition of the posts with your favorite text editor
- Post preview
- Save posts as drafts and resume later
- Transformation of every post to its own html page, using the title as the URL
- Generation of an index.html file with the latest 10 posts
- Generation of an RSS file! Blog's magic is the RSS file, isn't it...?
- Generation of a page with all posts, to solve the index.html pagination problem
- Rebuilding the index files without the need to create a new entry
- Google Analytics support
- Feedburner support
- Auto-generated CSS support
- Headers, footers, and in general everything that a well-structured html file has
- xhtml validation, CSS validation, RSS validation by the w3c
- Everything contained in a single 700-line bash script!
- A simple but nice and readable design, with nothing but the blog posts

Non features (not planned)
--------------------------

- Comments. Would need a CAPTCHA or another antispam mechanism. Comments are handled through twitter, with a Twitter button

Read the CHANGELOG section of the script header for more updates