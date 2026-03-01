# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-03-01)

<section class="features">

### Features

-   [`0e62b3f`](https://github.com/stdlib-js/stdlib/commit/0e62b3fbc7f29583bfd0ba72f9e3d900af99e9a4) - add C implementation for `blas/ext/base/ndarray/ssum` [(#10078)](https://github.com/stdlib-js/stdlib/pull/10078)
-   [`e21c16f`](https://github.com/stdlib-js/stdlib/commit/e21c16fb0ca9a5d7a4018c2189e7aaada33c477e) - add `HH_H` macro in `math/base/napi/binary` [(#9577)](https://github.com/stdlib-js/stdlib/pull/9577)
-   [`a2d1f94`](https://github.com/stdlib-js/stdlib/commit/a2d1f943965c8f2fbd40bb56a71be529c9fa5b82) - add C implementation for `stats/base/ndarray/smaxabs` [(#10040)](https://github.com/stdlib-js/stdlib/pull/10040)
-   [`a2a6b49`](https://github.com/stdlib-js/stdlib/commit/a2a6b49348a8057afc805b27b535dcbce79fd117) - add C implementation for `stats/base/ndarray/sminabs` [(#10044)](https://github.com/stdlib-js/stdlib/pull/10044)
-   [`0682ac1`](https://github.com/stdlib-js/stdlib/commit/0682ac10d0ad67b46453f186b3577901886fa42c) - add C implementation for `stats/base/ndarray/dmean` [(#10052)](https://github.com/stdlib-js/stdlib/pull/10052)
-   [`d7c9033`](https://github.com/stdlib-js/stdlib/commit/d7c9033dec5f569d53dd71706ce6f1124e886259) - add C implementation for `blas/ext/base/ndarray/dsum` [(#10065)](https://github.com/stdlib-js/stdlib/pull/10065)
-   [`de74169`](https://github.com/stdlib-js/stdlib/commit/de7416999fa2bd9a2e912d70b97540b0575d0599) - add `blas/ext/base/ndarray/gsort` [(#9734)](https://github.com/stdlib-js/stdlib/pull/9734)
-   [`b77641d`](https://github.com/stdlib-js/stdlib/commit/b77641d288f89a5333abf07b421cf54e575c5d03) - update `ndarray/base` TypeScript declarations [(#10558)](https://github.com/stdlib-js/stdlib/pull/10558)
-   [`2db642e`](https://github.com/stdlib-js/stdlib/commit/2db642edf40e64407f05bcffcb3f0cdae718f8aa) - update `ndarray` TypeScript declarations [(#10560)](https://github.com/stdlib-js/stdlib/pull/10560)
-   [`f91aca6`](https://github.com/stdlib-js/stdlib/commit/f91aca6650536cb46c7b4c41bd05a2a37e0fe475) - add `maybeBroadcastArrayExceptDimensions` to namespace
-   [`5324e96`](https://github.com/stdlib-js/stdlib/commit/5324e9618a4b8688b4792ccceb146b348d9a9f2f) - add `ndarray/base/maybe-broadcast-array-except-dimensions` [(#10413)](https://github.com/stdlib-js/stdlib/pull/10413)
-   [`9df924b`](https://github.com/stdlib-js/stdlib/commit/9df924b5f0b773c8b06d06b40e54dee75059ce08) - add writable parameter support to `ndarray/base/transpose` (#10474) [(#10474)](https://github.com/stdlib-js/stdlib/pull/10474)
-   [`e947540`](https://github.com/stdlib-js/stdlib/commit/e947540a4e87841d7bf140094e20b2768250de11) - add writable parameter to `ndarray/base/remove-singleton-dimensions` [(#9667)](https://github.com/stdlib-js/stdlib/pull/9667)
-   [`e5af570`](https://github.com/stdlib-js/stdlib/commit/e5af57010dbb7c873ea46afe2662c8ceb44ac637) - add `atleastnd` to namespace
-   [`53caca8`](https://github.com/stdlib-js/stdlib/commit/53caca808d0b9aad069992056c6fe64b0c780e8f) - add `ndarray/base/atleastnd` [(#10422)](https://github.com/stdlib-js/stdlib/pull/10422)
-   [`94c1431`](https://github.com/stdlib-js/stdlib/commit/94c143124e150a3751b1a70205917f986dca8c03) - add `stats/strided/dnanmskminabs` [(#10382)](https://github.com/stdlib-js/stdlib/pull/10382)
-   [`9221bdb`](https://github.com/stdlib-js/stdlib/commit/9221bdb56bac8544a387c8b8f74ae69ae5ec2961) - add `toTransposed` to namespace
-   [`5606366`](https://github.com/stdlib-js/stdlib/commit/560636601a3ebbc74e58ba18752ba832c3548215) - add `ndarray/base/to-transposed` [(#10499)](https://github.com/stdlib-js/stdlib/pull/10499)
-   [`01a25b3`](https://github.com/stdlib-js/stdlib/commit/01a25b340fc172d9754d027cc09330e0be32babb) - add `unflattenShape` to namespace
-   [`4049c73`](https://github.com/stdlib-js/stdlib/commit/4049c7358fb474ef3b7c3f1a1dc94206c37fd105) - add `ndarray/base/unflatten-shape` [(#10441)](https://github.com/stdlib-js/stdlib/pull/10441)
-   [`0d32b1b`](https://github.com/stdlib-js/stdlib/commit/0d32b1b98dc0bf319b6330e9535e2a3ba0980adf) - add `toReversedDimension` to namespace
-   [`287c085`](https://github.com/stdlib-js/stdlib/commit/287c08582a945209e4b6da083fbd8102b8bf8321) - add `ndarray/to-reversed-dimension` [(#10058)](https://github.com/stdlib-js/stdlib/pull/10058)
-   [`e7a30dc`](https://github.com/stdlib-js/stdlib/commit/e7a30dcc468a1db97d78ae16cea85090a13d5fac) - add `broadcastScalar` to namespace
-   [`6bc5ee5`](https://github.com/stdlib-js/stdlib/commit/6bc5ee550629c3aaae7687630c315d607c185ba9) - add `ndarray/broadcast-scalar` [(#9916)](https://github.com/stdlib-js/stdlib/pull/9916)
-   [`e8b00ab`](https://github.com/stdlib-js/stdlib/commit/e8b00abfb7e1a012c9df982553c6ede3f6b261d9) - add `unshift` to namespace
-   [`d703ebd`](https://github.com/stdlib-js/stdlib/commit/d703ebd30fb8f62c7e3718074648bb901de0c267) - add `spreadDimensions` to namespace
-   [`853269d`](https://github.com/stdlib-js/stdlib/commit/853269d40f022bbeb9dfb3b751ec9e3da769e1db) - add `some` to namespace
-   [`e4dc41b`](https://github.com/stdlib-js/stdlib/commit/e4dc41b5cb957c29d5035de9f1a03b23596f5df2) - add `push` to namespace
-   [`2b44a14`](https://github.com/stdlib-js/stdlib/commit/2b44a14f3e9320f09189749176998ed6ce21d459) - add `prependSingletonDimensions` to namespace
-   [`6438f89`](https://github.com/stdlib-js/stdlib/commit/6438f8920f0cdbb525f7b1a1b4c818806e48da2b) - add `flipud` to namespace
-   [`5a4177b`](https://github.com/stdlib-js/stdlib/commit/5a4177bef249b76469c6cd06218acf33e72762d5) - add `fliplr` to namespace
-   [`9a7bd40`](https://github.com/stdlib-js/stdlib/commit/9a7bd407645ceeac99c6ac8bf46a905dad66739d) - add `flattenFromBy` to namespace
-   [`f53b521`](https://github.com/stdlib-js/stdlib/commit/f53b521efeef869b0ef0ccf07e878bdeaa2fed12) - add `findLast` to namespace
-   [`39c40c5`](https://github.com/stdlib-js/stdlib/commit/39c40c569825bc185a8e8a802452ed1ebaed7ece) - add `concat1d` to namespace
-   [`78d37a0`](https://github.com/stdlib-js/stdlib/commit/78d37a025058a2260ccfe38ff5ead8ab9e09af3e) - add `scalar2ndarrayLike` to namespace
-   [`2b0c11f`](https://github.com/stdlib-js/stdlib/commit/2b0c11f5339edc83e5de241d702230e73552136d) - add `ndarray/from-scalar-like` [(#9940)](https://github.com/stdlib-js/stdlib/pull/9940)
-   [`793a38c`](https://github.com/stdlib-js/stdlib/commit/793a38c29f31677807e0cf6748f1ca54fbbef4ec) - add `toLocaleString` method to `ndarray/base/ctor` [(#9435)](https://github.com/stdlib-js/stdlib/pull/9435)
-   [`707fcd4`](https://github.com/stdlib-js/stdlib/commit/707fcd4483bd8989ea064842812555f5e382dc52) - add `stats/base/ndarray/dnanstdevpn` [(#10375)](https://github.com/stdlib-js/stdlib/pull/10375)
-   [`8a0bdab`](https://github.com/stdlib-js/stdlib/commit/8a0bdab18b22e650ce6ec73b87f347846774890f) - add `stats/strided/distances/dchebyshev
-   [`e53e179`](https://github.com/stdlib-js/stdlib/commit/e53e179ec5f9b063604744804b989bd6ebe2381a) - add `stats/base/ndarray/dnanstdev` [(#10271)](https://github.com/stdlib-js/stdlib/pull/10271)
-   [`c51df70`](https://github.com/stdlib-js/stdlib/commit/c51df700dde62d157e7fd9bbcfa9148d82ccef7f) - add implementation of `math/base/special/floor2f` [(#10323)](https://github.com/stdlib-js/stdlib/pull/10323)
-   [`5a64342`](https://github.com/stdlib-js/stdlib/commit/5a643426403fa397b0bd695ff1deeddd002cc641) - add C implementation for `stats/base/ndarray/snanrange` [(#10258)](https://github.com/stdlib-js/stdlib/pull/10258)
-   [`10b28fd`](https://github.com/stdlib-js/stdlib/commit/10b28fdb54393277d093066bf40c84412ca7601d) - add `stats/array/nanmidrange-by` [(#10273)](https://github.com/stdlib-js/stdlib/pull/10273)
-   [`8bfb552`](https://github.com/stdlib-js/stdlib/commit/8bfb5524d89a26ed6d0524d72d11e5a893338c5d) - add C implementation for `stats/base/ndarray/snanmax` [(#10198)](https://github.com/stdlib-js/stdlib/pull/10198)
-   [`53aaf81`](https://github.com/stdlib-js/stdlib/commit/53aaf8135f7feba8476da758d895cc24da20caad) - add C implementation for `math/base/special/heaviside` [(#10196)](https://github.com/stdlib-js/stdlib/pull/10196)
-   [`f04bd84`](https://github.com/stdlib-js/stdlib/commit/f04bd8446b04ed6a0e45822b20dbccf45bcb2ef7) - add `stats/array/mskmaxabs` [(#10280)](https://github.com/stdlib-js/stdlib/pull/10280)
-   [`c7b5ae5`](https://github.com/stdlib-js/stdlib/commit/c7b5ae52a7ed0b5be7025ee3b93f8ae3f5d5aada) - add `stats/array/mskminabs` [(#10281)](https://github.com/stdlib-js/stdlib/pull/10281)
-   [`0f2ea57`](https://github.com/stdlib-js/stdlib/commit/0f2ea572ed30d6c259cb103182a1237ec430b983) - add Wald distribution variance package [(#9730)](https://github.com/stdlib-js/stdlib/pull/9730)
-   [`7ef3bae`](https://github.com/stdlib-js/stdlib/commit/7ef3bae65f5d876db0c56d57ab84ea52e7699b7d) - add `stats/array/nanmskmidrange` [(#10224)](https://github.com/stdlib-js/stdlib/pull/10224)
-   [`aec0634`](https://github.com/stdlib-js/stdlib/commit/aec0634d886bdade0dd7dd221bbe1bd655669594) - add `stats/array/rangeabs` [(#10227)](https://github.com/stdlib-js/stdlib/pull/10227)
-   [`3088f39`](https://github.com/stdlib-js/stdlib/commit/3088f3987094c907d9b81fbdeeea5ac58a915ac3) - add implementation of `stats/base/dists/wald/kurtosis` [(#10216)](https://github.com/stdlib-js/stdlib/pull/10216)
-   [`96f2808`](https://github.com/stdlib-js/stdlib/commit/96f28086b0a4bf03556f5ba91078d68c1823a27d) - add implementation of `stats/base/dists/wald/skewness` [(#10206)](https://github.com/stdlib-js/stdlib/pull/10206)
-   [`5dfd41d`](https://github.com/stdlib-js/stdlib/commit/5dfd41df5e698950034ed3e54d9f32dc9ff03355) - add C implementation for `stats/base/ndarray/srangeabs` [(#10240)](https://github.com/stdlib-js/stdlib/pull/10240)
-   [`2a8cda9`](https://github.com/stdlib-js/stdlib/commit/2a8cda98b404d0507e04c4c62d572726a08b015a) - add `stats/array/midrange-by` [(#10263)](https://github.com/stdlib-js/stdlib/pull/10263)
-   [`ab43b7f`](https://github.com/stdlib-js/stdlib/commit/ab43b7fff2a33d8e101f50d65d18bfa914dbfcf0) - add `stats/array/mskmidrange` [(#10221)](https://github.com/stdlib-js/stdlib/pull/10221)
-   [`2eea8bb`](https://github.com/stdlib-js/stdlib/commit/2eea8bb24c99fb81c56ec7c14d0cca8d88b1cb52) - add implementation of `math/base/special/coshf` [(#10177)](https://github.com/stdlib-js/stdlib/pull/10177)
-   [`c70d9ed`](https://github.com/stdlib-js/stdlib/commit/c70d9eda1f4465e886f967cf09fdc54f0b11900d) - add `stats/array/midrange` [(#10189)](https://github.com/stdlib-js/stdlib/pull/10189)
-   [`b47c0f0`](https://github.com/stdlib-js/stdlib/commit/b47c0f0b2d39710600184eeb20fcc9e1c870e3f9) - add `math/base/special/sincosdf` [(#9822)](https://github.com/stdlib-js/stdlib/pull/9822)
-   [`79a051f`](https://github.com/stdlib-js/stdlib/commit/79a051fbab0d43293a1cb71a92625c7dd2969bfa) - add `stats/array/nanmidrange` [(#10201)](https://github.com/stdlib-js/stdlib/pull/10201)
-   [`42ada99`](https://github.com/stdlib-js/stdlib/commit/42ada99a46614cf0d14f2f8f70c5d95869e08bd8) - add C implementation of `stats/base/ndarray/dmaxabs` [(#10039)](https://github.com/stdlib-js/stdlib/pull/10039)
-   [`06e3710`](https://github.com/stdlib-js/stdlib/commit/06e37102b1e86507533abe95f50c4c44e4ddcf54) - add C implementation for `stats/base/ndarray/dminabs` [(#10046)](https://github.com/stdlib-js/stdlib/pull/10046)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`60fcd9d`](https://github.com/stdlib-js/stdlib/commit/60fcd9dc51b43ad76b1b14e6d7b4c30a5670114a) - improve type specificity
-   [`f10a6aa`](https://github.com/stdlib-js/stdlib/commit/f10a6aaf98c37bb630ac75e1a50dd0bd4a0eb417) - ensure unique indices
-   [`383707f`](https://github.com/stdlib-js/stdlib/commit/383707fb11279899f663267e47dcb303070f63b4) - remove erroneous `browser` field excluding `ndarray` method in `stats/strided/mskminabs` and `blas/ext/base/gnannsumkbn`
-   [`d65bf73`](https://github.com/stdlib-js/stdlib/commit/d65bf7356a9f65e0e512ac1a6809e731528a09a9) - rename incorrect manifest file name in `constants/float32/max-ln` [(#10167)](https://github.com/stdlib-js/stdlib/pull/10167)

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`b77641d`](https://github.com/stdlib-js/stdlib/commit/b77641d288f89a5333abf07b421cf54e575c5d03): add writable parameter to and always return a new ndarray in `removeSingletonDimensions`

    -   To migrate, in order to preserve prior writable behavior, users should set the final parameter equal to a boolean indicating whether the input ndarray is writable. If not, pass `false`; if yes, pass `true`.
        To preserve prior behavior in which the input ndarray is returned if it does not have singleton dimensions, use `maybeRemoveSingletonDimensions`.

-   [`9df924b`](https://github.com/stdlib-js/stdlib/commit/9df924b5f0b773c8b06d06b40e54dee75059ce08): add writable parameter

    -   To migrate and preserve prior behavior, users should always pass `true` for the second parameter.

-   [`e947540`](https://github.com/stdlib-js/stdlib/commit/e947540a4e87841d7bf140094e20b2768250de11): add writable parameter and always return a new view

    -   To migrate, in order to preserve prior writable behavior, users should set the final parameter equal to a boolean indicating whether the input ndarray is writable. If not, pass `false`; if yes, pass `true`.
        To preserve prior behavior in which the input ndarray is returned if it does not have singleton dimensions, use `ndarray/base/maybe-remove-singleton-dimensions`.

-   [`becb440`](https://github.com/stdlib-js/stdlib/commit/becb440aaa166ce435909ba82f743009ad1e7b6d): remove `stats/strided/distances/dchebychev`

    -   To migrate, users should update their require/import paths to use
        `@stdlib/stats/strided/distances/dchebyshev` which provides the same API and implementation.

-   [`cc812eb`](https://github.com/stdlib-js/stdlib/commit/cc812eb5ac0285a79e7e0ac15ad09a194bd7364b): remove `dchebychev`

    -   To migrate, users should access the symbol `dchebyshev` via the
        `@stdlib/stats/strided/distances` namespace.

</section>

<!-- /.breaking-changes -->

<section class="issues">

### Closed Issues

A total of 15 issues were closed in this release:

[#9964](https://github.com/stdlib-js/stdlib/issues/9964), [#10042](https://github.com/stdlib-js/stdlib/issues/10042), [#10166](https://github.com/stdlib-js/stdlib/issues/10166), [#10211](https://github.com/stdlib-js/stdlib/issues/10211), [#10246](https://github.com/stdlib-js/stdlib/issues/10246), [#10285](https://github.com/stdlib-js/stdlib/issues/10285), [#10327](https://github.com/stdlib-js/stdlib/issues/10327), [#10355](https://github.com/stdlib-js/stdlib/issues/10355), [#10377](https://github.com/stdlib-js/stdlib/issues/10377), [#10378](https://github.com/stdlib-js/stdlib/issues/10378), [#10400](https://github.com/stdlib-js/stdlib/issues/10400), [#10417](https://github.com/stdlib-js/stdlib/issues/10417), [#10423](https://github.com/stdlib-js/stdlib/issues/10423), [#10475](https://github.com/stdlib-js/stdlib/issues/10475), [#10556](https://github.com/stdlib-js/stdlib/issues/10556)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`1a62e75`](https://github.com/stdlib-js/stdlib/commit/1a62e75a0677036eccaa0485fe3a6ff5462428d5) - **bench:** use string interpolation in `strided/base/binary-signature-callbacks` [(#10581)](https://github.com/stdlib-js/stdlib/pull/10581) _(by Vishal Gaikwad)_
-   [`0e62b3f`](https://github.com/stdlib-js/stdlib/commit/0e62b3fbc7f29583bfd0ba72f9e3d900af99e9a4) - **feat:** add C implementation for `blas/ext/base/ndarray/ssum` [(#10078)](https://github.com/stdlib-js/stdlib/pull/10078) _(by Kaustubh Patange, Athan Reines)_
-   [`5a53af0`](https://github.com/stdlib-js/stdlib/commit/5a53af029ad1dd8b36b11583e3081cf2d61aa06b) - **bench:** refactor to use string interpolation in `blas/ext/base/dapxsumpw` [(#10518)](https://github.com/stdlib-js/stdlib/pull/10518) _(by Kamal Singh Rautela)_
-   [`29f6a68`](https://github.com/stdlib-js/stdlib/commit/29f6a6888d2d653afc0f7ea8d81bb1872fb42780) - **bench:** refactor to use string interpolation in `stats/base/dists/negative-binomial` [(#10101)](https://github.com/stdlib-js/stdlib/pull/10101) _(by Shubham, Philipp Burckhardt)_
-   [`8fff79b`](https://github.com/stdlib-js/stdlib/commit/8fff79b16224ab75b57074709c5f8d9d9c9439e5) - **bench:** use string interpolation in `blas/base/dtrmv` [(#10551)](https://github.com/stdlib-js/stdlib/pull/10551) _(by Om-A-osc)_
-   [`9d4fd4d`](https://github.com/stdlib-js/stdlib/commit/9d4fd4d04449738e03dfc62aab9dce8f9ae4d822) - **bench:** use string interpolation in `blas/base/gasum` [(#10553)](https://github.com/stdlib-js/stdlib/pull/10553) _(by Om-A-osc)_
-   [`637d083`](https://github.com/stdlib-js/stdlib/commit/637d0837af7524404e244e128e237a07f2e30819) - **bench:** use string interpolation in `blas/base/dtrsv` [(#10552)](https://github.com/stdlib-js/stdlib/pull/10552) _(by Om-A-osc)_
-   [`e21c16f`](https://github.com/stdlib-js/stdlib/commit/e21c16fb0ca9a5d7a4018c2189e7aaada33c477e) - **feat:** add `HH_H` macro in `math/base/napi/binary` [(#9577)](https://github.com/stdlib-js/stdlib/pull/9577) _(by Neeraj Pathak, Athan Reines)_
-   [`c265420`](https://github.com/stdlib-js/stdlib/commit/c265420bbb10e78261bf3d1beebe2f5764f0a5c5) - **bench:** update random value generation for `stats/base/dists/f/ctor` [(#10373)](https://github.com/stdlib-js/stdlib/pull/10373) _(by Lokesh Ranjan)_
-   [`c333671`](https://github.com/stdlib-js/stdlib/commit/c3336710c7caf084fc146ddaed7bb9e02a1bb891) - **bench:** refactor to use dynamic memory allocation in `blas/base/sswap` [(#10573)](https://github.com/stdlib-js/stdlib/pull/10573) _(by Prajjwal Bajpai)_
-   [`2e03fe9`](https://github.com/stdlib-js/stdlib/commit/2e03fe9e548309edda7bf7c5c66c3f671a9e2daf) - **bench:** refactor to use dynamic memory allocation in `blas/ext/base/dapxsumkbn2` [(#10574)](https://github.com/stdlib-js/stdlib/pull/10574) _(by Prajjwal Bajpai)_
-   [`a77363d`](https://github.com/stdlib-js/stdlib/commit/a77363df1266f71666762de91ea7b9c7f6022317) - **bench:** use string interpolation in `stats/strided/dmskmin` [(#10570)](https://github.com/stdlib-js/stdlib/pull/10570) _(by Om-A-osc)_
-   [`56b63fa`](https://github.com/stdlib-js/stdlib/commit/56b63fa3c38a36688609217c4f9c4ce9d946f3c0) - **bench:** use string interpolation in `stats/strided/dmskrange` [(#10571)](https://github.com/stdlib-js/stdlib/pull/10571) _(by Om-A-osc)_
-   [`96cd05f`](https://github.com/stdlib-js/stdlib/commit/96cd05f68ec3cb1836e7d357241b90d7d3fb5b8b) - **bench:** refactor to use string interpolation in `ndarray/slice-dimension-to` [(#10523)](https://github.com/stdlib-js/stdlib/pull/10523) _(by Sagar Ratna Chaudhary, Athan Reines)_
-   [`cb4d2f8`](https://github.com/stdlib-js/stdlib/commit/cb4d2f8660ab48b27f7eaf98699300ad4d000c09) - **bench:** use string interpolation in `stats/strided/dnanmax` [(#10572)](https://github.com/stdlib-js/stdlib/pull/10572) _(by Om-A-osc)_
-   [`49a4c22`](https://github.com/stdlib-js/stdlib/commit/49a4c224154a4eb0337818c19353046705c9cea5) - **bench:** refactor to use string interpolation in `blas/ext/base/dapxsumkbn2` [(#10575)](https://github.com/stdlib-js/stdlib/pull/10575) _(by Prajjwal Bajpai)_
-   [`086d2d6`](https://github.com/stdlib-js/stdlib/commit/086d2d61999c12b8ec98b96dbbf9677b835181ea) - **chore:** fix JavaScript lint errors [(#10557)](https://github.com/stdlib-js/stdlib/pull/10557) _(by Partha Das, Athan Reines)_
-   [`a2d1f94`](https://github.com/stdlib-js/stdlib/commit/a2d1f943965c8f2fbd40bb56a71be529c9fa5b82) - **feat:** add C implementation for `stats/base/ndarray/smaxabs` [(#10040)](https://github.com/stdlib-js/stdlib/pull/10040) _(by Samarth Kolarkar, Athan Reines, Sachin Pangal)_
-   [`a2a6b49`](https://github.com/stdlib-js/stdlib/commit/a2a6b49348a8057afc805b27b535dcbce79fd117) - **feat:** add C implementation for `stats/base/ndarray/sminabs` [(#10044)](https://github.com/stdlib-js/stdlib/pull/10044) _(by Samarth Kolarkar, Sachin Pangal)_
-   [`193969a`](https://github.com/stdlib-js/stdlib/commit/193969ac0ad54607dea783913e21eceab9c6d5c3) - **chore:** fix JavaScript lint errors [(#10401)](https://github.com/stdlib-js/stdlib/pull/10401) _(by Vipeen Kumar, Athan Reines)_
-   [`0682ac1`](https://github.com/stdlib-js/stdlib/commit/0682ac10d0ad67b46453f186b3577901886fa42c) - **feat:** add C implementation for `stats/base/ndarray/dmean` [(#10052)](https://github.com/stdlib-js/stdlib/pull/10052) _(by Kaustubh Patange, Athan Reines, Sachin Pangal)_
-   [`ebf2a0a`](https://github.com/stdlib-js/stdlib/commit/ebf2a0a88ad5d3400b62e9769c8095d9768e6e9a) - **chore:** fix JavaScript lint errors [(#10043)](https://github.com/stdlib-js/stdlib/pull/10043) _(by Bhargav Dabhade)_
-   [`217401a`](https://github.com/stdlib-js/stdlib/commit/217401ace9e30879c844967d58e004af54d48336) - **test:** update test message in `stats/strided/distances/dcityblock` [(#10563)](https://github.com/stdlib-js/stdlib/pull/10563) _(by Nakul Krishnakumar)_
-   [`d7c9033`](https://github.com/stdlib-js/stdlib/commit/d7c9033dec5f569d53dd71706ce6f1124e886259) - **feat:** add C implementation for `blas/ext/base/ndarray/dsum` [(#10065)](https://github.com/stdlib-js/stdlib/pull/10065) _(by Kaustubh Patange, Athan Reines)_
-   [`040efaf`](https://github.com/stdlib-js/stdlib/commit/040efaff1efa5576e2625694c19e3a5644c92f5c) - **bench:** refactor to use string interpolation in `array/typed-real` [(#10036)](https://github.com/stdlib-js/stdlib/pull/10036) _(by Aman Singh)_
-   [`de74169`](https://github.com/stdlib-js/stdlib/commit/de7416999fa2bd9a2e912d70b97540b0575d0599) - **feat:** add `blas/ext/base/ndarray/gsort` [(#9734)](https://github.com/stdlib-js/stdlib/pull/9734) _(by Muhammad Haris, Athan Reines)_
-   [`839986d`](https://github.com/stdlib-js/stdlib/commit/839986d9f41ebee28ff3139ec094ab9c8b98d8df) - **test:** ensure dtype equality _(by Athan Reines)_
-   [`7620700`](https://github.com/stdlib-js/stdlib/commit/76207003b2d5be09c0bc2b5bf156c691ba224640) - **docs:** fix type _(by Athan Reines)_
-   [`60fcd9d`](https://github.com/stdlib-js/stdlib/commit/60fcd9dc51b43ad76b1b14e6d7b4c30a5670114a) - **fix:** improve type specificity _(by Athan Reines)_
-   [`b77641d`](https://github.com/stdlib-js/stdlib/commit/b77641d288f89a5333abf07b421cf54e575c5d03) - **feat:** update `ndarray/base` TypeScript declarations [(#10558)](https://github.com/stdlib-js/stdlib/pull/10558) _(by stdlib-bot)_
-   [`2db642e`](https://github.com/stdlib-js/stdlib/commit/2db642edf40e64407f05bcffcb3f0cdae718f8aa) - **feat:** update `ndarray` TypeScript declarations [(#10560)](https://github.com/stdlib-js/stdlib/pull/10560) _(by stdlib-bot)_
-   [`cde3eaa`](https://github.com/stdlib-js/stdlib/commit/cde3eaa0ce2ef0013f69cd458a3ae17b1ed57e56) - **docs:** update REPL namespace documentation [(#10559)](https://github.com/stdlib-js/stdlib/pull/10559) _(by stdlib-bot)_
-   [`2cc758b`](https://github.com/stdlib-js/stdlib/commit/2cc758b7e8b6e3a713cadbabd6d13ad635cb2fcd) - **docs:** update namespace table of contents [(#10561)](https://github.com/stdlib-js/stdlib/pull/10561) _(by stdlib-bot)_
-   [`f7bad8d`](https://github.com/stdlib-js/stdlib/commit/f7bad8d512bc207e4e25ed18a15b43a6e98540aa) - **test:** update test _(by Athan Reines)_
-   [`663e715`](https://github.com/stdlib-js/stdlib/commit/663e715df67c0008b1d807e55a4555e54bf8d5ef) - **test:** update test _(by Athan Reines)_
-   [`93406df`](https://github.com/stdlib-js/stdlib/commit/93406df6ffbb6494062605352b7df9c05694c81d) - **test:** add missing tests _(by Athan Reines)_
-   [`f91aca6`](https://github.com/stdlib-js/stdlib/commit/f91aca6650536cb46c7b4c41bd05a2a37e0fe475) - **feat:** add `maybeBroadcastArrayExceptDimensions` to namespace _(by Athan Reines)_
-   [`5324e96`](https://github.com/stdlib-js/stdlib/commit/5324e9618a4b8688b4792ccceb146b348d9a9f2f) - **feat:** add `ndarray/base/maybe-broadcast-array-except-dimensions` [(#10413)](https://github.com/stdlib-js/stdlib/pull/10413) _(by Muhammad Haris, Athan Reines)_
-   [`f10a6aa`](https://github.com/stdlib-js/stdlib/commit/f10a6aaf98c37bb630ac75e1a50dd0bd4a0eb417) - **fix:** ensure unique indices _(by Athan Reines)_
-   [`9df924b`](https://github.com/stdlib-js/stdlib/commit/9df924b5f0b773c8b06d06b40e54dee75059ce08) - **feat:** add writable parameter support to `ndarray/base/transpose` (#10474) [(#10474)](https://github.com/stdlib-js/stdlib/pull/10474) _(by Muhammad Haris, Athan Reines)_
-   [`e947540`](https://github.com/stdlib-js/stdlib/commit/e947540a4e87841d7bf140094e20b2768250de11) - **feat:** add writable parameter to `ndarray/base/remove-singleton-dimensions` [(#9667)](https://github.com/stdlib-js/stdlib/pull/9667) _(by Muhammad Haris, Athan Reines)_
-   [`e9054b2`](https://github.com/stdlib-js/stdlib/commit/e9054b2892ab8d483449efd9b78aaed53c6fcb2b) - **docs:** add note _(by Athan Reines)_
-   [`116c553`](https://github.com/stdlib-js/stdlib/commit/116c5535ab59050c12731f9cff548b0ae3bb8662) - **bench:** refactor to use string interpolation in `blas/base/wasm/dscal` [(#10545)](https://github.com/stdlib-js/stdlib/pull/10545) _(by Shubham)_
-   [`db9486e`](https://github.com/stdlib-js/stdlib/commit/db9486e09c6c357c40d15ea3685930088827bc4e) - **bench:** refactor to use string interpolation in `blas/base/wasm/drot` [(#10546)](https://github.com/stdlib-js/stdlib/pull/10546) _(by Shubham)_
-   [`5154372`](https://github.com/stdlib-js/stdlib/commit/51543724b7c82e0825fcac2de00d6267ae043d4e) - **bench:** refactor to use string interpolation in `blas/base/wasm/dznrm2` [(#10547)](https://github.com/stdlib-js/stdlib/pull/10547) _(by Shubham)_
-   [`75fe17b`](https://github.com/stdlib-js/stdlib/commit/75fe17b70513a2f00bbffc911a7007084c781d13) - **bench:** refactor to use string interpolation in `blas/base/wasm/dswap` [(#10548)](https://github.com/stdlib-js/stdlib/pull/10548) _(by Shubham)_
-   [`43e7c3a`](https://github.com/stdlib-js/stdlib/commit/43e7c3ac1af11e9f93a122a2e09d6e0a3b4a2cd5) - **bench:** refactor to use string interpolation in `blas/base/wasm/dsdot` [(#10549)](https://github.com/stdlib-js/stdlib/pull/10549) _(by Shubham)_
-   [`1f61670`](https://github.com/stdlib-js/stdlib/commit/1f61670cd14e63d5dec2da8950a2d42a76542e4b) - **bench:** refactor to use string interpolation in `blas/base/wasm/drotm` [(#10550)](https://github.com/stdlib-js/stdlib/pull/10550) _(by Shubham)_
-   [`53fb242`](https://github.com/stdlib-js/stdlib/commit/53fb24251d7be54ea7424b60a991f5eaf96fe32a) - **bench:** refactor to use string interpolation in `symbol/ctor` [(#10555)](https://github.com/stdlib-js/stdlib/pull/10555) _(by Vishal Gaikwad)_
-   [`e5af570`](https://github.com/stdlib-js/stdlib/commit/e5af57010dbb7c873ea46afe2662c8ceb44ac637) - **feat:** add `atleastnd` to namespace _(by Athan Reines)_
-   [`53caca8`](https://github.com/stdlib-js/stdlib/commit/53caca808d0b9aad069992056c6fe64b0c780e8f) - **feat:** add `ndarray/base/atleastnd` [(#10422)](https://github.com/stdlib-js/stdlib/pull/10422) _(by Muhammad Haris, Athan Reines)_
-   [`177c9b9`](https://github.com/stdlib-js/stdlib/commit/177c9b9ef19cd92078c39b8f8aa0bd8364fb6ca3) - **docs:** fix notes _(by Athan Reines)_
-   [`8e51991`](https://github.com/stdlib-js/stdlib/commit/8e519911fa82286c82b696e058c5da2fba071c3e) - **style:** revert style changes _(by Athan Reines)_
-   [`c3789be`](https://github.com/stdlib-js/stdlib/commit/c3789bef602f59a085b2dd60fe691357e323da99) - **docs:** fix example _(by Athan Reines)_
-   [`2d771d9`](https://github.com/stdlib-js/stdlib/commit/2d771d906a8ecd41c343ca61128107aa7d7c18e5) - **bench:** update random value generation for `stats/base/dists/gumbel/entropy` [(#10362)](https://github.com/stdlib-js/stdlib/pull/10362) _(by Bhargav Dabhade)_
-   [`965c4b9`](https://github.com/stdlib-js/stdlib/commit/965c4b9341f4a3b721a06bfd5c48e1393b5ab59d) - **chore:** fix JavaScript lint errors [(#10380)](https://github.com/stdlib-js/stdlib/pull/10380) _(by Bhargav Dabhade)_
-   [`94c1431`](https://github.com/stdlib-js/stdlib/commit/94c143124e150a3751b1a70205917f986dca8c03) - **feat:** add `stats/strided/dnanmskminabs` [(#10382)](https://github.com/stdlib-js/stdlib/pull/10382) _(by Sachin Pangal)_
-   [`786e059`](https://github.com/stdlib-js/stdlib/commit/786e0590341f600854e001e75285b7a6afdb7319) - **chore:** fix C lint errors [(#10418)](https://github.com/stdlib-js/stdlib/pull/10418) _(by Geo Daoyu)_
-   [`89d9070`](https://github.com/stdlib-js/stdlib/commit/89d9070d056ca57753d003ed352b830e4c36a7a0) - **bench:** refactor to use string interpolation in `buffer/from-string` [(#10500)](https://github.com/stdlib-js/stdlib/pull/10500) _(by Kamal Singh Rautela)_
-   [`c890b1a`](https://github.com/stdlib-js/stdlib/commit/c890b1ad0c88bdb2ec57a7e423f835a15947bfd5) - **bench:** refactor to use string interpolation in `blas/ext/base/dcusum` [(#10532)](https://github.com/stdlib-js/stdlib/pull/10532) _(by Kamal Singh Rautela)_
-   [`7eb18f2`](https://github.com/stdlib-js/stdlib/commit/7eb18f24166f78119540ec88e652e5643a5d2518) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`9221bdb`](https://github.com/stdlib-js/stdlib/commit/9221bdb56bac8544a387c8b8f74ae69ae5ec2961) - **feat:** add `toTransposed` to namespace _(by Athan Reines)_
-   [`5606366`](https://github.com/stdlib-js/stdlib/commit/560636601a3ebbc74e58ba18752ba832c3548215) - **feat:** add `ndarray/base/to-transposed` [(#10499)](https://github.com/stdlib-js/stdlib/pull/10499) _(by Muhammad Haris, Athan Reines)_
-   [`cd6574f`](https://github.com/stdlib-js/stdlib/commit/cd6574f18432cbcc57d476f00bc58d255ac13f0a) - **style:** revert style changes _(by Athan Reines)_
-   [`b721461`](https://github.com/stdlib-js/stdlib/commit/b721461895b04dd66f0915c76347244a7cc56148) - **docs:** revert style changes _(by Athan Reines)_
-   [`01a25b3`](https://github.com/stdlib-js/stdlib/commit/01a25b340fc172d9754d027cc09330e0be32babb) - **feat:** add `unflattenShape` to namespace _(by Athan Reines)_
-   [`4049c73`](https://github.com/stdlib-js/stdlib/commit/4049c7358fb474ef3b7c3f1a1dc94206c37fd105) - **feat:** add `ndarray/base/unflatten-shape` [(#10441)](https://github.com/stdlib-js/stdlib/pull/10441) _(by Muhammad Haris, Athan Reines)_
-   [`fda918b`](https://github.com/stdlib-js/stdlib/commit/fda918b01397d0a842c3d3fb87a4680122eaa8ff) - **docs:** fix section structure and lint errors in READMEs _(by Philipp Burckhardt)_
-   [`3024bb3`](https://github.com/stdlib-js/stdlib/commit/3024bb37f70bf55295d9c4bf81107ff57c15ff8a) - **docs:** fix section comments and lint errors in `array` and `assert` READMEs _(by Philipp Burckhardt)_
-   [`3422651`](https://github.com/stdlib-js/stdlib/commit/3422651a3ec2e6717f25d82020a62f00dbe2aa78) - **docs:** add missing section closing comments in READMEs _(by Philipp Burckhardt)_
-   [`40a80f6`](https://github.com/stdlib-js/stdlib/commit/40a80f62a767edfc5d664d617f44a4b8cb335cdd) - **docs:** add missing section closing comments in `math/base/special` READMEs _(by Philipp Burckhardt)_
-   [`abedf58`](https://github.com/stdlib-js/stdlib/commit/abedf5837f3b62af132cc2e9a8dac5dabc3939bc) - **docs:** fix typo in section closing comments in `math/base/special/gammasgn*` READMEs _(by Philipp Burckhardt)_
-   [`078b193`](https://github.com/stdlib-js/stdlib/commit/078b19390e586d8fd746133f6f51f65a513da49b) - **docs:** fix orphaned section comments in `assert/is-*` READMEs _(by Philipp Burckhardt)_
-   [`ee1f1a7`](https://github.com/stdlib-js/stdlib/commit/ee1f1a7b7d7de0dba506731a05698e0bb43b2d1c) - **docs:** fix wrong section order in `stats/base/dists` and `stats/strided` READMEs _(by Philipp Burckhardt)_
-   [`0249e24`](https://github.com/stdlib-js/stdlib/commit/0249e2403b412deca30b2675326eaef513a7ce3e) - **docs:** remove redundant NaN notes in `stats/base/ndarray/dnanstdev*` READMEs _(by Philipp Burckhardt)_
-   [`f886d31`](https://github.com/stdlib-js/stdlib/commit/f886d3153a4fd2e2270db0475ba4a4ece0a5d26e) - **docs:** fix orphaned section comments in `stats/base/dists/geometric` READMEs _(by Philipp Burckhardt)_
-   [`0d32b1b`](https://github.com/stdlib-js/stdlib/commit/0d32b1b98dc0bf319b6330e9535e2a3ba0980adf) - **feat:** add `toReversedDimension` to namespace _(by Athan Reines)_
-   [`287c085`](https://github.com/stdlib-js/stdlib/commit/287c08582a945209e4b6da083fbd8102b8bf8321) - **feat:** add `ndarray/to-reversed-dimension` [(#10058)](https://github.com/stdlib-js/stdlib/pull/10058) _(by Muhammad Haris, Athan Reines)_
-   [`841ab2e`](https://github.com/stdlib-js/stdlib/commit/841ab2eab4f9ee75fc3c99b0dfc186051061e0bf) - **bench:** refactor to use string interpolation in `blas/base/wasm/daxpy` [(#10505)](https://github.com/stdlib-js/stdlib/pull/10505) _(by Shubham)_
-   [`34a2bca`](https://github.com/stdlib-js/stdlib/commit/34a2bcac9bd7b76456a57cd7bcbfea5a8da4c7be) - **bench:** refactor to use string interpolation in `blas/base/wasm/dasum` [(#10506)](https://github.com/stdlib-js/stdlib/pull/10506) _(by Shubham)_
-   [`680d163`](https://github.com/stdlib-js/stdlib/commit/680d163820a00a331e89bcd9aabc5fcd3cc8d2c4) - **bench:** refactor to use string interpolation in `blas/base/wasm/ddot` [(#10507)](https://github.com/stdlib-js/stdlib/pull/10507) _(by Shubham)_
-   [`0024bd6`](https://github.com/stdlib-js/stdlib/commit/0024bd635fe210b1d2a13ccc6abf34633a9cd1d7) - **bench:** refactor to use string interpolation in `blas/base/wasm/dcopy` [(#10508)](https://github.com/stdlib-js/stdlib/pull/10508) _(by Shubham)_
-   [`ea168c7`](https://github.com/stdlib-js/stdlib/commit/ea168c728e02cb236ed771716c785534b6b77dad) - **bench:** refactor to use string interpolation in `blas/base/wasm/dnrm2` [(#10509)](https://github.com/stdlib-js/stdlib/pull/10509) _(by Shubham)_
-   [`5e94b53`](https://github.com/stdlib-js/stdlib/commit/5e94b5366163e541eee1767360ac01eecf4a5df4) - **bench:** use string interpolation in `blas/base/dspr` [(#10516)](https://github.com/stdlib-js/stdlib/pull/10516) _(by Om-A-osc)_
-   [`a65cb70`](https://github.com/stdlib-js/stdlib/commit/a65cb70770257d5d69d35aa6b6b2d76879f33dfc) - **bench:** refactor to use string interpolation in `strided/base/binary-addon-dispatch` [(#10519)](https://github.com/stdlib-js/stdlib/pull/10519) _(by Vishal Gaikwad)_
-   [`2b0c8cd`](https://github.com/stdlib-js/stdlib/commit/2b0c8cd4d13f0f5d4fd5b9f464e40b5e239cd7c8) - **bench:** refactor to use string interpolation in `strided/dispatch` [(#10520)](https://github.com/stdlib-js/stdlib/pull/10520) _(by Vishal Gaikwad)_
-   [`8bb0e6f`](https://github.com/stdlib-js/stdlib/commit/8bb0e6f15ff0a45a403393551d630830ee0afa05) - **bench:** use string interpolation in `blas/base/dsymv` [(#10521)](https://github.com/stdlib-js/stdlib/pull/10521) _(by Om-A-osc)_
-   [`e71e7b6`](https://github.com/stdlib-js/stdlib/commit/e71e7b60f251ecec8e5591f4b9580e5b133da2b5) - **bench:** refactor to use string interpolation in `strided/dispatch-by` [(#10522)](https://github.com/stdlib-js/stdlib/pull/10522) _(by Vishal Gaikwad)_
-   [`e7a30dc`](https://github.com/stdlib-js/stdlib/commit/e7a30dcc468a1db97d78ae16cea85090a13d5fac) - **feat:** add `broadcastScalar` to namespace _(by Athan Reines)_
-   [`6bc5ee5`](https://github.com/stdlib-js/stdlib/commit/6bc5ee550629c3aaae7687630c315d607c185ba9) - **feat:** add `ndarray/broadcast-scalar` [(#9916)](https://github.com/stdlib-js/stdlib/pull/9916) _(by Muhammad Haris, Athan Reines)_
-   [`e8b00ab`](https://github.com/stdlib-js/stdlib/commit/e8b00abfb7e1a012c9df982553c6ede3f6b261d9) - **feat:** add `unshift` to namespace _(by Athan Reines)_
-   [`d703ebd`](https://github.com/stdlib-js/stdlib/commit/d703ebd30fb8f62c7e3718074648bb901de0c267) - **feat:** add `spreadDimensions` to namespace _(by Athan Reines)_
-   [`853269d`](https://github.com/stdlib-js/stdlib/commit/853269d40f022bbeb9dfb3b751ec9e3da769e1db) - **feat:** add `some` to namespace _(by Athan Reines)_
-   [`e4dc41b`](https://github.com/stdlib-js/stdlib/commit/e4dc41b5cb957c29d5035de9f1a03b23596f5df2) - **feat:** add `push` to namespace _(by Athan Reines)_
-   [`2b44a14`](https://github.com/stdlib-js/stdlib/commit/2b44a14f3e9320f09189749176998ed6ce21d459) - **feat:** add `prependSingletonDimensions` to namespace _(by Athan Reines)_
-   [`6438f89`](https://github.com/stdlib-js/stdlib/commit/6438f8920f0cdbb525f7b1a1b4c818806e48da2b) - **feat:** add `flipud` to namespace _(by Athan Reines)_
-   [`5a4177b`](https://github.com/stdlib-js/stdlib/commit/5a4177bef249b76469c6cd06218acf33e72762d5) - **feat:** add `fliplr` to namespace _(by Athan Reines)_
-   [`9a7bd40`](https://github.com/stdlib-js/stdlib/commit/9a7bd407645ceeac99c6ac8bf46a905dad66739d) - **feat:** add `flattenFromBy` to namespace _(by Athan Reines)_
-   [`f53b521`](https://github.com/stdlib-js/stdlib/commit/f53b521efeef869b0ef0ccf07e878bdeaa2fed12) - **feat:** add `findLast` to namespace _(by Athan Reines)_
-   [`39c40c5`](https://github.com/stdlib-js/stdlib/commit/39c40c569825bc185a8e8a802452ed1ebaed7ece) - **feat:** add `concat1d` to namespace _(by Athan Reines)_
-   [`78d37a0`](https://github.com/stdlib-js/stdlib/commit/78d37a025058a2260ccfe38ff5ead8ab9e09af3e) - **feat:** add `scalar2ndarrayLike` to namespace _(by Athan Reines)_
-   [`9bdd54a`](https://github.com/stdlib-js/stdlib/commit/9bdd54a97d6458edeb891ac49cbcffa86470e354) - **docs:** update description _(by Athan Reines)_
-   [`2b0c11f`](https://github.com/stdlib-js/stdlib/commit/2b0c11f5339edc83e5de241d702230e73552136d) - **feat:** add `ndarray/from-scalar-like` [(#9940)](https://github.com/stdlib-js/stdlib/pull/9940) _(by Muhammad Haris, Athan Reines)_
-   [`793a38c`](https://github.com/stdlib-js/stdlib/commit/793a38c29f31677807e0cf6748f1ca54fbbef4ec) - **feat:** add `toLocaleString` method to `ndarray/base/ctor` [(#9435)](https://github.com/stdlib-js/stdlib/pull/9435) _(by Muhammad Haris, Athan Reines)_
-   [`9687965`](https://github.com/stdlib-js/stdlib/commit/96879652e1c3ee69d36d5abcc6296b4830bee4a9) - **chore:** address commit comments for commit `8b01d81` [(#10433)](https://github.com/stdlib-js/stdlib/pull/10433) _(by Daniel Mungai Chege)_
-   [`a78342c`](https://github.com/stdlib-js/stdlib/commit/a78342cc43324f4c168429d8c76c85691f502faf) - **chore:** fix JavaScript lint errors [(#10482)](https://github.com/stdlib-js/stdlib/pull/10482) _(by Aryan kumar)_
-   [`5cad666`](https://github.com/stdlib-js/stdlib/commit/5cad666695971ba8af5bc2392893d1f32687a1f1) - **bench:** refactor to use string interpolation in `array/empty-like` [(#10484)](https://github.com/stdlib-js/stdlib/pull/10484) _(by Aman Singh)_
-   [`05e2a72`](https://github.com/stdlib-js/stdlib/commit/05e2a7238d6385111152d041b60e1f27d478db97) - **bench:** refactor to use string interpolation in `array/fixed-endian-float32` [(#10486)](https://github.com/stdlib-js/stdlib/pull/10486) _(by Aman Singh)_
-   [`872f2fa`](https://github.com/stdlib-js/stdlib/commit/872f2fae9ed2edd497d3fc48dafc129f73dc103d) - **bench:** refactor to use string interpolation in `blas/base/wasm/ccopy` [(#10487)](https://github.com/stdlib-js/stdlib/pull/10487) _(by Shubham)_
-   [`4ff9eb4`](https://github.com/stdlib-js/stdlib/commit/4ff9eb447269f2a45e7a7deb589e8675e67af11e) - **bench:** refactor to use string interpolation in `blas/base/wasm/cscal` [(#10488)](https://github.com/stdlib-js/stdlib/pull/10488) _(by Shubham)_
-   [`e7bbe68`](https://github.com/stdlib-js/stdlib/commit/e7bbe68e59ac0a3adb146adab70fb5db47038847) - **bench:** refactor to use string interpolation in `blas/base/wasm/csrot` [(#10489)](https://github.com/stdlib-js/stdlib/pull/10489) _(by Shubham)_
-   [`3dd5b4f`](https://github.com/stdlib-js/stdlib/commit/3dd5b4fd6aea4394b8a39b587961d2f94c4cdd9c) - **bench:** refactor to use string interpolation in `blas/base/sswap` [(#10491)](https://github.com/stdlib-js/stdlib/pull/10491) _(by Shubham)_
-   [`6080e64`](https://github.com/stdlib-js/stdlib/commit/6080e640d14b68905c598330ebcb6bb8e415ddd0) - **style:** remove whitespace inside `API_SUFFIX` macro calls _(by Philipp Burckhardt)_
-   [`4756e95`](https://github.com/stdlib-js/stdlib/commit/4756e952607ba75dc0013d2b8e226e7d3db000d9) - **docs:** use \"probability mass function\" instead of \"probability density function\" for PMF methods _(by Philipp Burckhardt)_
-   [`383707f`](https://github.com/stdlib-js/stdlib/commit/383707fb11279899f663267e47dcb303070f63b4) - **fix:** remove erroneous `browser` field excluding `ndarray` method in `stats/strided/mskminabs` and `blas/ext/base/gnannsumkbn` _(by Philipp Burckhardt)_
-   [`6154a32`](https://github.com/stdlib-js/stdlib/commit/6154a32beaac09d20e3f76af7daabf41bfa22c32) - **docs:** fix section tags and disable spellcheck for false positives in README files _(by Philipp Burckhardt)_
-   [`e5fc414`](https://github.com/stdlib-js/stdlib/commit/e5fc414b47afe395178b88858a9731651f409b46) - **chore:** fix JSDoc and spacing issues _(by Philipp Burckhardt)_
-   [`0ebd0ed`](https://github.com/stdlib-js/stdlib/commit/0ebd0ed2722511ffc2a8a158a387aeb90d915c8f) - **docs:** fix lint errors in README files _(by Philipp Burckhardt)_
-   [`8101713`](https://github.com/stdlib-js/stdlib/commit/810171368ca80b1d10b4782987cb509a5be2c869) - **docs:** add missing C examples sections in `constants/float32` README files _(by Philipp Burckhardt)_
-   [`46f06ad`](https://github.com/stdlib-js/stdlib/commit/46f06ad6754741320241c60ff79ffdf0a7175b07) - **docs:** fix section tags in README files _(by Philipp Burckhardt)_
-   [`4fb4995`](https://github.com/stdlib-js/stdlib/commit/4fb49958095bee6d0cfee8b5d63fcfdf94f87e6e) - **docs:** fix missing and malformed section tags in README files _(by Philipp Burckhardt)_
-   [`c66d383`](https://github.com/stdlib-js/stdlib/commit/c66d383f66a223c0bfc3c099ba59826b8f22c783) - **docs:** add missing semicolons in `blas/ext` TypeScript examples _(by Philipp Burckhardt)_
-   [`f7191c0`](https://github.com/stdlib-js/stdlib/commit/f7191c093f0607ad6de9b7a21612f36bb3a84d90) - **chore:** use relative paths and remove trailing slashes in require paths _(by Philipp Burckhardt)_
-   [`b7879ad`](https://github.com/stdlib-js/stdlib/commit/b7879adce2d3bf7a6a1d4e626fd60172b3e33155) - **docs:** fix missing and malformed section closing tags in README files _(by Philipp Burckhardt)_
-   [`0ca797b`](https://github.com/stdlib-js/stdlib/commit/0ca797b5558b96111256a7446eafe101761b240b) - **bench:** use float literals for `uniform` range arguments _(by Philipp Burckhardt)_
-   [`685691c`](https://github.com/stdlib-js/stdlib/commit/685691c6065af53a0527bcd690d1ade468f452df) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`10cd4eb`](https://github.com/stdlib-js/stdlib/commit/10cd4ebe76e9d71bf4de1807716e1cc9ff5edf79) - **style:** add spaces and use leading slash in relative require _(by Philipp Burckhardt)_
-   [`12181cb`](https://github.com/stdlib-js/stdlib/commit/12181cb83b3a9a3092d9c41170c31d83db2c0636) - **chore:** use relative path and update spacing _(by Philipp Burckhardt)_
-   [`157ea4e`](https://github.com/stdlib-js/stdlib/commit/157ea4e1fe500feee3e8252c9e03162da1b53db7) - **chore:** use relative paths _(by Philipp Burckhardt)_
-   [`707fcd4`](https://github.com/stdlib-js/stdlib/commit/707fcd4483bd8989ea064842812555f5e382dc52) - **feat:** add `stats/base/ndarray/dnanstdevpn` [(#10375)](https://github.com/stdlib-js/stdlib/pull/10375) _(by Pratik, Athan Reines)_
-   [`8318891`](https://github.com/stdlib-js/stdlib/commit/8318891b30c2a8f2649e386f2abba4d064111c54) - **docs:** improve doctest for ndarray instances in `math/tools/unary` [(#10470)](https://github.com/stdlib-js/stdlib/pull/10470) _(by AyushiJain18270)_
-   [`8156d8e`](https://github.com/stdlib-js/stdlib/commit/8156d8e838de021a64886a2d4879ac898695389d) - **bench:** refactor to use string interpolation in `math/base/utils` [(#10473)](https://github.com/stdlib-js/stdlib/pull/10473) _(by Vishal Gaikwad)_
-   [`1c79757`](https://github.com/stdlib-js/stdlib/commit/1c79757a58ad07f354d864008d6f898d891cb540) - **bench:** refactor to use string interpolation in `stats/base/cuminabs` [(#10472)](https://github.com/stdlib-js/stdlib/pull/10472) _(by Vishal Gaikwad)_
-   [`8f0eca3`](https://github.com/stdlib-js/stdlib/commit/8f0eca3776656e00cdc36beb5bf6acb57ace9940) - **bench:** refactor to use string interpolation in `stats/base/cumin` [(#10471)](https://github.com/stdlib-js/stdlib/pull/10471) _(by Vishal Gaikwad)_
-   [`a448775`](https://github.com/stdlib-js/stdlib/commit/a44877524a5d66af917bdac7d3e2ea7e74ff6329) - **docs:** update `blas/ext/base/ndarray` TypeScript declarations [(#10477)](https://github.com/stdlib-js/stdlib/pull/10477) _(by stdlib-bot)_
-   [`823392d`](https://github.com/stdlib-js/stdlib/commit/823392d1ffb3c5284df53c1be033150b87d6ad85) - **docs:** update `math/special` TypeScript declarations [(#10479)](https://github.com/stdlib-js/stdlib/pull/10479) _(by stdlib-bot)_
-   [`33a845a`](https://github.com/stdlib-js/stdlib/commit/33a845af56916162ec6229a6ea8c51b48017ac20) - **docs:** update REPL namespace documentation [(#10478)](https://github.com/stdlib-js/stdlib/pull/10478) _(by stdlib-bot)_
-   [`500788a`](https://github.com/stdlib-js/stdlib/commit/500788a9423352a0e8fd50b7eda644ff8e79c8b9) - **test:** use relative paths _(by Philipp Burckhardt)_
-   [`ddc8202`](https://github.com/stdlib-js/stdlib/commit/ddc820270cfbdc5f88b832442bf62752bbdc2b78) - **docs:** improve doctests for ndarray instances in `math/special/abs` [(#10435)](https://github.com/stdlib-js/stdlib/pull/10435) _(by AyushiJain18270)_
-   [`d65bf73`](https://github.com/stdlib-js/stdlib/commit/d65bf7356a9f65e0e512ac1a6809e731528a09a9) - **fix:** rename incorrect manifest file name in `constants/float32/max-ln` [(#10167)](https://github.com/stdlib-js/stdlib/pull/10167) _(by Shubham)_
-   [`9f7e9c8`](https://github.com/stdlib-js/stdlib/commit/9f7e9c8319f1557ae399ddde2f912ef86361a9f9) - **docs:** improve doctests for ndarray instances in `ndarray/scusum` [(#10403)](https://github.com/stdlib-js/stdlib/pull/10403) _(by AyushiJain18270)_
-   [`920af07`](https://github.com/stdlib-js/stdlib/commit/920af071bafa97f0a933d6c3f0d04e33ad7e0b39) - **bench:** refactor to use string interpolation in `blas/base/ssymv` [(#10456)](https://github.com/stdlib-js/stdlib/pull/10456) _(by Lokesh Ranjan)_
-   [`b01344e`](https://github.com/stdlib-js/stdlib/commit/b01344ed3b330781f2fc55fb1cfd652cae06d4f1) - **bench:** refactor to use string interpolation in `stats/kstest` [(#10457)](https://github.com/stdlib-js/stdlib/pull/10457) _(by Kamal Singh Rautela)_
-   [`5b091c2`](https://github.com/stdlib-js/stdlib/commit/5b091c2142b1eb2472a7049910be65fcda5a87bf) - **bench:** refactor to use string interpolation in `blas/base/ssyr` [(#10458)](https://github.com/stdlib-js/stdlib/pull/10458) _(by Lokesh Ranjan)_
-   [`7784156`](https://github.com/stdlib-js/stdlib/commit/7784156d4d3b0f963e2b91005dfcd6cde2787770) - **bench:** refactor to use string interpolation in `stats/maxsorted` [(#10459)](https://github.com/stdlib-js/stdlib/pull/10459) _(by Kamal Singh Rautela)_
-   [`ce9806d`](https://github.com/stdlib-js/stdlib/commit/ce9806d70a5ca2d24fc81930a0bd84a58203769e) - **bench:** refactor to use string interpolation in `blas/base/ssyr2` [(#10460)](https://github.com/stdlib-js/stdlib/pull/10460) _(by Lokesh Ranjan)_
-   [`e540461`](https://github.com/stdlib-js/stdlib/commit/e540461e94f4d7bcc56d361e0fc4d24790143b52) - **bench:** refactor to use string interpolation in `blas/base/strmv` [(#10461)](https://github.com/stdlib-js/stdlib/pull/10461) _(by Lokesh Ranjan)_
-   [`4e515d0`](https://github.com/stdlib-js/stdlib/commit/4e515d00f1842205ce95fa65d53d95d19b1ee939) - **bench:** refactor to use string interpolation in `stats/nanmax-by` [(#10462)](https://github.com/stdlib-js/stdlib/pull/10462) _(by Kamal Singh Rautela)_
-   [`23afcd1`](https://github.com/stdlib-js/stdlib/commit/23afcd14843e27539f59f83026a53cabe4bb3a1c) - **bench:** refactor to use string interpolation in `blas/base/strsv` [(#10463)](https://github.com/stdlib-js/stdlib/pull/10463) _(by Lokesh Ranjan)_
-   [`7f69289`](https://github.com/stdlib-js/stdlib/commit/7f69289b72f9026099def38e09c93ee50068b056) - **bench:** update random value generation for `stats/base/dists/gumbel/mean` [(#10363)](https://github.com/stdlib-js/stdlib/pull/10363) _(by Bhargav Dabhade)_
-   [`a60fc25`](https://github.com/stdlib-js/stdlib/commit/a60fc2596e69278abc19df474aa63f259f9bdbe5) - **test:** use powf in `absgammaInf` [(#10437)](https://github.com/stdlib-js/stdlib/pull/10437) _(by Sagar Ratna Chaudhary)_
-   [`0c1fea4`](https://github.com/stdlib-js/stdlib/commit/0c1fea42a94d1ec0d4ba8e9f29e411f0f3515041) - **bench:** update random value generation for `stats/base/dists/levy` [(#10449)](https://github.com/stdlib-js/stdlib/pull/10449) _(by Lokesh Ranjan, Philipp Burckhardt)_
-   [`6d2d900`](https://github.com/stdlib-js/stdlib/commit/6d2d90074716499c606c3e446afef21e58f71ba5) - **bench:** refactor to use string interpolation in `blas/base/sgemv` [(#10450)](https://github.com/stdlib-js/stdlib/pull/10450) _(by Lokesh Ranjan)_
-   [`0e4b6e6`](https://github.com/stdlib-js/stdlib/commit/0e4b6e646f948b05a305094846a61f99862f9b63) - **bench:** refactor to use string interpolation in `blas/base/sger` [(#10451)](https://github.com/stdlib-js/stdlib/pull/10451) _(by Lokesh Ranjan)_
-   [`4be2dc5`](https://github.com/stdlib-js/stdlib/commit/4be2dc517dc9668611f34b2a57c8a90fa5b48d53) - **bench:** refactor to use string interpolation in `blas/base/snrm2` [(#10452)](https://github.com/stdlib-js/stdlib/pull/10452) _(by Lokesh Ranjan)_
-   [`5faf52b`](https://github.com/stdlib-js/stdlib/commit/5faf52b86b2a03b2ac4434598792700547a5a81f) - **bench:** refactor to use string interpolation in `blas/base/srotg` [(#10453)](https://github.com/stdlib-js/stdlib/pull/10453) _(by Lokesh Ranjan)_
-   [`78c066a`](https://github.com/stdlib-js/stdlib/commit/78c066ad4f3da1d33317f3188b77ea0436ea7428) - **bench:** refactor to use string interpolation in `blas/base/sscal` [(#10454)](https://github.com/stdlib-js/stdlib/pull/10454) _(by Lokesh Ranjan)_
-   [`9a0fc0a`](https://github.com/stdlib-js/stdlib/commit/9a0fc0a169aba8d7986307a49dcdb5ee6b0eeb15) - **bench:** refactor to use string interpolation in `blas/base/sspmv` [(#10455)](https://github.com/stdlib-js/stdlib/pull/10455) _(by Lokesh Ranjan)_
-   [`1ca4102`](https://github.com/stdlib-js/stdlib/commit/1ca410285a07bc2fe47b66732c4c24bfadd50771) - **chore:** fix EditorConfig lint errors [(#10406)](https://github.com/stdlib-js/stdlib/pull/10406) _(by Kamal Singh Rautela)_
-   [`45e5fab`](https://github.com/stdlib-js/stdlib/commit/45e5fabec7c1617c1aa88cc757ade2f799221a38) - **bench:** refactor to use string interpolation in `stats/base/dists/geometric` [(#10361)](https://github.com/stdlib-js/stdlib/pull/10361) _(by Vishal Gaikwad, Athan Reines)_
-   [`6146ff9`](https://github.com/stdlib-js/stdlib/commit/6146ff9bbfd717fab87a500642ceb09c693eb24d) - **bench:** update random value generation for `stats/base/dists/levy/ctor` [(#10443)](https://github.com/stdlib-js/stdlib/pull/10443) _(by Lokesh Ranjan)_
-   [`8a6c701`](https://github.com/stdlib-js/stdlib/commit/8a6c701c26772991b4f50e0d2b5194d676c80d1b) - **bench:** refactor to use string interpolation in `stats/base/dists/invgamma` [(#10442)](https://github.com/stdlib-js/stdlib/pull/10442) _(by Lokesh Ranjan)_
-   [`bdd38d9`](https://github.com/stdlib-js/stdlib/commit/bdd38d971f4c0a24d43aca632ca5098cc0b90332) - **bench:** refactor to use string interpolation in `stats/base/dists/levy` [(#10444)](https://github.com/stdlib-js/stdlib/pull/10444) _(by Vishal Gaikwad)_
-   [`797d3a0`](https://github.com/stdlib-js/stdlib/commit/797d3a0bbe3f062d53e7ff8b7919e54a0e6c0d00) - **bench:** refactor to use string interpolation in `stats/base/dists/lognormal` [(#10445)](https://github.com/stdlib-js/stdlib/pull/10445) _(by Vishal Gaikwad)_
-   [`3f8da9f`](https://github.com/stdlib-js/stdlib/commit/3f8da9f06286333269e9065344b495a7d91fffa4) - **bench:** refactor to use string interpolation in `stats/base/dists/laplace` [(#10440)](https://github.com/stdlib-js/stdlib/pull/10440) _(by Vishal Gaikwad)_
-   [`6c08cf3`](https://github.com/stdlib-js/stdlib/commit/6c08cf3af7e3b88320f7bb153220328a0872c64e) - **bench:** refactor to use string interpolation in `stats/base/dists/negative-binomial` [(#10446)](https://github.com/stdlib-js/stdlib/pull/10446) _(by Vishal Gaikwad)_
-   [`c1755b9`](https://github.com/stdlib-js/stdlib/commit/c1755b981f95c57388279aa966dfc43595434846) - **bench:** refactor to use string interpolation in `blas/base/isamax` [(#10428)](https://github.com/stdlib-js/stdlib/pull/10428) _(by Shubham)_
-   [`833eeed`](https://github.com/stdlib-js/stdlib/commit/833eeed3643df0fd0d94df57c68065b8ada8a74f) - **bench:** refactor to use string interpolation in `blas/base/sasum` [(#10429)](https://github.com/stdlib-js/stdlib/pull/10429) _(by Shubham)_
-   [`82e5efd`](https://github.com/stdlib-js/stdlib/commit/82e5efd18ff2c2d276e88e4384e49d5f32c24959) - **bench:** refactor to use string interpolation in `blas/base/scasum` [(#10430)](https://github.com/stdlib-js/stdlib/pull/10430) _(by Shubham)_
-   [`a8411ae`](https://github.com/stdlib-js/stdlib/commit/a8411ae90fd217e642d0d70ffa6cd2494967f73d) - **bench:** refactor to use string interpolation in `blas/base/scnrm2` [(#10431)](https://github.com/stdlib-js/stdlib/pull/10431) _(by Shubham)_
-   [`02d748a`](https://github.com/stdlib-js/stdlib/commit/02d748a8c61dcb97200e82857b2fde9b3ae84f83) - **bench:** refactor to use string interpolation in `iter/push` [(#10434)](https://github.com/stdlib-js/stdlib/pull/10434) _(by Sagar Ratna Chaudhary)_
-   [`e9e7da0`](https://github.com/stdlib-js/stdlib/commit/e9e7da08db53d90feb98a6926e29d388c5de117e) - **bench:** refactor to use string interpolation in `array/base/broadcasted-quaternary4d` [(#10436)](https://github.com/stdlib-js/stdlib/pull/10436) _(by anee3)_
-   [`c695d88`](https://github.com/stdlib-js/stdlib/commit/c695d883771b97f493c0d370973fbd2bd39d521e) - **bench:** refactor to use string interpolation in `array/base/broadcasted-quinary2d` [(#10438)](https://github.com/stdlib-js/stdlib/pull/10438) _(by anee3)_
-   [`6564170`](https://github.com/stdlib-js/stdlib/commit/6564170f3bf0724a927a23b64f3c624294978182) - **bench:** refactor to use string interpolation in `array/empty` [(#10439)](https://github.com/stdlib-js/stdlib/pull/10439) _(by Aman Singh)_
-   [`4afe7e2`](https://github.com/stdlib-js/stdlib/commit/4afe7e2c67726f35d17696cb100df1bc94f09db9) - **style:** add missing space [(#10061)](https://github.com/stdlib-js/stdlib/pull/10061) _(by LZYCODEr, stdlib-bot)_
-   [`ac2de21`](https://github.com/stdlib-js/stdlib/commit/ac2de219ef2fb87ceb61360e6c267c5ab1e3cdbb) - **style:** replace erroneous tab character with space _(by Philipp Burckhardt)_
-   [`5df50ac`](https://github.com/stdlib-js/stdlib/commit/5df50ac0f9c50b825e81aae2e10a3d843692e140) - **style:** disable lint rule [(#10356)](https://github.com/stdlib-js/stdlib/pull/10356) _(by nickolaif-svg, Athan Reines)_
-   [`77a562a`](https://github.com/stdlib-js/stdlib/commit/77a562af730f04df4f25308c21fca66cb994b65a) - **bench:** refactor to use string interpolation in `stats/base/dists/hypergeometric` [(#10390)](https://github.com/stdlib-js/stdlib/pull/10390) _(by Vishal Gaikwad)_
-   [`8620184`](https://github.com/stdlib-js/stdlib/commit/8620184ee6817de3a8014563248653c7f8d578e4) - **bench:** use string interpolation in `stats/base/ndarray/smskrange` [(#10344)](https://github.com/stdlib-js/stdlib/pull/10344) _(by ANKIT SINGH YADAV)_
-   [`7bf88ba`](https://github.com/stdlib-js/stdlib/commit/7bf88bae362e09e9fd53718b05af4bd11e6f79af) - **bench:** refactor to use string interpolation in `array/fixed-endian-float64` [(#10342)](https://github.com/stdlib-js/stdlib/pull/10342) _(by Bhargav Dabhade, Athan Reines)_
-   [`df7e670`](https://github.com/stdlib-js/stdlib/commit/df7e670a48f3403adefb402ce0a4e5e977e7af53) - **bench:** refactor to use string interpolation in `stats/base/dists/degenerate` [(#10326)](https://github.com/stdlib-js/stdlib/pull/10326) _(by Vishal Gaikwad, Athan Reines)_
-   [`e2b91ec`](https://github.com/stdlib-js/stdlib/commit/e2b91ec8f083aa6724029bd2f3d180d07230cf9e) - **bench:** refactor to use string interpolation in `array/bool` [(#10370)](https://github.com/stdlib-js/stdlib/pull/10370) _(by Shubham, Athan Reines)_
-   [`8f782c1`](https://github.com/stdlib-js/stdlib/commit/8f782c1e3d721d52693c5b5e1418f21c6e81d166) - **docs:** update namespace table of contents [(#10425)](https://github.com/stdlib-js/stdlib/pull/10425) _(by stdlib-bot)_
-   [`6c58908`](https://github.com/stdlib-js/stdlib/commit/6c58908473e2462a6155d2cc1af1ccd045bc7eb1) - **docs:** update related packages sections [(#10328)](https://github.com/stdlib-js/stdlib/pull/10328) _(by stdlib-bot)_
-   [`3172206`](https://github.com/stdlib-js/stdlib/commit/317220684f42b0b7c51373e65eb354e7d2be6fc7) - **bench:** fix description _(by Athan Reines)_
-   [`eff29c8`](https://github.com/stdlib-js/stdlib/commit/eff29c8492e90564c18a01db480cc4ab3455aff6) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`aecc65d`](https://github.com/stdlib-js/stdlib/commit/aecc65d494cda9ca4cb51a0a5badc002bd070604) - **style:** fix missing semicolon _(by Athan Reines)_
-   [`955bb7d`](https://github.com/stdlib-js/stdlib/commit/955bb7d29d23da091807ab2fb5c087c30d2faee2) - **style:** fix missing semicolon _(by Athan Reines)_
-   [`8f2c32e`](https://github.com/stdlib-js/stdlib/commit/8f2c32e8ba9b6f92d5eb397b3ef357ed5edc3d15) - **bench:** refactor to use dynamic memory allocation in `blas/ext/base/dsnansumors` [(#10113)](https://github.com/stdlib-js/stdlib/pull/10113) _(by AyushiJain18270)_
-   [`5cc3f4f`](https://github.com/stdlib-js/stdlib/commit/5cc3f4f8aad580d87fe6ae2ed41271e4791cca70) - **bench:** refactor to use string interpolation in `stats/base/dists/exponential` [(#10346)](https://github.com/stdlib-js/stdlib/pull/10346) _(by Vishal Gaikwad)_
-   [`a7bf4ae`](https://github.com/stdlib-js/stdlib/commit/a7bf4aec94324369038c58bc51206f9397e59e16) - **bench:** refactor to use string interpolation in `ndarray/zeros-like` [(#10366)](https://github.com/stdlib-js/stdlib/pull/10366) _(by Shubham)_
-   [`7bb3870`](https://github.com/stdlib-js/stdlib/commit/7bb3870f66f09ffa34133204b0e02bc9411c9e6d) - **bench:** refactor to use string interpolation in `blas/base/caxpy` [(#10367)](https://github.com/stdlib-js/stdlib/pull/10367) _(by Shubham)_
-   [`fc49fa5`](https://github.com/stdlib-js/stdlib/commit/fc49fa5c72ab4433c55f48750ea4cae10446c40c) - **bench:** refactor to use string interpolation in `blas/base/ccopy` [(#10368)](https://github.com/stdlib-js/stdlib/pull/10368) _(by Shubham)_
-   [`6979901`](https://github.com/stdlib-js/stdlib/commit/697990190ede7a6b807372e724546eb9470aa81b) - **bench:** refactor to use string interpolation in `math/base/special/sec` [(#10359)](https://github.com/stdlib-js/stdlib/pull/10359) _(by AyushiJain18270)_
-   [`6a0008d`](https://github.com/stdlib-js/stdlib/commit/6a0008d0315752288d76406de68fbcdc3b3015e5) - **bench:** refactor to use string interpolation in `ndarray/zeros` [(#10369)](https://github.com/stdlib-js/stdlib/pull/10369) _(by Shubham)_
-   [`b54e895`](https://github.com/stdlib-js/stdlib/commit/b54e8953f36e1feed4338c25f8e422ab6616ac30) - **bench:** refactor to use string interpolation in `blas/base/csscal` [(#10392)](https://github.com/stdlib-js/stdlib/pull/10392) _(by Shubham)_
-   [`2b6a46b`](https://github.com/stdlib-js/stdlib/commit/2b6a46b984472ebff561251d4918c164e2a57b59) - **bench:** refactor to use string interpolation in `blas/base/cswap` [(#10393)](https://github.com/stdlib-js/stdlib/pull/10393) _(by Shubham)_
-   [`ac99312`](https://github.com/stdlib-js/stdlib/commit/ac99312b4e8b2b6a31bb37a7077399ee35a2c186) - **bench:** refactor to use string interpolation in `blas/base/csrot` [(#10391)](https://github.com/stdlib-js/stdlib/pull/10391) _(by Shubham)_
-   [`9858a43`](https://github.com/stdlib-js/stdlib/commit/9858a43edd095b6b9abeb5bb69213b54ba9dc9ad) - **bench:** use string interpolation in `stats/strided/covarmtk` [(#10407)](https://github.com/stdlib-js/stdlib/pull/10407) _(by Om-A-osc)_
-   [`9108058`](https://github.com/stdlib-js/stdlib/commit/9108058ec47102a250344cb84df5e8de2a40435b) - **bench:** refactor to use string interpolation in `blas/base/dnrm2` [(#10408)](https://github.com/stdlib-js/stdlib/pull/10408) _(by Shubham)_
-   [`25a83a9`](https://github.com/stdlib-js/stdlib/commit/25a83a9791bb03905fa36e7905d5a8551417f578) - **bench:** refactor to use string interpolation in `blas/base/daxpy` [(#10409)](https://github.com/stdlib-js/stdlib/pull/10409) _(by Shubham)_
-   [`ff26214`](https://github.com/stdlib-js/stdlib/commit/ff262145f210fc52950aa2de33b8a746d0bdf805) - **bench:** refactor to use string interpolation in `blas/base/dasum` [(#10411)](https://github.com/stdlib-js/stdlib/pull/10411) _(by Shubham)_
-   [`23859a1`](https://github.com/stdlib-js/stdlib/commit/23859a1be95fbece6101dd9527c053d029a76f64) - **bench:** refactor to use string interpolation in `blas/base/dznrm2` [(#10410)](https://github.com/stdlib-js/stdlib/pull/10410) _(by Shubham)_
-   [`a77d03a`](https://github.com/stdlib-js/stdlib/commit/a77d03ae128ff08d5404758c075fba5ac594ca0b) - **bench:** use string interpolation in `stats/strided/dcovarmtk` [(#10412)](https://github.com/stdlib-js/stdlib/pull/10412) _(by Om-A-osc)_
-   [`33e892a`](https://github.com/stdlib-js/stdlib/commit/33e892a03f8c628919751d82db58de78f90aa663) - **bench:** refactor to use string interpolation in `lapack/base/claset` [(#10092)](https://github.com/stdlib-js/stdlib/pull/10092) _(by Prajjwal Bajpai, Athan Reines)_
-   [`5064174`](https://github.com/stdlib-js/stdlib/commit/5064174c60795a3122eff919ecdb06e5cbeefbed) - **bench:** refactor to use string interpolation in `lapack/base/clacpy` [(#10091)](https://github.com/stdlib-js/stdlib/pull/10091) _(by Prajjwal Bajpai, Athan Reines)_
-   [`a9a8876`](https://github.com/stdlib-js/stdlib/commit/a9a8876832e118b718fc4e7727774ab017a73ca2) - **bench:** refactor to use string interpolation in `lapack/base/dge-trans` [(#10095)](https://github.com/stdlib-js/stdlib/pull/10095) _(by Prajjwal Bajpai, Athan Reines)_
-   [`9d39628`](https://github.com/stdlib-js/stdlib/commit/9d39628f9f41d0e8115684bc155aaba353ede02e) - **bench:** refactor to use string interpolation in `lapack/base/dlacpy` [(#10097)](https://github.com/stdlib-js/stdlib/pull/10097) _(by Prajjwal Bajpai, Athan Reines)_
-   [`d5bc8be`](https://github.com/stdlib-js/stdlib/commit/d5bc8be211508459a7a6ac0c63a6f9fb3573b82e) - **bench:** refactor to use string interpolation in `lapack/base/claswp` [(#10093)](https://github.com/stdlib-js/stdlib/pull/10093) _(by Prajjwal Bajpai, Athan Reines)_
-   [`8198d19`](https://github.com/stdlib-js/stdlib/commit/8198d196d6af765c7c9c39e4a71fe55713ad3748) - **bench:** refactor to use string interpolation in `lapack/base/dlaset` [(#10099)](https://github.com/stdlib-js/stdlib/pull/10099) _(by Prajjwal Bajpai, Athan Reines)_
-   [`fc043ce`](https://github.com/stdlib-js/stdlib/commit/fc043ce359c6e100fe4d3b7747b2e37234e4bef7) - **bench:** refactor to use string interpolation in `lapack/base/iladlc` [(#10117)](https://github.com/stdlib-js/stdlib/pull/10117) _(by Prajjwal Bajpai, Athan Reines)_
-   [`cc6f4ba`](https://github.com/stdlib-js/stdlib/commit/cc6f4bab257a418105ee8f914e94130c7a3608ea) - **bench:** refactor to use string interpolation in `lapack/base/iladlr` [(#10120)](https://github.com/stdlib-js/stdlib/pull/10120) _(by Prajjwal Bajpai, Athan Reines)_
-   [`50d86a6`](https://github.com/stdlib-js/stdlib/commit/50d86a6882b7d6b0d8506de33c3467102e955e4a) - **bench:** refactor to use string interpolation in `lapack/base/sge-trans` [(#10123)](https://github.com/stdlib-js/stdlib/pull/10123) _(by Prajjwal Bajpai, Athan Reines)_
-   [`401114d`](https://github.com/stdlib-js/stdlib/commit/401114d47c349c8e1e5dd329b747fc0ec2614529) - **bench:** refactor to use string interpolation in `lapack/base/dlaswp` [(#10102)](https://github.com/stdlib-js/stdlib/pull/10102) _(by Prajjwal Bajpai, Athan Reines)_
-   [`f9491c3`](https://github.com/stdlib-js/stdlib/commit/f9491c3fa3b043ed4c0d9ea3141cedfdd4239ee6) - **bench:** refactor to use string interpolation in `lapack/base/dlarf1f` [(#10098)](https://github.com/stdlib-js/stdlib/pull/10098) _(by Prajjwal Bajpai, Athan Reines)_
-   [`fbc802f`](https://github.com/stdlib-js/stdlib/commit/fbc802f7b268582103397618d302eb25afcb0c7f) - **bench:** refactor to use string interpolation in `lapack/base/slacpy` [(#10124)](https://github.com/stdlib-js/stdlib/pull/10124) _(by Prajjwal Bajpai, Athan Reines)_
-   [`fb50958`](https://github.com/stdlib-js/stdlib/commit/fb50958365f133ae79a6caedaa2351be561cfd75) - **bench:** refactor to use string interpolation in `lapack/base/slaswp` [(#10125)](https://github.com/stdlib-js/stdlib/pull/10125) _(by Prajjwal Bajpai, Athan Reines)_
-   [`b2ac230`](https://github.com/stdlib-js/stdlib/commit/b2ac2304fe21c8c482b272646776c591be9282e2) - **bench:** refactor to use string interpolation in `lapack/base/zlacpy` [(#10128)](https://github.com/stdlib-js/stdlib/pull/10128) _(by Prajjwal Bajpai, Athan Reines)_
-   [`648fb21`](https://github.com/stdlib-js/stdlib/commit/648fb21364cce31bee7b94e6aaa2f136b7801f87) - **bench:** refactor to use string interpolation in `lapack/base/zlaset` [(#10129)](https://github.com/stdlib-js/stdlib/pull/10129) _(by Prajjwal Bajpai, Athan Reines)_
-   [`87878e7`](https://github.com/stdlib-js/stdlib/commit/87878e70356befd4c09e8ae67b5b73026c5648b5) - **bench:** refactor to use string interpolation in `lapack/base/zlaswp` [(#10130)](https://github.com/stdlib-js/stdlib/pull/10130) _(by Prajjwal Bajpai, Athan Reines)_
-   [`04ce2a4`](https://github.com/stdlib-js/stdlib/commit/04ce2a4f5679a2075bc2bd37e3c27b0f9cb422f7) - **bench:** refactor to use string interpolation in `lapack/base/dlassq` [(#10100)](https://github.com/stdlib-js/stdlib/pull/10100) _(by Prajjwal Bajpai)_
-   [`208c5bf`](https://github.com/stdlib-js/stdlib/commit/208c5bf44bb87460a2a310e593193970c0366455) - **bench:** refactor to use string interpolation in `lapack/base/dpttrf` [(#10103)](https://github.com/stdlib-js/stdlib/pull/10103) _(by Prajjwal Bajpai)_
-   [`cbd1066`](https://github.com/stdlib-js/stdlib/commit/cbd1066cbd4df6dcb9e699d2fdd94d3447db9e8a) - **bench:** refactor to use string interpolation in `lapack/base/spttrf` [(#10126)](https://github.com/stdlib-js/stdlib/pull/10126) _(by Prajjwal Bajpai)_
-   [`db7bb4c`](https://github.com/stdlib-js/stdlib/commit/db7bb4c8b129e4d082aaa8531cca082603107fe3) - **bench:** refactor to use string interpolation in `lapack/base/zlacgv` [(#10127)](https://github.com/stdlib-js/stdlib/pull/10127) _(by Prajjwal Bajpai)_
-   [`f9c61b1`](https://github.com/stdlib-js/stdlib/commit/f9c61b1b1f411ee4b15cf97b5cae853500bc6483) - **bench:** refactor to use string interpolation in `stats/base/dists/gumbel/ctor` [(#10397)](https://github.com/stdlib-js/stdlib/pull/10397) _(by Lokesh Ranjan)_
-   [`becb440`](https://github.com/stdlib-js/stdlib/commit/becb440aaa166ce435909ba82f743009ad1e7b6d) - **remove:** remove `stats/strided/distances/dchebychev` _(by nakul-krishnakumar)_
-   [`cc812eb`](https://github.com/stdlib-js/stdlib/commit/cc812eb5ac0285a79e7e0ac15ad09a194bd7364b) - **remove:** remove `dchebychev` from namespace _(by nakul-krishnakumar)_
-   [`8a0bdab`](https://github.com/stdlib-js/stdlib/commit/8a0bdab18b22e650ce6ec73b87f347846774890f) - **feat:** add `stats/strided/distances/dchebyshev _(by nakul-krishnakumar)_
-   [`ff420ae`](https://github.com/stdlib-js/stdlib/commit/ff420aed1e79bd9e89c7394571e2692c4108583c) - **bench:** fix description _(by Athan Reines)_
-   [`c14812b`](https://github.com/stdlib-js/stdlib/commit/c14812bfee0ec6951166b9ff869289a39eba4174) - **style:** add missing decimal _(by Athan Reines)_
-   [`8452bac`](https://github.com/stdlib-js/stdlib/commit/8452bacd27b9cb267bc12c5d87d0e80fb4955f4d) - **bench:** refactor to use string interpolation in `array/zeros-like` [(#10349)](https://github.com/stdlib-js/stdlib/pull/10349) _(by Shubham)_
-   [`bad91bf`](https://github.com/stdlib-js/stdlib/commit/bad91bf9fad4693af649750fd4ebe30640358e48) - **bench:** refactor to use string interpolation in `array/zero-to-like` [(#10350)](https://github.com/stdlib-js/stdlib/pull/10350) _(by Shubham)_
-   [`d8c8201`](https://github.com/stdlib-js/stdlib/commit/d8c8201ac4ca8c5e2150a5a970a98a551672ac48) - **bench:** refactor to use string interpolation in `array/zero-to` [(#10351)](https://github.com/stdlib-js/stdlib/pull/10351) _(by Shubham)_
-   [`0e5ccc5`](https://github.com/stdlib-js/stdlib/commit/0e5ccc5a2d4faa9df26004b4931020c4c38eff5e) - **bench:** use string interpolation in `blas/ext/base/ndarray/gsumkbn` [(#10353)](https://github.com/stdlib-js/stdlib/pull/10353) _(by AyushiJain18270)_
-   [`e53e179`](https://github.com/stdlib-js/stdlib/commit/e53e179ec5f9b063604744804b989bd6ebe2381a) - **feat:** add `stats/base/ndarray/dnanstdev` [(#10271)](https://github.com/stdlib-js/stdlib/pull/10271) _(by Pratik)_
-   [`d7c9e82`](https://github.com/stdlib-js/stdlib/commit/d7c9e8257ce6c5eead817a24a26556c3efb62cf8) - **test:** remove empty line between require statements in `test.dsyr2.js` [(#10288)](https://github.com/stdlib-js/stdlib/pull/10288) _(by Lakshmi Sravya Vedantham, lakshmisravya123)_
-   [`c51df70`](https://github.com/stdlib-js/stdlib/commit/c51df700dde62d157e7fd9bbcfa9148d82ccef7f) - **feat:** add implementation of `math/base/special/floor2f` [(#10323)](https://github.com/stdlib-js/stdlib/pull/10323) _(by Shubham, Philipp Burckhardt)_
-   [`8b01d81`](https://github.com/stdlib-js/stdlib/commit/8b01d81e8346ac3e4795b7d79a51902e201b2b98) - **chore:** fix JavaScript lint errors [(#10331)](https://github.com/stdlib-js/stdlib/pull/10331) _(by Bhargav Dabhade)_
-   [`f834c92`](https://github.com/stdlib-js/stdlib/commit/f834c92ade215691ff1d2d5cf36894e8ed697ffe) - **bench:** refactor to use string interpolation in `blas/ext/base/ndarray/dcusumpw` [(#10329)](https://github.com/stdlib-js/stdlib/pull/10329) _(by AyushiJain18270)_
-   [`88c63b2`](https://github.com/stdlib-js/stdlib/commit/88c63b2692cdefa8caa7b42906478865bedd0521) - **bench:** update random value generation for `stats/base/dists/exponential` [(#10330)](https://github.com/stdlib-js/stdlib/pull/10330) _(by Siddhartha Mondal, Philipp Burckhardt)_
-   [`9a18a03`](https://github.com/stdlib-js/stdlib/commit/9a18a03e86bfed34475b176b2732303aab09c86c) - **bench:** refactor to use dynamic memory allocation in `blas/base/sspr` [(#10332)](https://github.com/stdlib-js/stdlib/pull/10332) _(by Prajjwal Bajpai)_
-   [`338737a`](https://github.com/stdlib-js/stdlib/commit/338737a1f9c6f3b88a9bc5338f35dc90dc82b43a) - **bench:** refactor to use string interpolation in `blas/base/sspr` [(#10333)](https://github.com/stdlib-js/stdlib/pull/10333) _(by Prajjwal Bajpai, Philipp Burckhardt)_
-   [`18db4f6`](https://github.com/stdlib-js/stdlib/commit/18db4f6ca8230913325b71f53a49ad0aac41b10b) - **bench:** update random value generation for `stats/base/dists/frechet` [(#10335)](https://github.com/stdlib-js/stdlib/pull/10335) _(by Lokesh Ranjan)_
-   [`1c5a33e`](https://github.com/stdlib-js/stdlib/commit/1c5a33ead802b48aa8b7eab6d816923df6ce8aa9) - **bench:** refactor to use string interpolation in `array/base/fillednd-by` [(#10334)](https://github.com/stdlib-js/stdlib/pull/10334) _(by Rohit R Bhat)_
-   [`b241151`](https://github.com/stdlib-js/stdlib/commit/b241151321d4ccfe331d708cd47c384bd1359032) - **bench:** refactor to use string interpolation in `array/index` [(#10336)](https://github.com/stdlib-js/stdlib/pull/10336) _(by Shubham)_
-   [`ddc5bee`](https://github.com/stdlib-js/stdlib/commit/ddc5beeef572cad7d02537bb0086ba434ef77a23) - **bench:** refactor to use string interpolation in `array/uint8` [(#10337)](https://github.com/stdlib-js/stdlib/pull/10337) _(by Shubham)_
-   [`45bbad6`](https://github.com/stdlib-js/stdlib/commit/45bbad6ba1be96aa1bfdcf7229b6747fa207b043) - **bench:** refactor to use string interpolation in `array/uint8c` [(#10338)](https://github.com/stdlib-js/stdlib/pull/10338) _(by Shubham)_
-   [`56a8cb7`](https://github.com/stdlib-js/stdlib/commit/56a8cb7fe77a856743eadfec5e2715a06dc86453) - **bench:** refactor to use string interpolation in `array/uint16` [(#10339)](https://github.com/stdlib-js/stdlib/pull/10339) _(by Shubham)_
-   [`9d0b88a`](https://github.com/stdlib-js/stdlib/commit/9d0b88a0ac8a16ec7eb28b7e300cf239cc580096) - **bench:** refactor to use string interpolation in `array/uint32` [(#10340)](https://github.com/stdlib-js/stdlib/pull/10340) _(by Shubham)_
-   [`f5199d6`](https://github.com/stdlib-js/stdlib/commit/f5199d619314724b7b0627f41aba3114b559cec8) - **bench:** update random value generation for `stats/base/dists/frechet` [(#10317)](https://github.com/stdlib-js/stdlib/pull/10317) _(by Lokesh Ranjan, Philipp Burckhardt)_
-   [`1ac0545`](https://github.com/stdlib-js/stdlib/commit/1ac0545653898f2f1c6943f52d42afb9d46195c6) - **chore:** update tests and use string interpolation in `math/base/special/sqrt1pm1` [(#10324)](https://github.com/stdlib-js/stdlib/pull/10324) _(by Shubham)_
-   [`5c41472`](https://github.com/stdlib-js/stdlib/commit/5c41472c12ae782ea7dc703108ccbd92405c5397) - **bench:** refactor to use string interpolation in `blas/base/srotm` [(#10314)](https://github.com/stdlib-js/stdlib/pull/10314) _(by Prajjwal Bajpai)_
-   [`2e3e0e9`](https://github.com/stdlib-js/stdlib/commit/2e3e0e9f450c5fbcf1cab51d1d87a558afcaa93a) - **bench:** update random value generation for `stats/base/dists/f` [(#10316)](https://github.com/stdlib-js/stdlib/pull/10316) _(by Lokesh Ranjan)_
-   [`1ebdf55`](https://github.com/stdlib-js/stdlib/commit/1ebdf55506f7035fd461b57300609ae6cb432934) - **bench:** refactor to use string interpolation in `array/filled-by` [(#10319)](https://github.com/stdlib-js/stdlib/pull/10319) _(by Shubham)_
-   [`b260ecf`](https://github.com/stdlib-js/stdlib/commit/b260ecf81debab4fb8571d9f41d28944fac33bbf) - **bench:** refactor to use string interpolation in `array/full-like` [(#10320)](https://github.com/stdlib-js/stdlib/pull/10320) _(by Shubham)_
-   [`e487975`](https://github.com/stdlib-js/stdlib/commit/e487975ccd8c36a0c13d3765bac19de5995104d5) - **bench:** refactor to use string interpolation in `array/filled` [(#10321)](https://github.com/stdlib-js/stdlib/pull/10321) _(by Shubham)_
-   [`5a64342`](https://github.com/stdlib-js/stdlib/commit/5a643426403fa397b0bd695ff1deeddd002cc641) - **feat:** add C implementation for `stats/base/ndarray/snanrange` [(#10258)](https://github.com/stdlib-js/stdlib/pull/10258) _(by Bhargav Dabhade, Sachin Pangal)_
-   [`0feb882`](https://github.com/stdlib-js/stdlib/commit/0feb882c947d76d28bc6a7cd6b32d1c3431611d2) - **bench:** use single-colon for method and property access benchmarks _(by Philipp Burckhardt)_
-   [`8d7f767`](https://github.com/stdlib-js/stdlib/commit/8d7f767735bb60e4ef54292f14da380f077fa953) - **test:** remove non-equal branch when testing against fixtures _(by Philipp Burckhardt)_
-   [`a0c2995`](https://github.com/stdlib-js/stdlib/commit/a0c2995765caeb58bd72a0f9031f9d247c9a2cb0) - **test:** use Distributions for fixtures generation for independent verification _(by Philipp Burckhardt)_
-   [`f884c94`](https://github.com/stdlib-js/stdlib/commit/f884c94958214a509cf48747280543d3b5ec396f) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`33e3d9f`](https://github.com/stdlib-js/stdlib/commit/33e3d9f96ce3fc32b31dd3f46a017c92b73b0425) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`2e38ad1`](https://github.com/stdlib-js/stdlib/commit/2e38ad1d6a8f51a4dbe8ed07072961774e8bbdfa) - **test:** fix variable acess and regenerate fixtures _(by Philipp Burckhardt)_
-   [`6ecc272`](https://github.com/stdlib-js/stdlib/commit/6ecc272a3117e71d4a9b0ec55864e5fed4e2386c) - **chore:** fix example code and add missing semicolon _(by Philipp Burckhardt)_
-   [`2ed3934`](https://github.com/stdlib-js/stdlib/commit/2ed3934650fc6e9dd7065f21c4de66e3457cc5cb) - **test:** fix argument order and regenerate fixtures _(by Philipp Burckhardt)_
-   [`f38e8a7`](https://github.com/stdlib-js/stdlib/commit/f38e8a7b433e0e9888eb57c83f4374073089ad85) - **docs:** clean-up parameters in Julia fixtures scripts _(by Philipp Burckhardt)_
-   [`a429a6a`](https://github.com/stdlib-js/stdlib/commit/a429a6abc8c3588478436c91a3ced18c31198948) - **bench:** refactor to use dynamic memory allocation in `blas/base/scopy` [(#10155)](https://github.com/stdlib-js/stdlib/pull/10155) _(by Prajjwal Bajpai)_
-   [`d86efd1`](https://github.com/stdlib-js/stdlib/commit/d86efd10c0a4bc76a291c78ee8ebde52aa4f4926) - **bench:** refactor to use string interpolation in `blas/base/scopy` [(#10156)](https://github.com/stdlib-js/stdlib/pull/10156) _(by Prajjwal Bajpai)_
-   [`c62573e`](https://github.com/stdlib-js/stdlib/commit/c62573efea9252a74eeb9056ca91c55485199286) - **bench:** refactor to use dynamic memory allocation in `blas/base/sdot` [(#10173)](https://github.com/stdlib-js/stdlib/pull/10173) _(by Prajjwal Bajpai)_
-   [`70190d9`](https://github.com/stdlib-js/stdlib/commit/70190d95cd081cf661a70f834828a0b93bef5288) - **bench:** refactor to use string interpolation in `blas/ext/base/ndarray/dcusumkbn` [(#10296)](https://github.com/stdlib-js/stdlib/pull/10296) _(by AyushiJain18270)_
-   [`a20ca4a`](https://github.com/stdlib-js/stdlib/commit/a20ca4a869cb0f37fce36449969104314f3e78c8) - **docs:** update REPL namespace documentation [(#10309)](https://github.com/stdlib-js/stdlib/pull/10309) _(by stdlib-bot, Philipp Burckhardt)_
-   [`17fd10b`](https://github.com/stdlib-js/stdlib/commit/17fd10bc90d3cb7469ad3c2e4713363b7097eb42) - **docs:** update `blas/ext/base/ndarray` TypeScript declarations [(#10310)](https://github.com/stdlib-js/stdlib/pull/10310) _(by stdlib-bot)_
-   [`a253e63`](https://github.com/stdlib-js/stdlib/commit/a253e6394fc69bc1251c0544ca051b605c8adad3) - **docs:** update `math/base/special` TypeScript declarations [(#10311)](https://github.com/stdlib-js/stdlib/pull/10311) _(by stdlib-bot)_
-   [`1e31792`](https://github.com/stdlib-js/stdlib/commit/1e31792b8dc259eab7ccf802a688556ce376bfb5) - **bench:** refactor to use string interpolation in `array/int16` [(#10274)](https://github.com/stdlib-js/stdlib/pull/10274) _(by Shubham, Philipp Burckhardt)_
-   [`7d88343`](https://github.com/stdlib-js/stdlib/commit/7d88343dc553ac2b116119cb618d3eee0f11a513) - **bench:** refactor to use dynamic memory allocation in `blas/base/srot` [(#10287)](https://github.com/stdlib-js/stdlib/pull/10287) _(by Prajjwal Bajpai)_
-   [`9fc0b94`](https://github.com/stdlib-js/stdlib/commit/9fc0b943505f6b3fb58781fe53b726e65c061e2e) - **bench:** refactor to use string interpolation in `blas/base/srot` [(#10289)](https://github.com/stdlib-js/stdlib/pull/10289) _(by Prajjwal Bajpai)_
-   [`570ea52`](https://github.com/stdlib-js/stdlib/commit/570ea52237318497987a193d4b8069a6dceff78f) - **bench:** use string interpolation in `blas/base/dgemv` [(#10290)](https://github.com/stdlib-js/stdlib/pull/10290) _(by Om-A-osc)_
-   [`d3f62b1`](https://github.com/stdlib-js/stdlib/commit/d3f62b1dc6a274e004e047928832ce378798768a) - **bench:** use string interpolation in `blas/base/dger` [(#10292)](https://github.com/stdlib-js/stdlib/pull/10292) _(by Om-A-osc)_
-   [`8a000b4`](https://github.com/stdlib-js/stdlib/commit/8a000b4c884be979078c342d56f96b52a8bc5b0c) - **bench:** use string interpolation in `blas/base/dgemm` [(#10294)](https://github.com/stdlib-js/stdlib/pull/10294) _(by Om-A-osc)_
-   [`1cccd61`](https://github.com/stdlib-js/stdlib/commit/1cccd611ff6c4edd77ecf39f8f684b583499d379) - **bench:** use string interpolation in `blas/base/drot` [(#10295)](https://github.com/stdlib-js/stdlib/pull/10295) _(by Om-A-osc)_
-   [`e1fa36c`](https://github.com/stdlib-js/stdlib/commit/e1fa36c2e0773845bab939eb700d3ee665a5cec9) - **bench:** refactor to use string interpolation in `array/complex128` [(#10301)](https://github.com/stdlib-js/stdlib/pull/10301) _(by Shubham)_
-   [`9efe7df`](https://github.com/stdlib-js/stdlib/commit/9efe7df13c315e32a9e938830a15f874fb1cb4a0) - **bench:** refactor to use string interpolation in `array/complex64` [(#10302)](https://github.com/stdlib-js/stdlib/pull/10302) _(by Shubham)_
-   [`dd728e2`](https://github.com/stdlib-js/stdlib/commit/dd728e2944ff7318d68b89e9e8c33d9e84d94e7e) - **bench:** refactor to use string interpolation in `blas/base/cscal` [(#10308)](https://github.com/stdlib-js/stdlib/pull/10308) _(by Bhargav Dabhade)_
-   [`10b28fd`](https://github.com/stdlib-js/stdlib/commit/10b28fdb54393277d093066bf40c84412ca7601d) - **feat:** add `stats/array/nanmidrange-by` [(#10273)](https://github.com/stdlib-js/stdlib/pull/10273) _(by Om-A-osc, Philipp Burckhardt, Sachin Pangal)_
-   [`5360fda`](https://github.com/stdlib-js/stdlib/commit/5360fda9c2b6ace5ef3ebb3acdf96920d1ab6089) - **docs:** use correct PDF reference link in `stats/base/dists/signrank/pdf` [(#10303)](https://github.com/stdlib-js/stdlib/pull/10303) _(by Shubham)_
-   [`80b62e9`](https://github.com/stdlib-js/stdlib/commit/80b62e996caedc9d65e3c4d319b2abd01d0429e7) - **bench:** refactor to use string interpolation in `blas/base/sdot` [(#10175)](https://github.com/stdlib-js/stdlib/pull/10175) _(by Prajjwal Bajpai)_
-   [`e83179b`](https://github.com/stdlib-js/stdlib/commit/e83179b9b342021ac4b62eb9985e82137462ff0e) - **docs:** improve doctests for complex number instances in `math/base/special/cceilf` [(#10183)](https://github.com/stdlib-js/stdlib/pull/10183) _(by Vishal Gaikwad)_
-   [`51c43ad`](https://github.com/stdlib-js/stdlib/commit/51c43ad346f4f7a14e7f131b0ea5ebf477959bae) - **bench:** refactor to use string interpolation in `blas/base/sdsdot` [(#10190)](https://github.com/stdlib-js/stdlib/pull/10190) _(by Prajjwal Bajpai)_
-   [`8bfb552`](https://github.com/stdlib-js/stdlib/commit/8bfb5524d89a26ed6d0524d72d11e5a893338c5d) - **feat:** add C implementation for `stats/base/ndarray/snanmax` [(#10198)](https://github.com/stdlib-js/stdlib/pull/10198) _(by Samarth Kolarkar, orthodox-64)_
-   [`5ae946b`](https://github.com/stdlib-js/stdlib/commit/5ae946bda58f813e9ed23610719f395416985c88) - **bench:** update array initialisation and refactor to use string interpolation in `stats/anova1` [(#10199)](https://github.com/stdlib-js/stdlib/pull/10199) _(by Shubham)_
-   [`53aaf81`](https://github.com/stdlib-js/stdlib/commit/53aaf8135f7feba8476da758d895cc24da20caad) - **feat:** add C implementation for `math/base/special/heaviside` [(#10196)](https://github.com/stdlib-js/stdlib/pull/10196) _(by Kamal Singh Rautela)_
-   [`a98984e`](https://github.com/stdlib-js/stdlib/commit/a98984e09c439362ebab1a1fa8ba45aca64c2fc6) - **chore:** fix lint errors [(#10212)](https://github.com/stdlib-js/stdlib/pull/10212) _(by Om-A-osc)_
-   [`9df57d4`](https://github.com/stdlib-js/stdlib/commit/9df57d4d7a7383c849ad00e3cc4335888b6f2197) - **docs:** improve doctests for ndarray instances in `ndarray/gcusum` [(#10250)](https://github.com/stdlib-js/stdlib/pull/10250) _(by AyushiJain18270)_
-   [`4126555`](https://github.com/stdlib-js/stdlib/commit/412655574507fcca6df462c015ab741d7353fec0) - **bench:** update random value generation for `stats/base/dists/gumbel/skewness` [(#10261)](https://github.com/stdlib-js/stdlib/pull/10261) _(by Bhargav Dabhade)_
-   [`bb63f81`](https://github.com/stdlib-js/stdlib/commit/bb63f8127455cd4fc055aec5aa600f4e5b1eafb5) - **bench:** refactor to use string interpolation in `array/zeros` [(#10272)](https://github.com/stdlib-js/stdlib/pull/10272) _(by Aman Singh)_
-   [`bf1ee75`](https://github.com/stdlib-js/stdlib/commit/bf1ee75f724235ffc70d27d16a58d18c7e4e0d56) - **bench:** refactor to use string interpolation in `stats/base/dists/logistic` [(#10105)](https://github.com/stdlib-js/stdlib/pull/10105) _(by Shubham)_
-   [`b816c5e`](https://github.com/stdlib-js/stdlib/commit/b816c5eed90e36341b7688cecf3c5ee688e0a001) - **bench:** refactor to use string interpolation in `array/int32` [(#10275)](https://github.com/stdlib-js/stdlib/pull/10275) _(by Shubham)_
-   [`f04bd84`](https://github.com/stdlib-js/stdlib/commit/f04bd8446b04ed6a0e45822b20dbccf45bcb2ef7) - **feat:** add `stats/array/mskmaxabs` [(#10280)](https://github.com/stdlib-js/stdlib/pull/10280) _(by Sachin Pangal)_
-   [`c7b5ae5`](https://github.com/stdlib-js/stdlib/commit/c7b5ae52a7ed0b5be7025ee3b93f8ae3f5d5aada) - **feat:** add `stats/array/mskminabs` [(#10281)](https://github.com/stdlib-js/stdlib/pull/10281) _(by Sachin Pangal)_
-   [`0f2ea57`](https://github.com/stdlib-js/stdlib/commit/0f2ea572ed30d6c259cb103182a1237ec430b983) - **feat:** add Wald distribution variance package [(#9730)](https://github.com/stdlib-js/stdlib/pull/9730) _(by Manit Roy)_
-   [`7b1ec1e`](https://github.com/stdlib-js/stdlib/commit/7b1ec1ee410f8c2a2e49d70bcf878e57ddb966d9) - **bench:** refactor to use string interpolation in `stats/base/dists/frechet` [(#10122)](https://github.com/stdlib-js/stdlib/pull/10122) _(by Shubham)_
-   [`7ef3bae`](https://github.com/stdlib-js/stdlib/commit/7ef3bae65f5d876db0c56d57ab84ea52e7699b7d) - **feat:** add `stats/array/nanmskmidrange` [(#10224)](https://github.com/stdlib-js/stdlib/pull/10224) _(by Sachin Pangal, stdlib-bot)_
-   [`ea860cb`](https://github.com/stdlib-js/stdlib/commit/ea860cb837689aeec224d0f0e4f71054bc5b309d) - **bench:** refactor to use string interpolation in `blas/base/dcopy` [(#10260)](https://github.com/stdlib-js/stdlib/pull/10260) _(by Bhargav Dabhade)_
-   [`ac4c4d6`](https://github.com/stdlib-js/stdlib/commit/ac4c4d68fb8dafc6566eadf8961eb3ad03b482f7) - **docs:** update `blas/ext` TypeScript declarations [(#10286)](https://github.com/stdlib-js/stdlib/pull/10286) _(by stdlib-bot)_
-   [`1c77c62`](https://github.com/stdlib-js/stdlib/commit/1c77c6221a42796e036a3f370732dfec9d579264) - **bench:** refactor to use string interpolation in `lapack/base/clacgv` [(#10088)](https://github.com/stdlib-js/stdlib/pull/10088) _(by Prajjwal Bajpai)_
-   [`143c2b8`](https://github.com/stdlib-js/stdlib/commit/143c2b82010dee7aeff548e4cfdd946fe410b8ee) - **bench:** refactor to use string interpolation in `lapack/base/crot` [(#10094)](https://github.com/stdlib-js/stdlib/pull/10094) _(by Prajjwal Bajpai)_
-   [`4a7457b`](https://github.com/stdlib-js/stdlib/commit/4a7457b1f6ab68883f0501b5c0186a3ddcdea707) - **bench:** refactor to use string interpolation in `lapack/base/dgttrf` [(#10096)](https://github.com/stdlib-js/stdlib/pull/10096) _(by Prajjwal Bajpai)_
-   [`aec0634`](https://github.com/stdlib-js/stdlib/commit/aec0634d886bdade0dd7dd221bbe1bd655669594) - **feat:** add `stats/array/rangeabs` [(#10227)](https://github.com/stdlib-js/stdlib/pull/10227) _(by Sachin Pangal)_
-   [`71f75c9`](https://github.com/stdlib-js/stdlib/commit/71f75c9b9b996b6b0e6a1e4a75229a726c3a1ea3) - **chore:** fix JavaScript lint errors [(#10247)](https://github.com/stdlib-js/stdlib/pull/10247) _(by Bhargav Dabhade)_
-   [`337e9e8`](https://github.com/stdlib-js/stdlib/commit/337e9e8ceed38e6409a2ec0b2268e79a15dc6ff1) - **bench:** refactor to use string interpolation in `stats/base/dists/cosine` [(#10169)](https://github.com/stdlib-js/stdlib/pull/10169) _(by Bhargav Dabhade)_
-   [`e7e6955`](https://github.com/stdlib-js/stdlib/commit/e7e695564ed321e40640ba406cf85d8c2f854fc3) - **bench:** use string interpolation in `stats/base/ndarray/nanmeanpn` [(#10170)](https://github.com/stdlib-js/stdlib/pull/10170) _(by Om-A-osc)_
-   [`3088f39`](https://github.com/stdlib-js/stdlib/commit/3088f3987094c907d9b81fbdeeea5ac58a915ac3) - **feat:** add implementation of `stats/base/dists/wald/kurtosis` [(#10216)](https://github.com/stdlib-js/stdlib/pull/10216) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`96f2808`](https://github.com/stdlib-js/stdlib/commit/96f28086b0a4bf03556f5ba91078d68c1823a27d) - **feat:** add implementation of `stats/base/dists/wald/skewness` [(#10206)](https://github.com/stdlib-js/stdlib/pull/10206) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`5dfd41d`](https://github.com/stdlib-js/stdlib/commit/5dfd41df5e698950034ed3e54d9f32dc9ff03355) - **feat:** add C implementation for `stats/base/ndarray/srangeabs` [(#10240)](https://github.com/stdlib-js/stdlib/pull/10240) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`564b95d`](https://github.com/stdlib-js/stdlib/commit/564b95d10f2ba27c7ecc0db98712df489458c657) - **bench:** refactor to use string interpolation in `stats/base/dists/cauchy` [(#10249)](https://github.com/stdlib-js/stdlib/pull/10249) _(by Vishal Gaikwad, Philipp Burckhardt)_
-   [`2a8cda9`](https://github.com/stdlib-js/stdlib/commit/2a8cda98b404d0507e04c4c62d572726a08b015a) - **feat:** add `stats/array/midrange-by` [(#10263)](https://github.com/stdlib-js/stdlib/pull/10263) _(by Sachin Pangal, Philipp Burckhardt)_
-   [`6e63e9c`](https://github.com/stdlib-js/stdlib/commit/6e63e9ce06c0b20294f1b019b955ee0f3f881568) - **bench:** refactor to use string interpolation in `array/int8` [(#10192)](https://github.com/stdlib-js/stdlib/pull/10192) _(by Shubham)_
-   [`a76fdd9`](https://github.com/stdlib-js/stdlib/commit/a76fdd9159a85d9e63982dce2c3a87861d1bf662) - **bench:** update random value generation for `stats/base/dists/f` [(#10238)](https://github.com/stdlib-js/stdlib/pull/10238) _(by Lokesh Ranjan, Philipp Burckhardt)_
-   [`091611e`](https://github.com/stdlib-js/stdlib/commit/091611e823cdf35c232dec0ba9ef441f5542acd2) - **bench:** use string interpolation in `blas/base/zdscal` [(#10253)](https://github.com/stdlib-js/stdlib/pull/10253) _(by Om-A-osc)_
-   [`941a193`](https://github.com/stdlib-js/stdlib/commit/941a1939d08e0aff5c4fe5b3106cba6410566cd6) - **bench:** use string interpolation in `blas/base/zdrot` [(#10254)](https://github.com/stdlib-js/stdlib/pull/10254) _(by Om-A-osc)_
-   [`f490e6f`](https://github.com/stdlib-js/stdlib/commit/f490e6fc9a92d5e8e9d125d842b9c572b04eb4b3) - **bench:** use string interpolation in `blas/base/zscal` [(#10255)](https://github.com/stdlib-js/stdlib/pull/10255) _(by Om-A-osc)_
-   [`f33b43c`](https://github.com/stdlib-js/stdlib/commit/f33b43c48b34eaa32ac9a1b3d1ae92509cd06251) - **bench:** use string interpolation in `blas/base/zswap` [(#10256)](https://github.com/stdlib-js/stdlib/pull/10256) _(by Om-A-osc)_
-   [`a92ae46`](https://github.com/stdlib-js/stdlib/commit/a92ae4642159e98a945676a90269ffc75a211b87) - **bench:** refactor to use string interpolation in `blas/base/ddot` [(#10259)](https://github.com/stdlib-js/stdlib/pull/10259) _(by Bhargav Dabhade)_
-   [`ab43b7f`](https://github.com/stdlib-js/stdlib/commit/ab43b7fff2a33d8e101f50d65d18bfa914dbfcf0) - **feat:** add `stats/array/mskmidrange` [(#10221)](https://github.com/stdlib-js/stdlib/pull/10221) _(by Sachin Pangal, Philipp Burckhardt)_
-   [`46881ca`](https://github.com/stdlib-js/stdlib/commit/46881ca28f2b7e02fafe36c3f436636015edac59) - **bench:** refactor to use string interpolation in`random/base/geometric` [(#10229)](https://github.com/stdlib-js/stdlib/pull/10229) _(by Shubham)_
-   [`3a78025`](https://github.com/stdlib-js/stdlib/commit/3a7802537873ad795db7f3ecf9a78699f5488f16) - **bench:** refactor to use string interpolation in `random/base/frechet` [(#10231)](https://github.com/stdlib-js/stdlib/pull/10231) _(by Shubham)_
-   [`8278221`](https://github.com/stdlib-js/stdlib/commit/827822124d84eb3bb20c27345217745db93cd214) - **bench:** refactor to use string interpolation in `random/base/exponential` [(#10230)](https://github.com/stdlib-js/stdlib/pull/10230) _(by Shubham)_
-   [`749de6f`](https://github.com/stdlib-js/stdlib/commit/749de6f8c437bf7daad8413ff86175781c934df2) - **bench:** refactor to use string interpolation in `stats/base/dists/bradford` [(#10234)](https://github.com/stdlib-js/stdlib/pull/10234) _(by Vishal Gaikwad)_
-   [`46aeb95`](https://github.com/stdlib-js/stdlib/commit/46aeb956e694d0e7fe1fd1a95a706d230c7bc4a9) - **bench:** update random value generation for `stats/base/dists/gumbel/stdev` [(#10241)](https://github.com/stdlib-js/stdlib/pull/10241) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`1d869c7`](https://github.com/stdlib-js/stdlib/commit/1d869c731b86a36a2463698a060cdfb6d2b401f2) - **bench:** update random value generation for stats/base/dists/gumbel/variance [(#10242)](https://github.com/stdlib-js/stdlib/pull/10242) _(by Bhargav Dabhade, Philipp Burckhardt)_
-   [`1c014d0`](https://github.com/stdlib-js/stdlib/commit/1c014d0bd6d77de7c034db4fe86060fab87a4a53) - **bench:** refactor to use string interpolation in `stats/base/snanvarianceyc` [(#10243)](https://github.com/stdlib-js/stdlib/pull/10243) _(by Bhargav Dabhade)_
-   [`6a53aa7`](https://github.com/stdlib-js/stdlib/commit/6a53aa7c12756f57916ccbaeab9f09913aa9b8ee) - **bench:** refactor to use string interpolation in `stats/base/snanvariancewd` [(#10244)](https://github.com/stdlib-js/stdlib/pull/10244) _(by Bhargav Dabhade)_
-   [`3f082c4`](https://github.com/stdlib-js/stdlib/commit/3f082c405532bdd617a97fb6b4f4ea3dac67a633) - **bench:** refactor to use string interpolation in `stats/base/snanvariancetk` [(#10245)](https://github.com/stdlib-js/stdlib/pull/10245) _(by Bhargav Dabhade)_
-   [`1bb7d5b`](https://github.com/stdlib-js/stdlib/commit/1bb7d5bec1f232fd5541f56734612f40bb63cf89) - **bench:** refactor to use string interpolation in `stats/base/cumaxabs` [(#10161)](https://github.com/stdlib-js/stdlib/pull/10161) _(by Vishal Gaikwad)_
-   [`582219e`](https://github.com/stdlib-js/stdlib/commit/582219ec5e332c28c5bd1e5f3cdbb9f7904d6b1c) - **bench:** use string interpolation in `stats/base/ndarray/nanmean` [(#10164)](https://github.com/stdlib-js/stdlib/pull/10164) _(by Om-A-osc)_
-   [`7476e20`](https://github.com/stdlib-js/stdlib/commit/7476e2084236526a362d28d3c6f335cc4331fd8c) - **bench:** use string interpolation in `stats/base/ndarray/nanmaxabs` [(#10165)](https://github.com/stdlib-js/stdlib/pull/10165) _(by Om-A-osc)_
-   [`2eea8bb`](https://github.com/stdlib-js/stdlib/commit/2eea8bb24c99fb81c56ec7c14d0cca8d88b1cb52) - **feat:** add implementation of `math/base/special/coshf` [(#10177)](https://github.com/stdlib-js/stdlib/pull/10177) _(by Shubham)_
-   [`c70d9ed`](https://github.com/stdlib-js/stdlib/commit/c70d9eda1f4465e886f967cf09fdc54f0b11900d) - **feat:** add `stats/array/midrange` [(#10189)](https://github.com/stdlib-js/stdlib/pull/10189) _(by Sachin Pangal)_
-   [`90c521f`](https://github.com/stdlib-js/stdlib/commit/90c521fba4bb69acd67ea5b4d1ff8748559b15b2) - **docs:** remove extra empty line [(#10225)](https://github.com/stdlib-js/stdlib/pull/10225) _(by stdlib-bot)_
-   [`61e0c07`](https://github.com/stdlib-js/stdlib/commit/61e0c078903198eb07fe30301f14c3180186f5c9) - **bench:** use string interpolation in `stats/base/ndarray/nanmeanors` [(#10163)](https://github.com/stdlib-js/stdlib/pull/10163) _(by Om-A-osc)_
-   [`6bd2cc0`](https://github.com/stdlib-js/stdlib/commit/6bd2cc0e88930b003aacdae33981e3050a1c99a7) - **bench:** refactor to use string interpolation in `stats/base/snanvariancech` [(#10202)](https://github.com/stdlib-js/stdlib/pull/10202) _(by Shubham)_
-   [`3ec99c9`](https://github.com/stdlib-js/stdlib/commit/3ec99c94c286bafabeee0971d4beb29b3a3fc756) - **bench:** refactor to use string interpolation in `stats/base/snanvariancepn` [(#10204)](https://github.com/stdlib-js/stdlib/pull/10204) _(by Shubham)_
-   [`40cc554`](https://github.com/stdlib-js/stdlib/commit/40cc554a45933e2bc58e7d6ec4ba7b1611006a41) - **bench:** refactor to use string interpolation in `stats/base/snanvariance` [(#10200)](https://github.com/stdlib-js/stdlib/pull/10200) _(by Shubham)_
-   [`ace22bd`](https://github.com/stdlib-js/stdlib/commit/ace22bd1a1e27e34ee1436e7ed5a82be99584f34) - **bench:** refactor to use string interpolation in `lapack/base/zrot` [(#10131)](https://github.com/stdlib-js/stdlib/pull/10131) _(by Prajjwal Bajpai)_
-   [`b47c0f0`](https://github.com/stdlib-js/stdlib/commit/b47c0f0b2d39710600184eeb20fcc9e1c870e3f9) - **feat:** add `math/base/special/sincosdf` [(#9822)](https://github.com/stdlib-js/stdlib/pull/9822) _(by Shantanu Kharwar, Philipp Burckhardt)_
-   [`0ae8a91`](https://github.com/stdlib-js/stdlib/commit/0ae8a917f3759d3228e59c3945b348398a21c7b7) - **docs:** remove extra empty line [(#10168)](https://github.com/stdlib-js/stdlib/pull/10168) _(by stdlib-bot)_
-   [`f1626a2`](https://github.com/stdlib-js/stdlib/commit/f1626a2f9e5d8a71f99d878dfb2e60132e27af6d) - **bench:** refactor to use dynamic memory allocation in `blas/base/sdsdot` [(#10188)](https://github.com/stdlib-js/stdlib/pull/10188) _(by Prajjwal Bajpai)_
-   [`e825c5f`](https://github.com/stdlib-js/stdlib/commit/e825c5f034fc6bdfe21abd22ab6f6f82eb31153c) - **bench(dcusum):** use dynamic memory allocation [(#10209)](https://github.com/stdlib-js/stdlib/pull/10209) _(by me0-0, Philipp Burckhardt)_
-   [`c34c46b`](https://github.com/stdlib-js/stdlib/commit/c34c46b17469f73663378429eca8dba95dbf1dcd) - **bench:** refactor to use string interpolation in `ndarray/array` [(#10193)](https://github.com/stdlib-js/stdlib/pull/10193) _(by Shubham)_
-   [`79a051f`](https://github.com/stdlib-js/stdlib/commit/79a051fbab0d43293a1cb71a92625c7dd2969bfa) - **feat:** add `stats/array/nanmidrange` [(#10201)](https://github.com/stdlib-js/stdlib/pull/10201) _(by Sachin Pangal, stdlib-bot)_
-   [`81fd782`](https://github.com/stdlib-js/stdlib/commit/81fd7822d544bff51fccb618844e07f7edf31e8b) - **bench:** use string interpolation in `stats/base/dists/chi` [(#10171)](https://github.com/stdlib-js/stdlib/pull/10171) _(by Om-A-osc)_
-   [`de6983f`](https://github.com/stdlib-js/stdlib/commit/de6983f8c2359024668e5b4b5e7f65eb472118ee) - **bench:** refactor to use string interpolation in `math/base/assert` [(#10195)](https://github.com/stdlib-js/stdlib/pull/10195) _(by Lokesh Ranjan)_
-   [`0a3bfa2`](https://github.com/stdlib-js/stdlib/commit/0a3bfa2d83ccf5139c1557f07b936fac61cf5838) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`a7bba71`](https://github.com/stdlib-js/stdlib/commit/a7bba712251731591ce02227e24f4d61042e1710) - **style:** fix indentation _(by Philipp Burckhardt)_
-   [`65ac870`](https://github.com/stdlib-js/stdlib/commit/65ac870bcc9363ee25cdde72514d9e0783b5395e) - **bench:** use string interpolation in `stats/base/cumax` [(#10135)](https://github.com/stdlib-js/stdlib/pull/10135) _(by Om-A-osc, Athan Reines)_
-   [`231d457`](https://github.com/stdlib-js/stdlib/commit/231d45774d3ba684ce107e85fc7df41a679845e3) - **bench:** refactor to use string interpolation in `math/base/assert` [(#10072)](https://github.com/stdlib-js/stdlib/pull/10072) _(by Lokesh Ranjan)_
-   [`1eee288`](https://github.com/stdlib-js/stdlib/commit/1eee288269d47dffe3b59766b0bb846089ad2b42) - **bench:** refactor to use string interpolation in `math/base/assert` [(#10133)](https://github.com/stdlib-js/stdlib/pull/10133) _(by Lokesh Ranjan)_
-   [`84c8c5c`](https://github.com/stdlib-js/stdlib/commit/84c8c5c9581cc66cbfad9d74f75270a01677abf5) - **bench:** refractor to use string interpolation in `stats/base/sdsnanmean` [(#10137)](https://github.com/stdlib-js/stdlib/pull/10137) _(by Shubham)_
-   [`8b905a5`](https://github.com/stdlib-js/stdlib/commit/8b905a5660d1c61e3cbac7ad25e376eb4988dcb4) - **bench:** refractor to use string interpolation in `stats/base/snanstdevpn` [(#10138)](https://github.com/stdlib-js/stdlib/pull/10138) _(by Shubham)_
-   [`f52da9e`](https://github.com/stdlib-js/stdlib/commit/f52da9e13bdc5a66f81238e00794dc4d04713f50) - **bench:** refractor to use string interpolation in `stats/base/snanstdevch` [(#10139)](https://github.com/stdlib-js/stdlib/pull/10139) _(by Shubham)_
-   [`7826bce`](https://github.com/stdlib-js/stdlib/commit/7826bce4fef1d743e5ed065281e2c067e657c8de) - **bench:** refractor to use string interpolation in `stats/base/snanstdev` [(#10140)](https://github.com/stdlib-js/stdlib/pull/10140) _(by Shubham)_
-   [`45ed6fc`](https://github.com/stdlib-js/stdlib/commit/45ed6fc6c6eee93a191b1ba9ecf89e058ad3e57d) - **bench:** refractor to use string interpolation in `stats/base/snanstdevwd` [(#10141)](https://github.com/stdlib-js/stdlib/pull/10141) _(by Shubham)_
-   [`6253df4`](https://github.com/stdlib-js/stdlib/commit/6253df45cc1376691e0bf7e044c14d64d0ceb179) - **bench:** refractor to use string interpolation in `stats/base/snanstdevtk` [(#10142)](https://github.com/stdlib-js/stdlib/pull/10142) _(by Shubham)_
-   [`2636ccd`](https://github.com/stdlib-js/stdlib/commit/2636ccdeb3d938f63e50fd110d3aad0a3cf57805) - **bench:** use string interpolation in `stats/base/ndarray/dmskmax` [(#10144)](https://github.com/stdlib-js/stdlib/pull/10144) _(by Om-A-osc)_
-   [`9d9b268`](https://github.com/stdlib-js/stdlib/commit/9d9b2684d2d965826e3fa1426a1eb204e44231a8) - **bench:** refactor to use dynamic memory allocation in `blas/base/saxpy` [(#10146)](https://github.com/stdlib-js/stdlib/pull/10146) _(by Prajjwal Bajpai)_
-   [`b22ed96`](https://github.com/stdlib-js/stdlib/commit/b22ed969fd6fcff0278ffc6c50c2ce774ab00ba7) - **bench:** refactor to use string interpolation in `blas/base/saxpy` [(#10147)](https://github.com/stdlib-js/stdlib/pull/10147) _(by Prajjwal Bajpai)_
-   [`baaed47`](https://github.com/stdlib-js/stdlib/commit/baaed472c168e6b26437cf48137cdf79c3fd544b) - **bench:** refractor to use string interpolation in `stats/base/dists/triangular` [(#10063)](https://github.com/stdlib-js/stdlib/pull/10063) _(by Shubham, Athan Reines)_
-   [`42ada99`](https://github.com/stdlib-js/stdlib/commit/42ada99a46614cf0d14f2f8f70c5d95869e08bd8) - **feat:** add C implementation of `stats/base/ndarray/dmaxabs` [(#10039)](https://github.com/stdlib-js/stdlib/pull/10039) _(by Bhargav Dabhade)_
-   [`b1ead99`](https://github.com/stdlib-js/stdlib/commit/b1ead9929135bf59212a215d8dc84b414184e919) - **chore:** fix EditorConfig lint errors [(#9969)](https://github.com/stdlib-js/stdlib/pull/9969) _(by Suyash Pathak)_
-   [`9b98e3f`](https://github.com/stdlib-js/stdlib/commit/9b98e3f6a8a80db920ed4aa05264e356aa019605) - **refactor:** reduce FLOPs _(by Athan Reines)_
-   [`1212357`](https://github.com/stdlib-js/stdlib/commit/121235768111adbe05f293a18ec2ca2ca75815df) - **bench:** use string interpolation in `stats/base/dists/cauchy/pdf` [(#10064)](https://github.com/stdlib-js/stdlib/pull/10064) _(by Om-A-osc)_
-   [`ad89c98`](https://github.com/stdlib-js/stdlib/commit/ad89c984e5b495cb695c61e1140d99067d8ebf1b) - **bench:** refractor to use string interpolation in `stats/base/dists/kumaraswamy` [(#10066)](https://github.com/stdlib-js/stdlib/pull/10066) _(by Shubham)_
-   [`8cd8362`](https://github.com/stdlib-js/stdlib/commit/8cd836257e3921abc52ad245dce15642aea6288e) - **bench:** refactor to use string interpolation in `stats/base/dists/bernoulli/ctor` [(#10053)](https://github.com/stdlib-js/stdlib/pull/10053) _(by Lokesh Ranjan, Athan Reines)_
-   [`928d410`](https://github.com/stdlib-js/stdlib/commit/928d41013a8327b8727232d4b44b2879a9687e05) - **bench:** refactor to use dynamic memory allocation in `blas/ext/base/dcusumkbn` [(#10085)](https://github.com/stdlib-js/stdlib/pull/10085) _(by Loay Ahmed)_
-   [`06e3710`](https://github.com/stdlib-js/stdlib/commit/06e37102b1e86507533abe95f50c4c44e4ddcf54) - **feat:** add C implementation for `stats/base/ndarray/dminabs` [(#10046)](https://github.com/stdlib-js/stdlib/pull/10046) _(by Samarth Kolarkar, Athan Reines)_
-   [`b1ac7f1`](https://github.com/stdlib-js/stdlib/commit/b1ac7f156f4a3e4fba31d27f4797843676515519) - **bench:** refactor to use string interpolation in `stats/base/dists/arcsine/ctor` [(#10054)](https://github.com/stdlib-js/stdlib/pull/10054) _(by Lokesh Ranjan)_
-   [`63ff72c`](https://github.com/stdlib-js/stdlib/commit/63ff72c16348d71085f70d8cb8d413921a0ce551) - **bench:** refactor to use dynamic memory allocation in `blas/base/ext/dcusumors` [(#10086)](https://github.com/stdlib-js/stdlib/pull/10086) _(by AyushiJain18270)_
-   [`06188d1`](https://github.com/stdlib-js/stdlib/commit/06188d19cb37068a0aa27c391a443a48fd6b6b56) - **bench:** fix types _(by Athan Reines)_
-   [`b2b06e2`](https://github.com/stdlib-js/stdlib/commit/b2b06e25153452e89a95ed63ae1ae4f7646d7c1d) - **bench:** fix dtypes _(by Athan Reines)_
-   [`8842552`](https://github.com/stdlib-js/stdlib/commit/884255265619ee97385a996f5444d6a437c789a1) - **bench:** refactor to use string interpolation in `stats/base/dists/betaprime` [(#10050)](https://github.com/stdlib-js/stdlib/pull/10050) _(by Harsh Yadav)_
-   [`9d71f4b`](https://github.com/stdlib-js/stdlib/commit/9d71f4b4d116829abcea63c67ffb7b61d798e11c) - **bench:** refactor to use string interpolation in `stats/base/dists/beta` [(#10049)](https://github.com/stdlib-js/stdlib/pull/10049) _(by Harsh Yadav)_
-   [`805412f`](https://github.com/stdlib-js/stdlib/commit/805412fecd7227470a7fb28606c94f00d1e7538e) - **docs:** update `ndarray/base` TypeScript declarations [(#10021)](https://github.com/stdlib-js/stdlib/pull/10021) _(by stdlib-bot)_
-   [`018fa2a`](https://github.com/stdlib-js/stdlib/commit/018fa2aa531d50354ebc463143ca9744124afb75) - **docs:** update REPL namespace documentation [(#10020)](https://github.com/stdlib-js/stdlib/pull/10020) _(by stdlib-bot)_
-   [`9696b4d`](https://github.com/stdlib-js/stdlib/commit/9696b4d2af500640e8fdd5f76a499248e3f2f17a) - **docs:** update namespace table of contents [(#10022)](https://github.com/stdlib-js/stdlib/pull/10022) _(by stdlib-bot)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 40 people contributed to this release. Thank you to the following contributors:

-   ANKIT SINGH YADAV
-   Aman Singh
-   Aryan kumar
-   Athan Reines
-   AyushiJain18270
-   Bhargav Dabhade
-   Daniel Mungai Chege
-   Geo Daoyu
-   Harsh Yadav
-   Kamal Singh Rautela
-   Kaustubh Patange
-   LZYCODEr
-   Lakshmi Sravya Vedantham
-   Loay Ahmed
-   Lokesh Ranjan
-   Manit Roy
-   Muhammad Haris
-   Nakul Krishnakumar
-   Neeraj Pathak
-   Om-A-osc
-   Partha Das
-   Philipp Burckhardt
-   Prajjwal Bajpai
-   Pratik
-   Rohit R Bhat
-   Sachin Pangal
-   Sagar Ratna Chaudhary
-   Samarth Kolarkar
-   Shantanu Kharwar
-   Shubham
-   Siddhartha Mondal
-   Suyash Pathak
-   Vipeen Kumar
-   Vishal Gaikwad
-   anee3
-   lakshmisravya123
-   me0-0
-   nakul-krishnakumar
-   nickolaif-svg
-   orthodox-64

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->


