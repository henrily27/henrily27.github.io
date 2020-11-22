---
layout: splash
title: "Collapsible Tree of Aristocratic Families in Leo Tolstoy's *War and Peace*"
date: 2020-11-15
tags: [collapsible tree, d3.js]
header:
  overlay_color: "gray"
excerpt: >
  *We can know only that we know nothing. And that is the highest degree of human wisdom.*<br />
  <small>--Leo Tolstoy, War and Peace</small>

feature_row_left:
  - image_path: /images/war_n_peace/Tolstoy.jpg
    title: "Leo Tolstoy"
    excerpt: "***War and Peace*** is regarded as one of Tolstoy's finest literary achievements. The novel chronicles the French invasion of Russia and the impact of the Napoleonic era on Tsarist society through the stories of five Russian aristocratic families."
    url: https://www.wikiwand.com/en/War_and_Peace
    btn_class: "btn--primary"
    btn_label: "Learn more"


mathjax: "true"
---

{% include feature_row id="feature_row_left" type="left" %}

For a recent work project, I created a 20-page questionnaire document to train the internal team.  There were 3 different scenarios in the document, and for the majority of the time, only one of the 3 scenarios will apply to each business case.  It was not efficient to scroll through the pages to figure out which section one would need for which business case.  Hence, come the *Collapsible Tree* - an interactive decision tree that guide the user through each node and the corresponding choices follow that node. It's called "collapsible" because the rest of the branch can be collapsed into the parent node by clicking on the parent node. The collapsible tree can quickly point the user to the right branch and only need to worry about navigating that branch.  The collapsible tree can be created using the Javascript library d3.js.

The example in this post illustrates the same collapsible tree concept using d3.js.  In this case, I created a collapsible tree depicting the five Russian aristocratic families from Leo Tolstoy's *War and Peace*. The actors' pictures are from [BBC ](https://www.bbc.co.uk/programmes/profiles/pcqw2nXWtYmwZ4SL1YTDRB/characters).

- [The Five Families](#the-five-families)
  - [Bolkonsky Family](#bolkonsky-family)
  - [Rostov Family](#rostov-family)
  - [Bezukhov Family](#bezukhov-family)
  - [Kuragin Family](#kuragin-family)
  - [Drubetskoy Family](#drubetskoy-family)
- [The Collapsible Tree](#the-collapsible-tree)
  

# The Five Families
<div style="width:70%; font-size:80%; text-align:center">
<img src="/images/war_n_peace/WnP_five_families.PNG" style="padding-bottom:0.5em;"/>
</div>  

## Bolkonsky Family
<div style="width:80%; font-size:80%; text-align:center">
<img src="/images/war_n_peace/Bolkonsky.PNG" style="padding-bottom:0.5em;"/>
</div>  

## Rostov Family
<div style="width:75%; font-size:80%; text-align:center">
<img src="/images/war_n_peace/Rostov.PNG" style="padding-bottom:0.5em;"/>
</div>  

## Bezukhov Family
<div style="width:60%; font-size:80%; text-align:center">
<img src="/images/war_n_peace/Bezukhov.PNG" style="padding-bottom:0.5em;"/>
</div>  

## Kuragin Family
<div style="width:60%; font-size:80%; text-align:center">
<img src="/images/war_n_peace/Kuragin.PNG" style="padding-bottom:0.5em;"/>
</div>  

## Drubetskoy Family
<div style="width:60%; font-size:80%; text-align:center">
<img src="/images/war_n_peace/Drubetskoy.PNG" style="padding-bottom:0.5em;"/>
</div> 

# The Collapsible Tree
There are two main components to the tree:
- "name": this value indicates the parent node
- "children": these are the child nodes associate with "name"

In the tree example below, the parent node "Prince Bolkonsky" has multiple child nodes:
- "son: Prince Andrei Bolkonsky"
- "daughter: Princess Marya Bolkonskya"
- "orphan: Mademoiselle Bourienne"

The same information can be repeated over and over again to create more branches to the tree.  

<img src="{{ site.url }}{{ site.baseurl }}/images/war_n_peace/collapsible_tree.PNG" alt="collapsible tree">

I also want the selected nodes to be highlighted to distinguish from the unselected nodes. The component "level" can be set for the color of the selected nodes.  Some of the texts can be long so I want the height of the box to be adjusted based on the text content. The component "value" adjusts the height of the nodes based on the length of the text.  They can be defined as below.

<img src="{{ site.url }}{{ site.baseurl }}/images/war_n_peace/collapsible_tree2.PNG" alt="level and value">

You can also attach picture or "icon" to each node using the code below.

<img src="{{ site.url }}{{ site.baseurl }}/images/war_n_peace/collapsible_tree3.PNG" alt="icon">

For complete detail on this collapsible tree, please visit [Collapsible Tree](https://github.com/VictoriaQTHuynh/collapsible_tree_d3_js)

