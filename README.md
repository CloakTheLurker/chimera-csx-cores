# Chimera CSX 1.0.0 cores

The core packages for Chimera CSX 1.0.0: for each official Chimera core, the
newest nightly it had published on or before 2026-10-27.

These are the `.chimeraCore` files the cores' own repositories published,
unmodified. Nothing here is rebuilt, renamed or repacked, so a file's SHA-256
is the digest GitHub recorded for that release asset.

## Using them

Copy the `.chimeraCore` files from `1.0.0Cores` into Chimera CSX's `Cores`
folder, beside the executable. **File > Core Manager** shows where that folder
is and lists what it found.

Any number of builds can sit side by side: a project runs the build it pins
when that build is in the folder, and otherwise the one last opened with
**File > Open Core**, failing that the newest.

All 55 packages were built by the cores' own CI on x86_64 runners. A release
of that time did not name a CPU, so no file name carries one; these packages
are for x86_64 Windows, Linux and Intel Macs.

## What is here

55 packages, 795 MiB together. The nightly named is the one published on that
date; the commit inside each package is the version it stamps.

| Core | Systems | Nightly | Package |
|---|---|---|---|
| [AppleWin](https://github.com/ToolAssisted-run/chimera-core-applewin) | AppleII | nightly-2026-10-11 | [applewin-449dcc6b06076f13feacc0574f81f24273018a9d.chimeraCore](1.0.0Cores/applewin-449dcc6b06076f13feacc0574f81f24273018a9d.chimeraCore) |
| [ares](https://github.com/ToolAssisted-run/chimera-core-ares) | N64, N64DD, NES, GEN, SMS, GG, SG, A26, MYV, GB, GBC, WS, WSC, ZXS, GBA, CV, MSX, PS1, A52, NGP, NGPC, NG, SFC, 32X, MSX2, MCD, PCE, SGX, MCD32X, PCECD | nightly-2026-10-22 | [ares-2ab01b5a8a71487453caa677d2b0137d2feddf94.chimeraCore](1.0.0Cores/ares-2ab01b5a8a71487453caa677d2b0137d2feddf94.chimeraCore) |
| [Azahar](https://github.com/ToolAssisted-run/chimera-core-azahar) | 3DS | nightly-2026-10-24 | [azahar-a8ba29aedfc450e1d39466dcd74fdde74c882ef2.chimeraCore](1.0.0Cores/azahar-a8ba29aedfc450e1d39466dcd74fdde74c882ef2.chimeraCore) |
| [Cadmium](https://github.com/ToolAssisted-run/chimera-core-cadmium) | CHIP8 | nightly-2026-10-13 | [cadmium-23000d99da8062e8b8ee05e1daaf4fe5889c488b.chimeraCore](1.0.0Cores/cadmium-23000d99da8062e8b8ee05e1daaf4fe5889c488b.chimeraCore) |
| [Dolphin](https://github.com/ToolAssisted-run/chimera-core-dolphin) | GC, Wii, Triforce | nightly-2026-10-24 | [dolphin-1cb28ff26db34753b3efa1a35c1770f24cda6d71.chimeraCore](1.0.0Cores/dolphin-1cb28ff26db34753b3efa1a35c1770f24cda6d71.chimeraCore) |
| [DOSBox-X](https://github.com/ToolAssisted-run/chimera-core-dosbox-x) | DOS | nightly-2026-10-22 | [dosbox-x-5ceb0851a603f6c9ca3f55727290ea56b4643db8.chimeraCore](1.0.0Cores/dosbox-x-5ceb0851a603f6c9ca3f55727290ea56b4643db8.chimeraCore) |
| [DSDA-Doom](https://github.com/ToolAssisted-run/chimera-core-dsda) | Doom | nightly-2026-10-11 | [dsda-9a0fed48469f4322fa8c2ebd90e8ed7407b78687.chimeraCore](1.0.0Cores/dsda-9a0fed48469f4322fa8c2ebd90e8ed7407b78687.chimeraCore) |
| [DuckStation](https://github.com/ToolAssisted-run/chimera-core-duckstation) | PS1, NAMCOS11, KONAMIGQ | nightly-2026-10-24 | [duckstation-d6921e542cec3d1f5102a57085f1fb55f28f1f51.chimeraCore](1.0.0Cores/duckstation-d6921e542cec3d1f5102a57085f1fb55f28f1f51.chimeraCore) |
| [EKA2L1](https://github.com/ToolAssisted-run/chimera-core-eka2l1) | SYMBIAN | nightly-2026-10-20 | [eka2l1-b6e158f61a4f187941d05c94d3a74cf65b284e05.chimeraCore](1.0.0Cores/eka2l1-b6e158f61a4f187941d05c94d3a74cf65b284e05.chimeraCore) |
| [FBNeo](https://github.com/ToolAssisted-run/chimera-core-fbneo) | CPS1, CPS2, CPS3, NEOGEO, SYS16, NEOCD | nightly-2026-10-22 | [fbneo-5d6c350cfd94652ef7f4870003bcbcb7017e6b45.chimeraCore](1.0.0Cores/fbneo-5d6c350cfd94652ef7f4870003bcbcb7017e6b45.chimeraCore) |
| [Flycast](https://github.com/ToolAssisted-run/chimera-core-flycast) | DC, NAOMI, NAOMI2, AW | nightly-2026-10-24 | [flycast-9fba0493b230847af431bd195080201b216ad3d4.chimeraCore](1.0.0Cores/flycast-9fba0493b230847af431bd195080201b216ad3d4.chimeraCore) |
| [FreeJ2ME-Plus](https://github.com/ToolAssisted-run/chimera-core-freej2me) | J2ME | nightly-2026-10-20 | [freej2me-80db8b0935cfe2a6a6c13657a1e1784d7ba26bdc.chimeraCore](1.0.0Cores/freej2me-80db8b0935cfe2a6a6c13657a1e1784d7ba26bdc.chimeraCore) |
| [Fuse](https://github.com/ToolAssisted-run/chimera-core-fuse) | ZXS | nightly-2026-10-13 | [fuse-3e9981e5cbb1a3a6e5a8477d36cfa7ea82f6dcdd.chimeraCore](1.0.0Cores/fuse-3e9981e5cbb1a3a6e5a8477d36cfa7ea82f6dcdd.chimeraCore) |
| [Gambatte](https://github.com/ToolAssisted-run/chimera-core-gambatte) | GB, GBC, SGB, GBL | nightly-2026-10-22 | [gambatte-fc6a0787aba96c77b3c345558b4ec993788ef825.chimeraCore](1.0.0Cores/gambatte-fc6a0787aba96c77b3c345558b4ec993788ef825.chimeraCore) |
| [Godot 4.4](https://github.com/ToolAssisted-run/chimera-core-godot44) | Godot | nightly-2026-10-22 | [godot44-312de87697ca91f261ba9a795896cf8499cf1238.chimeraCore](1.0.0Cores/godot44-312de87697ca91f261ba9a795896cf8499cf1238.chimeraCore) |
| [Godot 4.5](https://github.com/ToolAssisted-run/chimera-core-godot45) | Godot | nightly-2026-10-22 | [godot45-fb299788709b1179db346a74a8a855e60a80b42b.chimeraCore](1.0.0Cores/godot45-fb299788709b1179db346a74a8a855e60a80b42b.chimeraCore) |
| [Godot 4.6](https://github.com/ToolAssisted-run/chimera-core-godot46) | Godot | nightly-2026-10-22 | [godot46-1cf008dc8fb9f83f8200a56b22ab7a2e30e33357.chimeraCore](1.0.0Cores/godot46-1cf008dc8fb9f83f8200a56b22ab7a2e30e33357.chimeraCore) |
| [Godot 4.7](https://github.com/ToolAssisted-run/chimera-core-godot47) | Godot | nightly-2026-10-22 | [godot-8f2fa218b43498a2d580f122cf1e6e491dfc43e4.chimeraCore](1.0.0Cores/godot-8f2fa218b43498a2d580f122cf1e6e491dfc43e4.chimeraCore) |
| [Genesis Plus GX](https://github.com/ToolAssisted-run/chimera-core-gpgx) | GEN, SMS, GG, SG, PICO | nightly-2026-10-22 | [gpgx-e1b55209d8abe7044379215957db03e52b2b42b4.chimeraCore](1.0.0Cores/gpgx-e1b55209d8abe7044379215957db03e52b2b42b4.chimeraCore) |
| [Ikemen GO](https://github.com/ToolAssisted-run/chimera-core-ikemen) | IkemenGO | nightly-2026-10-22 | [ikemen-44f0e26f6cbf0b30ce238df8aca9d554938f5164.chimeraCore](1.0.0Cores/ikemen-44f0e26f6cbf0b30ce238df8aca9d554938f5164.chimeraCore) |
| [MAME](https://github.com/ToolAssisted-run/chimera-core-mame) | ARCADE | nightly-2026-10-22 | [mame-8f0ccbced89029602bb96a18b5b63a816eeaffe7.chimeraCore](1.0.0Cores/mame-8f0ccbced89029602bb96a18b5b63a816eeaffe7.chimeraCore) |
| [MAME Home Systems](https://github.com/ToolAssisted-run/chimera-core-mamehome) | A78, INTV, VEC, O2, ChannelF, AmstradCPC, TI83, BBC | nightly-2026-10-24 | [mamehome-a5597b480a16b1107d680d50efbd3c8f4e44bfcc.chimeraCore](1.0.0Cores/mamehome-a5597b480a16b1107d680d50efbd3c8f4e44bfcc.chimeraCore) |
| [Mednafen](https://github.com/ToolAssisted-run/chimera-core-mednafen) | SAT, VB, PCFX, LYNX, STV | nightly-2026-10-22 | [mednafen-0a9526d2bf76515c49c074ceea821e7ea7301e89.chimeraCore](1.0.0Cores/mednafen-0a9526d2bf76515c49c074ceea821e7ea7301e89.chimeraCore) |
| [melonDS](https://github.com/ToolAssisted-run/chimera-core-melonds) | NDS, DSI | nightly-2026-10-22 | [melonds-bdbf89cf4883c6d588523dd72cbbf640935413e4.chimeraCore](1.0.0Cores/melonds-bdbf89cf4883c6d588523dd72cbbf640935413e4.chimeraCore) |
| [Open4DBoxing](https://github.com/ToolAssisted-run/chimera-core-open4dboxing) | 4DSportsBoxing | nightly-2026-10-25 | [open4dboxing-d0e69f6ee7d3ffe8939278922791c95165575b9b.chimeraCore](1.0.0Cores/open4dboxing-d0e69f6ee7d3ffe8939278922791c95165575b9b.chimeraCore) |
| [OpenBOR](https://github.com/ToolAssisted-run/chimera-core-openbor) | OpenBOR | nightly-2026-10-22 | [openbor-45b2d535018494a2cdf7ec5e83b46a62ffc9550d.chimeraCore](1.0.0Cores/openbor-45b2d535018494a2cdf7ec5e83b46a62ffc9550d.chimeraCore) |
| [OpenSamurai](https://github.com/ToolAssisted-run/chimera-core-opensamurai) | SwordOfTheSamurai | nightly-2026-10-22 | [opensamurai-4fc5442686e10e3fa63c00a8702bfaca32b74488.chimeraCore](1.0.0Cores/opensamurai-4fc5442686e10e3fa63c00a8702bfaca32b74488.chimeraCore) |
| [Opera](https://github.com/ToolAssisted-run/chimera-core-opera) | 3DO | nightly-2026-10-22 | [opera-2dbe1a01756653e2280f124d1b20efdbe2184266.chimeraCore](1.0.0Cores/opera-2dbe1a01756653e2280f124d1b20efdbe2184266.chimeraCore) |
| [PCem](https://github.com/ToolAssisted-run/chimera-core-pcem) | PC | nightly-2026-10-15 | [pcem-d888c407871a9cfb045953e8ed9f9ba33e8ed157.chimeraCore](1.0.0Cores/pcem-d888c407871a9cfb045953e8ed9f9ba33e8ed157.chimeraCore) |
| [PCSX2](https://github.com/ToolAssisted-run/chimera-core-pcsx2) | PS2, NAMCO246, NAMCO256, NAMCOSUPER256 | nightly-2026-10-25 | [pcsx2-45e1ad01b0d6491cf299763f20b3d17ffff52731.chimeraCore](1.0.0Cores/pcsx2-45e1ad01b0d6491cf299763f20b3d17ffff52731.chimeraCore) |
| [PPSSPP](https://github.com/ToolAssisted-run/chimera-core-ppsspp) | PSP | nightly-2026-10-22 | [ppsspp-386f14ca4ecfb33319c748e4d1530b574e9d925c.chimeraCore](1.0.0Cores/ppsspp-386f14ca4ecfb33319c748e4d1530b574e9d925c.chimeraCore) |
| [PUAE](https://github.com/ToolAssisted-run/chimera-core-puae) | AMIGA, CD32, CDTV | nightly-2026-10-15 | [puae-89120b1e8c9c8c510d27242630031c9b37e61167.chimeraCore](1.0.0Cores/puae-89120b1e8c9c8c510d27242630031c9b37e61167.chimeraCore) |
| [quickerNES](https://github.com/ToolAssisted-run/chimera-core-quickernes) | NES | nightly-2026-10-22 | [quickernes-abfaccdd3c9ff70213791f6417a54fea6af43f3f.chimeraCore](1.0.0Cores/quickernes-abfaccdd3c9ff70213791f6417a54fea6af43f3f.chimeraCore) |
| [QuickerNesHawk](https://github.com/ToolAssisted-run/chimera-core-neshawk) | NES | nightly-2026-10-22 | [quickerneshawk-a6d99c646015b28305070f6afe0b20c0bd8f7b8d.chimeraCore](1.0.0Cores/quickerneshawk-a6d99c646015b28305070f6afe0b20c0bd8f7b8d.chimeraCore) |
| [rawgl](https://github.com/ToolAssisted-run/chimera-core-rawgl) | AnotherWorld | nightly-2026-10-22 | [rawgl-a005bac32c3674041ba82c7517275e085f66d5ef.chimeraCore](1.0.0Cores/rawgl-a005bac32c3674041ba82c7517275e085f66d5ef.chimeraCore) |
| [RPCS3](https://github.com/ToolAssisted-run/chimera-core-rpcs3) | PS3 | nightly-2026-10-25 | [rpcs3-a6fca7eedc700e51074d52e43ff26d7ea2ef5bf4.chimeraCore](1.0.0Cores/rpcs3-a6fca7eedc700e51074d52e43ff26d7ea2ef5bf4.chimeraCore) |
| [RSDKv3](https://github.com/ToolAssisted-run/chimera-core-rsdkv3) | SonicCD | nightly-2026-10-22 | [rsdkv3-2d1ba8ca6ea776d8e004624b6790519864dd536d.chimeraCore](1.0.0Cores/rsdkv3-2d1ba8ca6ea776d8e004624b6790519864dd536d.chimeraCore) |
| [RSDKv4](https://github.com/ToolAssisted-run/chimera-core-rsdkv4) | Sonic1, Sonic2 | nightly-2026-10-22 | [rsdkv4-f46f84d0d8f935fa53d8299e69a8d2a2cebc82d9.chimeraCore](1.0.0Cores/rsdkv4-f46f84d0d8f935fa53d8299e69a8d2a2cebc82d9.chimeraCore) |
| [RSDKv5](https://github.com/ToolAssisted-run/chimera-core-rsdkv5) | SonicMania | nightly-2026-10-22 | [rsdkv5-3848e7c7bd0bcc3824381bc21598789fb5c71ed5.chimeraCore](1.0.0Cores/rsdkv5-3848e7c7bd0bcc3824381bc21598789fb5c71ed5.chimeraCore) |
| [Ruffle](https://github.com/ToolAssisted-run/chimera-core-ruffle) | Flash | nightly-2026-10-24 | [ruffle-aa50bf87f24da42176c00e6a1deadc3c1ab925b3.chimeraCore](1.0.0Cores/ruffle-aa50bf87f24da42176c00e6a1deadc3c1ab925b3.chimeraCore) |
| [SDLPoP](https://github.com/ToolAssisted-run/chimera-core-sdlpop) | PrinceOfPersia | nightly-2026-10-22 | [sdlpop-c9e1e62f16a9040ec02ef03246dc51be7df0efa9.chimeraCore](1.0.0Cores/sdlpop-c9e1e62f16a9040ec02ef03246dc51be7df0efa9.chimeraCore) |
| [SDLPoP2](https://github.com/ToolAssisted-run/chimera-core-sdlpop2) | PrinceOfPersia2 | nightly-2026-10-22 | [sdlpop2-fbd1a5c94c9eb636eb98a4a80f4ad7fa2e5e6c24.chimeraCore](1.0.0Cores/sdlpop2-fbd1a5c94c9eb636eb98a4a80f4ad7fa2e5e6c24.chimeraCore) |
| [Snes9x](https://github.com/ToolAssisted-run/chimera-core-snes9x) | SNES | nightly-2026-10-22 | [snes9x-79e0f35a9214c0009cfdf9241f96730c53322d81.chimeraCore](1.0.0Cores/snes9x-79e0f35a9214c0009cfdf9241f96730c53322d81.chimeraCore) |
| [Stella](https://github.com/ToolAssisted-run/chimera-core-stella) | A26 | nightly-2026-10-22 | [stella-3c47bccbf9f481d1b1d34de22bc3c5ab267fc2d0.chimeraCore](1.0.0Cores/stella-3c47bccbf9f481d1b1d34de22bc3c5ab267fc2d0.chimeraCore) |
| [SyndicatFX](https://github.com/ToolAssisted-run/chimera-core-syndicatfx) | Syndicate | nightly-2026-10-11 | [syndicatfx-d77a1dc595840596671f49d15cdfd1b7892eb0ba.chimeraCore](1.0.0Cores/syndicatfx-d77a1dc595840596671f49d15cdfd1b7892eb0ba.chimeraCore) |
| [TIC-80](https://github.com/ToolAssisted-run/chimera-core-tic80) | TIC80 | nightly-2026-10-22 | [tic80-8a650b63bb63a9dd44f025171cc71ee0cd765f28.chimeraCore](1.0.0Cores/tic80-8a650b63bb63a9dd44f025171cc71ee0cd765f28.chimeraCore) |
| [touchHLE](https://github.com/ToolAssisted-run/chimera-core-touchhle) | iOS | nightly-2026-10-11 | [touchhle-52b4984695c8e6367fc4c47d46ac5df67848daf5.chimeraCore](1.0.0Cores/touchhle-52b4984695c8e6367fc4c47d46ac5df67848daf5.chimeraCore) |
| [Uzem](https://github.com/ToolAssisted-run/chimera-core-uzem) | UZE | nightly-2026-10-22 | [uzem-94f0c84999e4b6344f9a925fbae80771bfd2ecfb.chimeraCore](1.0.0Cores/uzem-94f0c84999e4b6344f9a925fbae80771bfd2ecfb.chimeraCore) |
| [VICE](https://github.com/ToolAssisted-run/chimera-core-vice) | C64 | nightly-2026-10-22 | [vice-b2865403b2469a7ead969286a9dd1cb74c4581ad.chimeraCore](1.0.0Cores/vice-b2865403b2469a7ead969286a9dd1cb74c4581ad.chimeraCore) |
| [Virtual Jaguar](https://github.com/ToolAssisted-run/chimera-core-virtualjaguar) | JAG, JAGCD | nightly-2026-10-22 | [virtualjaguar-a8e4e48bacb28a3cc5b181354e2be777672d7e72.chimeraCore](1.0.0Cores/virtualjaguar-a8e4e48bacb28a3cc5b181354e2be777672d7e72.chimeraCore) |
| [Vita3K](https://github.com/ToolAssisted-run/chimera-core-vita3k) | PSV | nightly-2026-10-24 | [vita3k-8e3051686a29452d25626528e9050117970a6b73.chimeraCore](1.0.0Cores/vita3k-8e3051686a29452d25626528e9050117970a6b73.chimeraCore) |
| [MAME X68000](https://github.com/ToolAssisted-run/chimera-core-x68k) | X68000 | nightly-2026-10-24 | [x68k-d2b1f731f7c666d5019c86839da374551fe9d119.chimeraCore](1.0.0Cores/x68k-d2b1f731f7c666d5019c86839da374551fe9d119.chimeraCore) |
| [xemu](https://github.com/ToolAssisted-run/chimera-core-xemu) | XBOX | nightly-2026-10-24 | [xemu-77cb1dde1121a03fe5ebf17f0dae8c18ae208e34.chimeraCore](1.0.0Cores/xemu-77cb1dde1121a03fe5ebf17f0dae8c18ae208e34.chimeraCore) |
| [Xenia](https://github.com/ToolAssisted-run/chimera-core-xenia) | X360 | nightly-2026-10-22 | [xenia-eb4282e3e4d700443bfaa284c1a7954eb265bc3b.chimeraCore](1.0.0Cores/xenia-eb4282e3e4d700443bfaa284c1a7954eb265bc3b.chimeraCore) |
| [Zeebx](https://github.com/ToolAssisted-run/chimera-core-zeebx) | ZEEBO | nightly-2026-10-22 | [zeebx-eaace3e2b60f9220a432a85a07aa1635f3d3cba8.chimeraCore](1.0.0Cores/zeebx-eaace3e2b60f9220a432a85a07aa1635f3d3cba8.chimeraCore) |

The table uses the roster's names. The name a package itself carries is
`packageName` in [cores.json](cores.json); the Godot 4.7 package, for one,
says just Godot.

## What is not here

Seven cores in Chimera's roster had published no nightly by 2026-10-27 and so
have no package here:

[mesen](https://github.com/ToolAssisted-run/chimera-core-mesen), [cemu](https://github.com/ToolAssisted-run/chimera-core-cemu), [86box](https://github.com/ToolAssisted-run/chimera-core-86box), [zesarux](https://github.com/ToolAssisted-run/chimera-core-zesarux), [rsdkv5u](https://github.com/ToolAssisted-run/chimera-core-rsdkv5u), [scummvm](https://github.com/ToolAssisted-run/chimera-core-scummvm), [supermodel](https://github.com/ToolAssisted-run/chimera-core-supermodel)

Cores published after that date are not part of this set.

## Index

[cores.json](cores.json) lists every package with its repository, nightly,
commit, commit date, size and SHA-256, and the release page it came from.

## Licenses

Each core is its own project under its own license and copyright. Every
package carries its licenses inside, under `licenses/` in the zip, including
the license of the emulator it builds and of the Chimera integration. This
repository only stores those published packages as they are.
