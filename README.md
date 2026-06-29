<div align="center">
  <table border="0" cellpadding="0" cellspacing="0">
    <tr>
      <td align="center" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/4f222af6-7d25-4b8a-b29e-ba9c0ae45a66" width="100%" max-width="800px" alt="Rough Layout For The PCB" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 500;">
      </td>
    </tr>
  </table>
</div>


| Title | Nano-Spark |
| :-- | :---|
|Author |Sadrita Neogi|

## What's this?
NanoSpark is an Digispark clone with All 6 GPIOs from the attiny available 5V output (direct from USB) 3V3 output (via AMS1117 voltage regulator) Power LED Onboard LED connected to PB1 USB-A connector

## Why I built it ?

To learn more about electronics and PCB design and also because the Digispark boards don't have a 3V3 output. This board also uses USB-A instead of Micro USB so I don't need any extra cable to connect to my laptop.

## Programming

The attiny chip needs to be flashed with a bootloader so that you can use it without a programmer (like an Arduino board). 
#### [Bootloader](https://github.com/Sadrita404/Nano-Spark/tree/main/Boot%20loader)

**[GUIDE](https://circuitdigest.com/microcontroller-projects/attiny85-ic-programming-through-usb-using-digispark-bootloader)**

These tutorials use the micronucleus bootloader used by the Digispark attiny boards.

There is an onboard LED hardwired to PB1 so you can get your blink sketch running without any extra hardware.

## Features

* All 6 GPIOs from the attiny available 

* 5V output (direct from USB)

* 3V3 output (via AMS1117 voltage regulator)

* Power LED

* Onboard LED connected to PB1

* USB-A connector


<div align="center">


| | PCB Designing | |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/f3996346-9013-45c8-81eb-966b92ee7805" width="250" alt="Design 1" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/689ccf27-2927-4a25-876f-f0e7e0b3bbcb" width="250" alt="Design 2" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/7131f6af-de08-4118-a3be-8388d53fe837" width="250" alt="Design 3" style="border-radius: 12px;" /> |
| <img src="https://github.com/user-attachments/assets/7ddaf136-164d-4602-bb74-db82ddface24" width="250" alt="Design 4" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/ec1e138d-eb47-40f2-a7a6-cc64ede112cb" width="250" alt="Design 5" style="border-radius: 12px;" /> | <img src="https://github.com/user-attachments/assets/3791158d-f04d-446e-bc0d-424ccaa4afaf" width="250" alt="Design 6" style="border-radius: 12px;" /> |


<div align="center">
  <h2> Final Look </h2>
  <table border="0" cellpadding="10" cellspacing="0" style="border-collapse: collapse;">
    <tr>
      <!-- FRONT SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/4e8d0080-9d9d-42d7-a549-8090d7686f4c" width="100%" alt="Front Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Front Side View
        </div>
      </td>
      <!-- SPACER FOR GITHUB MOBILE DEGRADATION -->
      <td width="2%">&nbsp;</td>
      <!-- BACK SIDE CARD -->
      <td align="center" valign="top" width="50%" style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.05);">
        <img src="https://github.com/user-attachments/assets/01a76375-cd6b-42a0-951b-603d2630b545" width="100%" alt="Back Side View" style="border-radius: 6px;" />
        <div style="margin-top: 12px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 13px; color: #57606a; font-weight: 600; text-transform: uppercase; letter-spacing: 0.5px;">
          ▲ Back Side View
        </div>
      </td>
    </tr>
  </table>
</div>
</div>


<div align="center">
  <h2> Bill of Materials </h2>
</div>

