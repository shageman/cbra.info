# cbra.info
## Component-Base Rails Applications Resources

This page is intended as a comprehensive list of the resources created on the topic of _cbra_. Component-based Rails (with the 'a' standing for architecture or application) is a code organization and management technique that breaks large applications into small, distinct parts. These parts are separate from and maintain explicit dependencies between each other. Components are implemented as gems and engines.</p>

### Books

![CBRA Book Cover](https://octodex.github.com/images/yaktocat.png)

[Component-based Rails Applications](https://leanpub.com/cbra) by [Stephan Hagemann](@shageman). The source code to the book is at https://github.com/shageman/cbra_book_code.

### Sample apps

* https://github.com/shageman/the_next_big_thing
* https://github.com/shageman/rails_container_and_engines (deprecated)
* https://github.com/taskrabbit/rails_engines_example

### Tools

* https://github.com/dugancathal/transdeps Gem to find inconsistent dependency versions in cbra apps.
* https://github.com/shageman/cobratest Gem to run tests in cbra app based on git changes in components
* https://github.com/shageman/cobradeps Gem to print dependency graph of cbra app

### Scripts

* https://gist.github.com/fernandes/f1dd4401ebdfc4754116 Script to bump the version of a dependency across all components

### Blog Posts

* http://teotti.com/reduce-memory-footprint-requiring-portions-of-your-component-based-rails-applications/
* http://teotti.com/gemfiles-hierarchy-in-ruby-on-rails-component-based-architecture/
* http://teotti.com/feature-flagging-portions-of-your-ruby-on-rails-application-with-engines/
* http://teotti.com/using-plugins-as-components-of-a-large-ruby-on-rails2-application/
* http://tech.taskrabbit.com/blog/2014/02/11/rails-4-engines/
* http://pivotallabs.com/strict-separation-component-based-rails/
* http://pivotallabs.com/admin-engines-for-cobra/
* http://pivotallabs.com/rubymine_6-component-based-architectures/
* http://pivotallabs.com/rails-autoloading-for-your-gem/
* http://pivotallabs.com/migrating-from-a-single-rails-app-to-a-suite-of-rails-engines/
* http://pivotallabs.com/rails-a-container-for-web-application-development-and-deployment/
* http://pivotallabs.com/unbuilt-rails-dependencies-how-to-design-for-loosely-coupled-highly-cohesive-components-within-a-rails-application/
* https://teamgaslight.com/blog/maintainable-and-scalable-systems-with-rails-engines
* http://pivotallabs.com/writing-rails-engine-rspec-controller-tests/
* http://pivotallabs.com/faking-authentication-for-capybara-tests-within-a-rails-engine/
* http://pivotallabs.com/moving-db-tables-between-rails-engines/
* http://pivotallabs.com/leave-your-migrations-in-your-rails-engines/

### Talks

* http://www.confreaks.com/videos/3344-railsconf-refactoring-towards-component-based-rails-architectures
* http://www.confreaks.com/videos/2646-rockymountainruby2013-how-i-architected-my-big-rails-app-for-success
* http://www.confreaks.com/videos/2350-mwrc2013-component-based-architectures-in-ruby-and-rails
* http://www.confreaks.com/videos/1263-rockymtnruby2012-wrangling-large-rails-codebases