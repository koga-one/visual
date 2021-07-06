---
# Essential settings
title: "{{ replace .Name "-" " " | title }}"
type: "section"
date: {{ .Date }}
translationKey: "{{ replace .Name "-" " " | title }}"

# Scheduling
draft: false
---