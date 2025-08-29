# Reports

Report definitions and templates in crm_phonecall.

```mermaid
classDiagram
    class CrmPhonecallReport
    Model <|-- CrmPhonecallReport
```

## Available Reports

### Analytical/Dashboard Reports
- **Phone Calls Analysis** (Analysis/Dashboard)


## Report Files

- **crm_phonecall_report.py** (Python logic)
- **crm_phonecall_report_view.xml** (XML template/definition)
- **__init__.py** (Python logic)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
