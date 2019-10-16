# Template README for Web Developer take-home

*Fill this template out before submitting your take-home to your recruiting
coordinator.*

## Installation

To setup this project and install it's tools/dependencies, if any, run the
following command(s):

### how I set up this project
To save on time, I used a webapp generator [Gulp](https://gulpjs.com/) set up from a [Yeoman](https://yeoman.io/) I learned while at North Face. Ripped some of the Bootstrap components out tried to create a quick scass templating system to organize the layout. I focused primarly on trying to match the design comps, and wanted to showcase my design skills and thoughts around structure. 

See below for the *Getting started* from the official documention on [Yeoman Github](https://github.com/yeoman/generator-webapp)

```

    Install: npm install --global yo gulp-cli generator-webapp
    Run yo webapp to scaffold your webapp
    Run npm start to preview and watch for changes
    Run npm start -- --port=8080 to preview and watch for changes in port 8080
    Run npm install --save <package> to install dependencies, frontend included
    Run npm run serve:test to run the tests in the browser
    Run npm run serve:test -- --port=8085 to run the tests in the browser in port 8085
    Run npm run build to build your webapp for production
    Run npm run serve:dist to preview the production build
    Run npm run serve:dist -- --port=5000 to preview the production build in port 5000

```

## Running locally

To run this project locally as a static-webpage, run the following command(s):

```
npm start
```

## Future improvements

### Javascript improvements

**Event handling**
As it is currently, there is not any custom Javascript components built out to handle things like signup, or modal overlays. I think for this I would want to dig into some component JS functionality that be reused elsewhere on the site. 

**custom animation/illustration**
Also, the illustrations are really interesting. In the hero element or the big cube section in the beginning, I would ask what purpose that area can serve, perhaps it can tie to some interactive data points to showcase some of the product features. 

**custom AI search input**
On the 'Increase Conversions and Lower Bounce' section, it wasn't really clear from the mockup what that input box can do, return, and how to use it. Ideally, this would be another good place for JS to work with calls to the technology that drives the enrichment tools of the product. And really hone in on how customers could potentially *test drive* a search? 

### Animation & css
Given I was only provided one comp, I ran out of time to do the mobile mockup, but if I were to re-do this, I would start mobile-first. Then work my way out to a larger design. Also, there can be room for some simple but not overly exagerrated and functional animation. Like having the navigation slide down on scroll down, or slide down on scroll up. Google has a good guide in their web fundamentals on performance for animation too. via the [RAIL method](https://developers.google.com/web/fundamentals/performance/rail);

**illustrations**
A lot of the illustrations can me made in CSS3 as well most likely. So instead of loading an image, we could potentially build areas where an illustration is needed without requesting an image from the server

### Test and build out comp more
Continuing to cross browser test and build out the design and features as necessary to get it production ready. Want to make sure also that there are no usability bugs. 

### Accessible & SEO
In 2019, it's very important to make sure that the web is accessible to all. I would want to research accessability more, and make sure that form elements, or screen readers can digest the content. Simarly, that certain elements adhere to [schema.org](schema.org) make up to be found by the search engine. 

