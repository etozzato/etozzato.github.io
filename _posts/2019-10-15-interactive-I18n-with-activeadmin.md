---
layout: post
title: multi-tenant, self-service localization interface in Rails and ActiveAdmin using I18n#exception_handler
subtitle: AKA there must be something I can delegate to my users, perhaps finding and fixing missing translations.
tags:
- Rails
- I18n
layout: post
subtitle: AKA there must be something I can delegate to my users.
author: Emanuele Tozzato
comments: true
---

I started thinking that my current Rails application might contain an important number of strings that use the localization helper but are not yet in the language file. 
<br><br>
From the very beginning of the project, a strong effort to localize each bit of the UI was adopted, but the actual translation is lagging and missing translations can be hard to find. 

{% highlight ruby %}
module OmniLogger
  # to be continued...
end
{% endhighlight %}
