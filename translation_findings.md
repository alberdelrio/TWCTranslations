# TWC Translation Findings — 2026-04-20

## Org Details
- **Alias:** twcdev
- **URL:** https://twcfs--twcdev.sandbox.my.salesforce.com
- **Username:** alberto.delrio@ncino.com.twcdev
- **Org Language:** en_US | **Locale:** en_GB
- **Translation language code:** `es` (Spanish generic)

---

## Custom Labels (CAT-A) — Discovery Summary

- **Total labels in org:** 13,546 (queried via Tooling API)
- **Items matched (API name confirmed):** 67 unique labels
- **Items NOT FOUND (need manual investigation):** 11 tracker IDs (see section below)
- **Items resolved via nForce__Translation__c:** 7 tracker IDs (import CSV, not SFDX)

### Matched Custom Labels — Included in es.translation-meta.xml

| Tracker ID | API Name (full) | Namespace | Spanish Translation |
|-----------|----------------|-----------|---------------------|
| REL-002 | LLC_BI__Loan_PickList_Status | LLC_BI | Estado |
| REL-003 | LLC_BI__Convert_Product_Package_Name_Field | LLC_BI | Nombre |
| REL-004 | LLC_BI__Fee_Category_Column_Header | LLC_BI | Categoría |
| REL-010 | LLC_BI__Connection_Role | LLC_BI | Rol de conexión |
| PRD-001 | LLC_BI__Loan_Products | LLC_BI | Derechos de Cobro |
| PRD-002 | LLC_BI__Total_Exposure_Summary | LLC_BI | Resumen de exposición total |
| PRD-004 | LLC_BI__Borrower_Type | LLC_BI | Tipo de interviniente |
| PRD-005 | LLC_BI__Commercial_Workspace_Column_Header_Loan_Number | LLC_BI | Número de contrato |
| PRD-006 | LLC_BI__Loan_PickList_Stage | LLC_BI | Etapa |
| CR-001 | Tab_Collaboration | (custom) | Colaboración |
| CR-002 | LLC_BI__Product_Package_SN_Loan_Facilities | LLC_BI | Contratos |
| CR-005 | nCRED__Loan_Name | nCRED | Nombre del contrato |
| CR-006 | LLC_BI__Commercial_Workspace_Column_Header_Loan_Number | LLC_BI | Número de contrato |
| CR-007 | LLC_BI__Maturity_Date | LLC_BI | Fecha de vencimiento |
| CR-008 | nCRED__Original_Amount | nCRED | Importe original |
| CR-010 | LLC_BI__Credit_Action_Title | LLC_BI | Acciones crediticias |
| CR-011 | LLC_BI__Credit_Action_Details | LLC_BI | Detalle de la acción crediticia |
| CR-012 | LLC_BI__Credit_Action_Current_Action | LLC_BI | Acción actual |
| CR-013 | LLC_BI__Credit_Action_Credit_Action | LLC_BI | Acción crediticia |
| CR-014 | LLC_BI__Credit_Action_Review_Type | LLC_BI | Tipo de revisión |
| CR-016 | LLC_BI__Tree_Grid_Edit_Panel_Multi_Edit | LLC_BI | Aplicar cambios a todos los contratos seleccionados (1) |
| CR-017 | LLC_BI__Credit_Action_Select_Product_Package | LLC_BI | Seleccionar Financiación Multiproducto |
| CR-018 | LLC_BI__Credit_Action_New_Product_Package | LLC_BI | Nueva Financiación Multiproducto |
| CR-019 | LLC_BI__Credit_Action_Existing_Product_Package | LLC_BI | Financiación Multiproducto actual |
| CR-020 | nCino__Conditions_DefineCondition_Description | nCino | Descripción |
| CR-022 | LLC_BI__Risk_Grade_Analysis | LLC_BI | Grade |
| NC-001 | nCRED__Route_Loan_Dashboard | nCRED | Panel del contrato |
| NC-002 | nCRED__Loan_Dashboard_Stage_History | nCRED | Historial de etapas |
| NC-003 | nCRED__Number_Of_Days | nCRED | Número de días |
| NC-004 | LLC_BI__Loan_Stage_History_Expand_or_Collapse | LLC_BI | Expandir / Contraer historial de etapas del contrato |
| NC-005 | LLC_BI__New_Loan_Details | LLC_BI | Detalles del contrato |
| NC-006 | LLC_BI__Create_Relationship_Product_Line | LLC_BI | Línea de producto |
| NC-007 | nCRED__Product_Type | nCRED | Tipo de producto |
| NC-008 | LLC_BI__Loan_PickList_Product | LLC_BI | Producto |
| NC-009 | nFORMS__Form_Generation | nFORMS | Generación de documentos |
| NC-010 | LLC_BI__Info | LLC_BI | Información |
| NC-013 | LLC_BI__Product_Package_SN_Entity_Involvement | LLC_BI | Estructura |
| NC-017 | LLC_BI__Col_Admin_Cancel_Button | LLC_BI | Cancelar |
| NC-018 | LLC_BI__Button_Continue | LLC_BI | Continuar |
| NC-019 | LLC_BI__Borrowing_Structure | LLC_BI | Estructura de participantes |
| NC-020 | LLC_BI__Add_Borrowers_and_Authorized_Signers | LLC_BI | Añade relaciones como prestatarios... |
| NC-021 | LLC_BI__MTAS_Add_Entity_Involvement | LLC_BI | Añadir participante |
| NC-022 | LLC_BI__Commercial_Workspace_Navigate_To_Relationship | LLC_BI | Haz clic en el enlace para navegar... |
| NC-023 | LLC_BI__Borrower_Type | LLC_BI | Tipo de interviniente |
| NC-024 | LLC_BI__Contingent_Type | LLC_BI | Tipo de contingencia |
| NC-026 | nCRED__Contingent_Percentage | nCRED | Porcentaje contingente |
| NC-027 | LLC_BI__Actions | LLC_BI | Acciones |
| NC-028 | LLC_BI__Add_Signer | LLC_BI | Añadir firmante |
| NC-031 | LLC_BI__Suggested_Relationships | LLC_BI | Relaciones sugeridas |
| NC-032 | LLC_BI__Search_Relationships | LLC_BI | Buscar relaciones |
| NC-033 | LLC_BI__MTAS_Relationship_Type | LLC_BI | Tipo de relación |
| NC-034 | LLC_BI__Individuals | LLC_BI | Personas físicas |
| NC-035 | LLC_BI__Businesses | LLC_BI | Empresas |
| NC-036 | nCino__No_Suggested_Relationships_Message | nCino | No se han encontrado relaciones sugeridas... |
| NC-037 | LLC_BI__MTAS_Add_Selected_Signers | LLC_BI | Añadir firmantes seleccionados |
| NC-038 | LLC_BI__MTAS_Warning_Icon_Text | LLC_BI | Debes añadir una persona física... |
| NC-040 | LLC_BI__Collateral_Summary | LLC_BI | Resumen de garantías |
| NC-048 | nCino__Conditions_All | nCino | Todos |
| NC-049 | LLC_BI__Pending_Approval_Status | LLC_BI | Pendiente |
| NC-050 | LLC_BI__Checklist_In_Progress | LLC_BI | En progreso |
| NC-051 | LLC_BI__Exception | LLC_BI | Excepción |
| NC-053 | LLC_BI__Task_Assignee | LLC_BI | Asignado a |
| NC-054 | LLC_BI__Null_Document_Option_Label | LLC_BI | Ninguno |
| NC-057 | nCRED__Policy_Exceptions_Auto_Processing | nCRED | Procesando |
| NC-058 | nCino__OP_Stage_Check_Tab_Label | nCino | Verificación de etapa |
| NC-060 | LLC_BI__DMW_Workspace_Button | LLC_BI | Abrir espacio de trabajo |
| EV-003 | TWC_Approval_Details_in_Review | (custom) | Detalles de la aprobación |
| AP-003 | nFORCE__Locked_Record_Message | nFORCE | Este registro está pendiente de aprobación y por tanto se encuentra bloqueado |
| CR-021 | LLC_BI__Relationship | LLC_BI | Relación |

