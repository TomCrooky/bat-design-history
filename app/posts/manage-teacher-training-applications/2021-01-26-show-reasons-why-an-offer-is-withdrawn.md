---
title: Show reasons why an offer is withdrawn
description: Let users see the reasons why they withdrew an offer
date: 2021-01-26
screenshots:
  items:
    - Feedback page
tags:
  - AN029
---

Providers give feedback to candidates when [withdrawing an offer](/manage-teacher-training-applications/withdrawing-an-offer/). But up to now (as an oversight) we haven’t shown it in the service.

This is also inconsistent with how we [show feedback when an application is rejected](/manage-teacher-training-applications/better-feedback-for-automatically-rejected-applications/).

So we added the feedback to the ‘feedback’ page so providers can always look at it. It’s also a logical place to land once the user withdraws the offer.

## User needs

{% from "user-needs/macro.njk" import appUserNeeds %}
{{ appUserNeeds({ items: collections['user-need'] | slugs(tags)}) }}
