---
name: Kubernetes
x-slug: kubernetes
description: Manage a cluster of Linux containers as a single system to accelerate
  Dev and simplify Ops. Kubernetes is an open source orchestration system for Docker
  containers. It handles scheduling onto nodes in a compute cluster and actively manages
  workloads to ensure that their state matches the users declared intentions. Using
  the concepts of labels and pods, it groups the containers which make up an application
  into logical units for easy management and discovery.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Limits
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apis.md
specificationVersion: "0.14"
apis:
- name: Kubernetes - Get Limitranges
  x-api-slug: apiv1beta3limitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-openapi.md
- name: Kubernetes - Get Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Post Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-post
  description: Create a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-post-openapi.md
- name: Kubernetes - Delete Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-delete
  description: Delete a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-delete-openapi.md
- name: Kubernetes - Get Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-get
  description: Read the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Put Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-put
  description: Update the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-put-openapi.md
- name: Kubernetes - Get Watch Limitranges
  x-api-slug: apiv1beta3watchlimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchlimitranges-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges Name
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitrangesname-get
  description: Watch a particular limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Get Limitranges
  x-api-slug: apiv1beta3limitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-openapi.md
- name: Kubernetes - Get Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Post Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-post
  description: Create a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-post-openapi.md
- name: Kubernetes - Delete Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-delete
  description: Delete a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-delete-openapi.md
- name: Kubernetes - Get Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-get
  description: Read the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Put Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-put
  description: Update the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-put-openapi.md
- name: Kubernetes - Get Watch Limitranges
  x-api-slug: apiv1beta3watchlimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchlimitranges-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges Name
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitrangesname-get
  description: Watch a particular limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Get Limitranges
  x-api-slug: apiv1beta3limitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-openapi.md
- name: Kubernetes - Get Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Post Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-post
  description: Create a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-post-openapi.md
- name: Kubernetes - Delete Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-delete
  description: Delete a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-delete-openapi.md
- name: Kubernetes - Get Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-get
  description: Read the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Put Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-put
  description: Update the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-put-openapi.md
- name: Kubernetes - Get Watch Limitranges
  x-api-slug: apiv1beta3watchlimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchlimitranges-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges Name
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitrangesname-get
  description: Watch a particular limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges Name
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitrangesname-get
  description: Watch a particular limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Get Watch Namespaces Limitranges
  x-api-slug: apiv1beta3watchnamespacesnamespaceslimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchnamespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Get Watch Limitranges
  x-api-slug: apiv1beta3watchlimitranges-get
  description: Watch a list of limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3watchlimitranges-get-openapi.md
- name: Kubernetes - Put Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-put
  description: Update the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-put-openapi.md
- name: Kubernetes - Get Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-get
  description: Read the specified limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-get-openapi.md
- name: Kubernetes - Delete Namespaces Limitranges Name
  x-api-slug: apiv1beta3namespacesnamespaceslimitrangesname-delete
  description: Delete a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitrangesname-delete-openapi.md
- name: Kubernetes - Post Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-post
  description: Create a limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-post-openapi.md
- name: Kubernetes - Get Namespaces Limitranges
  x-api-slug: apiv1beta3namespacesnamespaceslimitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3namespacesnamespaceslimitranges-get-openapi.md
- name: Kubernetes - Get Limitranges
  x-api-slug: apiv1beta3limitranges-get
  description: List objects of kind limitrange.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/kubernetes-logo.png
  humanURL: http://kubernetes.io/
  baseURL: :///api/v1beta3/127.0.0.1:6443
  tags: Containers, Google, Stack Network, API Service Provider, Containers, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/limits/master/_listings/kubernetes/apiv1beta3limitranges-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://knoema.api.gallery.streamdata.io
- type: x-api-stack
  url: http://kubernetes.stack.network
- type: x-blog
  url: http://blog.kubernetes.io/
- type: x-blog-rss
  url: http://blog.kubernetes.io/feeds/posts/default
- type: x-github
  url: https://github.com/kubernetes
- type: x-twitter
  url: https://twitter.com/kubernetesio
- type: x-website
  url: http://kubernetes.io/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---