---

## Field Translations (CAT-B) — Already Done (12 files)

All files are in `force-app/main/default/objectTranslations/` and have been updated with Spanish `<label>` values:

### LLC_BI__Loan__c-es (5 fields)

| Tracker ID | File | API Name | Spanish Label |
|-----------|------|----------|---------------|
| CR-023 | LLC_BI__AmountOutstanding__c.fieldTranslation-meta.xml | LLC_BI__AmountOutstanding__c | Saldo pendiente |
| CR-024 | LLC_BI__Principal_Balance__c.fieldTranslation-meta.xml | LLC_BI__Principal_Balance__c | Principal |
| EV-004 | Submitted_for_Approval_Date__c.fieldTranslation-meta.xml | Submitted_for_Approval_Date__c | Fecha de envío a aprobación |
| EV-005 | LLC_BI__Credit_Approval_Date__c.fieldTranslation-meta.xml | LLC_BI__Credit_Approval_Date__c | Fecha de aprobación crediticia |
| NC-061 | Full_Product_Name__c.fieldTranslation-meta.xml | Full_Product_Name__c | Nombre del producto |

### LLC_BI__Collateral__c-es (7 fields)

| Tracker ID | File | API Name | Spanish Label |
|-----------|------|----------|---------------|
| PRD-008 | LLC_BI__Collateral_Name__c.fieldTranslation-meta.xml | LLC_BI__Collateral_Name__c | Nombre de garantía |
| PRD-009 | LLC_BI__Lendable_Value__c.fieldTranslation-meta.xml | LLC_BI__Lendable_Value__c | Límite operativo |
| PRD-010 | LLC_BI__Total_Active_Loans_Value__c.fieldTranslation-meta.xml | LLC_BI__Total_Active_Loans_Value__c | Total preasignaciones activas |
| PRD-011 | LLC_BI__Total_Lien_Amount__c.fieldTranslation-meta.xml | LLC_BI__Total_Lien_Amount__c | Total cesiones activas |
| PRD-012 | LLC_BI__Remaining_Lendable_Value__c.fieldTranslation-meta.xml | LLC_BI__Remaining_Lendable_Value__c | Límite disponible propuesto |
| PRD-013 | TWC_Temporary_Extension_Amount__c.fieldTranslation-meta.xml | TWC_Temporary_Extension_Amount__c | Importe límite temporal |
| PRD-014 | TWC_Temporary_Extension_Due_Date__c.fieldTranslation-meta.xml | TWC_Temporary_Extension_Due_Date__c | Fecha vencimiento límite temporal |

