# NovaFlare additive compatibility interfaces

Restores original initVars and prepareDrawMatrix. transformMatrix/matrixExposed remain compatibility fields and do not alter the legacy draw matrix or animation update.

The earlier broad integration changed existing behavior and is superseded by this repair. Compatibility additions must preserve existing NF calls, defaults and update/render/audio paths. Unsupported additions may return a neutral result instead of replacing a legacy implementation.

Windows x64 and Android ARMv7/ARM64/x86_64 native Lime binaries have been rebuilt. The full game targets Windows x64 and Android ARM64. Visual gameplay acceptance is performed manually by the project owner.
