## Hello!
This soon (may not be this soon, I'm on vacation at the moment :D ) will become my photography portfolio.

Special thanks to [Ram](https://github.com/rampatra) for the website and inspiration to finally share my photography with the world.

P.S.: I will leave Highlights and Quick Start sections, so you can see how easy it is to set up and share your work.

### Highlights
1. Easy setup and you get a website of your own for free. No web hosting charges too.
2. To add new pictures, you need to just upload them. No code changes required.
3. And, my favorite, you get to see EXIF data like aperture, shutter speed, iso etc. when you click on any image, automagically. Moreover, you can customize this as per your needs.

### Quick Start
If you know a tad about tech and love taking pictures then this open-source project may help you setup a website to showcase
all your creations without effort. And not just that, with this you need not pay a single dime to host your website as
it's hosted by GitHub for __free__.

#### Run the website locally to test
1. `$ cd photography` - go to the project directory
2. `$ bundle install` - install gems
3. Change the `baseurl` in `_config.yml`
4. `$ bundle exec jekyll serve` - start/run the website

#### Build the website
1. `$ cd photography` - go to the project directory
2. `$ npm install` - install all npm dependencies
3. `$ gulp` - minify css, js, resize images, etc.

Note: You only need to build the website if you make changes such as replacing the images, modifying the css styles, etc.
