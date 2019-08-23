# System Information Gatherer And Reporter. 

Fork of hyperic/sigar with some fixes. Support only ruby binding. Part of [Eye gem](https://github.com/kostya/eye).

## Fixed:

### [2.0.6] 18-01-2019
* Fix compilation on FreeBSD 12 [#6](https://github.com/kostya/sigar/issues/6)([commit](https://github.com/kostya/sigar/commit/2bb67fa1bf6f6f0ddc2626cf028bcc0e4a8cb377))

### [2.0.5] 02-12-2018
* Fix compilation with musl libc [#4](https://github.com/kostya/sigar/pull/4)([commit](https://github.com/kostya/sigar/pull/4/commits/cd07923dd2ed34aca353dfd182f2f85c13853fd9))

### [2.0.4] 10-06-2018
* fix compilation with glibc 2.26, major/minor functions [#2](https://github.com/kostya/sigar/issues/2)([commit](https://github.com/kostya/sigar/commit/a2c67588d0f686e0007dadcaf0e4bbb35c0e1e83))

### [2.0.2] 30-05-2018
* Remove obsolete rpc usage (fix compilation fail with glibc 2.27) [#213](https://github.com/kostya/eye/issues/213)([commit](https://github.com/kostya/sigar/commit/a971b9e8e1443fdf236c5ffa199c1994c05fcd4b))

### [2.0.1] 10-04-2018
* FreeBSD: don't use v_cache_min/max [#68](https://github.com/hyperic/sigar/pull/68)([commit](https://github.com/kostya/sigar/commit/800076db97bcacb1ba90805d740b4f9a5a1d3cca))

### [2.0.0] 22-01-2018
* sigfaulted logger, [#28](https://github.com/hyperic/sigar/pull/28)([commit](https://github.com/kostya/sigar/commit/c2a1af))
* bug undefined symbol: sigar_skip_token, [#60](https://github.com/hyperic/sigar/pull/60)([commit](https://github.com/kostya/sigar/commit/dfe8fe))
* bug detection boot_time on linux (now it works like gnu ps, and fix some issues with process start_time) ([commit](https://github.com/kostya/sigar/commit/660259))


## Installation:

    $ gem install kostya-sigar
