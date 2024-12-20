SparkFun Quadband GNSS RTK Breakout - LG290P (Qwiic)
========================================

[![SparkFun Quadband GNSS RTK Breakout - LG290P (Qwiic)](https://cdn.sparkfun.com/r/600-600/assets/parts/2/7/6/3/7/26620-LG290P-Quadband-GNSS-Breakout-Feature.jpg)](https://www.sparkfun.com/products/26620)

[*SparkFun Quadband GNSS RTK Breakout - LG290P (Qwiic) (GPS-26620)*](https://www.sparkfun.com/products/26620)


The [SparkFun Quadband GNSS RTK Breakout - LG290P (Qwiic)](https://www.sparkfun.com/products/26620) features the Quectel LG290P GNSS module. The board's dimensions, pin layout, and connectors are exactly the same as our vary popular [SparkFun GPS-RTK-SMA Breakout - ZED-F9P (Qwiic)](https://www.sparkfun.com/products/16481); and can be used as a drop-in replacement. The board also accommodates users with a diverse choice of interfaces including UART, SPI*, and I2C*.

The LG290P module is a quad-band, multi-constellation, high-precision, RTK GNSS receiver. The module is capable of simultaneously receiving signals from the `L1`, `L2`, `L5`, and `L6`/`E6` frequency bands of the GPS, GLONASS, Galileo, BDS, QZSS, and NavIC GNSS constellations. In addition, the module supports SBAS augmentation systems (WASS, EGNOS, BDSBAS, MSAS, GAGAN, and SDCM), PPP services* (BDS PPP-B2b, QZSS CLAS, MADOCA-PPP, and Galileo HAS), and RTK corrections for precision navigation with a fast convergence time and reliable performance.

The built-in NIC anti-jamming unit provides professional-grade interference signal detection and elimination algorithms, which effectively mitigate against multiple narrow-band interference sources and significantly improves the signal reception performance in complex electromagnetic environments. Additionally, the embedded algorithms ensure reliable positioning in complex scenarios such as urban environments and deep tree cover.

With its performance advantages of high-precision and low power consumption, this board is an ideal choice for high-precision navigation applications, such as intelligent robots, UAVs, precision agriculture, mining, surveying, and autonomous navigation.

> [!NOTE]
> `*`: Feature is still under development

> [!IMPORTANT]
> - Currently, only the UART interface is supported by the module. All three UART ports are broken out to the USB-C connector *(via CH342 USB-serial converter)*, 4-pin locking JST connector, and BlueSMiRF 6-pin header.
> - Additionally, the corrections for some of the PPP services may not be implemented yet.



Documentation
--------------

* **[Hookup Guide (mkdocs)](http://docs.sparkfun.com/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/)** - The hookup guide for the SparkFun Quadband GNSS RTK Breakout - LG290P (Qwiic) hosted by GitHub pages.<br>
  [![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/) [![GitHub Pages Deploy](https://github.com/sparkfun/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/actions/workflows/mkdocs.yml/badge.svg)](https://github.com/sparkfun/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/actions/workflows/mkdocs.yml)
* [SparkFun LG290P GNSS Arduino Library](https://github.com/sparkfun/SparkFun_LG290P_GNSS_Arduino_Library) - An Arduino library for the LG290P GNSS module


*Need to download or print our hookup guide?*

* [Print *(Print to PDF)* from Single-Page View](http://docs.sparkfun.com/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/print_view)

Repository Contents
-------------------

* **[/docs](/docs/)** - Online documentation files
    * [assets](/docs/assets/) - Assets files
        * [3d_model](/docs/assets/3d_model/) - Files for the 3D models
            * [3D CAD Model](/docs/assets/3d_model/cad_model.step) (.step)
        * [board_files](/docs/assets/board_files/) - Files for the product design
            * [KiCad Design Files](/docs/assets/board_files/kicad_files.zip) (.zip)
            * [Schematic](/docs/assets/board_files/schematic.pdf) (.pdf)
            * [Dimensions](/docs/assets/board_files/dimensions.pdf) (.pdf)
        * [component_documentation](/docs/assets/component_documentation/) - Datasheets for hardware components
        * [img/hookup_guide/](/docs/assets/img/hookup_guide/) - Images for hookup guide documentation
* **[/Hardware](/Hardware/)** - Hardware design files (.brd, .sch)
  * **[/Production](/Production/)** - Production files

Product Variants
----------------

* [GPS-26620](https://www.sparkfun.com/products/26620) - v1.0, Initial Release
* [GPS-26916](https://www.sparkfun.com/products/26916) - SparkFun RTK Postcard *(w/ ESP32)*

Version History
---------------

* [v10](https://github.com/sparkfun/SparkFun_LG290P_Quadband_GNSS_RTK_Breakout/releases/tag/v10) - Initial Release


License Information
-------------------

This product is ***open source***!

Please review the [`LICENSE.md`](./LICENSE.md) file for license information.

If you have any questions or concerns about licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
