# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-01-26)

<section class="features">

### Features

-   [`f6efb5e`](https://github.com/stdlib-js/stdlib/commit/f6efb5ea8dbd31affbd90bb35c8de06b33bb3704) - add support for float16 array types [(#9806)](https://github.com/stdlib-js/stdlib/pull/9806)
-   [`b1a1b7f`](https://github.com/stdlib-js/stdlib/commit/b1a1b7fe3c8b93365c70632b726d6797d2af4438) - add support for ndarray data type objects and update existing type definitions
-   [`061325b`](https://github.com/stdlib-js/stdlib/commit/061325b654cc24df9e3a22db6dc04a043ec3327a) - add data type string type definitions
-   [`59de9af`](https://github.com/stdlib-js/stdlib/commit/59de9af4fe3b0f11fd63d9325a9bc4c9589a66e6) - add `MatrixOrientation` type definition
-   [`0b8d575`](https://github.com/stdlib-js/stdlib/commit/0b8d575e0c787c115519dee6d61e054739ea5512) - add accumulation input casting policy
-   [`d190eea`](https://github.com/stdlib-js/stdlib/commit/d190eea269491a659fe14618dff48bf701998813) - add input ndarray casting policies
-   [`e931ab0`](https://github.com/stdlib-js/stdlib/commit/e931ab0052e0b209c6e2693247d477a2cc8dc7af) - add accumulation and index output policies
-   [`6434c4c`](https://github.com/stdlib-js/stdlib/commit/6434c4c682aabf548a48569b05bd9096dfef10d2) - add array indexing data type kinds
-   [`78bdf25`](https://github.com/stdlib-js/stdlib/commit/78bdf258a7dc0ba33814cb4b3fd1f01a560777e0) - add output policies which provide special accommodation for the \"generic\" data type
-   [`c82dc90`](https://github.com/stdlib-js/stdlib/commit/c82dc908163b731fd5b7f33010f697779518afda) - add index types and reduce duplication
-   [`8e1a0b9`](https://github.com/stdlib-js/stdlib/commit/8e1a0b90271cbd1e64deebe7d893eeb73edf4599) - add ndarray dtype maps and index types

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`b1a1b7f`](https://github.com/stdlib-js/stdlib/commit/b1a1b7fe3c8b93365c70632b726d6797d2af4438): add support for data type objects

    -   To migrate, users should avoid accessing ndarray properties via
        property accessors and instead use functional APIs, such as
        `@stdlib/ndarray/dtype`. If a string is expected, wrap the call
        to `ndarray/dtype` with `String(dt)` to force the dtype value to
        always be a string.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`f6efb5e`](https://github.com/stdlib-js/stdlib/commit/f6efb5ea8dbd31affbd90bb35c8de06b33bb3704) - **feat:** add support for float16 array types [(#9806)](https://github.com/stdlib-js/stdlib/pull/9806) _(by Gururaj Gurram)_
-   [`64fa79c`](https://github.com/stdlib-js/stdlib/commit/64fa79c79b2aa6a98404676be3c05b5048684011) - **style:** disable lint rule _(by Athan Reines)_
-   [`b1a1b7f`](https://github.com/stdlib-js/stdlib/commit/b1a1b7fe3c8b93365c70632b726d6797d2af4438) - **feat:** add support for ndarray data type objects and update existing type definitions _(by Athan Reines)_
-   [`061325b`](https://github.com/stdlib-js/stdlib/commit/061325b654cc24df9e3a22db6dc04a043ec3327a) - **feat:** add data type string type definitions _(by Athan Reines)_
-   [`59de9af`](https://github.com/stdlib-js/stdlib/commit/59de9af4fe3b0f11fd63d9325a9bc4c9589a66e6) - **feat:** add `MatrixOrientation` type definition _(by Athan Reines)_
-   [`0b8d575`](https://github.com/stdlib-js/stdlib/commit/0b8d575e0c787c115519dee6d61e054739ea5512) - **feat:** add accumulation input casting policy _(by Athan Reines)_
-   [`d190eea`](https://github.com/stdlib-js/stdlib/commit/d190eea269491a659fe14618dff48bf701998813) - **feat:** add input ndarray casting policies _(by Athan Reines)_
-   [`e931ab0`](https://github.com/stdlib-js/stdlib/commit/e931ab0052e0b209c6e2693247d477a2cc8dc7af) - **feat:** add accumulation and index output policies _(by Athan Reines)_
-   [`6434c4c`](https://github.com/stdlib-js/stdlib/commit/6434c4c682aabf548a48569b05bd9096dfef10d2) - **feat:** add array indexing data type kinds _(by Athan Reines)_
-   [`245e6f9`](https://github.com/stdlib-js/stdlib/commit/245e6f9961dc243789357c90f8aec3a16bef0bc0) - **refactor:** improve type specificity and ensure consistency between ndarray types _(by Athan Reines)_
-   [`78bdf25`](https://github.com/stdlib-js/stdlib/commit/78bdf258a7dc0ba33814cb4b3fd1f01a560777e0) - **feat:** add output policies which provide special accommodation for the \"generic\" data type _(by Athan Reines)_
-   [`0e81d53`](https://github.com/stdlib-js/stdlib/commit/0e81d53283cb6d6e1d1b95194115d424cc719b80) - **style:** resolve lint error _(by Athan Reines)_
-   [`c82dc90`](https://github.com/stdlib-js/stdlib/commit/c82dc908163b731fd5b7f33010f697779518afda) - **feat:** add index types and reduce duplication _(by Athan Reines)_
-   [`8e1a0b9`](https://github.com/stdlib-js/stdlib/commit/8e1a0b90271cbd1e64deebe7d893eeb73edf4599) - **feat:** add ndarray dtype maps and index types _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gururaj Gurram

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.4.3">

## 0.4.3 (2024-11-05)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.4.2">

## 0.4.2 (2024-11-05)

<section class="features">

### Features

-   [`8a705c1`](https://github.com/stdlib-js/stdlib/commit/8a705c186da6520d402005633f397819a131581c) - add `wasm` namespace

</section>

<!-- /.features -->

<section class="commits">

### Commits

<details>

-   [`3723016`](https://github.com/stdlib-js/stdlib/commit/372301698741dabe395a42571d592c181920152f) - **style:** disable lint rule _(by Athan Reines)_
-   [`8a705c1`](https://github.com/stdlib-js/stdlib/commit/8a705c186da6520d402005633f397819a131581c) - **feat:** add `wasm` namespace _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.4.1">

## 0.4.1 (2024-08-18)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.4.0">

## 0.4.0 (2024-08-17)

<section class="features">

### Features

-   [`2254a56`](https://github.com/stdlib-js/stdlib/commit/2254a5616945ee973f080c6d35f19e51778e24ee) - add `blas/base/strmv` [(#2535)](https://github.com/stdlib-js/stdlib/pull/2535)
-   [`4bdd095`](https://github.com/stdlib-js/stdlib/commit/4bdd09568cf3d39d09c82aa19b5f4e271cce4af3) - add `booleanndarray` and `boolndarray` type definitions
-   [`16e0808`](https://github.com/stdlib-js/stdlib/commit/16e0808004b7bd4f16eea7eced5229ee1120b577) - add boolean dtype support to `ndarray/dtypes` [(#2550)](https://github.com/stdlib-js/stdlib/pull/2550)
-   [`62744b5`](https://github.com/stdlib-js/stdlib/commit/62744b5bd1fc7a9502d527be5ff3239f0491e05c) - add `blas/base/ssymv` [(#2305)](https://github.com/stdlib-js/stdlib/pull/2305)
-   [`c8ed312`](https://github.com/stdlib-js/stdlib/commit/c8ed31299777aa990960a022e3f6ea161ac7ff76) - add boolean array types
-   [`819d2e4`](https://github.com/stdlib-js/stdlib/commit/819d2e407146d4dcc17f8bab53b591b3d573f8a1) - add data type maps and replace use of overloads [(#1317)](https://github.com/stdlib-js/stdlib/pull/1317)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`2254a56`](https://github.com/stdlib-js/stdlib/commit/2254a5616945ee973f080c6d35f19e51778e24ee): rename `none` transpose operation to `no-transpose` in `@stdlib/types`

    -   To migrate, users should change their usage of `none` to `no-transpose`. This change enhances code readability and aligns the string literal with the C enumeration constant.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`2254a56`](https://github.com/stdlib-js/stdlib/commit/2254a5616945ee973f080c6d35f19e51778e24ee) - **feat:** add `blas/base/strmv` [(#2535)](https://github.com/stdlib-js/stdlib/pull/2535) _(by Aman Bhansali, Athan Reines)_
-   [`4bdd095`](https://github.com/stdlib-js/stdlib/commit/4bdd09568cf3d39d09c82aa19b5f4e271cce4af3) - **feat:** add `booleanndarray` and `boolndarray` type definitions _(by Athan Reines)_
-   [`16e0808`](https://github.com/stdlib-js/stdlib/commit/16e0808004b7bd4f16eea7eced5229ee1120b577) - **feat:** add boolean dtype support to `ndarray/dtypes` [(#2550)](https://github.com/stdlib-js/stdlib/pull/2550) _(by Jaysukh Makvana, Athan Reines)_
-   [`62744b5`](https://github.com/stdlib-js/stdlib/commit/62744b5bd1fc7a9502d527be5ff3239f0491e05c) - **feat:** add `blas/base/ssymv` [(#2305)](https://github.com/stdlib-js/stdlib/pull/2305) _(by Aman Bhansali, Athan Reines)_
-   [`c8ed312`](https://github.com/stdlib-js/stdlib/commit/c8ed31299777aa990960a022e3f6ea161ac7ff76) - **feat:** add boolean array types _(by Athan Reines)_
-   [`819d2e4`](https://github.com/stdlib-js/stdlib/commit/819d2e407146d4dcc17f8bab53b591b3d573f8a1) - **feat:** add data type maps and replace use of overloads [(#1317)](https://github.com/stdlib-js/stdlib/pull/1317) _(by Philipp Burckhardt, Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 4 people contributed to this release. Thank you to the following contributors:

-   Aman Bhansali
-   Athan Reines
-   Jaysukh Makvana
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.3.2">

## 0.3.2 (2024-02-21)

<section class="features">

### Features

-   [`68f8e27`](https://github.com/stdlib-js/stdlib/commit/68f8e278c133feec5dda214511f737a68dc3ad7e) - add array index type definitions
-   [`2688213`](https://github.com/stdlib-js/stdlib/commit/2688213b4b1fdc884f4f15b8ec8fe45f44d45e5e) - add \"typed\" to list of data type kinds

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`af32757`](https://github.com/stdlib-js/stdlib/commit/af32757a3fc6c17f6c15bb793f1b2845a8349b8d) - allow `dtype` to be `null`
-   [`8ea713a`](https://github.com/stdlib-js/stdlib/commit/8ea713aa09d3e68311eb1da7c6ffe99635a6e2b5) - allow `dtype` to be `null`
-   [`195184a`](https://github.com/stdlib-js/stdlib/commit/195184a6c145cd8896f46a1318215e92bcde741f) - include boolean and undefined in index signature to satisy TS

</section>

<!-- /.bug-fixes -->

<section class="commits">

### Commits

<details>

-   [`af32757`](https://github.com/stdlib-js/stdlib/commit/af32757a3fc6c17f6c15bb793f1b2845a8349b8d) - **fix:** allow `dtype` to be `null` _(by Athan Reines)_
-   [`8ea713a`](https://github.com/stdlib-js/stdlib/commit/8ea713aa09d3e68311eb1da7c6ffe99635a6e2b5) - **fix:** allow `dtype` to be `null` _(by Athan Reines)_
-   [`68f8e27`](https://github.com/stdlib-js/stdlib/commit/68f8e278c133feec5dda214511f737a68dc3ad7e) - **feat:** add array index type definitions _(by Athan Reines)_
-   [`195184a`](https://github.com/stdlib-js/stdlib/commit/195184a6c145cd8896f46a1318215e92bcde741f) - **fix:** include boolean and undefined in index signature to satisy TS _(by Philipp Burckhardt)_
-   [`ffd9201`](https://github.com/stdlib-js/stdlib/commit/ffd9201e73c2a0d27108f5c64e4fde451924ae50) - **refactor:** inline union _(by Athan Reines)_
-   [`2688213`](https://github.com/stdlib-js/stdlib/commit/2688213b4b1fdc884f4f15b8ec8fe45f44d45e5e) - **feat:** add \"typed\" to list of data type kinds _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.3.1">

## 0.3.1 (2024-02-05)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.3.0">

## 0.3.0 (2024-02-05)

<section class="features">

### Features

-   [`a37ebf5`](https://github.com/stdlib-js/stdlib/commit/a37ebf5627a53b5e52924f00ce15faf3f954884e) - extend data type kinds to include \"generic\" variations
-   [`2e68ac6`](https://github.com/stdlib-js/stdlib/commit/2e68ac699f5458f25ca2c62a07c4b23148d0575e) - add type definitions for data type \"kinds\"
-   [`e25b23b`](https://github.com/stdlib-js/stdlib/commit/e25b23b917ee6e387722db7192d22e4a70222da0) - rename type definitions for array and ndarray data types
-   [`43285ee`](https://github.com/stdlib-js/stdlib/commit/43285ee720a90e182524b20701935dee5af48886) - add interface describing ndarray flags
-   [`1fc9020`](https://github.com/stdlib-js/stdlib/commit/1fc9020622fa791746dc9e9457979cef355f3db6) - add support for `normalize` index mode

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`e25b23b`](https://github.com/stdlib-js/stdlib/commit/e25b23b917ee6e387722db7192d22e4a70222da0): rename type definitions for array and ndarray data types

    -   In order to migrate, users should update their implementations to
        use the latest naming conventions. The affected type definitions
        are aliases for individual data type strings, so their should be
        no behavioral changes.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`a37ebf5`](https://github.com/stdlib-js/stdlib/commit/a37ebf5627a53b5e52924f00ce15faf3f954884e) - **feat:** extend data type kinds to include \"generic\" variations _(by Athan Reines)_
-   [`2e68ac6`](https://github.com/stdlib-js/stdlib/commit/2e68ac699f5458f25ca2c62a07c4b23148d0575e) - **feat:** add type definitions for data type \"kinds\" _(by Athan Reines)_
-   [`e25b23b`](https://github.com/stdlib-js/stdlib/commit/e25b23b917ee6e387722db7192d22e4a70222da0) - **feat:** rename type definitions for array and ndarray data types _(by Athan Reines)_
-   [`f4a22f1`](https://github.com/stdlib-js/stdlib/commit/f4a22f17477b622a8dd500d831c57f8a01f7b820) - **docs:** fix description _(by Athan Reines)_
-   [`43285ee`](https://github.com/stdlib-js/stdlib/commit/43285ee720a90e182524b20701935dee5af48886) - **feat:** add interface describing ndarray flags _(by Athan Reines)_
-   [`1fc9020`](https://github.com/stdlib-js/stdlib/commit/1fc9020622fa791746dc9e9457979cef355f3db6) - **feat:** add support for `normalize` index mode _(by Athan Reines)_
-   [`d1ea078`](https://github.com/stdlib-js/stdlib/commit/d1ea078e4075bd1c77fb27f7977b17a436fe940c) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2023-11-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-22)

<section class="features">

### Features

-   [`3af398c`](https://github.com/stdlib-js/stdlib/commit/3af398c171b2e6608b0a013dfdd8ca2ee943b23d) - add `MultiSlice` interface
-   [`775de05`](https://github.com/stdlib-js/stdlib/commit/775de0592650d6d50ee49f201a36832d0c959688) - add module for slice definitions
-   [`9ceabce`](https://github.com/stdlib-js/stdlib/commit/9ceabcefa3f213b90d5827baf5e480e10285797f) - add shape for zero-dimensional ndarray
-   [`21ec8a6`](https://github.com/stdlib-js/stdlib/commit/21ec8a6790cd4f5c8950f141b7a46685132a9eb6) - add types for shapes and strides corresponding to specific dimensionalities
-   [`bde4671`](https://github.com/stdlib-js/stdlib/commit/bde4671201dfa6b510f88bcb60d455f44c0842e1) - move `Collection` type defn to array type module
-   [`fa7e420`](https://github.com/stdlib-js/stdlib/commit/fa7e420dcfc39a1af4c43ea43cf6e0353786a519) - move complex number types to separate module
-   [`b0b5d31`](https://github.com/stdlib-js/stdlib/commit/b0b5d319f73a3804eb70ce1079be2bba3852df63) - add nested array types
-   [`edcd742`](https://github.com/stdlib-js/stdlib/commit/edcd74294f953cdba01e61a0b088942283c79d20) - convert `Collection` to generic
-   [`191e983`](https://github.com/stdlib-js/stdlib/commit/191e98381657335c8b6d55b5c199d558484239dd) - add `OutputPolicies` type definition
-   [`164ae5a`](https://github.com/stdlib-js/stdlib/commit/164ae5ad933fb7b0e0817efb6b65a0ec052c44bb) - convert `genericndarray` to a generic to allow better specificity

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`66c36f4`](https://github.com/stdlib-js/stdlib/commit/66c36f49864867c19a59bbdf7661b5d9b05d99f9) - rename `OutputPolicies` to `OutputPolicy` to make data type defs

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`bde4671`](https://github.com/stdlib-js/stdlib/commit/bde4671201dfa6b510f88bcb60d455f44c0842e1): move `Collection` type defn to array type module

    -   To migrate, users should import `@stdlib/types/array` instead of
        `@stdlib/types/object` when using the `Collection` type definition.

-   [`fa7e420`](https://github.com/stdlib-js/stdlib/commit/fa7e420dcfc39a1af4c43ea43cf6e0353786a519): move complex number types to separate module

    -   To migrate, users should import `@stdlib/types/complex` instead of
        `@stdlib/types/object` when wanting to use complex number type
        definitions.

-   [`edcd742`](https://github.com/stdlib-js/stdlib/commit/edcd74294f953cdba01e61a0b088942283c79d20): `Collection` is now a generic

    -   To migrate, users should upgrade their TypeScript version and
        provide element type information when using the `Collection` type
        (e.g., `Collection<number>`). By default, the element type is `any`
        which is equivalent to previous behavior.

-   [`164ae5a`](https://github.com/stdlib-js/stdlib/commit/164ae5ad933fb7b0e0817efb6b65a0ec052c44bb): convert type to a generic

    -   To migrate, users should update usage by providing an explicit type.
        Existing code should continue to work as is; however, for better
        specificity and type hints, providing a type is advised.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`3af398c`](https://github.com/stdlib-js/stdlib/commit/3af398c171b2e6608b0a013dfdd8ca2ee943b23d) - **feat:** add `MultiSlice` interface _(by Athan Reines)_
-   [`775de05`](https://github.com/stdlib-js/stdlib/commit/775de0592650d6d50ee49f201a36832d0c959688) - **feat:** add module for slice definitions _(by Athan Reines)_
-   [`9ceabce`](https://github.com/stdlib-js/stdlib/commit/9ceabcefa3f213b90d5827baf5e480e10285797f) - **feat:** add shape for zero-dimensional ndarray _(by Athan Reines)_
-   [`21ec8a6`](https://github.com/stdlib-js/stdlib/commit/21ec8a6790cd4f5c8950f141b7a46685132a9eb6) - **feat:** add types for shapes and strides corresponding to specific dimensionalities _(by Athan Reines)_
-   [`bde4671`](https://github.com/stdlib-js/stdlib/commit/bde4671201dfa6b510f88bcb60d455f44c0842e1) - **feat:** move `Collection` type defn to array type module _(by Athan Reines)_
-   [`fa7e420`](https://github.com/stdlib-js/stdlib/commit/fa7e420dcfc39a1af4c43ea43cf6e0353786a519) - **feat:** move complex number types to separate module _(by Athan Reines)_
-   [`b0b5d31`](https://github.com/stdlib-js/stdlib/commit/b0b5d319f73a3804eb70ce1079be2bba3852df63) - **feat:** add nested array types _(by Athan Reines)_
-   [`edcd742`](https://github.com/stdlib-js/stdlib/commit/edcd74294f953cdba01e61a0b088942283c79d20) - **feat:** convert `Collection` to generic _(by Athan Reines)_
-   [`66c36f4`](https://github.com/stdlib-js/stdlib/commit/66c36f49864867c19a59bbdf7661b5d9b05d99f9) - **fix:** rename `OutputPolicies` to `OutputPolicy` to make data type defs _(by Athan Reines)_
-   [`191e983`](https://github.com/stdlib-js/stdlib/commit/191e98381657335c8b6d55b5c199d558484239dd) - **feat:** add `OutputPolicies` type definition _(by Athan Reines)_
-   [`164ae5a`](https://github.com/stdlib-js/stdlib/commit/164ae5ad933fb7b0e0817efb6b65a0ec052c44bb) - **feat:** convert `genericndarray` to a generic to allow better specificity _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.14">

## 0.0.14 (2022-02-18)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.13">

## 0.0.13 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.12">

## 0.0.12 (2021-07-06)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.11">

## 0.0.11 (2021-06-27)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.10">

## 0.0.10 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.9">

## 0.0.9 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.8">

## 0.0.8 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2021-06-13)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2021-06-13)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-06-12)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-06-12)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-10)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-10)

No changes reported for this release.

</section>

<!-- /.release -->

