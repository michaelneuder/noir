# Changelog

## [0.2.0](https://github.com/michaelneuder/noir/compare/v0.1.1...v0.2.0) (2023-02-12)


### ⚠ BREAKING CHANGES

* **nargo:** bump MSRV to 1.66.0 ([#799](https://github.com/michaelneuder/noir/issues/799))
* **noir:** Returned values are no longer required by the prover ([#731](https://github.com/michaelneuder/noir/issues/731))
* **std_lib:** modulus bits/bytes methods, and to_bits -> to_le_bits ([#697](https://github.com/michaelneuder/noir/issues/697))

### Features

* **acvm:** Update to acvm 0.4.1 ([#779](https://github.com/michaelneuder/noir/issues/779)) ([6f57e86](https://github.com/michaelneuder/noir/commit/6f57e86c3d51191aa516a3b9315337b925810433))
* add support for local dependencies ([#400](https://github.com/michaelneuder/noir/issues/400)) ([5f34b79](https://github.com/michaelneuder/noir/commit/5f34b79768f86e6c6feb7df990af75a4dd1497dd))
* **ci:** Add concurrency group for rust workflow ([#806](https://github.com/michaelneuder/noir/issues/806)) ([1b80f55](https://github.com/michaelneuder/noir/commit/1b80f559599c2a7d7b8697f42f63db8e59d318c5))
* **ci:** Add concurreny group for rust workflow ([1b80f55](https://github.com/michaelneuder/noir/commit/1b80f559599c2a7d7b8697f42f63db8e59d318c5))
* **ci:** Add workflow to validate PR title ([#730](https://github.com/michaelneuder/noir/issues/730)) ([e5e8542](https://github.com/michaelneuder/noir/commit/e5e85423946e52b431a32ee37c4967bef3c2fc88))
* **ci:** Build binaries when a release is made ([#773](https://github.com/michaelneuder/noir/issues/773)) ([a0c0c2c](https://github.com/michaelneuder/noir/commit/a0c0c2c354b50c80eba425ba2f8c235015696c35))
* **ci:** Change release workflow to use release-please ([950ca55](https://github.com/michaelneuder/noir/commit/950ca5535ba52de3aafd861fd00a75d5c0bf0125))
* **docs:** Introduce Conventional Commits & release process docs ([#717](https://github.com/michaelneuder/noir/issues/717)) ([950ca55](https://github.com/michaelneuder/noir/commit/950ca5535ba52de3aafd861fd00a75d5c0bf0125))
* Impls with generics ([#798](https://github.com/michaelneuder/noir/issues/798)) ([bea735d](https://github.com/michaelneuder/noir/commit/bea735d98e162f42df5957781638101c1e6c75f6))
* improve abi checks to handle for violated range checks ([#572](https://github.com/michaelneuder/noir/issues/572)) ([a4da774](https://github.com/michaelneuder/noir/commit/a4da7740c44ea92a548af518cbaf6d5de87444fb))
* **nargo:** add `nargo execute` command ([#725](https://github.com/michaelneuder/noir/issues/725)) ([9d6be60](https://github.com/michaelneuder/noir/commit/9d6be60bbf2ef8cdeb272942fc2d3d94f5dda96f))
* **nargo:** Add `nargo test` command to run all unit tests ([#728](https://github.com/michaelneuder/noir/issues/728)) ([2e1dc82](https://github.com/michaelneuder/noir/commit/2e1dc823643c3c522eafdd38b5d92f6f431226f4))
* **nargo:** add option to save witness to file in execute command ([9d6be60](https://github.com/michaelneuder/noir/commit/9d6be60bbf2ef8cdeb272942fc2d3d94f5dda96f))
* **nargo:** add support for testing noir libraries ([#752](https://github.com/michaelneuder/noir/issues/752)) ([27bd2ac](https://github.com/michaelneuder/noir/commit/27bd2ac26370400c9605262eeb12c2b47d94149e))
* **nargo:** include short git commit in cli version output ([#721](https://github.com/michaelneuder/noir/issues/721)) ([6e01c2f](https://github.com/michaelneuder/noir/commit/6e01c2f8518e6a551acbc987b3117649d2e0ed8f))
* **nargo:** Leverage rustls instead of openssl for downloads ([#691](https://github.com/michaelneuder/noir/issues/691)) ([933809c](https://github.com/michaelneuder/noir/commit/933809cc52029330c4823d330c088e0acb4e87c3))
* **noir:** Returned values are no longer required by the prover ([#731](https://github.com/michaelneuder/noir/issues/731)) ([90b6036](https://github.com/michaelneuder/noir/commit/90b6036daf958f34b336219f1b5f99397a3250ef))
* **std_lib:** modulus bits/bytes methods, and to_bits -&gt; to_le_bits ([#697](https://github.com/michaelneuder/noir/issues/697)) ([a20e1c1](https://github.com/michaelneuder/noir/commit/a20e1c1cf26f6fbfbcafd35c0009803e66dc8354))


### Bug Fixes

* 214 ([#218](https://github.com/michaelneuder/noir/issues/218)) ([6ad1449](https://github.com/michaelneuder/noir/commit/6ad144961d569d9d18c6bf090dc4d301a0e68cda))
* 419 by disallowing bitwise operations on fields during type checking ([#687](https://github.com/michaelneuder/noir/issues/687)) ([35bef8d](https://github.com/michaelneuder/noir/commit/35bef8d84f0f4d32327dbc4dc4fd4180fd038a40))
* 577 ([#578](https://github.com/michaelneuder/noir/issues/578)) ([5da0559](https://github.com/michaelneuder/noir/commit/5da0559278ae9ec901476b1c02f5086187b916c5))
* 628 ([#653](https://github.com/michaelneuder/noir/issues/653)) ([a03ef15](https://github.com/michaelneuder/noir/commit/a03ef15e2540a13acefca7d85b81c06f84d82fdb))
* **ci:** Skip the title check if handling a merge group ([#790](https://github.com/michaelneuder/noir/issues/790)) ([71b179c](https://github.com/michaelneuder/noir/commit/71b179c4f812f773282a0911082dd759ad20c450))
* **nargo:** `nargo test` now only runs test functions defined in the current module ([#805](https://github.com/michaelneuder/noir/issues/805)) ([c6293c9](https://github.com/michaelneuder/noir/commit/c6293c9d1657a6937a95a10b931dbb6c3d9c94d7))
* operators issuing type errors when used with matching integer types arising from generic code ([#789](https://github.com/michaelneuder/noir/issues/789)) ([932943a](https://github.com/michaelneuder/noir/commit/932943a0f7af8f91ba55964ecc574e569a99508d))
* **ssa:** delete instructions with false predicate ([#760](https://github.com/michaelneuder/noir/issues/760)) ([f329379](https://github.com/michaelneuder/noir/commit/f3293793e7fd4a595971c24c4dcab9b0e7b921dd))
* **ssa:** synchronisation for functions ([#764](https://github.com/michaelneuder/noir/issues/764)) ([615357a](https://github.com/michaelneuder/noir/commit/615357af4173d767af87df9086bb9fb78fd749c6))
* typos ([8dcc8db](https://github.com/michaelneuder/noir/commit/8dcc8db6e0423761da21982c1d45dc6f7052b066))
* typos ([#458](https://github.com/michaelneuder/noir/issues/458)) ([8dcc8db](https://github.com/michaelneuder/noir/commit/8dcc8db6e0423761da21982c1d45dc6f7052b066))


### Miscellaneous Chores

* **nargo:** bump MSRV to 1.66.0 ([#799](https://github.com/michaelneuder/noir/issues/799)) ([59ff9e8](https://github.com/michaelneuder/noir/commit/59ff9e897195aede863e3c166773c222e1bc7a54))

## [0.1.1](https://github.com/noir-lang/noir/compare/v0.1.0...v0.1.1) (2023-02-06)


### Features

* **ci:** Add workflow to validate PR title ([#730](https://github.com/noir-lang/noir/issues/730)) ([e5e8542](https://github.com/noir-lang/noir/commit/e5e85423946e52b431a32ee37c4967bef3c2fc88))
* **ci:** Change release workflow to use release-please ([950ca55](https://github.com/noir-lang/noir/commit/950ca5535ba52de3aafd861fd00a75d5c0bf0125))
* **docs:** Introduce Conventional Commits & release process docs ([#717](https://github.com/noir-lang/noir/issues/717)) ([950ca55](https://github.com/noir-lang/noir/commit/950ca5535ba52de3aafd861fd00a75d5c0bf0125))
* **nargo:** add `nargo execute` command ([#725](https://github.com/noir-lang/noir/issues/725)) ([9d6be60](https://github.com/noir-lang/noir/commit/9d6be60bbf2ef8cdeb272942fc2d3d94f5dda96f))
* **nargo:** Add `nargo test` command to run all unit tests ([#728](https://github.com/noir-lang/noir/issues/728)) ([2e1dc82](https://github.com/noir-lang/noir/commit/2e1dc823643c3c522eafdd38b5d92f6f431226f4))
* **nargo:** add option to save witness to file in execute command ([9d6be60](https://github.com/noir-lang/noir/commit/9d6be60bbf2ef8cdeb272942fc2d3d94f5dda96f))
* **nargo:** add support for testing noir libraries ([#752](https://github.com/noir-lang/noir/issues/752)) ([27bd2ac](https://github.com/noir-lang/noir/commit/27bd2ac26370400c9605262eeb12c2b47d94149e))
* **nargo:** Leverage rustls instead of openssl for downloads ([#691](https://github.com/noir-lang/noir/issues/691)) ([933809c](https://github.com/noir-lang/noir/commit/933809cc52029330c4823d330c088e0acb4e87c3))
