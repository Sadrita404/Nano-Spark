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


