---
layout: tools
title: HTML Encoder Decoder online tools
permalink: tools/html-encoder-decoder/
---
<script type="text/javascript"> function $(esc_tool){ return document.getElementById(esc_tool) } var char2entity = { "'" : '&#39;', '"' : '&quot;',  '<' : '&lt;', '>' : '&gt;',  '&' : '&amp;'}; function escape_entities(str) { var rv = ''; for (var i = 0;i < str.length; i++) { var ch = str.charAt(i); rv += char2entity[ch] || ch; } return rv; } function do_escape(e){ $('escaped').value = escape_entities(e.value) }    </script> <br />

Simply Just Paste your HTML code into the first box and you will automatically see the converted characters into the second box.

**Enter your code here:**

<textarea onchange="do_escape(this)" onkeyup="do_escape(this)" rows="10" style="font-family: ‘courier new’,monospace; height: 10em; width: 450px;"></textarea> <br /><br /> 


**Your encoded code is:**


<textarea id="escaped" onclick="this.select()" onfocus="this.select()" readonly="readonly" rows="10" style="background: #f0f0f0; font-family: ‘courier new’,monospace; height: 10em; width: 450px;"></textarea>  


**Note:** At this time, this tool is only helpful to convert adsense ads code. Soon I will develop to covert all HTML entities.

