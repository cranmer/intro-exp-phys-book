# Notes about this book

I started with the demo jupyter-book and started to delete pages I didn't want.

I creaetd a new project repository and set GitHub pages to look for the source in the `master` branch. 
This means that the url is `cranmer.github.io/intro-exp-phys-book`. 
That didn't work at first, that URL was redirected to the `introduction.html` landing page automatically.
Later I realized I needed to modify the `_config.yml` file to be:
```
baseurl: "/intro-exp-phys-book" # the subpath of your site, e.g. /blog. If there is no subpath for your site, use an empty string ""
url: "https://cranmer.github.io" # the base hostname & protocol for your site, e.g. http://example.com
```

Now it's working. 