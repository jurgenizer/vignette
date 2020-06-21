---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
url: {{ replace .Name "-" " " | lower }}
type: form
layout: contact
submit_button_label: Send
formspree_form_id: # your@email.here
---
