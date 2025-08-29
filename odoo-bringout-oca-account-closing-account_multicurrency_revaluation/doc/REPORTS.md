# Reports

Report definitions and templates in account_multicurrency_revaluation.

```mermaid
classDiagram
    class ShellAccount
    object <|-- ShellAccount
    class CurrencyUnrealizedReport
    AbstractModel <|-- CurrencyUnrealizedReport
```

## Available Reports

### PDF/Document Reports
- **Currency Revaluation Report** (PDF/Print)


## Report Files

- **currency_unrealized_report.py** (Python logic)
- **__init__.py** (Python logic)
- **report.xml** (XML template/definition)
- **unrealized_currency_gain_loss.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
