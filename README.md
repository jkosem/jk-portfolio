# README

This portfolio site is a work in progress. Hopefully you should gather that. It's all open source, so mind the license and give credit, although in this case maybe not much is deserved, where it's due.

## Dependencies

Ruby 2.6 and above (to get this version working at any rate)

Jekyll 4.1 and above

All the hosting is done on the Github page. Link over up there on the right with the URL.

## How to use

1. Have everything installed like above, namely Ruby and Jekyll
2. Need to build `jekyll build` to release
3. Can also, whilst developing, use `jekyll serve --livereload` which will upon saving, reload the file in browser at `http://localhost:4000/`
4. Need to `git add .`, `git commit -m <message>` and `git push` to get it to GitHub to get it to be available at URL
5. Check deployments at [https://github.com/jkosem/jk-portfolio/deployments](https://github.com/jkosem/jk-portfolio/deployments)
6. If you screw around with both the gem files and/or trying to go back to old versions, and end up getting tons of Ruby errors and that, it's a lot of times easier to just start a new Jekyll project and copy things into it. This can be done either by `jekyll <project> new` which does the minimal base install with the Minima theme, or `jekyll <project> new --blank` which creates the extensive folders which is more or less complete.

## Links, reference, etc.

A lot of the things [here](https://github.com/jekyll/jekyll/issues/3984) worked

[This page](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_install_jekyll_on_mac.html) was also helpful

[This tutorial](https://www.youtube.com/watch?v=-LhLFeuvc38) was probably the easiest to follow

[Navigation](https://learn.cloudcannon.com/jekyll/simple-navigation/)

[Issues with directories and CSS not showing up properly](https://github.community/t/css-not-being-applied-in-pages/10466/10)

This guy has a good post on [How to Make a Jekyll Site/Blog](https://brianm.me/posts/how-to-make-jekyll-site-blog)

I nicked a lot of things on how to do posts from [here](https://www.section.io/engineering-education/build-a-jekyll-site/).

I'm rubbish at doing menus properly from memory, so [the classic float menu at W3C](https://www.w3schools.com/Css/css_navbar_horizontal.asp)

This tutorial on [How to Set up GoDaddy Domain with GitHub Pages](https://hackernoon.com/how-to-set-up-godaddy-domain-with-github-pages-a9300366c7b) worked like a charm. It took a bit (2 hours?) for the HTTPS to update, but once that was done it was cool.

[This page](https://jhooq.com/github-permission-denied-publickey/) showed how to sort out the SSH keys thing fairly easily.
