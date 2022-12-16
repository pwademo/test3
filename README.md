---
---
# Readme

[relative reference to a LICENSE](../blob/main/LICENSE)



https://github.com/pwademo/workshop-example/blob/main/LICENSE 


{% assign directoryroot = site.source-code | append: "/tree/main" %}
{% assign fileroot = site.source-code | append: "/blob/main" %}

# {{ directoryroot }}

## Pages
Pages is in this directory: 
<a target="_blank" href="{{ directoryroot | append: '/pages' }}">{{ directoryroot | append: '/pages' }}</a>

## Gallery
All images in this directory: 
<a target="_blank" href="{{ directoryroot | append: '/gallery' }}">{{ directoryroot | append: '/gallery' }}</a>

All meta-data for the images in the gallery is in this file:
<a target="_blank" href="{{ fileroot | append: '/_data/gallery.json' }}">{{ fileroot | append: '/_data/gallery.json' }}</a>

## Layout settings
<a target="_blank" href="{{ fileroot | append: '/_data/settings.json' }}">{{ fileroot | append: '/_data/settings.json' }}</a>

## Favicons
<a target="_blank" href="{{ directoryroot | append: '/favicons' }}">{{ directoryroot | append: '/favicons' }}</a>



