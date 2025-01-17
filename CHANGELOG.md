# Changelog

## [2.18.1](https://github.com/RoinujNosde/SimpleClans/compare/v2.18.0...v2.18.1) (2022-11-29)


### Bug Fixes

* added check for clan_member on land commands ([fc81e76](https://github.com/RoinujNosde/SimpleClans/commit/fc81e765211bebe22a7a6aa5d5158754580bbdc5))
* attempt at fixing NPE on getAllClanPlayers ([26ba9f7](https://github.com/RoinujNosde/SimpleClans/commit/26ba9f73296a772eaa698d2ede6fbc3831da850c))
* **bungee:** error deserializing clan banners ([56c7908](https://github.com/RoinujNosde/SimpleClans/commit/56c7908c332167cec9cca6a4ea054977d0d68b9f))
* channel auto creation setting not respected on join/link ([7f9d133](https://github.com/RoinujNosde/SimpleClans/commit/7f9d133051b9011837d0a5114abc6c3637a3f02c))
* default ranks were getting re-added on config load ([7a37382](https://github.com/RoinujNosde/SimpleClans/commit/7a37382264ff4dd5456f6930045b5102bf491897))
* missing getHandlerList on HomeRegroupEvent ([#338](https://github.com/RoinujNosde/SimpleClans/issues/338)) ([8fa465d](https://github.com/RoinujNosde/SimpleClans/commit/8fa465da385f36b1fb075031c375ef94df78ea52))
* money was not given back when channel creation failed ([#336](https://github.com/RoinujNosde/SimpleClans/issues/336)) ([d8cb61b](https://github.com/RoinujNosde/SimpleClans/commit/d8cb61b0fc9584bb58f421faf98596816621053f))
* wrong path of discord economy section ([#334](https://github.com/RoinujNosde/SimpleClans/issues/334)) ([3f1b06d](https://github.com/RoinujNosde/SimpleClans/commit/3f1b06dcf996e51a878b7fc281069e236ebcbfce))

## [2.18.0](https://github.com/RoinujNosde/SimpleClans/compare/v2.17.0...v2.18.0) (2022-10-14)


### Features

* add help-size config ([25197cd](https://github.com/RoinujNosde/SimpleClans/commit/25197cdd729cea63d7e223dc1e0aaef830613327))
* added method for registering protection providers ([2ea7444](https://github.com/RoinujNosde/SimpleClans/commit/2ea744443f502970b15859818e9d5e45ca69d453))
* adds permission to bypass the teleport delay ([d56a0a9](https://github.com/RoinujNosde/SimpleClans/commit/d56a0a979a47a140115742518e934a2469e6f880))
* adds PlayerHomeClearEvent ([becb88b](https://github.com/RoinujNosde/SimpleClans/commit/becb88b763380bed5a2e1dd209c32c8363a7f88b))
* adds starter-ranks ([a440834](https://github.com/RoinujNosde/SimpleClans/commit/a4408343479d7efa6ae5a65894f8b822ecd47ebb))
* Improves Bungee support ([#327](https://github.com/RoinujNosde/SimpleClans/issues/327)) ([2c9b0f9](https://github.com/RoinujNosde/SimpleClans/commit/2c9b0f98fe3942ea74190c1a81d61be2c8647db8))
* **lang:** new crowdin updates ([#319](https://github.com/RoinujNosde/SimpleClans/issues/319)) ([87ece22](https://github.com/RoinujNosde/SimpleClans/commit/87ece22036fb674c8c362b6a1b86fe884543e6ad))


### Bug Fixes

* changes size of some frames for better visualization on Bedrock ([1adec0b](https://github.com/RoinujNosde/SimpleClans/commit/1adec0b89d676767cdb94dcdf91ba37a231eb4a8))
* ConfigurationSerializableAdapter NPE ([30a501c](https://github.com/RoinujNosde/SimpleClans/commit/30a501c063aa9dbcf596df83adc2b15baf0e4bb9))
* getPastClans() preserves the insertion order ([af07988](https://github.com/RoinujNosde/SimpleClans/commit/af079881030bd299b9bae1ebf0cc62353af7e6fc))
* NoClassDefFoundError in WorldGuard6Provider ([a859928](https://github.com/RoinujNosde/SimpleClans/commit/a8599286225ba603ea124b8b52510245b94ffd24))
* NPE while collecting fees ([c47289c](https://github.com/RoinujNosde/SimpleClans/commit/c47289c5bf8113a9d6a8e1ee74a5afb0358647b6))
* NPE while purging data ([f14c425](https://github.com/RoinujNosde/SimpleClans/commit/f14c42548846feef01b484acbb5f02bcbcabd8db))
* NPE while sending a message to spies ([#322](https://github.com/RoinujNosde/SimpleClans/issues/322)) ([e7f756f](https://github.com/RoinujNosde/SimpleClans/commit/e7f756f3063c646e21415e08eea73f123d2818a0))
* removes duplicate /clan from help ([f7e7ec6](https://github.com/RoinujNosde/SimpleClans/commit/f7e7ec66243359e26d3c456a9740a53753951c48))
* removes rank and join date on disband ([2a1ad5b](https://github.com/RoinujNosde/SimpleClans/commit/2a1ad5b5c8d2937a8ee6dd6f7f43d85c86f08307))
* set useSSL to false ([f484bc1](https://github.com/RoinujNosde/SimpleClans/commit/f484bc16c6176ccd13e05aae2169400e7bcf5d62))
* supports '.' and '*' as username prefix by default ([37f0ecf](https://github.com/RoinujNosde/SimpleClans/commit/37f0ecff506d06f3047e3598848117a14c2b7ead))
* updates join date when joining a clan ([#326](https://github.com/RoinujNosde/SimpleClans/issues/326)) ([96a13d8](https://github.com/RoinujNosde/SimpleClans/commit/96a13d8d6cc18c91d4dee20dd632cd5d65db5213))


### Performance Improvements

* improved UUID lookup performance ([4ab53d1](https://github.com/RoinujNosde/SimpleClans/commit/4ab53d16135ecf5a4067b1a63d058da392dc5313))
