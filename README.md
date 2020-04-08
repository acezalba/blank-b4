# blank-b4

A fork of blank-init. Bundles full bootstrap files for development and bootstrap CDN links for production.

## What is it

This repository bundles the following:

- an `index.html` with:
  - browser and seo `meta` tags
  - stylesheet & script sections for:
    - development
    - production
  - `nav`, `header`, `main`, `aside`, and `footer` tags
  - Updated stylesheet and script sections for Bootstrap and its dependencies
- a basic `/asset` folder with:
  - a `/js` folder with a blank `script.js`, and bundled `jquery-3.4.1` and `bootstrap.bundle.js` files
  - an `/img` folder with a placeholder `favicon.ico`
  - a `css/style.css` with simple table of contents & sections for clean organized code
  - `Normalize.css` v8.0.1 for consistent defaults across browsers.

## How to use it

Easiest way is to download the zip to your computer or clone via `git clone https://github.com/acezalba/blank-b4.git new_project_name`, where new_project_name is the name of future project. Then modify and reuse to your heart's content.

**Beginner Tips:**

- place your project resources in the assets folder: `/img` for your images, `/css` for your stylesheets, and `/js` for your scripts. Place your css styles in the `style.css` file and your scripts in the `script.js` file.
- replace the `favicon.ico` in `assets/img/` with your own project favicon. The included icon is a sun emoji because sun. emoji.
- delete or edit the `LICENSE` and the `README.md` file. Now you are ready.

## Licensing and Attributions

- [Normalize.css](http://github.com/necolas/normalize.css), [Bootstrap](https://getbootstrap.com/), [Jquery](https://jquery.com/), and [Popper.js](https://github.com/popperjs/popper-core/blob/master/LICENSE.md) are covered under MIT License, as provided for in their sites.
- The Sun Favicon is a placeholder emoji icon generated through [Favicon.io](http://favicon.io). Website by [John Sorrentino](https://twitter.com/johnsorrentino).
- All other blank-b4 files that are not governed by third-party dependencies and their respective licenses are covered under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
