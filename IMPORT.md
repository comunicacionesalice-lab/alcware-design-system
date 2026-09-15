# Import in OpenDesign

Recommended route: import this folder/repository as an OpenDesign Design System package through the GitHub-repo or local-folder design-system importer.

Do not use `Describe brand` as the system name. The stable name must come from `manifest.json`: `ALCWARE`.

If OpenDesign shows a generated slug such as `alcware-is-a-cross-product...`, Inter as the intended typeface, Primary `#004F58` as the CTA, or generic dashed/text button families, the importer has fallen back to normalized brand extraction instead of consuming the package contract.

Expected core bindings:
- Name: ALCWARE
- Font: DM Sans
- Canvas: #F4F8F9
- Surface: #FFFFFF
- Foreground: #102124
- Accent / primary CTA: #00909E
- Accent hover: #007C88
- Accent active: #006B76
- Border: #EAF3F4
- Border strong: #DDECEE
- Control radius: 12px
- Card radius: 20px
- Table action radius: 10px
- Pill radius: 9999px
