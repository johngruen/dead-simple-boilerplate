I put this repo together because I wanted the quickest method I could think of to  prototype *Look and Feel* design ideas in code. There's no linting, and the build toolchain is buried in [Harpjs](http://harpjs.com/) so you're not tempted to fuss with or optimize webpack or gulp config for hours before getting into code.

## Get Started

You'll need [node](https://nodejs.org/en/) to do the following:  

```
// only do this if you don't already have harp installed

npm i -g harp

// change 'myproject' to whatever you want your thing to be called

harp init myproject --boilerplate johngruen/dead-simple-boilerplate
cd myproject
harp server
```

## Directory Structure

```
├── README.md
├── harp.json // put data in here, harp will pipe it around
└── public // served content
    ├── _layout.jade // root layout thing
    ├── index.jade // your index
    ├── lib // third party utils for working faster
    │   ├── _normalize.scss
    │   └── jquery.min.js
    ├── scripts // scripts live here
    │   └── main.js
    └── styles // styles live here
        ├── _mixins.scss // mixins i find useful on lots of projects
        ├── _utils.scss // resets
        └── main.scss // your styles here
```

nb. you might want to add a `partials` or `images` directories to `public`. I left them out b/c i didn't want dummy files sitting around just to satisfy git.

