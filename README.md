# BitDevs LA

Simple Zola site for hosting all of the links from meetups past and future.

## Development

You'll need [Zola](https://www.getzola.org/documentation/getting-started/installation/) to run the
site locally. Once they're setup:

* Clone the repository and go into the directory
* Run `zola serve`
* Go to http://localhost:1024

## Making a Post

To make a new post, make a new file in `content` directory with a title of
`YYYY-MM-DD-title-goes-here.md`. At the top of the file you'll want to provide the
following information:

```md
+++
title = "<title goes here>"
template = "post.html"
[extra]
meetup_id = "<optional meetup id goes here>"
+++
```

After that, it's just simple markdown. The site will auto-generate the rest.

## Changing Site Data

All site configurations are contained in `config.toml`.

## Attributions

Thanks to [BitDevs NYC](https://github.com/BitDevsNYC/BitDevsNYC.github.io) for the
Jekyll site this site is based on.