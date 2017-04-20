---
layout: frontpage
title:
---

<p class="text-center"><strong>International Conference on Knowledge Engineering and Semantic Web</strong></p>

<p class="text-center"><strong>08-10 November 2017</strong></p>

<p class="text-center"><strong>Szczecin, Poland</strong></p>

<blockquote>
    <p><strong>Latest news:</strong></p>
    <ul class="news">
    {% for post in site.posts limit: 3 %}
        <li>
            {{ post.date | date: "%-d %B %Y" }}
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
    </ul>
</blockquote>


<p class="text-justify">KESW 2017 will be the 8th conference in the series. KESW is a top international event dedicated to discussing research results and directions in the areas related to Knowledge Representation and Reasoning, Semantic Web, and Linked Data. Its aim is to bring together researchers, practitioners, and educators, in particular from ex-USSR, Eastern and Northern Europe, to present and share ideas regarding Semantic Web, and popularize the area in these regions.</p>

<p class="text-justify">The conference especially welcomes students, postdocs, and other early career researchers and encourages them to participate, contribute, and discuss research projects regardless of their maturity.</p>

<p class="text-justify">More information will be announced later, stay tuned and <a href="https://twitter.com/keswconference">follow us</a> on Twitter!</p>

<blockquote>
<h4>IMPORTANT DATES</h4>
<ul>
    <li>Abstract submission: <b>Monday, 5 June 2017</b></li>
    <li>Full paper submission: <b>Monday, 19 June 2017</b></li>
    <li>Author notification: <b>Thursday, 3 August 2017</b></li>
    <li>Camera-ready submission: <b>Monday, 21 August 2017</b></li>
    <li>Early registration: <b>TBD</b></li>
    <li>Late registration: <b>TBD</b></li>
    <li>Conference dates: <b>November 08 – 10, 2017</b></li>
</ul>


<p class="text-justify"><i>All deadlines are for the Hawaii time zone.</i></p>
</blockquote>
