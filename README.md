hackathon2016
==============

This repo is for the homepage for the 2016 hackathon.

It is made in Jekyll, but otherwise it is just files that may be edited, merged and so on like any other github text based project.

Common tasks
-----------------

### Updating talks

In each `_techtalks_xxx` directory there is a subdirectory called `talks`.

The files contains the following
> ---
> layout: talk
> title: This text is shown as the title
> presenter: This text is shown as the presenter
> time: e.g. "15:10". This is shown as time and the sorting is based on this
> description: This is the description. It may include <em>html</em>
> ---

The name of the file is not used.


To use
-----------

1. [Fork it](https://help.github.com/articles/fork-a-repo/)
2. [Clone it](https://git-scm.com/docs/git-clone)
3. [Install jekyll](https://jekyllrb.com/docs/installation/)
4. `cd ealtechevents`
5. `bundle install --path .gem`
5. `bundle exec jekyll serve` or `bundle exec jekyll serve --host 0.0.0.0`
6. go to [http://localhost:4000](http://localhost:4000) to see the result

Update the site, issue a git commit, push it and do a [pull request](https://help.github.com/articles/using-pull-requests/) to get it included in the live website.

Please note we are using the gh-pages branch enable the github feature that automatically creates the [github.io website](http://moozer.github.io/hackerthon2016).

Feedback
----------

Feel free to copy, clone and whatever and send pull requests if you feel you have imporvements for the site.

Or you can send me an [email](mailto:bigmoozer@gmail.com).
