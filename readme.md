# Jaycar Filament Swatches

A printable filament swatch system for cataloguing and displaying Jaycar Electronics filament colours and materials.

> **Disclaimer:** This is an independent project and is not affiliated with, endorsed by, or sponsored by Jaycar Electronics. Jaycar/Elegoo/Sunlu/Slic3D product names, colours, and product numbers are used only to identify the filaments represented by the swatches.

## About

Each swatch is designed to be printed using the filament it represents, providing a physical reference for comparing colours and materials.

The system uses printable trays to organise the swatches into a compact reference collection.

The collection may be expanded as additional Jaycar filament lines and colours become available.


![Colour collection as of 1/10/2026](https://github.com/CampbellFabrications/Jaycar-Filament-Swatches/blob/e08a98dbe06c7334d842ad76a958743b53a6c58b/Collection%20Preview.png)

## Files

### `Colour Insert.stl`

The primary printable filament swatch.

Print the insert using the filament being catalogued. The swatch includes the relevant Jaycar product number for identification.

The model is designed to print without modification using a standard FDM printing profile.

### `Trays/`

Printable trays for organising and displaying the completed swatches.

### `Colour_Swatch_Sign.pdf`

An A5 printable sign containing a QR code linking to the colour swatch insert.

### `Part Number Spool.3mf`

A .3mf file containing the outer spool with a modifier object that needs to be set to the part number of the insert colour being printed.

- I recommend setting the plate colour order to the text first, then the spool, as travel moves and colour bleed may affect the legibility of the part number.
- The use of a Skirt can help prime the text colour should extrusion issues present themselves between the prime/purge line and the object itself.

## Printing

The swatches are designed for straightforward FDM printing.

Recommended starting point:

- **Material:** Filament being catalogued
- **Layer height:** Default profile
- **Infill:** Default profile
- **Supports:** Not required
- **Brim:** Not required

Normal printer and filament profiles should be suitable.

## Colour Reference

The printed swatches are intended as a physical reference rather than a calibrated colour standard.

Actual appearance may vary due to:

- Printer
- Nozzle
- Layer height
- Printing temperature
- Filament batch
- Slicer settings
- Lighting

For colour/material comparison, the physical swatch should be treated as the reference.

## Source Files

The printable files in this repository are the released output of the project's CAD design process.

The original Fusion 360 source files are not currently included. Submit an issue if you would like access to the design source files.

The CAD design is still subject to development, including potential changes to:

- Multi-material printing support
- Part appearances and material definitions for slicer importing
- Fusion 360 timeline structure
- Reference tray designs
- Labelling and identification
- Support for future filament ranges

The source files may be released separately in the future.

## Contributions and Acknowledgements
- [Diggle's Filament Colour Swatches and generic trays](https://makerworld.com/en/models/209262-5g-mini-spool-filament-swatch-gridfinity)
- Jaycar Electronics Management - For allowing this project to continue thus far and allowing 'third-party' signage to be displayed to link to this project.