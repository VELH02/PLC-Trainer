# PLC-Trainer
This project consists of a trainer for Siemens Programmable Logic Controllers (PLC), developed for educational and training purposes. The system is designed to facilitate learning and practice in PLC programming.

## Components Used
- **Siemens 230RCo:** PLC without a display, programmable via cable [6ED1052-2FB00-0BA5]
- **Siemens Sirius 3RT1026-1A:** Three-phase relay
- **Indicator lights (Pilot lights) 120VAC:**
  - 2 Green lights
  - 1 Red light
  - 1 Amber light
- **Pushbuttons:**
  - 1 Green NO (Normally Open) pushbutton
  - 1 Red NC (Normally Closed) pushbutton
  - 1 Three-position selector switch (2 NO switches)
- 24 Banana plugs for connections
- Project box (nothing special): [LINK](https://www.amazon.com/-/es/Heyiarbeit-conexiones-proyectos-pulgadas-bricolaje/dp/B08X69B4L3/ref=sr_1_5?__mk_es_US=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=381M0VCN3GS2Y&dib=eyJ2IjoiMSJ9.hKKYKic5nFXL9zspsSnchp6GIupVcOE3sa0ocKo64LlOve4X0K2cV1d40aeLEP0L4xloja3ZREF-9xAugVYLpBU8GAjGl9BHhFARxGbPI9wyc24NoS58gq5DDTflZOgvfrYqT8dNRoo5Wm1jidZQBJa0OAI0foeOLdz0ceiUv-RqAMx6Fn4g0mjoQWeo-8G8WEXhvTdNpBHHTuPxA7vWYBqYneUyzj7uKXbZ_bDTFtO0ltJl-Opwb1iO-2PXz8iy5x3UwsdgNjj-FhkJ6bvenWGFRvtycR4UGmCnqM50wa8.Y0wA3HvHFxa6CJQejmwXyMT8_U2Y5sYNP0UV5q_vvE0&dib_tag=se&keywords=Caja%2bde%2bconexiones%2belectr%C3%B3nica%2bpara%2bproyectos,%2bde%2bmetal%2bazul&qid=1728872974&s=industrial&sprefix=caja%2bde%2bconexiones%2belectr%C3%B3nica%2bpara%2bproyectos,%2bde%2bmetal%2bazul,industrial,159&sr=1-5&th=1)

## Schematic
![Schematic](https://github.com/VELH02/PLC-Trainer/blob/main/Imagenes/Esquematico.png?raw=true)

## Result
![PLC Trainer Working](https://github.com/VELH02/PLC-Trainer/blob/main/Imagenes/Working.jpg?raw=true)

## Tips
1. Use a step drill bit that goes up to at least 22mm, like this one: ![Step](https://github.com/VELH02/PLC-Trainer/blob/main/Imagenes/Step.jpg?raw=true)
2. When opening the AC input hole, remember to get one with a power switch (unlike what I did); otherwise, you'll need another two- or three-position switch to turn the module on and off, as it's not ideal for it to always be on. ![AC Plug](https://github.com/VELH02/PLC-Trainer/blob/main/Imagenes/AC%20plug.jpg?raw=true)
3. It’s good practice to ground all metal parts of the box so that if a live wire becomes loose and electrifies a metal plate, it will short with the ground instead of with a student or user.

## CadeSimu
The schematic was made using CadeSimu.

Download link for CadeSimu [Link](https://cade-simu.com/).

The test programs were written in Ladder Logic in L.