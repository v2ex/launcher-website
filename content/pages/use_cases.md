+++
title = "Use Cases"
path = "use-cases"
template = "page.html"
+++

On this page, you'll find a list of useful things you can achieve with CodeLauncher.

## Web Development

Most modern web development frameworks use a web server on localhost, and developers can start those web servers by running a command. You may already be using a snippet manager to organize those commands. CodeLauncher is designed for such tasks, making it easier to start and manage web servers for modern web development.

## Tests

Tests in many projects are invoked by a command like:

* `pytest -vvv`
* `cargo test`
* `swift test`

You can add those commands as an on-demand task in your project, running them when you need to and seeing the results in the output.

<p>
  <picture>
  <source srcset="/screenshots/swift-test.webp" type="image/webp">
  <img src="/screenshots/swift-test.png" alt="swift test" class="screenshot">
  </picture>
</p>

## Static Site Generators

Many popular static site generators like [Jekyll](https://jekyllrb.com/) and [Zola](https://www.getzola.org/) use a `serve` command to monitor changes to the source files and automatically regenerate the site.

You can set working directory to your static site project and run `serve` command with CodeLauncher.

<p>
  <picture>
  <source srcset="/screenshots/CodeLauncher-screenshot-1.webp" type="image/webp">
  <img src="/screenshots/CodeLauncher-screenshot-1.png" alt="zola serve" class="screenshot">
  </picture>
</p>