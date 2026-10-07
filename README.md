# SAP-Study-Road-Map

Repositório central do meu roadmap de estudos SAP: reúne o índice de todos os
repositórios de estudo, organizados por fase, e as convenções comuns a eles.
Cada tema é um repositório público próprio em `github.com/igor-barral`, com o
mesmo nome da pasta. Os itens marcados com `[x]` no índice já foram concluídos e
publicados; os demais ainda estão em andamento.

## Como usar

- **Documentação** (`erp` e repositórios de noção): só `README.md`.
- **ABAP**: formato abapGit (`src/`, `.abapgit.xml`). `docker compose run --rm abaplint`
  verifica a sintaxe sem sistema SAP; a execução real é no BTP ABAP Environment trial
  (fases 1 a 6) ou no ABAP Platform Trial (fase 7), importando via abapGit.
- **JavaScript** (SAPUI5, Fiori Elements, CAP, QUnit, OPA5): `docker compose up`, com
  backend simulado. Veja o "Como rodar" de cada README.
- Para publicar um repositório: `cd <pasta> && git init`, criar o repositório no GitHub com
  o mesmo nome e fazer o push. O nome da pasta é o nome do repositório.

## Índice


### Fase 0

- [x] [SAP-ECC-erp-study](https://github.com/igor-barral/SAP-ECC-erp-study)
- [x] [SAP-S4HANA-erp-study](https://github.com/igor-barral/SAP-S4HANA-erp-study)
- [x] [SAP-S4HANA-On-Premise-erp-study](https://github.com/igor-barral/SAP-S4HANA-On-Premise-erp-study)
- [x] [SAP-S4HANA-Cloud-Private-Edition-erp-study](https://github.com/igor-barral/SAP-S4HANA-Cloud-Private-Edition-erp-study)
- [x] [SAP-S4HANA-Cloud-Public-Edition-erp-study](https://github.com/igor-barral/SAP-S4HANA-Cloud-Public-Edition-erp-study)
- [x] [RISE-with-SAP-erp-study](https://github.com/igor-barral/RISE-with-SAP-erp-study)
- [x] [GROW-with-SAP-erp-study](https://github.com/igor-barral/GROW-with-SAP-erp-study)
- [x] [SAP-Enterprise-Structure-erp-study](https://github.com/igor-barral/SAP-Enterprise-Structure-erp-study)
- [x] [SAP-Business-Partner-erp-study](https://github.com/igor-barral/SAP-Business-Partner-erp-study)
- [x] [SAP-RICEFW-erp-study](https://github.com/igor-barral/SAP-RICEFW-erp-study)
- [x] [SAP-MM-erp-study](https://github.com/igor-barral/SAP-MM-erp-study)
- [x] [SAP-SD-erp-study](https://github.com/igor-barral/SAP-SD-erp-study)
- [ ] [SAP-FI-erp-study](https://github.com/igor-barral/SAP-FI-erp-study)
- [ ] [SAP-CO-erp-study](https://github.com/igor-barral/SAP-CO-erp-study)
- [ ] [SAP-WM-erp-study](https://github.com/igor-barral/SAP-WM-erp-study)
- [ ] [SAP-EWM-erp-study](https://github.com/igor-barral/SAP-EWM-erp-study)
- [ ] [SAP-Procure-to-Pay-erp-study](https://github.com/igor-barral/SAP-Procure-to-Pay-erp-study)
- [ ] [SAP-Order-to-Cash-erp-study](https://github.com/igor-barral/SAP-Order-to-Cash-erp-study)

### Fase 1

- [ ] [SAP-BTP-devops-study](https://github.com/igor-barral/SAP-BTP-devops-study)
- [ ] [SAP-BTP-ABAP-Environment-devops-study](https://github.com/igor-barral/SAP-BTP-ABAP-Environment-devops-study)
- [ ] [ABAP-Development-Tools-devops-study](https://github.com/igor-barral/ABAP-Development-Tools-devops-study)
- [ ] [abapGit-devops-study](https://github.com/igor-barral/abapGit-devops-study)
- [ ] [SAP-gCTS-devops-study](https://github.com/igor-barral/SAP-gCTS-devops-study)

### Fase 2

- [ ] [ABAP-language-study](https://github.com/igor-barral/ABAP-language-study)
- [ ] [ABAP-Internal-Tables-language-study](https://github.com/igor-barral/ABAP-Internal-Tables-language-study)
- [ ] [ABAP-SQL-db-study](https://github.com/igor-barral/ABAP-SQL-db-study)
- [ ] [SAP-HANA-db-study](https://github.com/igor-barral/SAP-HANA-db-study)
- [ ] [AMDP-db-study](https://github.com/igor-barral/AMDP-db-study)
- [ ] [ADBC-db-study](https://github.com/igor-barral/ADBC-db-study)
- [ ] [ABAP-OO-softwarearchitecture-study](https://github.com/igor-barral/ABAP-OO-softwarearchitecture-study)
- [ ] [ABAP-Unit-softwarearchitecture-study](https://github.com/igor-barral/ABAP-Unit-softwarearchitecture-study)
- [ ] [Clean-ABAP-softwarearchitecture-study](https://github.com/igor-barral/Clean-ABAP-softwarearchitecture-study)
- [ ] [ABAP-Test-Cockpit-softwarearchitecture-study](https://github.com/igor-barral/ABAP-Test-Cockpit-softwarearchitecture-study)
- [ ] [abaplint-devops-study](https://github.com/igor-barral/abaplint-devops-study)
- [ ] [sap-freight-calculation-case](https://github.com/igor-barral/sap-freight-calculation-case)

### Fase 3

- [ ] [ABAP-Dictionary-db-study](https://github.com/igor-barral/ABAP-Dictionary-db-study)
- [ ] [CDS-View-Entities-db-study](https://github.com/igor-barral/CDS-View-Entities-db-study)
- [ ] [SAP-VDM-softwarearchitecture-study](https://github.com/igor-barral/SAP-VDM-softwarearchitecture-study)
- [ ] [CDS-Access-Control-security-study](https://github.com/igor-barral/CDS-Access-Control-security-study)

### Fase 4

- [ ] [RAP-Managed-framework-study](https://github.com/igor-barral/RAP-Managed-framework-study)
- [ ] [RAP-Draft-framework-study](https://github.com/igor-barral/RAP-Draft-framework-study)
- [ ] [RAP-Unmanaged-framework-study](https://github.com/igor-barral/RAP-Unmanaged-framework-study)
- [ ] [OData-V4-integration-study](https://github.com/igor-barral/OData-V4-integration-study)
- [ ] [sap-rap-delivery-management-case](https://github.com/igor-barral/sap-rap-delivery-management-case)

### Fase 5

- [ ] [SAP-Fiori-Elements-framework-study](https://github.com/igor-barral/SAP-Fiori-Elements-framework-study)
- [ ] [SAP-Fiori-tools-devops-study](https://github.com/igor-barral/SAP-Fiori-tools-devops-study)
- [ ] [SAP-Business-Application-Studio-devops-study](https://github.com/igor-barral/SAP-Business-Application-Studio-devops-study)
- [ ] [SAPUI5-framework-study](https://github.com/igor-barral/SAPUI5-framework-study)
- [ ] [QUnit-lib-study](https://github.com/igor-barral/QUnit-lib-study)
- [ ] [OPA5-lib-study](https://github.com/igor-barral/OPA5-lib-study)
- [ ] [SAP-Fiori-Launchpad-framework-study](https://github.com/igor-barral/SAP-Fiori-Launchpad-framework-study)

### Fase 6

- [ ] [SAP-Clean-Core-softwarearchitecture-study](https://github.com/igor-barral/SAP-Clean-Core-softwarearchitecture-study)
- [ ] [SAP-Business-Accelerator-Hub-integration-study](https://github.com/igor-barral/SAP-Business-Accelerator-Hub-integration-study)
- [ ] [ABAP-Cloud-Extensibility-softwarearchitecture-study](https://github.com/igor-barral/ABAP-Cloud-Extensibility-softwarearchitecture-study)
- [ ] [SAP-CAP-Nodejs-framework-study](https://github.com/igor-barral/SAP-CAP-Nodejs-framework-study)
- [ ] [SAP-BTP-Cloud-Foundry-devops-study](https://github.com/igor-barral/SAP-BTP-Cloud-Foundry-devops-study)
- [ ] [SAP-BTP-Kyma-devops-study](https://github.com/igor-barral/SAP-BTP-Kyma-devops-study)
- [ ] [SAP-Integration-Suite-integration-study](https://github.com/igor-barral/SAP-Integration-Suite-integration-study)
- [ ] [SAP-Joule-ai-study](https://github.com/igor-barral/SAP-Joule-ai-study)

### Fase 7

- [ ] [SAP-GUI-devops-study](https://github.com/igor-barral/SAP-GUI-devops-study)
- [ ] [SAP-Transport-Management-devops-study](https://github.com/igor-barral/SAP-Transport-Management-devops-study)
- [ ] [ABAP-ALV-Reports-lib-study](https://github.com/igor-barral/ABAP-ALV-Reports-lib-study)
- [ ] [SAP-BAPI-integration-study](https://github.com/igor-barral/SAP-BAPI-integration-study)
- [ ] [SAP-RFC-integration-study](https://github.com/igor-barral/SAP-RFC-integration-study)
- [ ] [SAP-Gateway-integration-study](https://github.com/igor-barral/SAP-Gateway-integration-study)
- [ ] [OData-V2-integration-study](https://github.com/igor-barral/OData-V2-integration-study)
- [ ] [ABAP-Enhancement-Framework-softwarearchitecture-study](https://github.com/igor-barral/ABAP-Enhancement-Framework-softwarearchitecture-study)
- [ ] [ABAP-BAdI-softwarearchitecture-study](https://github.com/igor-barral/ABAP-BAdI-softwarearchitecture-study)
- [ ] [SAP-IDoc-integration-study](https://github.com/igor-barral/SAP-IDoc-integration-study)
- [ ] [ABAP-Performance-Analysis-performance-study](https://github.com/igor-barral/ABAP-Performance-Analysis-performance-study)
- [ ] [SAP-S4HANA-Migration-erp-study](https://github.com/igor-barral/SAP-S4HANA-Migration-erp-study)
- [ ] [SAP-S4HANA-Migration-Cockpit-erp-study](https://github.com/igor-barral/SAP-S4HANA-Migration-Cockpit-erp-study)
- [ ] [SAP-LSMW-erp-study](https://github.com/igor-barral/SAP-LSMW-erp-study)
- [ ] [SAP-SmartForms-lib-study](https://github.com/igor-barral/SAP-SmartForms-lib-study)
- [ ] [SAP-Adobe-Forms-lib-study](https://github.com/igor-barral/SAP-Adobe-Forms-lib-study)
- [ ] [SAPscript-lib-study](https://github.com/igor-barral/SAPscript-lib-study)
- [ ] [SAP-Business-Workflow-erp-study](https://github.com/igor-barral/SAP-Business-Workflow-erp-study)
- [ ] [sap-classic-alv-bapi-case](https://github.com/igor-barral/sap-classic-alv-bapi-case)

### Fase 8: certificação `C_ABAPD`

