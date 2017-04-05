Just enough bang out quick prototypes without having to start from scratch.


Uses [Harp](http://harpjs.com/)

## Get Started  
```
npm i -g harp  
harp init myproject --boilerplate johngruen/dead-simple-boilerplate
harp server
```

## Directory Structure

```
├── README.md
├── harp.json // data passed in to jade files
└── public
    ├── _layout.jade // wrapper for all pages
    ├── index.jade // root page
    ├── lib // copy pasted 3rd party utils
    │   ├── _normalize.scss
    │   └── jquery.min.js
    ├── main.js // write js here
    └── main.scss // write scss here
```

