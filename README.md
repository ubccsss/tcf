# tcf

Website for the Technical Career Fair.

## Contributing

We welcome contributions of any kind including pages, suggestions, bug reports,
pull requests etc. We would love to hear from you.

#### Important files folders

##### `config.yaml`

Configuration data for the site. The sidebar menu and event details are defined here. 
Adjusting `params.date` will also change various titles to be "TCF{year}".

##### `content/`

Contains content files corresponding to every page, including the companies list.

##### `content/companies/`

Each markdown file here represents a company at the career fair. 
The company `title`, `website`, and `booth` number are specified in the front matter.

##### `layouts/`.

HTML template files for the site. These files transform markdown from `content/` into HTML.

##### `static/`

Static files that are copied into the website with no modifications. Images are placed here.

### Build

To view the site locally, you need to clone this repository:

```bash
git clone https://github.com/ubccsss/tcf.git
```

You'll also need to
[install Hugo](https://gohugo.io/getting-started/installing/). 

Then to view the website in your browser, run Hugo and open up the link:

```bash
▶ hugo server

Building sites ...
.
.
Serving pages from memory
Web Server is available at http://localhost:1313/ (bind address 127.0.0.1)
Press Ctrl+C to stop
```
