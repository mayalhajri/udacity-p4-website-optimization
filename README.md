# Project 4: Website Performance Optimization


## Part 1: index.html

[Live Demo](http://hipslikeyeah.github.io/udacity-p4-website-optimization/)

#### Results

- Mobile : 92/100
- Desktop: 94/100

#### Changes Made

- Move scripts to the bottom
- Change external script loading to async
- Optimize images and remove external image hosting
- Switch font loading to javascript
- Minify js and css
- Remove unnecessary styles (unused or redundant)
- Inline CSS

## Part 2: pizza.html

[Live Demo](http://hipslikeyeah.github.io/udacity-p4-website-optimization/views/pizza.html)

#### Results

- Target timeline on similar to [provided](http://i.imgur.com/cI6zwUo.jpg)
- Time to resize pizzas under 5s

#### Changes Made

- In updatePositions(): calculate expensive math operations once, outside for loop
- In changePizzaSizes(): only calculate newwidth once, with one "example pizza"

## Resources Used

- [http://cssminifier.com/](http://cssminifier.com/)
- [https://imageoptim.com/](https://imageoptim.com/)
- [http://jscompress.com/](http://jscompress.com/)