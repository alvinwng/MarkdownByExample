---
layout: base
title: GoodTool - API examples
---

## API examples

### Access to API factory (Java)

Get the API factory: `GoodTool api = GoodTool.getAPI();`

### Usage of API factory (Java)

Set monitoring of only one CPU thread:

{% highlight java %}
    GoodTool api = GoodTool.getAPI();
    api.setMonitoredThreads(1);
{% endhighlight %}
    
