# Changelog

## 1.1.0 (2026-07-18)

Full Changelog: [v1.0.0...v1.1.0](https://github.com/Gizmo-OS/gizmo-sdk-python/compare/v1.0.0...v1.1.0)

### Features

* **api:** api update ([a47aa82](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/a47aa826f9be2f525d132d9e20aef505d79a91f4))
* **api:** api update ([d833096](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/d833096a32c152ec64c77336ae5d4b66108675bf))
* **api:** api update ([02bb8b9](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/02bb8b9f3a666d9953c0e43e6606c6fe2710a005))
* **api:** api update ([18d3680](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/18d36802f7c4876a44ec97843e8aafc16c0f11f8))
* **api:** api update ([03d4f26](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/03d4f26abf51330639b239477aea677f98a341df))
* **api:** manual updates ([de296e4](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/de296e4c40a2cef1274cbd89d3a5d0b47c711443))
* **stlc:** configurable CI runner and private-production-repo support in workflow templates ([6eb5a8f](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/6eb5a8f29bef2cd3bd801a79979ffa505aa75f2c))


### Bug Fixes

* **client:** close streams without requiring full consumption ([f88cc56](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/f88cc563053e2cbf07c85aef5c7fdf34a0983224))
* compat with Python 3.14 ([eab30d2](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/eab30d2066a8578c39788992b0f43c9df057c2f5))
* **compat:** update signatures of `model_dump` and `model_dump_json` for Pydantic v1 ([2046718](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/2046718dc38bf4462b2494074b2d6c7fd7ff3fd9))
* ensure streams are always closed ([22bd3dc](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/22bd3dc5495026bdf4d1494919e806f7a1450e84))
* **types:** allow pyright to infer TypedDict types within SequenceNotStr ([1c3fcbb](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/1c3fcbb318e060285e5159540faba3da73c7756d))
* use async_to_httpx_files in patch method ([71c46cd](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/71c46cd6d4ab7424ad31fa4f33c0fcf6dd7263f7))


### Chores

* add missing docstrings ([1088c3d](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/1088c3dc7204037e19dbec9998ef6358aa4d039e))
* add Python 3.14 classifier and testing ([2e9fc43](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/2e9fc436cc891239725023afcc79ed4089cca47f))
* **deps:** mypy 1.18.1 has a regression, pin to 1.17 ([60879fc](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/60879fc731b766b7dd42b1f9911f8fe3f74bff4d))
* **docs:** use environment variables for authentication in code snippets ([776e8fe](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/776e8fe0b62ff3c8dec10ae68e3aa55e8b727e79))
* **internal/tests:** avoid race condition with implicit client cleanup ([e7c9b31](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/e7c9b315ecb2817c0283d2781c8a1dd716fa076c))
* **internal:** add `--fix` argument to lint script ([3dbd805](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/3dbd805c431da44ccd3eb96f94763a86ee32eb66))
* **internal:** add missing files argument to base client ([58fda46](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/58fda46491ac76dccdcf5ee5602d0488624c62ac))
* **internal:** codegen related update ([b36e581](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/b36e581046627db7e1b3f56091ade68875bb6382))
* **internal:** codegen related update ([d8e93d9](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/d8e93d93be95286cdbf0462b5342ff443795835d))
* **internal:** codegen related update ([115809f](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/115809f6bfb13f697ef9917289aaac913af74280))
* **internal:** codegen related update ([c35be83](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/c35be83082847f55429de04ce9ed2295f9998a5f))
* **internal:** codegen related update ([c948018](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/c948018632995a12050d8f7afaad3259fb162d6f))
* **internal:** codegen related update ([57bf148](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/57bf1484784f09b570cd149d9b29b47f61a18801))
* **internal:** codegen related update ([4775c63](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/4775c639c0756a5074ac9b6c082ac5b6c01fc92c))
* **internal:** codegen related update ([9b15758](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/9b15758813256fce4e6ddb09860758b70304eb46))
* **internal:** codegen related update ([772cd39](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/772cd39b00c5d27465c45aa12e325d3cd7d1662f))
* **internal:** codegen related update ([022ec7b](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/022ec7bbbfd4bce1e0d611d23d73d1d1adfee209))
* **internal:** codegen related update ([8d4d339](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/8d4d33938d6e7fb83f3341e0ce0883518f586cc0))
* **internal:** codegen related update ([f392a84](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/f392a84b4e53742dd34acae5250c3de9b6188155))
* **internal:** grammar fix (it's -&gt; its) ([af5e63e](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/af5e63eacb885ad45c2528bd97297ae958741760))
* **package:** drop Python 3.8 support ([d1b481f](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/d1b481f3fc96d28c573bbae62de93eb43b744714))
* speedup initial import ([5db4c40](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/5db4c4094e6d8faed4cf295cea0fbcc80ab58dfe))
* update lockfile ([8b266ca](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/8b266caf0880d5ed9b2cf44c4f8cf3b105ff1eb7))

## 1.0.0 (2025-10-21)

Full Changelog: [v0.0.1...v1.0.0](https://github.com/Gizmo-OS/gizmo-sdk-python/compare/v0.0.1...v1.0.0)

### Chores

* configure new SDK language ([6e8362f](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/6e8362f1f61c561260ba1f499e810fa84cc93096))
* update SDK settings ([077a95b](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/077a95b7acdec0affdceb01963c0d29959a59bbc))
* update SDK settings ([881ccde](https://github.com/Gizmo-OS/gizmo-sdk-python/commit/881ccdea631a6326d7f703fd16a1779ee16c0b1d))
