# Webref data analyses

## Description

This repository contains **machine-readable and human-readable analysis reports of Web spec crawls**. The contents of the repository are updated roughly **every 6 hours**, whenever new data gets published to [Webref](https://github.com/w3c/webref).

Specifications covered by this repository are technical Web specifications that are directly implemented or that will be implemented by Web browsers; in other words, those that appear in [browser-specs](https://github.com/w3c/browser-specs).

## Analysis reports

This repository contains the following human-readable reports:

- [Potential spec anomalies, per spec](https://w3c.github.io/webref-analysis/)
- [Potential spec anomalies, per anomaly](https://w3c.github.io/webref-analysis/)

These reports are created from a machine-readable [JSON report](https://w3c.github.io/webref-analysis/index.json) assembled by running [Strudy](https://github.com/w3c/strudy) on the crawl data published for latest Editor's Drafts of specs in [Webref](https://github.com/w3c/webref).

Beware, anomaly reports may contain false positives!
