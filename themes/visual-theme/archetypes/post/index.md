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

# Prototyping
layout: "prototype"

# Thumbnail / Featured
thumb: "images/Placeholder.jpg"

# Meta
summary: 
---