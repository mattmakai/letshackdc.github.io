# Contributing

Contributions are welcome and greatly appreciated! 


## Fix Typos, Grammar Errors, etc
Create pull requests on the 
[GitHub repository](https://github.com/makaimc/letshackdc.github.com/pulls).


## Submit Feedback
The best way to send feedback is to file an issue is on 
[repository\'s issues page](https://github.com/makaimc/letshackdc.github.com/issues).


## Get Started!
If you\'re not familiar with [Pelican](http://docs.getpelican.com/), 
check out the blog post on 
[Getting Started with Pelican and GitHub Pages](http://www.mattmakai.com/introduction-to-pelican.html).

Ready to contribute? Here\'s how to set up 
[Let\'s Hack DC](http://www.letshackdc.com/) for local development.

1. Fork the 
   [letshackdc.github.com](https://github.com/makaimc/letshackdc.github.io) 
   Git repository.

2. Clone your fork locally.

```
$ git clone git@github.com:your_name_here/letshackdc.github.io.git lhdc
```

3. Install your local copy into a Python virtualenv and set up your fork for 
   local development

```
$ virtualenv --no-site-packages venvs/lhdc
$ source venvs/lhdc/bin/activate
$ cd lhdc
```

Note: make changes to the source/content/pages/\*.markdown files then execute a
*make run* command from the source/ directory.

6. Commit your changes and push your branch to GitHub

```
$ git add .
$ git commit -m "Your description of the changes."
$ git push origin gh-pages
```

7. Submit a pull request through the GitHub website.

