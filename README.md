# NVIDIA DGX Spark — 3D-Printed Modular Rack

**Modular PETG racks for 2, 3 or 4 NVIDIA DGX Spark computers.**

Designed by **Toro Tocho Reviews** in Fusion 360 for makers building compact local-AI clusters.

> **Important:** Print in **PETG, not PLA**. Sustained heat can deform PLA. Monitor temperatures and ensure that the DGX Spark ventilation openings remain unobstructed.

## Available designs

Three printable models are prepared:

| Configuration | STL filename | Approximate dimensions (X × Y × Z) |
|---|---|---|
| 2 DGX Spark | `DGX-Spark-Rack-2-Units.stl` | 166 × 144 × 203 mm |
| 3 DGX Spark | `DGX-Spark-Rack-3-Units.stl` | 166.4 × 144.4 × 270.9 mm |
| 4 DGX Spark | `DGX-Spark-Rack-4-Units.stl` | 166.4 × 144.4 × 324.4 mm |

*Dimensions assume millimeter units. Check print orientation and available build volume in your slicer.*

**STL files and the photo gallery are being prepared for upload.** The full release will include real photographs, CAD previews and downloadable models.

## Design and ventilation

The open honeycomb walls provide ventilation paths and help keep the rack compact. The units are closer together than I would ideally like: **my 3D printer was already at its maximum build volume**. If you have a larger printer, **increase the spacing between devices** to give air more room to circulate. It will be less compact but potentially easier to cool.

### Is an additional fan worthwhile?

I tested an optional fan configuration and saw only **about 3–4 °C lower temperatures** in my setup. I therefore recommend the **fanless version** for most users: simpler construction for a relatively modest measured improvement. Your results may differ.

### Why PETG instead of aluminum?

A properly engineered aluminum rack could spread heat much better **if designed with appropriate thermal contact**. However, aluminum fabrication could cost hundreds of dollars, whereas **my PETG printing cost was about US$15 per piece**. PETG is a much more accessible maker option.

## Power adapters

Multiple DGX Spark computers mean multiple bulky external power supplies. It would be useful if NVIDIA offered an **official, appropriately rated multi-output power supply** for two, three or four units. For now, use the approved power supply for each computer.

## Printing and safety notes

- **Material:** PETG recommended; avoid PLA.
- **Printer:** verify the model fits your machine before slicing.
- **Cooling:** keep manufacturer intake and exhaust vents clear.
- **Operation:** check temperatures, rack stability and any material deformation during sustained workloads.
- **Status:** personal maker design, not an official NVIDIA product or a certified enclosure.

## Future improvements

More spacing, better cable and power-adapter management, controlled cooling comparisons and possibly a hybrid aluminum construction.

## Creator

**Toro Tocho Reviews** — PC hardware, local AI, 3D printing and maker projects. Instagram / TikTok: **@toro_tocho**.

## License

This project uses **Creative Commons Attribution 4.0 International (CC BY 4.0)**. See [LICENSE](LICENSE) for the full terms.
