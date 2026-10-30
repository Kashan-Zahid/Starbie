# Starbie

Starbie is a custom electronics project built around a designed PCB, firmware, and a 3D-printed enclosure. The project combines circuit design, component integration, embedded programming, and enclosure modelling into one compact device.

## Circuit Design

The circuit schematic and PCB layout were designed using KiCad. The schematic defines the electrical connections, while the PCB layout arranges the components and their connections on the board.

![Starbie Circuit Diagram](https://github.com/user-attachments/assets/329e47fb-0429-4ef8-8664-4f3258ea716c)

## Casing Design

I designed a custom 3D-printed enclosure to house and protect the electronics. The casing went through design revisions to improve its appearance and fit with the PCB.

![Starbie Casing](https://github.com/user-attachments/assets/2f47eb87-2596-42f0-b5d4-61d5c0fc846f)

## Why I Made It

I wanted to challenge myself to develop a hardware project from scratch and combine electronics, PCB design, firmware, and 3D modelling. This project gave me an opportunity to work through the process of turning a circuit design into a physical product.

## Features and Operation

- Custom PCB designed in KiCad.
- Electronic components integrated onto the board.
- Custom 3D-printed enclosure.
- Tactile buttons for user input.
- USB-C power connection, if supported by the final assembled design.

Refer to the final firmware and schematic for the exact functions supported by the completed device.

## Assembly Instructions

### 1. Review the design files

Open the KiCad schematic (`.kicad_sch`) and PCB layout (`.kicad_pcb`). Review the component positions, footprints, and electrical connections before assembly.

### 2. Prepare the PCB

Export the Gerber and drill files from KiCad if the board will be manufactured by a PCB fabrication service. Check the manufacturing outputs before submitting them.

### 3. Gather the components

Use the BOM to identify the required components, quantities, and package types. Confirm that each component matches the footprint and electrical specifications in the schematic.

### 4. Assemble the electronics

Place each component according to the PCB silkscreen, schematic, and component polarity markings. Solder the components that require soldering, checking for solder bridges and incorrect orientations.

### 5. Inspect the assembled board

Before applying power, inspect the solder joints and verify the power connections. Check for shorts between power and ground with a multimeter.

### 6. Install the firmware

Use the firmware files included in the repository and follow the programming instructions for the microcontroller used in the final design. Confirm that the firmware matches the hardware and required pin assignments.

### 7. Test the electronics

Power the board using its specified supply voltage. Test the display, sensors, buttons, and other connected components individually, then verify that they work together as intended.

### 8. Fit the enclosure

Place the tested PCB into the 3D-printed casing. Check the alignment of the display, buttons, connectors, and mounting points. Make any necessary adjustments before final assembly.

**Note:** These are general assembly steps. Exact soldering locations, firmware commands, pin assignments, and mounting instructions should be added from the final hardware and firmware files.

## Challenges I Faced

Designing the PCB and creating a casing that fits the electronics required careful planning and revisions. I improved the PCB layout after reviewing the earlier design and worked on redesigning the enclosure to achieve a better fit and appearance. Preparing manufacturing files also helped me understand how a digital PCB design becomes a physical board.

## What I Learned

- Designing electronic schematics and PCB layouts using KiCad.
- Organising components and checking footprints.
- Preparing PCB manufacturing files.
- Designing and revising a 3D-printed enclosure.
- Planning the integration of electronics, firmware, and physical components.

## Bill of Materials (BOM)

The following table lists the component prices previously recorded for the project. Prices and availability must be confirmed against the linked product listings before they are treated as verified current prices.

| Component | Quantity | Supplier | Unit price (USD) | Line total (USD) |
|---|---:|---|---:|---:|
| DHT11 temperature and humidity sensor | 1 | [Circuit.pk](https://circuit.pk/product/227) | $1.00 | $1.00 |
| OLED display | 1 | [Circuit.pk](https://circuit.pk/product/606) | $3.61 | $3.61 |
| MPU6500 motion sensor | 1 | [Circuit.pk](https://circuit.pk/product/4431) | $1.73 | $1.73 |
| Mechanical keyboard switches | 2 | [MegaTechMall](https://megatechmall.com/shop/electronic-devices/mechanical-keyboard-silent-switches-200pcs-dustproof-switches/) | $0.73 | $1.46 |
| 10 kΩ resistor | 1 | [Daraz.pk](https://www.daraz.pk/products/25-10k-ohm-14w-i186088466) | $0.16 | $0.16 |
| MB102 breadboard | 1 | [Digilog.pk](https://digilog.pk/products/mb102-830-points-solderless-prototype-pcb-breadboard-high-quality-in-pakistan) | $1.01 | $1.01 |
| **Component subtotal** | | | | **$8.97** |
| Shipping | — | Multiple suppliers | Not verified | Not verified |
| **Total** | | | | **$8.97 + actual shipping** |

The component subtotal is calculated from the recorded prices above; it is not a verified final purchase cost. The previous $6.00 shipping figure has not been independently confirmed and is therefore excluded from the total.

**Important:** The breadboard is a prototyping item, so confirm whether it belongs in the final project BOM or was only used during development. Also confirm that the listed components match the final PCB design.

See [`BOM.csv`](BOM.csv) for the component list.

## Editable 3D Design (Onshape)

The Starbie enclosure was designed using Onshape. I created and revised the 3D model to fit the electronics and provide a finished enclosure for the project.

The original editable CAD document is available here:

**[View Starbie's Editable 3D Design on Onshape](https://cad.onshape.com/documents/d6ad51c0185554a6a528b003/w/05fafd2a75e4a24dc14ee40b/e/c8ed782f1f7a7a6b0a75496d?renderMode=0&uiState=6ae42ee53693e84fc74a8607)**

The editable document allows others to inspect the original design and understand how the enclosure was modelled.
