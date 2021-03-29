# How to use this site
- install Ruby if you're on windows ([use this link](https://rubyinstaller.org/))
- install jekyll and the Ruby package installer, which is called "bundler":
  - `gem install jekyll bundler`

Then clone the site and also get a local copy of the content directory:
- `git clone git@github.com:DigitalHistory/covid-jekyll-site.git`
- `git submodule init` 
- `git submodule update`

Now, get everything you need up and running:
- `bundle install`
- `bundle exec jekyll serve`

now navigate to  http://localhost:4000  and see if you can see the site
