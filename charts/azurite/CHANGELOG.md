# Changelog

All notable changes to this library will be documented in this file.

Entries should be ordered as follows:

- [CHANGE]
- [FEATURE]
- [ENHANCEMENT]
- [BUGFIX]

Entries should include a reference to the pull request that introduced the change.

## 1.10.0

- [FEATURE] Allow specifying imagePullSecret in initJob
- [FEATURE] make --loose configurable
- [ENHANCEMENT] bump default Azurite version to 3.26.0
- [CHANGE] move image version into values and adjust format to be compatible with renovate/dependabot
- [CHANGE] don't hardcode initJob image, move image config into values.yaml instead

## 1.8.0

- [CHANGE] Bump Azurite version to 3.21.0
- [BUGFIX] Set missing serviceName on StatefulSet

## 1.7.0

- [FEATURE] Allow to set annotations on statefulset

## 1.6.0

- [FEATURE] Allow to change type of service

## 1.5.0

- [FEATURE] Add `tls` support on ingress

## 1.4.0

- [FEATURE] Add `containerSecurityContext`

## 1.3.1

- [BUGFIX] Fix ingress conditions 

## 1.3.0

- [CHANGE] Change ingress defaults

## 1.2.0

- [CHANGE] Use `--disableProductStyleUrl` in StatefulSet
- [CHANGE] Rework ingress routing 

## 1.1.0

- [CHANGE] `initJob` for blobs is now disabled by default 
- [FIX] Fixed ingress paths 

## 1.0.0

- [FEATURE] Release working chart
- [BUGFIX] Fix connection string for containers init job

## 0.1.0

- [FEATURE] Initial version of the `azurite` Helm chart.
