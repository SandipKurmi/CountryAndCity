### CountryAndCity
in this repo, i create a script to convert city and country in JSON structure
```
{
  Cuba: [
    "Havana",
    "Habana",
    "La Habana",
    "Matanzas",
    "Villa",
    "Bayamo",
    "Cienfuegos",
    "Santiago de Cuba",
    "HolguÃ­n",
    "Ciego de Ãvila",
    "Pinar del RÃ­o",
    "Sancti SpÃ­ritus",
    "CamagÃ¼ey",
    "Las Tunas",
    "GuantÃ¡namo",
    "Varadero",
  ],
  "Saint Helena": ["Tristan Da Cunha", "Jamestown"],
  "Christmas Island": ["Flying Fish Cove"],
  Ethiopia: ["Addis Ababa", "Awasa", "Jijiga"],
  "British Indian Ocean Territory": [""],
};
```

## convert the original JSON object to the desired format:

```
    {
        "country": "Cuba",
        "cities": [
            "Havana",
            "Habana",
            "La Habana",
            "Matanzas",
            "Villa",
            "Bayamo",
            "Cienfuegos",
            "Santiago de Cuba",
            "HolguÃ­n",
            "Ciego de Ãvila",
            "Pinar del RÃ­o",
            "Sancti SpÃ­ritus",
            "CamagÃ¼ey",
            "Las Tunas",
            "GuantÃ¡namo",
            "Varadero"
        ]
    },
    {
        "country": "Saint Helena",
        "cities": [
            "Tristan Da Cunha",
            "Jamestown"
        ]
    },
    {
        "country": "Christmas Island",
        "cities": [
            "Flying Fish Cove"
        ]
    },
    {
        "country": "Ethiopia",
        "cities": [
            "Addis Ababa",
            "Awasa",
            "Jijiga"
        ]
    },
    {
        "country": "British Indian Ocean Territory",
        "cities": []
    }
```
