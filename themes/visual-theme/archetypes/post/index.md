---
# Essential settings
title: "{{ replace .Name "-" " " | title }}"
type: "post"
date: {{ .Date }}
translationKey: "{{ replace .Name "-" " " | title }}"

# Scheduling
draft: false

# Organization
weight:
categories: [""]
tags: []

# Thumbnail / Featured
thumb: "images/Placeholder.jpg"
---