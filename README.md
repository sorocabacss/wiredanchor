# wiredanchor
WiredAnchor is a web project.
It creates a stylesheet for links in texts so that they are more conspicuous and better perceived by users.
As a result of this, links can be better marked and the user does not have to search for them in a time-consuming way.

If you If you want to participate in this project, create a fork first. After pushing the changes to your local repository, you can then create a pull request.

## Using Grunt and SCSS
`cd` into your project directory and run `npm install` to install Grunt and other dependencies.

Now run `grunt watch` to have Grunt watch your SCSS file for changes to compile into the CSS file.

Never edit the CSS file directly; always work from the SCSS file as any changes made in the SCSS file will override changes in the CSS file once Grunt is run.

## Dependencies

Ensure that your system has <a href="https://www.ruby-lang.org/en/documentation/installation/">Ruby</a> installed, as well as <a href="https://nodejs.org/en/">NodeJS</a>.

To install Grunt on your system, open up your command line and run `npm install -g grunt-cli` to install Grunt globally on your machine.