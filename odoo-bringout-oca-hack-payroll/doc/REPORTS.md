# Reports

Report definitions and templates in payroll.

```mermaid
classDiagram
    class PayslipDetailsReport
    AbstractModel <|-- PayslipDetailsReport
    class ContributionRegisterReport
    AbstractModel <|-- ContributionRegisterReport
```

## Available Reports

### PDF/Document Reports
- **Payslip Contribution Register Lines** (PDF/Print)
- **Payslip** (PDF/Print)
- **PaySlip Details** (PDF/Print)


## Report Files

- **__init__.py** (Python logic)
- **report_contribution_register.py** (Python logic)
- **report_payslip_details.py** (Python logic)
- **report.xml** (XML template/definition)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
