

#  Starbie

Starbie is a tiny motion-controlled digital pet: basically a desktop Tamagotchi with minimal gameplay buttons. Instead of pressing controls, you interact with it by physically moving the board.


## Circuit Design

The circuit schematic and PCB layout were designed using KiCad.

![Starbie Circuit Diagram](https://github.com/user-attachments/assets/329e47fb-0429-4ef8-8664-4f3258ea716c)

##  Casing Design

I designed a custom 3D-printed casing to house the electronics and give the project a finished form.

![Starbie Casing](https://github.com/user-attachments/assets/2f47eb87-2596-42f0-b5d4-61d5c0fc846f)

##  Why I Made It

I wanted to challenge myself to design a hardware project from scratch and combine electronics, PCB design, firmware, and 3D modelling.

## How To Use it

1.Powering On: Connect the board via USB-C to power the unit.

2. Setting the Alarm: Use the primary tactile buttons to adjust hours/minutes and enable the alarm.
   
3. Silencing: Press the snooze/dismiss button when the alarm sounds.

##  Challenges I Faced

Designing the PCB and creating a casing that fits the electronics required careful planning and design revisions. I also learned how to prepare manufacturing files for a custom PCB.

##  What I Learned

- Designing schematics and PCBs using KiCad.
- Creating a custom 3D-printed enclosure.

##  Bill of Materials (BOM)

| Component | Quantity | Supplier | Unit Cost | Total |
|---|---:|---|---:|---:|
| DHT11 sensor | 1 | [Circuit.pk](https://circuit.pk/product/227) | $1.00 | $1.00 |
| OLED display | 1 | [Circuit.pk](https://circuit.pk/product/606) | $3.61 | $3.61 |
| MPU6500 motion sensor | 1 | [Circuit.pk](https://circuit.pk/product/4431) | $1.73 | $1.73 |
| Cherry MX switches | 2 | [MegaTechMall](https://megatechmall.com/shop/electronic-devices/mechanical-keyboard-silent-switches-200pcs-dustproof-switches/) | $0.73 | $1.46 |
| Resistor | 1 | [Daraz.pk](https://www.daraz.pk/products/25-10k-ohm-14w-i186088466) | $0.16 | $0.16 |
| Breadboard | 1 | [Digilog.pk](https://digilog.pk/products/mb102-830-points-solderless-prototype-pcb-breadboard-high-quality-in-pakistan) | $1.01 | $1.01 |
| Estimated shipping | — | Various suppliers | — | $6.00 |
| **Grand Total** | | | | **$14.97** |

See [`BOM.csv`](BOM.csv) for the complete component list.

*Prices are estimates. Verify component names, quantities, and costs against the final design.*
