+++
author = "Gamer64"
title = 'Mandarine 1.0'
date = 2024-08-10
description = "The initial release"
+++

## Things that are from Citra Enhanced:

- Android: Rework settings UI (@Ishan09811)
- Android: Implement oboe audio backend
- Android: Implement touch opacity controls
- Android: Implement invididual button scaling (@gperrio)
- Android: Implement haptic feedback support (@gperrio)
- Android & PC: Switched Anaglyph shader technique from Dubois to Rendepth (@cybereality)
- Android & PC: Migrate to tracy profiler from Microprofile (@raphaelthegreat)
- PC: Disable accurate mul by default
- Android & PC: Backport Skip Slow Draw, Skip Texture Copy and Skip CPU Write hacks from Citra MMJ (@weihuoya)
- Android/ARM64: Optimize AreQuaternionsOpposite (@weihuoya)
- Android & PC: Implement priority boost starved threads hack (known as Priority Boost Hack)
- Android: Implement swap screens hotkey (@gperrio)
- Android & PC: Restore Frame Skip functionality (with some help of @rtiangha)
- Android: Implement Adreno GPU Boost (@Ishan09811)
- Android & PC: Implement Realtime audio
- Android & PC: Implement reduce downcount slice (based on @weihuoya cpu usage limit hack)
- renderer_vulkan: Initial vertex-shader SPIR-V generation (@Wunkolo)
- android: Add button dpad bindings (@OpenSauce04)
- Android: Implement RAM usage counter into FPS counter (@Ishan09811)
- android: Gamepads can now control the in-game menu (@OpenSauce04)
- citra_qt: Add support for favorites, desktop shortcuts, and play time tracking (@FearlessTobi)
- PC: Better game titles on the window and Discord RPC (@BlurrySquire)
- PC: Implement Layout settings tab and support (@blakbin)
- glsl_fs_shader_gen: Use a better way to discard GasMode
- Android: Implement About Game Dialog (@Ishan09811)
- Android: fix non runtime runnable settings bugs (@Ishan09811)

## Things that are new on Mandarine rebrand:

- Skip Slow Draw, Skip Texture Copy and Skip CPU Write hacks got rebranded to Force Hardware Vertex Shaders, Disable Surface Texture Copy and Disable Flush CPU Write.
- New options got reordered and positioned on better sites.
- Fixed all graphic issues of frameskip
- memory.cpp: Fix a minor memory leak
- Android: Replace company with game region for card game
- PC: Implement emulator data migration functionality + prompt (@OpenSauce04)
- Android: Implement Expand to Display Cutout option
- Android: Re-implement ForegroundService
- oboe_sink: Set AudioApi to OpenSLES and minor improvements
- externals: Massive submodule updates (vulkan headers, glslang, libadrenotools...)
- pica_types: Correctly restrict Float<M, E> precision (@vitor-k)
- Another minor improvements and cleanups

## Download Links

[mandarine-android-universal-20240806-a22d894.apk](https://github.com/mandarine3ds/mandarine/releases/download/r1.0/mandarine-android-universal-20240806-a22d894.apk)
[mandarine-linux-appimage-20240806-a22d894.tar.gz](https://github.com/mandarine3ds/mandarine/releases/download/r1.0/mandarine-linux-appimage-20240806-a22d894.tar.gz)
[mandarine-macos-universal-20240806-a22d894.tar.gz](https://github.com/mandarine3ds/mandarine/releases/download/r1.0/mandarine-macos-universal-20240806-a22d894.tar.gz)
[mandarine-windows-msvc-20240806-a22d894.zip](https://github.com/mandarine3ds/mandarine/releases/download/r1.0/mandarine-windows-msvc-20240806-a22d894.zip)
[mandarine-windows-msys2-20240806-a22d894.zip](https://github.com/mandarine3ds/mandarine/releases/download/r1.0/mandarine-windows-msys2-20240806-a22d894.zip)
