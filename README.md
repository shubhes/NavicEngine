# NavicEngine

Welcome to the Diesel Engine Fault Diagnosis Dataset repository- **NavicEngine**! This repository contains experimental data collected from an inline 6-cylinder Navistar production DT diesel engine for the purpose of fault diagnosis and performance analysis. The dataset provides valuable insights into the behavior of the engine under various operating conditions and simulated faults in the fuel injector and injection system.

# Table of Contents

**Experimental Setup**

**Data Collection**

**Design of Experiments**

**Dataset Contents**

**Usage**

**Citation**

**License**

# Experimental Setup

The experimental setup involved utilizing an inline 6-cylinder 7.6 L Navistar production DT diesel engine provided by Pure Power Technologies, Inc. The engine was equipped with overhead valves, electro-hydraulic fuel injectors, and a dual-staged turbocharger. Various sensors were strategically installed to measure critical parameters such as airflow rate, fuel flow rate, fuel rail pressure, intake and exhaust pressure, and temperatures at different locations along the intake and exhaust flow paths. These sensors enabled comprehensive data collection to analyze the engine's performance and detect potential cylinder faults.

# Data Collection

Data collection was performed using a combination of tools and systems, including an active dynamometer, the AVL PUMA testbed automation system, and the INCA software for engine control and calibration. The dataset includes two types of files for each operating condition:

1. **ECU Save-File:** This file contains data from approximately 100 real and virtual sensors monitored by the ECU. The data was collected at a rate of once per engine cycle.

2. **PUMA Test Cell Automation Save-File:** This file provides information on test cell conditions such as temperatures, pressures, and flow rates. The data was collected at a sample rate of 10 Hz.

# Design of Experiments

The dataset was generated using a structured experimental design at various engine speeds (1000, 1200, 1400, and 1600 RPM). Three types of potential faults related to the fuel injector or injection system were introduced:

1. Variation in Injection Duration: The injection duration of a single cylinder was increased or decreased from the nominal ECU value. This simulates injector failure scenarios caused by factors such as injector deposits, eroded injector nozzle holes, or solenoid coil/command signal anomalies.

2. Start of Injection: The injection timing of one of the cylinders was slightly perturbed compared to the ECU-commanded signal.

3. Injection Pressure Fault: The fuel pressure set-point was adjusted from the ECU command.

# Dataset Contents

1. **processed_PUMA.zip:** Zipped folder containing PUMA data.

2. **INCA files:** INCA files are the ones with 'INCA_' prefix attached.

# Usage

Researchers and practitioners in the field of engine diagnostics and fault analysis can utilize this dataset for various purposes, including:

*Developing and testing fault detection algorithms

*Validating and calibrating diagnostic models

*Investigating engine behavior under different operating conditions

# Citation

**BibTex:**

@misc{shubhesN96:online,

author = {},

title = {shubhes/NavicEngine},

howpublished = {\url{https://github.com/shubhes/NavicEngine}},

month = {},

year = {},

note = {(Accessed on 08/18/2023)}

}

# License

This dataset is provided under the Creative Commons **Attribution-NonCommercial-ShareAlike 4.0 International License**. Please review the license terms before using the dataset for any purpose other than non-commercial research and educational activities.

For more information, contact **shubhes@g.clemson.edu**.
