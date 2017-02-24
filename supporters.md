---
layout: default
title: Supporters
---

# Supporters

<!-- when adding sponsor logos here, need also to add them to the sponsor ticker tape - see include/footer.php file -->

<!--

## Platinum

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "platinum"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 80px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</p>

-->

## Gold

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "gold"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 80px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</p>


## Silver


<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "silver"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 80px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</p>

<!--
<div class="sponsors">
   <center>
      <table width="100%" border="0">
         <tr>
            <td align="center">
               <a href="//www.akamai.com/"><img src="images/sponsors/akamai.png" alt="Akamai" style="width: 35%;"/></a>
            </td>
         </tr>
      </table>
   </center>
</div>
-->

## Bronze

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "bronze"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 80px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</p>


## Universities

<p>
<div style="text-align: center;">
{% for supporter in site.data.supporters
%}{% if supporter[7] == "university"
%}<a href="{{ supporter[2] }}"><img src="{{ site.baseurl }}/images/sponsors/{{ supporter[1] }}" alt="{{ supporter[3] }}" style="height: 80px; margin: 10px" /></a>
{% endif
%}{% endfor %}
</div>
</p>
