---
title: "Issue Discovery"
subtitle: "High-Fidelity"
description: "Comprehensive data and visualizations for Onsite, Onpage, and Competitive gaps found during the audit. We transition from observations to algorithmic evidence."
type: "issue-discovery"
layout: "single"
weight: 3
onsite:
  total_urls: "4,000+"
  strategic: 56
  duplicate: 26
  errors: 16
  other: 2
  duplication_rate: "15%"
  duplication_desc: "Analysis reveals consistent crawl waste across 4,000+ URLs. Primary drivers: Inconsistent trailing slash enforcement and un-canonicalized session ID handling in dynamic facets."
  alert: "Duplicate parameters are diluting internal link equity by 32% across high-intent category nodes."
onpage:
  latency_label: "3-5 DAYS GAP"
  depth_map:
    - label: "Depth 1-2"
      value: "15%"
    - label: "Depth 3-4"
      value: "45%"
    - label: "Depth 5+"
      value: "40%"
      highlight: true
  depth_desc: "Internal equity dilution identified. 40% of strategic content is buried too deep for consistent re-crawling."
competitive:
  sov_gap: "25% Gap"
  sov_desc: "Competitor A dominates long-tail commercial intent."
  arch: "Flat (Max 3)"
  arch_desc: "Optimal link flow facilitates rapid sub-page indexing."
  ttfb: "<200ms"
  ttfb_desc: "Superior edge caching infrastructure vs our 850ms."
---
