# Hugo + PicoCSS

## Installation

Install Hugo and create a new site. See [the Hugo documentation](https://gohugo.io/getting-started/quick-start/) for details.

### Hugo module

Initialize your site as hugo module:

    $ hugo mod init github.com/USERNAME/SITENAME

Add hugo-picocss module as a dependency of your site:

    $ hugo mod get github.com/ohzqq/hugo-picocss

## Configuration

params:
  picocss:
    layout: container-fluid
    breadcrumbs: true
    color: amber
