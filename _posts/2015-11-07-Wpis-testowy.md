---
layout: post
title: Pierwszy wpis
permalink: /posts/
image: http://www.svims.ca/council/illust/Psilocybe%20pelliculosa%201%20Kit%20Scates%20Barnhart.jpg
table: ['one','two','three']
---
![Photo]({{page.image}})

{% for item in page.table%}
  {{item}}
{% endfor%}
