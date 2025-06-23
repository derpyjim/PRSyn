# Synlith

Site upkeep


[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/)

## Setup

1. Edit site and author details in `_config.yml`.
2. Add Google Analytics and Disqus keys to `_config.yml`.
3. Get a workflow going to see site output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Hydra is already optimised for adding, updating and removing pages, staff, advice, company details and footer elements in CloudCannon.

### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff** collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with formsubmit.co.
* Sends email to the address listed in company details.

### Staff

* Reused around the site to save multiple editing locations.
* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Set in the *Data* / *Navigation* section.

### Footer

* Set in the *Data* / *Footer* section.
