# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [1.0.2](https://github.com/ecomclub/storage-api/compare/v1.0.1...v1.0.2) (2020-02-20)

### [1.0.1](https://github.com/ecomclub/storage-api/compare/v1.0.0...v1.0.1) (2020-02-20)


### Bug Fixes

* **kraken:** receive callback url as param, set 'callback_url' or 'wait' ([8fecfab](https://github.com/ecomclub/storage-api/commit/8fecfab748c2000609adc659cdd4730cf315d375))
* **web:** pass calback url to kraken handler ([c91b524](https://github.com/ecomclub/storage-api/commit/c91b52414c32be04d49fb6baa874292555487d99))

## 1.0.0 (2020-02-20)


### Features

* **kraken:** add webp compression ([d0011c3](https://github.com/ecomclub/storage-api/commit/d0011c32fc7e1533d7f8643a334c0a6f431e493e))
* **upload:** add cache control and handle convertion to webp ([7ef5a85](https://github.com/ecomclub/storage-api/commit/7ef5a8543edfbc0acb8a39ddaf72434ac236cf96))
* **upload:** optimze/save save fallback img (not webp) with middle size ([6181b2c](https://github.com/ecomclub/storage-api/commit/6181b2c798f90b622171aa21cc680cad04350f2a))
* supporting gif and bmp image types ([a9881de](https://github.com/ecomclub/storage-api/commit/a9881de79a30869c0401d332bdc5a7896854040d))


### Bug Fixes

* **img-optimization:** use always original image as base ([7952bb1](https://github.com/ecomclub/storage-api/commit/7952bb113b93a976c84515eb3062b940b9f03d3c))
* **kraken:** debug optim options, set request timeout ([ad01e99](https://github.com/ecomclub/storage-api/commit/ad01e99b7eeb42b2918cbc180e06a22abcc5ce38))
* **kraken:** fix handling request timeout and get image fallback ([3d05459](https://github.com/ecomclub/storage-api/commit/3d05459a76c697ddd59931eb59d51a835703de05))
* **kraken:** fix to handle webp compression ([718a77a](https://github.com/ecomclub/storage-api/commit/718a77a5c19821c82c8673bea11ff5b9ba41ce2a))
* **kraken:** force timeout with 20s ([7192e10](https://github.com/ecomclub/storage-api/commit/7192e1086856b02aa767c06820d5b4934643c851))
* **kraken:** handle webp compression only if not webp yet ([b5fc7d8](https://github.com/ecomclub/storage-api/commit/b5fc7d85e2257a2a2ec88c19ad17227b166a35c3))
* **kraken:** hardset webp/lossy options ([e699a3f](https://github.com/ecomclub/storage-api/commit/e699a3fd779822710ff9ae6c6bb8bb1807dee72f))
* **kraken:** must set opts object inside parse function ([fb884da](https://github.com/ecomclub/storage-api/commit/fb884daba9de1c682a9c1438fe3e453782fd8b16))
* **s3-put:** fix CacheControl param ([5d420aa](https://github.com/ecomclub/storage-api/commit/5d420aa0318e868d86908c186ecdba565c0b4acf))
* **upload:** back with .webp extension, use different size for fl img ([3cb4da4](https://github.com/ecomclub/storage-api/commit/3cb4da4b32ab74e40b2dc98f1f87d3c9ffb34c0f))
* **upload:** check data on callback function before handling put ([163d421](https://github.com/ecomclub/storage-api/commit/163d42134950817411b713af979659f7578831eb))
* **upload:** check isSavingFallback boolean to prevent duplicated response ([618ebac](https://github.com/ecomclub/storage-api/commit/618ebacf6864665150f5a92b4aba5f694efeb9d5))
* **upload:** delay to save webp fallback with middle size ([7dbf631](https://github.com/ecomclub/storage-api/commit/7dbf6318d08237a135ea4dcbb0aaf524f154a786))
* **upload:** edit new key (with label), fix handling picture objects ([b33d4d7](https://github.com/ecomclub/storage-api/commit/b33d4d77e621c10e637e360187d2aac52046517a))
* **upload:** fix key with .webp on first upload ([de925ef](https://github.com/ecomclub/storage-api/commit/de925ef72d5a536eccb29c0b02cc72a5a3e24958))
* **upload:** fix looping widths and web, count before checking length ([11431c6](https://github.com/ecomclub/storage-api/commit/11431c68aff0ea8cccf863b6251d2f7b1a365f78))
* **upload:** fix looping widths and webp variations ([8ec7989](https://github.com/ecomclub/storage-api/commit/8ec798919b77f7ea345b0bd7a6f162794ebe8905))
* **upload:** fix looping widths and webp variations ([ee78649](https://github.com/ecomclub/storage-api/commit/ee786498966c392a84a12aeb2cf6e6f8376d47e6))
* **upload:** fix picture labels from optims array ([035f06f](https://github.com/ecomclub/storage-api/commit/035f06f2e3f5a0bca31c87c7be57dec3d645527e))
* **upload:** fixes to handle last parse to flk image ([9a91b79](https://github.com/ecomclub/storage-api/commit/9a91b799df7ac2392bf3039a674efead1696822a))
* **upload:** keep original content type when saving webp fallback ([144f0da](https://github.com/ecomclub/storage-api/commit/144f0da9e0a34edfe41083757e687153762df4a8))
* **upload:** mark new upladed keys with 'v2-' prefix ([4b004b9](https://github.com/ecomclub/storage-api/commit/4b004b974f260b95a74515887405aefff130a757))
* **upload:** prefix for webp fallback image ([f7e2688](https://github.com/ecomclub/storage-api/commit/f7e2688f854a3e67f69e3030c43587b815a105c2))
* **upload:** reset isWebp to save fallback images ([865d2ac](https://github.com/ecomclub/storage-api/commit/865d2acea1c77deb99cc2643f8b1c977cbae114d))
* **upload:** stop hardsetting webp extension on s3 keys ([5099aac](https://github.com/ecomclub/storage-api/commit/5099aacde0010cf9c9b64cf0f04f9ffd61f37c7f))
* **upload:** using promise then instead of finally (no polyfill) ([b02f6eb](https://github.com/ecomclub/storage-api/commit/b02f6eb2ea8f83dfc3dd42e12e1a7bc237eb2402))
* **web:** update aws and kraken setup and upload function with new lib ([62a10fa](https://github.com/ecomclub/storage-api/commit/62a10fa95ad96fe4ba71be2cbe957702a4601898))
* error when kraken fails sending the s3 uri ([211aae3](https://github.com/ecomclub/storage-api/commit/211aae3d03179cd2c36e4a9852c3c1df9069c0dd))
* respond with error when kraken fails ([3b3b3ba](https://github.com/ecomclub/storage-api/commit/3b3b3ba8259742b6eb56ba6918e38c6f956c20a6))
* stop logging all kraken errors directly ([312b149](https://github.com/ecomclub/storage-api/commit/312b1496adb4ddcb0194f965ef2dc9a9381dcfa1))