### Not Updated (needs investigation)

| Tracker ID | Object | English Label | Issue |
|-----------|--------|--------------|-------|
| PRD-007 | LLC_BI__Collateral__c | Collateral Number | No `Collateral_Number__c` field found. May be the auto-number Name field. |
| REL-005 to REL-008 | Contact | Salutation, First Name, Middle Name, Last Name | Standard Contact fields — covered by SF language pack. |

---

## Validation Rules (CAT-D)

| Tracker ID | ValidationName | Object | Namespace | Translatable? | Status |
|-----------|---------------|--------|-----------|--------------|--------|
| LV04 / AP-002 | Loan_Validation_04 | LLC_BI__Loan__c | NONE (custom) | YES | **TRANSLATED** in objectTranslation |
| REL-001 | TWC_CNAERequired | Account | NONE (custom) | YES | **NOT TRANSLATED** — Error msg = "It's mandatory to inform the CNAE." Does NOT match expected "CNAE cedente/etapa de Prospecto" text from brief. Needs clarification. |
| EV-001 | NOT FOUND | — | — | — | Expected error about "Cuentas anuales auditadas / etapa de Propuesta" not found in any VR. May be in Flow or Apex. |
| AP-001 | NOT FOUND | — | — | — | Expected error about "Validación del credit memo / etapa de Evaluación" not found in any VR. May be in Flow or Apex. |

