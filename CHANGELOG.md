# Changelog

## [3.3.3](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/3.3.2...3.3.3) (2022-05-24)

- chore: release v3.3.3 [`a95f894`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/a95f894d3861ba8f296f094717fa7451dfc9d333)
- fix(ecs-ipfs): index log group [`ddfad47`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/ddfad47c410e5c47010bf3264b071bdf32baecd1)

## [3.3.2](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/3.3.1...3.3.2) (2022-05-24)

- chore: release v3.3.2 [`04e705c`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/04e705cdbfe04933e845639ea7883c5ddd0f349b)
- fix(ecs-ipfs): get default tags from locals [`dbd5509`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/dbd5509a3ca7b560675e720dcf1fcf336d4e201d)

## [3.3.1](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/3.3.0...3.3.1) (2022-05-24)

- feat(ecs): increase log group retention and prevent destroy [`f7e4459`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/f7e4459a789c7ebc76bb82722d1398a9e4d45140)
- fix(ecs-ipfs): add cloudwatch log group for datasync [`0596753`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/05967537aaa037bded5efb9d42480b54367f8d8b)
- chore: release v3.3.1 [`c83a6df`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c83a6df9d93d559ba59716192846049c16501cdf)

## [3.3.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/3.2.0...3.3.0) (2022-05-24)

- feat(ipfs): backup repo to s3 via datasync [`#16`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/16)
- chore: release v3.3.0 [`52d0eb8`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/52d0eb81bc3c89183acf04c29a5e07d63c379ce3)
- docs: bump minor version [`d6938d5`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/d6938d5c70c516edbfad734b9bcc8aa651bd137e)
- fix: update version in README.md [`f57a469`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/f57a469fe49e183484e7fc6d3c0f227decfad996)
- docs: add precondition for IPFS repo [`6f86059`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/6f86059a9ca2dde56bb987380604b6e70ad02fbf)

## [3.2.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/3.1.0...3.2.0) (2022-04-22)

- docs: update readme for pre-conditions [`#14`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/14)
- feat: make ssm peer id and private key optional [`#15`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/15)
- feat: ecs exec [`4ce0f36`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/4ce0f36fc9ac369e8d472c774bf9f56ab61ab5b4)
- fix: add `count` to `existing_peer` task definition [`fe6548f`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/fe6548ffcbca6df98603781bf5aa3d1d9cfd58c6)
- chore: release v3.2.0 [`e29ed5e`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/e29ed5e4b29a07ae42e638e26b3dc1312ecb3d88)

## [3.1.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/3.0.0...3.1.0) (2022-04-19)

- chore: release v3.1.0 [`60f1306`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/60f13061f827b9291edb439276ff9efe1cfd99e9)
- chore: update ipfs s3 root directory [`6c63585`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/6c6358534547bd00bb63927d78c15d1510d4327b)

## [3.0.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.3.0...3.0.0) (2022-04-10)

- feat: use `go-ipfs` instead of `js-ipfs` [`#13`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/13)
- Update README.md [`34873f9`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/34873f9294128b53c4f8558e226e46e139e7f22d)
- chore: release v3.0.0 [`42bc30c`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/42bc30c60c0ef113f6a45218b44e6136fa603b06)
- Update README.md [`079efb8`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/079efb8126a0b51ef35e3c1543c612cfca57ebbc)

## [2.3.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.2.0...2.3.0) (2022-04-07)

- fix: set ipfs ssl with bool [`22c9aec`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/22c9aec0cd9775cb35b52556f3ed09c42c6e81cd)
- chore: release v2.3.0 [`0505b16`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/0505b16469d4ab9f6edff5b03556a8a15b605012)

## [2.2.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.1.1...2.2.0) (2022-04-07)

- Ceramic v2 compatibility [`#12`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/12)
- Configure IPFS storage backends for ECS [`#10`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/10)
- Make ALB logs for IPFS optional [`#9`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/9)
- CORS default [`#4`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/4)
- Create pull_request_template.md [`b9c640c`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/b9c640c458c2d6eb7584b723e7b1470cce726c6d)
- Update issue templates [`a71a7a4`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/a71a7a45a46e31485d737418d9c41939c8af0321)
- chore: release v2.2.0 [`b5e3677`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/b5e3677acf3d8190878a11b6d0115df013933db4)
- fix(ecs-ipfs): update iam for s3 access [`b008317`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/b008317b2d2da2d1e32a1c6dd7034ed8443934e9)
- Rename .github/ISSUE_TEMPLATE/pull_request_template.md to .github/pull_request_template.md [`2b1dcf2`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/2b1dcf2ca8399e80a9cd5b06090495cd4e65b7b5)

## [2.1.1](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.1.0...2.1.1) (2021-08-27)

- chore: release v2.1.1 [`738639f`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/738639f8020b8d80def0d0e19f30d8e21d46ca95)
- feat: remove noop ipfs env var [`99a6248`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/99a6248efeb629642a20fcddb3acf31b204f3332)

## [2.1.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.0.4...2.1.0) (2021-05-28)

- chore: release v2.1.0 [`c75291a`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c75291a8aef8253440a3724a2d86d7c56278bdf4)
- feat: disable ipfs gateway and enable dht server mode [`dc89005`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/dc89005baa45d15beb68b0297f7301466df376d4)

## [2.0.4](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.0.3...2.0.4) (2021-05-21)

