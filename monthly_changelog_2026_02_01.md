# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-02-01)

<section class="features">

### Features

-   [`7b69002`](https://github.com/stdlib-js/stdlib/commit/7b69002e03bd424815f80e156e0994f150e80175) - ensure support for non-string dtypes and update tests to use functional accessors
-   [`75a4928`](https://github.com/stdlib-js/stdlib/commit/75a4928752ee93a88cbdf3114c12cd4ba2979c07) - update `stats` TypeScript declarations [(#10002)](https://github.com/stdlib-js/stdlib/pull/10002)
-   [`cef8ee6`](https://github.com/stdlib-js/stdlib/commit/cef8ee6f3805b44b0784449befe4399584dd3b47) - update `stats/base/ndarray` TypeScript declarations [(#10001)](https://github.com/stdlib-js/stdlib/pull/10001)
-   [`d660cab`](https://github.com/stdlib-js/stdlib/commit/d660cabc2799c7f43cda85b7a4ff65e0995a9a1e) - add C implementation for `stats/base/ndarray/smin` [(#9981)](https://github.com/stdlib-js/stdlib/pull/9981)
-   [`041e713`](https://github.com/stdlib-js/stdlib/commit/041e7138e20a8149b85835d9067c4065ce856893) - add C implementation for `stats/base/ndarray/smax` [(#9956)](https://github.com/stdlib-js/stdlib/pull/9956)
-   [`bbaef7b`](https://github.com/stdlib-js/stdlib/commit/bbaef7b113570a432bd33e31d03f18f070f3814b) - add C implementation for `stats/base/ndarray/dmin` [(#9939)](https://github.com/stdlib-js/stdlib/pull/9939)
-   [`fae4985`](https://github.com/stdlib-js/stdlib/commit/fae498583ef5643ae4826247852d855629e93d6a) - add `dstdevtk` and `dstdevyc` to namespace
-   [`af66e3c`](https://github.com/stdlib-js/stdlib/commit/af66e3c56f7a54ffbd16308bf506657f1f4948d0) - add `sstdevyc` to namespace
-   [`b1a3172`](https://github.com/stdlib-js/stdlib/commit/b1a31727a8fc6ba8cb2b07891e89c4c267a8242d) - add `sstdevtk` to namespace
-   [`58c2966`](https://github.com/stdlib-js/stdlib/commit/58c296693a0d4b9674368b5bbf71fb0dc4389007) - add `stats/base/ndarray/sstdevtk` [(#9917)](https://github.com/stdlib-js/stdlib/pull/9917)
-   [`df6733b`](https://github.com/stdlib-js/stdlib/commit/df6733b7cba6fd7122f3bd01811b609b84b97ca8) - add `nanrange`, `nanrangeBy`, `rangeBy` to namespace
-   [`4b9ded3`](https://github.com/stdlib-js/stdlib/commit/4b9ded3ba52a495d3cb976df6df8969eea3c8fe4) - add `nanmidrangeBy`, `nanminBy`, `nanminabs` to namespace
-   [`21a310e`](https://github.com/stdlib-js/stdlib/commit/21a310e5967dc01d80ac4505efbf66bc896f01dd) - add `nanmeanors`, `nanmeanpn`, `nanmeanwd` to namespace
-   [`18e825e`](https://github.com/stdlib-js/stdlib/commit/18e825eb623226175d0eca6141c98a37dd3dc3ea) - add `minsorted`, `nanmaxBy`, `nanmaxabs` to namespace
-   [`01f982c`](https://github.com/stdlib-js/stdlib/commit/01f982c89b9078a67483965e574f26edeeb25c73) - add `mediansorted`, `midrange`, `midrangeBy` to namespace
-   [`1ae0613`](https://github.com/stdlib-js/stdlib/commit/1ae0613632ccd365a9888087978398fe3af8faea) - add `meankbn2`, `meanors`, `meanpn`, `meanpw`, `meanwd` to namespace
-   [`c649696`](https://github.com/stdlib-js/stdlib/commit/c6496960fbe675dfb2d90e57312407bc1d14cd64) - add `maxsorted` and `meankbn` to namespace
-   [`6e7b3a8`](https://github.com/stdlib-js/stdlib/commit/6e7b3a875e396ef3d5f00953a7b241f34286b4a1) - add `rangeabs` to namespace
-   [`ff26c6d`](https://github.com/stdlib-js/stdlib/commit/ff26c6dd3ee1f76fa6c8deac6f1ae2ee5226baaa) - add `stats/rangeabs` [(#9972)](https://github.com/stdlib-js/stdlib/pull/9972)
-   [`67315ee`](https://github.com/stdlib-js/stdlib/commit/67315ee65982c6354194c8baa3f22c6709bf25d3) - add `stats/base/ndarray/dstdevyc` [(#9927)](https://github.com/stdlib-js/stdlib/pull/9927)
-   [`ead840b`](https://github.com/stdlib-js/stdlib/commit/ead840b4a3cbadea51b04eb2614e379b411bd7ca) - add `stats/base/ndarray/sstdevyc` [(#9922)](https://github.com/stdlib-js/stdlib/pull/9922)
-   [`f4f48b1`](https://github.com/stdlib-js/stdlib/commit/f4f48b130f926c2adff515c2a90ec99cbc308815) - add `stats/base/ndarray/dstdevtk` [(#9926)](https://github.com/stdlib-js/stdlib/pull/9926)
-   [`71f4422`](https://github.com/stdlib-js/stdlib/commit/71f442266b75b400c0087df6820a5f5ac8ba1a1f) - update `stats/strided` TypeScript declarations [(#9985)](https://github.com/stdlib-js/stdlib/pull/9985)
-   [`18a1271`](https://github.com/stdlib-js/stdlib/commit/18a1271042bb0163ba7f0b6a74433852a8eb882a) - update `stats/base/ndarray` TypeScript declarations [(#9984)](https://github.com/stdlib-js/stdlib/pull/9984)
-   [`ae0d247`](https://github.com/stdlib-js/stdlib/commit/ae0d247cceb75d109353ae90eec5c9489e786408) - add `stats/strided/mskminabs` [(#9722)](https://github.com/stdlib-js/stdlib/pull/9722)
-   [`6a778f7`](https://github.com/stdlib-js/stdlib/commit/6a778f7dffb0d8225bf2f5f8849b6677aa19434c) - add `smskmaxabs` to namespace
-   [`00e8094`](https://github.com/stdlib-js/stdlib/commit/00e80949192deafa3d801d12df8933c613fcb52c) - add `mskmaxabs` to namespace
-   [`991e692`](https://github.com/stdlib-js/stdlib/commit/991e6926616d85d4732140b22a85bb87cdb5720c) - add `dmskmaxabs` to namespace
-   [`ac01c27`](https://github.com/stdlib-js/stdlib/commit/ac01c274acc740fbf7ebad5b404d7ff2449b1b1d) - add `stats/base/ndarray/mskmaxabs` [(#9957)](https://github.com/stdlib-js/stdlib/pull/9957)
-   [`8ae9939`](https://github.com/stdlib-js/stdlib/commit/8ae993948492720e8b646c99bd17032be9bfea6c) - add `stats/strided/dmskmaxabs` [(#9743)](https://github.com/stdlib-js/stdlib/pull/9743)
-   [`b1c1ac0`](https://github.com/stdlib-js/stdlib/commit/b1c1ac0ca0ae8488c5cec52a8f109d29cddecff6) - add `stats/base/ndarray/smskmaxabs` [(#9961)](https://github.com/stdlib-js/stdlib/pull/9961)
-   [`a65d18d`](https://github.com/stdlib-js/stdlib/commit/a65d18d175d72246b54daca7ff8b59ccf7956f64) - update `stats/base/ndarray` TypeScript declarations [(#9966)](https://github.com/stdlib-js/stdlib/pull/9966)
-   [`6a6d716`](https://github.com/stdlib-js/stdlib/commit/6a6d7163446fadaa9ffa3ca5ec01a44c77fe3c0c) - add `drangeabs` to namespace
-   [`88808cc`](https://github.com/stdlib-js/stdlib/commit/88808ccb3992c3565daed22fc1d1cd6321f33802) - add `stats/base/ndarray/drangeabs` [(#9919)](https://github.com/stdlib-js/stdlib/pull/9919)
-   [`d9d3ea6`](https://github.com/stdlib-js/stdlib/commit/d9d3ea6f22ba8eb35a75bea6c4ed21a72b7f3618) - add `rangeabs` to namespace
-   [`0b8361f`](https://github.com/stdlib-js/stdlib/commit/0b8361f354a73d91b1ca235e74bf0fab1bd1d7ae) - add `stats/base/ndarray/rangeabs` [(#9918)](https://github.com/stdlib-js/stdlib/pull/9918)
-   [`2b5c80e`](https://github.com/stdlib-js/stdlib/commit/2b5c80e62c9d6d2583a009fdf496a4a5e1827d64) - add `srangeabs` to namespace
-   [`c66543d`](https://github.com/stdlib-js/stdlib/commit/c66543d7be8062e7a3efcc3e332e5e270986d59c) - add `stats/base/ndarray/srangeabs` [(#9920)](https://github.com/stdlib-js/stdlib/pull/9920)
-   [`aa9da1e`](https://github.com/stdlib-js/stdlib/commit/aa9da1e984009479baafb731970c49c0e2b0d423) - update `ndarray/base` TypeScript declarations [(#9935)](https://github.com/stdlib-js/stdlib/pull/9935)
-   [`aa4cdfd`](https://github.com/stdlib-js/stdlib/commit/aa4cdfd5a67ada2e018c7970c4a777187280cce2) - update `stats/strided/distances` TypeScript declarations [(#9936)](https://github.com/stdlib-js/stdlib/pull/9936)
-   [`2dc14e3`](https://github.com/stdlib-js/stdlib/commit/2dc14e39bc443c009059c88c1650e4ca227b708a) - update `stats/strided` TypeScript declarations [(#9937)](https://github.com/stdlib-js/stdlib/pull/9937)
-   [`07e112a`](https://github.com/stdlib-js/stdlib/commit/07e112a03fc1c0308bdc38bcb0425dc2fe6faec5) - add C API
-   [`3d21748`](https://github.com/stdlib-js/stdlib/commit/3d2174821f71a70dbb3052da07e0a3b3f6dfbaa0) - add function to return the index offset in units of elements
-   [`dd45a8f`](https://github.com/stdlib-js/stdlib/commit/dd45a8fcec70ba4716ec67606a448721a723f54b) - add function to return a dimension stride in units of elements
-   [`b00ba84`](https://github.com/stdlib-js/stdlib/commit/b00ba84689ed039d0896209f94716c187cd6cccb) - add function for returning the number of bytes per ndarray element
-   [`1e5789c`](https://github.com/stdlib-js/stdlib/commit/1e5789c70b7400b0ff1cd71d06798c1e5b26f16b) - add `blockSize` to namespace
-   [`a6117b1`](https://github.com/stdlib-js/stdlib/commit/a6117b1bd697083439d740567d41cbfa754f68ab) - add `quinaryBlockSize` to namespace
-   [`c6dca39`](https://github.com/stdlib-js/stdlib/commit/c6dca39c634f8c016dc6fa4d0330a47bba977eaf) - add `quaternaryBlockSize` to namespace
-   [`2d51ff6`](https://github.com/stdlib-js/stdlib/commit/2d51ff6a1af79d361401ff928fb755bfaa1170f7) - add `ndarray/base/tiling-block-size`
-   [`9c75b30`](https://github.com/stdlib-js/stdlib/commit/9c75b302a82df9b6c580b9f8afc647773e5684a3) - add `ndarray/base/quinary-tiling-block-size` [(#9871)](https://github.com/stdlib-js/stdlib/pull/9871)
-   [`d84de96`](https://github.com/stdlib-js/stdlib/commit/d84de9698683c20fa3b67eb9d2a615a403f6b707) - add `ndarray/base/quaternary-tiling-block-size` [(#9838)](https://github.com/stdlib-js/stdlib/pull/9838)
-   [`942fa9b`](https://github.com/stdlib-js/stdlib/commit/942fa9ba4e93c3064011ead7bae1d1f8ac0281de) - add `distances` to namespace
-   [`262f96d`](https://github.com/stdlib-js/stdlib/commit/262f96df7fe35057b1ad9a29802497f935788600) - update namespace
-   [`d0e3e71`](https://github.com/stdlib-js/stdlib/commit/d0e3e71f26da59d042df4ae94869589ee17f237a) - add `stats/strided/distances` namespace
-   [`0538a41`](https://github.com/stdlib-js/stdlib/commit/0538a41cc4147040c041d86068fce07ecfdca36d) - add `stats/strided/distances/dsquared-euclidean` [(#9680)](https://github.com/stdlib-js/stdlib/pull/9680)
-   [`fbc0835`](https://github.com/stdlib-js/stdlib/commit/fbc08352233e90ae7ff159385d4d3926dff1e13c) - add `snanmidrange` and `srangeabs` to namespace
-   [`52100d1`](https://github.com/stdlib-js/stdlib/commit/52100d116b87170e3a325bd87665b0ad223894e2) - add `smskmaxabs` and `smskmidrange` to namespace
-   [`bde889e`](https://github.com/stdlib-js/stdlib/commit/bde889e82b8692575b6a0a1876b28ba9130abf11) - add `rangeabs` to namespace
-   [`0e31507`](https://github.com/stdlib-js/stdlib/commit/0e31507fc2049fb7c9ab2e7a4f1ae95a97cee2ae) - add `nanmskmidrange` to namespace
-   [`c13da4c`](https://github.com/stdlib-js/stdlib/commit/c13da4c90cf6fc5fe8f95a092c16a3158e8dc957) - add `nanmidrange` and `nanmidrangeBy` to namespace
-   [`4d7e3d2`](https://github.com/stdlib-js/stdlib/commit/4d7e3d2d2a82112e93d9289c81a35f44d2e2e312) - add `mskmaxabs` and `mskmidrange` to namespace
-   [`c86ff1c`](https://github.com/stdlib-js/stdlib/commit/c86ff1cf8c853f3a549b92ee9231e6ce1571dfe7) - add `midrange` and `midrangeBy` to namespace
-   [`3f0d5ee`](https://github.com/stdlib-js/stdlib/commit/3f0d5ee64202dcd04ad9d5bf0aa4a2d22de82351) - add `drangeabs` to namespace
-   [`8c75c0d`](https://github.com/stdlib-js/stdlib/commit/8c75c0da4f1d5710fde341b06672faf7e18e221b) - add `dmskmidrange`, `dnanmidrange`, `dnanmskmidrange` to namespace
-   [`1fa6b54`](https://github.com/stdlib-js/stdlib/commit/1fa6b54311953d38b35d08bee5967e8496a5261d) - add `snanmskmidrange` to namespace
-   [`562065d`](https://github.com/stdlib-js/stdlib/commit/562065d7fcb441b25a487453c4321030478ee966) - add `stats/strided/snanmskmidrange` [(#9821)](https://github.com/stdlib-js/stdlib/pull/9821)
-   [`8f8998f`](https://github.com/stdlib-js/stdlib/commit/8f8998f02831c2db69698a26769916d68acfe54f) - update `ndarray/base` TypeScript declarations [(#9913)](https://github.com/stdlib-js/stdlib/pull/9913)
-   [`e3e238d`](https://github.com/stdlib-js/stdlib/commit/e3e238dd684b98b67ad10ae4da51f33f1cf5413d) - update `stats/base/ndarray` TypeScript declarations [(#9914)](https://github.com/stdlib-js/stdlib/pull/9914)
-   [`fabac99`](https://github.com/stdlib-js/stdlib/commit/fabac994a5faee54c764fc1744f9a3427a6cf7b3) - add `variance`, `variancech`, `variancewd` to namespace
-   [`b165d09`](https://github.com/stdlib-js/stdlib/commit/b165d09ba924d67d5ee7ed2f307a2a394708c830) - add `stdev`, `stdevch`, `stdevpn`, `stdevtk`, `stdevwd`, `stdevyc` to namespace
-   [`f68ce9c`](https://github.com/stdlib-js/stdlib/commit/f68ce9c54ec885f22090a8397346c865242aed80) - add `sstdev`, `sstdevch`, `sstdevpn`, `sstdevwd` to namespace
-   [`7139c25`](https://github.com/stdlib-js/stdlib/commit/7139c25a29aa627c32bd5995aee81e89511931b8) - add `snanrange` to namespace
-   [`94ff22d`](https://github.com/stdlib-js/stdlib/commit/94ff22dca4d701f12d6bb6abdcab72adb28715c0) - add `snanmskmax`, `snanmskmin`, `snanmskrange` to namespace
-   [`b38d7db`](https://github.com/stdlib-js/stdlib/commit/b38d7db968c63307010eb6ab7d9911cd22395497) - add `snanmidrange` to namespace
-   [`a3c5163`](https://github.com/stdlib-js/stdlib/commit/a3c516334b198d5e75651fe6ccab356fb859a0b0) - add `smskmax`, `smskmidrange`, `smskmin`, `smskrange` to namespace
-   [`e76145c`](https://github.com/stdlib-js/stdlib/commit/e76145c08e0d14d58ebd4000b4be3e5aa2b847cd) - add `smeanors`, `smediansorted`, `smidrange` to namespace
-   [`1ef47af`](https://github.com/stdlib-js/stdlib/commit/1ef47afe2c2d359bdcbdd581377e55a3ae32bf98) - add `sdsmean`, `sdsmeanors`, `sdsnanmeanors` to namespace
-   [`ce723a4`](https://github.com/stdlib-js/stdlib/commit/ce723a44bfba8592c4add60f31021768b7497798) - add `nanrange` and `nanrangeBy` to namespace
-   [`87ee49b`](https://github.com/stdlib-js/stdlib/commit/87ee49bd98f76bfe8f7819206cc941de1d1b09eb) - add `nanmskmax`, `nanmskmin`, `nanmskrange` to namespace
-   [`a4d6dcf`](https://github.com/stdlib-js/stdlib/commit/a4d6dcfe836dbab948b11ef1e86e0b9fcb52f58e) - add `nanmeanors`, `nanmidrange`, `nanmidrangeBy`, `nanminBy` to namespace
-   [`5feabb7`](https://github.com/stdlib-js/stdlib/commit/5feabb757b0306583c947e77cb327316cc340080) - add `mskmidrange` to namespace
-   [`a6c1cde`](https://github.com/stdlib-js/stdlib/commit/a6c1cde8db2eb893de6912f2942b715837c28cb9) - add `nanmaxBy` to namespace
-   [`f916336`](https://github.com/stdlib-js/stdlib/commit/f916336ffb65ee1718c971dc97ac4cdc4beda3b3) - add `midrange` and `midrangeBy` to namespace
-   [`d99d331`](https://github.com/stdlib-js/stdlib/commit/d99d331a62b1521342ac812793a7080e449d192d) - add `dstdev`, `dstdevch`, `dstdevpn`, and `dstdevwd` to namespace
-   [`52f25b4`](https://github.com/stdlib-js/stdlib/commit/52f25b4a749bfafacdbeb46884c1c314b3a25f73) - add `dnanrange` to namespace
-   [`6a81c76`](https://github.com/stdlib-js/stdlib/commit/6a81c76e896d7fe3794f9857ed8b157fccc7493b) - add `dnanmskmax`, `dnanmskmin`, and `dnanmskrange` to namespace
-   [`43ad0bc`](https://github.com/stdlib-js/stdlib/commit/43ad0bc483f79583c41354c4e494e28022c6e83d) - add `dnanmidrange` to namespace
-   [`b90d38d`](https://github.com/stdlib-js/stdlib/commit/b90d38d7eb7f24e6370c07ecabe0c6bf6d3b2b80) - add `dmskmax`, `dmskmin`, and `dmskrange` to namespace
-   [`914b803`](https://github.com/stdlib-js/stdlib/commit/914b80399759dcf6911f9a92a4ff6845527d8bb8) - add `dmediansorted` and `dmidrange` to namespace
-   [`4a91724`](https://github.com/stdlib-js/stdlib/commit/4a91724da0e502a7f861b71a80796b5c980ac042) - add `dmeanstdev` to namespace
-   [`3c8018f`](https://github.com/stdlib-js/stdlib/commit/3c8018f6095b3553a0004d9eb164e4daecc22b9e) - add `dmeanors` to namespace
-   [`7f787ff`](https://github.com/stdlib-js/stdlib/commit/7f787ffc41f715cdca8a37fe39d46da733c53e32) - add `dmeanwd` to namespace
-   [`b6d8bcc`](https://github.com/stdlib-js/stdlib/commit/b6d8bcc8e3a285d4f874748191904580321aa0e8) - add `quinaryLoopOrder` to namespace
-   [`f3a6bc0`](https://github.com/stdlib-js/stdlib/commit/f3a6bc070f6ac5e2dee1374534ba6b0c134e4db6) - add `quaternaryLoopOrder` to namespace
-   [`02b9b76`](https://github.com/stdlib-js/stdlib/commit/02b9b7662449c9a04917e1353a8b53ff85df45d4) - add `broadcastScalarLike` to namespace
-   [`483630f`](https://github.com/stdlib-js/stdlib/commit/483630fecc6f60fb8fbbe4066d37a95e3dd1e48e) - add `ndarray/base/broadcast-scalar-like` [(#9893)](https://github.com/stdlib-js/stdlib/pull/9893)
-   [`ebe7a8b`](https://github.com/stdlib-js/stdlib/commit/ebe7a8b476f13186ac83014965e4b60e502e6135) - add `ndarray/base/quaternary-loop-interchange-order` [(#9832)](https://github.com/stdlib-js/stdlib/pull/9832)
-   [`4641a30`](https://github.com/stdlib-js/stdlib/commit/4641a30d086f904746679c39e05898ecc65a3778) - add `ndarray/base/quinary-loop-interchange-order` [(#9870)](https://github.com/stdlib-js/stdlib/pull/9870)
-   [`3f76170`](https://github.com/stdlib-js/stdlib/commit/3f76170e20453f17308441619f3160bb22cc6c11) - add `stats/nanmidrange-by` [(#9637)](https://github.com/stdlib-js/stdlib/pull/9637)
-   [`896a1d4`](https://github.com/stdlib-js/stdlib/commit/896a1d454943f4aa2cff2f09cfe3045469dcf43e) - add `stats/strided/rangeabs` [(#9693)](https://github.com/stdlib-js/stdlib/pull/9693)
-   [`79d674d`](https://github.com/stdlib-js/stdlib/commit/79d674df0faad3185d690e5feab9cf8b160c4c35) - add `stats/midrange-by` [(#9681)](https://github.com/stdlib-js/stdlib/pull/9681)
-   [`ef33867`](https://github.com/stdlib-js/stdlib/commit/ef33867476544151b1ccfeb094c44b64c18dc1e0) - add `stats/strided/drangeabs` [(#9865)](https://github.com/stdlib-js/stdlib/pull/9865)
-   [`e6a8746`](https://github.com/stdlib-js/stdlib/commit/e6a87460491fd4ddba7e52f23555663dc4557ccd) - add `stats/strided/smskmaxabs` [(#9729)](https://github.com/stdlib-js/stdlib/pull/9729)
-   [`4152dbe`](https://github.com/stdlib-js/stdlib/commit/4152dbe038aa147be4d0712b9944fb916d14ef2f) - add `stats/base/ndarray/variance` [(#9828)](https://github.com/stdlib-js/stdlib/pull/9828)
-   [`3d6cd7d`](https://github.com/stdlib-js/stdlib/commit/3d6cd7d04e8f02dfa2fca7beda923f230c57a695) - add `stats/base/ndarray/stdevyc` [(#9736)](https://github.com/stdlib-js/stdlib/pull/9736)
-   [`aa0c054`](https://github.com/stdlib-js/stdlib/commit/aa0c05478633005f146d6ddde6113f935f50e8da) - add `number/float64/base/sub3` [(#9778)](https://github.com/stdlib-js/stdlib/pull/9778)
-   [`5b47953`](https://github.com/stdlib-js/stdlib/commit/5b479534f84d156b55e370c5cdb68f09b3943ed4) - add `stats/base/ndarray/dstdevwd` [(#9852)](https://github.com/stdlib-js/stdlib/pull/9852)
-   [`7a516b3`](https://github.com/stdlib-js/stdlib/commit/7a516b358abf02f8c4e871b9e7bb6b52c2ac9a42) - add `stats/base/ndarray/dstdevch` [(#9761)](https://github.com/stdlib-js/stdlib/pull/9761)
-   [`f6efb5e`](https://github.com/stdlib-js/stdlib/commit/f6efb5ea8dbd31affbd90bb35c8de06b33bb3704) - add support for float16 array types [(#9806)](https://github.com/stdlib-js/stdlib/pull/9806)
-   [`794dd4a`](https://github.com/stdlib-js/stdlib/commit/794dd4ad9f6be2c42f70119dade0d569ce382ad2) - add `stats/base/dists/halfnormal/mode` [(#9705)](https://github.com/stdlib-js/stdlib/pull/9705)
-   [`c9d512a`](https://github.com/stdlib-js/stdlib/commit/c9d512afde29049ca85e7e9e814eb33bf0bb5072) - add `stats/strided/srangeabs` [(#9850)](https://github.com/stdlib-js/stdlib/pull/9850)
-   [`9bf5e56`](https://github.com/stdlib-js/stdlib/commit/9bf5e561b497aea964565bfa9ca59964be12476c) - add `stats/base/dists/halfnormal/entropy` [(#9753)](https://github.com/stdlib-js/stdlib/pull/9753)
-   [`2463b16`](https://github.com/stdlib-js/stdlib/commit/2463b161e2b13334b7ac23c24fe85323e6447484) - add implementation of `stats/base/dists/halfnormal/kurtosis` [(#9771)](https://github.com/stdlib-js/stdlib/pull/9771)
-   [`ed81430`](https://github.com/stdlib-js/stdlib/commit/ed81430366dc2e2f58a354fafbbcd588f4b9069d) - add `math/base/special/acothf` [(#9803)](https://github.com/stdlib-js/stdlib/pull/9803)
-   [`1b8a546`](https://github.com/stdlib-js/stdlib/commit/1b8a546a22a9b669cd5287c32a5c16f9422c48c9) - add `stats/strided/dnanmskmidrange` [(#9823)](https://github.com/stdlib-js/stdlib/pull/9823)
-   [`3dc14f7`](https://github.com/stdlib-js/stdlib/commit/3dc14f7bbee9514c55b44940004f77c6771d7b12) - add `stats/base/ndarray/dstdevpn` [(#9787)](https://github.com/stdlib-js/stdlib/pull/9787)
-   [`717d578`](https://github.com/stdlib-js/stdlib/commit/717d5781130080c98d0a6f205cda38f24c62a3d9) - update `object` TypeScript declarations [(#9827)](https://github.com/stdlib-js/stdlib/pull/9827)
-   [`fc99e79`](https://github.com/stdlib-js/stdlib/commit/fc99e79e5cc20a58d1bb69644fdda25f2370474d) - add packages to object namespace
-   [`7f68fc4`](https://github.com/stdlib-js/stdlib/commit/7f68fc4aa254ea41b4d104041ff513239f104ba3) - add `math/base/special/atanhf` [(#9514)](https://github.com/stdlib-js/stdlib/pull/9514)
-   [`242c076`](https://github.com/stdlib-js/stdlib/commit/242c076de549632a025fe3bc519fbf1a5d46be7a) - add `stats/base/dists/halfnormal/mean` [(#9613)](https://github.com/stdlib-js/stdlib/pull/9613)
-   [`55a4c2f`](https://github.com/stdlib-js/stdlib/commit/55a4c2f90ee136423bf8d282893fdf6a3ba805ef) - add `blas/ext/base/drsskbn` [(#9013)](https://github.com/stdlib-js/stdlib/pull/9013)
-   [`069d813`](https://github.com/stdlib-js/stdlib/commit/069d81355ab0d2bf36773bbfd1ed1bc90ebaccb1) - add `stats/base/ndarray/dmeanstdev` [(#8525)](https://github.com/stdlib-js/stdlib/pull/8525)
-   [`85c8240`](https://github.com/stdlib-js/stdlib/commit/85c82409c5230249613943f9693ca0e8a19f5500) - add `stats/base/dists/halfnormal/stdev` [(#9714)](https://github.com/stdlib-js/stdlib/pull/9714)
-   [`19d5fc4`](https://github.com/stdlib-js/stdlib/commit/19d5fc4f36db513023e981a90103c9718eea59ff) - add `blas/ext/base/gsort` [(#9712)](https://github.com/stdlib-js/stdlib/pull/9712)
-   [`8b93c8d`](https://github.com/stdlib-js/stdlib/commit/8b93c8d51432c3ceb2a41f80bda77f77021e021e) - update `random/tools` TypeScript declarations [(#9718)](https://github.com/stdlib-js/stdlib/pull/9718)
-   [`ef9c1b0`](https://github.com/stdlib-js/stdlib/commit/ef9c1b0b52ac28c95221d46d7cb0e4165343f893) - update `random` TypeScript declarations [(#9717)](https://github.com/stdlib-js/stdlib/pull/9717)
-   [`2e20261`](https://github.com/stdlib-js/stdlib/commit/2e202614b34a0dedadc99d69ae8516d2f2524710) - add `object/deep-set`
-   [`c8781bb`](https://github.com/stdlib-js/stdlib/commit/c8781bb6f4f9745c8abd24b3b67ea7ba7aee8f78) - add `stats/strided/nanmskmidrange` [(#9417)](https://github.com/stdlib-js/stdlib/pull/9417)
-   [`a7ff263`](https://github.com/stdlib-js/stdlib/commit/a7ff263ba2b391497325f42217dc89386ec6012e) - add `stats/base/ndarray/variancewd` [(#9634)](https://github.com/stdlib-js/stdlib/pull/9634)
-   [`709563c`](https://github.com/stdlib-js/stdlib/commit/709563c0d7337b5c0632d1988fb263cf39305f86) - update `ndarray/base` TypeScript declarations [(#9716)](https://github.com/stdlib-js/stdlib/pull/9716)
-   [`d3a2eff`](https://github.com/stdlib-js/stdlib/commit/d3a2eff2cb9c18a89c287cf65cb0498a5b5b6245) - add `stats/strided/mskmaxabs` [(#9696)](https://github.com/stdlib-js/stdlib/pull/9696)
-   [`521f824`](https://github.com/stdlib-js/stdlib/commit/521f824a62e2f5b14db1022e760c88f0fffdf0ad) - add C implementation for `stats/base/dists/erlang/mgf` [(#8754)](https://github.com/stdlib-js/stdlib/pull/8754)
-   [`cfab032`](https://github.com/stdlib-js/stdlib/commit/cfab0325f798bcf48334e36d307ee33330824aff) - add `triangular` to namespace
-   [`132493e`](https://github.com/stdlib-js/stdlib/commit/132493e15add93ab5e56eb89c7f42ec08f06c402) - add `random/triangular`
-   [`a064afe`](https://github.com/stdlib-js/stdlib/commit/a064afe74bb89a7f835fafc63d16bb446e9f21e5) - add `hypergeometric` to namespace
-   [`62872f6`](https://github.com/stdlib-js/stdlib/commit/62872f64e1e235f44e063b81aea3dd721c4afedc) - add `random/hypergeometric`
-   [`cab5bb0`](https://github.com/stdlib-js/stdlib/commit/cab5bb08a4db8727097c61b4edb39c88137273eb) - add `frechet` to namespace
-   [`73344ab`](https://github.com/stdlib-js/stdlib/commit/73344abe4ac57ef5a27e6879e4274882caf596d6) - add `random/frechet`
-   [`fe91f02`](https://github.com/stdlib-js/stdlib/commit/fe91f02a931515c8dabe9e84a50fb9d124822111) - add `ternaryFactory` to namespace
-   [`244addc`](https://github.com/stdlib-js/stdlib/commit/244addce1a75c839b48065f9ebf7f763163e8723) - add `ternary` to namespace
-   [`36bb700`](https://github.com/stdlib-js/stdlib/commit/36bb70027e01d79ff0b0a42847df67deb0e22ce5) - add `random/tools/ternary-factory`
-   [`bb15dcc`](https://github.com/stdlib-js/stdlib/commit/bb15dcc572a4a67f7e7450919e7a0e3e915988dc) - add `random/tools/ternary`
-   [`f738a37`](https://github.com/stdlib-js/stdlib/commit/f738a37c1cc32a740c7ecc4cbc7982eca26f67d2) - add `ternaryBlockSize` to namespace
-   [`b490370`](https://github.com/stdlib-js/stdlib/commit/b49037059ac498f7e864cb83f0cf59b3feb3b459) - add `ternaryLoopOrder` to namespace
-   [`88e4096`](https://github.com/stdlib-js/stdlib/commit/88e4096e8e5941fecc15ef2fd2d5b27e91d69233) - add `ternary` to namespace
-   [`5fbedba`](https://github.com/stdlib-js/stdlib/commit/5fbedba2f71e2c6a20c33f0de574d0060536c0f5) - add `ternaryOutputDataType` to namespace
-   [`9d38a93`](https://github.com/stdlib-js/stdlib/commit/9d38a9324e99a3a00f733b30a37510e8d1e4b6a4) - add `ndarray/base/ternary-output-dtype`
-   [`b1a1b7f`](https://github.com/stdlib-js/stdlib/commit/b1a1b7fe3c8b93365c70632b726d6797d2af4438) - add support for ndarray data type objects and update existing type definitions
-   [`c6e2443`](https://github.com/stdlib-js/stdlib/commit/c6e24436d222d609c3ea153fd81f31e1d16451bc) - add `ndarray/base/ternary` [(#9566)](https://github.com/stdlib-js/stdlib/pull/9566)
-   [`38631fc`](https://github.com/stdlib-js/stdlib/commit/38631fc2f158f3334031ae6a8ac31d0307d46159) - add `blas/ext/base/dsort` [(#9684)](https://github.com/stdlib-js/stdlib/pull/9684)
-   [`bfbb4d1`](https://github.com/stdlib-js/stdlib/commit/bfbb4d12bfeed5c11da8384a5ab94935259eec82) - add `object/deep-get`
-   [`caea326`](https://github.com/stdlib-js/stdlib/commit/caea3266d32a5b6deadd1b75747d5d88e08699d2) - add `blas/ext/base/drss` [(#9647)](https://github.com/stdlib-js/stdlib/pull/9647)
-   [`88f0620`](https://github.com/stdlib-js/stdlib/commit/88f06201ec78b8b5376ad685f92aa3d3135a3d59) - add `stats/base/ndarray/sstdevwd` [(#9565)](https://github.com/stdlib-js/stdlib/pull/9565)
-   [`8019f5c`](https://github.com/stdlib-js/stdlib/commit/8019f5c04432ee29e3f16513dd29f3f4ed436346) - add `stats/strided/distances/dcityblock` [(#9586)](https://github.com/stdlib-js/stdlib/pull/9586)
-   [`4e8074a`](https://github.com/stdlib-js/stdlib/commit/4e8074a0fd574272817ba43ee2fa24fbb7431e43) - add `number/float16/base/assert/is-positive-zero` [(#9643)](https://github.com/stdlib-js/stdlib/pull/9643)
-   [`f36844d`](https://github.com/stdlib-js/stdlib/commit/f36844d1d51ef37e1934b6013481e39ef8052d09) - add `blas/ext/base/drssbl` [(#8722)](https://github.com/stdlib-js/stdlib/pull/8722)
-   [`4c079e0`](https://github.com/stdlib-js/stdlib/commit/4c079e04a6ed2aa27be8e42e599786bf8327f670) - add `H_H` macro in `math/base/napi/unary` [(#9576)](https://github.com/stdlib-js/stdlib/pull/9576)
-   [`2e1dd2a`](https://github.com/stdlib-js/stdlib/commit/2e1dd2a67c285b42e70077e0214b982fe18a55a2) - add `object/bifurcate-own`
-   [`1749282`](https://github.com/stdlib-js/stdlib/commit/1749282903f4364994431735e440fa2c2973ee00) - add `stats/base/ndarray/variancech` [(#9633)](https://github.com/stdlib-js/stdlib/pull/9633)
-   [`2d6416a`](https://github.com/stdlib-js/stdlib/commit/2d6416add43fe03624335438d20fb293bf78405a) - add `number/float16/base/assert/is-negative-zero` [(#9623)](https://github.com/stdlib-js/stdlib/pull/9623)
-   [`1aff763`](https://github.com/stdlib-js/stdlib/commit/1aff763c61863b7d737a699db89729d2bba0e1bc) - add `ndarray/spread-dimensions` [(#9424)](https://github.com/stdlib-js/stdlib/pull/9424)
-   [`aebc415`](https://github.com/stdlib-js/stdlib/commit/aebc415cd7b1579ef8935576eb4fae94a4277846) - add `number/float16/base/assert/is-nan` [(#9625)](https://github.com/stdlib-js/stdlib/pull/9625)
-   [`3c567b6`](https://github.com/stdlib-js/stdlib/commit/3c567b634cf5e5fa5e31b64f94206db5b4a88133) - update `ndarray/base` TypeScript declarations (#9640) [(#9640)](https://github.com/stdlib-js/stdlib/pull/9640)
-   [`483acba`](https://github.com/stdlib-js/stdlib/commit/483acba3dbcea263aa0014a2db41e1c073f8338b) - add `ndarray/find-last` [(#8724)](https://github.com/stdlib-js/stdlib/pull/8724)
-   [`fd99657`](https://github.com/stdlib-js/stdlib/commit/fd99657f0da9706d3c1d7b03c5f9caf97069d3df) - add `ndarray/prepend-singleton-dimensions` [(#9478)](https://github.com/stdlib-js/stdlib/pull/9478)
-   [`f475c84`](https://github.com/stdlib-js/stdlib/commit/f475c843a4b1579eef6533e464e4c16766d7ecdd) - add writable parameter to `ndarray/base/expand-dimensions` [(#9476)](https://github.com/stdlib-js/stdlib/pull/9476)
-   [`a068c72`](https://github.com/stdlib-js/stdlib/commit/a068c72880b9f3757d8b00ec945eb4e9cba31a8b) - add `math/base/special/roundnf` [(#9389)](https://github.com/stdlib-js/stdlib/pull/9389)
-   [`ef0435b`](https://github.com/stdlib-js/stdlib/commit/ef0435b69f05fa6a8d0e7d4ee44c72e1ccff1dd9) - add Wald distribution PDF [(#9324)](https://github.com/stdlib-js/stdlib/pull/9324)
-   [`da01e3d`](https://github.com/stdlib-js/stdlib/commit/da01e3d2071bb474ecef81e1d8ab07561f4b78f5) - add `number/float16/base/sub` [(#9558)](https://github.com/stdlib-js/stdlib/pull/9558)
-   [`5301fb5`](https://github.com/stdlib-js/stdlib/commit/5301fb5c6146068494dfa645007e823aa0777f84) - add `number/float16/base/assert/is-almost-equal` [(#9500)](https://github.com/stdlib-js/stdlib/pull/9500)
-   [`92d23f5`](https://github.com/stdlib-js/stdlib/commit/92d23f56523bf43782063a7a00b4499502ac1c38) - add Wald distribution mean [(#9502)](https://github.com/stdlib-js/stdlib/pull/9502)
-   [`cb09f58`](https://github.com/stdlib-js/stdlib/commit/cb09f5862f03c3056c8259164653940108068f30) - add `math/base/special/fast/atanhf` [(#9046)](https://github.com/stdlib-js/stdlib/pull/9046)
-   [`e19e323`](https://github.com/stdlib-js/stdlib/commit/e19e323575c6413702679045e005fcb1572eb1d9) - add `constants/float16/min-base10-exponent-subnormal` [(#9275)](https://github.com/stdlib-js/stdlib/pull/9275)
-   [`939e2d5`](https://github.com/stdlib-js/stdlib/commit/939e2d5e564a3f4015135894e4764d44e97b76ce) - add `constants/float32/num-exponent-bits` [(#9551)](https://github.com/stdlib-js/stdlib/pull/9551)
-   [`542d57c`](https://github.com/stdlib-js/stdlib/commit/542d57c97e7b8e8d9b41221d86c5378fa02d0d87) - add `math/base/special/floornf` [(#4881)](https://github.com/stdlib-js/stdlib/pull/4881)
-   [`008ae82`](https://github.com/stdlib-js/stdlib/commit/008ae82617ebeff86a92987e405e2c30ad627f1d) - add `stats/strided/distances/dchebychev` [(#9559)](https://github.com/stdlib-js/stdlib/pull/9559)
-   [`9422059`](https://github.com/stdlib-js/stdlib/commit/94220593c164a6c649125950794a496da05b10ef) - add `stats/strided/distances/deuclidean` [(#9376)](https://github.com/stdlib-js/stdlib/pull/9376)
-   [`09140c2`](https://github.com/stdlib-js/stdlib/commit/09140c2f44214e91e61ce3d6b993d36b56a08f12) - add `stats/strided/distances/dcosine-distance` [(#9430)](https://github.com/stdlib-js/stdlib/pull/9430)
-   [`c87f6a8`](https://github.com/stdlib-js/stdlib/commit/c87f6a88410d8742df047cd1b656bfa2e3088b23) - add `object/bifurcate-in`
-   [`fcc1f3c`](https://github.com/stdlib-js/stdlib/commit/fcc1f3cce959e57ada8f4cc484b8a55157ad6087) - add `stats/base/ndarray/sstdevpn` [(#9534)](https://github.com/stdlib-js/stdlib/pull/9534)
-   [`1d19423`](https://github.com/stdlib-js/stdlib/commit/1d19423c208ee726419674b8e44ed9b7d4f21ec2) - add `stats/base/ndarray/dstdev` [(#9516)](https://github.com/stdlib-js/stdlib/pull/9516)
-   [`aa31c82`](https://github.com/stdlib-js/stdlib/commit/aa31c82f3d919244c5393ae7a8b7331355eb2e17) - add `stats/base/ndarray/nanmidrange-by` [(#9501)](https://github.com/stdlib-js/stdlib/pull/9501)
-   [`6986d92`](https://github.com/stdlib-js/stdlib/commit/6986d92dd402cf96c394abfea5340be84184d2c1) - add `stats/base/ndarray/midrange-by` [(#9512)](https://github.com/stdlib-js/stdlib/pull/9512)
-   [`c216b80`](https://github.com/stdlib-js/stdlib/commit/c216b80baf3efe0d21387a280368c44122328b76) - add `stats/base/ndarray/smskmidrange` [(#9519)](https://github.com/stdlib-js/stdlib/pull/9519)
-   [`d681872`](https://github.com/stdlib-js/stdlib/commit/d681872a9b87321f4f66852f5aabfeec19e195fc) - add `stats/base/ndarray/mskmidrange` [(#9511)](https://github.com/stdlib-js/stdlib/pull/9511)
-   [`c824fea`](https://github.com/stdlib-js/stdlib/commit/c824feae2f1582ff59f0d3bee99896fa77ef1f81) - add `stats/base/ndarray/snanmidrange` [(#9505)](https://github.com/stdlib-js/stdlib/pull/9505)
-   [`a53615b`](https://github.com/stdlib-js/stdlib/commit/a53615b3210cdd787a16f1e8721d2d4e17153883) - add `object/inverse`
-   [`f40ccb7`](https://github.com/stdlib-js/stdlib/commit/f40ccb75929e92538b8c366145589addccdaafbe) - add `ndarray/base/ternary-loop-interchange-order` [(#9499)](https://github.com/stdlib-js/stdlib/pull/9499)
-   [`1f79854`](https://github.com/stdlib-js/stdlib/commit/1f798549409c47de0261c5396dccf64012e54a9c) - add `ndarray/base/ternary-tiling-block-size` [(#9495)](https://github.com/stdlib-js/stdlib/pull/9495)
-   [`8107a5a`](https://github.com/stdlib-js/stdlib/commit/8107a5a755bbdeb69c8110a2dbc9ed1a39d136c9) - add `stats/base/ndarray/dnanmidrange` [(#9504)](https://github.com/stdlib-js/stdlib/pull/9504)
-   [`fb7c43e`](https://github.com/stdlib-js/stdlib/commit/fb7c43e10a7a6f10f2677fa7ea1790fff535c968) - add `stats/strided/smskmidrange` [(#9492)](https://github.com/stdlib-js/stdlib/pull/9492)
-   [`327cda9`](https://github.com/stdlib-js/stdlib/commit/327cda9b2dda086b20da9ce256df388573486946) - update `ndarray` TypeScript declarations [(#9508)](https://github.com/stdlib-js/stdlib/pull/9508)
-   [`81f1cc5`](https://github.com/stdlib-js/stdlib/commit/81f1cc50d12dbb6ad9c0a198850ee56455c76db7) - add `stats/base/ndarray/nanmidrange` [(#9418)](https://github.com/stdlib-js/stdlib/pull/9418)
-   [`a7cbc8d`](https://github.com/stdlib-js/stdlib/commit/a7cbc8dbdbd69453891b1d5ffc1fcca9126910e2) - move optional argument to options object in `ndarray/concat` [(#9480)](https://github.com/stdlib-js/stdlib/pull/9480)
-   [`ea8228b`](https://github.com/stdlib-js/stdlib/commit/ea8228b082c03c6c8c8182d237c709ae279c05d2) - add `math/base/special/acoshf` [(#5812)](https://github.com/stdlib-js/stdlib/pull/5812)
-   [`e6a30ce`](https://github.com/stdlib-js/stdlib/commit/e6a30ce5227ad8260959fe518e88875e4d85a975) - update `complex/float64/base` TypeScript declarations [(#9466)](https://github.com/stdlib-js/stdlib/pull/9466)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`17da583`](https://github.com/stdlib-js/stdlib/commit/17da583dbeb78fa8b171d68af7011cba7b4f6be6) - improve type specificity
-   [`11cc2cf`](https://github.com/stdlib-js/stdlib/commit/11cc2cf8869a4b6ebf48545d5678eda25513529e) - use ndarray assertion utility
-   [`a1443d1`](https://github.com/stdlib-js/stdlib/commit/a1443d1b397d7a15382692e3ba76ecdd19fcfeff) - use correct `WebAssembly.instantiate` callback signature in `wasm/module-wrapper` [(#9720)](https://github.com/stdlib-js/stdlib/pull/9720)
-   [`7df5cea`](https://github.com/stdlib-js/stdlib/commit/7df5cea68c5d3239fa979b7e4d200d19c10bf9f2) - remove unneeded export comments and ensure browser build includes ndarray method
-   [`ad77b26`](https://github.com/stdlib-js/stdlib/commit/ad77b26a72b25bb371da51c3cb665c2803a8d9b0) - remove unneeded export comments and ensure browser build includes ndarray method
-   [`924aa84`](https://github.com/stdlib-js/stdlib/commit/924aa84174dd5191cf02f2e6e985ff90f4acceb4) - remove unneeded export comments and ensure browser build includes ndarray method
-   [`26ea808`](https://github.com/stdlib-js/stdlib/commit/26ea808b6afc4bb6db6492a9020f8325ebd2157e) - ensure browser-specific version of package has ndarray method
-   [`108e110`](https://github.com/stdlib-js/stdlib/commit/108e1100258d7c684177568b9d36abf77f1303f1) - use correct analytic formula and update tests and documentation
-   [`0ea192f`](https://github.com/stdlib-js/stdlib/commit/0ea192f53e0a69d4158693c1f4bab555a3a2fde2) - add missing exports comments
-   [`83c537b`](https://github.com/stdlib-js/stdlib/commit/83c537bacb40e371143295b9493c7d984d9b70ba) - add missing exports comment
-   [`5b1c0fd`](https://github.com/stdlib-js/stdlib/commit/5b1c0fd3f21b52b9cf1a791ab74367a08e79b2c8) - add missing exports comments
-   [`2828866`](https://github.com/stdlib-js/stdlib/commit/282886626527e6ecead4302731138ba11c04998f) - add missing exports comment directive
-   [`ef082b9`](https://github.com/stdlib-js/stdlib/commit/ef082b94577dd75dcbd855e795bf22cf87cecf5e) - update require to new location
-   [`6544e40`](https://github.com/stdlib-js/stdlib/commit/6544e40467b59c16865cd47427a9c01861a351b4) - inline constant value
-   [`a1fbf46`](https://github.com/stdlib-js/stdlib/commit/a1fbf4635c30c28ed3c8044ded17640bc877ca0d) - require `sigma` be greater than zero
-   [`20e08f9`](https://github.com/stdlib-js/stdlib/commit/20e08f9e46bae5fdc67e1d0f7e635be8afa3d1fd) - prevent deadlock on single-core systems and with empty arrays in `utils/parallel` [(#9597)](https://github.com/stdlib-js/stdlib/pull/9597)
-   [`376e7a3`](https://github.com/stdlib-js/stdlib/commit/376e7a36d5239ed7a21a3fb3f8114561cc0c20ef) - update TypeScript definitions to use `keys` instead of `indices`
-   [`d2d06f4`](https://github.com/stdlib-js/stdlib/commit/d2d06f45f5df1d830aa0a14331bd6b883d9992d5) - avoid infinite recursion and update examples
-   [`3af0a04`](https://github.com/stdlib-js/stdlib/commit/3af0a041f6ae95c251cbfa2acae82b30e3b4579b) - return `NaN` when the number of indexed elements is zero in `stats/strided/distances/dcosine-similarity` [(#9497)](https://github.com/stdlib-js/stdlib/pull/9497)
-   [`bda1a5c`](https://github.com/stdlib-js/stdlib/commit/bda1a5c6cfa6777839ab5f941296b2008880b75a) - use correct types

</section>

<!-- /.bug-fixes -->

<section class="reverts">

### Reverts

-   [`932f042`](https://github.com/stdlib-js/stdlib/commit/932f0422195ffa4db9efaca5e060881716aae006) - chore: add src to directories

</section>

<!-- /.reverts -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`cf38d87`](https://github.com/stdlib-js/stdlib/commit/cf38d87a6820408d2ec054cbf0e20561e8352deb): rename `stdlib_ndarray_bytelength` to `stdlib_ndarray_byte_length`

    -   To migrate, users using the C API should update their call signatures
        accordingly.

-   [`45ca891`](https://github.com/stdlib-js/stdlib/commit/45ca891a86f94011ad8b407ba8cf53a7cecbb7b5): rename `with` to `ndarrayWith` in `ndarray` namespace

    -   Users should migrate to the new function name when using it directly via the namespace object.

-   [`2cdca3d`](https://github.com/stdlib-js/stdlib/commit/2cdca3d0e0b00fd1c1cc5a46a8e8f367fceb9c3d): remove `utils/deep-set`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/object/deep-set` which provides the same API and implementation.

-   [`1a7afed`](https://github.com/stdlib-js/stdlib/commit/1a7afedb20f93966a643171629dac8620772219c): remove `deepSet`

    -   To migrate, users should access the same symbol via the
        `@stdlib/object` namespace.

-   [`b1a1b7f`](https://github.com/stdlib-js/stdlib/commit/b1a1b7fe3c8b93365c70632b726d6797d2af4438): add support for data type objects

    -   To migrate, users should avoid accessing ndarray properties via
        property accessors and instead use functional APIs, such as
        `@stdlib/ndarray/dtype`. If a string is expected, wrap the call
        to `ndarray/dtype` with `String(dt)` to force the dtype value to
        always be a string.

-   [`c774606`](https://github.com/stdlib-js/stdlib/commit/c77460647fe72de99efa50c75cff73ce3285a50f): remove `utils/deep-get`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/object/deep-get` which provides the same API and implementation.

-   [`ff350f3`](https://github.com/stdlib-js/stdlib/commit/ff350f3aa902afbd7dad2e32c03c3f0d5ced798f): remove `deepGet`

    -   To migrate, users should access the same symbol via the
        `@stdlib/object` namespace.

-   [`abfb9e2`](https://github.com/stdlib-js/stdlib/commit/abfb9e2214268f3681deaf54b1d0a454dbe1e4b1): remove `utils/bifurcate-own`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/object/bifurcate-own` which provides the same API and implementation.

-   [`2af3d97`](https://github.com/stdlib-js/stdlib/commit/2af3d9749b0aa0c5fe4c04f5e526e567b963e26a): remove `bifurcateOwn`

    -   To migrate, users should access the same symbol via the
        `@stdlib/object` namespace.

-   [`3c567b6`](https://github.com/stdlib-js/stdlib/commit/3c567b634cf5e5fa5e31b64f94206db5b4a88133): add `writable` parameter

    -   To migrate, users should explicitly provide a third argument indicating whether the ndarray returned by `expandDimensions` should be read-only. To preserve previous behavior, users should set the third argument to a boolean indicating whether a provided input ndarray is read-only.

-   [`f475c84`](https://github.com/stdlib-js/stdlib/commit/f475c843a4b1579eef6533e464e4c16766d7ecdd): add `writable` parameter

    -   To migrate, users should explicitly provide a third argument indicating whether to return a read-only ndarray. To preserve prior behavior, users should provide a boolean based on whether an input ndarray is read-only.

-   [`e776e3f`](https://github.com/stdlib-js/stdlib/commit/e776e3f55c8636a4d777c47a3f4b076d5523db33): remove `utils/bifurcate-in`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/object/bifurcate-in` which provides the same API and implementation.

-   [`20ee8cb`](https://github.com/stdlib-js/stdlib/commit/20ee8cb96a8d3d0de5b6229a72b040acbd965188): remove `bifurcateIn`

    -   To migrate, users should access the same symbol via the
        `@stdlib/object` namespace.

-   [`55030f9`](https://github.com/stdlib-js/stdlib/commit/55030f9809f5dba8e7ab8015c1f7faf9ab337aac): remove `utils/object-inverse`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/object/inverse` which provides the same API and implementation.

-   [`9ccefc9`](https://github.com/stdlib-js/stdlib/commit/9ccefc92d742e8e4a2555a39a65849c078d4e86e): remove `objectInverse`

    -   To migrate, users should access the same symbol via the
        `@stdlib/object` namespace.

-   [`327cda9`](https://github.com/stdlib-js/stdlib/commit/327cda9b2dda086b20da9ce256df388573486946): move `dim` argument to option

    -   To migrate, users wanting to specify a dimension along which to concatenate input arrays should provide an object containing a `dim` property.

-   [`a7cbc8d`](https://github.com/stdlib-js/stdlib/commit/a7cbc8dbdbd69453891b1d5ffc1fcca9126910e2): move `dim` argument to options object

    -   To migrate, users should replace any usage of an optional `dim` argument with an options object with a `dim` property (e.g., `{'dim': -1}`).

</section>

<!-- /.breaking-changes -->

<section class="issues">

### Closed Issues

A total of 40 issues were closed in this release:

[#209](https://github.com/stdlib-js/stdlib/issues/209), [#3573](https://github.com/stdlib-js/stdlib/issues/3573), [#5860](https://github.com/stdlib-js/stdlib/issues/5860), [#8294](https://github.com/stdlib-js/stdlib/issues/8294), [#8563](https://github.com/stdlib-js/stdlib/issues/8563), [#9403](https://github.com/stdlib-js/stdlib/issues/9403), [#9462](https://github.com/stdlib-js/stdlib/issues/9462), [#9463](https://github.com/stdlib-js/stdlib/issues/9463), [#9464](https://github.com/stdlib-js/stdlib/issues/9464), [#9506](https://github.com/stdlib-js/stdlib/issues/9506), [#9526](https://github.com/stdlib-js/stdlib/issues/9526), [#9527](https://github.com/stdlib-js/stdlib/issues/9527), [#9544](https://github.com/stdlib-js/stdlib/issues/9544), [#9550](https://github.com/stdlib-js/stdlib/issues/9550), [#9567](https://github.com/stdlib-js/stdlib/issues/9567), [#9569](https://github.com/stdlib-js/stdlib/issues/9569), [#9570](https://github.com/stdlib-js/stdlib/issues/9570), [#9614](https://github.com/stdlib-js/stdlib/issues/9614), [#9615](https://github.com/stdlib-js/stdlib/issues/9615), [#9638](https://github.com/stdlib-js/stdlib/issues/9638), [#9658](https://github.com/stdlib-js/stdlib/issues/9658), [#9687](https://github.com/stdlib-js/stdlib/issues/9687), [#9715](https://github.com/stdlib-js/stdlib/issues/9715), [#9754](https://github.com/stdlib-js/stdlib/issues/9754), [#9767](https://github.com/stdlib-js/stdlib/issues/9767), [#9777](https://github.com/stdlib-js/stdlib/issues/9777), [#9792](https://github.com/stdlib-js/stdlib/issues/9792), [#9792](https://github.com/stdlib-js/stdlib/issues/9792), [#9800](https://github.com/stdlib-js/stdlib/issues/9800), [#9800](https://github.com/stdlib-js/stdlib/issues/9800), [#9800](https://github.com/stdlib-js/stdlib/issues/9800), [#9800](https://github.com/stdlib-js/stdlib/issues/9800), [#9812](https://github.com/stdlib-js/stdlib/issues/9812), [#9824](https://github.com/stdlib-js/stdlib/issues/9824), [#9833](https://github.com/stdlib-js/stdlib/issues/9833), [#9843](https://github.com/stdlib-js/stdlib/issues/9843), [#9851](https://github.com/stdlib-js/stdlib/issues/9851), [#9883](https://github.com/stdlib-js/stdlib/issues/9883), [#9897](https://github.com/stdlib-js/stdlib/issues/9897), [#9965](https://github.com/stdlib-js/stdlib/issues/9965)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`ee4e852`](https://github.com/stdlib-js/stdlib/commit/ee4e852c6aebea0c9ce7316f364736622e4bf6a4) - **docs:** fix comments and returns description [(#10015)](https://github.com/stdlib-js/stdlib/pull/10015) _(by Sachin Pangal)_
-   [`66c95d7`](https://github.com/stdlib-js/stdlib/commit/66c95d76361e89d0774e48eaeeda47a0224dd954) - **bench:** update random value generation for `stats/base/dists/poisson` [(#10008)](https://github.com/stdlib-js/stdlib/pull/10008) _(by Bhargav Dabhade)_
-   [`c581849`](https://github.com/stdlib-js/stdlib/commit/c5818493ad7d9bc39aa8ccae27a8a6b3b905406b) - **bench:** update random value generation for `stats/base/dists/uniform` [(#10010)](https://github.com/stdlib-js/stdlib/pull/10010) _(by Lokesh Ranjan, Athan Reines)_
-   [`647b041`](https://github.com/stdlib-js/stdlib/commit/647b041046ea97ebc3cc35297e13f87134438c75) - **bench:** update random value generation for `stats/base/dists/uniform` [(#10007)](https://github.com/stdlib-js/stdlib/pull/10007) _(by Lokesh Ranjan)_
-   [`7b69002`](https://github.com/stdlib-js/stdlib/commit/7b69002e03bd424815f80e156e0994f150e80175) - **feat:** ensure support for non-string dtypes and update tests to use functional accessors _(by Athan Reines)_
-   [`4794f9e`](https://github.com/stdlib-js/stdlib/commit/4794f9e933b2f3375daa7d74d856dd8af79ce5ea) - **test:** use functional accessors and ensure support for non-string dtypes _(by Athan Reines)_
-   [`91a321e`](https://github.com/stdlib-js/stdlib/commit/91a321e84c6925239d651a2b9824a2c4aa3a23ee) - **chore:** clean-up and allow non-string dtypes _(by Athan Reines)_
-   [`3762b83`](https://github.com/stdlib-js/stdlib/commit/3762b83d30536b528ba17199d81f9da0b3c09cf6) - **refactor:** reduce duplication _(by Athan Reines)_
-   [`302f85f`](https://github.com/stdlib-js/stdlib/commit/302f85fd95665bfac64102e17641dc54eb59898f) - **test:** use functional accessors and update examples _(by Athan Reines)_
-   [`2b2ae6a`](https://github.com/stdlib-js/stdlib/commit/2b2ae6abbdb5752c90e0164c74d7669607e65895) - **docs:** improve doctests for ndarray instances in `ndarray/dcusumpw` [(#10005)](https://github.com/stdlib-js/stdlib/pull/10005) _(by Bhargav Dabhade)_
-   [`0712008`](https://github.com/stdlib-js/stdlib/commit/07120085d6b5279bbd4eee82128e9e54d2dae2d2) - **bench:** update random value generation for `stats/base/dists/poisson` [(#9997)](https://github.com/stdlib-js/stdlib/pull/9997) _(by Lokesh Ranjan, Athan Reines)_
-   [`d995add`](https://github.com/stdlib-js/stdlib/commit/d995add873841c6b6dc99502d72cde529caa7bf9) - **bench:** update random value generation for `stats/base/dists/poisson` [(#9998)](https://github.com/stdlib-js/stdlib/pull/9998) _(by Lokesh Ranjan)_
-   [`186140c`](https://github.com/stdlib-js/stdlib/commit/186140c35eeb2285177275b7c4027f95406d444a) - **bench:** update random value generation [(#9991)](https://github.com/stdlib-js/stdlib/pull/9991) _(by Harsh Yadav)_
-   [`17c6ab5`](https://github.com/stdlib-js/stdlib/commit/17c6ab555ace596db717d8a79b8b7784f8572f48) - **bench:** refactor to use string interpolation in `array/typed` [(#9994)](https://github.com/stdlib-js/stdlib/pull/9994) _(by Aman Singh)_
-   [`7b6aa5d`](https://github.com/stdlib-js/stdlib/commit/7b6aa5da510d61fdc069869e35128fe60e06b6f0) - **bench:** refactor to use string interpolation in `stats/base/dists/bernoulli` [(#9992)](https://github.com/stdlib-js/stdlib/pull/9992) _(by Lokesh Ranjan)_
-   [`f5f5199`](https://github.com/stdlib-js/stdlib/commit/f5f5199a93a6a91e708a30552586919367ba2289) - **bench:** update random value generation [(#9989)](https://github.com/stdlib-js/stdlib/pull/9989) _(by Harsh Yadav)_
-   [`94fd9d1`](https://github.com/stdlib-js/stdlib/commit/94fd9d14ec766730cb1db7f8e5fa3ec8dd53493e) - **bench:** refactor to use string interpolation in `plot/sparkline/unicode/line` [(#9988)](https://github.com/stdlib-js/stdlib/pull/9988) _(by AyushiJain18270)_
-   [`ec0d83c`](https://github.com/stdlib-js/stdlib/commit/ec0d83c87503b82fc4a192b6886ea3feab4b3448) - **docs:** update namespace table of contents [(#10003)](https://github.com/stdlib-js/stdlib/pull/10003) _(by stdlib-bot)_
-   [`75a4928`](https://github.com/stdlib-js/stdlib/commit/75a4928752ee93a88cbdf3114c12cd4ba2979c07) - **feat:** update `stats` TypeScript declarations [(#10002)](https://github.com/stdlib-js/stdlib/pull/10002) _(by stdlib-bot)_
-   [`cef8ee6`](https://github.com/stdlib-js/stdlib/commit/cef8ee6f3805b44b0784449befe4399584dd3b47) - **feat:** update `stats/base/ndarray` TypeScript declarations [(#10001)](https://github.com/stdlib-js/stdlib/pull/10001) _(by stdlib-bot)_
-   [`d660cab`](https://github.com/stdlib-js/stdlib/commit/d660cabc2799c7f43cda85b7a4ff65e0995a9a1e) - **feat:** add C implementation for `stats/base/ndarray/smin` [(#9981)](https://github.com/stdlib-js/stdlib/pull/9981) _(by Kaustubh Patange, Athan Reines)_
-   [`041e713`](https://github.com/stdlib-js/stdlib/commit/041e7138e20a8149b85835d9067c4065ce856893) - **feat:** add C implementation for `stats/base/ndarray/smax` [(#9956)](https://github.com/stdlib-js/stdlib/pull/9956) _(by Kaustubh Patange, Athan Reines)_
-   [`bbaef7b`](https://github.com/stdlib-js/stdlib/commit/bbaef7b113570a432bd33e31d03f18f070f3814b) - **feat:** add C implementation for `stats/base/ndarray/dmin` [(#9939)](https://github.com/stdlib-js/stdlib/pull/9939) _(by Kaustubh Patange)_
-   [`c300ff9`](https://github.com/stdlib-js/stdlib/commit/c300ff914062f53a0fcf2d195f694bbb90cc96a2) - **bench:** refactor to use string interpolation in `array/ones` [(#9970)](https://github.com/stdlib-js/stdlib/pull/9970) _(by Aman Singh)_
-   [`d42b8ed`](https://github.com/stdlib-js/stdlib/commit/d42b8edf519d8397417cabdfde090e34d9729021) - **bench:** refactor to use string interpolation in `array/ones-like` [(#9971)](https://github.com/stdlib-js/stdlib/pull/9971) _(by Aman Singh)_
-   [`fae4985`](https://github.com/stdlib-js/stdlib/commit/fae498583ef5643ae4826247852d855629e93d6a) - **feat:** add `dstdevtk` and `dstdevyc` to namespace _(by Athan Reines)_
-   [`af66e3c`](https://github.com/stdlib-js/stdlib/commit/af66e3c56f7a54ffbd16308bf506657f1f4948d0) - **feat:** add `sstdevyc` to namespace _(by Athan Reines)_
-   [`b1a3172`](https://github.com/stdlib-js/stdlib/commit/b1a31727a8fc6ba8cb2b07891e89c4c267a8242d) - **feat:** add `sstdevtk` to namespace _(by Athan Reines)_
-   [`58c2966`](https://github.com/stdlib-js/stdlib/commit/58c296693a0d4b9674368b5bbf71fb0dc4389007) - **feat:** add `stats/base/ndarray/sstdevtk` [(#9917)](https://github.com/stdlib-js/stdlib/pull/9917) _(by Samarth Kolarkar)_
-   [`df6733b`](https://github.com/stdlib-js/stdlib/commit/df6733b7cba6fd7122f3bd01811b609b84b97ca8) - **feat:** add `nanrange`, `nanrangeBy`, `rangeBy` to namespace _(by Athan Reines)_
-   [`4b9ded3`](https://github.com/stdlib-js/stdlib/commit/4b9ded3ba52a495d3cb976df6df8969eea3c8fe4) - **feat:** add `nanmidrangeBy`, `nanminBy`, `nanminabs` to namespace _(by Athan Reines)_
-   [`21a310e`](https://github.com/stdlib-js/stdlib/commit/21a310e5967dc01d80ac4505efbf66bc896f01dd) - **feat:** add `nanmeanors`, `nanmeanpn`, `nanmeanwd` to namespace _(by Athan Reines)_
-   [`18e825e`](https://github.com/stdlib-js/stdlib/commit/18e825eb623226175d0eca6141c98a37dd3dc3ea) - **feat:** add `minsorted`, `nanmaxBy`, `nanmaxabs` to namespace _(by Athan Reines)_
-   [`01f982c`](https://github.com/stdlib-js/stdlib/commit/01f982c89b9078a67483965e574f26edeeb25c73) - **feat:** add `mediansorted`, `midrange`, `midrangeBy` to namespace _(by Athan Reines)_
-   [`1ae0613`](https://github.com/stdlib-js/stdlib/commit/1ae0613632ccd365a9888087978398fe3af8faea) - **feat:** add `meankbn2`, `meanors`, `meanpn`, `meanpw`, `meanwd` to namespace _(by Athan Reines)_
-   [`c649696`](https://github.com/stdlib-js/stdlib/commit/c6496960fbe675dfb2d90e57312407bc1d14cd64) - **feat:** add `maxsorted` and `meankbn` to namespace _(by Athan Reines)_
-   [`6e7b3a8`](https://github.com/stdlib-js/stdlib/commit/6e7b3a875e396ef3d5f00953a7b241f34286b4a1) - **feat:** add `rangeabs` to namespace _(by Athan Reines)_
-   [`ff26c6d`](https://github.com/stdlib-js/stdlib/commit/ff26c6dd3ee1f76fa6c8deac6f1ae2ee5226baaa) - **feat:** add `stats/rangeabs` [(#9972)](https://github.com/stdlib-js/stdlib/pull/9972) _(by Sachin Pangal, Athan Reines, stdlib-bot)_
-   [`50af83b`](https://github.com/stdlib-js/stdlib/commit/50af83bcaa184b672be143271ee32f0b9fba06e1) - **docs:** update copy _(by Athan Reines)_
-   [`67315ee`](https://github.com/stdlib-js/stdlib/commit/67315ee65982c6354194c8baa3f22c6709bf25d3) - **feat:** add `stats/base/ndarray/dstdevyc` [(#9927)](https://github.com/stdlib-js/stdlib/pull/9927) _(by Samarth Kolarkar)_
-   [`ead840b`](https://github.com/stdlib-js/stdlib/commit/ead840b4a3cbadea51b04eb2614e379b411bd7ca) - **feat:** add `stats/base/ndarray/sstdevyc` [(#9922)](https://github.com/stdlib-js/stdlib/pull/9922) _(by Samarth Kolarkar)_
-   [`2503829`](https://github.com/stdlib-js/stdlib/commit/25038294c6793e8d14d5776bd364c99ab1a98ddc) - **docs:** improve doctests for ndarray instances in `blas/ext/base/ndarray/dcusumors` [(#9974)](https://github.com/stdlib-js/stdlib/pull/9974) _(by AyushiJain18270)_
-   [`8aaad97`](https://github.com/stdlib-js/stdlib/commit/8aaad97b1c15eb494a1607a00492cfdeee2acb98) - **bench:** update random value generation for `stats/base/dists/arcsine` [(#9973)](https://github.com/stdlib-js/stdlib/pull/9973) _(by Lokesh Ranjan)_
-   [`f4f48b1`](https://github.com/stdlib-js/stdlib/commit/f4f48b130f926c2adff515c2a90ec99cbc308815) - **feat:** add `stats/base/ndarray/dstdevtk` [(#9926)](https://github.com/stdlib-js/stdlib/pull/9926) _(by Samarth Kolarkar)_
-   [`71f4422`](https://github.com/stdlib-js/stdlib/commit/71f442266b75b400c0087df6820a5f5ac8ba1a1f) - **feat:** update `stats/strided` TypeScript declarations [(#9985)](https://github.com/stdlib-js/stdlib/pull/9985) _(by stdlib-bot)_
-   [`18a1271`](https://github.com/stdlib-js/stdlib/commit/18a1271042bb0163ba7f0b6a74433852a8eb882a) - **feat:** update `stats/base/ndarray` TypeScript declarations [(#9984)](https://github.com/stdlib-js/stdlib/pull/9984) _(by stdlib-bot)_
-   [`221e7ef`](https://github.com/stdlib-js/stdlib/commit/221e7efeec2d6c2e74c977b3e3f2f2fadb63860a) - **bench:** update random value generation [(#9976)](https://github.com/stdlib-js/stdlib/pull/9976) _(by Harsh Yadav)_
-   [`9159299`](https://github.com/stdlib-js/stdlib/commit/915929996cd4681abd544eebe75198b9eda29fa3) - **docs:** update namespace table of contents [(#9986)](https://github.com/stdlib-js/stdlib/pull/9986) _(by stdlib-bot)_
-   [`d4045a4`](https://github.com/stdlib-js/stdlib/commit/d4045a4b6c1bc9ead77c9b03068aec27a6cb863c) - **chore:** fix JavaScript lint errors [(#9968)](https://github.com/stdlib-js/stdlib/pull/9968) _(by Suyash Pathak, Athan Reines)_
-   [`ae0d247`](https://github.com/stdlib-js/stdlib/commit/ae0d247cceb75d109353ae90eec5c9489e786408) - **feat:** add `stats/strided/mskminabs` [(#9722)](https://github.com/stdlib-js/stdlib/pull/9722) _(by Sachin Pangal, Athan Reines, stdlib-bot)_
-   [`112d5e4`](https://github.com/stdlib-js/stdlib/commit/112d5e414e8e3b764e435aea7a3d8d41c62dabaf) - **bench:** refactor to use string interpolation _(by Athan Reines)_
-   [`fb97a2e`](https://github.com/stdlib-js/stdlib/commit/fb97a2e03b8bace788979a6ab9d880669740cf76) - **refactor:** export native add-on if available _(by Athan Reines)_
-   [`6a778f7`](https://github.com/stdlib-js/stdlib/commit/6a778f7dffb0d8225bf2f5f8849b6677aa19434c) - **feat:** add `smskmaxabs` to namespace _(by Athan Reines)_
-   [`00e8094`](https://github.com/stdlib-js/stdlib/commit/00e80949192deafa3d801d12df8933c613fcb52c) - **feat:** add `mskmaxabs` to namespace _(by Athan Reines)_
-   [`498e8b2`](https://github.com/stdlib-js/stdlib/commit/498e8b2882c1737a5bf5757704a97c0c63d90711) - **docs:** move content to notes _(by Athan Reines)_
-   [`991e692`](https://github.com/stdlib-js/stdlib/commit/991e6926616d85d4732140b22a85bb87cdb5720c) - **feat:** add `dmskmaxabs` to namespace _(by Athan Reines)_
-   [`ac01c27`](https://github.com/stdlib-js/stdlib/commit/ac01c274acc740fbf7ebad5b404d7ff2449b1b1d) - **feat:** add `stats/base/ndarray/mskmaxabs` [(#9957)](https://github.com/stdlib-js/stdlib/pull/9957) _(by Sachin Pangal, Athan Reines)_
-   [`31e075c`](https://github.com/stdlib-js/stdlib/commit/31e075c065f55f86226182872b987f585b489818) - **style:** remove empty line _(by Athan Reines)_
-   [`8ae9939`](https://github.com/stdlib-js/stdlib/commit/8ae993948492720e8b646c99bd17032be9bfea6c) - **feat:** add `stats/strided/dmskmaxabs` [(#9743)](https://github.com/stdlib-js/stdlib/pull/9743) _(by Sachin Pangal, Athan Reines, stdlib-bot)_
-   [`b1c1ac0`](https://github.com/stdlib-js/stdlib/commit/b1c1ac0ca0ae8488c5cec52a8f109d29cddecff6) - **feat:** add `stats/base/ndarray/smskmaxabs` [(#9961)](https://github.com/stdlib-js/stdlib/pull/9961) _(by Sachin Pangal, Athan Reines)_
-   [`7062ec1`](https://github.com/stdlib-js/stdlib/commit/7062ec16b2a4ebb8bc83d2460cd55e8ad09374d3) - **docs:** update copy _(by Athan Reines)_
-   [`17da583`](https://github.com/stdlib-js/stdlib/commit/17da583dbeb78fa8b171d68af7011cba7b4f6be6) - **fix:** improve type specificity _(by Athan Reines)_
-   [`b2ded58`](https://github.com/stdlib-js/stdlib/commit/b2ded58e47be1142dc7a054df093d77feeb49bf1) - **bench:** update random value generation [(#9925)](https://github.com/stdlib-js/stdlib/pull/9925) _(by Harsh Yadav)_
-   [`111fc36`](https://github.com/stdlib-js/stdlib/commit/111fc36035d3cc5eca9cd60a26c82f030636d583) - **bench:** update random value generation for `stats/base/dists/arcsine` [(#9953)](https://github.com/stdlib-js/stdlib/pull/9953) _(by Lokesh Ranjan)_
-   [`ec5723e`](https://github.com/stdlib-js/stdlib/commit/ec5723e300a5d71760c93a7e03b6aff9c9a62148) - **bench:** refactor to use string interpolation in `array/nans` [(#9948)](https://github.com/stdlib-js/stdlib/pull/9948) _(by Aman Singh)_
-   [`e0024f5`](https://github.com/stdlib-js/stdlib/commit/e0024f57d0cb09f2c897025dbc466732706f1eb8) - **bench:** refactor to use string interpolation in `array/nans-like` [(#9949)](https://github.com/stdlib-js/stdlib/pull/9949) _(by Aman Singh)_
-   [`d049e52`](https://github.com/stdlib-js/stdlib/commit/d049e5243020569ca3918432053c8b81e7652047) - **bench:** refactor to use string interpolation in `array/one-to` [(#9950)](https://github.com/stdlib-js/stdlib/pull/9950) _(by Aman Singh)_
-   [`c78d081`](https://github.com/stdlib-js/stdlib/commit/c78d081deff5ed3bc95010860bc5003cfb0a0563) - **bench:** refactor to use string interpolation in `array/one-to-like` [(#9952)](https://github.com/stdlib-js/stdlib/pull/9952) _(by Aman Singh)_
-   [`6860622`](https://github.com/stdlib-js/stdlib/commit/686062223abc7a79a5ae7f7fcc21fa93e943a101) - **bench:** refactor to use string interpolation in `stats/base/dists/erlang` [(#9941)](https://github.com/stdlib-js/stdlib/pull/9941) _(by Bhargav Dabhade)_
-   [`3c0d17b`](https://github.com/stdlib-js/stdlib/commit/3c0d17b0ea89b722f56db662f6d5496713e16d3f) - **docs:** update namespace table of contents [(#9967)](https://github.com/stdlib-js/stdlib/pull/9967) _(by stdlib-bot)_
-   [`a65d18d`](https://github.com/stdlib-js/stdlib/commit/a65d18d175d72246b54daca7ff8b59ccf7956f64) - **feat:** update `stats/base/ndarray` TypeScript declarations [(#9966)](https://github.com/stdlib-js/stdlib/pull/9966) _(by stdlib-bot)_
-   [`4018ee6`](https://github.com/stdlib-js/stdlib/commit/4018ee617715d836b7cc1dd3ab5861b5ff1d5b6e) - **bench:** fix name _(by Athan Reines)_
-   [`3a975ff`](https://github.com/stdlib-js/stdlib/commit/3a975ff10be645021132858cbea5e588afdfaa38) - **bench:** fix name _(by Athan Reines)_
-   [`64eb01b`](https://github.com/stdlib-js/stdlib/commit/64eb01b2ec3b527e033196d7b9629ea256c9acbd) - **bench:** include native suffix in benchmark [(#9921)](https://github.com/stdlib-js/stdlib/pull/9921) _(by Harsh Yadav)_
-   [`6a6d716`](https://github.com/stdlib-js/stdlib/commit/6a6d7163446fadaa9ffa3ca5ec01a44c77fe3c0c) - **feat:** add `drangeabs` to namespace _(by Athan Reines)_
-   [`88808cc`](https://github.com/stdlib-js/stdlib/commit/88808ccb3992c3565daed22fc1d1cd6321f33802) - **feat:** add `stats/base/ndarray/drangeabs` [(#9919)](https://github.com/stdlib-js/stdlib/pull/9919) _(by Sachin Pangal)_
-   [`d9d3ea6`](https://github.com/stdlib-js/stdlib/commit/d9d3ea6f22ba8eb35a75bea6c4ed21a72b7f3618) - **feat:** add `rangeabs` to namespace _(by Athan Reines)_
-   [`0b8361f`](https://github.com/stdlib-js/stdlib/commit/0b8361f354a73d91b1ca235e74bf0fab1bd1d7ae) - **feat:** add `stats/base/ndarray/rangeabs` [(#9918)](https://github.com/stdlib-js/stdlib/pull/9918) _(by Sachin Pangal)_
-   [`2b5c80e`](https://github.com/stdlib-js/stdlib/commit/2b5c80e62c9d6d2583a009fdf496a4a5e1827d64) - **feat:** add `srangeabs` to namespace _(by Athan Reines)_
-   [`c66543d`](https://github.com/stdlib-js/stdlib/commit/c66543d7be8062e7a3efcc3e332e5e270986d59c) - **feat:** add `stats/base/ndarray/srangeabs` [(#9920)](https://github.com/stdlib-js/stdlib/pull/9920) _(by Sachin Pangal)_
-   [`5ff8286`](https://github.com/stdlib-js/stdlib/commit/5ff82862ae371a0b87203969dad69861fd5ef180) - **bench:** update random value generation [(#9923)](https://github.com/stdlib-js/stdlib/pull/9923) _(by Harsh Yadav)_
-   [`12a9091`](https://github.com/stdlib-js/stdlib/commit/12a9091c51692376b7c516aa250906ffcc26d6c4) - **bench:** update random value generation for `stats/base/dists/arcsine` [(#9924)](https://github.com/stdlib-js/stdlib/pull/9924) _(by Lokesh Ranjan, Athan Reines)_
-   [`6926cf8`](https://github.com/stdlib-js/stdlib/commit/6926cf846717f27831738dbc96fa4bd902ef9dc5) - **bench:** refactor to use string interpolation in `stats/base/dists/uniform` [(#9928)](https://github.com/stdlib-js/stdlib/pull/9928) _(by Lokesh Ranjan)_
-   [`2c83b54`](https://github.com/stdlib-js/stdlib/commit/2c83b54c7edbcdfe83002fe8d161a6ba7ffc15f0) - **bench:** refactor to use string interpolation in `array/full` [(#9929)](https://github.com/stdlib-js/stdlib/pull/9929) _(by Sagar Ratna Chaudhary)_
-   [`3c6ce73`](https://github.com/stdlib-js/stdlib/commit/3c6ce73fcba6d4e4228609ef4dd23297c7dce41d) - **docs:** remove unused include _(by Athan Reines)_
-   [`27f8d66`](https://github.com/stdlib-js/stdlib/commit/27f8d6680258f746da15c2f5af7a712a57886492) - **chore:** fix missing closing section tag in README [(#9930)](https://github.com/stdlib-js/stdlib/pull/9930) _(by pxxad, Athan Reines)_
-   [`96537c4`](https://github.com/stdlib-js/stdlib/commit/96537c4a420cfd9517b9033531bde46eeb8c7ea4) - **chore:** clean-up examples _(by Athan Reines)_
-   [`aa9da1e`](https://github.com/stdlib-js/stdlib/commit/aa9da1e984009479baafb731970c49c0e2b0d423) - **feat:** update `ndarray/base` TypeScript declarations [(#9935)](https://github.com/stdlib-js/stdlib/pull/9935) _(by stdlib-bot)_
-   [`aa4cdfd`](https://github.com/stdlib-js/stdlib/commit/aa4cdfd5a67ada2e018c7970c4a777187280cce2) - **feat:** update `stats/strided/distances` TypeScript declarations [(#9936)](https://github.com/stdlib-js/stdlib/pull/9936) _(by stdlib-bot)_
-   [`2dc14e3`](https://github.com/stdlib-js/stdlib/commit/2dc14e39bc443c009059c88c1650e4ca227b708a) - **feat:** update `stats/strided` TypeScript declarations [(#9937)](https://github.com/stdlib-js/stdlib/pull/9937) _(by stdlib-bot)_
-   [`a87bde4`](https://github.com/stdlib-js/stdlib/commit/a87bde4102c9e3637ab02b18b39de03815e8d927) - **docs:** update namespace table of contents [(#9938)](https://github.com/stdlib-js/stdlib/pull/9938) _(by stdlib-bot)_
-   [`886ac7f`](https://github.com/stdlib-js/stdlib/commit/886ac7f190023a49a18e580f5345e9fdf71155bf) - **chore:** fix copyright year _(by Philipp Burckhardt)_
-   [`5ff04ce`](https://github.com/stdlib-js/stdlib/commit/5ff04cee55e8b5665706a925f9455b072b859684) - **docs:** update notes _(by Philipp Burckhardt)_
-   [`640d00d`](https://github.com/stdlib-js/stdlib/commit/640d00d5567707d2dcef81f1e6fafbdb947b6eab) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`e970275`](https://github.com/stdlib-js/stdlib/commit/e970275b9a144b5c27a875d315b6f6a6ab3ad063) - **docs:** update example _(by Athan Reines)_
-   [`b6a0e1f`](https://github.com/stdlib-js/stdlib/commit/b6a0e1f3b0044a068a51acd7cd1352ab0f8e4a60) - **bench:** fix call signature _(by Athan Reines)_
-   [`07e112a`](https://github.com/stdlib-js/stdlib/commit/07e112a03fc1c0308bdc38bcb0425dc2fe6faec5) - **feat:** add C API _(by Athan Reines)_
-   [`3d21748`](https://github.com/stdlib-js/stdlib/commit/3d2174821f71a70dbb3052da07e0a3b3f6dfbaa0) - **feat:** add function to return the index offset in units of elements _(by Athan Reines)_
-   [`dd45a8f`](https://github.com/stdlib-js/stdlib/commit/dd45a8fcec70ba4716ec67606a448721a723f54b) - **feat:** add function to return a dimension stride in units of elements _(by Athan Reines)_
-   [`b00ba84`](https://github.com/stdlib-js/stdlib/commit/b00ba84689ed039d0896209f94716c187cd6cccb) - **feat:** add function for returning the number of bytes per ndarray element _(by Athan Reines)_
-   [`cf38d87`](https://github.com/stdlib-js/stdlib/commit/cf38d87a6820408d2ec054cbf0e20561e8352deb) - **refactor:** rename `stdlib_ndarray_bytelength` to `stdlib_ndarray_byte_length` _(by Athan Reines)_
-   [`40c30fb`](https://github.com/stdlib-js/stdlib/commit/40c30fb11f3c1b99e073b5a2aa217bce452c3402) - **docs:** fix type _(by Athan Reines)_
-   [`46c8d0e`](https://github.com/stdlib-js/stdlib/commit/46c8d0eb953a8bd39e4486a93d65aca6c45af934) - **docs:** fix examples _(by Athan Reines)_
-   [`9d7f220`](https://github.com/stdlib-js/stdlib/commit/9d7f220eca1b55eb1c59b1f31efd91f66a450af2) - **refactor:** use generalized utility _(by Athan Reines)_
-   [`7f54590`](https://github.com/stdlib-js/stdlib/commit/7f54590d0556e5c8b13d8bc2c527dbfc90e55201) - **refactor:** use generalized utility _(by Athan Reines)_
-   [`45ee3d6`](https://github.com/stdlib-js/stdlib/commit/45ee3d69be75dcd538d8fde2f2b23ac100995c4b) - **refactor:** use generalized utility _(by Athan Reines)_
-   [`51e9e67`](https://github.com/stdlib-js/stdlib/commit/51e9e67bf770b750204cb4f97b0420faa06191ce) - **refactor:** use generalized utility _(by Athan Reines)_
-   [`6ebb5c9`](https://github.com/stdlib-js/stdlib/commit/6ebb5c96300bde3f75f7cbae57fdecf8c5a08f93) - **refactor:** use generalized utility _(by Athan Reines)_
-   [`24cd22d`](https://github.com/stdlib-js/stdlib/commit/24cd22d47029be52bb7992bcdb839edb7711b68f) - **refactor:** call into generalized utility _(by Athan Reines)_
-   [`622fb73`](https://github.com/stdlib-js/stdlib/commit/622fb73db38259c72bcbf0d10afa063400914f24) - **test:** fix condition _(by Athan Reines)_
-   [`1e5789c`](https://github.com/stdlib-js/stdlib/commit/1e5789c70b7400b0ff1cd71d06798c1e5b26f16b) - **feat:** add `blockSize` to namespace _(by Athan Reines)_
-   [`a6117b1`](https://github.com/stdlib-js/stdlib/commit/a6117b1bd697083439d740567d41cbfa754f68ab) - **feat:** add `quinaryBlockSize` to namespace _(by Athan Reines)_
-   [`c6dca39`](https://github.com/stdlib-js/stdlib/commit/c6dca39c634f8c016dc6fa4d0330a47bba977eaf) - **feat:** add `quaternaryBlockSize` to namespace _(by Athan Reines)_
-   [`2d51ff6`](https://github.com/stdlib-js/stdlib/commit/2d51ff6a1af79d361401ff928fb755bfaa1170f7) - **feat:** add `ndarray/base/tiling-block-size` _(by Athan Reines)_
-   [`9c75b30`](https://github.com/stdlib-js/stdlib/commit/9c75b302a82df9b6c580b9f8afc647773e5684a3) - **feat:** add `ndarray/base/quinary-tiling-block-size` [(#9871)](https://github.com/stdlib-js/stdlib/pull/9871) _(by Muhammad Haris, Athan Reines)_
-   [`d84de96`](https://github.com/stdlib-js/stdlib/commit/d84de9698683c20fa3b67eb9d2a615a403f6b707) - **feat:** add `ndarray/base/quaternary-tiling-block-size` [(#9838)](https://github.com/stdlib-js/stdlib/pull/9838) _(by Muhammad Haris, Athan Reines)_
-   [`942fa9b`](https://github.com/stdlib-js/stdlib/commit/942fa9ba4e93c3064011ead7bae1d1f8ac0281de) - **feat:** add `distances` to namespace _(by Athan Reines)_
-   [`262f96d`](https://github.com/stdlib-js/stdlib/commit/262f96df7fe35057b1ad9a29802497f935788600) - **feat:** update namespace _(by Athan Reines)_
-   [`d0e3e71`](https://github.com/stdlib-js/stdlib/commit/d0e3e71f26da59d042df4ae94869589ee17f237a) - **feat:** add `stats/strided/distances` namespace _(by Athan Reines)_
-   [`0538a41`](https://github.com/stdlib-js/stdlib/commit/0538a41cc4147040c041d86068fce07ecfdca36d) - **feat:** add `stats/strided/distances/dsquared-euclidean` [(#9680)](https://github.com/stdlib-js/stdlib/pull/9680) _(by Nakul Krishnakumar, Athan Reines)_
-   [`fbc0835`](https://github.com/stdlib-js/stdlib/commit/fbc08352233e90ae7ff159385d4d3926dff1e13c) - **feat:** add `snanmidrange` and `srangeabs` to namespace _(by Athan Reines)_
-   [`52100d1`](https://github.com/stdlib-js/stdlib/commit/52100d116b87170e3a325bd87665b0ad223894e2) - **feat:** add `smskmaxabs` and `smskmidrange` to namespace _(by Athan Reines)_
-   [`bde889e`](https://github.com/stdlib-js/stdlib/commit/bde889e82b8692575b6a0a1876b28ba9130abf11) - **feat:** add `rangeabs` to namespace _(by Athan Reines)_
-   [`0e31507`](https://github.com/stdlib-js/stdlib/commit/0e31507fc2049fb7c9ab2e7a4f1ae95a97cee2ae) - **feat:** add `nanmskmidrange` to namespace _(by Athan Reines)_
-   [`c13da4c`](https://github.com/stdlib-js/stdlib/commit/c13da4c90cf6fc5fe8f95a092c16a3158e8dc957) - **feat:** add `nanmidrange` and `nanmidrangeBy` to namespace _(by Athan Reines)_
-   [`4d7e3d2`](https://github.com/stdlib-js/stdlib/commit/4d7e3d2d2a82112e93d9289c81a35f44d2e2e312) - **feat:** add `mskmaxabs` and `mskmidrange` to namespace _(by Athan Reines)_
-   [`c86ff1c`](https://github.com/stdlib-js/stdlib/commit/c86ff1cf8c853f3a549b92ee9231e6ce1571dfe7) - **feat:** add `midrange` and `midrangeBy` to namespace _(by Athan Reines)_
-   [`3f0d5ee`](https://github.com/stdlib-js/stdlib/commit/3f0d5ee64202dcd04ad9d5bf0aa4a2d22de82351) - **feat:** add `drangeabs` to namespace _(by Athan Reines)_
-   [`8c75c0d`](https://github.com/stdlib-js/stdlib/commit/8c75c0da4f1d5710fde341b06672faf7e18e221b) - **feat:** add `dmskmidrange`, `dnanmidrange`, `dnanmskmidrange` to namespace _(by Athan Reines)_
-   [`1fa6b54`](https://github.com/stdlib-js/stdlib/commit/1fa6b54311953d38b35d08bee5967e8496a5261d) - **feat:** add `snanmskmidrange` to namespace _(by Athan Reines)_
-   [`562065d`](https://github.com/stdlib-js/stdlib/commit/562065d7fcb441b25a487453c4321030478ee966) - **feat:** add `stats/strided/snanmskmidrange` [(#9821)](https://github.com/stdlib-js/stdlib/pull/9821) _(by Sachin Pangal, Philipp Burckhardt, Athan Reines)_
-   [`8f8998f`](https://github.com/stdlib-js/stdlib/commit/8f8998f02831c2db69698a26769916d68acfe54f) - **feat:** update `ndarray/base` TypeScript declarations [(#9913)](https://github.com/stdlib-js/stdlib/pull/9913) _(by stdlib-bot)_
-   [`e3e238d`](https://github.com/stdlib-js/stdlib/commit/e3e238dd684b98b67ad10ae4da51f33f1cf5413d) - **feat:** update `stats/base/ndarray` TypeScript declarations [(#9914)](https://github.com/stdlib-js/stdlib/pull/9914) _(by stdlib-bot, Athan Reines)_
-   [`ce2a3e1`](https://github.com/stdlib-js/stdlib/commit/ce2a3e195b5cfda0de0e06da8c7c82da70ff1339) - **docs:** fix example _(by Athan Reines)_
-   [`196734e`](https://github.com/stdlib-js/stdlib/commit/196734eccb0d43439332b2a275fb3a50cb73df67) - **docs:** update namespace table of contents [(#9915)](https://github.com/stdlib-js/stdlib/pull/9915) _(by stdlib-bot)_
-   [`f693285`](https://github.com/stdlib-js/stdlib/commit/f69328578f728111a8993e9fae78c7aef0a7143f) - **bench:** refactor to use string interpolation in `number/float32/base/assert` [(#9910)](https://github.com/stdlib-js/stdlib/pull/9910) _(by Lokesh Ranjan)_
-   [`765abdf`](https://github.com/stdlib-js/stdlib/commit/765abdffa2d20193f4fe18f7add2061d7700ec1f) - **bench:** refactor to use string interpolation in `number/float32/base` [(#9909)](https://github.com/stdlib-js/stdlib/pull/9909) _(by Lokesh Ranjan)_
-   [`755d5cb`](https://github.com/stdlib-js/stdlib/commit/755d5cb22e6b18aafee24426257953f33cc1f0ec) - **bench:** refactor to use string interpolation in `number/float32/base` [(#9908)](https://github.com/stdlib-js/stdlib/pull/9908) _(by Lokesh Ranjan)_
-   [`de545e8`](https://github.com/stdlib-js/stdlib/commit/de545e8b4d05e9f6fbadc4387c3bd254c6abfcef) - **bench:** add opts and use string interpolation in `stats/base/dists/halfnormal/mode` [(#9904)](https://github.com/stdlib-js/stdlib/pull/9904) _(by Lokesh Ranjan)_
-   [`56a8646`](https://github.com/stdlib-js/stdlib/commit/56a864622858956ca75eb8a2af74e81b827115e7) - **bench:** refactor to use string interpolation in `number/float32/base` [(#9907)](https://github.com/stdlib-js/stdlib/pull/9907) _(by Lokesh Ranjan)_
-   [`b98b7fd`](https://github.com/stdlib-js/stdlib/commit/b98b7fdd51f62e84065397f1d261a125aa62ad23) - **bench:** refactor to use string interpolation in `number/float16/base` [(#9906)](https://github.com/stdlib-js/stdlib/pull/9906) _(by Lokesh Ranjan)_
-   [`f79a945`](https://github.com/stdlib-js/stdlib/commit/f79a9459ee83a526964301bb1e400059f0daf08d) - **bench:** refactor to use string interpolation in `stats/base/dists/planck` [(#9901)](https://github.com/stdlib-js/stdlib/pull/9901) _(by Suyash Pathak)_
-   [`fabac99`](https://github.com/stdlib-js/stdlib/commit/fabac994a5faee54c764fc1744f9a3427a6cf7b3) - **feat:** add `variance`, `variancech`, `variancewd` to namespace _(by Athan Reines)_
-   [`b165d09`](https://github.com/stdlib-js/stdlib/commit/b165d09ba924d67d5ee7ed2f307a2a394708c830) - **feat:** add `stdev`, `stdevch`, `stdevpn`, `stdevtk`, `stdevwd`, `stdevyc` to namespace _(by Athan Reines)_
-   [`f68ce9c`](https://github.com/stdlib-js/stdlib/commit/f68ce9c54ec885f22090a8397346c865242aed80) - **feat:** add `sstdev`, `sstdevch`, `sstdevpn`, `sstdevwd` to namespace _(by Athan Reines)_
-   [`7139c25`](https://github.com/stdlib-js/stdlib/commit/7139c25a29aa627c32bd5995aee81e89511931b8) - **feat:** add `snanrange` to namespace _(by Athan Reines)_
-   [`94ff22d`](https://github.com/stdlib-js/stdlib/commit/94ff22dca4d701f12d6bb6abdcab72adb28715c0) - **feat:** add `snanmskmax`, `snanmskmin`, `snanmskrange` to namespace _(by Athan Reines)_
-   [`b38d7db`](https://github.com/stdlib-js/stdlib/commit/b38d7db968c63307010eb6ab7d9911cd22395497) - **feat:** add `snanmidrange` to namespace _(by Athan Reines)_
-   [`a3c5163`](https://github.com/stdlib-js/stdlib/commit/a3c516334b198d5e75651fe6ccab356fb859a0b0) - **feat:** add `smskmax`, `smskmidrange`, `smskmin`, `smskrange` to namespace _(by Athan Reines)_
-   [`e76145c`](https://github.com/stdlib-js/stdlib/commit/e76145c08e0d14d58ebd4000b4be3e5aa2b847cd) - **feat:** add `smeanors`, `smediansorted`, `smidrange` to namespace _(by Athan Reines)_
-   [`1ef47af`](https://github.com/stdlib-js/stdlib/commit/1ef47afe2c2d359bdcbdd581377e55a3ae32bf98) - **feat:** add `sdsmean`, `sdsmeanors`, `sdsnanmeanors` to namespace _(by Athan Reines)_
-   [`ce723a4`](https://github.com/stdlib-js/stdlib/commit/ce723a44bfba8592c4add60f31021768b7497798) - **feat:** add `nanrange` and `nanrangeBy` to namespace _(by Athan Reines)_
-   [`87ee49b`](https://github.com/stdlib-js/stdlib/commit/87ee49bd98f76bfe8f7819206cc941de1d1b09eb) - **feat:** add `nanmskmax`, `nanmskmin`, `nanmskrange` to namespace _(by Athan Reines)_
-   [`a4d6dcf`](https://github.com/stdlib-js/stdlib/commit/a4d6dcfe836dbab948b11ef1e86e0b9fcb52f58e) - **feat:** add `nanmeanors`, `nanmidrange`, `nanmidrangeBy`, `nanminBy` to namespace _(by Athan Reines)_
-   [`5feabb7`](https://github.com/stdlib-js/stdlib/commit/5feabb757b0306583c947e77cb327316cc340080) - **feat:** add `mskmidrange` to namespace _(by Athan Reines)_
-   [`a6c1cde`](https://github.com/stdlib-js/stdlib/commit/a6c1cde8db2eb893de6912f2942b715837c28cb9) - **feat:** add `nanmaxBy` to namespace _(by Athan Reines)_
-   [`f916336`](https://github.com/stdlib-js/stdlib/commit/f916336ffb65ee1718c971dc97ac4cdc4beda3b3) - **feat:** add `midrange` and `midrangeBy` to namespace _(by Athan Reines)_
-   [`d99d331`](https://github.com/stdlib-js/stdlib/commit/d99d331a62b1521342ac812793a7080e449d192d) - **feat:** add `dstdev`, `dstdevch`, `dstdevpn`, and `dstdevwd` to namespace _(by Athan Reines)_
-   [`52f25b4`](https://github.com/stdlib-js/stdlib/commit/52f25b4a749bfafacdbeb46884c1c314b3a25f73) - **feat:** add `dnanrange` to namespace _(by Athan Reines)_
-   [`6a81c76`](https://github.com/stdlib-js/stdlib/commit/6a81c76e896d7fe3794f9857ed8b157fccc7493b) - **feat:** add `dnanmskmax`, `dnanmskmin`, and `dnanmskrange` to namespace _(by Athan Reines)_
-   [`43ad0bc`](https://github.com/stdlib-js/stdlib/commit/43ad0bc483f79583c41354c4e494e28022c6e83d) - **feat:** add `dnanmidrange` to namespace _(by Athan Reines)_
-   [`b90d38d`](https://github.com/stdlib-js/stdlib/commit/b90d38d7eb7f24e6370c07ecabe0c6bf6d3b2b80) - **feat:** add `dmskmax`, `dmskmin`, and `dmskrange` to namespace _(by Athan Reines)_
-   [`914b803`](https://github.com/stdlib-js/stdlib/commit/914b80399759dcf6911f9a92a4ff6845527d8bb8) - **feat:** add `dmediansorted` and `dmidrange` to namespace _(by Athan Reines)_
-   [`4a91724`](https://github.com/stdlib-js/stdlib/commit/4a91724da0e502a7f861b71a80796b5c980ac042) - **feat:** add `dmeanstdev` to namespace _(by Athan Reines)_
-   [`3c8018f`](https://github.com/stdlib-js/stdlib/commit/3c8018f6095b3553a0004d9eb164e4daecc22b9e) - **feat:** add `dmeanors` to namespace _(by Athan Reines)_
-   [`7f787ff`](https://github.com/stdlib-js/stdlib/commit/7f787ffc41f715cdca8a37fe39d46da733c53e32) - **feat:** add `dmeanwd` to namespace _(by Athan Reines)_
-   [`b6d8bcc`](https://github.com/stdlib-js/stdlib/commit/b6d8bcc8e3a285d4f874748191904580321aa0e8) - **feat:** add `quinaryLoopOrder` to namespace _(by Athan Reines)_
-   [`f3a6bc0`](https://github.com/stdlib-js/stdlib/commit/f3a6bc070f6ac5e2dee1374534ba6b0c134e4db6) - **feat:** add `quaternaryLoopOrder` to namespace _(by Athan Reines)_
-   [`02b9b76`](https://github.com/stdlib-js/stdlib/commit/02b9b7662449c9a04917e1353a8b53ff85df45d4) - **feat:** add `broadcastScalarLike` to namespace _(by Athan Reines)_
-   [`483630f`](https://github.com/stdlib-js/stdlib/commit/483630fecc6f60fb8fbbe4066d37a95e3dd1e48e) - **feat:** add `ndarray/base/broadcast-scalar-like` [(#9893)](https://github.com/stdlib-js/stdlib/pull/9893) _(by Muhammad Haris, Athan Reines)_
-   [`65aa64a`](https://github.com/stdlib-js/stdlib/commit/65aa64a2f860129b3ca2f09f47641e4355303799) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`dad3808`](https://github.com/stdlib-js/stdlib/commit/dad3808a07099bb09b7eaa4c03260aefee2e1ace) - **bench:** create empty ndarrays for better dtype generality _(by Athan Reines)_
-   [`11cc2cf`](https://github.com/stdlib-js/stdlib/commit/11cc2cf8869a4b6ebf48545d5678eda25513529e) - **fix:** use ndarray assertion utility _(by Athan Reines)_
-   [`7fbc3d9`](https://github.com/stdlib-js/stdlib/commit/7fbc3d91696d37d3f3f37377d14bd8e5e4d22358) - **bench:** use string interpolation in benchmark descriptions [(#9601)](https://github.com/stdlib-js/stdlib/pull/9601) _(by KovidhRaj)_
-   [`ebe7a8b`](https://github.com/stdlib-js/stdlib/commit/ebe7a8b476f13186ac83014965e4b60e502e6135) - **feat:** add `ndarray/base/quaternary-loop-interchange-order` [(#9832)](https://github.com/stdlib-js/stdlib/pull/9832) _(by Muhammad Haris)_
-   [`4641a30`](https://github.com/stdlib-js/stdlib/commit/4641a30d086f904746679c39e05898ecc65a3778) - **feat:** add `ndarray/base/quinary-loop-interchange-order` [(#9870)](https://github.com/stdlib-js/stdlib/pull/9870) _(by Muhammad Haris)_
-   [`085eb24`](https://github.com/stdlib-js/stdlib/commit/085eb2426b60071db157a9ae63e0ff85797e134f) - **chore:** fix JavaScript lint errors [(#9900)](https://github.com/stdlib-js/stdlib/pull/9900) _(by Suyash Pathak, Athan Reines)_
-   [`3f76170`](https://github.com/stdlib-js/stdlib/commit/3f76170e20453f17308441619f3160bb22cc6c11) - **feat:** add `stats/nanmidrange-by` [(#9637)](https://github.com/stdlib-js/stdlib/pull/9637) _(by Sachin Pangal)_
-   [`896a1d4`](https://github.com/stdlib-js/stdlib/commit/896a1d454943f4aa2cff2f09cfe3045469dcf43e) - **feat:** add `stats/strided/rangeabs` [(#9693)](https://github.com/stdlib-js/stdlib/pull/9693) _(by Sachin Pangal, Athan Reines)_
-   [`a1b3377`](https://github.com/stdlib-js/stdlib/commit/a1b3377d032d908a777785b05f9c08da0681543c) - **docs:** update `number/int8/base` TypeScript declarations [(#9899)](https://github.com/stdlib-js/stdlib/pull/9899) _(by stdlib-bot)_
-   [`41c55d8`](https://github.com/stdlib-js/stdlib/commit/41c55d85d758d40bf6a2533bdeb130790199304b) - **docs:** update `number/int16/base` TypeScript declarations [(#9898)](https://github.com/stdlib-js/stdlib/pull/9898) _(by stdlib-bot)_
-   [`79d674d`](https://github.com/stdlib-js/stdlib/commit/79d674df0faad3185d690e5feab9cf8b160c4c35) - **feat:** add `stats/midrange-by` [(#9681)](https://github.com/stdlib-js/stdlib/pull/9681) _(by Sachin Pangal)_
-   [`ef33867`](https://github.com/stdlib-js/stdlib/commit/ef33867476544151b1ccfeb094c44b64c18dc1e0) - **feat:** add `stats/strided/drangeabs` [(#9865)](https://github.com/stdlib-js/stdlib/pull/9865) _(by Sachin Pangal, Athan Reines)_
-   [`3cebbe5`](https://github.com/stdlib-js/stdlib/commit/3cebbe518119ad62a6ba1657a740e43fff916342) - **refactor:** perform explicit push when using generic arrays [(#9873)](https://github.com/stdlib-js/stdlib/pull/9873) _(by Om-A-osc, Athan Reines)_
-   [`4a2e646`](https://github.com/stdlib-js/stdlib/commit/4a2e6469a8bcab9e12a0a758c12aae7dbbf4da46) - **chore:** fix JavaScript lint errors [(#9846)](https://github.com/stdlib-js/stdlib/pull/9846) _(by Suyash Pathak, Athan Reines)_
-   [`86da9c3`](https://github.com/stdlib-js/stdlib/commit/86da9c36f2d5aab25056a563688ae2b9cc42616b) - **chore:** fix JavaScript lint errors [(#9560)](https://github.com/stdlib-js/stdlib/pull/9560) _(by Shreelaxmi Hegde)_
-   [`53c6e6c`](https://github.com/stdlib-js/stdlib/commit/53c6e6c6d4c9f0ce1d2ebfb19f340d1879c8e8ae) - **bench:** update random value generation [(#9891)](https://github.com/stdlib-js/stdlib/pull/9891) _(by Harsh Yadav, Athan Reines)_
-   [`225a1d9`](https://github.com/stdlib-js/stdlib/commit/225a1d993e50804e3ae39f5effe14508bc253015) - **chore:** fix JavaScript lint errors [(#9813)](https://github.com/stdlib-js/stdlib/pull/9813) _(by nnyouung, Athan Reines)_
-   [`e6a8746`](https://github.com/stdlib-js/stdlib/commit/e6a87460491fd4ddba7e52f23555663dc4557ccd) - **feat:** add `stats/strided/smskmaxabs` [(#9729)](https://github.com/stdlib-js/stdlib/pull/9729) _(by Sachin Pangal, Athan Reines)_
-   [`fbf9b05`](https://github.com/stdlib-js/stdlib/commit/fbf9b05485f4e55d549c1da242c01e39972dd2ac) - **chore:** resolve lint errors [(#9853)](https://github.com/stdlib-js/stdlib/pull/9853) _(by Om-A-osc, Athan Reines)_
-   [`4152dbe`](https://github.com/stdlib-js/stdlib/commit/4152dbe038aa147be4d0712b9944fb916d14ef2f) - **feat:** add `stats/base/ndarray/variance` [(#9828)](https://github.com/stdlib-js/stdlib/pull/9828) _(by Divyanshu)_
-   [`3d6cd7d`](https://github.com/stdlib-js/stdlib/commit/3d6cd7d04e8f02dfa2fca7beda923f230c57a695) - **feat:** add `stats/base/ndarray/stdevyc` [(#9736)](https://github.com/stdlib-js/stdlib/pull/9736) _(by Pratik, Athan Reines)_
-   [`aa0c054`](https://github.com/stdlib-js/stdlib/commit/aa0c05478633005f146d6ddde6113f935f50e8da) - **feat:** add `number/float64/base/sub3` [(#9778)](https://github.com/stdlib-js/stdlib/pull/9778) _(by Sachin Pangal, Neeraj Pathak)_
-   [`5b47953`](https://github.com/stdlib-js/stdlib/commit/5b479534f84d156b55e370c5cdb68f09b3943ed4) - **feat:** add `stats/base/ndarray/dstdevwd` [(#9852)](https://github.com/stdlib-js/stdlib/pull/9852) _(by Pratik)_
-   [`7a516b3`](https://github.com/stdlib-js/stdlib/commit/7a516b358abf02f8c4e871b9e7bb6b52c2ac9a42) - **feat:** add `stats/base/ndarray/dstdevch` [(#9761)](https://github.com/stdlib-js/stdlib/pull/9761) _(by Pratik)_
-   [`c404057`](https://github.com/stdlib-js/stdlib/commit/c4040575dcca6cc615621c9a3b1dc3eb0ff18f6d) - **bench:** update random value generation [(#9820)](https://github.com/stdlib-js/stdlib/pull/9820) _(by Harsh Yadav)_
-   [`bfcc8d1`](https://github.com/stdlib-js/stdlib/commit/bfcc8d119234d1aabb2003ec613f6a62fee0cdf9) - **chore:** fix JavaScript lint errors [(#9888)](https://github.com/stdlib-js/stdlib/pull/9888) _(by Suyash Pathak, Athan Reines)_
-   [`b5e65f7`](https://github.com/stdlib-js/stdlib/commit/b5e65f77cc4d0d175f408c2c44aaca987a76354d) - **bench:** add opts and use string interpolation [(#9889)](https://github.com/stdlib-js/stdlib/pull/9889) _(by Harsh Yadav)_
-   [`4f42b6a`](https://github.com/stdlib-js/stdlib/commit/4f42b6af6b471d4ba9786f73d308e93992a12cdb) - **bench:** refactor to use string interpolation in `stats/base/dists/levy/mean` [(#9896)](https://github.com/stdlib-js/stdlib/pull/9896) _(by Daksha Raj)_
-   [`a1443d1`](https://github.com/stdlib-js/stdlib/commit/a1443d1b397d7a15382692e3ba76ecdd19fcfeff) - **fix:** use correct `WebAssembly.instantiate` callback signature in `wasm/module-wrapper` [(#9720)](https://github.com/stdlib-js/stdlib/pull/9720) _(by Shivam Mittal, Athan Reines)_
-   [`f6efb5e`](https://github.com/stdlib-js/stdlib/commit/f6efb5ea8dbd31affbd90bb35c8de06b33bb3704) - **feat:** add support for float16 array types [(#9806)](https://github.com/stdlib-js/stdlib/pull/9806) _(by Gururaj Gurram)_
-   [`bcac5a8`](https://github.com/stdlib-js/stdlib/commit/bcac5a8416e8cc611010ee290899cd72177087b1) - **bench:** refactor to use string interpolation in various `assert` packages [(#9786)](https://github.com/stdlib-js/stdlib/pull/9786) _(by Anant Sharma, Athan Reines)_
-   [`2a9e3c5`](https://github.com/stdlib-js/stdlib/commit/2a9e3c51b801951fed1dd75b0cdd3180b91c5ca6) - **bench:** refactor `stats/base/dists/arcsine/cdf` benchmarks [(#9881)](https://github.com/stdlib-js/stdlib/pull/9881) _(by Om-A-osc, Athan Reines)_
-   [`ecf4b7c`](https://github.com/stdlib-js/stdlib/commit/ecf4b7c12430e95d5ea3438b003b839a55628f18) - **bench:** refactor to use string interpolation in `assert/is-almost-equal-complex64array` [(#9874)](https://github.com/stdlib-js/stdlib/pull/9874) _(by Sagar Ratna Chaudhary)_
-   [`9342bfc`](https://github.com/stdlib-js/stdlib/commit/9342bfcbac1f1b266884212947f2c4140cb82fa9) - **bench:** refactor to use string interpolation in `assert/is-almost-equal-array` [(#9875)](https://github.com/stdlib-js/stdlib/pull/9875) _(by Sagar Ratna Chaudhary)_
-   [`b0d9263`](https://github.com/stdlib-js/stdlib/commit/b0d926308b169cdf980b88bf60055b1ad4853cd2) - **bench:** refactor to use string interpolation in `assert/is-almost-equal-float64array` [(#9878)](https://github.com/stdlib-js/stdlib/pull/9878) _(by Sagar Ratna Chaudhary)_
-   [`5439372`](https://github.com/stdlib-js/stdlib/commit/54393723510567614137ca86403213c39c407559) - **bench:** refactor to use string interpolation in `assert/is-almost-equal-complex128array` [(#9876)](https://github.com/stdlib-js/stdlib/pull/9876) _(by Sagar Ratna Chaudhary)_
-   [`6e21629`](https://github.com/stdlib-js/stdlib/commit/6e21629c4064ea16b800fa43138c6c70debc0039) - **bench:** refactor to use string interpolation in `assert/is-almost-equal-float32array` [(#9877)](https://github.com/stdlib-js/stdlib/pull/9877) _(by Sagar Ratna Chaudhary)_
-   [`0646933`](https://github.com/stdlib-js/stdlib/commit/06469331a90eca2105b96749522f3e73450b556c) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`e42451a`](https://github.com/stdlib-js/stdlib/commit/e42451a082479c4f573c60885a54fa9a6fc4313e) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`49b870b`](https://github.com/stdlib-js/stdlib/commit/49b870bdbabb88bb852fc22744ebb76f7dde5d44) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`a976e0d`](https://github.com/stdlib-js/stdlib/commit/a976e0d977a2c0b117d83581d38441fd15ca6273) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`a830720`](https://github.com/stdlib-js/stdlib/commit/a830720e1179ecd50924edf20d884483cc39f570) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`0db4998`](https://github.com/stdlib-js/stdlib/commit/0db499866f3b5f50061f3827c7726851c6b8e320) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`719e685`](https://github.com/stdlib-js/stdlib/commit/719e685eaa6460d9ded69333953019952455750f) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`430583e`](https://github.com/stdlib-js/stdlib/commit/430583e905716d80351b947a43631e3aa26ee257) - **refactor:** simplify package structure and remove extra browser entry _(by Philipp Burckhardt)_
-   [`f133840`](https://github.com/stdlib-js/stdlib/commit/f1338403c5121a8cdbae93a51e98adf7c16caaaa) - **chore:** add `number/int16/base` scaffolding _(by Philipp Burckhardt)_
-   [`d52aafd`](https://github.com/stdlib-js/stdlib/commit/d52aafdfacb06727b40f92ab6a1872bd3905a117) - **chore:** add `number/int8/base` scaffolding _(by Philipp Burckhardt)_
-   [`b665247`](https://github.com/stdlib-js/stdlib/commit/b665247f7098a8dda04c8cee2e8f8f14a6923f1a) - **docs:** add missing references for `stats/base/ndarray/sstdevwd` [(#9864)](https://github.com/stdlib-js/stdlib/pull/9864) _(by Pratik)_
-   [`f9db7b8`](https://github.com/stdlib-js/stdlib/commit/f9db7b8a5287fffa18da2ba9438513bb05cfb194) - **docs:** update namespace table of contents [(#9884)](https://github.com/stdlib-js/stdlib/pull/9884) _(by stdlib-bot)_
-   [`c36d8f4`](https://github.com/stdlib-js/stdlib/commit/c36d8f4e60350651e664c63c07761fc344d5234f) - **chore:** clean-up _(by Athan Reines)_
-   [`1c9a785`](https://github.com/stdlib-js/stdlib/commit/1c9a785ad53c5dac99aa5e019402cd4d8e7bccaa) - **bench:** add missing benchmarks _(by Athan Reines)_
-   [`a1628e3`](https://github.com/stdlib-js/stdlib/commit/a1628e3cd7cfded6ca980c21645c29fd34ede4ce) - **chore:** clean-up _(by Athan Reines)_
-   [`45ca891`](https://github.com/stdlib-js/stdlib/commit/45ca891a86f94011ad8b407ba8cf53a7cecbb7b5) - **refactor:** rename `with` alias to `ndarrayWith` in `ndarray` _(by Philipp Burckhardt)_
-   [`56a6ce8`](https://github.com/stdlib-js/stdlib/commit/56a6ce8ba25fe8e1710f04aad9d99696332b7616) - **refactor:** do not require static `byteLength` method _(by Philipp Burckhardt)_
-   [`e28d2fe`](https://github.com/stdlib-js/stdlib/commit/e28d2fe0eba692438ff7322feedcc8db4da6c308) - **chore:** remove unneeded exports comment _(by Philipp Burckhardt)_
-   [`7df5cea`](https://github.com/stdlib-js/stdlib/commit/7df5cea68c5d3239fa979b7e4d200d19c10bf9f2) - **fix:** remove unneeded export comments and ensure browser build includes ndarray method _(by Philipp Burckhardt)_
-   [`ad77b26`](https://github.com/stdlib-js/stdlib/commit/ad77b26a72b25bb371da51c3cb665c2803a8d9b0) - **fix:** remove unneeded export comments and ensure browser build includes ndarray method _(by Philipp Burckhardt)_
-   [`924aa84`](https://github.com/stdlib-js/stdlib/commit/924aa84174dd5191cf02f2e6e985ff90f4acceb4) - **fix:** remove unneeded export comments and ensure browser build includes ndarray method _(by Philipp Burckhardt)_
-   [`90da141`](https://github.com/stdlib-js/stdlib/commit/90da141063d7deb9af83a387dc4bbd27b73e8095) - **chore:** remove exports comments _(by Philipp Burckhardt)_
-   [`ae31fc0`](https://github.com/stdlib-js/stdlib/commit/ae31fc062e919fcbca412e037a61ae68956eada0) - **test:** update require to match implementation file _(by Philipp Burckhardt)_
-   [`26ea808`](https://github.com/stdlib-js/stdlib/commit/26ea808b6afc4bb6db6492a9020f8325ebd2157e) - **fix:** ensure browser-specific version of package has ndarray method _(by Philipp Burckhardt)_
-   [`108e110`](https://github.com/stdlib-js/stdlib/commit/108e1100258d7c684177568b9d36abf77f1303f1) - **fix:** use correct analytic formula and update tests and documentation _(by Athan Reines)_
-   [`2816724`](https://github.com/stdlib-js/stdlib/commit/2816724d9493a837fd62b1bce1ea1527afe6f2bc) - **chore:** clean-up _(by Athan Reines)_
-   [`ac1050a`](https://github.com/stdlib-js/stdlib/commit/ac1050ab5716b16ad08fc7acd45b0742ee775461) - **chore:** clean-up _(by Athan Reines)_
-   [`95a8d60`](https://github.com/stdlib-js/stdlib/commit/95a8d60c4d73ed9df86cf640230f1874aa8be9e7) - **chore:** remove exports comment _(by Philipp Burckhardt)_
-   [`0954a22`](https://github.com/stdlib-js/stdlib/commit/0954a22ec2926b4d772482696031a5d36f2d747d) - **chore:** add missing exports comments _(by Philipp Burckhardt)_
-   [`94692a4`](https://github.com/stdlib-js/stdlib/commit/94692a42667fa49bcd4c25abf5e717ab4c7f904c) - **chore:** use format instead of string concatenation [(#9863)](https://github.com/stdlib-js/stdlib/pull/9863) _(by Om-A-osc)_
-   [`b0c70d4`](https://github.com/stdlib-js/stdlib/commit/b0c70d4e0ee87f9678d29c51613a90b05c7aae92) - **chore:** clean-up _(by Athan Reines)_
-   [`42a21ef`](https://github.com/stdlib-js/stdlib/commit/42a21ef96b20ae2c821330ef5ddf8b1bce032bfc) - **chore:** add missing exports comments _(by Philipp Burckhardt)_
-   [`ca3ead8`](https://github.com/stdlib-js/stdlib/commit/ca3ead8968414cc4d281ddfce84449fc10ac3ffa) - **chore:** remove unneeded exports comment _(by Philipp Burckhardt)_
-   [`da376aa`](https://github.com/stdlib-js/stdlib/commit/da376aaaf20f9eacc241279eba60a6de5d476c00) - **bench:** update random value generation [(#9860)](https://github.com/stdlib-js/stdlib/pull/9860) _(by Harsh Yadav)_
-   [`a3eec0d`](https://github.com/stdlib-js/stdlib/commit/a3eec0d8cf8121d20be4e9bb178ad99ac46096a0) - **bench:** refactor to use string interpolation in `math/base/special/atanhf` [(#9861)](https://github.com/stdlib-js/stdlib/pull/9861) _(by Harsh Yadav)_
-   [`cccf137`](https://github.com/stdlib-js/stdlib/commit/cccf1373cfe50773b96a7d2a4a538ed54987780b) - **bench:** refactor to use string interpolation in `array/pool` [(#9862)](https://github.com/stdlib-js/stdlib/pull/9862) _(by Sagar Ratna Chaudhary)_
-   [`89e6e3f`](https://github.com/stdlib-js/stdlib/commit/89e6e3f78d7a3adb40799b58f51a7d79c298a0bc) - **bench:** update random value generation [(#9855)](https://github.com/stdlib-js/stdlib/pull/9855) _(by Harsh Yadav)_
-   [`6114701`](https://github.com/stdlib-js/stdlib/commit/611470131a2d7acced9ee078458b6817b78138c3) - **docs:** minor clean-up _(by Philipp Burckhardt)_
-   [`1dc536d`](https://github.com/stdlib-js/stdlib/commit/1dc536d94d8783c36df2f1dd9fc8777689155d23) - **refactor:** pre-calculate constant _(by Philipp Burckhardt)_
-   [`794dd4a`](https://github.com/stdlib-js/stdlib/commit/794dd4ad9f6be2c42f70119dade0d569ce382ad2) - **feat:** add `stats/base/dists/halfnormal/mode` [(#9705)](https://github.com/stdlib-js/stdlib/pull/9705) _(by Lokesh Ranjan, Philipp Burckhardt)_
-   [`c9d512a`](https://github.com/stdlib-js/stdlib/commit/c9d512afde29049ca85e7e9e814eb33bf0bb5072) - **feat:** add `stats/strided/srangeabs` [(#9850)](https://github.com/stdlib-js/stdlib/pull/9850) _(by Sachin Pangal, stdlib-bot)_
-   [`9bf5e56`](https://github.com/stdlib-js/stdlib/commit/9bf5e561b497aea964565bfa9ca59964be12476c) - **feat:** add `stats/base/dists/halfnormal/entropy` [(#9753)](https://github.com/stdlib-js/stdlib/pull/9753) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`2463b16`](https://github.com/stdlib-js/stdlib/commit/2463b161e2b13334b7ac23c24fe85323e6447484) - **feat:** add implementation of `stats/base/dists/halfnormal/kurtosis` [(#9771)](https://github.com/stdlib-js/stdlib/pull/9771) _(by Om-A-osc, Philipp Burckhardt)_
-   [`f79b9dd`](https://github.com/stdlib-js/stdlib/commit/f79b9dd302d7278cb14028a3e847293a83403cf9) - **docs:** fix and regenerate `random` namespace README _(by Philipp Burckhardt)_
-   [`68446dc`](https://github.com/stdlib-js/stdlib/commit/68446dcb55d7b08e39baf6efae7ba5ba038c923f) - **docs:** update namespace table of contents [(#9848)](https://github.com/stdlib-js/stdlib/pull/9848) _(by stdlib-bot)_
-   [`f4988cf`](https://github.com/stdlib-js/stdlib/commit/f4988cf2c32f31b975e6c7bf14ba0eaccff7dad3) - **docs:** add missing closing section tag in `regexp` README _(by Philipp Burckhardt)_
-   [`ed81430`](https://github.com/stdlib-js/stdlib/commit/ed81430366dc2e2f58a354fafbbcd588f4b9069d) - **feat:** add `math/base/special/acothf` [(#9803)](https://github.com/stdlib-js/stdlib/pull/9803) _(by Harsh Yadav, Philipp Burckhardt)_
-   [`5852d17`](https://github.com/stdlib-js/stdlib/commit/5852d1790fb92fa1464b4cca295bb7724d557013) - **chore:** fix JavaScript lint errors [(#9837)](https://github.com/stdlib-js/stdlib/pull/9837) _(by Utkarsh Singhal)_
-   [`74650c6`](https://github.com/stdlib-js/stdlib/commit/74650c6ff0f1cc54f930032127c3d1fc586d5f5c) - **chore:** remove extra empty lines [(#9834)](https://github.com/stdlib-js/stdlib/pull/9834) _(by stdlib-bot)_
-   [`457ce9c`](https://github.com/stdlib-js/stdlib/commit/457ce9c6b58b09832b290d2d4ae030421b509eeb) - **docs:** update `math/base/special` TypeScript declaration example code [(#9835)](https://github.com/stdlib-js/stdlib/pull/9835) _(by stdlib-bot)_
-   [`14448a8`](https://github.com/stdlib-js/stdlib/commit/14448a82bf9147190d1aa08a9aa756f7187227df) - **docs:** update REPL namespace documentation [(#9836)](https://github.com/stdlib-js/stdlib/pull/9836) _(by stdlib-bot)_
-   [`1b8a546`](https://github.com/stdlib-js/stdlib/commit/1b8a546a22a9b669cd5287c32a5c16f9422c48c9) - **feat:** add `stats/strided/dnanmskmidrange` [(#9823)](https://github.com/stdlib-js/stdlib/pull/9823) _(by Sachin Pangal, Philipp Burckhardt, stdlib-bot)_
-   [`3dc14f7`](https://github.com/stdlib-js/stdlib/commit/3dc14f7bbee9514c55b44940004f77c6771d7b12) - **feat:** add `stats/base/ndarray/dstdevpn` [(#9787)](https://github.com/stdlib-js/stdlib/pull/9787) _(by Pratik, Philipp Burckhardt)_
-   [`7ddfd47`](https://github.com/stdlib-js/stdlib/commit/7ddfd47647bffccc63781211c7bf1e529f6822eb) - **test:** remove duplicate test cases in `stats/base/dists/normal` packages _(by Philipp Burckhardt)_
-   [`5ee0c78`](https://github.com/stdlib-js/stdlib/commit/5ee0c781e82099b730ddd0126f888515b817b47c) - **test:** remove duplicate test cases in `stats/base/dists/lognormal` packages _(by Philipp Burckhardt)_
-   [`749fcaf`](https://github.com/stdlib-js/stdlib/commit/749fcafc87f8a07912d99a10fe3cb32ac2701f20) - **test:** remove duplicate test cases in `stats/base/dists/logistic` packages _(by Philipp Burckhardt)_
-   [`99d1d40`](https://github.com/stdlib-js/stdlib/commit/99d1d40243aee2ea033af6eb4cc168841755a62e) - **test:** remove duplicate test cases in `stats/base/dists/levy` packages _(by Philipp Burckhardt)_
-   [`ce2a193`](https://github.com/stdlib-js/stdlib/commit/ce2a1930b7c0014fd2404c7cf5f7a90f44e9f6fa) - **test:** remove duplicate test cases in `stats/base/dists/laplace` packages _(by Philipp Burckhardt)_
-   [`81d3277`](https://github.com/stdlib-js/stdlib/commit/81d3277b781d2270f126ae12bc67269107d23a5f) - **test:** remove duplicate test cases in `stats/base/dists/kumaraswamy` packages _(by Philipp Burckhardt)_
-   [`af9f6dc`](https://github.com/stdlib-js/stdlib/commit/af9f6dcb8d83eaf080cdda5828eb9a27cf182378) - **test:** remove duplicate test cases in `stats/base/dists/gumbel` packages _(by Philipp Burckhardt)_
-   [`3459117`](https://github.com/stdlib-js/stdlib/commit/345911757db54bdd60ac0e41615b421536a2f4a4) - **test:** remove duplicate test cases in `stats/base/dists/frechet` packages _(by Philipp Burckhardt)_
-   [`590f3d5`](https://github.com/stdlib-js/stdlib/commit/590f3d50f63756ba32242c90aa0d0ef672180159) - **test:** remove duplicate test cases in `stats/base/dists/cosine` packages _(by Philipp Burckhardt)_
-   [`50f2408`](https://github.com/stdlib-js/stdlib/commit/50f240842114b46d91ccc84ca97f93f6c21ae5ac) - **test:** remove duplicate test cases in `string/base` packages _(by Philipp Burckhardt)_
-   [`7ffed96`](https://github.com/stdlib-js/stdlib/commit/7ffed96e4ed10b5ee1a340adc368d27902d54591) - **test:** remove duplicate test cases in `math/base/special` packages _(by Philipp Burckhardt)_
-   [`1ec4672`](https://github.com/stdlib-js/stdlib/commit/1ec46724592393aa1503e774e9ddedf52873d3f8) - **bench:** refactor to use use dynamic memory allocation in `stats/strided/dmeankbn` [(#9814)](https://github.com/stdlib-js/stdlib/pull/9814) _(by Vishal Gaikwad)_
-   [`7188b0d`](https://github.com/stdlib-js/stdlib/commit/7188b0d35d337eba56bd34d4970b2c852f25ebf9) - **docs:** improve doctests for complex number instances in `math/base/special/cflipsign` [(#9815)](https://github.com/stdlib-js/stdlib/pull/9815) _(by Vishal Gaikwad)_
-   [`b5ee1c6`](https://github.com/stdlib-js/stdlib/commit/b5ee1c6c5b7b982be4373a8c4f1e5b598f5cdcec) - **bench:** refactor to use use dynamic memory allocation in `stats/strided/dmeankbn2` [(#9816)](https://github.com/stdlib-js/stdlib/pull/9816) _(by Vishal Gaikwad)_
-   [`6f5aec7`](https://github.com/stdlib-js/stdlib/commit/6f5aec7cf9da6150245618637de7b50bc7594993) - **test:** remove duplicate test cases in normal variance [(#9826)](https://github.com/stdlib-js/stdlib/pull/9826) _(by Geo Daoyu)_
-   [`717d578`](https://github.com/stdlib-js/stdlib/commit/717d5781130080c98d0a6f205cda38f24c62a3d9) - **feat:** update `object` TypeScript declarations [(#9827)](https://github.com/stdlib-js/stdlib/pull/9827) _(by stdlib-bot)_
-   [`0ea192f`](https://github.com/stdlib-js/stdlib/commit/0ea192f53e0a69d4158693c1f4bab555a3a2fde2) - **fix:** add missing exports comments _(by Philipp Burckhardt)_
-   [`fc99e79`](https://github.com/stdlib-js/stdlib/commit/fc99e79e5cc20a58d1bb69644fdda25f2370474d) - **feat:** add packages to object namespace _(by Philipp Burckhardt)_
-   [`83c537b`](https://github.com/stdlib-js/stdlib/commit/83c537bacb40e371143295b9493c7d984d9b70ba) - **fix:** add missing exports comment _(by Philipp Burckhardt)_
-   [`5b1c0fd`](https://github.com/stdlib-js/stdlib/commit/5b1c0fd3f21b52b9cf1a791ab74367a08e79b2c8) - **fix:** add missing exports comments _(by Philipp Burckhardt)_
-   [`2828866`](https://github.com/stdlib-js/stdlib/commit/282886626527e6ecead4302731138ba11c04998f) - **fix:** add missing exports comment directive _(by Philipp Burckhardt)_
-   [`ef082b9`](https://github.com/stdlib-js/stdlib/commit/ef082b94577dd75dcbd855e795bf22cf87cecf5e) - **fix:** update require to new location _(by Philipp Burckhardt)_
-   [`c11b35c`](https://github.com/stdlib-js/stdlib/commit/c11b35c2be07283d370662abf5438b9935b49fff) - **bench:** refactor to use string interpolation in `array/base/fillednd` [(#9779)](https://github.com/stdlib-js/stdlib/pull/9779) _(by Rohit R Bhat)_
-   [`2141b2f`](https://github.com/stdlib-js/stdlib/commit/2141b2f3469ee6e013716201f8e39e083d3676d3) - **bench:** update random value generation [(#9780)](https://github.com/stdlib-js/stdlib/pull/9780) _(by Harsh Yadav)_
-   [`960af8f`](https://github.com/stdlib-js/stdlib/commit/960af8f193a0e7eaa20215e8ae231f943e825366) - **bench:** update random value generation [(#9781)](https://github.com/stdlib-js/stdlib/pull/9781) _(by Harsh Yadav)_
-   [`99d0a3c`](https://github.com/stdlib-js/stdlib/commit/99d0a3c95c5bbf6f2b0d3f8b6b0648bee9ef310b) - **bench:** update random value generation [(#9782)](https://github.com/stdlib-js/stdlib/pull/9782) _(by Harsh Yadav)_
-   [`610a4d0`](https://github.com/stdlib-js/stdlib/commit/610a4d02b5171f87c334c586160a1b159d8de7ee) - **bench:** update random value generation [(#9783)](https://github.com/stdlib-js/stdlib/pull/9783) _(by Harsh Yadav)_
-   [`b71d961`](https://github.com/stdlib-js/stdlib/commit/b71d961f103c018065390d2db1118c292be181fa) - **bench:** refactor to use string interpolation in `stats/base/dists/rayleigh/stdev` [(#9788)](https://github.com/stdlib-js/stdlib/pull/9788) _(by Bhargav Dabhade)_
-   [`ebcc5cd`](https://github.com/stdlib-js/stdlib/commit/ebcc5cd5aa8cca5f5825f6720b6c9573c0daff48) - **test:** replace `math-assert` with `float16-assert` [(#9789)](https://github.com/stdlib-js/stdlib/pull/9789) _(by Lokesh Ranjan)_
-   [`b44c340`](https://github.com/stdlib-js/stdlib/commit/b44c3408ddfda03b8a06c4042818bc5d9283c713) - **test:** replace `math-assert` with `float16-assert` [(#9790)](https://github.com/stdlib-js/stdlib/pull/9790) _(by Lokesh Ranjan)_
-   [`d45387d`](https://github.com/stdlib-js/stdlib/commit/d45387d1f3fdfa5d217c1e6a6ee2f75fba4f4bd7) - **docs:** update `blas/ext/base/ndarray` TypeScript declaration example code [(#9793)](https://github.com/stdlib-js/stdlib/pull/9793) _(by stdlib-bot)_
-   [`8107f89`](https://github.com/stdlib-js/stdlib/commit/8107f890aa2789811bc8b1e8448dd79f8eb42ab8) - **test:** replace math-assert with float16-assert for `to-float64` [(#9799)](https://github.com/stdlib-js/stdlib/pull/9799) _(by Lokesh Ranjan)_
-   [`86031ac`](https://github.com/stdlib-js/stdlib/commit/86031ace3c539a7bc339082990d9896abde895d4) - **chore:** fix JavaScript lint errors [(#9801)](https://github.com/stdlib-js/stdlib/pull/9801) _(by Suyash Pathak)_
-   [`92a0acc`](https://github.com/stdlib-js/stdlib/commit/92a0acc04033b0feb7113d04b6ade7ab1ebbc406) - **bench:** update random value generation [(#9802)](https://github.com/stdlib-js/stdlib/pull/9802) _(by Harsh Yadav)_
-   [`f8d3ce2`](https://github.com/stdlib-js/stdlib/commit/f8d3ce2b1a1be97a9706ca05559ab384e2587c54) - **docs:** update REPL namespace documentation [(#9795)](https://github.com/stdlib-js/stdlib/pull/9795) _(by stdlib-bot)_
-   [`a76d474`](https://github.com/stdlib-js/stdlib/commit/a76d474ab4fa9b2d936d21f9b9aca714b1349ff4) - **docs:** update `math/base/special` TypeScript declaration example code [(#9794)](https://github.com/stdlib-js/stdlib/pull/9794) _(by stdlib-bot)_
-   [`be2d13e`](https://github.com/stdlib-js/stdlib/commit/be2d13ea3b0b13e51fbc9a51a0788b03d1eb3618) - **chore:** fix JavaScript lint errors [(#9796)](https://github.com/stdlib-js/stdlib/pull/9796) _(by 가은 정)_
-   [`b3348f7`](https://github.com/stdlib-js/stdlib/commit/b3348f7d884b3e4aaf5927b008405c0296d5c9b6) - **test:** replace math-assert with float16-assert for `from-binary-string` [(#9798)](https://github.com/stdlib-js/stdlib/pull/9798) _(by Lokesh Ranjan)_
-   [`0472076`](https://github.com/stdlib-js/stdlib/commit/04720767c484e6277ad9411dff3dc5a116c31378) - **docs:** remove duplicated words in documentation and comments _(by Philipp Burckhardt)_
-   [`57ab662`](https://github.com/stdlib-js/stdlib/commit/57ab662159582de03be649f2414066a5387b8fd2) - **docs:** update description in `object/deep-set` [(#9735)](https://github.com/stdlib-js/stdlib/pull/9735) _(by Neeraj Pathak, Athan Reines)_
-   [`aaac825`](https://github.com/stdlib-js/stdlib/commit/aaac825c751f8ffc88d9d45e3e44f06bb36e297c) - **bench:** fix assertions _(by Athan Reines)_
-   [`6544e40`](https://github.com/stdlib-js/stdlib/commit/6544e40467b59c16865cd47427a9c01861a351b4) - **fix:** inline constant value _(by Athan Reines)_
-   [`4418e62`](https://github.com/stdlib-js/stdlib/commit/4418e626e0a3ec318b6451f4e3b3397b0d43c6f2) - **test:** fix broken tests _(by Athan Reines)_
-   [`4ae9a8a`](https://github.com/stdlib-js/stdlib/commit/4ae9a8a3077bbd8ace12af0e8be28dc750d122e0) - **chore:** clean-up _(by Athan Reines)_
-   [`c729420`](https://github.com/stdlib-js/stdlib/commit/c7294205a503ea3e9a37d1588b2aea4e12331aa6) - **chore:** clean-up _(by Athan Reines)_
-   [`a1fbf46`](https://github.com/stdlib-js/stdlib/commit/a1fbf4635c30c28ed3c8044ded17640bc877ca0d) - **fix:** require `sigma` be greater than zero _(by Athan Reines)_
-   [`7b347fa`](https://github.com/stdlib-js/stdlib/commit/7b347facd7397468a643699e102d2c3b6e379198) - **style:** resolve lint failure _(by Athan Reines)_
-   [`612180d`](https://github.com/stdlib-js/stdlib/commit/612180d3f3bdb24cdb8d4c6a3882ce85ba309dac) - **chore:** clean-up _(by Athan Reines)_
-   [`c47b2ba`](https://github.com/stdlib-js/stdlib/commit/c47b2ba406b1466b6c477445a598138b6e1ba6cc) - **chore:** clean-up _(by Athan Reines)_
-   [`52f3b09`](https://github.com/stdlib-js/stdlib/commit/52f3b09939070e38ef2ef12d8625afe03b6180e1) - **style:** add empty line _(by Athan Reines)_
-   [`1a6a202`](https://github.com/stdlib-js/stdlib/commit/1a6a20298bc6eaf5f2dc9607994f2a9b19fb1ff5) - **chore:** clean-up _(by Athan Reines)_
-   [`af1b1d0`](https://github.com/stdlib-js/stdlib/commit/af1b1d09c7e06a87d1eecd4c7ac5becfedf05d27) - **chore:** clean-up _(by Athan Reines)_
-   [`7f68fc4`](https://github.com/stdlib-js/stdlib/commit/7f68fc4aa254ea41b4d104041ff513239f104ba3) - **feat:** add `math/base/special/atanhf` [(#9514)](https://github.com/stdlib-js/stdlib/pull/9514) _(by Harsh Yadav, Karan Anand, Philipp Burckhardt)_
-   [`72af2aa`](https://github.com/stdlib-js/stdlib/commit/72af2aacb1ff59c6e96de88b5994790ca756aca4) - **chore:** fix spelling errors in `array` [(#9768)](https://github.com/stdlib-js/stdlib/pull/9768) _(by Shubham, Philipp Burckhardt)_
-   [`242c076`](https://github.com/stdlib-js/stdlib/commit/242c076de549632a025fe3bc519fbf1a5d46be7a) - **feat:** add `stats/base/dists/halfnormal/mean` [(#9613)](https://github.com/stdlib-js/stdlib/pull/9613) _(by Shubham)_
-   [`b18cbc4`](https://github.com/stdlib-js/stdlib/commit/b18cbc48334f3a417ea68d706df69b683b7ad20c) - **docs:** improve doctests for complex number instances in `math/base/special/cexp` [(#9769)](https://github.com/stdlib-js/stdlib/pull/9769) _(by Vishal Gaikwad)_
-   [`28c9d60`](https://github.com/stdlib-js/stdlib/commit/28c9d605d7fd1fd3c60a471d950b8553faf5f51f) - **docs:** update REPL namespace documentation [(#9774)](https://github.com/stdlib-js/stdlib/pull/9774) _(by stdlib-bot, Philipp Burckhardt)_
-   [`089d872`](https://github.com/stdlib-js/stdlib/commit/089d872ce2b44fc51d5d58700a518214f18a6a48) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dmskrange` [(#9749)](https://github.com/stdlib-js/stdlib/pull/9749) _(by Vishal Gaikwad)_
-   [`bf8af22`](https://github.com/stdlib-js/stdlib/commit/bf8af2283026f8ba57f0df6647e28e619887e3ca) - **bench:** update random value generation [(#9764)](https://github.com/stdlib-js/stdlib/pull/9764) _(by Harsh Yadav)_
-   [`872403f`](https://github.com/stdlib-js/stdlib/commit/872403fdf92d939ae463a63a6a921ca65d8387fd) - **bench:** update random value generation [(#9765)](https://github.com/stdlib-js/stdlib/pull/9765) _(by Harsh Yadav)_
-   [`8da46ee`](https://github.com/stdlib-js/stdlib/commit/8da46ee80a830f024f0b347b84e48e239b9eaee9) - **docs:** improve doctests for complex number instances in `math/base/special/cfloor` [(#9766)](https://github.com/stdlib-js/stdlib/pull/9766) _(by Vishal Gaikwad)_
-   [`16e4fd3`](https://github.com/stdlib-js/stdlib/commit/16e4fd3d3f18326c2d1a1e46d4cca60a2afad037) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dnanmeanpw` [(#9770)](https://github.com/stdlib-js/stdlib/pull/9770) _(by Vishal Gaikwad)_
-   [`267b6c4`](https://github.com/stdlib-js/stdlib/commit/267b6c4821ff03378a33888a3fc83330de7a660d) - **docs:** improve doctests for ndarray instances in `ndarray/dcusum` [(#9772)](https://github.com/stdlib-js/stdlib/pull/9772) _(by Diyan)_
-   [`e21e6df`](https://github.com/stdlib-js/stdlib/commit/e21e6dfa62d160bd43b2c282b136021085e9d45a) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dmean` [(#9773)](https://github.com/stdlib-js/stdlib/pull/9773) _(by Bhargav Dabhade)_
-   [`5b02960`](https://github.com/stdlib-js/stdlib/commit/5b0296021280236d1e98e0d2c6d2082eb4ebb47d) - **bench:** update random value generation [(#9737)](https://github.com/stdlib-js/stdlib/pull/9737) _(by Harsh Yadav)_
-   [`5e9a7cd`](https://github.com/stdlib-js/stdlib/commit/5e9a7cdd0bc9d07a331dfb72a74adc96b14b815c) - **bench:** update random value generation [(#9738)](https://github.com/stdlib-js/stdlib/pull/9738) _(by Harsh Yadav)_
-   [`a6b5609`](https://github.com/stdlib-js/stdlib/commit/a6b5609b1e8e92ec33fda5874e3c03c9e3e571c6) - **bench:** update random value generation [(#9745)](https://github.com/stdlib-js/stdlib/pull/9745) _(by Harsh Yadav)_
-   [`e5d2034`](https://github.com/stdlib-js/stdlib/commit/e5d203481f08ab2ecbdc7a4dbfe36462736cb7e7) - **bench:** update random value generation [(#9746)](https://github.com/stdlib-js/stdlib/pull/9746) _(by Harsh Yadav)_
-   [`0bf02be`](https://github.com/stdlib-js/stdlib/commit/0bf02be23ebbde03611a294ffab98c55ca770000) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dnanmax` [(#9750)](https://github.com/stdlib-js/stdlib/pull/9750) _(by Vishal Gaikwad)_
-   [`0a326f9`](https://github.com/stdlib-js/stdlib/commit/0a326f9f502b6d12dcc058ee92774b8f937b5840) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dnanmaxabs` [(#9751)](https://github.com/stdlib-js/stdlib/pull/9751) _(by Vishal Gaikwad)_
-   [`e0ab0b1`](https://github.com/stdlib-js/stdlib/commit/e0ab0b1c2933b865aa5302ae60b4bc22bc0d4a39) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dnanmean` [(#9752)](https://github.com/stdlib-js/stdlib/pull/9752) _(by Vishal Gaikwad)_
-   [`a0f0513`](https://github.com/stdlib-js/stdlib/commit/a0f05135e37f5343ba7870b16e124ff2d642643d) - **chore:** fix EditorConfig lint errors [(#9755)](https://github.com/stdlib-js/stdlib/pull/9755) _(by Divyanshu)_
-   [`eee0e09`](https://github.com/stdlib-js/stdlib/commit/eee0e097b23ead16e0933da53a9a1c40dc5b713e) - **docs:** remove extra empty line [(#9756)](https://github.com/stdlib-js/stdlib/pull/9756) _(by stdlib-bot)_
-   [`c9e2fc3`](https://github.com/stdlib-js/stdlib/commit/c9e2fc31d0016bd526c33ca8b3eefb7a6999fb2e) - **docs:** update `ndarray` TypeScript declarations [(#9757)](https://github.com/stdlib-js/stdlib/pull/9757) _(by stdlib-bot)_
-   [`359927e`](https://github.com/stdlib-js/stdlib/commit/359927e885c436eec620032dd44ede85b96ab11b) - **docs:** update REPL namespace documentation [(#9758)](https://github.com/stdlib-js/stdlib/pull/9758) _(by stdlib-bot, Philipp Burckhardt)_
-   [`3b73da5`](https://github.com/stdlib-js/stdlib/commit/3b73da5a3793534fa08f009722a98f96c61b0314) - **docs:** update related packages sections [(#9732)](https://github.com/stdlib-js/stdlib/pull/9732) _(by stdlib-bot, Athan Reines)_
-   [`01c8ec0`](https://github.com/stdlib-js/stdlib/commit/01c8ec0123460ecfe8cd001e9f3cc2a67ff5b971) - **chore:** fix JavaScript lint errors [(#8565)](https://github.com/stdlib-js/stdlib/pull/8565) _(by kaushal-kumar-it)_
-   [`55a4c2f`](https://github.com/stdlib-js/stdlib/commit/55a4c2f90ee136423bf8d282893fdf6a3ba805ef) - **feat:** add `blas/ext/base/drsskbn` [(#9013)](https://github.com/stdlib-js/stdlib/pull/9013) _(by Nakul Krishnakumar, stdlib-bot, Athan Reines, Philipp Burckhardt)_
-   [`11560ee`](https://github.com/stdlib-js/stdlib/commit/11560ee7b8f8bc2876ec2edb35d6b880247eda5e) - **chore:** clean-up _(by Athan Reines)_
-   [`388fbd3`](https://github.com/stdlib-js/stdlib/commit/388fbd3b0145683c9a1eed07884d481552fc58d9) - **style:** remove empty line and reorder declarations _(by Athan Reines)_
-   [`eb06ec9`](https://github.com/stdlib-js/stdlib/commit/eb06ec9ef3065afe65255cac5d792ab2e21ba570) - **docs:** update examples _(by Athan Reines)_
-   [`046aa27`](https://github.com/stdlib-js/stdlib/commit/046aa2706a8234829cc81483d0dcd3d21867258c) - **refactor:** update require path _(by Athan Reines)_
-   [`3bcebe9`](https://github.com/stdlib-js/stdlib/commit/3bcebe9121e353676f8bfcb1d0f5870dc6d74146) - **refactor:** update require path _(by Athan Reines)_
-   [`e2c03c0`](https://github.com/stdlib-js/stdlib/commit/e2c03c048787bde4a01ed8b6968ea6437e9e652a) - **docs:** improve doctests for complex number instances in `ndarray/base/unary` [(#8999)](https://github.com/stdlib-js/stdlib/pull/8999) _(by Aryan kumar, Athan Reines)_
-   [`51f5eea`](https://github.com/stdlib-js/stdlib/commit/51f5eea4350c3aff97620bda4ff3066935c23e3f) - **docs:** improve doctests for ndarray instances in `ndarray/some-by` [(#9410)](https://github.com/stdlib-js/stdlib/pull/9410) _(by kaushal-kumar-it, Athan Reines)_
-   [`571b88f`](https://github.com/stdlib-js/stdlib/commit/571b88f7e7b93c3578efc017cb8e3bd9b6b99954) - **docs:** improve doctests for ndarray instances in `ndarray/map` [(#9676)](https://github.com/stdlib-js/stdlib/pull/9676) _(by Shreelaxmi Hegde, Athan Reines)_
-   [`069d813`](https://github.com/stdlib-js/stdlib/commit/069d81355ab0d2bf36773bbfd1ed1bc90ebaccb1) - **feat:** add `stats/base/ndarray/dmeanstdev` [(#8525)](https://github.com/stdlib-js/stdlib/pull/8525) _(by Sachin Pangal, Athan Reines, stdlib-bot)_
-   [`85c8240`](https://github.com/stdlib-js/stdlib/commit/85c82409c5230249613943f9693ca0e8a19f5500) - **feat:** add `stats/base/dists/halfnormal/stdev` [(#9714)](https://github.com/stdlib-js/stdlib/pull/9714) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`19d5fc4`](https://github.com/stdlib-js/stdlib/commit/19d5fc4f36db513023e981a90103c9718eea59ff) - **feat:** add `blas/ext/base/gsort` [(#9712)](https://github.com/stdlib-js/stdlib/pull/9712) _(by Muhammad Haris, Athan Reines)_
-   [`b1ccc8c`](https://github.com/stdlib-js/stdlib/commit/b1ccc8cfa3a936af09b78f992d16e5e9e0fc3cad) - **docs:** remove note _(by Athan Reines)_
-   [`8b93c8d`](https://github.com/stdlib-js/stdlib/commit/8b93c8d51432c3ceb2a41f80bda77f77021e021e) - **feat:** update `random/tools` TypeScript declarations [(#9718)](https://github.com/stdlib-js/stdlib/pull/9718) _(by stdlib-bot)_
-   [`ef9c1b0`](https://github.com/stdlib-js/stdlib/commit/ef9c1b0b52ac28c95221d46d7cb0e4165343f893) - **feat:** update `random` TypeScript declarations [(#9717)](https://github.com/stdlib-js/stdlib/pull/9717) _(by stdlib-bot)_
-   [`2cdca3d`](https://github.com/stdlib-js/stdlib/commit/2cdca3d0e0b00fd1c1cc5a46a8e8f367fceb9c3d) - **remove:** remove `utils/deep-set` _(by Neeraj Pathak)_
-   [`fb171e3`](https://github.com/stdlib-js/stdlib/commit/fb171e313f8973bd4cd7d873f89f8b248b2cf14e) - **refactor:** update paths _(by Neeraj Pathak)_
-   [`1a7afed`](https://github.com/stdlib-js/stdlib/commit/1a7afedb20f93966a643171629dac8620772219c) - **remove:** remove `deepSet` from namespace _(by Neeraj Pathak)_
-   [`2e20261`](https://github.com/stdlib-js/stdlib/commit/2e202614b34a0dedadc99d69ae8516d2f2524710) - **feat:** add `object/deep-set` _(by Neeraj Pathak)_
-   [`c8781bb`](https://github.com/stdlib-js/stdlib/commit/c8781bb6f4f9745c8abd24b3b67ea7ba7aee8f78) - **feat:** add `stats/strided/nanmskmidrange` [(#9417)](https://github.com/stdlib-js/stdlib/pull/9417) _(by Sachin Pangal, Philipp Burckhardt, stdlib-bot)_
-   [`3e81841`](https://github.com/stdlib-js/stdlib/commit/3e81841c3790593fb3b7e85e7cfdc41680ed67be) - **bench:** update random value generation [(#9727)](https://github.com/stdlib-js/stdlib/pull/9727) _(by Harsh Yadav)_
-   [`efd9272`](https://github.com/stdlib-js/stdlib/commit/efd92729d0fe46c08c4e0f647fb5a8dd5d713510) - **bench:** update random value generation [(#9728)](https://github.com/stdlib-js/stdlib/pull/9728) _(by Harsh Yadav)_
-   [`a7ff263`](https://github.com/stdlib-js/stdlib/commit/a7ff263ba2b391497325f42217dc89386ec6012e) - **feat:** add `stats/base/ndarray/variancewd` [(#9634)](https://github.com/stdlib-js/stdlib/pull/9634) _(by Divyanshu, stdlib-bot)_
-   [`24c8448`](https://github.com/stdlib-js/stdlib/commit/24c84489858238aac982a4560b69a50634e71c60) - **chore:** fix JavaScript lint errors [(#9719)](https://github.com/stdlib-js/stdlib/pull/9719) _(by Shubham)_
-   [`709563c`](https://github.com/stdlib-js/stdlib/commit/709563c0d7337b5c0632d1988fb263cf39305f86) - **feat:** update `ndarray/base` TypeScript declarations [(#9716)](https://github.com/stdlib-js/stdlib/pull/9716) _(by stdlib-bot)_
-   [`6aee8e2`](https://github.com/stdlib-js/stdlib/commit/6aee8e232a2cebd57d5246d76ffe08e67941c0a4) - **docs:** move content to notes _(by Athan Reines)_
-   [`93e0c79`](https://github.com/stdlib-js/stdlib/commit/93e0c79faa246da751b6d7a640b5133fefad00f2) - **refactor:** return the input ndarray and update examples _(by Athan Reines)_
-   [`d5ddfc7`](https://github.com/stdlib-js/stdlib/commit/d5ddfc76b9363a57791e018c8435c33dd18a9bee) - **style:** remove empty line _(by Athan Reines)_
-   [`4026f6b`](https://github.com/stdlib-js/stdlib/commit/4026f6b885a77192ae147c6314c691db8d375f26) - **docs:** add references _(by Athan Reines)_
-   [`7c08a3d`](https://github.com/stdlib-js/stdlib/commit/7c08a3d15a919d79650bfc723822f0c3134e5277) - **docs:** add references _(by Athan Reines)_
-   [`1e61003`](https://github.com/stdlib-js/stdlib/commit/1e610036abcefe23cb1ea91e8c2308352323a47f) - **refactor:** remove unreachable path _(by Athan Reines)_
-   [`2f98c26`](https://github.com/stdlib-js/stdlib/commit/2f98c26670b9e7d7a57401953f85f0369ceff39d) - **refactor:** remove unreachable path _(by Athan Reines)_
-   [`18f7a74`](https://github.com/stdlib-js/stdlib/commit/18f7a74934a8c1d64798818b20e03c353f4db981) - **test:** fix supplied arguments in fifth argument tests _(by Philipp Burckhardt)_
-   [`5e66c6b`](https://github.com/stdlib-js/stdlib/commit/5e66c6b607019fb254c45fe269011000e81b862c) - **docs:** fix return annotation _(by Philipp Burckhardt)_
-   [`d3a2eff`](https://github.com/stdlib-js/stdlib/commit/d3a2eff2cb9c18a89c287cf65cb0498a5b5b6245) - **feat:** add `stats/strided/mskmaxabs` [(#9696)](https://github.com/stdlib-js/stdlib/pull/9696) _(by Sachin Pangal, Philipp Burckhardt)_
-   [`521f824`](https://github.com/stdlib-js/stdlib/commit/521f824a62e2f5b14db1022e760c88f0fffdf0ad) - **feat:** add C implementation for `stats/base/dists/erlang/mgf` [(#8754)](https://github.com/stdlib-js/stdlib/pull/8754) _(by Neeraj Pathak, Philipp Burckhardt, stdlib-bot)_
-   [`afa33d2`](https://github.com/stdlib-js/stdlib/commit/afa33d21dadcaf449b9950ea9ec30a12f4596738) - **docs:** update examples [(#9700)](https://github.com/stdlib-js/stdlib/pull/9700) _(by stdlib-bot)_
-   [`a3ddcf5`](https://github.com/stdlib-js/stdlib/commit/a3ddcf5aeb332dd504ec46745807dcdd6d52474e) - **docs:** update REPL namespace documentation [(#9701)](https://github.com/stdlib-js/stdlib/pull/9701) _(by stdlib-bot)_
-   [`e35173c`](https://github.com/stdlib-js/stdlib/commit/e35173c604edc492ad422e05948fbc4352f40be7) - **docs:** update examples _(by Athan Reines)_
-   [`4a75382`](https://github.com/stdlib-js/stdlib/commit/4a75382aef854b53f9629a570225662723fb83cb) - **docs:** update README _(by Athan Reines)_
-   [`55a2f26`](https://github.com/stdlib-js/stdlib/commit/55a2f260629b5dca631ea8176ce8c3c1b0b78c8f) - **build:** add scaffold for ternary random packages _(by Athan Reines)_
-   [`cfab032`](https://github.com/stdlib-js/stdlib/commit/cfab0325f798bcf48334e36d307ee33330824aff) - **feat:** add `triangular` to namespace _(by Athan Reines)_
-   [`132493e`](https://github.com/stdlib-js/stdlib/commit/132493e15add93ab5e56eb89c7f42ec08f06c402) - **feat:** add `random/triangular` _(by Athan Reines)_
-   [`a064afe`](https://github.com/stdlib-js/stdlib/commit/a064afe74bb89a7f835fafc63d16bb446e9f21e5) - **feat:** add `hypergeometric` to namespace _(by Athan Reines)_
-   [`62872f6`](https://github.com/stdlib-js/stdlib/commit/62872f64e1e235f44e063b81aea3dd721c4afedc) - **feat:** add `random/hypergeometric` _(by Athan Reines)_
-   [`30ca17e`](https://github.com/stdlib-js/stdlib/commit/30ca17eb7931a0065e3ed1ef7fc4742316449106) - **docs:** remove extraneous comma in `random/frechet` function signature _(by Philipp Burckhardt)_
-   [`cab5bb0`](https://github.com/stdlib-js/stdlib/commit/cab5bb08a4db8727097c61b4edb39c88137273eb) - **feat:** add `frechet` to namespace _(by Athan Reines)_
-   [`73344ab`](https://github.com/stdlib-js/stdlib/commit/73344abe4ac57ef5a27e6879e4274882caf596d6) - **feat:** add `random/frechet` _(by Athan Reines)_
-   [`fe91f02`](https://github.com/stdlib-js/stdlib/commit/fe91f02a931515c8dabe9e84a50fb9d124822111) - **feat:** add `ternaryFactory` to namespace _(by Athan Reines)_
-   [`244addc`](https://github.com/stdlib-js/stdlib/commit/244addce1a75c839b48065f9ebf7f763163e8723) - **feat:** add `ternary` to namespace _(by Athan Reines)_
-   [`36bb700`](https://github.com/stdlib-js/stdlib/commit/36bb70027e01d79ff0b0a42847df67deb0e22ce5) - **feat:** add `random/tools/ternary-factory` _(by Athan Reines)_
-   [`b18f5a0`](https://github.com/stdlib-js/stdlib/commit/b18f5a066b3725837f844bc6aa57a15831267093) - **style:** resolve lint failure _(by Athan Reines)_
-   [`4b0f789`](https://github.com/stdlib-js/stdlib/commit/4b0f78943f49adfc5e2867c951496ffea6b0702b) - **style:** resolve lint failure _(by Athan Reines)_
-   [`41a6983`](https://github.com/stdlib-js/stdlib/commit/41a6983e5a9c2d152009806cf6614478d9e1d7f2) - **style:** resolve lint failure _(by Athan Reines)_
-   [`c3ece9a`](https://github.com/stdlib-js/stdlib/commit/c3ece9ace946b87712312c74eb171252644fa0f4) - **style:** resolve lint failure _(by Athan Reines)_
-   [`bb15dcc`](https://github.com/stdlib-js/stdlib/commit/bb15dcc572a4a67f7e7450919e7a0e3e915988dc) - **feat:** add `random/tools/ternary` _(by Athan Reines)_
-   [`64fa79c`](https://github.com/stdlib-js/stdlib/commit/64fa79c79b2aa6a98404676be3c05b5048684011) - **style:** disable lint rule _(by Athan Reines)_
-   [`fdfdf13`](https://github.com/stdlib-js/stdlib/commit/fdfdf139a4f787dd67d5cdcf94130bf6469c92a2) - **docs:** fix example to ensure valid type promotion _(by Athan Reines)_
-   [`f738a37`](https://github.com/stdlib-js/stdlib/commit/f738a37c1cc32a740c7ecc4cbc7982eca26f67d2) - **feat:** add `ternaryBlockSize` to namespace _(by Athan Reines)_
-   [`b490370`](https://github.com/stdlib-js/stdlib/commit/b49037059ac498f7e864cb83f0cf59b3feb3b459) - **feat:** add `ternaryLoopOrder` to namespace _(by Athan Reines)_
-   [`88e4096`](https://github.com/stdlib-js/stdlib/commit/88e4096e8e5941fecc15ef2fd2d5b27e91d69233) - **feat:** add `ternary` to namespace _(by Athan Reines)_
-   [`5fbedba`](https://github.com/stdlib-js/stdlib/commit/5fbedba2f71e2c6a20c33f0de574d0060536c0f5) - **feat:** add `ternaryOutputDataType` to namespace _(by Athan Reines)_
-   [`9d38a93`](https://github.com/stdlib-js/stdlib/commit/9d38a9324e99a3a00f733b30a37510e8d1e4b6a4) - **feat:** add `ndarray/base/ternary-output-dtype` _(by Athan Reines)_
-   [`6d4630b`](https://github.com/stdlib-js/stdlib/commit/6d4630be9a3d2d65b464ca289db0c8db452466f2) - **docs:** update to support data type objects and be opaque regarding return value _(by Athan Reines)_
-   [`4f2cdaa`](https://github.com/stdlib-js/stdlib/commit/4f2cdaafcee4670fb5b1b5f562d445d7367c8404) - **docs:** update to support data type objects and be opaque regarding return value _(by Athan Reines)_
-   [`b1a1b7f`](https://github.com/stdlib-js/stdlib/commit/b1a1b7fe3c8b93365c70632b726d6797d2af4438) - **feat:** add support for ndarray data type objects and update existing type definitions _(by Athan Reines)_
-   [`c6e2443`](https://github.com/stdlib-js/stdlib/commit/c6e24436d222d609c3ea153fd81f31e1d16451bc) - **feat:** add `ndarray/base/ternary` [(#9566)](https://github.com/stdlib-js/stdlib/pull/9566) _(by Muhammad Haris, Athan Reines)_
-   [`0e64df0`](https://github.com/stdlib-js/stdlib/commit/0e64df09f90ee261c1bf2dc56ae5ad3c1705b120) - **docs:** update examples [(#9688)](https://github.com/stdlib-js/stdlib/pull/9688) _(by stdlib-bot)_
-   [`38631fc`](https://github.com/stdlib-js/stdlib/commit/38631fc2f158f3334031ae6a8ac31d0307d46159) - **feat:** add `blas/ext/base/dsort` [(#9684)](https://github.com/stdlib-js/stdlib/pull/9684) _(by Muhammad Haris, Athan Reines)_
-   [`1216f34`](https://github.com/stdlib-js/stdlib/commit/1216f342bddf49075c7b29c30bf145f413171344) - **test:** visually group require statements _(by Athan Reines)_
-   [`7aec76a`](https://github.com/stdlib-js/stdlib/commit/7aec76a713e908d3489003144b7d1e470b62745e) - **refactor:** ensure contiguous array allocation _(by Athan Reines)_
-   [`e882812`](https://github.com/stdlib-js/stdlib/commit/e882812a788d6648dd848e9e5667a11a1878bb3d) - **docs:** update REPL namespace documentation [(#9689)](https://github.com/stdlib-js/stdlib/pull/9689) _(by stdlib-bot, Philipp Burckhardt)_
-   [`7d17660`](https://github.com/stdlib-js/stdlib/commit/7d17660137c611ad174f81df229a31f4d3080cbc) - **chore:** fix JavaScript lint errors [(#9690)](https://github.com/stdlib-js/stdlib/pull/9690) _(by Divyanshu)_
-   [`c774606`](https://github.com/stdlib-js/stdlib/commit/c77460647fe72de99efa50c75cff73ce3285a50f) - **remove:** remove `utils/deep-get` _(by Neeraj Pathak)_
-   [`dfee33b`](https://github.com/stdlib-js/stdlib/commit/dfee33b1f8c6ae3b28465f81a0dafbd50366f9f0) - **refactor:** update paths _(by Neeraj Pathak)_
-   [`ff350f3`](https://github.com/stdlib-js/stdlib/commit/ff350f3aa902afbd7dad2e32c03c3f0d5ced798f) - **remove:** remove `deepGet` from namespace _(by Neeraj Pathak)_
-   [`bfbb4d1`](https://github.com/stdlib-js/stdlib/commit/bfbb4d12bfeed5c11da8384a5ab94935259eec82) - **feat:** add `object/deep-get` _(by Neeraj Pathak)_
-   [`f477420`](https://github.com/stdlib-js/stdlib/commit/f477420675c7c2b4c00729e0ed7ef75d4e1cdb11) - **test:** add tests to `ndarray/count-if` [(#9671)](https://github.com/stdlib-js/stdlib/pull/9671) _(by Muhammad Haris, Athan Reines)_
-   [`892be43`](https://github.com/stdlib-js/stdlib/commit/892be43dfec83129f37877bae20fff27f73f8cf2) - **test:** fix description _(by Athan Reines)_
-   [`2699f38`](https://github.com/stdlib-js/stdlib/commit/2699f38dd49d6686d3104a9100b2c05fe8d537f2) - **docs:** improve doctests for ndarray instances in `ndarray/filter-map` [(#9663)](https://github.com/stdlib-js/stdlib/pull/9663) _(by Shreelaxmi Hegde, Athan Reines)_
-   [`0376e06`](https://github.com/stdlib-js/stdlib/commit/0376e06fa1a8c4aebe3bfe8f708136f86432f9eb) - **docs:** improve doctests for ndarray instances in `ndarray/fliplr` [(#9672)](https://github.com/stdlib-js/stdlib/pull/9672) _(by Shreelaxmi Hegde)_
-   [`6a08125`](https://github.com/stdlib-js/stdlib/commit/6a0812589be9a47f48809b7223377399c24ba272) - **docs:** improve doctests for ndarray instances in `ndarray/flipud` [(#9673)](https://github.com/stdlib-js/stdlib/pull/9673) _(by Shreelaxmi Hegde)_
-   [`2f7e474`](https://github.com/stdlib-js/stdlib/commit/2f7e474c405543951d4104d10b1e186ead3a68ee) - **test:** add tests to `ndarray/count-falsy` [(#9670)](https://github.com/stdlib-js/stdlib/pull/9670) _(by Muhammad Haris)_
-   [`141399c`](https://github.com/stdlib-js/stdlib/commit/141399ca349aa5d998ba9d5df2e46f4ceb316210) - **docs:** improve doctests for ndarray instances in `ndarray/flatten-by` [(#9666)](https://github.com/stdlib-js/stdlib/pull/9666) _(by Shreelaxmi Hegde)_
-   [`bb5b731`](https://github.com/stdlib-js/stdlib/commit/bb5b7312bfd8a87b84615de701b8c1e132521e93) - **docs:** improve doctests for ndarray instances in `ndarray/flatten-from` [(#9668)](https://github.com/stdlib-js/stdlib/pull/9668) _(by Shreelaxmi Hegde)_
-   [`2035f34`](https://github.com/stdlib-js/stdlib/commit/2035f344a1a469278042b7532f034dc6119933b3) - **docs:** add function documentation _(by Athan Reines)_
-   [`caea326`](https://github.com/stdlib-js/stdlib/commit/caea3266d32a5b6deadd1b75747d5d88e08699d2) - **feat:** add `blas/ext/base/drss` [(#9647)](https://github.com/stdlib-js/stdlib/pull/9647) _(by Nakul Krishnakumar, Athan Reines)_
-   [`bfc8c3a`](https://github.com/stdlib-js/stdlib/commit/bfc8c3a7bcebf1a049c9e457ab440f540fd5c7a9) - **chore:** use one asterisk for license comment in TS files _(by Philipp Burckhardt)_
-   [`88f0620`](https://github.com/stdlib-js/stdlib/commit/88f06201ec78b8b5376ad685f92aa3d3135a3d59) - **feat:** add `stats/base/ndarray/sstdevwd` [(#9565)](https://github.com/stdlib-js/stdlib/pull/9565) _(by Divyanshu)_
-   [`3686f6f`](https://github.com/stdlib-js/stdlib/commit/3686f6f542397f4000ce69cd3f1e9f5052d68321) - **docs:** improve doctests for ndarray instances in `ndarray/flatten` [(#9665)](https://github.com/stdlib-js/stdlib/pull/9665) _(by Shreelaxmi Hegde)_
-   [`279f181`](https://github.com/stdlib-js/stdlib/commit/279f1817651a774f8d97f053529ac2bd94a94f91) - **docs:** update parameter name and description in `ndarray/base` TypeScript declaration  [(#9660)](https://github.com/stdlib-js/stdlib/pull/9660) _(by stdlib-bot)_
-   [`7169fdd`](https://github.com/stdlib-js/stdlib/commit/7169fdd88c02203cb5eb31969417c99bff24057f) - **docs:** update `ndarray` TypeScript declaration example code [(#9661)](https://github.com/stdlib-js/stdlib/pull/9661) _(by stdlib-bot)_
-   [`d2b039b`](https://github.com/stdlib-js/stdlib/commit/d2b039b4d16169fa7e6c43ebbbda7300c2391a74) - **docs:** update REPL namespace documentation [(#9662)](https://github.com/stdlib-js/stdlib/pull/9662) _(by stdlib-bot, Philipp Burckhardt)_
-   [`223666d`](https://github.com/stdlib-js/stdlib/commit/223666db0fdb0aba4b1390d470ccc826fdaf44ab) - **chore:** clean-up _(by Athan Reines)_
-   [`8019f5c`](https://github.com/stdlib-js/stdlib/commit/8019f5c04432ee29e3f16513dd29f3f4ed436346) - **feat:** add `stats/strided/distances/dcityblock` [(#9586)](https://github.com/stdlib-js/stdlib/pull/9586) _(by Nakul Krishnakumar, Athan Reines)_
-   [`b6d9f4d`](https://github.com/stdlib-js/stdlib/commit/b6d9f4d465b6a0ec5ceac8d3d5dda7aaa4c6d8c6) - **chore:** fix JavaScript lint errors [(#9659)](https://github.com/stdlib-js/stdlib/pull/9659) _(by Shreelaxmi Hegde, Athan Reines)_
-   [`426da6e`](https://github.com/stdlib-js/stdlib/commit/426da6ec175dfdb72a9435612069bd5e2819b194) - **test:** add tests to `ndarray/count-truthy` for complete test code coverage [(#9593)](https://github.com/stdlib-js/stdlib/pull/9593) _(by Muhammad Haris, Athan Reines)_
-   [`272fd1f`](https://github.com/stdlib-js/stdlib/commit/272fd1fc3c65386c4955ccfa39aa59adc812578a) - **docs:** update example to match text and supply missing argument in C code _(by Philipp Burckhardt)_
-   [`6f08c1e`](https://github.com/stdlib-js/stdlib/commit/6f08c1e408e4b75314ef3c9a175c91ed2a266eea) - **docs:** fix description _(by Philipp Burckhardt)_
-   [`1129c90`](https://github.com/stdlib-js/stdlib/commit/1129c90ea87de4910cd73e4dbfee2289a3a5dc16) - **style:** remove whitespace and update keywords _(by Athan Reines)_
-   [`4e8074a`](https://github.com/stdlib-js/stdlib/commit/4e8074a0fd574272817ba43ee2fa24fbb7431e43) - **feat:** add `number/float16/base/assert/is-positive-zero` [(#9643)](https://github.com/stdlib-js/stdlib/pull/9643) _(by Neeraj Pathak, Philipp Burckhardt)_
-   [`20e08f9`](https://github.com/stdlib-js/stdlib/commit/20e08f9e46bae5fdc67e1d0f7e635be8afa3d1fd) - **fix:** prevent deadlock on single-core systems and with empty arrays in `utils/parallel` [(#9597)](https://github.com/stdlib-js/stdlib/pull/9597) _(by Shivam Mittal, Athan Reines)_
-   [`4669c51`](https://github.com/stdlib-js/stdlib/commit/4669c51aa02b1d7d8c463e387df494f73c636587) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dmskmin` [(#9652)](https://github.com/stdlib-js/stdlib/pull/9652) _(by Vishal Gaikwad, Athan Reines)_
-   [`411353c`](https://github.com/stdlib-js/stdlib/commit/411353c97c756168a89eff9f5252ee32048819de) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dmskmax` [(#9650)](https://github.com/stdlib-js/stdlib/pull/9650) _(by Vishal Gaikwad, Athan Reines)_
-   [`3d8c416`](https://github.com/stdlib-js/stdlib/commit/3d8c4168a574f6940eaa978408c63542162558ba) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dminsorted` [(#9648)](https://github.com/stdlib-js/stdlib/pull/9648) _(by Vishal Gaikwad)_
-   [`76e16c8`](https://github.com/stdlib-js/stdlib/commit/76e16c836df4e881b5246c198433cc2170d11357) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dnanmeanpn` [(#9655)](https://github.com/stdlib-js/stdlib/pull/9655) _(by Bhargav Dabhade, Athan Reines)_
-   [`efec547`](https://github.com/stdlib-js/stdlib/commit/efec5470c54d62b675c8ca598fe352c7ac16a6cb) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dnanmeanwd` [(#9657)](https://github.com/stdlib-js/stdlib/pull/9657) _(by Bhargav Dabhade, Athan Reines)_
-   [`676581b`](https://github.com/stdlib-js/stdlib/commit/676581b4f1f4ffbece1ae5234a2e6ef1e8fca9f1) - **bench:** refactor to use string interpolation in `array/cartesian-power` [(#9653)](https://github.com/stdlib-js/stdlib/pull/9653) _(by Diyan)_
-   [`f36844d`](https://github.com/stdlib-js/stdlib/commit/f36844d1d51ef37e1934b6013481e39ef8052d09) - **feat:** add `blas/ext/base/drssbl` [(#8722)](https://github.com/stdlib-js/stdlib/pull/8722) _(by Nakul Krishnakumar, Athan Reines, stdlib-bot)_
-   [`a5a3d29`](https://github.com/stdlib-js/stdlib/commit/a5a3d29ccbc51f322d2f8d84608411e3ebce3d11) - **docs:** improve doctests for ndarray instances in `ndarray/filter` [(#9606)](https://github.com/stdlib-js/stdlib/pull/9606) _(by Harshit Verma, Athan Reines)_
-   [`1012150`](https://github.com/stdlib-js/stdlib/commit/1012150cdd393f4050502120b0123ed575dcd6de) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dmediansorted` [(#9604)](https://github.com/stdlib-js/stdlib/pull/9604) _(by Vishal Gaikwad, Athan Reines)_
-   [`75e4432`](https://github.com/stdlib-js/stdlib/commit/75e44322fd78e14954befe091e8890cc8a810076) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dmidrange` [(#9603)](https://github.com/stdlib-js/stdlib/pull/9603) _(by Vishal Gaikwad)_
-   [`5f66676`](https://github.com/stdlib-js/stdlib/commit/5f666765772650801c7ba6f73237c85bb67c1574) - **bench:** refactor to use dynamic memory allocation in `stats/strided/dminabs` [(#9605)](https://github.com/stdlib-js/stdlib/pull/9605) _(by Vishal Gaikwad)_
-   [`bfab153`](https://github.com/stdlib-js/stdlib/commit/bfab1532d8a54a05baac781a2913db458a1e8570) - **bench:** refactor to use string interpolation in `array/base/bifurcate-values-by` [(#9607)](https://github.com/stdlib-js/stdlib/pull/9607) _(by Bhargav Dabhade)_
-   [`4c079e0`](https://github.com/stdlib-js/stdlib/commit/4c079e04a6ed2aa27be8e42e599786bf8327f670) - **feat:** add `H_H` macro in `math/base/napi/unary` [(#9576)](https://github.com/stdlib-js/stdlib/pull/9576) _(by Neeraj Pathak, Athan Reines)_
-   [`abfb9e2`](https://github.com/stdlib-js/stdlib/commit/abfb9e2214268f3681deaf54b1d0a454dbe1e4b1) - **remove:** remove `utils/bifurcate-own` _(by Neeraj Pathak)_
-   [`c8bd14e`](https://github.com/stdlib-js/stdlib/commit/c8bd14eed3693ab50a341bdb9a24cf98cc64bf60) - **refactor:** update paths _(by Neeraj Pathak)_
-   [`2af3d97`](https://github.com/stdlib-js/stdlib/commit/2af3d9749b0aa0c5fe4c04f5e526e567b963e26a) - **remove:** remove `bifurcateOwn` from namespace _(by Neeraj Pathak)_
-   [`2e1dd2a`](https://github.com/stdlib-js/stdlib/commit/2e1dd2a67c285b42e70077e0214b982fe18a55a2) - **feat:** add `object/bifurcate-own` _(by Neeraj Pathak)_
-   [`63e3c0c`](https://github.com/stdlib-js/stdlib/commit/63e3c0c70c31fae2111b4dfb4141a3665bc0dea0) - **test:** add tests to `ndarray/find` [(#9311)](https://github.com/stdlib-js/stdlib/pull/9311) _(by Muhammad Haris, Athan Reines, stdlib-bot)_
-   [`582d828`](https://github.com/stdlib-js/stdlib/commit/582d8280f7d6f077f686db7348e3132971476939) - **test:** add tests _(by Athan Reines)_
-   [`59c9027`](https://github.com/stdlib-js/stdlib/commit/59c90279d6241a73c8d82fd92c49f64c4f068db7) - **test:** add tests _(by Athan Reines)_
-   [`26dfea9`](https://github.com/stdlib-js/stdlib/commit/26dfea9906df6cc05c0da7b331beb2f553911344) - **style:** fix line wrapping _(by Athan Reines)_
-   [`63a9af5`](https://github.com/stdlib-js/stdlib/commit/63a9af59c1d602d79ae593bb98346e991b0f2874) - **docs:** update descriptions _(by Athan Reines)_
-   [`8ea33d5`](https://github.com/stdlib-js/stdlib/commit/8ea33d58d9a5beb31e6023ceaf331fc4175c74fa) - **docs:** rename parameter _(by Athan Reines)_
-   [`5149a6b`](https://github.com/stdlib-js/stdlib/commit/5149a6b650b60568bd0df248c2a97a3d8ca2ca87) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`1749282`](https://github.com/stdlib-js/stdlib/commit/1749282903f4364994431735e440fa2c2973ee00) - **feat:** add `stats/base/ndarray/variancech` [(#9633)](https://github.com/stdlib-js/stdlib/pull/9633) _(by Divyanshu, stdlib-bot)_
-   [`2d6416a`](https://github.com/stdlib-js/stdlib/commit/2d6416add43fe03624335438d20fb293bf78405a) - **feat:** add `number/float16/base/assert/is-negative-zero` [(#9623)](https://github.com/stdlib-js/stdlib/pull/9623) _(by Neeraj Pathak)_
-   [`1aff763`](https://github.com/stdlib-js/stdlib/commit/1aff763c61863b7d737a699db89729d2bba0e1bc) - **feat:** add `ndarray/spread-dimensions` [(#9424)](https://github.com/stdlib-js/stdlib/pull/9424) _(by Muhammad Haris, Athan Reines)_
-   [`aebc415`](https://github.com/stdlib-js/stdlib/commit/aebc415cd7b1579ef8935576eb4fae94a4277846) - **feat:** add `number/float16/base/assert/is-nan` [(#9625)](https://github.com/stdlib-js/stdlib/pull/9625) _(by Lokesh Ranjan)_
-   [`9d53583`](https://github.com/stdlib-js/stdlib/commit/9d53583c9f82e1b2e5dc084849d98bd9c3214d45) - **test:** update descriptions _(by Athan Reines)_
-   [`bb3344f`](https://github.com/stdlib-js/stdlib/commit/bb3344fa8ee3aacb533b6d76531c9687bd7a7ef8) - **chore:** fix EditorConfig lint errors [(#9641)](https://github.com/stdlib-js/stdlib/pull/9641) _(by Shreelaxmi Hegde)_
-   [`3c567b6`](https://github.com/stdlib-js/stdlib/commit/3c567b634cf5e5fa5e31b64f94206db5b4a88133) - **feat:** update `ndarray/base` TypeScript declarations (#9640) [(#9640)](https://github.com/stdlib-js/stdlib/pull/9640) _(by stdlib-bot)_
-   [`ef3792c`](https://github.com/stdlib-js/stdlib/commit/ef3792ccdbdc29b705429f08d8be976f727f8ccf) - **docs:** update related packages sections [(#9639)](https://github.com/stdlib-js/stdlib/pull/9639) _(by stdlib-bot)_
-   [`483acba`](https://github.com/stdlib-js/stdlib/commit/483acba3dbcea263aa0014a2db41e1c073f8338b) - **feat:** add `ndarray/find-last` [(#8724)](https://github.com/stdlib-js/stdlib/pull/8724) _(by Muhammad Haris, Athan Reines, stdlib-bot)_
-   [`90021da`](https://github.com/stdlib-js/stdlib/commit/90021dae5b5a3b4fbeb5e2366c71b5ddf2095555) - **chore:** clean-up _(by Athan Reines)_
-   [`fd99657`](https://github.com/stdlib-js/stdlib/commit/fd99657f0da9706d3c1d7b03c5f9caf97069d3df) - **feat:** add `ndarray/prepend-singleton-dimensions` [(#9478)](https://github.com/stdlib-js/stdlib/pull/9478) _(by Muhammad Haris, Athan Reines)_
-   [`f475c84`](https://github.com/stdlib-js/stdlib/commit/f475c843a4b1579eef6533e464e4c16766d7ecdd) - **feat:** add writable parameter to `ndarray/base/expand-dimensions` [(#9476)](https://github.com/stdlib-js/stdlib/pull/9476) _(by Muhammad Haris, Athan Reines)_
-   [`5cddadf`](https://github.com/stdlib-js/stdlib/commit/5cddadf2f755a8e623ca132a6a0aa91bf6a51fdc) - **chore:** clean-up _(by Athan Reines)_
-   [`fb07e54`](https://github.com/stdlib-js/stdlib/commit/fb07e549179ee734beabf5c39c66db876cc959b5) - **chore:** clean-up _(by Athan Reines)_
-   [`056ece8`](https://github.com/stdlib-js/stdlib/commit/056ece8dfb301d321667f266232a4c9833f4380e) - **chore:** update meta data _(by Athan Reines)_
-   [`48ad5e6`](https://github.com/stdlib-js/stdlib/commit/48ad5e6cd965d673404c69e4b074c2bbb5ae5869) - **chore:** clean-up _(by Athan Reines)_
-   [`dafbda6`](https://github.com/stdlib-js/stdlib/commit/dafbda6d3b1b782596f643582a90c842026688aa) - **chore:** update to use correct type and match README.md _(by Philipp Burckhardt)_
-   [`a068c72`](https://github.com/stdlib-js/stdlib/commit/a068c72880b9f3757d8b00ec945eb4e9cba31a8b) - **feat:** add `math/base/special/roundnf` [(#9389)](https://github.com/stdlib-js/stdlib/pull/9389) _(by Aman Singh, Karan Anand, Philipp Burckhardt, stdlib-bot)_
-   [`c364b92`](https://github.com/stdlib-js/stdlib/commit/c364b92c5f5b23e2ba74a43436de24bf3b305d75) - **chore:** fix JavaScript lint errors [(#9616)](https://github.com/stdlib-js/stdlib/pull/9616) _(by Ishanth)_
-   [`ef0435b`](https://github.com/stdlib-js/stdlib/commit/ef0435b69f05fa6a8d0e7d4ee44c72e1ccff1dd9) - **feat:** add Wald distribution PDF [(#9324)](https://github.com/stdlib-js/stdlib/pull/9324) _(by Manit Roy)_
-   [`518339b`](https://github.com/stdlib-js/stdlib/commit/518339b9e202765284968c5bb40a458bf25c9425) - **chore:** remove extra empty line [(#9617)](https://github.com/stdlib-js/stdlib/pull/9617) _(by stdlib-bot)_
-   [`f8b7e2e`](https://github.com/stdlib-js/stdlib/commit/f8b7e2e47633d1ee11a9013521476a5dc6bca786) - **chore:** fix EditorConfig lint errors [(#9618)](https://github.com/stdlib-js/stdlib/pull/9618) _(by Divyanshu)_
-   [`da01e3d`](https://github.com/stdlib-js/stdlib/commit/da01e3d2071bb474ecef81e1d8ab07561f4b78f5) - **feat:** add `number/float16/base/sub` [(#9558)](https://github.com/stdlib-js/stdlib/pull/9558) _(by Lokesh Ranjan, Philipp Burckhardt)_
-   [`5301fb5`](https://github.com/stdlib-js/stdlib/commit/5301fb5c6146068494dfa645007e823aa0777f84) - **feat:** add `number/float16/base/assert/is-almost-equal` [(#9500)](https://github.com/stdlib-js/stdlib/pull/9500) _(by Neeraj Pathak, Philipp Burckhardt)_
-   [`92d23f5`](https://github.com/stdlib-js/stdlib/commit/92d23f56523bf43782063a7a00b4499502ac1c38) - **feat:** add Wald distribution mean [(#9502)](https://github.com/stdlib-js/stdlib/pull/9502) _(by Manit Roy, Philipp Burckhardt)_
-   [`040d8ec`](https://github.com/stdlib-js/stdlib/commit/040d8ecffb823cc3df4a8b11753241fc10e645b1) - **chore:** fix JavaScript lint errors [(#9437)](https://github.com/stdlib-js/stdlib/pull/9437) _(by Shubham)_
-   [`9f70c31`](https://github.com/stdlib-js/stdlib/commit/9f70c314356bb4f683d135d4af7ce28ec6b8ceb6) - **bench:** refactor to use string interpolation in `buffer/to-json` [(#9580)](https://github.com/stdlib-js/stdlib/pull/9580) _(by Vishal Gaikwad)_
-   [`8e05341`](https://github.com/stdlib-js/stdlib/commit/8e0534149457bd04a06ae3c59d726191e32a1dcf) - **chore:** clean-up _(by Athan Reines)_
-   [`cb09f58`](https://github.com/stdlib-js/stdlib/commit/cb09f5862f03c3056c8259164653940108068f30) - **feat:** add `math/base/special/fast/atanhf` [(#9046)](https://github.com/stdlib-js/stdlib/pull/9046) _(by Nakul Krishnakumar, Philipp Burckhardt, stdlib-bot)_
-   [`ff11bf4`](https://github.com/stdlib-js/stdlib/commit/ff11bf419afd29bd798e46fb6705b0e913bb80bb) - **chore:** add structured package data for `number/float32/base/div` [(#9547)](https://github.com/stdlib-js/stdlib/pull/9547) _(by Neeraj Pathak)_
-   [`2b51497`](https://github.com/stdlib-js/stdlib/commit/2b514972090db1f2361e3e932bdcee8bbcdedfb7) - **chore:** add structured package data for `number/float64/base/div` [(#9490)](https://github.com/stdlib-js/stdlib/pull/9490) _(by Neeraj Pathak)_
-   [`3b0e321`](https://github.com/stdlib-js/stdlib/commit/3b0e321d7fe014b56def3bf6a769ac2760ac67eb) - **bench:** refactor to use string interpolation in `buffer/from-buffer` [(#9578)](https://github.com/stdlib-js/stdlib/pull/9578) _(by Vishal Gaikwad)_
-   [`01e7efb`](https://github.com/stdlib-js/stdlib/commit/01e7efb049f30e3903d29a05b145966a9b75d909) - **bench:** refactor to use string interpolation in `buffer/from-string` [(#9579)](https://github.com/stdlib-js/stdlib/pull/9579) _(by Vishal Gaikwad)_
-   [`f6e662c`](https://github.com/stdlib-js/stdlib/commit/f6e662c42b347d90ab8e7e77130e8288b979dc6f) - **bench:** update random value generation [(#9584)](https://github.com/stdlib-js/stdlib/pull/9584) _(by Harsh Yadav)_
-   [`a7a77a7`](https://github.com/stdlib-js/stdlib/commit/a7a77a7ba28bc0f55275db3a77a0117f0679b317) - **test:** remove duplicate NaN test cases in normal mean [(#9588)](https://github.com/stdlib-js/stdlib/pull/9588) _(by Suyash Pathak)_
-   [`75552e8`](https://github.com/stdlib-js/stdlib/commit/75552e80fb02f81854f91d7361586a661d6b377e) - **bench:** update random value generation [(#9589)](https://github.com/stdlib-js/stdlib/pull/9589) _(by Harsh Yadav)_
-   [`b1ec70f`](https://github.com/stdlib-js/stdlib/commit/b1ec70f8a9d7a4a242cc4c2d5a8076c0db9b7ff3) - **bench:** update random value generation [(#9590)](https://github.com/stdlib-js/stdlib/pull/9590) _(by Harsh Yadav)_
-   [`2b29d0d`](https://github.com/stdlib-js/stdlib/commit/2b29d0d81075f3f545eb8e6bfe5a23c2baa3acca) - **bench:** refactor to use string interpolation in `dstructs/circular-buffer` [(#9591)](https://github.com/stdlib-js/stdlib/pull/9591) _(by Shubham)_
-   [`ef91291`](https://github.com/stdlib-js/stdlib/commit/ef912916813cb9e2efce497e31a44a92f82289c5) - **docs:** update REPL namespace documentation [(#9595)](https://github.com/stdlib-js/stdlib/pull/9595) _(by stdlib-bot, Philipp Burckhardt)_
-   [`c68ca1f`](https://github.com/stdlib-js/stdlib/commit/c68ca1f56b551e3094df97c3a26f02dec913e930) - **docs:** update example code in `utils` TypeScript declarations [(#9596)](https://github.com/stdlib-js/stdlib/pull/9596) _(by stdlib-bot)_
-   [`376e7a3`](https://github.com/stdlib-js/stdlib/commit/376e7a36d5239ed7a21a3fb3f8114561cc0c20ef) - **fix:** update TypeScript definitions to use `keys` instead of `indices` _(by Philipp Burckhardt)_
-   [`7e63571`](https://github.com/stdlib-js/stdlib/commit/7e63571d1ad59b012697ee2ce76e3ca3ac008e7e) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`ff76be4`](https://github.com/stdlib-js/stdlib/commit/ff76be4bd7eb9ced1fc74441b9766d1e5e6d6d31) - **bench:** use string interpolation for benchmark names [(#9517)](https://github.com/stdlib-js/stdlib/pull/9517) _(by KovidhRaj)_
-   [`363aead`](https://github.com/stdlib-js/stdlib/commit/363aeadb3882671cf1429fc5e2f4a99dbaa9e09a) - **docs:** update examples [(#9575)](https://github.com/stdlib-js/stdlib/pull/9575) _(by stdlib-bot)_
-   [`d2d06f4`](https://github.com/stdlib-js/stdlib/commit/d2d06f45f5df1d830aa0a14331bd6b883d9992d5) - **fix:** avoid infinite recursion and update examples _(by Athan Reines)_
-   [`56e8832`](https://github.com/stdlib-js/stdlib/commit/56e88323cf168461852ccdc301e81c61c40d5d3f) - **docs:** update related packages sections [(#9573)](https://github.com/stdlib-js/stdlib/pull/9573) _(by stdlib-bot)_
-   [`941eb1f`](https://github.com/stdlib-js/stdlib/commit/941eb1ffe9d0a68b71bc097c9fbf21ca018cc6a3) - **docs:** update REPL namespace documentation [(#9574)](https://github.com/stdlib-js/stdlib/pull/9574) _(by stdlib-bot)_
-   [`e19e323`](https://github.com/stdlib-js/stdlib/commit/e19e323575c6413702679045e005fcb1572eb1d9) - **feat:** add `constants/float16/min-base10-exponent-subnormal` [(#9275)](https://github.com/stdlib-js/stdlib/pull/9275) _(by Samarth Kolarkar, Athan Reines, stdlib-bot)_
-   [`da6ecc9`](https://github.com/stdlib-js/stdlib/commit/da6ecc96d7f503e03007eef616703fc7a71587b8) - **chore:** fix JavaScript lint errors [(#9572)](https://github.com/stdlib-js/stdlib/pull/9572) _(by Shreelaxmi Hegde, Athan Reines)_
-   [`939e2d5`](https://github.com/stdlib-js/stdlib/commit/939e2d5e564a3f4015135894e4764d44e97b76ce) - **feat:** add `constants/float32/num-exponent-bits` [(#9551)](https://github.com/stdlib-js/stdlib/pull/9551) _(by Shubham, Athan Reines, Neeraj Pathak)_
-   [`542d57c`](https://github.com/stdlib-js/stdlib/commit/542d57c97e7b8e8d9b41221d86c5378fa02d0d87) - **feat:** add `math/base/special/floornf` [(#4881)](https://github.com/stdlib-js/stdlib/pull/4881) _(by Gururaj Gurram, Athan Reines, stdlib-bot, Karan Anand)_
-   [`008ae82`](https://github.com/stdlib-js/stdlib/commit/008ae82617ebeff86a92987e405e2c30ad627f1d) - **feat:** add `stats/strided/distances/dchebychev` [(#9559)](https://github.com/stdlib-js/stdlib/pull/9559) _(by Nakul Krishnakumar, Athan Reines, stdlib-bot)_
-   [`ed3afe7`](https://github.com/stdlib-js/stdlib/commit/ed3afe7252708109f1a8350c15bcdabcc96f6e0a) - **chore:** fix C lint errors [(#9571)](https://github.com/stdlib-js/stdlib/pull/9571) _(by Geo Daoyu)_
-   [`9422059`](https://github.com/stdlib-js/stdlib/commit/94220593c164a6c649125950794a496da05b10ef) - **feat:** add `stats/strided/distances/deuclidean` [(#9376)](https://github.com/stdlib-js/stdlib/pull/9376) _(by Nakul Krishnakumar, Athan Reines, stdlib-bot)_
-   [`09140c2`](https://github.com/stdlib-js/stdlib/commit/09140c2f44214e91e61ce3d6b993d36b56a08f12) - **feat:** add `stats/strided/distances/dcosine-distance` [(#9430)](https://github.com/stdlib-js/stdlib/pull/9430) _(by Nakul Krishnakumar, Athan Reines, stdlib-bot)_
-   [`d5f4e8c`](https://github.com/stdlib-js/stdlib/commit/d5f4e8cbabde611d9859f9acda04e5b4f0daecd9) - **style:** remove whitespace _(by Athan Reines)_
-   [`4016fcb`](https://github.com/stdlib-js/stdlib/commit/4016fcbd472fb1dc58b091a59f0828e810f73866) - **style:** remove whitespace _(by Athan Reines)_
-   [`a20542a`](https://github.com/stdlib-js/stdlib/commit/a20542aba55714d744e959d3073fa5bb9966e454) - **style:** remove whitespace _(by Athan Reines)_
-   [`2fee906`](https://github.com/stdlib-js/stdlib/commit/2fee906e7981ff2a9a0bf37bfcbfe3b77421bfcd) - **docs:** resolve lint failures _(by Athan Reines)_
-   [`989e453`](https://github.com/stdlib-js/stdlib/commit/989e45330b4284265444e286a926a693ec8518aa) - **docs:** update copy _(by Athan Reines)_
-   [`c4671b1`](https://github.com/stdlib-js/stdlib/commit/c4671b1cef6f00d28d483cfb9b558d9c1d5f81c9) - **docs:** resolve lint failures _(by Athan Reines)_
-   [`d72fd04`](https://github.com/stdlib-js/stdlib/commit/d72fd04a2081dae30650c5ba9ed842a9fdbfa25f) - **docs:** fix require paths in examples _(by Athan Reines)_
-   [`e776e3f`](https://github.com/stdlib-js/stdlib/commit/e776e3f55c8636a4d777c47a3f4b076d5523db33) - **remove:** remove `utils/bifurcate-in` _(by Neeraj Pathak)_
-   [`99d6070`](https://github.com/stdlib-js/stdlib/commit/99d60701eae79fec91f93de28cb68cd31a0bdfc1) - **refactor:** update paths _(by Neeraj Pathak)_
-   [`20ee8cb`](https://github.com/stdlib-js/stdlib/commit/20ee8cb96a8d3d0de5b6229a72b040acbd965188) - **remove:** remove `bifurcateIn` from namespace _(by Neeraj Pathak)_
-   [`c87f6a8`](https://github.com/stdlib-js/stdlib/commit/c87f6a88410d8742df047cd1b656bfa2e3088b23) - **feat:** add `object/bifurcate-in` _(by Neeraj Pathak)_
-   [`fcc1f3c`](https://github.com/stdlib-js/stdlib/commit/fcc1f3cce959e57ada8f4cc484b8a55157ad6087) - **feat:** add `stats/base/ndarray/sstdevpn` [(#9534)](https://github.com/stdlib-js/stdlib/pull/9534) _(by Pratik, Athan Reines)_
-   [`1d19423`](https://github.com/stdlib-js/stdlib/commit/1d19423c208ee726419674b8e44ed9b7d4f21ec2) - **feat:** add `stats/base/ndarray/dstdev` [(#9516)](https://github.com/stdlib-js/stdlib/pull/9516) _(by Pratik, Athan Reines)_
-   [`e80d912`](https://github.com/stdlib-js/stdlib/commit/e80d91298650049b369091edf4af6db7718cfa5d) - **bench:** fix descriptions _(by Athan Reines)_
-   [`803dfe6`](https://github.com/stdlib-js/stdlib/commit/803dfe64bff71c2fe1206eda1d807d6759d0a751) - **bench:** refactor to use string interpolation in `buffer/from-arraybuffer` [(#9554)](https://github.com/stdlib-js/stdlib/pull/9554) _(by Vishal Gaikwad)_
-   [`f4eb003`](https://github.com/stdlib-js/stdlib/commit/f4eb003101dc763c66363a1d52c013a3b3b7c3c7) - **bench:** refactor to use string interpolation in `buffer/from-array` [(#9553)](https://github.com/stdlib-js/stdlib/pull/9553) _(by Vishal Gaikwad)_
-   [`35ce703`](https://github.com/stdlib-js/stdlib/commit/35ce70320886dd8f426225b2bd300114e7ea4c7d) - **docs:** remove duplicate words in documentation [(#9555)](https://github.com/stdlib-js/stdlib/pull/9555) _(by Shivam Mittal)_
-   [`5571f97`](https://github.com/stdlib-js/stdlib/commit/5571f978ab8d57c06dfff08288f598dbd9f10645) - **docs:** remove duplicate word _(by Athan Reines)_
-   [`a83b4cc`](https://github.com/stdlib-js/stdlib/commit/a83b4cc2ff80364c1b0c6e4a312ea4fb4ed4e325) - **bench:** refactor to use string interpolation in `buffer/ctor` [(#9552)](https://github.com/stdlib-js/stdlib/pull/9552) _(by Vishal Gaikwad, stdlib-bot)_
-   [`948e04b`](https://github.com/stdlib-js/stdlib/commit/948e04bf760415e316dbf802d78d82478ca72b2c) - **docs:** update examples _(by Athan Reines)_
-   [`aa31c82`](https://github.com/stdlib-js/stdlib/commit/aa31c82f3d919244c5393ae7a8b7331355eb2e17) - **feat:** add `stats/base/ndarray/nanmidrange-by` [(#9501)](https://github.com/stdlib-js/stdlib/pull/9501) _(by Sachin Pangal, Athan Reines)_
-   [`6986d92`](https://github.com/stdlib-js/stdlib/commit/6986d92dd402cf96c394abfea5340be84184d2c1) - **feat:** add `stats/base/ndarray/midrange-by` [(#9512)](https://github.com/stdlib-js/stdlib/pull/9512) _(by Sachin Pangal)_
-   [`b0c05c9`](https://github.com/stdlib-js/stdlib/commit/b0c05c934c6654a95eee523ed88fb34e12fd552b) - **chore:** fix JavaScript lint errors [(#9546)](https://github.com/stdlib-js/stdlib/pull/9546) _(by DivitJain26)_
-   [`3af0a04`](https://github.com/stdlib-js/stdlib/commit/3af0a041f6ae95c251cbfa2acae82b30e3b4579b) - **fix:** return `NaN` when the number of indexed elements is zero in `stats/strided/distances/dcosine-similarity` [(#9497)](https://github.com/stdlib-js/stdlib/pull/9497) _(by Nakul Krishnakumar)_
-   [`c216b80`](https://github.com/stdlib-js/stdlib/commit/c216b80baf3efe0d21387a280368c44122328b76) - **feat:** add `stats/base/ndarray/smskmidrange` [(#9519)](https://github.com/stdlib-js/stdlib/pull/9519) _(by Sachin Pangal, Athan Reines)_
-   [`bda1a5c`](https://github.com/stdlib-js/stdlib/commit/bda1a5c6cfa6777839ab5f941296b2008880b75a) - **fix:** use correct types _(by Athan Reines)_
-   [`4bbb36f`](https://github.com/stdlib-js/stdlib/commit/4bbb36ffe5348c5f863bd34d2218464bc1c18f88) - **docs:** update REPL namespace documentation [(#9545)](https://github.com/stdlib-js/stdlib/pull/9545) _(by stdlib-bot)_
-   [`d681872`](https://github.com/stdlib-js/stdlib/commit/d681872a9b87321f4f66852f5aabfeec19e195fc) - **feat:** add `stats/base/ndarray/mskmidrange` [(#9511)](https://github.com/stdlib-js/stdlib/pull/9511) _(by Sachin Pangal)_
-   [`4bb46e9`](https://github.com/stdlib-js/stdlib/commit/4bb46e9a4f4421fd250ac065aba2fd7ca8dfa5da) - **chore:** fix JavaScript lint errors [(#9530)](https://github.com/stdlib-js/stdlib/pull/9530) _(by kaushal-kumar-it, Athan Reines)_
-   [`c824fea`](https://github.com/stdlib-js/stdlib/commit/c824feae2f1582ff59f0d3bee99896fa77ef1f81) - **feat:** add `stats/base/ndarray/snanmidrange` [(#9505)](https://github.com/stdlib-js/stdlib/pull/9505) _(by Sachin Pangal)_
-   [`c7b5670`](https://github.com/stdlib-js/stdlib/commit/c7b567035c988493c48a6f305b535d6510e72501) - **chore:** fix EditorConfig lint errors [(#9528)](https://github.com/stdlib-js/stdlib/pull/9528) _(by Shreelaxmi Hegde)_
-   [`a27671f`](https://github.com/stdlib-js/stdlib/commit/a27671f8fc907e4f054086e3e422234ed56964cd) - **docs:** update string interpolation in various `stats/base/dists` examples [(#9533)](https://github.com/stdlib-js/stdlib/pull/9533) _(by Harsh Yadav)_
-   [`374b631`](https://github.com/stdlib-js/stdlib/commit/374b6311d0d676952c1f8341f4d6fffb951fce28) - **bench:** refactor to use string interpolation in `buffer/alloc-unsafe` [(#9531)](https://github.com/stdlib-js/stdlib/pull/9531) _(by Shubham)_
-   [`ee1b451`](https://github.com/stdlib-js/stdlib/commit/ee1b4510c3da0bcfa8225cba9c003a128ae4672b) - **bench:** refactor to use string interpolation in `assert/deep-has-property` [(#9532)](https://github.com/stdlib-js/stdlib/pull/9532) _(by Shubham)_
-   [`e1c4c43`](https://github.com/stdlib-js/stdlib/commit/e1c4c4337a0ad754e9752546fe96ed63f51764da) - **test:** address review comments [(#9543)](https://github.com/stdlib-js/stdlib/pull/9543) _(by daksha607, Athan Reines)_
-   [`2611bf7`](https://github.com/stdlib-js/stdlib/commit/2611bf70b28a222e72e051a4901c266f5d979412) - **docs:** update REPL namespace documentation [(#9529)](https://github.com/stdlib-js/stdlib/pull/9529) _(by stdlib-bot)_
-   [`55030f9`](https://github.com/stdlib-js/stdlib/commit/55030f9809f5dba8e7ab8015c1f7faf9ab337aac) - **remove:** remove `utils/object-inverse` _(by Neeraj Pathak)_
-   [`46c47ec`](https://github.com/stdlib-js/stdlib/commit/46c47ec0c92f9a3608290ef8a6ca5cf0e9258866) - **refactor:** update paths _(by Neeraj Pathak)_
-   [`9ccefc9`](https://github.com/stdlib-js/stdlib/commit/9ccefc92d742e8e4a2555a39a65849c078d4e86e) - **remove:** remove `objectInverse` from namespace _(by Neeraj Pathak)_
-   [`a53615b`](https://github.com/stdlib-js/stdlib/commit/a53615b3210cdd787a16f1e8721d2d4e17153883) - **feat:** add `object/inverse` _(by Neeraj Pathak)_
-   [`d866858`](https://github.com/stdlib-js/stdlib/commit/d866858cf3082f7692f1c51883490c1da36d1879) - **bench:** refactor to use string interpolation in `array/uint8` [(#9518)](https://github.com/stdlib-js/stdlib/pull/9518) _(by Shubham)_
-   [`932f042`](https://github.com/stdlib-js/stdlib/commit/932f0422195ffa4db9efaca5e060881716aae006) - **revert:** chore: add src to directories _(by Philipp Burckhardt)_
-   [`7b5a1b5`](https://github.com/stdlib-js/stdlib/commit/7b5a1b57e9d707ea3944a616d775620a8f188bd8) - **test:** add test case for sx _(by Philipp Burckhardt)_
-   [`df82f00`](https://github.com/stdlib-js/stdlib/commit/df82f006202c8ade82178b4f7839063706723894) - **docs:** fix require path _(by Philipp Burckhardt)_
-   [`3b896f1`](https://github.com/stdlib-js/stdlib/commit/3b896f19550d799ea5a61d386974f6ce1f341eaa) - **chore:** add src to directories _(by Philipp Burckhardt)_
-   [`016b07f`](https://github.com/stdlib-js/stdlib/commit/016b07f8610e21332af7bfbc38afbacdbeac8583) - **refactor:** rename/reorder parameters _(by Athan Reines)_
-   [`5f0a844`](https://github.com/stdlib-js/stdlib/commit/5f0a844380510aaa97c8ca7d1b539868132ae2e7) - **refactor:** rename/reorder parameters _(by Athan Reines)_
-   [`f40ccb7`](https://github.com/stdlib-js/stdlib/commit/f40ccb75929e92538b8c366145589addccdaafbe) - **feat:** add `ndarray/base/ternary-loop-interchange-order` [(#9499)](https://github.com/stdlib-js/stdlib/pull/9499) _(by Muhammad Haris, Athan Reines)_
-   [`1f79854`](https://github.com/stdlib-js/stdlib/commit/1f798549409c47de0261c5396dccf64012e54a9c) - **feat:** add `ndarray/base/ternary-tiling-block-size` [(#9495)](https://github.com/stdlib-js/stdlib/pull/9495) _(by Muhammad Haris, Athan Reines)_
-   [`8107a5a`](https://github.com/stdlib-js/stdlib/commit/8107a5a755bbdeb69c8110a2dbc9ed1a39d136c9) - **feat:** add `stats/base/ndarray/dnanmidrange` [(#9504)](https://github.com/stdlib-js/stdlib/pull/9504) _(by Sachin Pangal)_
-   [`fb7c43e`](https://github.com/stdlib-js/stdlib/commit/fb7c43e10a7a6f10f2677fa7ea1790fff535c968) - **feat:** add `stats/strided/smskmidrange` [(#9492)](https://github.com/stdlib-js/stdlib/pull/9492) _(by Sachin Pangal, Athan Reines, stdlib-bot)_
-   [`33ce408`](https://github.com/stdlib-js/stdlib/commit/33ce4082725bbb85c660b4ffeb276774778ef0a8) - **docs:** fix broken Markdown link [(#9493)](https://github.com/stdlib-js/stdlib/pull/9493) _(by Suyash Pathak, Athan Reines)_
-   [`27d5d30`](https://github.com/stdlib-js/stdlib/commit/27d5d30af2380909aa925ce955fb7a4b79d5df43) - **style:** fix EditorConfig lint errors [(#9510)](https://github.com/stdlib-js/stdlib/pull/9510) _(by kaushal-kumar-it)_
-   [`327cda9`](https://github.com/stdlib-js/stdlib/commit/327cda9b2dda086b20da9ce256df388573486946) - **feat:** update `ndarray` TypeScript declarations [(#9508)](https://github.com/stdlib-js/stdlib/pull/9508) _(by stdlib-bot)_
-   [`c026135`](https://github.com/stdlib-js/stdlib/commit/c0261358afbc15c908bd276eb789f86f9d90ffaa) - **style:** remove empty line [(#9507)](https://github.com/stdlib-js/stdlib/pull/9507) _(by stdlib-bot)_
-   [`873beeb`](https://github.com/stdlib-js/stdlib/commit/873beeb4042c9ada02dff4c40ec0de82887faa17) - **chore:** remove square bracket and add private annotation _(by Philipp Burckhardt)_
-   [`81f1cc5`](https://github.com/stdlib-js/stdlib/commit/81f1cc50d12dbb6ad9c0a198850ee56455c76db7) - **feat:** add `stats/base/ndarray/nanmidrange` [(#9418)](https://github.com/stdlib-js/stdlib/pull/9418) _(by Sachin Pangal, stdlib-bot)_
-   [`8289a03`](https://github.com/stdlib-js/stdlib/commit/8289a036ebd5f568c35541a480ccdc341ba706af) - **bench:** refactor to use dynamic memory allocation in `math/strided/special/strunc` [(#9481)](https://github.com/stdlib-js/stdlib/pull/9481) _(by kshitijgarg2811-oss, Athan Reines)_
-   [`3ae6e96`](https://github.com/stdlib-js/stdlib/commit/3ae6e9691bbab7f2162ef8bb5e3279aefd517e47) - **chore:** add structured meta data _(by Athan Reines)_
-   [`a7cbc8d`](https://github.com/stdlib-js/stdlib/commit/a7cbc8dbdbd69453891b1d5ffc1fcca9126910e2) - **feat:** move optional argument to options object in `ndarray/concat` [(#9480)](https://github.com/stdlib-js/stdlib/pull/9480) _(by Muhammad Haris, Athan Reines)_
-   [`88af63a`](https://github.com/stdlib-js/stdlib/commit/88af63aa54165f09b84ef528cadc3dae622ab05a) - **docs:** replace manual `for` loop in examples [(#9444)](https://github.com/stdlib-js/stdlib/pull/9444) _(by Harsh Yadav)_
-   [`edccce1`](https://github.com/stdlib-js/stdlib/commit/edccce1444f24145380aa51e8439f95928bda403) - **docs:** replace manual `for` loop in examples [(#9479)](https://github.com/stdlib-js/stdlib/pull/9479) _(by Harsh Yadav)_
-   [`ea8228b`](https://github.com/stdlib-js/stdlib/commit/ea8228b082c03c6c8c8182d237c709ae279c05d2) - **feat:** add `math/base/special/acoshf` [(#5812)](https://github.com/stdlib-js/stdlib/pull/5812) _(by Prashant Kumar Yadav, Karan Anand, Nakul Krishnakumar, stdlib-bot)_
-   [`6b009d1`](https://github.com/stdlib-js/stdlib/commit/6b009d1d435f278d0c9bed8294f000e4a6d67490) - **test:** use correct variable name in `math/base/special/atanf` test _(by Philipp Burckhardt)_
-   [`a55e19f`](https://github.com/stdlib-js/stdlib/commit/a55e19f3343b4a34486a5c109805bbc52e4dbb16) - **test:** replace t.true with t.strictEqual so tests actually check main export _(by Philipp Burckhardt)_
-   [`e6a30ce`](https://github.com/stdlib-js/stdlib/commit/e6a30ce5227ad8260959fe518e88875e4d85a975) - **feat:** update `complex/float64/base` TypeScript declarations [(#9466)](https://github.com/stdlib-js/stdlib/pull/9466) _(by stdlib-bot)_
-   [`c681b91`](https://github.com/stdlib-js/stdlib/commit/c681b91b18f634d25dae56786f0e7389cdc05114) - **docs:** update REPL namespace documentation [(#9467)](https://github.com/stdlib-js/stdlib/pull/9467) _(by stdlib-bot, Philipp Burckhardt)_
-   [`9273054`](https://github.com/stdlib-js/stdlib/commit/9273054d9d5ab37c52da6ae37563b1289d7c8351) - **chore:** fix JavaScript lint errors [(#9473)](https://github.com/stdlib-js/stdlib/pull/9473) _(by Tejasvini Ramaswamy)_
-   [`e47459a`](https://github.com/stdlib-js/stdlib/commit/e47459a872746e9329b52b4bec80c8559d72543c) - **chore:** fix C lint errors [(#9475)](https://github.com/stdlib-js/stdlib/pull/9475) _(by Geo Daoyu)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 44 people contributed to this release. Thank you to the following contributors:

-   Aman Singh
-   Anant Sharma
-   Aryan kumar
-   Athan Reines
-   AyushiJain18270
-   Bhargav Dabhade
-   Daksha Raj
-   DivitJain26
-   Divyanshu
-   Diyan
-   Geo Daoyu
-   Gururaj Gurram
-   Harsh Yadav
-   Harshit Verma
-   Ishanth
-   Karan Anand
-   Kaustubh Patange
-   KovidhRaj
-   Lokesh Ranjan
-   Manit Roy
-   Muhammad Haris
-   Nakul Krishnakumar
-   Neeraj Pathak
-   Om-A-osc
-   Philipp Burckhardt
-   Prashant Kumar Yadav
-   Pratik
-   Rohit R Bhat
-   Sachin Pangal
-   Sagar Ratna Chaudhary
-   Samarth Kolarkar
-   Shivam Mittal
-   Shreelaxmi Hegde
-   Shubham
-   Suyash Pathak
-   Tejasvini Ramaswamy
-   Utkarsh Singhal
-   Vishal Gaikwad
-   daksha607
-   kaushal-kumar-it
-   kshitijgarg2811-oss
-   nnyouung
-   pxxad
-   가은 정

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->


