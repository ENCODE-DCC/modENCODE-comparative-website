# Website

Comparative modENCODE/ENCODE project website built with [Jekyll](jekyllrb.com), [SASS](http://www.sass-lang.com), [Bourbon](http://bourbon.io), [Neat](http://neat.bourbon.io), and [Bitters](http://bitters.bourbon.io).

## Development

### Set Up Environment

```ShellSession
$ gem install jekyll
```

### Serve Site for Local Development

To serve the site locally for development use the Jekyll ```serve``` command.

```ShellSession
$ jekyll serve --baseurl "" --watch
```

### View Site

```ShellSession
$ open http://0.0.0.0:4000/
```

The site works with Jekyll 2.0.0 or later.

### Optional Setup Instructions

To update the dependencies on Bourbon, Neat or Bitters additional gems are required.

```ShellSession
$ gem install bourbon
$ gem install neat
$ gem install bitters
```

Depending on your system your might have to run those as superuser using ```sudo```.

## Updating Content

### Main Papers

Paper meta information and content of the data pages is stored in ```chromatin.md```, ```regulation.md``` and ``` transcription.md```. The header of the files contains the meta information in YAML format and the body of the pages is the content of the data page in Markdown format.

### Companion Papers

Companion paper information is stored in Jekyll [data files](http://jekyllrb.com/docs/datafiles/) in the ```_data/publications``` directory with one file per journal. Companion paper meta information is provided using the following fields:

``` yaml
  - authors: Sisu et al.
    title: "Comparative analysis of pseudogenes across three phyla"
    meta: "Proceedings of the National Academy of Sciences USA, in press, 2014"
    url: 
    data_url: http://psicube.pseudogene.org
    software_url: 
```

The ```url```, ```data_url```, and ```software_url``` fields are optional. All other fields are required.

The content of the ```url``` field is used to link to the paper on the website of the publisher or in a repository such as PubMed Central. The content of the ```data_url``` and ```software_url``` fields is used to create addtional links to data and software related to the publication, respectively.


## Deployment

### GitHub Pages

Simply push the latest changes to the [gh-pages](https://github.com/parklab/comparative-website/tree/gh-pages) branch of this repository. 

### Web Server 

Static HTML and CSS for deployment are generated by the Jekyll ```build``` command.  To build the site for production deployment outside GitHub pages, the default ```baseurl``` in ```_config.yml``` needs to be overwritten using the ```baseurl``` defined in ```_config_production.yml```. __Please do not edit the ```baseurl``` in ```_config.yml```__.

```
jekyll build --config _config.yml,_config_production.yml
```

Then transfer the contents of the  ```_site``` directory to your webserver indicated by the ```baseurl``` in ```_config_production.yml```. A range of alternative deployment strategies is discussed in the [Jekyll documentation](http://jekyllrb.com/docs/deployment-methods/).