### Existing Spanish VR translation found (not overwritten)

| ValidationName | Object | Spanish Error Message |
|---------------|--------|---------------------|
| Check_for_Account_Default_for_New_Loans | LLC_BI__Loan__c | "No se puede añadir el interviniente al derecho de cobro. Por favor, revise su comportamiento de pago." |

---

## Record Types (CAT-C)

### LLC_BI__Loan__c Record Types

| DeveloperName | English Name | Spanish Label | Status |
|--------------|-------------|---------------|--------|
| Commercial_Loan_Record_Type | Contract Loan Record Type | Contrato | **TRANSLATED** |
| Receivable_Loan_Record_Type | Receivable Loan Record Type | Derecho de cobro | **TRANSLATED** |
| Consumer_Loan_Record_Type | Consumer Loan Record Type | Contrato consumo | **TRANSLATED** |
| Government_Guaranteed_Record_Type | Government Guaranteed Record Type | Garantía gubernamental | **TRANSLATED** |
| Guidance_Line_Record_Type | Guidance Line Record Type | — | Not in scope |
| Guidance_LOC_Sub_Loan_Record_Type | Guidance LOC Sub Loan Record Type | — | Not in scope |
| LLC_BI__Start | Start | — | Not in scope |

> **REM-001/003/005 (AssignmentBatch, CollectionBatch, PurchaseBatch):** These record types do NOT exist on LLC_BI__Loan__c. They may be on TWC_Batch__c or may not have been created yet. Needs VASS clarification.

### Account Record Types

| DeveloperName | English Name | Spanish Label | Status |
|--------------|-------------|---------------|--------|
| LLC_BI__Business | Business | Empresa | **TRANSLATED** |
| LLC_BI__Household | Household | Grupo Empresarial | **TRANSLATED** |
| LLC_BI__Lender | Lender | Prestamista | **TRANSLATED** |
| Agent | Agent | Agente | Already existed |
| Compartment | Compartment | Compartimento | Already existed |
| Fund | Fund | Fondo | Already existed |
| Insurance | Insurance | Aseguradora | Already existed |
| LLC_BI__Individual | Individual | — | Not in scope (different from PersonAccount) |
| Vendor | Vendor | — | Not in scope |

> **REL-015 (PersonAccount):** No PersonAccount record type found in Account-es objectTranslation file. May use a different DeveloperName or may need to be retrieved separately.

---

## Approval Processes (CAT-E)

### Processes on LLC_BI__Loan__c

| Process Name | Description |
|-------------|------------|
| TWC Contract Approval Flow | Used for Contract Loans |
| TWC Own Risk Approval | — |
| TWC Grade Exception Approval | Grade Exception in Factoring Contracts |
| LAP100 - Sample Loan Approval Process | Sample |
| PP-Two Step Approval Process | PP-level approval |
| LAP100 - nCino Gold Standard AP | Gold Standard |

### Steps Found

| Process | Step Name |
|---------|-----------|
| TWC Contract Approval Flow | LAP:001 |
| TWC Own Risk Approval | Step 1 |
| TWC Grade Exception Approval | LAP:001 |

> **AP-008 to AP-012 ("Adverse news check", "AML check initial", "PEPS check", "UBOs check", "Majority approval"):** These step names were NOT FOUND in any approval process. The actual steps have generic names (LAP:001, Step 1). These specific checks may be Smart Checklist items or may not exist in this sandbox.

