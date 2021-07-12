---
# Essential settings
title: "{{ replace .Name "-" " " | title }}"
subtitle: ""
type: "page"
date: {{ .Date }}
translationKey: "{{ replace .Name "-" " " | title }}"

# Scheduling
draft: false

# Organization
layout: "page"
weight:
buttons:
---