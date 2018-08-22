# NOTE
This theme is a work-in-progress until this notice is removed.  It likely doesn't work at all and definitely should not be used yet.

I have never written a hugo theme before and I am VERY heavily basing my work on another HTML5 UP I have found that is also on github here:

https://github.com/curttimson/hugo-theme-dopetrope

# /NOTE

# TXT

TXT theme ported from [HTML5 UP](https://html5up.net/) for use with the [Hugo static site generator](https://gohugo.io/).

Theme includes ability for:

 - Portfolio items
 - Blog posts

![](images/device-screenshots.jpg)

## Demo

https://hugo-txt.erratic.space

## Setup

### Configuration

See the demo's configuration as an example:

https://github.com/ctrowat/hugo-theme-txt/blob/master/exampleSite/config-prod.toml

### Front Matter

 - `description`
 - `date`
 - `thumbnail`
 - `image`
 - `title`
 - `slug`
 - `author`
 - `draft`
 - `disqusid` - See [Blog Comments](#blog-comments)
 - `hidesidebar` - Set to false to hide the sidebar on specific pages

### Blog Comments

Blog comments are supported by Disqus. Once set up comments will be displayed on the blog posts as well as a count on the homepage.

If not set up already, create a Disqus account and enter the account name in the `config.toml` file:

```
[params.settings]
    disqus = "hugo-dopetrope"
```

To display comments on a post a unique ID will need to be added to the specific blog posts. Enter these IDs in the front-matter of the post files themselves:

```
disqusid = "1"
```

### Cover Image

The cover image URL is hard-coded, therefore to replace this add an image to the following location in your Hugo application:

```
/static/images/frontpage.jpg
```

## Development

### Example Site Deployment

```
$ hugo --config config-prod.toml
```

## Original Theme Credits

 - [TXT by HTML5 UP](https://html5up.net/txt)

## License

This hugo theme is licensed under the [Creative Commons Attribution 3.0 License](https://creativecommons.org/licenses/by/3.0/). 

Read More - [LICENSE](LICENSE)