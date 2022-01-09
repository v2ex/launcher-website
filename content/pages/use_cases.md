+++
title = "Use Cases"
path = "use-cases"
template = "page.html"
+++

This page contains a list of useful things you can accomplish with CodeLauncher.

## Web Development

Most modern web development frameworks use a web server on localhost, and developers can start those web servers by running a command. You probably are already using some snippet manager to organize those commands. CodeLauncher is designed for those tasks to make it easier to start and manage web servers for modern web development.

## Tests

Tests in many projects are invoked by a command like:

* `pytest -vvv`
* `cargo test`

You can add those commands as a on demand task in your project. Run them when you need and see the results in the output.


## Static Site Generators

Many popular static site generators like [Jekyll](https://jekyllrb.com/) and [Zola](https://www.getzola.org/) use a `serve` command to monitor changes to the source files and automatically regenerate the site.

You can set working directory to your static site project and run `serve` command with CodeLauncher.