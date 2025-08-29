# Security

Access control and security definitions in ddmrp.

## Access Control Lists (ACLs)

Model access permissions defined in:
- **[ir.model.access.csv](../ddmrp/security/ir.model.access.csv)**
  - 20 model access rules

## Record Rules

Row-level security rules defined in:
- **[ddmrp_rules.xml](../ddmrp/security/ddmrp_rules.xml)**

## Security Groups & Configuration

Security groups and permissions defined in:
- **[ddmrp_groups.xml](../ddmrp/security/ddmrp_groups.xml)**
  - 3 security groups defined
- **[ddmrp_rules.xml](../ddmrp/security/ddmrp_rules.xml)**

```mermaid
graph TB
    subgraph "Security Layers"
        A[Users] --> B[Groups]
        B --> C[Access Control Lists]
        C --> D[Models]
        B --> E[Record Rules]
        E --> F[Individual Records]
    end
```

Security files overview:
- **[ddmrp_groups.xml](../ddmrp/security/ddmrp_groups.xml)**
  - Security groups, categories, and XML-based rules
- **[ddmrp_rules.xml](../ddmrp/security/ddmrp_rules.xml)**
  - Security groups, categories, and XML-based rules
- **[ir.model.access.csv](../ddmrp/security/ir.model.access.csv)**
  - Model access permissions (CRUD rights)

Notes
- Access Control Lists define which groups can access which models
- Record Rules provide row-level security (filter records by user/group)
- Security groups organize users and define permission sets
- All security is enforced at the ORM level by Odoo
