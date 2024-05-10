# Data from ons.org.br

Archive of data from https://www.ons.org.br/paginas/energia-agora/balanco-de-energia

http://tr.ons.org.br/Content/GetBalancoEnergetico/null is downloaded every 1 minute and archived in this repo

## Paths
The `Data` field in JSON split on `T` and turned into path:
```
Data = 2024-05-07T20:36:00-03:00
Path = 2024-05-07/20:36:00-03:00.json
```

## Example contents
```json
{
    "Data": "2024-05-07T20:36:00-03:00",
    "sudesteECentroOeste": {
        "geracao": {
            "total": 37683.9922,
            "hidraulica": 27161.5449,
            "termica": 3582.377,
            "eolica": 4,
            "nuclear": 1999.80811,
            "solar": 9.089946,
            "itaipu50HzBrasil": 1622.7699,
            "itaipu60Hz": 3304.40381
        },
        "cargaVerificada": 52773.543,
        "importacao": 15089.55,
        "exportacao": 0
    },
    "sul": {
        "geracao": {
            "total": 16240.041,
            "hidraulica": 14475.53,
            "termica": 845.0856,
            "eolica": 918.4256,
            "nuclear": 0,
            "solar": 1
        },
        "cargaVerificada": 15541.2344,
        "importacao": 125.392754,
        "exportacao": 824.1998
    },
    "nordeste": {
        "geracao": {
            "total": 19959.6563,
            "hidraulica": 5740.90625,
            "termica": 338.042236,
            "eolica": 13879.58,
            "nuclear": 0,
            "solar": 1.12817049
        },
        "cargaVerificada": 13911.2139,
        "importacao": 0,
        "exportacao": 6049.51465
    },
    "norte": {
        "geracao": {
            "total": 16098.0938,
            "hidraulica": 14871.8467,
            "termica": 1121.35986,
            "eolica": 104.886833,
            "nuclear": 0,
            "solar": 0
        },
        "cargaVerificada": 7882.2583,
        "importacao": 0,
        "exportacao": 8215.835
    },
    "internacional": {
        "argentina": -0.0020888173,
        "paraguai": 0,
        "uruguai": -125.390663
    },
    "intercambio": {
        "internacional_sul": 125.392754,
        "sul_sudeste": 824.1998,
        "sudeste_nordeste": -773.3108,
        "sudeste_norteFic": -13492.0391,
        "norte_norteFic": 8215.835,
        "norteFic_nordeste": -5276.204
    }
}
```
