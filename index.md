---
layout: splash
permalink: "/"

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/paper_banner.jpg
  actions:
    - label: "GitHub"
      url: "https://github.com/knio-org/knio-core"
excerpt: "From files to sockets, a true non-blocking I/O library built with Kotlin Coroutines and NIO — offering an efficient, readable, and user-friendly `java.io`-like API."

feature_row:
  - image_path: assets/images/paper_kotlin.jpg
    alt: "placeholder image 1"
    title: "Kotlin Coroutines"
    excerpt: "Enables concise, asynchronous, non-blocking code while maintaining the readability and maintainability of sequential programming."
    
  - image_path: /assets/images/paper_nio.jpg
    alt: "placeholder image 2"
    title: "NIO-Powered I/O"
    excerpt: "Built on Java's NIO framework for efficient, scalable, and truly non-blocking I/O operations."
    
  - image_path: /assets/images/paper_api.jpg
    title: "Familiar API"
    excerpt: "Provides a `java.io`-inspired API, allowing developers to modernize existing codebases effortlessly with minimal to no learning curve."

---


{% include feature_row %}
