# Changelog

## [0.3.0](https://github.com/tillknuesting/flagd/compare/flagd-proxy-v0.2.12...flagd-proxy/v0.3.0) (2023-10-24)


### ⚠ BREAKING CHANGES

* proposal - rename `kube-flagd-proxy` to `flagd-proxy` ([#576](https://github.com/tillknuesting/flagd/issues/576))

### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.5.1 ([#579](https://github.com/tillknuesting/flagd/issues/579)) ([58eed62](https://github.com/tillknuesting/flagd/commit/58eed62f5021e5c7a01a171067b725bf3ff83965))
* **deps:** update module github.com/open-feature/flagd/core to v0.5.2 ([#613](https://github.com/tillknuesting/flagd/issues/613)) ([218f435](https://github.com/tillknuesting/flagd/commit/218f435f0212fa24483b2af25e184e154e575eb1))
* **deps:** update module github.com/open-feature/flagd/core to v0.5.3 ([#634](https://github.com/tillknuesting/flagd/issues/634)) ([1bc7e99](https://github.com/tillknuesting/flagd/commit/1bc7e99473bc0c7bcacfb40030562e556d3895d6))
* **deps:** update module github.com/open-feature/flagd/core to v0.5.4 ([#693](https://github.com/tillknuesting/flagd/issues/693)) ([33705a6](https://github.com/tillknuesting/flagd/commit/33705a67300ec70760ba0baeb610f5a2e931205f))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.1 ([#745](https://github.com/tillknuesting/flagd/issues/745)) ([d290d8f](https://github.com/tillknuesting/flagd/commit/d290d8fda8aa84ed2db6454fdd26e60b028e3f7f))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.2 ([#779](https://github.com/tillknuesting/flagd/issues/779)) ([f34de59](https://github.com/tillknuesting/flagd/commit/f34de59fc8e636be043ce89758950d6ea3fe7376))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.3 ([#794](https://github.com/tillknuesting/flagd/issues/794)) ([9671964](https://github.com/tillknuesting/flagd/commit/96719649affeb1f8412e8b25f52d7292281d8230))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.4 ([#880](https://github.com/tillknuesting/flagd/issues/880)) ([ebb543d](https://github.com/tillknuesting/flagd/commit/ebb543d6eec18134e44ee7fe623fd2a336a1cf8d))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.5 ([#900](https://github.com/tillknuesting/flagd/issues/900)) ([c2ddcbf](https://github.com/tillknuesting/flagd/commit/c2ddcbfe49b8507fe463c11eb2b031bbc331792a))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.6 ([#916](https://github.com/tillknuesting/flagd/issues/916)) ([1f80e4d](https://github.com/tillknuesting/flagd/commit/1f80e4db9f8d1ba24884a71f2f8d552499ab5fe2))
* **deps:** update module github.com/open-feature/flagd/core to v0.6.7 ([#966](https://github.com/tillknuesting/flagd/issues/966)) ([c038a3a](https://github.com/tillknuesting/flagd/commit/c038a3a3700eee82afa3e2cb2484614ec6ed566c))
* **deps:** update module github.com/spf13/cobra to v1.7.0 ([#587](https://github.com/tillknuesting/flagd/issues/587)) ([12b3477](https://github.com/tillknuesting/flagd/commit/12b34773a68f6ae7e7e605aebc9f7075eb819994))
* **deps:** update module github.com/spf13/viper to v1.16.0 ([#679](https://github.com/tillknuesting/flagd/issues/679)) ([798a975](https://github.com/tillknuesting/flagd/commit/798a975bb1a47420e814b6dd439f1cece1a263e5))
* **deps:** update module github.com/spf13/viper to v1.17.0 ([#956](https://github.com/tillknuesting/flagd/issues/956)) ([31d015d](https://github.com/tillknuesting/flagd/commit/31d015d329ae9c1da3ec13878078371bcbf43fbf))
* **deps:** update module go.uber.org/zap to v1.25.0 ([#786](https://github.com/tillknuesting/flagd/issues/786)) ([40d0aa6](https://github.com/tillknuesting/flagd/commit/40d0aa66cf422db6811206d777b55396a96f330f))
* **deps:** update module go.uber.org/zap to v1.26.0 ([#917](https://github.com/tillknuesting/flagd/issues/917)) ([e57e206](https://github.com/tillknuesting/flagd/commit/e57e206c937d5b11b81d46ee57b3e92cc454dd88))
* **deps:** update opentelemetry-go monorepo ([#868](https://github.com/tillknuesting/flagd/issues/868)) ([d48317f](https://github.com/tillknuesting/flagd/commit/d48317f61d7db7ba0398dc9ab7cdd174a0b87555))


### ✨ New Features

* flagd OTEL collector ([#586](https://github.com/tillknuesting/flagd/issues/586)) ([494bec3](https://github.com/tillknuesting/flagd/commit/494bec33dcc1ddf0fa5cd0866f06265618408f5e))
* **flagd-proxy:** introduce zero-downtime ([#752](https://github.com/tillknuesting/flagd/issues/752)) ([ed5e6e5](https://github.com/tillknuesting/flagd/commit/ed5e6e5f3ee0a923c33dbf1a8bf20f80adec71bd))
* Introduce connect traces ([#624](https://github.com/tillknuesting/flagd/issues/624)) ([28bac6a](https://github.com/tillknuesting/flagd/commit/28bac6a54aed79cb8d84a147ffea296c36f5bd51))
* proposal - rename `kube-flagd-proxy` to `flagd-proxy` ([#576](https://github.com/tillknuesting/flagd/issues/576)) ([223de99](https://github.com/tillknuesting/flagd/commit/223de99ee3efbcd601bf75ab1f6258eeac0c426e))
* telemetry improvements ([#653](https://github.com/tillknuesting/flagd/issues/653)) ([ea02cba](https://github.com/tillknuesting/flagd/commit/ea02cba24bde982d55956fe54de1e8f27226bfc6))


### 🧹 Chore

* **deps:** update golang docker tag to v1.21 ([#822](https://github.com/tillknuesting/flagd/issues/822)) ([effe29d](https://github.com/tillknuesting/flagd/commit/effe29d50e33e6c06ef40d7f83f1b3f0df6bd1a2))
* release main ([#547](https://github.com/tillknuesting/flagd/issues/547)) ([529e3e9](https://github.com/tillknuesting/flagd/commit/529e3e913f2c02adfd4f1bf69455a7f6ba1f8368))
* release main ([#582](https://github.com/tillknuesting/flagd/issues/582)) ([f5ecc54](https://github.com/tillknuesting/flagd/commit/f5ecc5413753edab7c9f42e2a917ce10f81d63d2))
* release main ([#607](https://github.com/tillknuesting/flagd/issues/607)) ([0fbd30f](https://github.com/tillknuesting/flagd/commit/0fbd30f4b3ba25d3e8adf457d2708cd0990b68d8))
* release main ([#615](https://github.com/tillknuesting/flagd/issues/615)) ([ef5af58](https://github.com/tillknuesting/flagd/commit/ef5af58d1ee96bf866146e41b337f703fae62814))
* release main ([#643](https://github.com/tillknuesting/flagd/issues/643)) ([f3fbe6d](https://github.com/tillknuesting/flagd/commit/f3fbe6dc6f260caf0dd25737b0caeb46deaf3e0a))
* release main ([#694](https://github.com/tillknuesting/flagd/issues/694)) ([dbf7d2b](https://github.com/tillknuesting/flagd/commit/dbf7d2ba01cc7815f9646e25479b75875212666e))
* release main ([#750](https://github.com/tillknuesting/flagd/issues/750)) ([e3e03b0](https://github.com/tillknuesting/flagd/commit/e3e03b0af2ed3690aae8755facfe2bc8444c4f50))
* release main ([#774](https://github.com/tillknuesting/flagd/issues/774)) ([53028b5](https://github.com/tillknuesting/flagd/commit/53028b57f9d3045dd8e98dca5cb0d7c2813bb957))
* release main ([#780](https://github.com/tillknuesting/flagd/issues/780)) ([bf74c5a](https://github.com/tillknuesting/flagd/commit/bf74c5a3fc1b52108c2b057b3680576a90f31453))
* release main ([#796](https://github.com/tillknuesting/flagd/issues/796)) ([ee9116b](https://github.com/tillknuesting/flagd/commit/ee9116b34715cca0e6794dd01fe9c9eaea693529))
* release main ([#883](https://github.com/tillknuesting/flagd/issues/883)) ([43f15ea](https://github.com/tillknuesting/flagd/commit/43f15ea92339cb953b0dcfc6ee883cd0e1a4d9b3))
* release main ([#902](https://github.com/tillknuesting/flagd/issues/902)) ([90152ef](https://github.com/tillknuesting/flagd/commit/90152efa005b1e7881c496c71dd1b7adfa4eeb1a))
* release main ([#919](https://github.com/tillknuesting/flagd/issues/919)) ([3dd6929](https://github.com/tillknuesting/flagd/commit/3dd69297c4dcf87f4780432600903fd3f76916fb))
* update otel dependencies ([#649](https://github.com/tillknuesting/flagd/issues/649)) ([2114e41](https://github.com/tillknuesting/flagd/commit/2114e41c38951247866c0b408e5f933282902e70))
* upgrade to go 1.20 ([#891](https://github.com/tillknuesting/flagd/issues/891)) ([977167f](https://github.com/tillknuesting/flagd/commit/977167fb8db330b62726097616dcd691267199ad))


### 🔄 Refactoring

* **flagd-proxy:** update build.Dockerfile with buildkit caching ([#725](https://github.com/tillknuesting/flagd/issues/725)) ([06f3d2e](https://github.com/tillknuesting/flagd/commit/06f3d2eecbcff16bcf2fdfcab33b24c9e697e849))
* introduce additional linting rules + fix discrepancies ([#616](https://github.com/tillknuesting/flagd/issues/616)) ([aef0b90](https://github.com/tillknuesting/flagd/commit/aef0b9042dcbe5b3f9a7e97960b27366fe50adfe))
* introduce isyncstore interface ([#660](https://github.com/tillknuesting/flagd/issues/660)) ([c0e2fa0](https://github.com/tillknuesting/flagd/commit/c0e2fa00736d46db98f72114a449b2e2bf998e3d))
* remove protobuf dependency from eval package ([#701](https://github.com/tillknuesting/flagd/issues/701)) ([34ffafd](https://github.com/tillknuesting/flagd/commit/34ffafd9a777da3f11bd3bfa81565e774cc63214))

## [0.2.12](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.11...flagd-proxy/v0.2.12) (2023-10-12)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.6.6 ([#916](https://github.com/open-feature/flagd/issues/916)) ([1f80e4d](https://github.com/open-feature/flagd/commit/1f80e4db9f8d1ba24884a71f2f8d552499ab5fe2))
* **deps:** update module github.com/spf13/viper to v1.17.0 ([#956](https://github.com/open-feature/flagd/issues/956)) ([31d015d](https://github.com/open-feature/flagd/commit/31d015d329ae9c1da3ec13878078371bcbf43fbf))
* **deps:** update module go.uber.org/zap to v1.26.0 ([#917](https://github.com/open-feature/flagd/issues/917)) ([e57e206](https://github.com/open-feature/flagd/commit/e57e206c937d5b11b81d46ee57b3e92cc454dd88))

## [0.2.11](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.10...flagd-proxy/v0.2.11) (2023-09-14)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.6.5 ([#900](https://github.com/open-feature/flagd/issues/900)) ([c2ddcbf](https://github.com/open-feature/flagd/commit/c2ddcbfe49b8507fe463c11eb2b031bbc331792a))

## [0.2.10](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.9...flagd-proxy/v0.2.10) (2023-09-08)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.6.4 ([#880](https://github.com/open-feature/flagd/issues/880)) ([ebb543d](https://github.com/open-feature/flagd/commit/ebb543d6eec18134e44ee7fe623fd2a336a1cf8d))
* **deps:** update opentelemetry-go monorepo ([#868](https://github.com/open-feature/flagd/issues/868)) ([d48317f](https://github.com/open-feature/flagd/commit/d48317f61d7db7ba0398dc9ab7cdd174a0b87555))


### 🧹 Chore

* upgrade to go 1.20 ([#891](https://github.com/open-feature/flagd/issues/891)) ([977167f](https://github.com/open-feature/flagd/commit/977167fb8db330b62726097616dcd691267199ad))

## [0.2.9](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.8...flagd-proxy/v0.2.9) (2023-08-30)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.6.3 ([#794](https://github.com/open-feature/flagd/issues/794)) ([9671964](https://github.com/open-feature/flagd/commit/96719649affeb1f8412e8b25f52d7292281d8230))


### 🧹 Chore

* **deps:** update golang docker tag to v1.21 ([#822](https://github.com/open-feature/flagd/issues/822)) ([effe29d](https://github.com/open-feature/flagd/commit/effe29d50e33e6c06ef40d7f83f1b3f0df6bd1a2))

## [0.2.8](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.7...flagd-proxy/v0.2.8) (2023-08-04)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.6.2 ([#779](https://github.com/open-feature/flagd/issues/779)) ([f34de59](https://github.com/open-feature/flagd/commit/f34de59fc8e636be043ce89758950d6ea3fe7376))
* **deps:** update module go.uber.org/zap to v1.25.0 ([#786](https://github.com/open-feature/flagd/issues/786)) ([40d0aa6](https://github.com/open-feature/flagd/commit/40d0aa66cf422db6811206d777b55396a96f330f))

## [0.2.7](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.6...flagd-proxy/v0.2.7) (2023-07-28)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.6.1 ([#745](https://github.com/open-feature/flagd/issues/745)) ([d290d8f](https://github.com/open-feature/flagd/commit/d290d8fda8aa84ed2db6454fdd26e60b028e3f7f))

## [0.2.6](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.5...flagd-proxy/v0.2.6) (2023-07-27)


### ✨ New Features

* **flagd-proxy:** introduce zero-downtime ([#752](https://github.com/open-feature/flagd/issues/752)) ([ed5e6e5](https://github.com/open-feature/flagd/commit/ed5e6e5f3ee0a923c33dbf1a8bf20f80adec71bd))

## [0.2.5](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.4...flagd-proxy/v0.2.5) (2023-07-13)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.5.4 ([#693](https://github.com/open-feature/flagd/issues/693)) ([33705a6](https://github.com/open-feature/flagd/commit/33705a67300ec70760ba0baeb610f5a2e931205f))
* **deps:** update module github.com/spf13/viper to v1.16.0 ([#679](https://github.com/open-feature/flagd/issues/679)) ([798a975](https://github.com/open-feature/flagd/commit/798a975bb1a47420e814b6dd439f1cece1a263e5))


### 🔄 Refactoring

* **flagd-proxy:** update build.Dockerfile with buildkit caching ([#725](https://github.com/open-feature/flagd/issues/725)) ([06f3d2e](https://github.com/open-feature/flagd/commit/06f3d2eecbcff16bcf2fdfcab33b24c9e697e849))
* remove protobuf dependency from eval package ([#701](https://github.com/open-feature/flagd/issues/701)) ([34ffafd](https://github.com/open-feature/flagd/commit/34ffafd9a777da3f11bd3bfa81565e774cc63214))

## [0.2.4](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.3...flagd-proxy/v0.2.4) (2023-06-07)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.5.3 ([#634](https://github.com/open-feature/flagd/issues/634)) ([1bc7e99](https://github.com/open-feature/flagd/commit/1bc7e99473bc0c7bcacfb40030562e556d3895d6))


### 🧹 Chore

* update otel dependencies ([#649](https://github.com/open-feature/flagd/issues/649)) ([2114e41](https://github.com/open-feature/flagd/commit/2114e41c38951247866c0b408e5f933282902e70))


### ✨ New Features

* telemetry improvements ([#653](https://github.com/open-feature/flagd/issues/653)) ([ea02cba](https://github.com/open-feature/flagd/commit/ea02cba24bde982d55956fe54de1e8f27226bfc6))


### 🔄 Refactoring

* introduce additional linting rules + fix discrepancies ([#616](https://github.com/open-feature/flagd/issues/616)) ([aef0b90](https://github.com/open-feature/flagd/commit/aef0b9042dcbe5b3f9a7e97960b27366fe50adfe))
* introduce isyncstore interface ([#660](https://github.com/open-feature/flagd/issues/660)) ([c0e2fa0](https://github.com/open-feature/flagd/commit/c0e2fa00736d46db98f72114a449b2e2bf998e3d))

## [0.2.3](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.2...flagd-proxy/v0.2.3) (2023-05-04)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.5.2 ([#613](https://github.com/open-feature/flagd/issues/613)) ([218f435](https://github.com/open-feature/flagd/commit/218f435f0212fa24483b2af25e184e154e575eb1))
* **deps:** update module github.com/spf13/cobra to v1.7.0 ([#587](https://github.com/open-feature/flagd/issues/587)) ([12b3477](https://github.com/open-feature/flagd/commit/12b34773a68f6ae7e7e605aebc9f7075eb819994))


### ✨ New Features

* Introduce connect traces ([#624](https://github.com/open-feature/flagd/issues/624)) ([28bac6a](https://github.com/open-feature/flagd/commit/28bac6a54aed79cb8d84a147ffea296c36f5bd51))

## [0.2.2](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.1...flagd-proxy/v0.2.2) (2023-04-13)


### 🐛 Bug Fixes

* **deps:** update module github.com/open-feature/flagd/core to v0.5.1 ([#579](https://github.com/open-feature/flagd/issues/579)) ([58eed62](https://github.com/open-feature/flagd/commit/58eed62f5021e5c7a01a171067b725bf3ff83965))

## [0.2.1](https://github.com/open-feature/flagd/compare/flagd-proxy/v0.2.0...flagd-proxy/v0.2.1) (2023-04-12)


### ✨ New Features

* flagd OTEL collector ([#586](https://github.com/open-feature/flagd/issues/586)) ([494bec3](https://github.com/open-feature/flagd/commit/494bec33dcc1ddf0fa5cd0866f06265618408f5e))

## [0.2.0](https://github.com/open-feature/flagd/compare/flagd-proxy-v0.1.2...flagd-proxy/v0.2.0) (2023-03-30)


### ⚠ BREAKING CHANGES

* rename `kube-flagd-proxy` to `flagd-proxy` ([#576](https://github.com/open-feature/flagd/issues/576))

### ✨ New Features

* rename `kube-flagd-proxy` to `flagd-proxy` ([#576](https://github.com/open-feature/flagd/issues/576)) ([223de99](https://github.com/open-feature/flagd/commit/223de99ee3efbcd601bf75ab1f6258eeac0c426e))

## Changelog
