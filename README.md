My personal blog, dedicated to any and all of my personal interests, like photography, Legos, and home and auto repair.

Base Design
===========
My blog is built on top of [Poole][poole_repo]. I took inspiration and a lot of direction from Joshua Lande and his blog post [here][jl_poole].

Page Links in Header
====================
Following instructions in [Joshua Lande's post][jl_poole], I modified the masthead of the 'default.html' layout and added his code for displaying links to the top level pages. Also, the list of top level pages is defined in _config.yml.

Time Zone
=========
Initially, I didn't have a timezone set for the site. This actually caused a problem at one point, because the site builder generated my post with a different date than what I put in the post, after converting the time. This was fixed by setting the `timezone: America/Los_Angeles` in `_config.yml`.

[poole_repo]: https://github.com/poole/poole "Poole repository on GitHub"
[jl_poole]: http://joshualande.com/jekyll-github-pages-poole/ "Joshua Lande's blog post on Jekyll with Poole"
