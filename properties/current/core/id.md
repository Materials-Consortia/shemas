# ID (property)
This page documents an [OPTIMADE](https://www.optimade.org/) [Property Definition](https://schemas.optimade.org/#definitions). See [https://schemas.optimade.org/](https://schemas.optimade.org/) for more information.

**ID: [`https://schemas.optimade.org/properties/v1.2.0/core/id`](https://schemas.optimade.org/properties/v1.2.0/core/id)**  
**Definition name:** `id`

**Property name:** ID  
**Description:** A unique string referencing a specific entry in the database.  
**Type:** string  

**Requirements/Conventions:**

- Taken together, the ID and entry type MUST uniquely identify the entry.
- Reasonably short IDs are encouraged and SHOULD NOT be longer than 255 characters.
- IDs MAY change over time.

**Examples:**

- `db/1234567`
- `cod/2000000`
- `cod/2000000@1234567`
- `nomad/L1234567890`
- `42`

**Formats:** [[JSON](id.json)] [[MD](id.md)]

**JSON definition:**

``` json
{
    "$id": "https://schemas.optimade.org/properties/v1.2.0/core/id",
    "title": "ID",
    "x-optimade-type": "string",
    "x-optimade-definition": {
        "kind": "property",
        "version": "1.2.0",
        "format": "1.2",
        "name": "id"
    },
    "type": [
        "string"
    ],
    "description": "A unique string referencing a specific entry in the database.\n\n**Requirements/Conventions:**\n\n- Taken together, the ID and entry type MUST uniquely identify the entry.\n- Reasonably short IDs are encouraged and SHOULD NOT be longer than 255 characters.\n- IDs MAY change over time.",
    "examples": [
        "db/1234567",
        "cod/2000000",
        "cod/2000000@1234567",
        "nomad/L1234567890",
        "42"
    ],
    "x-optimade-unit": "inapplicable",
    "$schema": "https://schemas.optimade.org/meta/v1.2.0/optimade/property_definition.md"
}
```