### Platform Standard Labels (AP-003 to AP-007)
Approval platform messages (Approve, Reject, "pending approval and locked") are Salesforce standard labels. They auto-translate if Spanish language pack is active.

---

## Custom Buttons (CAT-F) — LLC_BI__Loan__c

### Quick Actions (translated in objectTranslation)

| API Name | English Label | Spanish Label | Status |
|----------|--------------|---------------|--------|
| Create_Assignment_Batch | Create Offer | Crear oferta de cesión | **TRANSLATED** |
| Create_Collection_Batch | Create Collection Batch | Crear remesa de cobro | **TRANSLATED** |
| Create_Purchase_Batch | Create Purchase Batch | Crear remesa de compra | **TRANSLATED** |
| TWC_Change_Product | Cambio de Producto | Cambio de Producto | Already existed |
| TWC_DownloadDocuments | Descargar Documentos | Descargar Documentos | Already existed |

### WebLinks

| API Name | English Label | Spanish Label | Status |
|----------|--------------|---------------|--------|
| LLC_BI__Change_Product | Change Product | Cambiar producto | **TRANSLATED** |
| LLC_BI__Copy_Loan | Copy Loan | Copiar contrato | **TRANSLATED** |
| LLC_BI__Credit_Memo | Credit Memo | Managed |
| LLC_BI__Decline_Loan | Decline Loan | Managed |
| LLC_BI__DocuSign | DocuSign | Managed |
| LLC_BI__Loan_Submit_For_Approval | Submit for Approval | Managed |
| LLC_BI__deleteLoan | Delete Loan | Managed |
| LLC_BI__renew_loan | Renew/Modify Loan | Managed |

---

## nForce__Translation__c Query Results (CAT-I)

- **Total `es` records:** 4,653
- **Object fields:** nFORCE__Language__c, nFORCE__Feature_Translation__c, nFORCE__Translation_Key__c, nFORCE__Original_Text__c, nFORCE__Translated_Text__c

### Feature Breakdown (top categories)

| Feature | Count | Status |
|---------|-------|--------|
| Spread_Statement_Record_Name | 734 | Most empty |
| Classification_Names | 565 | Most empty |
| Feature_Process_Descriptions | 390 | Most empty |
| Feature_Process_Names | 375 | Most empty |
| Section_Names | 355 | Most empty |
| Route_Names | 273 | Most empty |
| Screen_Names | 262 | Most empty |
| Connection_Role_Names | 28 | **ALL TRANSLATED** |
| Product_Names | 16 | 2 translated (Receivable - Invoice, Receivable - Promissory Note), 14 missing |
| Product_Type_Names | 8 | All empty |
| Product_Line_Names | 5 | All empty |
| Role_Names | 9 | All empty |

### Detailed Discovery (928 UI-relevant records)

| Feature | Total | Empty | Translated |
|---------|-------|-------|------------|
| Section_Names | 355 | 351 | 4 |
| Route_Names | 273 | 270 | 3 |
| Screen_Names | 262 | 261 | 1 |
| Product_Names | 16 | 14 | 2 |
| Product_Type_Names | 8 | 8 | 0 |
| Product_Line_Names | 5 | 5 | 0 |
| Role_Names | 9 | 9 | 0 |

### Key Findings

1. **Connection Roles are fully translated** — 28 records with Spanish values (e.g., "Empresa cuya tesorería es gestionada por", "Director de Compras")
2. **Route_Names, Screen_Names, Section_Names** — 918 empty out of 928 total. These include critical UI elements.
3. **14 records matched to TWC PDF items** — ready for import via `twc_ncino_translations_to_import.csv`
4. **Product translations** — Only 2 of 16 Product_Names translated ("Derecho de cobro - Factura", "Derecho de cobro - Pagaré"). Factoring and Confirming ready in import CSV.
5. **Full review CSV** — `twc_ncino_translations_full_review.csv` has all 918 empty records for Alberto/VASS to review
6. **Detailed report** — see `twc_ncino_translation_findings.md` for import instructions

