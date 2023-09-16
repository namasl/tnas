# TNAS - Thermal Noise Analysis Script

TNAS is a simple tool for analyzing electrical noise which functions well into the low-temperature/high-frequency regime (the primary reason it was written is the lack of such tools for cryogenic use).

When given a circuit netlist, the temperature of dissipative components, and the reference designator of a victim component, TNAS will display results such as the total noise spectrum, the fractional contribution of each component to the noise, the noise power flow across frequency, and thermal equilibrium temperatures.

At present the tool is fully functional, but completing the manual has been lagging. See [tnas_manual.pdf](https://github.com/namasl/tnas/blob/main/tnas_manual.pdf) for the latest partial writeup. The code itself is commented and should be understandable, but a higher level overview of usage is warranted.

## License

TNAS was originally written at IBM, and has been released under the [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
