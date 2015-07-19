---
layout: post
title: Nominal | A Jekyll Theme
breadcrumb: Nominal
---
## Nominal is a simple, minimal Jekyll theme, perfect for your blog and portfolio. It's built on <a href="http://github.com/estrattonbailey/svbstrate" target="_blank">Svbstrate</a> so it's fast and scalable. Easily hack around to make it your own!

Nominal is set in Open Sans and Georgia, so it's easy on the eyes and the load times. Simple typographic hierarchies look good at any screen size. Nominal also handles images well. Simply add them to your assets folder and insert theme directly into the Markdown of your posts, if you want them inline, or use the two handy *includes* to insert a full width photo or two photos next to each other.

```liquid
{%raw%}{% include blog/images/single.html img="path/to/you/image" img_alt="Alt text for your image" %}{%endraw%}
```

or

```liquid
{%raw%}{% include blog/images/double.html img_1="path/to/you/image" img_1_alt="Alt text for your image" img_2="path/to/you/second/image" img_2_alt="Alt text for your image" %}{%endraw%}
```

Which will output:

{% include blog/images/single.html img="/assets/images/startupstockphoto.jpg"  img_alt="Big, beautiful photos in a Jekyll theme." %}

{% include blog/images/double.html img_1="/assets/images/startupstockphoto2.jpg" img_1_alt="The versatility of Jekyll is really pretty awesome." img_2="/assets/images/startupstockphoto3.jpg" img_2_alt="Photos really can look good in a Jekyll theme." %}