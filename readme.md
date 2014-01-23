# Global CSS

## Reset and Modernizr

### Normalize
- build base off normalize instead of overriding

#### Sources
- [normalize.css](http://necolas.github.io/normalize.css/)
- [normalize wiki](https://github.com/necolas/normalize.css/wiki)

### Modernizr
- Feature-detection (HTML5 and CSS3) 
- Uses special class names to target support and unsupported features, similar to the Paul Irish technique, but more focused to specifice supported features rather than the shotgun approach of entire browser conditionals *( .border-box vs .no-border-box )*
- Sould try to use CSS cascading first. If browser doesn't support a feature it will ignore it and cascade to the next atribute
  
####  Thoughts
- **Progressive Enhancement:** starting with the most widely compatable foundation and building up features from there based on browser support. Think plain-text to modern-web or IE7 to Chrome. 

#### Questions
- IE7 support?
- Modernizr vs Compass?
- Modernizr vs Paul Irish Technique?

#### Sources
- [Modernizr](http://modernizr.com/)
- [A List Apart](http://alistapart.com/article/taking-advantage-of-html5-and-css3-with-modernizr)

### Conditional Classnames
- The *Paul Irish Hack* may not be needed. Instead of targeting entire browser versions use Modernizr to lazer target specific troublesome elements
- **IF** the hack is needed, use the techniques in [this article](http://nicolasgallagher.com/better-conditional-classnames-for-hack-free-css/) to work around the compatablity-view shit-storm

## Typography and Baseline 
- http://practicaltypography.com
- http://webtypography.net
- http://typecast.com/blog/a-more-modern-scale-for-web-typography