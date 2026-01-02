<h2 id="awards" style="margin: 60px 0px -15px;">Awards & Honors</h2>

<div class="awards">
<ol class="bibliography">

{% for award in site.data.awards.main %}

<li>
<div class="award-row">
  <strong>[{{ award.year }}]</strong> {{ award.icon }} {{ award.title }}
</div>
</li>

{% endfor %}

</ol>
</div>