| Name | Purpose | Qty | Total (USD) | Link | Distributor |
| :--- | :--- | :---: | :---: | :---: | :--- |
| PCB Board | The main Board | 5 | 2.10 | [jlcpcb](https://jlcpcb.com) | jlcpcb |
| USB-A male connector (MOLEX 48037-0001) | For the connector | 10 | 0.95 | [flyrobo](https://www.flyrobo.in/usb-type-4-pin-male-connector-socket?tracking=ads&srsltid=AfmBOophN-P9nD74dwqi0C-oFKkGJusqnoVQ49TIJ7Mypo4yTeV0mhCgyZ8) | flyrobo |
| Pin Headers (2x5) | For the connector | 5 | 0.24 | [robu](https://robu.in/product/1-month-warranty-921/) | robu |
| ATTINY13A-PU-MICROCHIP | The main chip | 3 | 5.71 | [robu](https://robu.in/product/attiny13a-pu-microchip-8-bit-mcu-low-power-high-performance-avr-attiny-family-attiny13-series-microcontrollers-avr/) | robu |
| 8 Pin DIP IC Socket Base Adaptor | For the chip | 5 | 0.26 | [robu](https://robu.in/product/8-pin-dip-ic-socket-base-adaptor-pack-of-10/) | robu |
| AMS1117 SMD voltage regulator | For Power control | 10 | 0.85 | [robu](https://robu.in/product/ams1117-3-3v-1a-sot-223-voltage-regulator-ic-pack-of-5-ics/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWeFunRL4eOrQvteNCIPCpvtP&gclid=Cj0KCQjwr4jSBhCSARIsAOX1E-LzS-G1lXeBRDXJ5HAJ51iWCYA7cqD56WnAvNN4MPlpvitz_v-2KbQaAvZoEALw_wcB) | robu |
| 1k Ohm 0.5W (moq 10) | resistor (for USB) | 10 | 0.11 | [robu](https://robu.in/product/1k-ohm-0-5w-metal-film-resistor-pack-of-50/) | robu |
| 68Ω (moq 10) | resistor (for USB) | 10 | 0.12 | [robu](https://robu.in/product/68-ohm-1w-metal-film-resistor-pack-of-40/) | robu |
| SMD 1206 LED (moq 10 ) | The main led | 10 | 0.20 | [robu](https://robu.in/product/1206-surface-mount-led-orange-50-pcs/) | robu |
| 470Ω (moq 10) | For the leds | 10 | 0.11 | [robu](https://robu.in/product/470-ohm-0-25w-metal-film-resistor-pack-of-100/?gad_source=1&gad_campaignid=17427802703&gbraid=0AAAAADvLFWeFunRL4eOrQvteNCIPCpvtP&gclid=Cj0KCQjwr4jSBhCSARIsAOX1E-IUyQc4-tC1BtG_hmUfrMOzM83BJ4yaenllbA7nt-rOSE-xktnRRhgaApbSEALw_wcB) | robu |


<div align="center">
  <table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; max-width: 600px;">
    <tr>
      <td style="background: #ffffff; border: 1px solid #d0d7de; border-radius: 12px; padding: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.05); font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif;">
        <div style="font-size: 16px; font-weight: 600; color: #24292f; margin-bottom: 12px; border-bottom: 1px solid #d0d7de; padding-bottom: 8px;">
           Final Summary Title
        </div>
        <table width="100%" border="0" style="border-collapse: collapse; font-size: 14px; color: #57606a;">
          <tr>
            <td style="padding: 4px 0;">Component Subtotal:</td>
            <td align="right" style="font-weight: 500; color: #24292f;">$10.65</td>
          </tr>
          <tr>
            <td style="padding: 4px 0;">Shipping Cost(incl. PCB):</td>
            <td align="right" style="font-weight: 500; color: #24292f;">$10.92</td>
          </tr>
          <tr>
            <td style="padding: 4px 0; padding-bottom: 8px;">Tax:</td>
            <td align="right" style="font-weight: 500; color: #24292f;">$1.5</td>
          </tr>
          <tr style="border-top: 1px dashed #d0d7de;">
            <td style="padding: 12px 0 0 0; font-weight: 600; color: #24292f; font-size: 15px;">Net Total Cost:</td>
            <td align="right" style="padding: 12px 0 0 0; font-weight: bold; color: #2da44e; font-size: 18px;">$23.07</td>
          </tr>
          <tr>
            <td style="padding: 2px 0 0 0; font-size: 11px; color: #8c959f;">Projected Budget Allocation:</td>
            <td align="right" style="padding: 2px 0 0 0; font-weight: 500; font-size: 12px; color: #8c959f;">$24</td>
          </tr>
        </table>
      </td>
    </tr>
  </table>
</div>

---

**Project Under Hack Club**
