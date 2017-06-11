---
layout: page
title: Organization committee
---

**General Chair:** [Przemyslaw Różewski](http://www.prozewski.zut.edu.pl/), West Pomeranian University of Technology in Szczecin, Poland

**Program Chair:** [Christoph Lange](https://langec.wordpress.com/about/), University of Bonn and Fraunhofer IAIS, Germany

**Local organisation team:**

  * Magdalena Kieruzel, West Pomeranian University of Technology in Szczecin, Poland
  * Wojciech Sałabun, West Pomeranian University of Technology in Szczecin, Poland
  * Tomasz Lipczynski, West Pomeranian University of Technology in Szczecin, Poland

<br/>
**Web Presence:** [Maxim Kolchin](http://kolchinmax.ru), ITMO University, Russia

### Program committee

<table id="pc">
{% for member in site.data.pc %}
    <tr>
        <td class="name" width="30%">
            {%if member.page %}
                <a href="{{ member.page }}">{{ member.name }}</a>
            {% else %}
                {{ member.name }}
            {% endif%}
        </td>
        <td class="affiliation" width="70%">{{ member.affiliation }}</td>
    </tr>
{% endfor %}
</table>
