
# Fortify Developer Guide

This guide is used to help unify the Fortify production documentation.
It includes information that help developers to quickly get started with our products and tools.

The site was built with [MkDocs](https://www.mkdocs.org/) and the styling was applied using [MkDocs  material](https://squidfunk.github.io/mkdocs-material/)

## Requirements
- python 3.11+
- pip 22.3.1+

## Download the repository

```
git clone git@github.com:techtimefly/fortify-dev-guide.git
```

## (Optional) Python Virtual Enviroment
It's recommended to create a python virtual environment in order to avoid conflicting with global python packages on the system

```
python -m pip -U install virtualenv

# navigate into the project folder and create the virtual environment

python -m virtualenv .env

# activate the virtual env on Windows

.env\scripts\activate

# activate the virtual env on linux/mac
.env\bin\Activate

```
## Installing
```
python -m pip install -r requirements.txt
```

## Running the application

```
python -m mkdocs serve
```

By defaul the application will be served on port 8080 and will be accessible at http://localhost:8080


## Running in production

The following syntax specifies the IP address, port, and disables live reloading

```
python -m mkdocs server -a ip:port --live-reload=false
```

## Slide Presentations
The ability to create presentations is made available though the Reveal.js libraries.

Within the `docs/slides/` directory there is are `.html` and .`md` files that share the same prefix.

Example:
- demo_slide.html (full page slide presenation)
- demo.md (iframe of the slide presentation)

The markdown files are used to show slides within an iframe while maintaing the navigation of the overall site.

The html files are the raw presentations that are viewed in full screen.

Recommend taking a look at `docs/slides/demo.html` and `docs/slides/demo.d` to see how these are implemented.

You can view those pages by running this application and navigation your browser to the urls below to see the slides
- http://localhost:8000/slides/demo/
- http://localhost:8000/slides/demo.html

You can copy `docs/slides/template.html` and `docs/slides/template.md` to get started it your own slides.

More more info an how to work with Reveal.js see the [official documentation](https://revealjs.com/)

## Adding Videos from Youtube

Youtube videos can be embedded within an iframe with the class of "vid"

Add a single video. 
Add the video ID after `/embed/`

```
<iframe class="vid" src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen/>
```
Add multiple videos to an unamed playlist
After `playlist` add the video ids

```
<iframe class="vid" src="https://www.youtube.com/embed/VIDEO_ID?playlist=vidID_1,vidID_2,vidID_3" allowfullscreen/>
```