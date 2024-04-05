---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /misc/
  - /misc.html
---

<span class='anchor' id='misc'></span>
<div style="overflow: hidden;">
  <h3 class="post-title" itemprop="name">
    <div id="title" onclick="onTileClick()">PhD Scheme</div>
  <h3>
  <div id="content" style="height:150px;transition: height 0.2s;">{% include_relative archive/PhDscheme.md %}</div>
<div>
<script type="text/javascript">
	var content = document.getElementById("content");
	function onTileClick() { content.style.height = content.offsetHeight===150 ? 0+'px' : 150+'px';}
</script> 