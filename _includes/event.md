<div class='highlight-box u-block flex'>

<div class="date">
  <div class="day">
    {{ event.day }}
  </div>
  <div class="month">
    {{ event.month }}
  </div>
  <div class="rest">
    18 Uhr<br/>
    @ HAW
  </div>
</div>

<div class="content" markdown='1'>

{:.u-no-margin}
### {{ event.title }}

{:.u-no-margin}
{{ event.description }}

{% for speaker in event.speakers %}
  {:.u-no-margin}
  *&mdash; {{ speaker }}*
{% endfor %}

<div class="c-spacing-2"></div>

{:.u-no-margin}
[Anmelden](https://docs.google.com/forms/d/e/1FAIpQLSf4g0PwGNVS4Bu0kFwv6QWKpLS4eCxY2nvENK8GfS-To10fLw/viewform){:.c-btn target="&#95;blank"}

</div>
</div>
