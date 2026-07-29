# Patent Architecture

[Main README](README.md) | [한국어](README_KR.md) | [中文](README_ZH.md)

## 1. Portfolio structure

The Cools Thermally Active Photonic Substrate portfolio is organized around one parent architecture and six orthogonal extension axes.

```text
Parent architecture
Alumina-based buried insulator + thermally conductive handler
        │
        ├─ Single-crystal sapphire BOX recovery
        ├─ Region-specific AAO porosity
        ├─ Variable thermal-conductance interlayer
        ├─ Optical/electrical partition + CTE-matched THV
        ├─ Mid-IR Si₃N₄ dual-cladding substrate
        └─ InP-on-SiC automotive LiDAR platform
```

The portfolio does not treat these as isolated inventions. Each extension changes a different design axis while remaining compatible with the common substrate stack.

---

## 2. Parent architecture

### Alumina-based buried insulator and thermally conductive handler

**Technical axis:** replace the conventional SiO₂ BOX with an alumina-based buried insulator and place it on a thermally conductive handler.

**Protected system concept:**

- photonic device layer;
- alumina-based BOX including sapphire, crystalline alumina, amorphous alumina or AAO;
- interface bonding layer;
- thermally conductive handler including RBSC, SiC, AlN or diamond composite;
- simultaneous optical-cladding and thermal-pathway function in the BOX;
- integration of substrate, interposer, heat-spreader and cooling-interface functions in the handler.

**Strategic significance:** this is the platform-level claim set from which the remaining inventions branch.

---

## 3. Orthogonal child-IP axes

### IP-1 — Repeated Smart-Cut recovery of single-crystal sapphire BOX

**Technical axis:** material utilization and scalable supply of single-crystal sapphire thin films.

**Key elements:**

- buried fragile plane in a sapphire donor;
- separation of a micrometre-scale sapphire film;
- recovery and surface regeneration of the remaining donor;
- repeated recovery cycles;
- use of the recovered film as the BOX on a thermally conductive handler.

**Commercial role:** converts a bulk sapphire crystal from a one-wafer material into a repeatable thin-film source.

---

### IP-2 — Region-specific porosity in an AAO BOX

**Technical axis:** spatially programmable optical, elastic and thermal properties.

**Key elements:**

- AAO as the buried insulator;
- different porosity in routing, modulator, filter and TOPS regions;
- region-dependent effective refractive index;
- region-dependent elastic modulus and stress compliance;
- differentiated anodization voltage, current density, masking or microelectrode control.

**Commercial role:** enables one substrate to support multiple photonic functions without forcing one BOX specification across the entire die.

---

### IP-3 — Variable thermal-conductance interlayer

**Technical axis:** time-domain control of heat transfer between the BOX and handler.

**Key elements:**

- a controllable thermal interface beneath selected photonic regions;
- low-conductance state for thermal confinement;
- high-conductance state for reset or heat removal;
- synchronization with modulator state, average-power envelope or TOPS control;
- phase-change, microcontact, fluidic or piezoelectric implementations.

**Commercial role:** transforms the substrate from a fixed thermal stack into a dynamically operated thermal circuit.

---

### IP-4 — Optical/electrical region partition with CTE-matched THV

**Technical axis:** photonic/electronic co-integration and vertical electrical connection through a non-silicon handler.

**Key elements:**

- planar partition between optical and electrical regions;
- preservation of optical BOX in the photonic region;
- replacement of the BOX by an electrical insulating support in the electronic region;
- through-handler via penetrating RBSC, SiC, AlN or another handler;
- CTE-matched ceramic or composite via body;
- conductive core or liner separated from the mechanical stress-bearing body;
- direct connection to backside redistribution without a separate silicon interposer.

**Commercial role:** removes the assumption that photonics and electronics must be assembled on a separate silicon interposer.

---

### IP-5 — Mid-IR Si₃N₄ dual-cladding photonic substrate

**Technical axis:** wavelength expansion beyond conventional SiO₂-limited photonics.

**Key elements:**

- Si₃N₄ waveguide core;
- alumina-based lower cladding/BOX;
- alumina-based or region-selected upper cladding;
- region-specific thickness for 1.55 μm and 2–5 μm operation;
- integrated communication and mid-infrared regions;
- gas sensing, spectroscopy and free-space optical applications.

**Commercial role:** expands the common substrate platform from telecom photonics into sensing and spectroscopy.

---

### IP-6 — InP thin film on a SiC heat-dissipating LiDAR platform

**Technical axis:** III–V optical function combined with a mechanically and thermally stable automotive platform.

**Key elements:**

- transferred InP-based III–V optical thin-film stack;
- SiC-based supporting and heat-spreading platform;
- 1.5 μm-class laser and optional detector integration;
- coherent FMCW optical paths and balanced detection;
- optical phased-array implementation;
- donor reuse and reduced InP material consumption;
- package-base and optical-alignment-reference integration.

**Commercial role:** connects the substrate platform to automotive coherent and solid-state LiDAR.

---

## 4. Combination matrix

| Combination | Resulting architecture |
|---|---|
| Parent + IP-1 | Sapphire-BOX photonic substrate with repeated donor reuse |
| Parent + IP-2 | Spatially programmable optical/thermal BOX |
| Parent + IP-3 | Time-programmable thermal substrate |
| Parent + IP-4 | Photonic/electronic co-integrated substrate without separate Si interposer |
| Parent + IP-5 | Thermally managed telecom and mid-IR photonics on one platform |
| Parent + IP-6 | Heat-spreading III–V automotive photonic module |
| IP-2 + IP-3 | Spatial and temporal control of thermal conductance |
| IP-1 + IP-4 | Sapphire optical region with CTE-matched vertical electrical fan-out |
| IP-2 + IP-5 | Region-specific AAO optimized for multi-wavelength photonics |
| IP-3 + IP-6 | Dynamically managed thermal path beneath LiDAR source or phase array |

---

## 5. Detectable structural features

Depending on the implementation, product-level analysis may identify combinations of:

- alumina-based BOX between the photonic layer and non-silicon handler;
- sapphire thin-film BOX with donor-splitting surface characteristics;
- regionally different AAO pore fraction or effective refractive index;
- localized variable thermal-conductance cells beneath selected devices;
- mechanical support frames surrounding variable-contact or fluidic regions;
- optical/electrical region boundary trenches;
- a THV containing a CTE-matched ceramic body and a distinct conductive core or liner;
- region-specific BOX thickness or upper-cladding material;
- transferred InP-based III–V thin film on a SiC-family support.

These features support both manufacturing control and technical identification of the implemented architecture.

---

## 6. Disclosure boundary

This document describes the patent architecture at system level. It does not provide all process windows, interface activation conditions, surface preparation details, defect-control methods, alignment tolerances or partner-specific manufacturing recipes.

Patent titles and technical summaries are presented for portfolio navigation and collaboration discussions. The legal scope of each invention is defined only by its filed claims and applicable prosecution history.
