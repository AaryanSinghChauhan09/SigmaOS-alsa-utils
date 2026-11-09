SigmaOS alsa-utils
==================

This repository currently contains a small Rust CLI scaffold for planned ALSA
utility integration. Its ``Tool`` API handles ``help``, ``status``, and
``version`` responses; it does not access audio devices or invoke ALSA tools.

The library and its tests are in ``src/lib.rs`` and ``tests/``. See the
`SigmaOS component wiki <https://github.com/AaryanSinghChauhan09/SigmaOS/wiki/Component-SigmaOS-alsa-utils-Guide>`_
for registry metadata and current implementation scope.

License metadata needs reconciliation before release: ``Cargo.toml`` and the
repository ``LICENSE`` declare MIT, while ``src/lib.rs`` has an Apache-2.0
SPDX header.
