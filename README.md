
# MAST Hackathon Project
Shane Abbott, Justin Amaya, Tyler Marleton, Christian White, Karla "Kenny" Madrigal

## Overview
[Project overview and goals to be added]

## Components

### 1. Patient Monitoring Device
Strapped onto the patient as a harness, monitoring vitals such as heart rate, blood pressure, temperature, etc. Would transmit this information.

### 2. Ambulance Repeater Device
Amplifies transmissions from the patient monitoring device to nearby hospitals.
This is also the data entry point for EMS personnel to add notes and or amplifying information (google that for more info on why it’s important, ie preexisiting conditions, physical description of pt, etc.).
It is also capable of pinging the hospital transceiver nodes for open beds and/or other qualifying information and services.
This will be our longest range device, so maximum wattage is desired to increase range and power through urban rf and physical environments.

### 3. Hospital Transciever Unit
Located in the hospital, possibly near the radio equipment (often found near the roof to coordinate with air ambulances and other medical aircraft).
This device should have excellent RX capabilities, but would still need to send out occasional pings with data on the hospitals available services and beds.

_Kenny: Question, could a filtering system allow doctors to subscribe to patient updates in real-time, receiving only information relevant to their assigned cases? Also, how do cases get assigned? I doubt whether any of these questions are within the scope of our project, and I think we're better off focusing on the existing components._


## Project Structure
I'd like for each project inside each directory (electrical/firmware/assembly) to have its own `DECISIONS.md` so we can keep track of... decisions.

I've initialized KiCad and PlatformIO projects in the electrical/firmware directories. Mech team (Christian, Justin, Shane) can decide how they want to structure the assembly directory.

```
├── patient-monitoring-device/
│   ├── electrical
│   ├── firmware
│   ├── assembly
│   └── DECISIONS.md
├── ambulance-repeater/
│   ├── electrical
│   ├── firmware
│   ├── assembly
│   └── DECISIONS.md
├── hospital-transciever/
│   ├── electrical
│   ├── firmware
│   ├── assembly
│   └── DECISIONS.md
│   
└── README.md
```

## Getting Started

### Prerequisites
- PlatformIO is an extension for VSCode. Feel free to check out [this video on YouTube](https://www.youtube.com/watch?v=PYSy_PLjytQ)

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## TODO

- [ ] Define clear project outcome and success criteria
- [ ] [Add additional tasks]
