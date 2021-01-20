---
title: "Home"
seo_title: "OpenGENESIS Working Group"
headline: "OpenGENESIS Working Group"
description: "The mission of the openGENESIS Working Group is to provide methods and tools for the assessment of artificial intelligence (AI) used for autonomous driving."
hide_page_title: true
hide_sidebar: true
hide_breadcrumb: true
show_featured_story: true
date: 2019-09-10T15:50:25-04:00
layout: "single"
container: "container-fluid"
---

{{< grid/section-container >}}
  {{< grid/div class="col-sm-15 margin-top-30" isMarkdown="false" >}}
    {{< newsroom/news
          title="News"
          titleClass="heading-line text-center"
          id="news-list-container"
          publishTarget="opengenesis"
          count="5"
          templateId="news-no-mh"
          templatePath="node_modules/eclipsefdn-hugo-solstice-theme/js/templates/news-no-mh.mustache"
          includeList="true" >}}
  {{</ grid/div >}}
  {{< grid/div class="col-sm-8 col-sm-offset-1 margin-top-30" isMarkdown="false" >}}
    {{< newsroom/events
          title="Events"
          titleClass="heading-line text-center"
          containerClass="news-items event-container"
          id="events-list-container"
          publishTarget="opengenesis"
          count="5"
          templateId="event-list-format"
          templatePath="node_modules/eclipsefdn-hugo-solstice-theme/js/templates/event-list-format.mustache"
          includeList="true" >}}
  {{</ grid/div >}}
{{</ grid/section-container >}}
