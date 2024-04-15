---
title: Integrating HashiCorp Vault and K8s
type: talk

event: hashicorp
event_url: https://events.hashicorp.com/hashitalks2020
summary: 'Integrating HashiCorp Vault and K8s Apps - No Code Changes Needed '
abstract: |
    * How do you authenticate apps in Vault?
    * How do you get an initial token?
    * How to read secrets from Vault?
    * How to keep token and secrets renewed?
    * How and when do you revoke tokens and secrets?

    That seems to be very different from typical a 12-factor apps setup when an app would simply read configuration and secrets from environment variables, isn't it? Should you write a library to encapsulate this logic? Or is there an SDK available? There is a way to address all questions above with little to no code changes at all!

    I'm going to demo it and then go into the nitty-gritty details of its implementation so you can repeat the same steps at home or work.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2020-02-20T18:00:00Z'
end_date: '2020-02-20T18:30:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2020-02-20T18:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
    caption: 'Image credit: [**youtube**](https://www.youtube.com/watch?v=t6ZKhY0-_cA)'
    focal_point: Right

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
# - internal-project

# Enable math on this page?
math: true
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/t6ZKhY0-_cA?si=cYtAXsp2VhpI8lik" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

{{% alert note %}}
HashiCorp is the leader in multi-cloud infrastructure automation software. The HashiCorp software suite enables organizations to adopt consistent workflows to provision, secure, connect, and run any infrastructure for any application. HashiCorp open source tools Vagrant, Packer, Terraform, Vault, Consul, Nomad, Boundary, and Waypoint are downloaded tens of millions of times each year and are broadly adopted by the Global 2000. Enterprise versions of these products enhance the open source tools with features that promote collaboration, operations, governance, and multi-data center functionality.
{{% /alert %}}
