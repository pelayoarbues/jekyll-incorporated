# Jekyll Incorporated by Inc
Modern Jekyll based blog. Great for companies, products or anything. See live at [blog.sendtoinc.com](http://blog.sendtoinc.com)

## Installation & Usage
    bundle install
    jekyll serve --watch
    
## Configuration
Edit: _config.yml (general options), main.css (theme colors &amp; fonts)

```
jekyll-incorporated/
├── _config.yml
├── _assets/
    ├── stylesheets/
        ├── main.scss
```

_Note:_ when editing config.yml, you need to restart jekyll to see the changes.

    
## Publish to Github Pages
1. Add your domain to _CNAME_
2. Edit your repo address at _Rakefile_
    
Run rake task. **NOTE: It will deploy the generated site to _gh-pages_ branch overwriting it**    
``` 
rake site:publish
```

## Authors

Originally build for [sendtoinc.com](https://sendtoinc.com), your workspace for sharing and organizing knowledge

**Karri Saarinen**

+ [http://twitter.com/karrisaarinen](http://twitter.com/karrisaarinen)
+ [http://github.com/ksaa](http://github.com/ksaa)

**Jori Lallo**

+ [http://twitter.com/jorilallo](http://twitter.com/jorilallo)
+ [http://github.com/jorde](http://github.com/jorilallo)

## Copyright and license

Copyright 2013 Kippt Inc. under [The MIT License ](LICENSE)

