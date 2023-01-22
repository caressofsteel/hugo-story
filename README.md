# Hugo Story
## A (modular, highly tweakable) responsive one-page theme for Hugo.

![](images/device-screenshots.png)

Hugo Story is a port of the static HTML template Story by HTML5 UP. It is designed to mirror the look and feel of the original template as closely as possible while incorporating some of the features Hugo has to offer.

This theme is designed for those who are comfortable editing HTML and integrating Hugo short codes and variables to customize the theme to their liking.

## Features

- Minimalist Design
- Fully Responsive
- Templates
  - Header
  - Footer
  - FootScripts
  - Favicon
- Partials for each element type
  - Banner
  - Spotlight
  - Gallery
  - Items
- Image gallery
- Short Codes
  - Site Title
  - Site Subtitle
  - Site Logo
  - Social Icons
- Favicon and Social icons
- FontAwesome Icon Support
- SASS and AutoMinify Support
- Google Analytics Support

## Demo
https://caressofsteel.github.io/demos/hugo/hugo-story/

## Using
### 1. Install Hugo.

[Install Hugo (Extended Version)](https://gohugo.io/overview/installing/)
    
> _This theme uses Hugo Pipes to compile SCSS & Sass so you'll have to use the **extended** version of Hugo. See the official [Hugo Quick Start Guide](https://gohugo.io/getting-started/quick-start/) for more information._
### 2. Create a new example site called `mystory`.

``` 
hugo new site mystory
```
### 3. Clone the Git repository.

```
cd mystory
git clone https://github.com/caressofsteel/hugo-story.git themes/hugo-story
```

> _Hint: See a note for non-Git users [here](https://gohugo.io/getting-started/quick-start/#step-3-add-a-theme)._
### 4. Copy contents of `themes/hugo-story/exampleSite/` to `mystory` root folder with overwrite.
```
cp -r themes/hugo-story/exampleSite/* ./
```
> _Hint: This sets up the `mystory` example website with a copy of the theme `assets`, `layouts`, `data`, and `configuration` files in the site's root folder and outside of the theme folder._

> _Hint: Theme assets in the site root, `if present`, take precedence over files in the theme folder._
> 
### 5. Start Hugo Server.
```
hugo server
```
### 6. Open Hugo Server in your browser.
```
http://localhost:1313/
```
Here you'll see the site running on the local Hugo server. You can now edit the theme and Hugo will rebuild the site when changes are detected.

### 7. Further steps.

- Edit the contents of `YML` files in the `data` folder. 
  - _Altering `banner.yml` will change the top block on the site. See more details [here](https://gohugo.io/templates/data-templates/)._

- Create a custom site layout.
  - Edit the `index.html` within `mystory/layouts/` to customize the layout the site.

  - By manipulating the the `{{ partial ... }}` tags within this file you can create a custom layout for the site. See more details [here](https://gohugo.io/templates/partials/).

- Continue exploring Hugo and the template!
## Credits

This theme was created using the _Story_ template by [HTML5 UP](https://html5up.net/uploads/demos/story/).

## License

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/" class="license-button"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png"></a>

This Hugo theme is licensed under the [Creative Commons Attribution 3.0 License](LICENSE).
