---
layout: page
title: "A Graph to Help Me Memorize English Words"
date: 2012-07-07 19:24
comments: true
sharing: true
footer: true
---

{% graphviz %}
digraph G {
  compound=true;

  dentist -> dent;

  profanity -> profane;
  profane -> pro;
  profane -> fane;
  fane -> temple;
  vihara -> temple;

  vacuo -> vacua;
  vacuity -> vacua;
  vacua -> vacuum;
  vacuate -> vacua;

  surf -> sur;
  surbase -> sur;
  surbase -> base;
  surface -> sur;
  surface -> face;

  surgury -> surg;
  surgeon -> surg;
}
{% endgraphviz %}
