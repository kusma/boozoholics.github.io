---
layout: default
prods:
  - title: Boozed Over the Limits (Wild)
    pouet-id: 10245
    url: http://www.scene.org/file.php?file=/parties/2003/symphony03/wild/boozed_over_the_limits-pgs-bzh.avi&fileinfo
  - title: Leia fucked the girl in Hanson (PC)
    pouet-id: 11048
    url: http://www.dritings.no/hanson.zip
  - title: HytteLAN 2004 Invitation (PC)
    pouet-id: 12694
    url: http://www.dritings.no/files/bzh-hytte.rar
  - title: fuckoff9007 (Amiga)
    pouet-id: 12043
    url: http://ftp.snt.utwente.nl/pub/misc/demoscene/Amiga%20Demo/BZHFUCK.lha
  - title: Orcane (Amiga)
    excuse: This great production (featuring the voicesynth that amazed the audience at breakpoint) sadly disappeared in a terrible harddrivecrash
  - title: Solskogen 2004 invitation (Amiga)
    pouet-id: 12387
    url: http://www.stud.ntnu.no/~remijoha/bzhsol04.lha
  - title: Dance Extravaganza (Amiga)
    pouet-id: 12715
    url: http://www.stud.ntnu.no/~remijoha/BzhDance.lha
  - title: Movement (Real life)
    excuse: Entry for the Altstork 2004 moving visuals compo. <a href="./assets/movement.jpg" target="_blank">Picture of the spectators</a>
  - title: Gay Fashion Show (Windows)
    pouet-id: 12954
    url: ./files/bzh-gay.rar
  - title: Deilig (Windows)
    pouet-id: 13387
    url: http://www.home.no/ebbe.smith/Bzh-Deilig.zip
---
**productions :**

<p>
{% for prod in page.prods %}
{% if prod.url %}
<strong><a href="{{ prod.url }}">{{ prod.title }}</a></strong> - <a href="http://www.pouet.net/prod.php?which={{ prod.pouet-id }}" target="_blank">Comment at Pouet</a>
{% else %}
<strong>{{ prod.title }}</strong> - {{ prod.excuse }}
{% endif %}
<br/>
{% endfor %}
</p>
