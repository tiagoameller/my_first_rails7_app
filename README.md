# My first Rails 7 app

`rails new sortable -j eslint -css bulma`

run servers as `./bin/dev`

Used this exercise to take a look to [Bulma CSS framework](https://bulma.io/)

js and css compiling is made watching file changes, but **eslint** has no live reloading. I've found tricks such [this](https://www.colby.so/posts/live-reloading-with-esbuild-and-rails), but not tried yet.

Another problem is Stimulus controllers must be declared one by one.

Configuration taken from [this GoRails tutorial](https://gorails.com/episodes/esbuild-jsbundling-rails).
Sortable sample taken from [Drifting Ruby episode #312](https://www.driftingruby.com/episodes/importmaps-in-rails-7)
