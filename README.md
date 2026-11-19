# Chimera CSX cores

The core packages for Chimera CSX, one folder per release:

* `1.0.0Cores` - the newest nightly each official core had published on or
  before 2026-10-27, when Chimera CSX 1.0.0 was cut: 55 packages.
* `1.2.0Cores` - the latest nightly each core had on 2026-11-14, less the one
  Chimera CSX 1.2.0 refuses: 62 packages.
* `1.4.0Cores` - the 1.2.0 set plus Mesen, whose single file is in
  `1.4.0Cores`: 63 packages, the 60 unchanged files read from `1.2.0Cores`.
* `1.4.1Cores` - the 1.4.0 set plus the nine cores added on 2026-11-15 and 16:
  72 packages, the nine new files in `1.4.1Cores` and the rest read from the
  earlier folders.
* `1.4.4Cores` - the 1.4.1 set plus fheroes2 and TheXTech, the two game cores
  added on 2026-11-19: 74 packages, the two new files in `1.4.4Cores` and the
  rest read from the earlier folders. It is for the next release, 1.4.4, whose
  roster names the two cores.

Every folder here holds the `.chimeraCore` files the cores' own repositories
published, unmodified. Nothing here is rebuilt, renamed or repacked, so a
file's SHA-256 is the digest GitHub recorded for that release asset.

## Using them

Copy the `.chimeraCore` files from the folder for your Chimera CSX version
into its `Cores` folder, beside the executable. **File > Core Manager** shows
where that folder is and lists what it found.

Use `1.0.0Cores` with Chimera CSX 1.0.0 and 1.1.0, `1.2.0Cores` with 1.2.0
and 1.3.x, `1.4.0Cores` with 1.4.0, `1.4.1Cores` with 1.4.1 to 1.4.3, and
`1.4.4Cores` with 1.4.4 and later. 1.4.4 is the first release whose roster
names fheroes2 and TheXTech; 1.4.3 opens both packages as it opens any other.
The newer packages name their settings by key and carry the words in
`languages/en.json`; 1.2.0 reads them, and an older build would show the keys
themselves. Mesen's package writes its labels as an array, which 1.4.0 reads and
1.2.0 refuses, so use Mesen with 1.4.0 or newer.

Any number of builds can sit side by side: a project runs the build it pins
when that build is in the folder, and otherwise the one last opened with
**File > Open Core**, failing that the newest.

Every package here is for x86_64, which is what Chimera CSX runs: the 1.0.0 set
was published before a file name named a CPU, and of the 1.2.0 set only the
x86_64 package is kept.

## 1.0.0Cores

55 packages, 795 MiB together. The nightly named is the one published on that
date; the commit inside each package is the version it stamps. Its index is
[cores.json](cores.json).

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

## 1.2.0Cores

62 packages, 1075 MiB together. Every core's latest nightly on 2026-11-14 except
Mesen: Chimera CSX 1.2.0 refuses its package because it declares
`settings[].optionLabels` as an array, where the frontend reads a map from
value to label. The core itself runs in Chimera's Qt window, without those
labels. The file is named in [cores-1.2.0.json](cores-1.2.0.json) so it can be
added when a frontend reads it.

