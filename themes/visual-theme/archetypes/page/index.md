---
# Essential settings
title: "{{ replace .Name "-" " " | title }}"
type: "page"
date: {{ .Date }}
translationKey: "{{ replace .Name "-" " " | title }}"

# Scheduling
draft: false

# Organization
weight:
---