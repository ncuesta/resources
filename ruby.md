# Ruby resources

* General / Reference
  * [Orats](https://github.com/nickjj/orats): opinionated Rails application templates.
  * [The twelve-factor app](http://12factor.net).
* Performance
  * [Crafting Ruby for Performance](http://www.sitepoint.com/crafting-ruby-performance): a pretty nice post
    on how GC can affect your apps perf and how profiling can help find bottlenecks.
  * [Flame grapsh in miniprofiler](http://samsaffron.com/archive/2013/03/19/flame-graphs-in-ruby-miniprofiler):
    nice (& detailed) flame graphs for miniprofiler.
  * [ruby-prof](https://github.com/ruby-prof/ruby-prof): profiler for MRI rubies.
  * A [gist](https://gist.github.com/dakull/5f3d22eff5fffb43e511) on how to use [jemalloc](https://github.com/jemalloc/jemalloc)
    for better memory management.
* Ruby on Rails development
  * [Rails settings cached](https://github.com/huacnlee/rails-settings-cached): DB-persisted settings with defaults,
    performance-wise caching, and ability to store per-model settings.
  * [AttrSearchable](https://github.com/mrkamel/attr_searchable): Adds a configurable way of specifying full-text
    searches to AR models.
* Deployment / Server configuration & maintenance
  * [Capistrano](http://capistranorb.com): Excellent deployment and remote task automation tool.
  * [capistrano-foreman](https://github.com/surzycki/capistrano-foreman): Capistrano3 extension that integrates your
    deployment tasks with [Foreman](http://ddollar.github.io/foreman).
    * A [tutorial](https://www.digitalocean.com/community/tutorials/how-to-set-up-zero-downtime-rails-deploys-using-puma-and-foreman)
      on setting up zero-downtime deploys with Foreman and Puma (I'm more of a Unicorn guy, but the same principles apply).
  * [Backup](http://meskyanichi.github.io/backup/v4): Perform backups for your app's DB & files.
    Originally seen at [GoRails](https://gorails.com/guides/hourly-production-server-database-and-file-backups).
  * [Errbit](http://errbit.github.io/errbit/): a self-hosted error tracking service for your production Rails apps.
    An OS alternative to [Airbrake](https://airbrake.io).
  * [Deployinator](https://github.com/etsy/deployinator): a pretty nifty project by Etsy that allows you to set up
    an application to manage your deployments from a single place. Read the introductory post [here](http://codeascraft.com/2010/05/20/quantum-of-deployment).
* Ruby/Rack Servers
  * [Unicorn](http://unicorn.bogomips.org).
  * [Puma](http://puma.io).