---

## BLOCKED Items — nCino Support Cases Required

| Tracker ID | English | Reason |
|-----------|---------|--------|
| CR-003 | Credit Actionable Loans | NOT FOUND in Custom Labels. Driven by FieldSet_Credit_Action. Per nCino article "Translating nCino Labels" this cannot be translated via standard mechanisms. Raise nCino Support case. |
| CR-004 | All Loans | NOT FOUND in Custom Labels. Driven by FieldSet_Facilities_All. Same limitation. |

---

## Items Resolved via nForce__Translation__c (Data Import Wizard)

These items were NOT Custom Labels but WERE found as nForce Translation records. Import via `twc_ncino_translations_to_import.csv`.

| Tracker ID | English Text | Spanish | nForce Record ID | Feature |
|-----------|-------------|---------|-----------------|---------|
| NC-011 | Pricing Conditions | Condiciones de precio | a4AAU000003QowX2AS | Route_Names |
| NC-014/NC-039 | Guarantee | Garantía | a4AAU000003Qp8F2AS + 2 more | Section/Route/Screen_Names |
| NC-029/EV-002 | Approvals | Aprobaciones | a4AAU000003QowM2AS | Route_Names |
| PRD-003 | Loan | Contrato | a4AAU000003Qots2AC | Route_Names |
| REL-009 | DocuSign | DocuSign | a4AAU000003Qov72AC | Route_Names |

---

## Items NOT FOUND Anywhere (likely LWC component strings)

These tracker IDs have no matching Custom Label, nForce Translation record, or field translation. They are likely hardcoded in nCino LWC components or TWC custom components. Flag for nCino Support.

| Tracker ID | English Text | Proposed Spanish | Investigation Notes |
|-----------|-------------|-----------------|---------------------|
| CR-009 | Product Package Name | Nombre del Financiación Multiproductos | May be field reference label |
| NC-012 | Pricing Condition Fields | Campos de condiciones de precio | Likely nCino LWC component |
| NC-016 | Minimum Advance per Document | Anticipo mínimo por documento | Likely TWC custom LWC |
| NC-025 | Contingent Amount | Importe contingente | Not found anywhere |
| NC-041 | Current LTV | LTV actual | Not found anywhere |
| NC-042 | Gross Collateral Value | Valor bruto de garantía | Not found anywhere |
| NC-043 | Current Gross Lendable Value | Límite operativo bruto actual | Not found anywhere |
| NC-044 | Total Collateral Pledged | Total preasignado | Not found anywhere |
| NC-045 | No guarantee has been pledged... | (pending) | Not found anywhere |
| NC-056 | Resolved by | Resuelto por | Not found anywhere |
| DS-001 | Document Stage (nav item) | Etapa del documento | Not found anywhere |

---

## CAT-G: nCino Record Config (Manual VASS Action)

| ID | Item | Action Required |
|----|------|-----------------|
| REL-011 | Smart Checklist category "REQUIREMENTS" | VASS to rename to "Requerimientos" in nCino Admin > Smart Checklist Categories |

---

## Existing Translations Found (NOT overwritten)

| File | Element | Existing Spanish Value |
|------|---------|----------------------|
| Account-es | recordType Agent | Agente |
| Account-es | recordType Compartment | Compartimento |
| Account-es | recordType Fund | Fondo |
| Account-es | recordType Insurance | Aseguradora |
| Account-es | quickAction TWC_Create_Contact | Crear Contacto |
| Account-es | quickAction TWC_Create_Contract_Proposal | Crear Propuesta de Contrato |
| Account-es | quickAction TWC_Downloaddocuments | Descargar documentos |
| Account-es | quickAction TWC_UpdateAddress | Actualizar Dirección |
| Account-es | caseValues singular | Interviniente |
| Account-es | caseValues plural | Intervinientes |
| Loan-es | quickAction TWC_Change_Product | Cambio de Producto |
| Loan-es | quickAction TWC_DownloadDocuments | Descargar Documentos |
| Loan-es | VR Check_for_Account_Default_for_New_Loans | "No se puede añadir el interviniente al derecho de cobro..." |

