# Changelog

All notable changes to this library will be documented in this file.

Entries should be ordered as follows:

- [CHANGE]
- [FEATURE]
- [ENHANCEMENT]
- [BUGFIX]

Entries should include a reference to the pull request that introduced the change.

## 2.0.0

- ⚠️ BREAKING [CHANGE] Make Azurite image configuration compatible with renovate/dependabot
- ⚠️ BREAKING [CHANGE] Disable --loose by default
- [FEATURE] Allow specifying imagePullSecret in initJob
- [FEATURE] Allow passing additional arguments to azurite process
- [ENHANCEMENT] Make --loose and --disableProductStyleUrl configurable
- [ENHANCEMENT] Move initJob image configuration into values.yaml
- [ENHANCEMENT] Bump default Azurite version to 3.29.0

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
