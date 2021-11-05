# Onimusha3Patch

Patch Onmimusha 3 to allow any screen resolution.

## How to use
1. Compile solution
2. Copy OniInjector.exe and OniPatch.dll to Onimusha 3 directory.
3. Run OniInjector.exe

## How it works
OniInjector.exe injects OniPatch.dll into the game (oni3.exe).

OniPatch.dll hooks DirectX 9 and CreateWindowExW to force the resolution size.