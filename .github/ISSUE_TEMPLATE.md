---
title: RELEASE {{ env.GITHUB_REF_NAME }}
labels: RELEASE
---
Author: {{ actor }}
Release date: {{ date | date('dddd, MMMM Do') }}
Version number: {{ env.GITHUB_REF_NAME }}
Changelog: {{env.GITHUB_ENV}}
