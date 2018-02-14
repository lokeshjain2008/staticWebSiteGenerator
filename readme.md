# Yo- Static website generator.

### Getting started
1. we are Following this `yo-generator` [link](https://github.com/yeoman/generator-webapp)

2. we have setup project with `bootstarp-4` and to add support 
for the pug need to include this reciepe. 
[pug receipe | https://github.com/yeoman/generator-webapp/blob/master/docs/recipes/pug.md]

3. for image optimization [smusher](https://github.com/grosser/smusher) a ruby gem. and for resize and other [imagemagic](https://www.npmjs.com/package/imagemagick).

4. There will error about `jQuery` and `popper.js`. include them using `bower`.

### how to theme project.
This project has some basic setup for `bootstrap4`, `pug(for faster html file generations)`.
Theming works on the cheating. I have includes core `bootstrap` sass files. which can be themed easily in the `main.scss`. This way we can theme our project using core `bootstrap` file and have full control like which modules we want to include. 


### getting stated.

1. download this project or `clone` it.

2. `> npm i && bower i(not fully rquired, will get rid of Bower prefer CDN)` 

3. create pug files and enjoy.


### development

1. Run  `npm run gulp serve` this also includes `live reload`.


### Production 

1. Just run `gulp`. This will create production ready dist files. 

2. If want to create `Zip` bundle of the project then run `gulp build` 


## Tasks

1. create support for the navigation sytem.

2. [ ] improve social tags.

3. [] Add support to create `amp` pages.
  
3. [] Add image optimiser.

4. [] Add support for animation.css

5. [] Write `gulp task` to deploy this to `gh-pages`

---

### Resources
1. Better pug files [with data files](https://tusharghate.com/rendering-pug-templates-with-multiple-data-files)
2. [Firebase tools](https://github.com/firebase/firebase-tools)
3. [Surge.sh](http://surge.sh/) and [Netify](https://www.netlify.com/) , [getPubli](https://getpublii.com/)

## SEO related
- Twitter
  - [card](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/overview/summary)
  - [validator](https://cards-dev.twitter.com/validator)
- Facebook
  - [OG](https://developers.facebook.com/docs/sharing/webmasters)
  - [Validator]()
  - <meta property="og:url" content="https://example.com/path" />
  - [Customer chat plugin](https://developers.facebook.com/docs/messenger-platform/discovery/customer-chat-plugin) (Customer Chat application button). 
  - [More excitement](https://messenger.fb.com/blog/2-2-release/)
  - 
