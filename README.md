# Merge log

Scroll down for the original README.md!

Base revision: 50b5bb44a009dc899d0d7722e50d8976ce4e34f1

|Pull Request|Commit|Title|Author|Merged?|
|----|----|----|----|----|
|[1](https://github.com/yuzu-emu/yuzu-canary/pull/1)|[a8dfe54](https://github.com/yuzu-emu/yuzu-canary/pull/1/files/)|Canary Base|[chris062689](https://github.com/chris062689)|Yes|
|[2824](https://github.com/yuzu-emu/yuzu/pull/2824)|[a7f6831](https://github.com/yuzu-emu/yuzu/pull/2824/files/)|Revert "Revert #2466" and stub FirmwareCall 4|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2812](https://github.com/yuzu-emu/yuzu/pull/2812)|[e353470](https://github.com/yuzu-emu/yuzu/pull/2812/files/)|shader_ir/conversion: Implement F2I and F2F F16 selector|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2811](https://github.com/yuzu-emu/yuzu/pull/2811)|[6207751](https://github.com/yuzu-emu/yuzu/pull/2811/files/)|float_set_predicate: Add missing negation bit for the second operand|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2810](https://github.com/yuzu-emu/yuzu/pull/2810)|[9bf77ce](https://github.com/yuzu-emu/yuzu/pull/2810/files/)|maxwell_3d: Avoid moving macro_params|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2802](https://github.com/yuzu-emu/yuzu/pull/2802)|[f83f222](https://github.com/yuzu-emu/yuzu/pull/2802/files/)|half_set_predicate: Fix HSETP2 predicate assignments|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2801](https://github.com/yuzu-emu/yuzu/pull/2801)|[9144a48](https://github.com/yuzu-emu/yuzu/pull/2801/files/)|gl_shader_decompiler: Rework GLSL decompiler type system|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2793](https://github.com/yuzu-emu/yuzu/pull/2793)|[80702aa](https://github.com/yuzu-emu/yuzu/pull/2793/files/)| renderer_opengl: Implement RGB565 framebuffer format |[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2759](https://github.com/yuzu-emu/yuzu/pull/2759)|[cf066e5](https://github.com/yuzu-emu/yuzu/pull/2759/files/)|gl_rasterizer: Bind images and samplers to compute|[ReinUsesLisp](https://github.com/ReinUsesLisp)|Yes|
|[2710](https://github.com/yuzu-emu/yuzu/pull/2710)|[abb2c5f](https://github.com/yuzu-emu/yuzu/pull/2710/files/)|am/kernel: Fix various bugs related to applet signalling and software keyboard|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2707](https://github.com/yuzu-emu/yuzu/pull/2707)|[adab188](https://github.com/yuzu-emu/yuzu/pull/2707/files/)|system_archive: Add open-source reimplementation of MiiModel data|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2542](https://github.com/yuzu-emu/yuzu/pull/2542)|[7aeb676](https://github.com/yuzu-emu/yuzu/pull/2542/files/)|lbl: Implement brightness and backlight services|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2444](https://github.com/yuzu-emu/yuzu/pull/2444)|[5d60166](https://github.com/yuzu-emu/yuzu/pull/2444/files/)|Port citra-emu/citra#3617: "QT: Add support for multiple game directories"|[FearlessTobi](https://github.com/FearlessTobi)|Yes|
|[2418](https://github.com/yuzu-emu/yuzu/pull/2418)|[50d5414](https://github.com/yuzu-emu/yuzu/pull/2418/files/)|es: Implement various ticket accessor commands from IEticketService|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[2365](https://github.com/yuzu-emu/yuzu/pull/2365)|[4fe8093](https://github.com/yuzu-emu/yuzu/pull/2365/files/)|Workaround to Mutex Corruption|[FernandoS27](https://github.com/FernandoS27)|Yes|
|[1703](https://github.com/yuzu-emu/yuzu/pull/1703)|[09d8109](https://github.com/yuzu-emu/yuzu/pull/1703/files/)|nvdrv: Stub nvdec/vic ioctls to bypass nvdec movies|[DarkLordZach](https://github.com/DarkLordZach)|Yes|
|[1340](https://github.com/yuzu-emu/yuzu/pull/1340)|[c359c00](https://github.com/yuzu-emu/yuzu/pull/1340/files/)|Implement a Better Ignore Assert|[FernandoS27](https://github.com/FernandoS27)|Yes|
|[1012](https://github.com/yuzu-emu/yuzu/pull/1012)|[7b98ac7](https://github.com/yuzu-emu/yuzu/pull/1012/files/)|filesystem: Create directory if it dosen't exist on open|[DarkLordZach](https://github.com/DarkLordZach)|Yes|


End of merge log. You can find the original README.md below the break.

------

yuzu emulator
=============
[![Travis CI Build Status](https://travis-ci.org/yuzu-emu/yuzu.svg?branch=master)](https://travis-ci.org/yuzu-emu/yuzu)
[![AppVeyor CI Build Status](https://ci.appveyor.com/api/projects/status/77k97svb2usreu68?svg=true)](https://ci.appveyor.com/project/bunnei/yuzu)
[![Azure Mainline CI Build Status](https://dev.azure.com/yuzu-emu/yuzu/_apis/build/status/yuzu%20mainline?branchName=master)](https://dev.azure.com/yuzu-emu/yuzu/)

yuzu is an experimental open-source emulator for the Nintendo Switch from the creators of [Citra](https://citra-emu.org/).

It is written in C++ with portability in mind, with builds actively maintained for Windows, Linux and macOS. The emulator is currently only useful for homebrew development and research purposes.

yuzu only emulates a subset of Switch hardware and therefore is generally only useful for running/debugging homebrew applications. yuzu can boot some games, to varying degrees of success.

yuzu is licensed under the GPLv2 (or any later version). Refer to the license.txt file included.

Check out our [website](https://yuzu-emu.org/)!

For development discussion, please join us on [Discord](https://discord.gg/XQV6dn9).

### Development

Most of the development happens on GitHub. It's also where [our central repository](https://github.com/yuzu-emu/yuzu) is hosted.

If you want to contribute please take a look at the [Contributor's Guide](CONTRIBUTING.md) and [Developer Information](https://github.com/yuzu-emu/yuzu/wiki/Developer-Information). You should as well contact any of the developers on Discord in order to know about the current state of the emulator.

### Building

* __Windows__: [Windows Build](https://github.com/yuzu-emu/yuzu/wiki/Building-For-Windows)
* __Linux__: [Linux Build](https://github.com/yuzu-emu/yuzu/wiki/Building-For-Linux)
* __macOS__: [macOS Build](https://github.com/yuzu-emu/yuzu/wiki/Building-for-macOS)


### Support
We happily accept monetary donations or donated games and hardware. Please see our [donations page](https://yuzu-emu.org/donate/) for more information on how you can contribute to yuzu. Any donations received will go towards things like:
* Switch consoles to explore and reverse-engineer the hardware
* Switch games for testing, reverse-engineering, and implementing new features
* Web hosting and infrastructure setup
* Software licenses (e.g. Visual Studio, IDA Pro, etc.)
* Additional hardware (e.g. GPUs as-needed to improve rendering support, other peripherals to add support for, etc.)

We also more than gladly accept used Switch consoles, preferably ones with firmware 3.0.0 or lower! If you would like to give yours away, don't hesitate to join our [Discord](https://discord.gg/VXqngT3) and talk to bunnei. You may also contact: donations@yuzu-emu.org.
