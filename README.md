# Shef_CodeFirst_Python


## Running the site
The course site has now, more or less, been converted to use Jekyll, the static site generator supported by GitHub.
This has some benefits include the ability to use templates to avoid having to re-write/copy-and-paste common
parts of the site, in the same spirit as that taught in the Python course!

So, to correctly load up the site (containing mostly partial HTML files with Jekyll specific meta-data such as the
[Front Matter](https://jekyllrb.com/docs/front-matter/)), first you need to install:
- Ruby v2.5.1 or higher. Check out this link for more instructions on [how to install Ruby for your OS](https://www.ruby-lang.org/en/downloads/);
- After Ruby has been installed, run `gem install bundler jekyll` from your terminal.

Once you have installed all of the above pre-requisite software, run the following:
```bash
$ cd shefcodefirst-python # Assuming terminal is pointing one directory level away from the course site directory, this changes it to point at it
$ bundle exec jekyll serve 
```

Course materials for the Advanced Python course in Sheffield 🤖

I created a custom stylesheet that overrides some of the default styles from the 'reveal.js' themes. This should work with both the 'white' and the 'black' themes. Feel free to use the one you like the most. You only need to modify this directly on the .html file you are working on.

You can check the demo one here: [https://darrenvong.github.io/shefcodefirst-python/](https://darrenvong.github.io/shefcodefirst-python/)


To start creating your own slides just fork the repository, go to the `gh-pages` branch and copy the demo `slide.html` file, rename it with the session number (e.g session1) and get working. Once you have completed your slides make a pull request and assign any other of your fellow instructors as a reviewer. They will then merge your PR.

The slides use reveal.js the GitHub repository for this can be found [here](https://github.com/hakimel/reveal.js/). It has all the documentation in case you want to have a look at it to add fragments, special slides or anything. 
 