---

## Files Modified (this session + previous session)

### New Files Created
1. `force-app/main/default/translations/es.translation-meta.xml` — 67 Custom Label translations
2. `twc_ncino_translations_to_import.csv` — 14 nForce Translation records ready for Data Import Wizard
3. `twc_ncino_translations_full_review.csv` — 918 empty nForce records for manual review
4. `twc_ncino_translation_findings.md` — nForce Translation detailed discovery report

### Files Updated (objectTranslations)
5. `LLC_BI__Loan__c-es/LLC_BI__Loan__c-es.objectTranslation-meta.xml` — nameFieldLabel, quick actions (3), record types (4), validation rule LV04, webLinks (2)
6. `Account-es/Account-es.objectTranslation-meta.xml` — record types (3: Business, Household, Lender)
4. `LLC_BI__Loan__c-es/LLC_BI__AmountOutstanding__c.fieldTranslation-meta.xml`
5. `LLC_BI__Loan__c-es/LLC_BI__Principal_Balance__c.fieldTranslation-meta.xml`
6. `LLC_BI__Loan__c-es/LLC_BI__Credit_Approval_Date__c.fieldTranslation-meta.xml`
7. `LLC_BI__Loan__c-es/Submitted_for_Approval_Date__c.fieldTranslation-meta.xml`
8. `LLC_BI__Loan__c-es/Full_Product_Name__c.fieldTranslation-meta.xml`
9. `LLC_BI__Collateral__c-es/LLC_BI__Collateral_Name__c.fieldTranslation-meta.xml`
10. `LLC_BI__Collateral__c-es/LLC_BI__Lendable_Value__c.fieldTranslation-meta.xml`
11. `LLC_BI__Collateral__c-es/LLC_BI__Remaining_Lendable_Value__c.fieldTranslation-meta.xml`
12. `LLC_BI__Collateral__c-es/LLC_BI__Total_Lien_Amount__c.fieldTranslation-meta.xml`
13. `LLC_BI__Collateral__c-es/LLC_BI__Total_Active_Loans_Value__c.fieldTranslation-meta.xml`
14. `LLC_BI__Collateral__c-es/TWC_Temporary_Extension_Amount__c.fieldTranslation-meta.xml`
15. `LLC_BI__Collateral__c-es/TWC_Temporary_Extension_Due_Date__c.fieldTranslation-meta.xml`

---

## Deployment Status

| Item | Status |
|------|--------|
| es.translation-meta.xml (67 Custom Labels) | CREATED locally |
| LLC_BI__Loan__c-es field translations (5 files) | UPDATED locally |
| LLC_BI__Collateral__c-es field translations (7 files) | UPDATED locally |
| LLC_BI__Loan__c-es objectTranslation (RTs, VRs, buttons) | UPDATED locally |
| Account-es objectTranslation (RTs) | UPDATED locally |
| Contact-es field translations | NOT UPDATED (standard fields, SF lang pack) |
| LLC_BI__Loan__c-es webLinks (Change_Product, Copy_Loan) | UPDATED locally |
| nForce Translation import CSV (14 records) | CREATED — import via Data Import Wizard |
| nForce Translation full review CSV (918 records) | CREATED — for manual review |
| Deployed to org | **NO** |
| Git committed | **YES** — branch `feature/TWC-UI-translation-es-April2026` |
| Git pushed | **YES** — https://github.com/alberdelrio/TWCTranslations |
