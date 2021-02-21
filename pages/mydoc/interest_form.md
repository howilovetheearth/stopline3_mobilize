---
title: Interest Form
tags: [background]
keywords: release notes, announcements, what's new, new features
last_updated: July 16, 2016
summary: "Committed to showing up? Thank you. Please follow the steps below."
sidebar: mydoc_sidebar
permalink: interest_form.html
folder: mydoc
---

## Sign up to Attend and Get in Touch with an Organizer

Fill out this form <a target="_blank" href="https://form.jotform.com/210335630809047">here</a>.

## Email your Regional Liaison to explore travelling together to Minnesota.

{% for region_data in site.data.regional_liaisons %}
- {{ region_data.region }}
    - <a href="mailto: {{ region_data.email }}">{{ region_data.email }}</a>
{% endfor %}

