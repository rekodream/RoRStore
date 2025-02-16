# What is RoRStore?
RoRStore is a Ruby on Rails Store based on Spree.

This app uses:

* Spree as engine
* Ruby 3.3 and Ruby on Rails 7.2
* Mysql

## Prepare
Add your own database.yml by `mv database.yml.example database.yml`, and modify mysql connection info.

## Installation

Make sure you have the following installed:
* Ruby 3.3 - [installation instructions](https://www.ruby-lang.org/en/documentation/installation/)
* Vips - [installation instructions](https://libvips.github.io/libvips/install.html)

```bash
bin/setup
```

If you want to use sample data (products, categories), you can load it using the following command:

```bash
bin/rake spree_sample:load
```