---
layout: page
title: "Ringvorlesung: Nachhaltige Produkte und Produktion"
events:
  - title: "Der Handabdruck: Ein Ansatz zur Messung positiver Nachhaltigkeitswirkungen von Produkten"
    description: Beschreibung folgt...
    day: 25
    month: März
    type: next
    speakers:
      - Samanthi Silva (Karlsruher Institut für Technologie)
      - Anna Usbek (angefragt)
  - title: "Gerechtigkeit in globalen Lieferketten"
    description: Beschreibung folgt...
    day: 1
    month: April
    type: future
    speakers:
      - Corporate Digital Responsibility – Hubertus Drinkuth (Systain, Otto Group)
      - Tobias Held (angefragt)
  - title: "Offen"
    description: Beschreibung folgt...
    day: 22
    month: April
    type: future
  - title: "Faire Elektronik"
    description: Beschreibung folgt...
    day: 29
    month: April
    type: future
    speakers:
      - Verena Kaiser (Nager IT)
      - Sebastian Jekutsch (FairLötet e.V.)
  - title: "Innovative Baustoffe gegen den Klimawandel"
    description: Beschreibung folgt...
    day: 6
    month: Mai
    type: future
    speakers:
      - Allison Dring (Made of Air)
  - title: "Nachhaltigkeit in anderen Ländern"
    description: Beschreibung folgt...
    day: 13
    month: Mai
    type: future
    speakers:
      - n.n. (Partnerhochschulen der HAW)
  - title: "Der SDG-Index: Spillover Effekte"
    description: Beschreibung folgt...
    day: 27
    month: Mai
    type: future
    speakers:
      - Finn Wölm (SDSN Paris)
---

![logo](https://sdg-events.de/static/sdg-logo.png){:height="100px"}

{:.u-no-margin}
# Nachhaltige Produkte und Produktion
## Öffentliche Ringvorlesung

Um das Wohlergehen heutiger und zukünftiger Generationen zu gewährleisten, ist es unbedingt erforderlich, dass wir die Art und Weise ändern, in der unsere Gesellschaft Waren produziert und konsumiert. Die mit dieser Verschiebung verbundenen technologischen Herausforderungen stehen im Mittelpunkt dieser öffentlichen Vorlesungsreihe: Welche Beiträge können Technologie, Ingenieurwesen und Informatik zu nachhaltigen Produkten, Konsum und größerer Transparenz und Ethik der globalen Lieferketten leisten?

## Nächster Termin

{% assign next_events = page.events | where: "type", "next" %}

{% for event in next_events %}
  {% include event.md event=event %}
{% endfor %}

## Weitere Termine

{% assign future_events = page.events | where: "type", "future" %}

{% for event in future_events %}
  {% include event.md event=event %}
{% endfor %}

## Was ist die Agenda 2030?

Mit der Agenda 2030 für nachhaltige Entwicklung dr&uuml;ckt die internationale Staatengemeinschaft ihre &Uuml;berzeugung aus, dass sich die globalen Herausforderungen nur gemeinsam l&ouml;sen lassen. Kern der Agenda 2030 der Vereinten Nationen (UN) sind die 17 Ziele, die bis 2030 erreicht werden sollen. Sie sind &ouml;konomischer, sozialer und &ouml;kologischer Natur, unteilbar und bedingen einander. Die Ziele sind [hier einsehbar](https://sustainabledevelopment.un.org/sdgs){:target="&#95;blank"}.

## Partner

<div class='o-grid' style='margin-bottom: 32px;'>
  <div class='o-grid__col--4-4-s o-grid__col--2-4-m o-grid__col--1-3-l' markdown='1'>
  [![Hochschule für Angewandte Wissenschaften](/assets/img/haw-logo.png){: style='margin: auto; height: 120px; max-width: 100%;'}](https://www.haw-hamburg.de/){:target="&#95;blank"}
  </div>
  <div class='o-grid__col--4-4-s o-grid__col--2-4-m o-grid__col--1-3-l' markdown='1'>
[![HAW Institut für Produkt- und Produktionsmanagement](/assets/img/ipp-logo.jpg){: style='margin: auto; height: 120px; max-width: 100%;'}](https://www.haw-hamburg.de/ti-mp/ipp/){:target="&#95;blank"}
  </div>
  <div class='o-grid__col--4-4-s o-grid__col--2-4-m o-grid__col--1-3-l' markdown='1'>
[![Förderverein Plan Aktionsgruppe Hamburg](/assets/img/plan-logo.png){: style='margin: auto; height: 120px; max-width: 100%;'}](https://www.plan-aktionsgruppe-hamburg.de/){:target="&#95;blank"}
  </div>
</div>


## Kontakt

**Prof. Dr.-Ing. Thomas Richters**  
Hochschule f&uuml;r Angewandte Wissenschaften Hamburg  
Institut f&uuml;r Produkt- und Produktionsmanagement  
Berliner Tor 21  
20099 Hamburg  
[thomas.richters@haw-hamburg.de](mailto:thomas.richters@haw-hamburg.de){:target="&#95;blank"}


**Dr. Julia W&ouml;lm**  
F&ouml;rderverein Plan Aktionsgruppe Hamburg e.V.  
Fliederweg 6  
22335 Hamburg  
[j.woelm@hamburg.de](mailto:j.woelm@hamburg.de){:target="&#95;blank"}

**Finn W&ouml;lm**  
SDG Index Analyst  
Sustainable Devlopment Solutions Network (SDSN)  
19 Rue Berg&egrave;re  
75009 Paris, Frankreich  
[finn.woelm@gmail.com](mailto:finn.woelm@gmail.com){:target="&#95;blank"}
