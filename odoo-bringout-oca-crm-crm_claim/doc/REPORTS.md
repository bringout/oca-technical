# Reports

Report definitions and templates in crm_claim.

```mermaid
classDiagram
    class CrmClaimReport
    Model <|-- CrmClaimReport
```

## Available Reports

### Analytical/Dashboard Reports
- **Claims Analysis** (Analysis/Dashboard)


## Report Files

- **crm_claim_report.py** (Python logic)
- **crm_claim_report_view.xml** (XML template/definition)
- **__init__.py** (Python logic)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
