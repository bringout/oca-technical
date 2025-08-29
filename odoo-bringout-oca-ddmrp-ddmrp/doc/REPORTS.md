# Reports

Report definitions and templates in ddmrp.

```mermaid
classDiagram
    class BomStructureReport
    AbstractModel <|-- BomStructureReport
```

## Available Reports

No named reports found in XML files.


## Report Files

- **__init__.py** (Python logic)
- **mrp_report_bom_structure.py** (Python logic)
- **mrp_report_bom_structure.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
