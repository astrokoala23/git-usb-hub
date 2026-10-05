<h1 align="center">
  Git USB Hub
</h1>
<p align="center">
  A basic 1-in 4-out USB hub in the shape of the Github logo, that double as a Github keychain.
</p>

<div align="center">
  <img width="891" height="321" alt="image" src="https://github.com/user-attachments/assets/71b1adb6-8a77-41e9-af58-cc391730c5bb" />
  <img width="421" height="437" alt="image" src="https://github.com/user-attachments/assets/d03ebe61-7a28-48d0-b22a-34de706086a4" />
  <img width="428" height="475" alt="image" src="https://github.com/user-attachments/assets/1329b3d9-7374-4f9c-8af5-b12bb786ef4d" />
  <img width="678" height="587" alt="image" src="https://github.com/user-attachments/assets/40f07cde-9cfb-4322-8e1f-2742a7b7dcef" />
</div>

<br>

## About Git USB Hub
The Git USB Hub is a 1-in 4-out USB hub that is shaped like the Github octocat.

Features:
- USB-C Input
- 2 USB-C & 2 USB-A output
- Decent size of ~7cm at largest

## Repository Structure
- `gerber`: Gerber files
- [Git_USB_Hub.epro](Git_USB_Hub.epro) - EasyEDA Pro Files


## Bill of Materials

| No. | Name                  | Quantity | Comment               | Designator               | Footprint                        | Value | Manufacturer Part     | Manufacturer    | Supplier Part | Supplier |
|-----|-----------------------|----------|-----------------------|--------------------------|----------------------------------|-------|-----------------------|-----------------|---------------|----------|
| 1   | 1uF                   | 8        | 1uF                   | C1,C2,C3,C4,C5,C6,C8,C10 | C0603                            | 1uF   |                       |                 |               |          |
| 2   | 100nF                 | 3        | 100nF                 | C7,C9,C11                | C0603                            | 100nF |                       |                 |               |          |
| 3   | 5.1K                  | 2        | 5.1K                  | R1,R2                    | R0603                            | 5.1K  |                       |                 |               |          |
| 4   | 56K                   | 4        | 56K                   | R3,R4,R5,R6              | R0603                            | 56K   |                       |                 |               |          |
| 5   | SL2.1s                | 1        | SL2.1s                | U1                       | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL |       | SL2.1s                | CoreChips(和芯润德) | C2684433      | LCSC     |
| 6   | TYPE-C 16PIN 2MD(073) | 3        | TYPE-C 16PIN 2MD(073) | USB1,USB2,USB3           | USB-C-SMD_TYPE-C-16PIN-2MD-073   |       | TYPE-C 16PIN 2MD(073) | SHOU HAN(首韩)    | C2765186      | LCSC     |
| 7   | 10.0 QHHTZB6.3        | 2        | 10.0 QHHTZB6.3        | USB4,USB5                | USB-A-TH_10.0QHHTZB6.3           |       | 10.0 QHHTZB6.3        | SHOU HAN(首韩)    | C668591       | LCSC     |


## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
