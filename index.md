---
layout: home
---
<div class="boxes">

<div class="box box2" markdown="1">

dip pens and pencils

gliding over the Moleskine

to reveal not much

</div>

<div class="box altbox" style="background: url('/doodles/assets/doodles/mad-murdoch.png') no-repeat center/cover;" markdown="1">
[some more doodles on Tumblr](https://opyate.tumblr.com/)
</div>


{% for item in site.posts %}

<div markdown="1">
[![]({{item.thumbnail}})]({{site.baseurl}}{{item.url}})
</div>

{% endfor %}

</div>
