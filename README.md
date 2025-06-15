# PSA_TU_Custom_ECU

This project aims to create documentation and a custom PCB based on the **Seepduino** project, to develop a **plug-and-play (PnP) ECU** for the **PSA TU engine family**.

The goal is to offer an affordable and open hardware solution tailored for enthusiasts, tuners, and developers working with Peugeot and Citroën TU-series engines.

---

## Development Status

Currently, development is focused on the **TU5J** engine, as I am working with a Peugeot 306 featuring the **TU5J (1.6L 8V)** engine.

I'm also planning to swap in a **TU5JP4 (1.6L 16V)**, which is known for better airflow and higher performance potential. This makes it a more capable base for tuning and further ECU development.

For now, the ECU will be based on simple hardware like the Mega 2560 Pro, but the end goal is to design a full standalone management board (SMB) using surface-mount components and a dedicated microcontroller (MCU).

---

## Harware 

The hardware design will be based on the proven components from the **Speeduino** project. The aim is to create a custom PCB around these parts to suit PSA TU engines in a plug-and-play format.

- Mega 2560 Pro (MCU devlopement board)

---
## ECU List for TU5J and TU5JP4

Below is a list of common ECUs found in PSA TU5J and TU5JP4 engines, which will guide compatibility and wiring design for this project:

| ECU Model          | Engine Type     | Notes                                  |
|--------------------|-----------------|---------------------------------------|
| Siemens SID803     | TU5J 1.6L 8V    | Used in early Peugeot 306 models      |
| Bosch ME7.4.5      | TU5JP4 1.6L 16V | Supports multi-point fuel injection |
| Valeo ECU (Various) | TU5J / TU5JP4  | Found in some Citroën models           |

> **Note:** These ECUs differ in their male header pin configurations, which affects wiring and connector compatibility. The custom PCB design will accommodate these differences for plug-and-play integration.

This list will be updated as testing and research progresses.

---
## ECU connector

#### M154 ECU 55 PIN
This connector is widely used by BOSCH ECUs, such as the BOSCH 0 261 203 912 (MP5.2) used with the TU engine.
![alt text](https://github.com/edenbwt/PSA_TU_Custom_ECU/blob/main/connector/IMG_5122-900x1200.jpg?raw=true)

#### BOSCH ME7.2, ME7.3, MP7.2, MP7.3
Those ECUs use a different type of connector header, but it's pretty hard to find. I'll do more research to identify the correct header pin, as it's likely to be needed for the TU5JP4 swap.

---
## Wiring Diagrams

As for the wiring, special thanks to **Sylvanos Motorsport** for sharing his research on the TU engine in the Citroën Xsara.  
Be sure to follow him on YouTube for top-tier car content:  
 [Sylvanos Motorsport](https://www.youtube.com/@Sylvanos) – an absolute legend in the community!


---

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You are free to:
- Use, modify, and share the files
- Not use them for commercial purposes

All derivatives must be shared under the same license, with proper attribution.

For commercial licensing inquiries, contact:  
**carl.guihot.pr@gmail.com**

 Full license text: [LICENSE.txt](./LICENSE.txt)  
 License details: [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

---

## Notes

- This project is in early development.
- Contributions, suggestions, and feedback are welcome — feel free to open an issue or start a discussion.

