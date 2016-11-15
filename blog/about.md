---
layout: page
title: About SZ Flex
permalink: /blog/about/
---

Jekyll 3.3 Theme for Blog · [**Live preview on gh-pages**](https://startzerognu.github.io/jekyll-szflex-theme/)

## Features

* 2 Columns
* Sass Boilerplate 1-7
* Normalize v.5.0.0
* Flexbox Layout (mobile first)
  * Chrome v.4 +, Chrome for android (all)
  * Firefox v.2 +, Firefox for android (all)
  * Opera v.12.1 +, Opera mobile v.12.1 +, Opera Mini (all)
  * Safari v.3.1 +
  * IE v.10 +, IE mobile v.10 +
  * Edge v.12 +
  * iOS safari v.3.2 +
  * Android browser v.2.1 +
  * Blackberry browser v.7 +
  * UC browser for android v.11 +
  * Samsung internet v.4 +
  * [**More info**][caniuse]
* Toggle aside without JS
* Icon font (font awesome)
* Full text search
* Pagination
* Sitemap

## Usage

* **GH-Pages**

  Fork repo, remove master branch and customize `config.yml` with your site settings.

  If you want to use the theme in a project page, add the name of the repository to
  `$base-url: '/assets/';` in `/assets/css/style.scss` like this:

  ```scss
  $base-url: '/jekyll-szflex-theme/assets/';
  ```

* **[Dr. Jekyll Themes][drjekyllthemes]**

  Install drjekyll

  ```
  ~ $ gem install drjekyll
  ```
  Download theme

  ```
  ~ $ drjekyll new szflex
  ```

  This will download the Theme from [Dr. Jekyll Themes][drjekyllthemes]

* **[Mr. Hyde's][hyde]**:

  Install mrhyde-tools

  ```
  ~ $ gem install mrhyde-tools
  ```

  Download Theme

  ```
  ~ $ mrhyde new sz-flex
  ```

  This will run [sz-flex.rb][script] from [Mr. Hyde's Scripts][hydescripts] and
  it will download the Theme from [Dr. Jekyll Themes][drjekyllthemes]

## Contributing

[Bug reports][issues] and pull requests are welcome.

## License

[Script][script] Public domain license · Theme [MIT][mit] license.

## Credits & Thanks

* [Mr. Hyde's][hyde] by [Gerald Bauer][geraldb]
* [Mr. Hyde's Scripts][hydescripts] by [Gerald Bauer][geraldb]
* [Dr. Jekyll Themes][drjekyllthemes] by [Gerald Bauer][geraldb]
* [Sass boilerplate][sass-boilerplate] by [Hugo Giraudel][hugogiraudel]
* [Normalize][normalize] by [Nicolas Gallagher][necolas]
* [Courgette][courgette] by [Karolina Lach][karolinalach]
* [Background Image][image] by [JDDesign][jddesign]
* [Font Awesome][font-awesome] by [Dave Gandy][dave-gandy]
* [Simple Jekyll Search][search] by [Christian Fei][christian-fei]
* [Jekyll Feed][feed] by [Ben Balter][ben-balter]
* [Jekyll Paginate][paginate] by [Parker Moore][parker-moore]
* [Jekyll Sitemap][sitemap] by [Ben Balter][ben-balter]

[caniuse]: http://caniuse.com/#feat=flexbox
[hyde]: https://github.com/mrhydescripts
[hydescripts]: https://github.com/mrhydescripts/scripts
[script]: https://github.com/mrhydescripts/scripts/blob/master/sz-flex.rb
[drjekyllthemes]: https://github.com/drjekyllthemes
[geraldb]: https://github.com/geraldb
[sass-boilerplate]: https://github.com/HugoGiraudel/sass-boilerplate
[hugogiraudel]: https://github.com/HugoGiraudel
[normalize]: https://github.com/necolas/normalize.css
[necolas]: https://github.com/necolas
[courgette]: https://fonts.google.com/specimen/Courgette
[karolinalach]: https://plus.google.com/+KarolinaLach
[image]: https://pixabay.com/en/background-polygon-purple-violet-1409025/
[jddesign]: https://pixabay.com/en/users/JDDesign-2595351/
[issues]: https://github.com/StartZeroGnu/jekyll-szflex-theme/issues
[mit]: https://opensource.org/licenses/MIT
[search]: https://github.com/christian-fei/Simple-Jekyll-Search
[christian-fei]: https://github.com/christian-fei
[font-awesome]: http://fontawesome.io/
[dave-gandy]: https://github.com/davegandy
[feed]: https://github.com/jekyll/jekyll-feed
[paginate]: https://github.com/jekyll/jekyll-paginate
[sitemap]: https://github.com/jekyll/jekyll-sitemap
[ben-balter]: https://github.com/benbalter
[parker-moore]: https://github.com/parkr
