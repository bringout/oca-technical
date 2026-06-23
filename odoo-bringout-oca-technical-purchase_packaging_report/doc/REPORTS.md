# Reports

Report definitions and templates in purchase_packaging_report.

```mermaid
classDiagram
    class PurchaseReport
    Model <|-- PurchaseReport
```

## Available Reports

No named reports found in XML files.


## Report Files

- **__init__.py** (Python logic)
- **purchase_order_templates.xml** (XML template/definition)
- **purchase_quotation_templates.xml** (XML template/definition)
- **purchase_report.py** (Python logic)
- **purchase_report_views.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
