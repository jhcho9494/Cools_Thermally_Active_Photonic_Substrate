# Cools Thermally Active Photonic Substrate

## Strategic relevance to Broadcom CPO and dense TOPS

**Dense TOPS arrays contain a structural contradiction: the phase shifter needs thermal isolation while heating, but strong thermal conduction while resetting.**

Cools resolves this at the architecture level:

- the low-conductivity path dominates during heating and phase holding;
- the high-conductivity path dominates during cooling, reset and idle;
- power efficiency and response speed are no longer forced into one fixed-path compromise;
- denser arrays can reduce thermal crosstalk and control overhead; and
- a CPO platform owner can capture the value through lower power, faster reconfiguration and higher optical-engine density.

Broadcom has the optical-engine and system-architecture depth to assess this directly from the patent map and implementation structure.

**Paired assembly architecture:** [Photonic Thermal Clutch for zero-thermal-budget EIC–PIC bonding](https://github.com/jhcho9494/Cools_CPO_Zero_Thermal_Budget_Bonding)


[한국어](README_KR.md) | [中文](README_ZH.md) | [Patent Architecture](PATENT_PORTFOLIO.md) | [Public Notice](PUBLIC_NOTICE.md)

## The buried insulator is no longer only an optical cladding.
## It becomes a controlled thermal pathway to a thermally active handler.

**Cools Thermally Active Photonic Substrate** is a photonic-integrated-circuit substrate architecture that replaces the conventional fixed-function SiO₂ buried oxide with an **alumina-based buried insulator** and places it on a **high-thermal-conductivity handler** such as reaction-bonded silicon carbide (RBSC), sintered SiC, AlN or diamond composite.

The platform is designed to integrate optical confinement, heat extraction, mechanical support, electrical feedthrough, interposer functions and cold-plate coupling into one substrate stack.

---

## 1. The bottleneck in conventional photonic substrates

Conventional Photonics-SOI uses a silicon photonic device layer, a SiO₂ buried oxide (BOX) and a silicon handle wafer. The SiO₂ layer provides excellent optical isolation, but its low thermal conductivity creates a thermal bottleneck directly beneath modulators, photodetectors and thermo-optic phase shifters.

The result is a fixed trade-off:

- optical isolation versus heat extraction;
- thermo-optic efficiency versus reset speed;
- modulator thermal isolation versus removal of average self-heating;
- dense optical integration versus thermal crosstalk;
- photonic integration versus additional interposer and cooling layers.

Cools changes the role of the BOX and the handler simultaneously.

---

## 2. Core substrate architecture

```text
Photonic device layer
        ↓
Alumina-based buried insulator
(optical cladding + thermal pathway)
        ↓
Interface bonding layer
        ↓
Thermally conductive handler
(substrate + interposer + heat spreader + cooling interface)
```

### Alumina-based buried insulator

The buried insulator may include:

- single-crystal sapphire thin film;
- crystalline alumina;
- amorphous alumina;
- anodic aluminum oxide (AAO);
- a composite stack combining dense alumina and porous AAO.

Unlike conventional SiO₂ BOX, the alumina-based layer is designed to perform two functions in the same layer:

1. lower optical cladding and optical leakage suppression;
2. heat-transfer pathway from the photonic device layer to the handler.

### Thermally conductive handler

The handler may include RBSC, sintered SiC, CVD poly-SiC, AlN, diamond composite, AlSiC, Cu-Mo, Cu-W or graphite composite. It may perform multiple functions that are conventionally distributed among separate components:

- mechanical substrate;
- heat spreader;
- electrical or photonic interposer;
- package support;
- cold-plate interface.

---

## 3. Platform innovation map

### A. Repeatedly recovered single-crystal sapphire BOX

A single-crystal sapphire donor can be reused through repeated thin-film splitting cycles. Only a micrometre-scale sapphire film is consumed for each photonic substrate rather than a full-thickness sapphire wafer. The recovered sapphire film serves as the optical BOX while the external high-thermal-conductivity handler provides mechanical support and heat spreading.

### B. Region-specific AAO buried insulator

AAO porosity can be differentiated by region within one photonic substrate. Optical-routing, modulator, filter and thermo-optic phase-shifter regions can therefore receive different effective refractive index, elastic modulus and thermal conductance.

```text
Routing / filter region → stronger confinement
Modulator region        → balanced optical and thermal response
TOPS region             → tailored heat confinement and release
```

The substrate is no longer forced to use one BOX specification for every photonic function.

### C. Variable thermal-conductance interlayer

A variable thermal-conductance interlayer can be placed selectively between the BOX and handler beneath modulators or thermo-optic phase shifters.

- During phase shifting or phase holding: low thermal conductance confines heat locally.
- During reset, cool-down or idle: high thermal conductance releases stored heat into the handler.
- In modulator regions: conductance can be adjusted according to enable, burst, idle, average-power or temperature signals.

Possible mechanisms include phase-change materials, variable microcontacts, fluidic microchannels and piezoelectrically controlled contact pressure.

### D. Optical/electrical region partitioning with CTE-matched THV

A single substrate may be divided into optical and electrical regions.

- The optical region preserves the BOX for optical confinement.
- The electrical region replaces the optical BOX locally with an electrical insulating support layer.
- A through-handler via (THV) penetrates the high-thermal-conductivity handler.

The THV may combine a handler-matched ceramic or composite mechanical body with a conductive core or liner. Mechanical stress and electrical conduction are therefore assigned to different structural elements, enabling substrate-level photonic/electronic co-integration without a separate silicon interposer.

### E. Mid-infrared Si₃N₄ photonics

A Si₃N₄ waveguide core may be combined with alumina-based upper and lower cladding. This avoids the strong mid-infrared absorption associated with conventional SiO₂ cladding and BOX structures.

The architecture supports:

- 1.55 μm communication regions;
- 2–5 μm mid-infrared regions;
- region-specific BOX thickness and cladding material;
- integrated gas sensing, spectroscopy and free-space optical functions.

### F. InP-on-SiC automotive LiDAR

An InP-based III–V optical thin-film stack can be transferred onto a SiC-based heat-dissipating and supporting platform. The platform can integrate a 1.5 μm-class source, detector, optical waveguide, coherent FMCW receiver and optical phased array.

The concept targets simultaneous improvement of:

- source junction-temperature control;
- wavelength and linewidth stability;
- phase stability for FMCW and optical phased arrays;
- vibration and automotive thermal-cycle reliability;
- InP donor reuse and material efficiency.

---

## 4. From passive substrate to active system infrastructure

| Conventional photonic substrate | Cools thermally active substrate |
|---|---|
| BOX is primarily optical insulation | BOX is optical insulation and a designed thermal pathway |
| Thermal conductance is fixed | Thermal conductance can vary by region and time |
| One BOX specification across the die | Region-specific optical, elastic and thermal properties |
| Separate photonic die, EIC and interposer | Substrate-level photonic/electronic co-integration |
| Silicon handler requires additional cooling stack | High-conductivity handler can integrate spreading and cooling interfaces |
| Near-IR-centered platform | Near-IR, mid-IR and LiDAR extensions |

---

## 5. Application domains

- co-packaged optics (CPO);
- silicon and Si₃N₄ photonic integrated circuits;
- dense wavelength-division multiplexing;
- thermo-optic phase-shifter arrays;
- optical phased arrays;
- 1.55 μm coherent automotive LiDAR;
- mid-infrared gas and chemical sensing;
- integrated spectroscopy;
- optical computing and optical interconnects;
- quantum and nonlinear photonic systems.

---

## 6. Relationship to other Cools platforms

This repository represents the **photonic-substrate layer** of the broader Cools architecture.

- **Transferred electrical/optical overlay:** [Cools Package-Substrate-Less SystemBoard](https://github.com/jhcho9494/Cools_Package_Substrate_Less_SystemBoard)
- **CPO bonding architecture:** [Cools CPO Zero Thermal Budget Bonding](https://github.com/jhcho9494/Cools_CPO_Zero_Thermal_Budget_Bonding)
- **Sapphire optical-domain platform:** [Cools Sapphire Single Optical Domain Computing](https://github.com/jhcho9494/Cools_Sapphire_Single_Optical_Domain_Computing)
- **Sapphire quantum interconnect:** [Cools Sapphire Quantum Optical Interconnect](https://github.com/jhcho9494/Cools_Sapphire_Quantum_Optical_Interconnect)

Together, these technologies connect photonic materials, thermal control, electrical redistribution, optical routing and package-level integration.

---

## 7. Development and IP status

This repository provides an architecture-level public technical disclosure derived from a coordinated patent portfolio. It does not disclose every process recipe, tolerance, material-treatment condition or manufacturing know-how required for implementation.

Quantitative values stated in the underlying patent documents include design ranges, analytical estimates and proposed validation targets unless independently identified as measured data. Experimental, simulation and manufacturing validation will be performed with suitable substrate, photonics, packaging and equipment partners.

---

## Contact

**Cools**  
Jinhyun Cho, Founder & CEO  
Republic of Korea

Technical collaboration, substrate development, photonic foundry integration, equipment partnership and licensing discussions are welcome.
