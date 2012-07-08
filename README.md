# jenkins-ci.org

This is the new [Jekyll](http://jekyllrb.com)-powered site for the Jenkins project.


### Beta site

The beta-version of the site is currently running at
[jekyll.jenkins-ci.org](http://jekyll.jenkins-ci.org)

### Running the site locally

You will need the gems located in the `Gemfile`, this typically means running a
`bundle install` on your machine. Once you have Jekyll installed you can
invoke:

    % rake server

Which will run a local server on [localhost:4000](http://localhost:4000) which
should contain the site.

You can incrementally re-generate the site by invoking:

    % rake
