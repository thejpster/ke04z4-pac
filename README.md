# ke04z4-pac

This is a [Peripheral Access Crate] for the NXP Kinetis [KE04Z4] series of microcontrollers. There are two variants in KE04Z series - this crate only supports the 16/20/24-pin form-factor with up to 8 KiB of Flash, known as the MKE04Z4 and MKE04Z8. The larger form-factor (e.g. TQFP-64) MKE04Z64 and MKE04Z128 parts have up to 128 KiB of Flash and hence have slightly a different register map. They are therefore not supported.

[Peripheral Access Crate]: https://rust-embedded.github.io/book/start/registers.html
[MKE04Z]: https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/ke-series-cortex-m4-m0-plus/kinetis-ke04-48-mhz-mainstream-microcontrollers-mcus-based-on-arm-cortex-m0-plus-core:KE04

This crate has been built using [svd2rust] version 0.17, using NXP's [MKE04Z BSP] version 12.2.0.

[svd2rust]: https://github.com/rust-embedded/svd2rust
[MKE04Z BSP]: http://mcuxpresso.nxp.com/cmsis_pack/repo/NXP.FRDM-KE04Z_BSP.12.2.0.pack

## Licence

The contents of this crate are auto-generated and licensed as [CC0]. Note that the underlying SVD file is licensed by NXP under a BSD-3-Clause licence.

[CC0]: https://creativecommons.org/publicdomain/zero/1.0/
