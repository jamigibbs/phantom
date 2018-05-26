---
layout: inner
title: About
permalink: /about/
---

## Hello World!

Aenean praesentium dolore aenean qui nesciunt dictumst molestiae, odit irure. Nesciunt fusce, atque pharetra odio quis quaerat accusantium? Integer aspernatur eligendi facilisis, do sodales. Consequat.

Arcu porro faucibus ante! Unde litora voluptate veniam fugit alias. Sociosqu! Augue, cupidatat excepturi laoreet magnis veniam repudiandae impedit venenatis alias iure ad ab! Enim.

Nibh quia necessitatibus omnis! Nemo nascetur penatibus iste morbi. Nisi, consequat! Rutrum. Quasi elementum, dignissim cillum, cubilia sapien vitae officia porta hendrerit. Mi aut recusandae.

Voluptatem sint. Sapiente porttitor vivamus sequi occaecat litora? Conubia molestias nostrud dicta quisque penatibus minim imperdiet? Aspernatur nostra doloribus nibh curae ac? Nobis quas? Sollicitudin.

## Syntax highlighting

Jekyll has [built in support](https://jekyllrb.com/docs/templates/#code-snippet-highlighting) for syntax highlighting of over 60 languages thanks to [Rouge](http://rouge.jneen.net/).

To render a code block with syntax highlighting, surround your code as follows:

{% highlight markdown %}
{% raw %}
{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}
{% endraw %}
{% endhighlight %}

[Pygments](http://pygments.org/) styles are present under section 6.0 of `css/style.scss` for customization.

### Examples

---

#### bash

{% highlight bash %}
$ ssh -i ~/.ssh/id_rsa account@host.com
$ var="my-value"
$ echo $var
my-value
$ logout
{% endhighlight %}

#### html

{% highlight html %}
<!DOCTYPE html>
<html>
 <head>
   <meta charset="UTF-8">
   <title>title</title>
 </head>
 <body>

 </body>
</html>
{% endhighlight %}

#### yaml

{% highlight yaml %}
# Site settings
# These are used to personalize your new site. If you look in the HTML files,
# you will see them accessed via {{ site.title }}, {{ site.email }}, and so on.
# You can create any custom variable you would like, and they will be accessible
# in the templates via {{ site.myvariable }}.
title: Your awesome title
email: your-email@example.com
description: Write an awesome description for your new site here.
baseurl: "" # the subpath of your site, e.g. /blog
url: "" # the base hostname & protocol for your site, e.g. http://example.com
twitter_username: jekyllrb
github_username:  jekyll
{% endhighlight %}
