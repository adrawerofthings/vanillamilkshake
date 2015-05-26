# Vanilla Milkshake

**A minimalist Wordpess theme built with elegant typography and responsive design for simple weblogs. Allows for easy customization and extension.**

![Screenshot of Vanilla Milkshake theme on desktop and mobile](screenshot.png)

## Who this theme is for

- Bloggers who just want a simple yet classic, two-column blog design that works just as well on mobile and tablet then it does on desktop.
- Wordpress theme developers who want a simple base theme with the bare minimum of template files and CSS styles.
- Frontend developers who want to see the [Tachyons](https://github.com/mrmrs/tachyons/) CSS framework in action.

## Theme features

- Responsive design
- Customizable colors
- Best-of-class typography defaults
- Treats text and images equally (the latter doesn't dominate)
- Media-rich excerpts
- Short loading times
- No external font or Javascript dependencies (works behind the Great Firewall)
- Accessibility enhanced
- Translation ready
- Easy to extend and build upon

## See the theme in action

- [88 Bar](http://88-bar.com/): a group blog about Chinese tech, media and design.
- [MBA Mondays Illustrated](http://www.mba-mondays-illustrated.com): business 101 for startups by Fred Wilson.

## Notes for theme developers

- *style.scss* actually doesn't use any SASS syntax; it's named such so that Codekit will minify them into *style.css*.
- Vanilla Milkshake currently uses the default, Wordpress-generated search and comment forms. (In case you were wondering where those were.)
- There is a custom, media-rich excerpt function (see inc/rich-excerpt.php), which has been tested with my blog and the theme test blog but may still have a bug or two.
- To build this theme, I used the [Twenty Fifteen](https://github.com/WordPress/WordPress/tree/master/wp-content/themes/twentyfifteen) theme as my starting point, and then stripped out as many custom functions and templates as I deemed reasonable. If something doesn't make sense, it's because it may be a vestige from [Twenty Fifteen](https://github.com/WordPress/WordPress/tree/master/wp-content/themes/twentyfifteen).
- The [Tachyons](https://github.com/mrmrs/tachyons/) CSS framework I use reads a lot like inline HTML and should make sense when you see the HTML templates. The basic philosophy behind it is that cascading styles often try to do too much and cause cascading errors. As such, specifying inline styles in the templates ends up creating cleaner code and better performance. (Also, I used [my own fork of Tachyons](https://github.com/hongkonggong/tachyons).

## Credits ##

- [Twenty Fifteen](https://wordpress.org/themes/twentyfifteen/) theme, which I used as a starting point
- [Tachyons](http://www.tachyons.io) lightning-fast CSS framework
- [Butterick's Practical Typography](practicaltypography.com/), whose advice I followed for system fonts
- [Type scale](http://type-scale.com/), a handy type-sizing tool 
- [unlimited edition](http://web.archive.org/web/20090423123137/http://www.hexaplex.nl/09/unlimited-edition), my former go-to theme for a default, minimalist aesthetic

## License ##

Vanilla Milkshake is released under the terms of the [GNU General Public License version 3](http://www.gnu.org/licenses/gpl.html).
