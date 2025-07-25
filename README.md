# JBoss Helm Chart

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Scalified/helm-jboss/blob/master/LICENSE)
[![Release](https://img.shields.io/github/v/release/Scalified/helm-jboss?style=flat-square)](https://github.com/Scalified/helm-jboss/releases/latest)
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/scalified-jboss)](https://artifacthub.io/packages/helm/scalified-jboss/jboss)

## Requirements

* [Helm 3+](https://helm.sh)

## Installation

```bash
helm repo add scalified-jboss https://scalified.github.io/helm-jboss/
helm upgrade --install jboss scalified-jboss/jboss --create-namespace --namespace jboss
```

---

**Made with ❤️ by [Scalified](http://www.scalified.com)**
