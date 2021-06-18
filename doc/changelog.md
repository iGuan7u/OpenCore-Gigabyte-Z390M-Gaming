# Change Log

## 2021-06-18

1. Update OpenCore to v0.7.0
2. Update Lilu.kext to v1.5.3
3. Update SMCProcessor.kext to v1.2.4
4. Update SMCSuperIO.kext to v1.2.4
5. Update VirtualSMC.kext to v1.2.4
6. Update WhateverGreen.kext to v1.5.0
7. Update IntelMausi.kext to v1.0.6
8. Update AppleALC.kext to v1.6.1

macOS sleep become more reliable, and support macOS 11. Have fun.

## 2020-10-10

1. Update OpenCore to v0.6.2
2. Update Lilu.kext to v1.4.8
3. Update SMCProcessor.kext to v1.1.7
4. Update SMCSuperIO.kext to v1.1.7
5. Update VirtualSMC.kext to v1.1.7
6. Update WhateverGreen.kext to v1.4.3
7. Update IntelMausi.kext to v1.0.4
8. Update AppleALC.kext to v1.5.3
9. Delete ApfsDriverLoader.efi, now OpenCore will try to load APFS drivers in APFS container
10. Delete MemoryAllocation.efi, combine with `DevirtualiseMmio` and `ProtectUefiServices` properties, enable KASLR memory injection
11. Delete FwRuntimeSerices.efi, now it is rename as `OpenCoreRuntime.efi`

Nothing seems is different, suit yourself.

## 2020-07-26

1. Update OpenCore to v0.5.9
2. Update Lilu.kext to v1.4.5
3. Update SMCProcessor.kext to v1.1.4
4. Update SMCSuperIO.kext to v1.1.4
5. Update VirtualSMC.kext to v1.1.4
6. Update WhateverGreen.kext to v1.4.0
7. Update IntelMausi.kext to v1.0.3
8. Update AppleALC.kext to v1.5.0
9. Add NVMeFix.kext
10. Disable OpenCore detect Windows EFI boot Option

Nothing seems is different, suit yourself.

## 2020-03-27

1. Update OpenCore to v0.5.6
2. Update Lilu.kext to v1.4.2
3. Update SMCProcessor.kext to v1.1.1
4. Update VirtualSMC to v1.1.1
5. Update WhateverGreen.kext to v1.3.7

The startup speed is a little bit faster than before, and the picker view looks way much better.

## 2020-02-16

Fix display problem with update to macOS 10.15.3, ACPI patch seems not worked after updating to macOS 10.15.3, now move back to WhateverGreen.

1. Update OpenCore to v0.5.5
2. Update WhatevenGreen.kext to v1.3.6
3. Add EFIShell tool.
4. Update AppleALC.kext to v1.4.5

## 2020-02-04

Fix some strange kernel problem.

1. Update Lilu.kext to v1.4.1
2. Update VirtualSMC.kext to v1.1.0