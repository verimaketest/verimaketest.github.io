# Group website

This repository contains the source code to build website for the group. It is built using [Hugo](https://gohugo.io/) with the research group template from [Wowchemy](https://wowchemy.com/).

The template code from Wowchemy was written by [George Cushen](https://georgecushen.com/), and is redistributed under the MIT License.

# Instructions

## Update the list of publications

You can manually add entries to the `publications.bib` file in `/static/`. An easy way to add all relevant publications is to go to [this INSPIRE page](https://inspirehep.net/authors/1020224), click on `cite all`, download the `bib` file, rename it to `publications.bib`, and replace the previous one.

## Add a new member profile

Each profile is located in a directory in `/content/authors/`, and there is a template in `/templates/`. Replace `avatar.jpg` with a picture named `avatar.xxx` (can be jpg, png, ...), and edit `_index.md`, which is pretty self-explanatory.

## Build the site

GitHub will build the site  by itself, so you don't have to worry about it. If you are making big modifications and prefer to see the changes live as you make them, then download the extended edition of [Hugo](https://gohugo.io/), and follow the (very easy) instructions on that website.
