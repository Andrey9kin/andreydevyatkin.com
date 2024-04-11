---
title: 'Andrey Devyatkin | Homepage'
draft: false
headless: false

sections:
    - type: 'section/about'

      hash_id: 'about'
      widget: 'hero' # See https://sourcethemes.com/academic/docs/page-builder/
      headless: true # This file represents a page section.
      active: true # Activate this widget? true/false
      weight: 10 # Order that this section will appear.

      title: 'Academia'
      hero_media: 'andrey.jpg'

      design:
          background:
              color: '#fff'
              # gradient_start: "#4bb4e3"
              # gradient_end: "#000"

              # Background image.
              # image = ""  # Name of image in `static/img/`.
              # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

              # Text color (true=light or false=dark).
              text_color_light: false

      #   btn:
      #       url: '/authors/admin'
      #       label: 'Know more'

      #   btn_alt:
      #       url: '#contact'
      #       label: 'Contact me'

      content: |
          ## Hi, my name is Andrey Devyatkin

          I'm independent consultant specialized in building secure application delivery platforms on AWS using HashiStack and Kubernetes.

          -   **AWS architect** (6x certifications)

          -   **Continuous Integration** and **Continuous delivery** expert

          -   Trainer (**Git**, **Jenkins**, **Docker**, **CI/CD**, **Terraform**, **Vault**)

          - Public speaker

          - Co-Founder at FivexL. Cloud Engineering Specialists

          - Co-host at DevSecOps Talks Podcast

          - Meetups organizer (Cloud Native Las Palmas de Gran Canaria, HashiCorp User Group Las Palmas de Gran Canaria).

    - type: 'section/simple'
      hash_id: 'consulting'

      heading: 'Consulting'

      image_src: 'andrey-consulting.jpg'
      image_alt: 'Consulting'
      image_position: right

      content: |
          * AWS infrastructure architecture - evolving existing or building from the ground up

          * Immutable Could infrastructure using HashiCorp Packer and HashiCorp Terraform

          * Orchestrating applications using AWS ECS/Kubernetes/HashiCorp Nomad

          * Infrastructure and application secret management using HashiCorp Vault

          * Cloud infrastructure and application security

          * Compliance in the Cloud environments

          * Building and scaling Continuous Integration and Continuous Delivery pipelines using Jenkins

    - type: 'section/simple'
      hash_id: 'certificates'

      heading: 'Certificates'

      content: |
          <div class="flex-next-in-paragraph">

            ![Solution Architect](/img/certificates/AWS-SolArchitect-Associate.png)
            ![Developer](/img/certificates/AWS-Developer-Associate.png)
            ![SysOps Administrator](/img/certificates/AWS-SolArchitect-Associate.png)
            ![Security](/img/certificates/AWS-Security-Specialty.png)
            ![Terraform Associate](/img/certificates/Terraform-Associate-Badge.png)
          </div>
    - type: 'section/simple'
      hash_id: 'speaking'

      heading: 'Public speakung'

      image_src: 'andrey-public-speaking.jpg'
      image_alt: 'Public speakung'
      image_position: left

      content: |
          - Why I do not recommend people learning Ansible? (DevOoops Piter 2020)

          - Vault Configuration as Code via Terraform: Stories from Trenches (DevOpsPro Moscow 2019, HashiTalks 2020, DevOpsDays Madrid 2020, DevOpsPro EU 2020, HashiConf Digital EU 2020)

          - Integrating HashiCorp Vault and Kubernetes apps (HashiTalks 2019)

          - Getting Git Right (GitMerge 2018)

          - Introduction to Continuous Delivery (RemoteForeverSummit 2017)

          - Patterns of Continuous Delivery (Continuous Delivery Conference Stockholm 2017)

          - Jenkins as Code (Day of Jenknis 2017 Oslo, Day of Jenknis 2017 Gothenburg)

          - Buffer or suffer? Growth pain of Continuous Delivery pipelines and what to do about it (Continuous Delivery Conference Stockholm 2016)

    - type: 'section/talks'
      hash_id: 'talks'
      heading: 'Talks'
      talks:
          - video_url: 'https://www.youtube.com/embed/PI9lU9jDlE8'
            title: 'Vault Configuration as Code via Terraform Stories From the Trenches'

          - video_url: 'https://www.youtube.com/embed/t6ZKhY0-_cA'
            title: 'Integrating HashiCorp Vault and K8s Apps - No Code Changes Needed'

          - video_url: 'https://www.youtube.com/embed/1UJdzpEr3rg'
            title: "Looking for that needle in the hay of Vault's audit log"

          - video_url: 'https://www.youtube.com/embed/hvQeWJSDwkE'
            title: 'Getting Git right - Git Merge 2018'

          - video_url: 'https://www.youtube.com/embed/JpkJDvhXkrE'
            title: 'Buffer or suffer? Growth pain of Continuous Delivery pipelines and what to do about it'
---
