---
layout: page
title: Component-Based Rails Applications
subtitle: Large Domains Under Control
use-site-title: true
permalink: /
---

Component-Based Rails is a proven method to manage the complexity of large applications. It ensures that we can maintain development speed, quality, and fun throughout the life cycle of applications. Components do this by enabling conversations about high-level structures that lead to improved communication of intent, more collaboration opportunities, and better maintenance capabilities.

## The Sportsball Sample Application

Below is a component-structure diagram for the [Sportsball sample application](https://github.com/shageman/sportsball). Each bubble is a component. Each arrow shows you a dependency of one component on another. Yes! Component-based applications will end up comprising of many components, each of which has a specific contribution to the overall application's functionality.

![Sportsball Component Structure](/img/sportsball.png)

Views, controllers, models, migrations, tests - they all live within each component and thus separate all aspects of the application's functionality. You can even go as far and not have any functionality within the main Rails application itself.

## Getting Started

To create your first component, create a new engine within your Rails app.

{% highlight bash %}
rails plugin new components/awesome_feature \
  --full \
  --mountable
{% endhighlight %}

Then, mount the engine in `config/routes.rb`.

{% highlight ruby %}
mount AwesomeFeature::Engine, at: "/awesome_feature"
{% endhighlight %}

Now, develop your application within this component (it is a Rails engine) like you would normally!

Obviously this is just the start... For all the snags you are going to run into and the little tricks you need to overcome them, check out [the Component-Based Rails Applications book](book). Consult it also for the *big* questions: Which components to create? How to refactor towards components? When to split off microservices?

Be sure to also check out the [resources page](resources) where you will find conference talk videos, blog posts, and links to tools and code samples.