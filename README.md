# Frontanería web

## Getting Started

Clone this repository on your local machine

```
git clone git@github.com:Frontaneria/as/frontaneria.github.io.git
cd frontaneria.github.io
```

### Prerequisites

To install dependencies following command:

```
gem install bundler
bundle install
```

To run the project run the following commands:

```
jekyll build
jekyll serve
```

## File Structure

The `_site` folder contains the generated HTML files. **Do not make any changes here**. They will get overwritten every time Jekyll builds the site. All the folders beginning with an underscore do not get output into the `_site` folder by Jekyll.

* **_config** Settings for Jekyll.
    * **_data** Contains a kind of static data base.
    * **_includes** Contains the apologize, footer, head, header, motto, post-list, reading_time, recommendations and sidebar.
    * **_layouts** Jekyll files for templating.
    * **_posts** Contains all the compiled posts and technical articles.
    * **_sass** Contains all the uncomipled file patterns.
    * **about** Contains Frontaneros/as about page.
    * **css** for css files.
        * **_sass** There's a sass file for every pattern. When adding new sass patterns, you'll need to import these into the `main.css` file.
        * **main.scss** imports all the sass files into one file. This is output in assets/css/main.css
    * **developers-interviews** Contains the Developers Interviews I have done to some of the most amazing web developers arround the globe! (WIP).
    * **FAQ** Contains questions that may help you before sending me an email.
    * **img** Contains all images and icons. This is output in assets/img/
    * **js** Contains all images and icons. This is output in assets/js/
    * **index.html** The Website index.
    * **LICENSE** Contains the project license.
* **README.md** Documentation (this)

## Sass Architecture

* [Hugo Giraudel's Sass 7-1 Architecture Guide](https://sass-guidelin.es/#architecture)
