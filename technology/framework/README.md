# Framework

## language version: Ruby 3+

`ruby 3+` is the first recommendation for language version for _new_ projects

You should **not** use older versions for _new_ projects and should try to migrate to 3+ whenever possible in _existing_ projects

## application framework: Ruby On Rails 6.1+

`rails 6.1+` is the first recommendation for RfG projects

It is recommended to use API mode if you plan to develop fully detached UI stack

Despite of various downsides Rails has the lowest entry barrier, is the most widely popular and will make future contributions to a RfG project as easy as possible

Rails also includes all basic pieces to start almost any possible project configuration, including ORM, rendering, messaging, storage, background workers, etc.

## testing: RSpec

`rspec` is the first recommendation for RfG projects

https://rspec.info

## background workers: Sidekiq

`sidekiq` is the first recommendation for background jobs and workers in new project

RfG projects may request PRO license

https://sidekiq.org/
