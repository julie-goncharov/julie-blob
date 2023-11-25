---
layout: default
title: Publications
permalink: /publications/
usebibtex: true
---
<!--
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script  type="text/javascript" src="{{ '/assets/js/bibtex_js.js' | relative_url }}"></script>

<bibtex src="{{ "/" | relative_url }}assets/docs/mybibliography.bib"></bibtex>
-->
<h1 class="mt-4">Publications</h1>

<div class="bibtex_structure">
  <div class="sort year" extra="DESC number">
          <div class="templates"></div>
  </div>
</div>

<div id="bibtex_display"></div>

<div class="bibtex_template" style="display: none;">
    <div class="pubitem">
      <div class="pubtitle">
          <span class="if year"><span class="year"></span></span>
          ,
          <span class="if title"><span class="title"></span></span>
      </div>
      <div class="pubauthors">
          <span class="author"></span>
          ,
          <span class="if journal"><em><span class="journal"></span></em>,</span>
          <span class="if publisher"><em><span class="publisher"></span></em>,</span>
          <span class="if booktitle">In <em><span class="booktitle"></span></em>,</span>
          <span class="if address"><span class="address"></span>,</span>
          <span class="if month"><span class="month"></span>,</span>
          <span class="if year"><span class="year"></span>.</span>
<!--          <span class="if note"><span class="note"></span></span> -->
         <span class="if note">
            <a class="bibtexVar" href="{{ "/" | relative_url }}assets/docs/+NOTE+" extra="note" target='_blank' rel="noopener noreferrer">
              [PDF]
            </a>
          </span>
          <span class="if url">
            <a class="bibtexVar" href="+URL+" extra="url" target='_blank' rel="noopener noreferrer">
              [WEB]
            </a>
          </span>
          <span class="if doi">
              <a class="bibtexVar" href="http://dx.doi.org/+DOI+" extra="doi" target='_blank' rel="noopener noreferrer">
                [DOI]
              </a>
          </span>
      </div>
      <div class="publinks">
          <details><summary style="cursor: pointer;"><a aria-controls="bib+BIBTEXKEY+"  extra="BIBTEXKEY" bibtexjs-css-escape>[BibTex]</a></summary>
               <div class="bibtexVar" id="bib+BIBTEXKEY+" extra="BIBTEXKEY">
                       <pre><span class="bibtexraw noread"></span></pre>
               </div>
           </details>
 
<!--          <a class="bibtexVar" href="{{ "/" | relative_url }}assets/docs/+BIBTEXKEY+.pdf" extra="BIBTEXKEY" target='_blank' rel="noopener noreferrer">PDF
          </a>
-->
<!--          <span class="if note">
            <a class="bibtexVar" href="{{ "/" | relative_url }}assets/docs/+NOTE+" extra="note" target='_blank' rel="noopener noreferrer">
              PDF
            </a>
          &nbsp;&nbsp;
          </span>
          <span class="if url">
            <a class="bibtexVar" href="+URL+" extra="url" target='_blank' rel="noopener noreferrer">
              WEB
            </a>
          &nbsp;&nbsp;
          </span>
          <span class="if doi">
              <a class="bibtexVar" href="http://dx.doi.org/+DOI+" extra="doi" target='_blank' rel="noopener noreferrer">
                DOI
              </a>
          &nbsp;&nbsp;
          </span>
-->
<!--
<table style="border: none;" cellspacing="0" cellpadding="0">
    <tbody>
        <tr>
          <td style="width: 15%;border:none;padding: 0px;">
                      <span class="if note">
            <a class="bibtexVar" href="{{ "/" | relative_url }}assets/docs/+NOTE+" extra="note" target='_blank' rel="noopener noreferrer">
              PDF
            </a>
          </span>
                      <span class="if url">
            <a class="bibtexVar" href="+URL+" extra="url" target='_blank' rel="noopener noreferrer">
              WEB
            </a>
          </span>
          <span class="if doi">
              <a class="bibtexVar" href="http://dx.doi.org/+DOI+" extra="doi" target='_blank' rel="noopener noreferrer">
                DOI
              </a>
          </span>
          </td>
            <td style="border:none;padding: 0px;">
          <details><summary style="cursor: pointer;"><a aria-controls="bib+BIBTEXKEY+"  extra="BIBTEXKEY" bibtexjs-css-escape>[BibTex]</a></summary>
               <div class="bibtexVar" id="bib+BIBTEXKEY+" extra="BIBTEXKEY">
                       <pre><span class="bibtexraw noread"></span></pre>
               </div>
           </details>
          </td>
        </tr>
      </tbody>
    </table>
-->
  </div>
    </div>
</div>

<!--
<h1 class="mt-4">Publications</h1>
{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}
<div class="pubitem">
  <div class="pubtitle">
            {{ pub.year}}, {{ pub.title }}
  </div>
  <div class="pubauthors">
    {{ pub.authors }}, {{ pub.publication }}
  </div>
  <div class="publinks">
  {% if pub.pdf %}
    <a href="{{ "/" | relative_url }}/assets/docs/{{ pub.pdf}}" target="_blank" rel="noopener noreferrer">PDF</a>
    {% endif %}
    &nbsp;&nbsp;
    <a href="{{ pub.url | relative_url }}"><i>Abstract</i></a>
  </div>
</div>
{% endfor %}
-->
