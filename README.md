# Pending Laws Transparency

This project makes the public data about Romanian pending laws searchable.
The original sites have no search engines and are hard to navigate.

See it live at [legi.vij.ro](http://legi.vij.ro).


## Documentation

Guides and the API reference are located in the
[docs](https://github.com/jshacks/boilerplate/tree/master/docs) directory.


## Quick Start

- install bower, npm, grunt, python2, python3, virtualenv, scrapy
- set up a virtualenv
- set up the backend:

        cd backend
        source ~/virtualenv/bin/activate
        ./manage.py migrate
        ./manage.py createindex
        ./manage.py runserver 9337
        
- set up the ui:

        cd Frontend
        npm install
        bower install
        grunt serve

- start crawling:
        
        scrapy crawl finante
        scrapy crawl afaceri_externe


## Short History

This project participated (and won a jury's prize) at the JSHacks 2016 hackathon.

This initiative was [Alex Morega](https://github.com/mgax)'s suggestion for a hackathon project.

## License

MIT © 2016
