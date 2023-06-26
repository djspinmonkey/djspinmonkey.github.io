# Github Pages Blog

## Setup

Install gems with `bundle install`

To run the site locally, us `jekyll serve` and visit `127.0.0.1:4000`. There
are a few different command-line options you can pass, depending on what you
want. Use `--livereload` to automatically reload the site when changes are
detected, and `--drafts` to include posts in the `_drafts` folder as well.

## Posting

There's a CLI to create posts and drafts. The `NAME` will be used as the
file-name, which is also used as the URL slug. It's added as the title of the
post in the metadata, which you can edit. The URL won't change unless you
change the filename.

| Command          | Description                                                 |
| ---------------- | ----------------------------------------------------------- |
| draft NAME       | Creates a new draft post with the given NAME                |
| post NAME        | Creates a new post with the given NAME                      |
| publish  PATH    | Moves a draft into the `_posts` directory and sets the date |
| unpublish PATH   | Moves a post back into the `_drafts` directory              |
| page NAME        | Creates a new page in sidebar with the given NAME           |
| rename PATH NAME | Moves a file to a given NAME and sets the title and date    |

## Plugins

`jekyll-paginate` for a paginated main page

`jekyll-gist` to embed gists with simple syntax

`jekyll-compose` provides cli for post/publish workflow

`jemoji` to add github/slack style emoji syntax
