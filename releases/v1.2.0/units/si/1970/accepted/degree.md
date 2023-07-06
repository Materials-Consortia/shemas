# degree, ° (unit)

This page documents an [OPTIMADE](https://www.optimade.org/) [Unit Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/defs/v1.2/units/si/1970/accepted/degree`](https://schemas.optimade.org/defs/v1.2/units/si/1970/accepted/degree)**  
**Definition name:** `degree`

**Unit name:** degree  
**Latin symbol:** degree  
**Display symbol:** °  
  
**Description:** A unit of plane and phase angle where a full circle is 360 degrees, which is equivalent to pi/180 rad, with rad defined according to the 1960 SI units.

The degree appear in the International System of Units (SI), 1th ed. (1970) defined as "1° = (pi/180) rad".

The International System of Units (SI), 1th ed. (1970) categorizes the unit as "Units in use with the International System."
The International System of Units (SI), 7th ed. (1998) adds as a footnote: "ISO 31 recommends that the degree be subdivided decimally rather than using the minute and second."
The International System of Units (SI), 8th ed. (2006) further adds to that footnote: "For navigation and surveying, however, the minute has the advantage that one minute of latitude on the surface of the Earth corresponds (approximately) to one nautical mile."
The International System of Units (SI), 9th ed. (2019) replaces the footnote with: "For some applications such as in astronomy, small angles are measured in arcseconds (i.e. seconds of plane angle), denoted as or ′′, or milliarcseconds, microarcseconds and picoarcseconds, denoted mas, μas and pas, respectively, where arcsecond is an alternative name for second of plane angle."
The formulation "denoted as or ″" is reproduced here faithfully from the source and suggests an alternate symbol may have been omitted due to a typographical error.
It is not clear what alternate symbol was intended to be referenced.

**Resources:**

- [Definition in the International System of Units (SI), 9th Edition](https://www.bipm.org/en/publications/si-brochure)
- [Wikipedia article describing the unit](https://en.wikipedia.org/wiki/Degree_(angle))


**Formats:** [[JSON](degree.json)] [[MD](degree.md)]

**JSON definition:**

``` json
{
    "$schema": "https://schemas.optimade.org/meta/v1.2/optimade/physical_unit_definition.md",
    "$id": "https://schemas.optimade.org/defs/v1.2/units/si/1970/accepted/degree",
    "title": "degree",
    "symbol": "degree",
    "display-symbol": "\u00b0",
    "description": "A unit of plane and phase angle where a full circle is 360 degrees, which is equivalent to pi/180 rad, with rad defined according to the 1960 SI units.\n\nThe degree appear in the International System of Units (SI), 1th ed. (1970) defined as \"1\u00b0 = (pi/180) rad\".\n\nThe International System of Units (SI), 1th ed. (1970) categorizes the unit as \"Units in use with the International System.\"\nThe International System of Units (SI), 7th ed. (1998) adds as a footnote: \"ISO 31 recommends that the degree be subdivided decimally rather than using the minute and second.\"\nThe International System of Units (SI), 8th ed. (2006) further adds to that footnote: \"For navigation and surveying, however, the minute has the advantage that one minute of latitude on the surface of the Earth corresponds (approximately) to one nautical mile.\"\nThe International System of Units (SI), 9th ed. (2019) replaces the footnote with: \"For some applications such as in astronomy, small angles are measured in arcseconds (i.e. seconds of plane angle), denoted as or \u2032\u2032, or milliarcseconds, microarcseconds and picoarcseconds, denoted mas, \u03bcas and pas, respectively, where arcsecond is an alternative name for second of plane angle.\"\nThe formulation \"denoted as or \u2033\" is reproduced here faithfully from the source and suggests an alternate symbol may have been omitted due to a typographical error.\nIt is not clear what alternate symbol was intended to be referenced.",
    "standard": {
        "name": "gnu units",
        "version": "3.15",
        "symbol": "degree"
    },
    "resources": [
        {
            "relation": "Definition in the International System of Units (SI), 9th Edition",
            "resource-id": "https://www.bipm.org/en/publications/si-brochure"
        },
        {
            "relation": "Wikipedia article describing the unit",
            "resource-id": "https://en.wikipedia.org/wiki/Degree_(angle)"
        }
    ],
    "defining-relation": {
        "base-units": [
            {
                "symbol": "pi",
                "id": "https://schema.optimade.org/units/constants/math/pi"
            },
            {
                "symbol": "rad",
                "id": "https://schema.optimade.org/units/si/2019/named/radian"
            }
        ],
        "base-units-expression": "pi*rad",
        "scale": {
            "denomenator": 180
        }
    },
    "x-optimade-definition": {
        "kind": "unit",
        "format": "1.2",
        "version": "1.2.0",
        "name": "degree"
    }
}
```