![image](https://github.com/EllenLI2000/EllenLI2000.github.io/assets/112480241/5835ecb8-f406-4e62-b686-5fc3536352d8)---
layout: inner
title: About Me
permalink: /about/
---
## Educational Background
- 2022.8 - 2023.6, MSc. Communication Science, University of Amsterdam
- 2018.8 - 2022.6, BA. Media and Communication, City University of Hong Kong
- 2019.7 - 2019.8, Advanced British Culture and Humanities Programme, University of Oxford,

## Research Experience
- 2023.9 - Present, Research Assistant (Full-time), supervised by [Dr. Yuhan Luo]("https://scholars.cityu.edu.hk/en/persons/yuhan-luo(9349cfbb-22d1-4097-bb5e-e3e20aaa13ba).html")
- 2022.6 - 2023.9, Researcher, Supervised by [Dr. Yuhan Luo]("https://scholars.cityu.edu.hk/en/persons/yuhan-luo(9349cfbb-22d1-4097-bb5e-e3e20aaa13ba).html")
- 2020.10 - 2022.9, Student Research Assistant (Part-time), supervised by [Prof. YU-li Liu]("https://scholars.cityu.edu.hk/en/persons/yuli-liu(cb5a972e-b906-4c9a-8966-2d04034e50f0).html")

## Working Experience
- 2022.3 - 2022.6, Account Executive Intern, [BlueCurrent (Hong Kong)](https://bluecurrentgroup.com.hk/)
- 2021.6 - 2021.9, Digital Advertising Specialist Intern, [BlueFocus (Beijing)](https://www.bluefocusgroup.com/en/)
- 2020.4 - 2020.8, Content Management Intern, [Bytedance (Tianjin)](https://www.bytedance.com/en/)


### Wide image

![Branching](https://guides.github.com/activities/hello-world/branching.png)

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

{% highlight txt %}
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
{% endhighlight %}

{% highlight txt %}
The final element.
{% endhighlight %}

---

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

#### Bash

{% highlight bash %}
>_ ssh -i ~/.ssh/id_rsa account@host.com
account@host:~$
$ var="my-value"
$ echo $var
my-value
$ logout
{% endhighlight %}

#### HTML

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

#### CSS

{% highlight css %}
/*--------------------------------------------------------------
	1.0 Defaults
--------------------------------------------------------------*/

@media (min-width: 1200px) {
  .container {
    width: 1200px;
  }
}

body {
  background-color: #e9edf0;
  @extend %opensans;
  -webkit-font-smoothing: antialiased;
}
{% endhighlight %}

#### YAML

{% highlight yaml %}
### Phantom settings
paginate: 10
footer_text: '© 2018 Jami Gibbs'
admin_name: 'Jami Gibbs'
google_analytics: "UA-9999999-99" # Update with your own tracking ID

#### Phantom Navigation menu
enable_nav: true
nav_item:
  - { url: '/', text: 'Home' }
  - { url: '/about', text: 'About' }
{% endhighlight %}