60 packages are in the folder. The other 2 - Cemu and ScummVM - are
each above GitHub's 100 MB limit for a repository file, so they are attached to
[the 1.2.0Cores-oversize release](https://github.com/CloakTheLurker/chimera-csx-cores/releases/tag/1.2.0Cores-oversize);
the links in the table below download them, and they belong in `Cores` beside
the rest.

bsnes v115 is here although Chimera's roster does not list it: upstream added
the core after the cut, and Chimera CSX opens it like any other package.

| Core | Systems | Nightly | Package |
|---|---|---|---|
| [86Box](https://github.com/ToolAssisted-run/chimera-core-86box) | PC | 2026-11-08 | <sub>[86box-0266464125b3315c4168d13f30c2f20981a8dc4b-x86_64.chimeraCore](1.2.0Cores/86box-0266464125b3315c4168d13f30c2f20981a8dc4b-x86_64.chimeraCore)</sub> |
| [AppleWin](https://github.com/ToolAssisted-run/chimera-core-applewin) | AppleII | 2026-11-07 | <sub>[applewin-89c936a996eca7422aaf73c8d994db8414e74d43-x86_64.chimeraCore](1.2.0Cores/applewin-89c936a996eca7422aaf73c8d994db8414e74d43-x86_64.chimeraCore)</sub> |
| [ares](https://github.com/ToolAssisted-run/chimera-core-ares) | N64, N64DD, NES, GEN, SMS, GG, SG, A26, MYV, GB, GBC, WS, WSC, ZXS, GBA, CV, MSX, PS1, A52, NGP, NGPC, NG, SFC, 32X, MSX2, MCD, PCE, SGX, MCD32X, PCECD | 2026-11-13 | <sub>[ares-544a670db182394cd8a22ab574c90c4d6ff1559a-x86_64.chimeraCore](1.2.0Cores/ares-544a670db182394cd8a22ab574c90c4d6ff1559a-x86_64.chimeraCore)</sub> |
| [Azahar](https://github.com/ToolAssisted-run/chimera-core-azahar) | 3DS | 2026-11-13 | <sub>[azahar-a3ac8efb14ce9f16402ab1538c31c055225c15bd-x86_64.chimeraCore](1.2.0Cores/azahar-a3ac8efb14ce9f16402ab1538c31c055225c15bd-x86_64.chimeraCore)</sub> |
| [bsnes v115](https://github.com/ToolAssisted-run/chimera-core-bsnes115) | SNES | 2026-11-12 | <sub>[bsnes115-f24ce1cf73cb7b039d898cb67a2503b5c6d5ba60-x86_64.chimeraCore](1.2.0Cores/bsnes115-f24ce1cf73cb7b039d898cb67a2503b5c6d5ba60-x86_64.chimeraCore)</sub> |
| [Cadmium](https://github.com/ToolAssisted-run/chimera-core-cadmium) | CHIP8 | 2026-11-07 | <sub>[cadmium-0f7c85dfdffc01648a2275d8ddd8aa60837170a0-x86_64.chimeraCore](1.2.0Cores/cadmium-0f7c85dfdffc01648a2275d8ddd8aa60837170a0-x86_64.chimeraCore)</sub> |
| [Cemu](https://github.com/ToolAssisted-run/chimera-core-cemu) | WIIU | 2026-11-13 | <sub>[cemu-8213f49f20835f4c343be1f5f51e5f66ce609e31-x86_64.chimeraCore](https://github.com/CloakTheLurker/chimera-csx-cores/releases/download/1.2.0Cores-oversize/cemu-8213f49f20835f4c343be1f5f51e5f66ce609e31-x86_64.chimeraCore)</sub> |
| [Dolphin](https://github.com/ToolAssisted-run/chimera-core-dolphin) | GC, Wii, Triforce | 2026-11-13 | <sub>[dolphin-05934d488a17b9c1e6a6e2b1235cbc6e959dbf67-x86_64.chimeraCore](1.2.0Cores/dolphin-05934d488a17b9c1e6a6e2b1235cbc6e959dbf67-x86_64.chimeraCore)</sub> |
| [DOSBox-X](https://github.com/ToolAssisted-run/chimera-core-dosbox-x) | DOS | 2026-11-09 | <sub>[dosbox-x-8e99b5bf369a366fa6e4bac0f6b24ae8b2598826-x86_64.chimeraCore](1.2.0Cores/dosbox-x-8e99b5bf369a366fa6e4bac0f6b24ae8b2598826-x86_64.chimeraCore)</sub> |
| [DSDA-Doom](https://github.com/ToolAssisted-run/chimera-core-dsda) | Doom | 2026-11-07 | <sub>[dsda-d2360d2e6dee1f6234b1cbff121624a032026de2-x86_64.chimeraCore](1.2.0Cores/dsda-d2360d2e6dee1f6234b1cbff121624a032026de2-x86_64.chimeraCore)</sub> |
| [DuckStation](https://github.com/ToolAssisted-run/chimera-core-duckstation) | PS1, NAMCOS11, KONAMIGQ | 2026-11-13 | <sub>[duckstation-22652846fc013d3de8d79cb8b3eb5ff1eb744d46-x86_64.chimeraCore](1.2.0Cores/duckstation-22652846fc013d3de8d79cb8b3eb5ff1eb744d46-x86_64.chimeraCore)</sub> |
| [EKA2L1](https://github.com/ToolAssisted-run/chimera-core-eka2l1) | SYMBIAN | 2026-11-13 | <sub>[eka2l1-c7554c94517b1decf407af9709a3b903bdd9a3fc-x86_64.chimeraCore](1.2.0Cores/eka2l1-c7554c94517b1decf407af9709a3b903bdd9a3fc-x86_64.chimeraCore)</sub> |
| [FBNeo](https://github.com/ToolAssisted-run/chimera-core-fbneo) | CPS1, CPS2, CPS3, NEOGEO, SYS16, NEOCD | 2026-11-08 | <sub>[fbneo-e54f1691bac57c016883e06d6d39e81777fb58af-x86_64.chimeraCore](1.2.0Cores/fbneo-e54f1691bac57c016883e06d6d39e81777fb58af-x86_64.chimeraCore)</sub> |
| [Flycast](https://github.com/ToolAssisted-run/chimera-core-flycast) | DC, NAOMI, NAOMI2, AW | 2026-11-13 | <sub>[flycast-a4c8c31759f45b18cf1866d0c394096330d5d9c9-x86_64.chimeraCore](1.2.0Cores/flycast-a4c8c31759f45b18cf1866d0c394096330d5d9c9-x86_64.chimeraCore)</sub> |
| [FreeJ2ME-Plus](https://github.com/ToolAssisted-run/chimera-core-freej2me) | J2ME | 2026-11-07 | <sub>[freej2me-3f5a1d36d2ea3d4c58ece231fd3d59461d002d2a-x86_64.chimeraCore](1.2.0Cores/freej2me-3f5a1d36d2ea3d4c58ece231fd3d59461d002d2a-x86_64.chimeraCore)</sub> |
| [Fuse](https://github.com/ToolAssisted-run/chimera-core-fuse) | ZXS | 2026-11-07 | <sub>[fuse-94a7374ff38133662d0a90842c7cd6e1fba5a827-x86_64.chimeraCore](1.2.0Cores/fuse-94a7374ff38133662d0a90842c7cd6e1fba5a827-x86_64.chimeraCore)</sub> |
| [Gambatte](https://github.com/ToolAssisted-run/chimera-core-gambatte) | GB, GBC, SGB, GBL | 2026-11-07 | <sub>[gambatte-19ab19745b2a9b19cca65c9efafcc3dec4052a8b-x86_64.chimeraCore](1.2.0Cores/gambatte-19ab19745b2a9b19cca65c9efafcc3dec4052a8b-x86_64.chimeraCore)</sub> |
| [Godot 4.4](https://github.com/ToolAssisted-run/chimera-core-godot44) | Godot | 2026-11-13 | <sub>[godot44-b523903be4bcb694bbd27561137ea2bdec1a745a-x86_64.chimeraCore](1.2.0Cores/godot44-b523903be4bcb694bbd27561137ea2bdec1a745a-x86_64.chimeraCore)</sub> |
| [Godot 4.5](https://github.com/ToolAssisted-run/chimera-core-godot45) | Godot | 2026-11-13 | <sub>[godot45-95c179a9bfb9432ba5a14f10305b4293ab9c3f46-x86_64.chimeraCore](1.2.0Cores/godot45-95c179a9bfb9432ba5a14f10305b4293ab9c3f46-x86_64.chimeraCore)</sub> |
| [Godot 4.6](https://github.com/ToolAssisted-run/chimera-core-godot46) | Godot | 2026-11-13 | <sub>[godot46-1e101bf2b9b0c193135857845457d679a6938039-x86_64.chimeraCore](1.2.0Cores/godot46-1e101bf2b9b0c193135857845457d679a6938039-x86_64.chimeraCore)</sub> |
| [Godot 4.7](https://github.com/ToolAssisted-run/chimera-core-godot47) | Godot | 2026-11-13 | <sub>[godot47-526677833d8e7290cc8e94ed59fe1b1114e9e5ab-x86_64.chimeraCore](1.2.0Cores/godot47-526677833d8e7290cc8e94ed59fe1b1114e9e5ab-x86_64.chimeraCore)</sub> |
| [Genesis Plus GX](https://github.com/ToolAssisted-run/chimera-core-gpgx) | GEN, SMS, GG, SG, PICO | 2026-11-07 | <sub>[gpgx-5f1e922a78ee7af3461ce42e8d89ac59a81da71d-x86_64.chimeraCore](1.2.0Cores/gpgx-5f1e922a78ee7af3461ce42e8d89ac59a81da71d-x86_64.chimeraCore)</sub> |
| [Ikemen GO](https://github.com/ToolAssisted-run/chimera-core-ikemen) | IkemenGO | 2026-11-13 | <sub>[ikemen-de65622f7288b975ff22500c3679d77f985730bb-x86_64.chimeraCore](1.2.0Cores/ikemen-de65622f7288b975ff22500c3679d77f985730bb-x86_64.chimeraCore)</sub> |
| [MAME](https://github.com/ToolAssisted-run/chimera-core-mame) | ARCADE | 2026-11-13 | <sub>[mame-b2d440a3cd4d7f718b8a28f6bc96cb3b55d99f03-x86_64.chimeraCore](1.2.0Cores/mame-b2d440a3cd4d7f718b8a28f6bc96cb3b55d99f03-x86_64.chimeraCore)</sub> |
| [MAME Home Systems](https://github.com/ToolAssisted-run/chimera-core-mamehome) | A78, INTV, VEC, O2, ChannelF, AmstradCPC, TI83, BBC | 2026-11-13 | <sub>[mamehome-7f90fb5a3f1bf44526131be0c1c5c37c3bbce20b-x86_64.chimeraCore](1.2.0Cores/mamehome-7f90fb5a3f1bf44526131be0c1c5c37c3bbce20b-x86_64.chimeraCore)</sub> |
| [Mednafen](https://github.com/ToolAssisted-run/chimera-core-mednafen) | SAT, VB, PCFX, LYNX, STV | 2026-11-08 | <sub>[mednafen-6657fcaf012e679d59a6e8d29fdf680787535b9f-x86_64.chimeraCore](1.2.0Cores/mednafen-6657fcaf012e679d59a6e8d29fdf680787535b9f-x86_64.chimeraCore)</sub> |
| [melonDS](https://github.com/ToolAssisted-run/chimera-core-melonds) | NDS, DSI | 2026-11-13 | <sub>[melonds-8764e4cc8bec1115b069bd8c94b042c14ddb6b47-x86_64.chimeraCore](1.2.0Cores/melonds-8764e4cc8bec1115b069bd8c94b042c14ddb6b47-x86_64.chimeraCore)</sub> |
| [Open4DBoxing](https://github.com/ToolAssisted-run/chimera-core-open4dboxing) | 4DSportsBoxing | 2026-11-06 | <sub>[open4dboxing-2558ee5fb4fa51d3cb708a509c52a7078bcc3576-x86_64.chimeraCore](1.2.0Cores/open4dboxing-2558ee5fb4fa51d3cb708a509c52a7078bcc3576-x86_64.chimeraCore)</sub> |
| [OpenBOR](https://github.com/ToolAssisted-run/chimera-core-openbor) | OpenBOR | 2026-11-07 | <sub>[openbor-b3682d815d95509eb7e227c5380c2c2a9119f7c5-x86_64.chimeraCore](1.2.0Cores/openbor-b3682d815d95509eb7e227c5380c2c2a9119f7c5-x86_64.chimeraCore)</sub> |
| [OpenSamurai](https://github.com/ToolAssisted-run/chimera-core-opensamurai) | SwordOfTheSamurai | 2026-11-13 | <sub>[opensamurai-16b1c9a9762d4767da093fce9978d1efd418b793-x86_64.chimeraCore](1.2.0Cores/opensamurai-16b1c9a9762d4767da093fce9978d1efd418b793-x86_64.chimeraCore)</sub> |
| [Opera](https://github.com/ToolAssisted-run/chimera-core-opera) | 3DO | 2026-11-07 | <sub>[opera-0e5c58ba19177d5da3b9a802a454e38cf824a3ae-x86_64.chimeraCore](1.2.0Cores/opera-0e5c58ba19177d5da3b9a802a454e38cf824a3ae-x86_64.chimeraCore)</sub> |
| [PCem](https://github.com/ToolAssisted-run/chimera-core-pcem) | PC | 2026-11-13 | <sub>[pcem-4ba9a26298e768875001977a133244b2176bb200-x86_64.chimeraCore](1.2.0Cores/pcem-4ba9a26298e768875001977a133244b2176bb200-x86_64.chimeraCore)</sub> |
| [PCSX2](https://github.com/ToolAssisted-run/chimera-core-pcsx2) | PS2, NAMCO246, NAMCO256, NAMCOSUPER256 | 2026-11-13 | <sub>[pcsx2-4e8141adebc56fd787374419ed31d64b26b6a693-x86_64.chimeraCore](1.2.0Cores/pcsx2-4e8141adebc56fd787374419ed31d64b26b6a693-x86_64.chimeraCore)</sub> |
| [PPSSPP](https://github.com/ToolAssisted-run/chimera-core-ppsspp) | PSP | 2026-11-13 | <sub>[ppsspp-f23eb8bbe2629d43a1c036f67c2e0f88bca73a19-x86_64.chimeraCore](1.2.0Cores/ppsspp-f23eb8bbe2629d43a1c036f67c2e0f88bca73a19-x86_64.chimeraCore)</sub> |
| [PUAE](https://github.com/ToolAssisted-run/chimera-core-puae) | AMIGA, CD32, CDTV | 2026-11-07 | <sub>[puae-9702a190b538d4adabd5b4dee8c80f854136e3e9-x86_64.chimeraCore](1.2.0Cores/puae-9702a190b538d4adabd5b4dee8c80f854136e3e9-x86_64.chimeraCore)</sub> |
| [quickerNES](https://github.com/ToolAssisted-run/chimera-core-quickernes) | NES | 2026-11-08 | <sub>[quickernes-34b7f0475b659f2137a3b17a716d5e9a1cea747f-x86_64.chimeraCore](1.2.0Cores/quickernes-34b7f0475b659f2137a3b17a716d5e9a1cea747f-x86_64.chimeraCore)</sub> |
| [QuickerNesHawk](https://github.com/ToolAssisted-run/chimera-core-neshawk) | NES | 2026-11-07 | <sub>[quickerneshawk-096d94fa7f52ea33dcd0a581883d0afbee0184cd-x86_64.chimeraCore](1.2.0Cores/quickerneshawk-096d94fa7f52ea33dcd0a581883d0afbee0184cd-x86_64.chimeraCore)</sub> |
| [rawgl](https://github.com/ToolAssisted-run/chimera-core-rawgl) | AnotherWorld | 2026-11-13 | <sub>[rawgl-24bc5d7cc2a6a20e4c77ad10bdee3f351c5e5dd6-x86_64.chimeraCore](1.2.0Cores/rawgl-24bc5d7cc2a6a20e4c77ad10bdee3f351c5e5dd6-x86_64.chimeraCore)</sub> |
| [RPCS3](https://github.com/ToolAssisted-run/chimera-core-rpcs3) | PS3 | 2026-11-13 | <sub>[rpcs3-8a65e4e858ff90acc5e809cee8a902adaaaeef3a-x86_64.chimeraCore](1.2.0Cores/rpcs3-8a65e4e858ff90acc5e809cee8a902adaaaeef3a-x86_64.chimeraCore)</sub> |
| [RSDKv3](https://github.com/ToolAssisted-run/chimera-core-rsdkv3) | SonicCD | 2026-11-07 | <sub>[rsdkv3-bb5d3f83a1d497e91cc4c823314c8b40bc0f110f-x86_64.chimeraCore](1.2.0Cores/rsdkv3-bb5d3f83a1d497e91cc4c823314c8b40bc0f110f-x86_64.chimeraCore)</sub> |
| [RSDKv4](https://github.com/ToolAssisted-run/chimera-core-rsdkv4) | Sonic1, Sonic2 | 2026-11-13 | <sub>[rsdkv4-cf33c9548ecf10aac609c7e54139ca0a8ddabfcb-x86_64.chimeraCore](1.2.0Cores/rsdkv4-cf33c9548ecf10aac609c7e54139ca0a8ddabfcb-x86_64.chimeraCore)</sub> |
| [RSDKv5](https://github.com/ToolAssisted-run/chimera-core-rsdkv5) | SonicMania | 2026-11-07 | <sub>[rsdkv5-aae935ba493c4dc109065f51b4d11cee5711ec25-x86_64.chimeraCore](1.2.0Cores/rsdkv5-aae935ba493c4dc109065f51b4d11cee5711ec25-x86_64.chimeraCore)</sub> |
| [RSDKv5U](https://github.com/ToolAssisted-run/chimera-core-rsdkv5u) | SonicOrigins | 2026-11-07 | <sub>[rsdkv5u-952541654b54af00da92e7ec4f18f2a4cd3897b2-x86_64.chimeraCore](1.2.0Cores/rsdkv5u-952541654b54af00da92e7ec4f18f2a4cd3897b2-x86_64.chimeraCore)</sub> |
| [Ruffle](https://github.com/ToolAssisted-run/chimera-core-ruffle) | Flash | 2026-11-13 | <sub>[ruffle-61d5d5888772526f0a4c8a5faca102d3c828a67c-x86_64.chimeraCore](1.2.0Cores/ruffle-61d5d5888772526f0a4c8a5faca102d3c828a67c-x86_64.chimeraCore)</sub> |
| [ScummVM](https://github.com/ToolAssisted-run/chimera-core-scummvm) | ScummVM | 2026-11-13 | <sub>[scummvm-d001bcd8b860c6630d9e82913291004c4bf9bee7-x86_64.chimeraCore](https://github.com/CloakTheLurker/chimera-csx-cores/releases/download/1.2.0Cores-oversize/scummvm-d001bcd8b860c6630d9e82913291004c4bf9bee7-x86_64.chimeraCore)</sub> |
| [SDLPoP](https://github.com/ToolAssisted-run/chimera-core-sdlpop) | PrinceOfPersia | 2026-11-13 | <sub>[sdlpop-f3c09396453409e3ee2a86b58fd51f3c9cde6255-x86_64.chimeraCore](1.2.0Cores/sdlpop-f3c09396453409e3ee2a86b58fd51f3c9cde6255-x86_64.chimeraCore)</sub> |
| [SDLPoP2](https://github.com/ToolAssisted-run/chimera-core-sdlpop2) | PrinceOfPersia2 | 2026-11-13 | <sub>[sdlpop2-e3e6615dcad806e8c305ac4024e2864d23b901af-x86_64.chimeraCore](1.2.0Cores/sdlpop2-e3e6615dcad806e8c305ac4024e2864d23b901af-x86_64.chimeraCore)</sub> |
| [Snes9x](https://github.com/ToolAssisted-run/chimera-core-snes9x) | SNES | 2026-11-08 | <sub>[snes9x-b1df21ac87c0cf351bf76810c73e51c405ba350a-x86_64.chimeraCore](1.2.0Cores/snes9x-b1df21ac87c0cf351bf76810c73e51c405ba350a-x86_64.chimeraCore)</sub> |
| [Stella](https://github.com/ToolAssisted-run/chimera-core-stella) | A26 | 2026-11-08 | <sub>[stella-bb69c2cc2b3e36f0d57654bc884964a2098f9493-x86_64.chimeraCore](1.2.0Cores/stella-bb69c2cc2b3e36f0d57654bc884964a2098f9493-x86_64.chimeraCore)</sub> |
| [Supermodel](https://github.com/ToolAssisted-run/chimera-core-supermodel) | Model3 | 2026-11-13 | <sub>[supermodel-cb1ad4a799b22559b936f20eb59299c0a5fb78b0-x86_64.chimeraCore](1.2.0Cores/supermodel-cb1ad4a799b22559b936f20eb59299c0a5fb78b0-x86_64.chimeraCore)</sub> |
| [SyndicatFX](https://github.com/ToolAssisted-run/chimera-core-syndicatfx) | Syndicate | 2026-11-13 | <sub>[syndicatfx-777d3b396e17337ac102eb26c416bba4062e50ee-x86_64.chimeraCore](1.2.0Cores/syndicatfx-777d3b396e17337ac102eb26c416bba4062e50ee-x86_64.chimeraCore)</sub> |
| [TIC-80](https://github.com/ToolAssisted-run/chimera-core-tic80) | TIC80 | 2026-11-07 | <sub>[tic80-c637a363e85b6c0e238021af404000c240948ad0-x86_64.chimeraCore](1.2.0Cores/tic80-c637a363e85b6c0e238021af404000c240948ad0-x86_64.chimeraCore)</sub> |
| [touchHLE](https://github.com/ToolAssisted-run/chimera-core-touchhle) | iOS | 2026-11-13 | <sub>[touchhle-63769570d241279e5c9941a936c91b94030d5b53-x86_64.chimeraCore](1.2.0Cores/touchhle-63769570d241279e5c9941a936c91b94030d5b53-x86_64.chimeraCore)</sub> |
| [Uzem](https://github.com/ToolAssisted-run/chimera-core-uzem) | UZE | 2026-11-07 | <sub>[uzem-9f5a31d220bcb5674a7903740d18ac79cf46a7c1-x86_64.chimeraCore](1.2.0Cores/uzem-9f5a31d220bcb5674a7903740d18ac79cf46a7c1-x86_64.chimeraCore)</sub> |
| [VICE](https://github.com/ToolAssisted-run/chimera-core-vice) | C64 | 2026-11-07 | <sub>[vice-243799b1eddf83e278ac2a028370195c574f8294-x86_64.chimeraCore](1.2.0Cores/vice-243799b1eddf83e278ac2a028370195c574f8294-x86_64.chimeraCore)</sub> |
| [Virtual Jaguar](https://github.com/ToolAssisted-run/chimera-core-virtualjaguar) | JAG, JAGCD | 2026-11-07 | <sub>[virtualjaguar-246b34ca629884a378d3c0b665b1cbc88dccd02f-x86_64.chimeraCore](1.2.0Cores/virtualjaguar-246b34ca629884a378d3c0b665b1cbc88dccd02f-x86_64.chimeraCore)</sub> |
| [Vita3K](https://github.com/ToolAssisted-run/chimera-core-vita3k) | PSV | 2026-11-13 | <sub>[vita3k-7bfe3b343bfbf59b6e281a40c0cf9e58e7cc3c68-x86_64.chimeraCore](1.2.0Cores/vita3k-7bfe3b343bfbf59b6e281a40c0cf9e58e7cc3c68-x86_64.chimeraCore)</sub> |
| [MAME X68000](https://github.com/ToolAssisted-run/chimera-core-x68k) | X68000 | 2026-11-13 | <sub>[x68k-68357c9e3c24b5b1446cac3c09ff9532a56b5e69-x86_64.chimeraCore](1.2.0Cores/x68k-68357c9e3c24b5b1446cac3c09ff9532a56b5e69-x86_64.chimeraCore)</sub> |
| [xemu](https://github.com/ToolAssisted-run/chimera-core-xemu) | XBOX | 2026-11-13 | <sub>[xemu-aae93b10e5da3ff455290db8cf841fcf044cda01-x86_64.chimeraCore](1.2.0Cores/xemu-aae93b10e5da3ff455290db8cf841fcf044cda01-x86_64.chimeraCore)</sub> |
| [Xenia](https://github.com/ToolAssisted-run/chimera-core-xenia) | X360 | 2026-11-13 | <sub>[xenia-cb45a542ec546947533aed0b78a134e8f0b75bca-x86_64.chimeraCore](1.2.0Cores/xenia-cb45a542ec546947533aed0b78a134e8f0b75bca-x86_64.chimeraCore)</sub> |
| [Zeebx](https://github.com/ToolAssisted-run/chimera-core-zeebx) | ZEEBO | 2026-11-13 | <sub>[zeebx-8209ffb0a97ee827fe599d53df5904bd27316ca0-x86_64.chimeraCore](1.2.0Cores/zeebx-8209ffb0a97ee827fe599d53df5904bd27316ca0-x86_64.chimeraCore)</sub> |
| [ZEsarUX](https://github.com/ToolAssisted-run/chimera-core-zesarux) | ZXN | 2026-11-07 | <sub>[zesarux-148b939238796bc06d4258f4f6da17981e382625-x86_64.chimeraCore](1.2.0Cores/zesarux-148b939238796bc06d4258f4f6da17981e382625-x86_64.chimeraCore)</sub> |

## 1.4.0Cores

63 packages. The 1.2.0 set is here unchanged, plus Mesen, so a project that
runs on 1.2.0 or 1.3.x runs on it too. Its index is
[cores-1.4.0.json](cores-1.4.0.json).

The 60 packages that were in the 1.2.0 folder stay in `1.2.0Cores/`; their
links in the 1.2.0 table above are the ones to use. The only file in
`1.4.0Cores/` is Mesen. Cemu and ScummVM are the same two files as before and
stay in
[the 1.2.0Cores-oversize release](https://github.com/CloakTheLurker/chimera-csx-cores/releases/tag/1.2.0Cores-oversize).
Copy the 60 from `1.2.0Cores`, Mesen from `1.4.0Cores`, and the two oversized
files into `Cores` together.

| Core | Systems | Nightly | Package |
|---|---|---|---|
| [Mesen](https://github.com/ToolAssisted-run/chimera-core-mesen) | NES, SNES, SGB, GB, GBC, GBA, PCE, SGX, PCECD, SMS, GG, SG, CV, WS, WSC, PCV2 | 2026-11-08 | <sub>[mesen-f979dd38e0c20285a4556eecc1d41b7574a59905-x86_64.chimeraCore](1.4.0Cores/mesen-f979dd38e0c20285a4556eecc1d41b7574a59905-x86_64.chimeraCore)</sub> |

Mesen's package declares `settings[].optionLabels` as an array in the order of
its options. Chimera CSX 1.2.0 refused that; 1.4.0 pairs the two and reads it.

## 1.4.1Cores

72 packages. The 1.4.0 set is here unchanged, plus the nine cores upstream
added on 2026-11-15 and 16: Gearboy, Gearsystem, Gearcoleco, Geargrafx,
Gearlynx, Pokket, Geartowns, blueMSX and Sonic 3 A.I.R. Its index is
[cores-1.4.1.json](cores-1.4.1.json).

The 60 packages in `1.2.0Cores/` and Mesen in `1.4.0Cores/` are the ones the
earlier tables link; the nine new files are in `1.4.1Cores/`. Cemu and ScummVM
are the same two files and stay in
[the 1.2.0Cores-oversize release](https://github.com/CloakTheLurker/chimera-csx-cores/releases/tag/1.2.0Cores-oversize).
Copy all of them into `Cores` together.

The nine bring the link-cable systems the earlier sets did not have - Game Gear
Link, Mark III Link and Atari Lynx Link - and the Coleco ADAM, the Sony
PocketStation, the FM Towns, and the MSX2+ and turbo R; Geargrafx adds another
PC Engine CD core and Gearboy another Game Boy family core, beside Sonic 3 A.I.R.
as a game core. Each package declares the firmware it
needs - boot ROMs, a System Card, MSX and PocketStation BIOSes, FM Towns ROMs or
the free TOWNSROM set, and the Sonic & Knuckles + Sonic 3 ROM - and the wizard
asks for it. Gearsystem's FM sound chip and Sonic 3 A.I.R. are non-commercial,
as Chimera's README says.

| Core | Systems | Nightly | Package |
|---|---|---|---|
| [Gearboy](https://github.com/ToolAssisted-run/chimera-core-gearboy) | GB, GBC, SGB, GBL | 2026-11-15 | <sub>[gearboy-7aaf5a77db9ca53e81243ede71b458bcb6eb7954-x86_64.chimeraCore](1.4.1Cores/gearboy-7aaf5a77db9ca53e81243ede71b458bcb6eb7954-x86_64.chimeraCore)</sub> |
| [Gearsystem](https://github.com/ToolAssisted-run/chimera-core-gearsystem) | SMS, GG, SG, GGL, M3L | 2026-11-15 | <sub>[gearsystem-fbd5a45f9737955bfceb209f56d8d33408698a18-x86_64.chimeraCore](1.4.1Cores/gearsystem-fbd5a45f9737955bfceb209f56d8d33408698a18-x86_64.chimeraCore)</sub> |
| [Gearcoleco](https://github.com/ToolAssisted-run/chimera-core-gearcoleco) | CV, ADAM | 2026-11-16 | <sub>[gearcoleco-a61de165d4454540af308c676e09e97bc269e0bf-x86_64.chimeraCore](1.4.1Cores/gearcoleco-a61de165d4454540af308c676e09e97bc269e0bf-x86_64.chimeraCore)</sub> |
| [Geargrafx](https://github.com/ToolAssisted-run/chimera-core-geargrafx) | PCE, SGX, PCECD | 2026-11-15 | <sub>[geargrafx-040d754715ae20c81b796fafeeeaea94b30e5432-x86_64.chimeraCore](1.4.1Cores/geargrafx-040d754715ae20c81b796fafeeeaea94b30e5432-x86_64.chimeraCore)</sub> |
| [Gearlynx](https://github.com/ToolAssisted-run/chimera-core-gearlynx) | LYNX, LYNXLINK | 2026-11-15 | <sub>[gearlynx-0c7ad05d7029e0bb209aa776367288696e0e854e-x86_64.chimeraCore](1.4.1Cores/gearlynx-0c7ad05d7029e0bb209aa776367288696e0e854e-x86_64.chimeraCore)</sub> |
| [Pokket](https://github.com/ToolAssisted-run/chimera-core-pokket) | POCKETSTATION | 2026-11-15 | <sub>[pokket-d1d441361feabed164db613eb2f63c63a85540d3-x86_64.chimeraCore](1.4.1Cores/pokket-d1d441361feabed164db613eb2f63c63a85540d3-x86_64.chimeraCore)</sub> |
| [Geartowns](https://github.com/ToolAssisted-run/chimera-core-geartowns) | FMTowns | 2026-11-15 | <sub>[geartowns-ce6070948052cbece44004766e4897babea50772-x86_64.chimeraCore](1.4.1Cores/geartowns-ce6070948052cbece44004766e4897babea50772-x86_64.chimeraCore)</sub> |
| [blueMSX](https://github.com/ToolAssisted-run/chimera-core-bluemsx) | MSX, MSX2, MSX2P, MSXTR | 2026-11-15 | <sub>[bluemsx-72c20df7437551d13837ca44488b581b515b1637-x86_64.chimeraCore](1.4.1Cores/bluemsx-72c20df7437551d13837ca44488b581b515b1637-x86_64.chimeraCore)</sub> |
| [Sonic 3 A.I.R.](https://github.com/ToolAssisted-run/chimera-core-sonic3air) | S3AIR | 2026-11-15 | <sub>[sonic3air-24e19755bac1d1aaac79c3c19450903c587145bf-x86_64.chimeraCore](1.4.1Cores/sonic3air-24e19755bac1d1aaac79c3c19450903c587145bf-x86_64.chimeraCore)</sub> |

## 1.4.4Cores

74 packages. The 1.4.1 set is here unchanged, plus the two game cores added on
2026-11-19: fheroes2, Heroes of Might and Magic II, and TheXTech, Super Mario
Bros. X. Its index is [cores-1.4.4.json](cores-1.4.4.json).

The 60 packages in `1.2.0Cores/`, Mesen in `1.4.0Cores/` and the nine in
`1.4.1Cores/` are the ones the earlier tables link; the two new files are in
`1.4.4Cores/`. Copy all of them into `Cores` together. Cemu and ScummVM are the
same two files as before and stay in
[the 1.2.0Cores-oversize release](https://github.com/CloakTheLurker/chimera-csx-cores/releases/tag/1.2.0Cores-oversize).

Both are game cores and both are x86_64: fheroes2 reads the game's own
`HEROES2.AGG` data file, or its free demo's, from a file slot, and TheXTech
wants an SMBX 1.3 asset pack there. Their terms are GPL-2.0 and GPL-3.0, and
neither is non-commercial. Each package also carries a Save Data window of its
own design; the WinForms window does not show a package's windows, and its own
Export Save Data does the same job.

| Core | Systems | Nightly | Package |
|---|---|---|---|
| [fheroes2](https://github.com/ToolAssisted-run/chimera-core-fheroes2) | HoMM2 | 2026-11-19 | <sub>[fheroes2-0645d3273b3354a9b66b441bf8f68ae90d04905b-x86_64.chimeraCore](1.4.4Cores/fheroes2-0645d3273b3354a9b66b441bf8f68ae90d04905b-x86_64.chimeraCore)</sub> |
| [TheXTech](https://github.com/ToolAssisted-run/chimera-core-thextech) | SMBX | 2026-11-19 | <sub>[thextech-5372b92b739802278e9deed9edceec55ec0a62cd-x86_64.chimeraCore](1.4.4Cores/thextech-5372b92b739802278e9deed9edceec55ec0a62cd-x86_64.chimeraCore)</sub> |

## Checked

Every file's SHA-256 equals the digest GitHub recorded for its release asset.
Against the Chimera CSX 1.2.0 release, the package contract tests (26) pass on
all 55 packages of `1.0.0Cores`; in `1.2.0Cores` every package is read and
becomes a factory, and the only candidate the tests refuse is Mesen, which is
not in the set.

Against Chimera CSX 1.4.0, the 36 package and roster contract tests pass on the
61 files in `1.4.0Cores`, including Mesen's package, its factory and the
roster's system names. The two oversized packages are the same files that were
checked with `1.2.0Cores`.

Against Chimera CSX 1.4.1, on 2026-11-16, the 36 package and roster contract
tests pass on the 70 files present here: the 60 in `1.2.0Cores`, Mesen, and the
nine in `1.4.1Cores`. The two oversized packages are the same files checked
with `1.2.0Cores`, and the roster names all 72.

Against Chimera CSX 1.4.3 with the 74-row roster of the next release, on
2026-11-19, the package, roster, mnemonic, language-table and theme contract
tests pass 39 of 39 on the 72 files in the four folders, with none failed and
none skipped. Cemu and ScummVM are not part of that check: they are the files
checked with `1.2.0Cores` and stay out of it.

## Licenses

Each core is its own project under its own license and copyright. Every
package carries its licenses inside, under `licenses/` in the zip, including
the license of the emulator it builds and of the Chimera integration. This
repository only stores those published packages as they are.
