---
title: "COVID-19 LAMP Test"

# excerpt goes on splash page
excerpt: "DIY diagnostic test for COVID-19"

header:
  image: /assets/project-assets/covid_test-2021/covid_test_hero.jpg
  teaser: /assets/project-assets/covid_test-2021/covid_test_thumb.jpg
sidebar:
  - image: /assets/project-assets/covid_test-2021/covid_test_flow.jpg
    image_alt: "Multiplex QUASR LAMP version."
  - title: "Year: 2021"
  - title: "Resources"
  - text: "[Publication](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8730513/){:target='_blank'}"
gallery:
  - url: /assets/project-assets/covid_test-2021/covid_test_results.jpg
    image_path: /assets/project-assets/covid_test-2021/covid_test_results.jpg
    alt: "Overview of results from a from the One Hour COVID test showing accuracy."
  - url: /assets/project-assets/covid_test-2021/covid_test_flow.jpg
    image_path: /assets/project-assets/covid_test-2021/covid_test_flow.jpg
    alt: "Overview of the One Hour COVID test"
  - url: /assets/project-assets/covid_test-2021/covid_test_tscreen.jpg
    image_path: /assets/project-assets/covid_test-2021/covid_test_tscreen.jpg
    alt: "Example of temperature screening experiment to determine optimal assay conditions."
---
In response to the dire need for accessible diagnostic testing early in the COVID-19 pandemic, I worked with a group of independent researchers to develop an open-source diagnostic test based on Loop-mediated Isothermal Amplification (LAMP). Our test used saliva as a minimally-invasive sample type collected via a commercially collection kit from DNAGenotek. We then adapted a nucleic isolation process used for DNA to work well with RNA that doesn't require a centrifuge. The LAMP assay itself is based on NEB's colorimetric LAMP kit which allows for easy visual readout using a colorimetric indicator. The time from collection to result can be as little as an hour with high specificty and sensitivity.

{% include gallery caption="" %}

In addition to the colorimetric LAMP assay, we explored the use of the QUASR-LAMP technique and developed a multiplex version shown in the banner image that can detect SARS-CoV-2 (green) and a human beta-actin internal control (red) at the same time. In combination, a result with both would result in a yellow fluorescent read-out. 

A link to the manuscript describing our colorimetric test is avaiable in the resources section to the left.
