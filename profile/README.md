# Nixiesearch: batteries included search engine

[![CI Status](https://github.com/nixiesearch/nixiesearch/workflows/Tests/badge.svg)](https://github.com/nixiesearch/nixiesearch/actions)
[![License: Apache 2](https://img.shields.io/badge/License-Apache2-green.svg)](https://opensource.org/licenses/Apache-2.0)
![Last commit](https://img.shields.io/github/last-commit/nixiesearch/nixiesearch)
![Last release](https://img.shields.io/github/release/nixiesearch/nixiesearch)
[![Join our slack](https://img.shields.io/badge/Slack-join%20the%20community-blue?logo=slack&style=social)](https://communityinviter.com/apps/nixiesearch/nixiesearch)
[![Visit demo](https://img.shields.io/badge/visit-demo-blue)](https://demo.nixiesearch.ai)

## What is Nixiesearch?

Nixiesearch is a **hybrid search engine** that fine-tunes to your data. 

* Designed to be cloud-native with [S3-compatible index persistence](https://www.nixiesearch.ai/deployment/distributed/persistence/s3). Distributed with stateless searchers and scale-to-zero. No more `status: red` on your cluster.
* Built on top of battle-tested [Apache Lucene](https://lucene.apache.org) library: [39 languages](https://www.nixiesearch.ai/reference/languages), [facets](https://www.nixiesearch.ai/features/search/facet), [advanced filters](https://www.nixiesearch.ai/features/search/filter), [autocomplete suggestions](https://www.nixiesearch.ai/features/autocomplete) and [sorting](https://www.nixiesearch.ai/features/search/sort) out of the box.
* Batteries included: [RAG queries](https://www.nixiesearch.ai/features/search/rag) and [vector search](https://www.nixiesearch.ai/reference/models/index) within a [single container](https://www.nixiesearch.ai/deployment/standalone) with a fully local CPU and [GPU inference](https://www.nixiesearch.ai/deployment/gpu). 
* Can learn the intent of a visitor by [fine-tuning an embedding model](https://github.com/nixiesearch/nixietune) to your data. Is "ketchup" relevant to a "tomato" query? It depends, but Nixiesearch can predict that from past user behavior.

> Want to learn more? Go straight to the [quickstart](https://www.nixiesearch.ai/quickstart/) and check out [the live demo](https://demo.nixiesearch.ai). 
