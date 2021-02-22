---
title: Interest Form
keywords: release notes, announcements, what's new, new features
last_updated: July 16, 2016
summary: "Committed to showing up? Thank you. Please follow the steps below."
sidebar: mydoc_sidebar
permalink: interest_form.html
folder: mydoc
---

## Step 1: Fill out this Form 

Fill out this form <a target="_blank" href="https://form.jotform.com/210335630809047">here</a>.

## Step 2: Email your Regional Liaison to explore travelling together to Minnesota.

{% for region_data in site.data.regional_liaisons %}
- {{ region_data.region }}
    - <a href="mailto: {{ region_data.email }}">{{ region_data.email }}</a>
{% endfor %}

