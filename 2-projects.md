---
layout: default
title: Projects
permalink: /projects/
---

<h1 class="mt-4">Projects</h1>
{% assign projects = site.projects | sort: 'num' | reverse %}
{% for proj in projects %}
<table class="project" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
            <td class="proj-left" align="center" valign="top">
                <span class="proj-logo">
                    <img src="{{ "/" | relative_url }}/assets/images/{{ proj.logo }}" class="project-image" />
                </span>
                {{ proj.short }}
            </td>
            <td class="proj-right">
                <div class="alignright">
                    <a class="button" target='_blank' href="{{ proj.ref }}">
                        <img style="width: 20px; height: 20px; border: none;" src="{{ "/" | relative_url }}assets/images/arrowright.png" />
                    </a>
                </div>
                {{ proj.period }}
                <div class="proj-title">{{ proj.title }}</div>
                {{ proj.excerpt }}
            </td>
        </tr>
    </tbody>
</table>
{% endfor %}
