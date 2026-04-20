# TWC nCino Record Translations — Discovery Report
**Date:** 2026-04-20  
**Org:** twcdev  

---

## Summary

| Metric | Count |
|--------|-------|
| Total nForce__Translation__c `es` records queried (UI-relevant) | 928 |
| Empty (untranslated) | 918 |
| Already translated | 10 |
| TWC PDF items matched to org records (confirmed) | 14 |
| TWC PDF items NOT found in nForce__Translation__c | 13 |

**Features analysed:** Section_Names (355), Route_Names (273), Screen_Names (262), Product_Names (16), Product_Type_Names (8), Product_Line_Names (5), Role_Names (9)

**Excluded (out of scope):** Connection_Role_Names (28, already translated), Feature_Process_Names (375), Feature_Process_Descriptions (390), Spread_Statement_Record_Name (734), Classification_Names (565)

---

## Matched Items — Ready to Import

These 14 records have confirmed matches and proposed Spanish translations. Import via Data Import Wizard.

| Tracker ID | Record ID | Feature | English Original | Proposed Spanish |
|------------|-----------|---------|-----------------|-----------------|
| EV-002/NC-029 | a4AAU000003QowM2AS | Route_Names | Approvals | Aprobaciones |
| NC-011 | a4AAU000003QowX2AS | Route_Names | Pricing Conditions | Condiciones de precio |
| NC-014/NC-039 | a4AAU000003Qp8F2AS | Section_Names | Guarantee | Garantía |
| NC-014 (route) | a4AAU000003Qovy2AC | Route_Names | Guarantee | Garantía |
| NC-014 (screen) | a4AAU000003Qp0M2AS | Screen_Names | Guarantee | Garantía |
| NC-015/NC-046 | a4AAU000003Qow92AC | Route_Names | Conditions | Condiciones |
| PRD-003 | a4AAU000003Qots2AC | Route_Names | Loan | Contrato |
| PRD-FACTORING | a4AAU000003Qo2k2AC | Product_Type_Names | Factoring | Factoring |
| PRD-CONFIRMING | a4AAU000003Qo2l2AC | Product_Type_Names | Confirming | Confirming |
| REL-009 | a4AAU000003Qov72AC | Route_Names | DocuSign | DocuSign |
| NC-040 (screen) | a4AAU000003Qoxs2AC | Screen_Names | Guarantee Summary | Resumen de garantías |
| NC-040 (section) | a4AAU000003Qp5d2AC | Section_Names | Guarantee Summary | Resumen de garantías |
| COLL (route) | a4AAU000003Qov62AC | Route_Names | Collateral Pledged | Garantías asignadas |
| COLL (section) | a4AAU000003Qp9U2AS | Section_Names | Collateral Pledged | Garantías asignadas |

---

## Unmatched Items — NOT in nForce__Translation__c

These 13 items from the TWC PDF were **not found** as nForce Translation records. They are likely hardcoded in nCino LWC components or custom TWC components. Flag for nCino Support or check component source code.

| Tracker ID | English | Proposed Spanish | Notes |
|------------|---------|-----------------|-------|
| NC-016 | Minimum Advance per Document | Anticipo mínimo por documento | Likely TWC custom LWC |
| NC-025 | Contingent Amount | Importe contingente | Not a label or nForce record |
| NC-041 | Current LTV | LTV actual | Not a label or nForce record |
| NC-042 | Gross Collateral Value | Valor bruto de garantía | Only generic "Collateral" exists |
| NC-043 | Current Gross Lendable Value | Límite operativo bruto actual | Not found |
| NC-044 | Total Collateral Pledged | Total preasignado | Only generic "Collateral Pledged" exists |
| NC-045 | No guarantee has been pledged... | [PENDING SPANISH] | Not found — likely LWC component string |
| NC-052 | Name | Nombre | Too generic — no standalone record |
| NC-055 | Description | Descripción | Only "Modification Description" exists |
| NC-056 | Resolved by | Resuelto por | Not found |
| NC-059 | Cancel | Cancelar | Not found (Custom Label exists separately) |
| DS-001 | Document Stage | Etapa del documento | Not found as Route or Screen name |
| PRD-LINE | Línea de riesgo | Línea de riesgo | Not found in Product_Line_Names |

---

## False Positives Removed

Step 2 initial matching produced 16 matches, but 5 were false positives (partial substring matches to wrong records). These were removed:

- **NC-042** "Gross Collateral Value" matched to generic "Collateral" section — wrong context
- **NC-044** "Total Collateral Pledged" matched to generic "Collateral" section — wrong context
- **NC-045** "No guarantee has been pledged" matched to "Guarantee" section — substring only
- **NC-052** "Name" matched to "Adverse Actions" via key substring — clearly wrong
- **NC-055** "Description" matched to "Modification Description" — partial match, different context

---

## Empty Records by Feature (for Alberto to review)

Full lists are in `twc_ncino_translations_full_review.csv`. Summary counts:

| Feature | Total Empty | Notes |
|---------|------------|-------|
| Section_Names | 351 | Largest category — includes panel headers, card titles |
| Route_Names | 270 | Navigation tabs, wizard steps |
| Screen_Names | 261 | Screen/page names in nCino UI |
| Product_Names | 14 | TWC product catalog items |
| Product_Type_Names | 8 | Factoring, Confirming, etc. |
| Product_Line_Names | 5 | Product line categories |
| Role_Names | 9 | User role labels |

---

## Files Produced

| File | Purpose |
|------|---------|
| `twc_ncino_translations_to_import.csv` | 14 records ready for Data Import Wizard |
| `twc_ncino_translations_full_review.csv` | 918 empty records for manual review |
| `twc_ncino_translation_findings.md` | This report |

---

## Import Instructions

1. Go to TWC dev org → Setup → **Data Import Wizard**
2. Select: **Update existing records** → Custom Objects → nForce Translation
3. Upload: `twc_ncino_translations_to_import.csv`
4. Map fields:
   - `Id` → Record ID
   - `nFORCE__Translated_Text__c` → Translated Text
5. Start import. Verify success in import log.
6. Test: switch a user to Spanish → navigate to the affected screens
7. **Note:** `tracker_id` and `nFORCE__Original_Text__c` columns are for reference only — do not map them during import.

---

## Next Steps

1. **Review the 14 confirmed translations** in the import CSV — approve or adjust the proposed Spanish
2. **Review `twc_ncino_translations_full_review.csv`** — Alberto and VASS decide which of the 918 empty records need Spanish translations for TWC end users
3. **For the 13 unmatched items** — open nCino Support case or inspect TWC custom LWC source code to find where these strings are defined
4. **Product_Names** — only TWC-specific products were included. Review the remaining 14 empty Product_Names to decide if any others need translating
