# UD3.AO.FC

Estructura de carpetes per a l'exercici d'Aplicacions d'Ofimàtica (Fulls de Càlcul).

## Plantilles creades (LibreOffice Calc - ODS)

A la carpeta `Ubuntu/LibreOffice/` hi ha:

- **01_checklist.ods** — Checklist amb sistema de recompte automàtic
  - Llista desplegable Sí/No (validació de dades)
  - Fórmules: `COUNTA` per total d'elements, `COUNTIF` per fets (Sí) i pendents (No)
  - Percentatge de completat

- **02_factura.ods** — Factura completa amb totes les operacions
  - Columnes: Codi, Article, Unitats, Preu unitari, % Descompte, Total descompte, Subtotal, % IVA, Total IVA, Total amb IVA
  - Fórmules per fila:
    - Subtotal = Unitats × Preu Unitari
    - Total descompte = Subtotal × % Descompte
    - Total IVA = (Subtotal − Total descompte) × % IVA
    - Total amb IVA = Subtotal − Total descompte + Total IVA
  - Resums: Import brut, total descomptes, base neta, desglose IVA per tipus (4%, 10%, 21%) amb SUMIF, TOTAL FACTURA

## Estructura

```
UD3.AO.FC/
├── Ubuntu/
│   ├── LibreOffice/
│   │   ├── 01_checklist.ods
│   │   ├── 02_factura.ods
│   │   └── README_plantilles.md
│   └── WPS Office/
└── Windows/
    ├── Microsoft Office/
    ├── WPS-Office/
    └── OpenOffice/
```

Objectius coberts: ús avançat de fulls de càlcul, disseny de plantilles, fórmules i validació de dades.
