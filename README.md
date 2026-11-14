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
| [AppleWin](https://github.com/ToolAssisted-run/chimera-core-applewin) | AppleII | 2026-10-11 | <sub>[applewin-449dcc6b06076f13feacc0574f81f24273018a9d.chimeraCore](1.0.0Cores/applewin-449dcc6b06076f13feacc0574f81f24273018a9d.chimeraCore)</sub> |
| [ares](https://github.com/ToolAssisted-run/chimera-core-ares) | N64, N64DD, NES, GEN, SMS, GG, SG, A26, MYV, GB, GBC, WS, WSC, ZXS, GBA, CV, MSX, PS1, A52, NGP, NGPC, NG, SFC, 32X, MSX2, MCD, PCE, SGX, MCD32X, PCECD | 2026-10-22 | <sub>[ares-2ab01b5a8a71487453caa677d2b0137d2feddf94.chimeraCore](1.0.0Cores/ares-2ab01b5a8a71487453caa677d2b0137d2feddf94.chimeraCore)</sub> |
| [Azahar](https://github.com/ToolAssisted-run/chimera-core-azahar) | 3DS | 2026-10-24 | <sub>[azahar-a8ba29aedfc450e1d39466dcd74fdde74c882ef2.chimeraCore](1.0.0Cores/azahar-a8ba29aedfc450e1d39466dcd74fdde74c882ef2.chimeraCore)</sub> |
| [Cadmium](https://github.com/ToolAssisted-run/chimera-core-cadmium) | CHIP8 | 2026-10-13 | <sub>[cadmium-23000d99da8062e8b8ee05e1daaf4fe5889c488b.chimeraCore](1.0.0Cores/cadmium-23000d99da8062e8b8ee05e1daaf4fe5889c488b.chimeraCore)</sub> |
| [Dolphin](https://github.com/ToolAssisted-run/chimera-core-dolphin) | GC, Wii, Triforce | 2026-10-24 | <sub>[dolphin-1cb28ff26db34753b3efa1a35c1770f24cda6d71.chimeraCore](1.0.0Cores/dolphin-1cb28ff26db34753b3efa1a35c1770f24cda6d71.chimeraCore)</sub> |
| [DOSBox-X](https://github.com/ToolAssisted-run/chimera-core-dosbox-x) | DOS | 2026-10-22 | <sub>[dosbox-x-5ceb0851a603f6c9ca3f55727290ea56b4643db8.chimeraCore](1.0.0Cores/dosbox-x-5ceb0851a603f6c9ca3f55727290ea56b4643db8.chimeraCore)</sub> |
| [DSDA-Doom](https://github.com/ToolAssisted-run/chimera-core-dsda) | Doom | 2026-10-11 | <sub>[dsda-9a0fed48469f4322fa8c2ebd90e8ed7407b78687.chimeraCore](1.0.0Cores/dsda-9a0fed48469f4322fa8c2ebd90e8ed7407b78687.chimeraCore)</sub> |
| [DuckStation](https://github.com/ToolAssisted-run/chimera-core-duckstation) | PS1, NAMCOS11, KONAMIGQ | 2026-10-24 | <sub>[duckstation-d6921e542cec3d1f5102a57085f1fb55f28f1f51.chimeraCore](1.0.0Cores/duckstation-d6921e542cec3d1f5102a57085f1fb55f28f1f51.chimeraCore)</sub> |
| [EKA2L1](https://github.com/ToolAssisted-run/chimera-core-eka2l1) | SYMBIAN | 2026-10-20 | <sub>[eka2l1-b6e158f61a4f187941d05c94d3a74cf65b284e05.chimeraCore](1.0.0Cores/eka2l1-b6e158f61a4f187941d05c94d3a74cf65b284e05.chimeraCore)</sub> |
| [FBNeo](https://github.com/ToolAssisted-run/chimera-core-fbneo) | CPS1, CPS2, CPS3, NEOGEO, SYS16, NEOCD | 2026-10-22 | <sub>[fbneo-5d6c350cfd94652ef7f4870003bcbcb7017e6b45.chimeraCore](1.0.0Cores/fbneo-5d6c350cfd94652ef7f4870003bcbcb7017e6b45.chimeraCore)</sub> |
| [Flycast](https://github.com/ToolAssisted-run/chimera-core-flycast) | DC, NAOMI, NAOMI2, AW | 2026-10-24 | <sub>[flycast-9fba0493b230847af431bd195080201b216ad3d4.chimeraCore](1.0.0Cores/flycast-9fba0493b230847af431bd195080201b216ad3d4.chimeraCore)</sub> |
| [FreeJ2ME-Plus](https://github.com/ToolAssisted-run/chimera-core-freej2me) | J2ME | 2026-10-20 | <sub>[freej2me-80db8b0935cfe2a6a6c13657a1e1784d7ba26bdc.chimeraCore](1.0.0Cores/freej2me-80db8b0935cfe2a6a6c13657a1e1784d7ba26bdc.chimeraCore)</sub> |
| [Fuse](https://github.com/ToolAssisted-run/chimera-core-fuse) | ZXS | 2026-10-13 | <sub>[fuse-3e9981e5cbb1a3a6e5a8477d36cfa7ea82f6dcdd.chimeraCore](1.0.0Cores/fuse-3e9981e5cbb1a3a6e5a8477d36cfa7ea82f6dcdd.chimeraCore)</sub> |
| [Gambatte](https://github.com/ToolAssisted-run/chimera-core-gambatte) | GB, GBC, SGB, GBL | 2026-10-22 | <sub>[gambatte-fc6a0787aba96c77b3c345558b4ec993788ef825.chimeraCore](1.0.0Cores/gambatte-fc6a0787aba96c77b3c345558b4ec993788ef825.chimeraCore)</sub> |
| [Godot 4.4](https://github.com/ToolAssisted-run/chimera-core-godot44) | Godot | 2026-10-22 | <sub>[godot44-312de87697ca91f261ba9a795896cf8499cf1238.chimeraCore](1.0.0Cores/godot44-312de87697ca91f261ba9a795896cf8499cf1238.chimeraCore)</sub> |
| [Godot 4.5](https://github.com/ToolAssisted-run/chimera-core-godot45) | Godot | 2026-10-22 | <sub>[godot45-fb299788709b1179db346a74a8a855e60a80b42b.chimeraCore](1.0.0Cores/godot45-fb299788709b1179db346a74a8a855e60a80b42b.chimeraCore)</sub> |
| [Godot 4.6](https://github.com/ToolAssisted-run/chimera-core-godot46) | Godot | 2026-10-22 | <sub>[godot46-1cf008dc8fb9f83f8200a56b22ab7a2e30e33357.chimeraCore](1.0.0Cores/godot46-1cf008dc8fb9f83f8200a56b22ab7a2e30e33357.chimeraCore)</sub> |
| [Godot 4.7](https://github.com/ToolAssisted-run/chimera-core-godot47) | Godot | 2026-10-22 | <sub>[godot-8f2fa218b43498a2d580f122cf1e6e491dfc43e4.chimeraCore](1.0.0Cores/godot-8f2fa218b43498a2d580f122cf1e6e491dfc43e4.chimeraCore)</sub> |
| [Genesis Plus GX](https://github.com/ToolAssisted-run/chimera-core-gpgx) | GEN, SMS, GG, SG, PICO | 2026-10-22 | <sub>[gpgx-e1b55209d8abe7044379215957db03e52b2b42b4.chimeraCore](1.0.0Cores/gpgx-e1b55209d8abe7044379215957db03e52b2b42b4.chimeraCore)</sub> |
| [Ikemen GO](https://github.com/ToolAssisted-run/chimera-core-ikemen) | IkemenGO | 2026-10-22 | <sub>[ikemen-44f0e26f6cbf0b30ce238df8aca9d554938f5164.chimeraCore](1.0.0Cores/ikemen-44f0e26f6cbf0b30ce238df8aca9d554938f5164.chimeraCore)</sub> |
| [MAME](https://github.com/ToolAssisted-run/chimera-core-mame) | ARCADE | 2026-10-22 | <sub>[mame-8f0ccbced89029602bb96a18b5b63a816eeaffe7.chimeraCore](1.0.0Cores/mame-8f0ccbced89029602bb96a18b5b63a816eeaffe7.chimeraCore)</sub> |
| [MAME Home Systems](https://github.com/ToolAssisted-run/chimera-core-mamehome) | A78, INTV, VEC, O2, ChannelF, AmstradCPC, TI83, BBC | 2026-10-24 | <sub>[mamehome-a5597b480a16b1107d680d50efbd3c8f4e44bfcc.chimeraCore](1.0.0Cores/mamehome-a5597b480a16b1107d680d50efbd3c8f4e44bfcc.chimeraCore)</sub> |
| [Mednafen](https://github.com/ToolAssisted-run/chimera-core-mednafen) | SAT, VB, PCFX, LYNX, STV | 2026-10-22 | <sub>[mednafen-0a9526d2bf76515c49c074ceea821e7ea7301e89.chimeraCore](1.0.0Cores/mednafen-0a9526d2bf76515c49c074ceea821e7ea7301e89.chimeraCore)</sub> |
| [melonDS](https://github.com/ToolAssisted-run/chimera-core-melonds) | NDS, DSI | 2026-10-22 | <sub>[melonds-bdbf89cf4883c6d588523dd72cbbf640935413e4.chimeraCore](1.0.0Cores/melonds-bdbf89cf4883c6d588523dd72cbbf640935413e4.chimeraCore)</sub> |
| [Open4DBoxing](https://github.com/ToolAssisted-run/chimera-core-open4dboxing) | 4DSportsBoxing | 2026-10-25 | <sub>[open4dboxing-d0e69f6ee7d3ffe8939278922791c95165575b9b.chimeraCore](1.0.0Cores/open4dboxing-d0e69f6ee7d3ffe8939278922791c95165575b9b.chimeraCore)</sub> |
| [OpenBOR](https://github.com/ToolAssisted-run/chimera-core-openbor) | OpenBOR | 2026-10-22 | <sub>[openbor-45b2d535018494a2cdf7ec5e83b46a62ffc9550d.chimeraCore](1.0.0Cores/openbor-45b2d535018494a2cdf7ec5e83b46a62ffc9550d.chimeraCore)</sub> |
| [OpenSamurai](https://github.com/ToolAssisted-run/chimera-core-opensamurai) | SwordOfTheSamurai | 2026-10-22 | <sub>[opensamurai-4fc5442686e10e3fa63c00a8702bfaca32b74488.chimeraCore](1.0.0Cores/opensamurai-4fc5442686e10e3fa63c00a8702bfaca32b74488.chimeraCore)</sub> |
| [Opera](https://github.com/ToolAssisted-run/chimera-core-opera) | 3DO | 2026-10-22 | <sub>[opera-2dbe1a01756653e2280f124d1b20efdbe2184266.chimeraCore](1.0.0Cores/opera-2dbe1a01756653e2280f124d1b20efdbe2184266.chimeraCore)</sub> |
| [PCem](https://github.com/ToolAssisted-run/chimera-core-pcem) | PC | 2026-10-15 | <sub>[pcem-d888c407871a9cfb045953e8ed9f9ba33e8ed157.chimeraCore](1.0.0Cores/pcem-d888c407871a9cfb045953e8ed9f9ba33e8ed157.chimeraCore)</sub> |
| [PCSX2](https://github.com/ToolAssisted-run/chimera-core-pcsx2) | PS2, NAMCO246, NAMCO256, NAMCOSUPER256 | 2026-10-25 | <sub>[pcsx2-45e1ad01b0d6491cf299763f20b3d17ffff52731.chimeraCore](1.0.0Cores/pcsx2-45e1ad01b0d6491cf299763f20b3d17ffff52731.chimeraCore)</sub> |
| [PPSSPP](https://github.com/ToolAssisted-run/chimera-core-ppsspp) | PSP | 2026-10-22 | <sub>[ppsspp-386f14ca4ecfb33319c748e4d1530b574e9d925c.chimeraCore](1.0.0Cores/ppsspp-386f14ca4ecfb33319c748e4d1530b574e9d925c.chimeraCore)</sub> |
| [PUAE](https://github.com/ToolAssisted-run/chimera-core-puae) | AMIGA, CD32, CDTV | 2026-10-15 | <sub>[puae-89120b1e8c9c8c510d27242630031c9b37e61167.chimeraCore](1.0.0Cores/puae-89120b1e8c9c8c510d27242630031c9b37e61167.chimeraCore)</sub> |
| [quickerNES](https://github.com/ToolAssisted-run/chimera-core-quickernes) | NES | 2026-10-22 | <sub>[quickernes-abfaccdd3c9ff70213791f6417a54fea6af43f3f.chimeraCore](1.0.0Cores/quickernes-abfaccdd3c9ff70213791f6417a54fea6af43f3f.chimeraCore)</sub> |
| [QuickerNesHawk](https://github.com/ToolAssisted-run/chimera-core-neshawk) | NES | 2026-10-22 | <sub>[quickerneshawk-a6d99c646015b28305070f6afe0b20c0bd8f7b8d.chimeraCore](1.0.0Cores/quickerneshawk-a6d99c646015b28305070f6afe0b20c0bd8f7b8d.chimeraCore)</sub> |
| [rawgl](https://github.com/ToolAssisted-run/chimera-core-rawgl) | AnotherWorld | 2026-10-22 | <sub>[rawgl-a005bac32c3674041ba82c7517275e085f66d5ef.chimeraCore](1.0.0Cores/rawgl-a005bac32c3674041ba82c7517275e085f66d5ef.chimeraCore)</sub> |
| [RPCS3](https://github.com/ToolAssisted-run/chimera-core-rpcs3) | PS3 | 2026-10-25 | <sub>[rpcs3-a6fca7eedc700e51074d52e43ff26d7ea2ef5bf4.chimeraCore](1.0.0Cores/rpcs3-a6fca7eedc700e51074d52e43ff26d7ea2ef5bf4.chimeraCore)</sub> |
| [RSDKv3](https://github.com/ToolAssisted-run/chimera-core-rsdkv3) | SonicCD | 2026-10-22 | <sub>[rsdkv3-2d1ba8ca6ea776d8e004624b6790519864dd536d.chimeraCore](1.0.0Cores/rsdkv3-2d1ba8ca6ea776d8e004624b6790519864dd536d.chimeraCore)</sub> |
| [RSDKv4](https://github.com/ToolAssisted-run/chimera-core-rsdkv4) | Sonic1, Sonic2 | 2026-10-22 | <sub>[rsdkv4-f46f84d0d8f935fa53d8299e69a8d2a2cebc82d9.chimeraCore](1.0.0Cores/rsdkv4-f46f84d0d8f935fa53d8299e69a8d2a2cebc82d9.chimeraCore)</sub> |
| [RSDKv5](https://github.com/ToolAssisted-run/chimera-core-rsdkv5) | SonicMania | 2026-10-22 | <sub>[rsdkv5-3848e7c7bd0bcc3824381bc21598789fb5c71ed5.chimeraCore](1.0.0Cores/rsdkv5-3848e7c7bd0bcc3824381bc21598789fb5c71ed5.chimeraCore)</sub> |
| [Ruffle](https://github.com/ToolAssisted-run/chimera-core-ruffle) | Flash | 2026-10-24 | <sub>[ruffle-aa50bf87f24da42176c00e6a1deadc3c1ab925b3.chimeraCore](1.0.0Cores/ruffle-aa50bf87f24da42176c00e6a1deadc3c1ab925b3.chimeraCore)</sub> |
| [SDLPoP](https://github.com/ToolAssisted-run/chimera-core-sdlpop) | PrinceOfPersia | 2026-10-22 | <sub>[sdlpop-c9e1e62f16a9040ec02ef03246dc51be7df0efa9.chimeraCore](1.0.0Cores/sdlpop-c9e1e62f16a9040ec02ef03246dc51be7df0efa9.chimeraCore)</sub> |
| [SDLPoP2](https://github.com/ToolAssisted-run/chimera-core-sdlpop2) | PrinceOfPersia2 | 2026-10-22 | <sub>[sdlpop2-fbd1a5c94c9eb636eb98a4a80f4ad7fa2e5e6c24.chimeraCore](1.0.0Cores/sdlpop2-fbd1a5c94c9eb636eb98a4a80f4ad7fa2e5e6c24.chimeraCore)</sub> |
| [Snes9x](https://github.com/ToolAssisted-run/chimera-core-snes9x) | SNES | 2026-10-22 | <sub>[snes9x-79e0f35a9214c0009cfdf9241f96730c53322d81.chimeraCore](1.0.0Cores/snes9x-79e0f35a9214c0009cfdf9241f96730c53322d81.chimeraCore)</sub> |
| [Stella](https://github.com/ToolAssisted-run/chimera-core-stella) | A26 | 2026-10-22 | <sub>[stella-3c47bccbf9f481d1b1d34de22bc3c5ab267fc2d0.chimeraCore](1.0.0Cores/stella-3c47bccbf9f481d1b1d34de22bc3c5ab267fc2d0.chimeraCore)</sub> |
| [SyndicatFX](https://github.com/ToolAssisted-run/chimera-core-syndicatfx) | Syndicate | 2026-10-11 | <sub>[syndicatfx-d77a1dc595840596671f49d15cdfd1b7892eb0ba.chimeraCore](1.0.0Cores/syndicatfx-d77a1dc595840596671f49d15cdfd1b7892eb0ba.chimeraCore)</sub> |
| [TIC-80](https://github.com/ToolAssisted-run/chimera-core-tic80) | TIC80 | 2026-10-22 | <sub>[tic80-8a650b63bb63a9dd44f025171cc71ee0cd765f28.chimeraCore](1.0.0Cores/tic80-8a650b63bb63a9dd44f025171cc71ee0cd765f28.chimeraCore)</sub> |
| [touchHLE](https://github.com/ToolAssisted-run/chimera-core-touchhle) | iOS | 2026-10-11 | <sub>[touchhle-52b4984695c8e6367fc4c47d46ac5df67848daf5.chimeraCore](1.0.0Cores/touchhle-52b4984695c8e6367fc4c47d46ac5df67848daf5.chimeraCore)</sub> |
| [Uzem](https://github.com/ToolAssisted-run/chimera-core-uzem) | UZE | 2026-10-22 | <sub>[uzem-94f0c84999e4b6344f9a925fbae80771bfd2ecfb.chimeraCore](1.0.0Cores/uzem-94f0c84999e4b6344f9a925fbae80771bfd2ecfb.chimeraCore)</sub> |
| [VICE](https://github.com/ToolAssisted-run/chimera-core-vice) | C64 | 2026-10-22 | <sub>[vice-b2865403b2469a7ead969286a9dd1cb74c4581ad.chimeraCore](1.0.0Cores/vice-b2865403b2469a7ead969286a9dd1cb74c4581ad.chimeraCore)</sub> |
| [Virtual Jaguar](https://github.com/ToolAssisted-run/chimera-core-virtualjaguar) | JAG, JAGCD | 2026-10-22 | <sub>[virtualjaguar-a8e4e48bacb28a3cc5b181354e2be777672d7e72.chimeraCore](1.0.0Cores/virtualjaguar-a8e4e48bacb28a3cc5b181354e2be777672d7e72.chimeraCore)</sub> |
| [Vita3K](https://github.com/ToolAssisted-run/chimera-core-vita3k) | PSV | 2026-10-24 | <sub>[vita3k-8e3051686a29452d25626528e9050117970a6b73.chimeraCore](1.0.0Cores/vita3k-8e3051686a29452d25626528e9050117970a6b73.chimeraCore)</sub> |
| [MAME X68000](https://github.com/ToolAssisted-run/chimera-core-x68k) | X68000 | 2026-10-24 | <sub>[x68k-d2b1f731f7c666d5019c86839da374551fe9d119.chimeraCore](1.0.0Cores/x68k-d2b1f731f7c666d5019c86839da374551fe9d119.chimeraCore)</sub> |
| [xemu](https://github.com/ToolAssisted-run/chimera-core-xemu) | XBOX | 2026-10-24 | <sub>[xemu-77cb1dde1121a03fe5ebf17f0dae8c18ae208e34.chimeraCore](1.0.0Cores/xemu-77cb1dde1121a03fe5ebf17f0dae8c18ae208e34.chimeraCore)</sub> |
| [Xenia](https://github.com/ToolAssisted-run/chimera-core-xenia) | X360 | 2026-10-22 | <sub>[xenia-eb4282e3e4d700443bfaa284c1a7954eb265bc3b.chimeraCore](1.0.0Cores/xenia-eb4282e3e4d700443bfaa284c1a7954eb265bc3b.chimeraCore)</sub> |
| [Zeebx](https://github.com/ToolAssisted-run/chimera-core-zeebx) | ZEEBO | 2026-10-22 | <sub>[zeebx-eaace3e2b60f9220a432a85a07aa1635f3d3cba8.chimeraCore](1.0.0Cores/zeebx-eaace3e2b60f9220a432a85a07aa1635f3d3cba8.chimeraCore)</sub> |

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

## Checked

Every file's SHA-256 equals the digest GitHub recorded for its release asset.
All 55 packages were opened by chimera-csx's `InstalledCorePackagesTests`, and
the set passes `MnemonicUniquenessTests` (26 tests in all, 2026-11-14).

## Licenses

Each core is its own project under its own license and copyright. Every
package carries its licenses inside, under `licenses/` in the zip, including
the license of the emulator it builds and of the Chimera integration. This
repository only stores those published packages as they are.
