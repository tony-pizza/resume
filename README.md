# How I do my resume

use [middleman](https://middlemanapp.com/), CSS and a [slim template](http://slim-lang.com/) to render a static webpage and then save it to a pdf from chrome

[see an example!](example.pdf)

### install

copy `data/resume.yml.example` to `data/resume.yml`

```
gem install bundler
bundle install
```

### run

```
middleman server
```

open [http://localhost:4567](http://localhost:4567) in your browser

### edit

update resume data in `data/resume.yml` and refresh the page in your browser

or update the template and styles in `source`

### save

File > Print > Save as PDF

### build for hosting

```
middleman build
```
