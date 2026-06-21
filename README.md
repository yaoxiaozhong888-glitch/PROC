# Bank PostgreSQL Migration Workspace

This workspace is organized for bank-style PostgreSQL migration development with ECPG, C, SQL, shell scripts, AWS assets, and Git.

## Directory Layout




```text
src/          ECPG, C source files, and shared headers
sql/          PostgreSQL DDL, DML, functions, indexes, grants, and rollback SQL
migrations/   Migration scripts, data conversion steps, validation, and rollback plans
scripts/      Build, database, AWS, deployment, and operations shell scripts
config/       Environment-specific configuration files
aws/          AWS infrastructure notes and IaC assets
tests/        Unit, SQL, integration, and migration validation tests
docs/         Architecture, migration plan, operations, and security documents
.vscode/      VSCode workspace settings and recommended extensions
```

## Suggested Naming

Use clear bank-domain names:

```text
customer_migration.pgc
account_balance_check.sql
daily_reconcile.sh
validate_account_totals.sql
rollback_customer_schema.sql
```

Prefer `object_action.ext`, for example `account_validate.sql` or `loan_contract_loader.pgc`.

