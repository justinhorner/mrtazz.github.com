---
layout: default
title: Talks
talks:
  -
    title: Scaling Deployment at Etsy (revised)
    url: https://speakerdeck.com/mrtazz/continuous-delivery-meetup-nyc-2013
    video: http://www.youtube.com/watch?v=moXWsHEtBEw
    conference: Continuous Delivery NYC Meetup
    date: Oct 09, 2013
  -
    title: Feature Flagging your Infrastructure for Fun and Profit
    url: https://speakerdeck.com/mrtazz/feature-flagging-your-infrastructure-for-fun-and-profit
    conference: NYC LOPSA Meetup
    date: Sep 11, 2013
  -
    title: DevTools at Etsy
    url: https://speakerdeck.com/mrtazz/devtools-at-etsy
    video: http://vimeo.com/70764386
    conference: DevOpsDays Berlin
    date: May 27, 2013
  -
    title: Scaling Deployment at Etsy
    url: https://speakerdeck.com/mrtazz/scaling-deployment-at-etsy
    video: http://www.youtube.com/watch?v=AwOG65UGAH4
    conference: Scaleconf Cape Town
    date: Apr 18, 2013
  -
    title: StatsD Workshop
    url: https://speakerdeck.com/mrtazz/statsd-workshop
    video: http://vimeo.com/67183450
    conference: Monitorama Boston
    date: Mar 29, 2013
  -
    title: Chef Workflow at Etsy
    url: https://speakerdeck.com/mrtazz/chef-workflow-at-etsy
    conference: NYC Chef Meetup
    date: Jan 29, 2013
---
## [Talks]({{page.url}})

<div class="postconent talks">
  <ul class="archive">
  {% for talk in page.talks %}
    <li>
    {{ talk.title }}, {{ talk.conference }}
    <a href="{{ talk.url }}"><i class="icon-edit" style="font-size: 15px;"> </i></a>
    {% if talk.video %}
    <a href="{{ talk.video }}"><i class="icon-film" style="font-size: 15px;"> </i></a>
    {% endif %}
    <span class="archivedate">{{ talk.date }}</span>
    </li>
  {% endfor %}
  </ul>
</div>
