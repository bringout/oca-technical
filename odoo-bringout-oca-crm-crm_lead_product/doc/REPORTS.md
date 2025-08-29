# Reports

Report definitions and templates in crm_lead_product.

```mermaid
classDiagram
    class ActivityReport
    Model <|-- ActivityReport
```

## Available Reports

### Analytical/Dashboard Reports
- **Pipeline by Product Analysis** (Analysis/Dashboard)


## Report Files

- **crm_product_report.py** (Python logic)
- **crm_product_report_views.xml** (XML template/definition)
- **__init__.py** (Python logic)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