- feat: optionally pass ceramic network to ipfs [`7576971`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/7576971933c1dfb987542112c12a31e7436a86ac)
- chore: release v2.0.4 [`c8051cf`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c8051cf81e0c24d40688ff69dce3f4ede3b7bb6b)

## [2.0.3](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.0.2...2.0.3) (2021-05-21)

- fix: use s3 for ipfs backends [`9f280bc`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/9f280bc748d4d89e758dc5ad16e9cc8a5d1e6b41)
- chore: release v2.0.3 [`37f013e`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/37f013e47a460e23cdca2c058af5a51516decd7e)

## [2.0.2](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.0.1...2.0.2) (2021-05-21)

- chore: release v2.0.2 [`1425bfc`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/1425bfcb30aee8e26029ab2952492c256c37168a)
- fix: remove gateway flag from ceramic [`a70cce2`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/a70cce23e72a8564631c2a58538c48c17bbb0514)
- docs: update example version number [`3cc786a`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/3cc786a553fc5bc51d27f0c0e924d541ac6c664a)

## [2.0.1](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/2.0.0...2.0.1) (2021-05-21)

- chore: release v2.0.1 [`e4f7c17`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/e4f7c170991606a6773172a5dc2fc99c5727d50f)
- fix: remove gateway flag from ceramic [`2bcbe06`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/2bcbe061278ab05761681b2155f7507fcc6175c9)

## [2.0.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.1.0...2.0.0) (2021-05-21)

- feat: update ipfs subdomains [`66743d0`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/66743d052bcd8f0b0c171aeaed48c72923ebf7a9)
- chore: release v2.0.0 [`205726e`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/205726efe3c415832c8bffc15d4dd65887badbc9)

## [1.1.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.0.5...1.1.0) (2021-05-20)

- feat: output ceramic dns name [`205a0a4`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/205a0a4aad41df21264cc048e456e597bcc71be0)
- chore: release v1.1.0 [`6fab5c2`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/6fab5c219e0c249ab88ee07e0c40348709218d2c)

## [1.0.5](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.0.4...1.0.5) (2021-05-20)

- fix: use resource for s3 list bucket [`569b8ad`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/569b8ad97660fe85ec554719ac8acd39f0873dec)
- chore: release v1.0.5 [`c1a98f3`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c1a98f39137448c610315cf22c1f0bacfeaaea4c)

## [1.0.4](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.0.3...1.0.4) (2021-05-20)

- fix: uncomment iam groups [`5cca912`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/5cca9126d139c517d3129971fd7f9c12783152e1)
- chore: release v1.0.4 [`56d6151`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/56d61516c37503e67d9ce760c5b080e7793b6400)

## [1.0.3](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.0.2...1.0.3) (2021-05-20)

- fix: add iam groups [`f7dcb85`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/f7dcb85ee6964d664eacc39188ca6aedfe07a10b)
- chore: release v1.0.3 [`c19da10`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c19da10beac7a665863bfa4d3dfc2de7f92fc99e)
- docs: add note about release dir [`4063698`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/4063698cd790d1cc6230c39e0f2e4075313de037)

## [1.0.2](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.0.1...1.0.2) (2021-05-20)

- chore: release v1.0.2 [`acdfec7`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/acdfec7dc57ef08ba3d5a46d225679dcdc90f51d)
- feat: remove allow empty from release-it [`5e50ce3`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/5e50ce368207100ff3a6444d2c7974287ac5d5dc)
- fix: add flag to release-it hook [`9f92675`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/9f926754240f6d8f3c3f83c31b1a7b2a77d38394)

## [1.0.1](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/1.0.0...1.0.1) (2021-05-20)

- chore: release v1.0.1 [`e07a8c2`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/e07a8c201a354c20ee984b5807767ecf30a63a28)
- docs: add changelog [`2c47ae5`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/2c47ae5acc6d26077a23f59f664084dcb6adeb8e)
- feat: add changelog to release [`9453a0a`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/9453a0a23b1e211a5bbc7f3f83abce4bfcd3c4c1)
- fix: allow empty release commits [`c8623df`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c8623dfb2ea31703ab82bdbb52db74e3bdc07242)
- docs: clean up wording [`d019c82`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/d019c8209d0a00d6a2fdca119b75805b29244adb)

## [1.0.0](https://github.com/Jackieyewang/terraform-aws-ceramic/compare/0.0.1...1.0.0) (2021-05-20)

- Clean up for deployment [`#2`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/2)
- docs: add development section [`240c754`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/240c7544a96137b622c7d9d0f8d37e5e19513a81)

## 0.0.1 (2021-05-13)

- Feat/#279: ELP Infra [`#1`](https://github.com/Jackieyewang/terraform-aws-ceramic/pull/1)
- fmt [`c63128a`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/c63128aa810dd051ef348523e3bdb79364fbfb8a)
- Initial commit [`1ef7365`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/1ef7365ed101ba589ba124e26493db22c182298d)
- feat: add no-verify flag to release-it [`029c09c`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/029c09c21a5b43ba16ec55dbe7f30356c0a3435e)
- feat: add release it [`8152bd4`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/8152bd44f7f2e8fb09f1590ebf51d33124d5daba)
- feat: add precommit [`b6ad019`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/b6ad0193b45546abf353992f478cae83fac96cce)
- fix: add required files for publishing [`39709f8`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/39709f86167f96c972616ba265bc3c605ca53f8a)
- feat: add standard terraform structure [`913df25`](https://github.com/Jackieyewang/terraform-aws-ceramic/commit/913df25dfbed6514fb256be416f95163f42c15e0)
