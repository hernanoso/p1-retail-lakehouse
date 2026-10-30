# Progress

Mark each item with `[x]` when the tutor has reviewed it.

## Step 0 · Setup
- [x] Git repo initialised with Hernan's author config and pushed to GitHub (public)
- [ ] Personal Azure account and subscription (not an employer's)
- [ ] Budget alert created in Cost Management
- [ ] Resource group created
- [ ] Azure CLI installed and `az login` works
- [ ] Explained step 0 in English

## Step 1 · ADLS Gen2
- [ ] Storage account with hierarchical namespace
- [ ] Containers `bronze`, `silver`, `gold`
- [ ] Explained in English

## Step 2 · Key Vault + Data Factory + managed identity
- [ ] Key Vault created
- [ ] Data Factory created with system-assigned managed identity
- [ ] RBAC: ADF can read/write the storage and read Key Vault secrets
- [ ] Explained in English

## Step 3 · Ingestion to Bronze
- [ ] Linked services (REST, HTTP/CSV, ADLS) using managed identity / Key Vault
- [ ] Parameterized pipeline lands raw JSON and CSV in `bronze/` by date
- [ ] Explained in English

## Step 4 · Silver
- [ ] Parquet in `silver/`
- [ ] Data-quality checks: nulls, duplicates, schema
- [ ] Explained in English

## Step 5 · Gold + Synapse serverless
- [ ] Star schema in `gold/`
- [ ] Views in Synapse serverless SQL
- [ ] Explained in English

## Step 6 · Operations
- [ ] Scheduled trigger
- [ ] Retries, failure handling, monitoring
- [ ] Explained in English

## Step 7 · Story and teardown
- [ ] README in English with architecture diagram
- [ ] 3-minute demo recorded
- [ ] Resource group deleted
