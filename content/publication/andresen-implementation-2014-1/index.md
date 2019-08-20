---
title: "Implementation of pixel level digital TDI for scanning type LWIR FPAs"
date: 2014-07-01
publishDate: 2019-08-14T08:21:45.381782Z
authors: ["Omer Ceylan", "Huseyin Kayahan", "Melik Yazici", "Sohaib Afridi", "Atia Shafique", "Yasar Gurbuz"]
publication_types: ["1"]
abstract: "Implementation of a CMOS digital readout integrated circuit (DROIC) based on pixel level digital time delay integration (TDI) for scanning type LWIR focal plane arrays (FPAs) is presented. TDI is implemented on 8 pixels with over sampling rate of 3. Analog signal integrated on integration capacitor is converted to digital domain in pixel, and digital data is transferred to TDI summation counters, where contributions of 8 pixels are added. Output data is 16 bit, where 8 bits are allocated for most significant bits and 8 bits for least significant bits. Control block of the ROIC, which is responsible of generating timing diagram for switches controlling the pixels and summation counters, is realized with VerilogHDL. Summation counters and parallel-to-serial converter to convert 16 bit parallel output data to single bit output are also realized with Verilog HDL. Synthesized verilog netlists are placed&routed and combined with analog under-pixel part of the design. Quantization noise of analog-to-digital conversion is less than 500e-. Since analog signal is converted to digital domain in-pixel, inaccuracies due to analog signal routing over large chip area is eliminated. ROIC is fabricated with 0.18μm CMOS process and chip area is 10mm2. Post-layout simulation results of the implemented design are presented. ROIC is programmable through serial or parallel interface. Input referred noise of ROIC is less than 750 rms electron, while power consumption is less than 30mW. ROIC is designed to perform in cryogenic temperatures."
featured: false
publication: ""
url_pdf: "http://proceedings.spiedigitallibrary.org/proceeding.aspx?doi=10.1117/12.2054638"
doi: "10.1117/12.2054638"
---

