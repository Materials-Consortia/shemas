# gray, Gy (unit)

This page documents an [OPTIMADE](https://www.optimade.org/) [Unit Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/defs/v1.2/units/si/general/gray`](https://schemas.optimade.org/defs/v1.2/units/si/general/gray.md)**  
**Definition name:** `gray`

**Unit name:** gray  
**Latin symbol:** Gy  
**Display symbol:** Gy  
  
**Description:** A unit for absorbed dose of ionizing radiation equal to m²·s⁻² using the current, or one of the historical, definitions of the SI units.

"The 15th Conférence Générale des Poids et Mesures, [...] adopts the following special name for the SI unit of ionizing radiation: gray, symbol Gy, equal to one joule per kilogram." [15th CGPM Meeting (1975)]

The gray was defined at the 15th CGPM Meeting in 1975, and implicitly redefined via the redefinition of the meter at the 17th CGPM Meeting in 1983, resolution 1.

This is a generalized definition taken to reference the current, or one of the historical, SI unit definitions.
This definition is intended for situations when it is not possible to be more precise, e.g., in contexts where data have been collected that uses different historical SI definitions.

**Resources:**

- [Definition at the 15th CGPM Meeting (1975)](https://www.bipm.org/en/committees/cg/cgpm/15-1975)
- [Redefinition of the metre at the 17th CGPM meeting (1983), resolution 1](https://www.bipm.org/en/committees/cg/cgpm/17-1983/resolution-1)
- [Wikipedia article describing the unit](https://en.wikipedia.org/wiki/Gray_(unit))


**Formats:** [[JSON](gray.json)] [[MD](gray.md)]

**JSON definition:**

``` json
{
    "$schema": "https://schemas.optimade.org/meta/v1.2/optimade/physical_unit_definition.md",
    "$id": "https://schemas.optimade.org/defs/v1.2/units/si/general/gray",
    "title": "gray",
    "symbol": "Gy",
    "display-symbol": "Gy",
    "description": "A unit for absorbed dose of ionizing radiation equal to m\u00b2\u00b7s\u207b\u00b2 using the current, or one of the historical, definitions of the SI units.\n\n\"The 15th Conf\u00e9rence G\u00e9n\u00e9rale des Poids et Mesures, [...] adopts the following special name for the SI unit of ionizing radiation: gray, symbol Gy, equal to one joule per kilogram.\" [15th CGPM Meeting (1975)]\n\nThe gray was defined at the 15th CGPM Meeting in 1975, and implicitly redefined via the redefinition of the meter at the 17th CGPM Meeting in 1983, resolution 1.\n\nThis is a generalized definition taken to reference the current, or one of the historical, SI unit definitions.\nThis definition is intended for situations when it is not possible to be more precise, e.g., in contexts where data have been collected that uses different historical SI definitions.",
    "compatibility": [
        "https://schemas.optimade.org/units/v1.2/si/1975/named/gray",
        "https://schemas.optimade.org/units/v1.2/si/1983/named/gray"
    ],
    "resources": [
        {
            "relation": "Definition at the 15th CGPM Meeting (1975)",
            "resource-id": "https://www.bipm.org/en/committees/cg/cgpm/15-1975"
        },
        {
            "relation": "Redefinition of the metre at the 17th CGPM meeting (1983), resolution 1",
            "resource-id": "https://www.bipm.org/en/committees/cg/cgpm/17-1983/resolution-1"
        },
        {
            "relation": "Wikipedia article describing the unit",
            "resource-id": "https://en.wikipedia.org/wiki/Gray_(unit)"
        }
    ],
    "defining-relation": {
        "base-units": [
            {
                "symbol": "m",
                "id": "https://schemas.optimade.org/units/v1.2/si/general/metre"
            },
            {
                "symbol": "s",
                "id": "https://schemas.optimade.org/units/v1.2/si/general/second"
            }
        ],
        "base-units-expression": "m^2*s^-2"
    },
    "x-optimade-definition": {
        "kind": "unit",
        "format": "1.2",
        "version": "1.2.0",
        "name": "gray"
    }
}
```