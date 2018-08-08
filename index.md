---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div class="home">
  {%- if site.github_userid -%}<img src="https://avatars.githubusercontent.com/u/{{ site.github_userid| cgi_escape | escape }}?" alt="avatar"/>{%- endif -%}
  <h1>{{ site.title }}</h1>
  <h2>{{ site.description }}</h2>

  <div>
    {%- include social.html -%}
    {%- if site.email -%}
    	<a class="u-email" href="mailto:{{ site.email }}">{{ site.email }}</a>
    {%- endif -%}
  </div>
</div>