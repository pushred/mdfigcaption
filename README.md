# mdfigcaption
Markdown-It plugin that allows for the insertion of figure and captioned images

npm install --save mdfigcaption
Usage:

````javascript
    var MdFigCaption = require('mdfigcaption');

    md.use(MdFigCaption);
````

````markdown
    ~[this is a caption](http://imgur.com/12345)
````

````html
    <figure>
        <img src="http://imgur.com/12345" />
        <figcaption>
            this is a caption
        </figcaption>
    </figure>
````
