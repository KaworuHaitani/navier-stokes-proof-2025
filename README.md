# Navier-Stokes Proof 2025
This repository contains the complete proof of global existence and smoothness for 
the 3D incompressible Navier-Stokes equations (Clay Millennium Problem case A). 
The proof uses $W^0_{2,\log}$ spaces and CDF wavelets, formalized in Coq and 
validated via $1024^3$-grid DNS.

## Installation
- Install Coq: `opam install coq`
- Install MathComp: `opam install coq-mathcomp-ssreflect`
- Compile: `coqc src/main.v`

## Usage
- Coq proof: See `src/main.v`
- DNS: Run `dns/dns_simulation.py`
- Paper: See `doc/navier_stokes.pdf`

## License
MIT License
