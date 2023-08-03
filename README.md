# flux-vs-argo-features

This document is meant to provide a succinct comparison of Flux and Argo CD features.

It's based on [Akuity's comparison](https://akuity.io/blog/argo-cd-flux-comparison/).

In each case, the feature is considered supported if it "ships with" the default product installation. Add-ons may be 
available, but they don't count here.

| Features                  | Flux      | Argo CD   |
|---------------------------|-----------|-----------|
| UI                        | No        | Yes       |
| Bootstrapping             | Yes       | No        |
| Multi-tenancy             | Yes       | Yes       |
| Partial Syncs             | No        | Yes       |
| Helm CLI Interoperability | Yes       | No        |
| Pre/Post Sync Hooks       | Helm only | Yes       |
| OCI Artifacts             | Yes       | Helm only |
| S3  Artifacts             | Yes       | No        |
| Automated Helm Rollback   | Yes       | No        |
