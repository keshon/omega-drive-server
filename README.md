# How to setup Server environment
## Make Airtable Account and create a table
Recreate two tabs as it shown on screenshots:
`airtable_paths_tab.png`
`airtable_users_tab.png`

## Install N8n.io api orchestrator
Import supplied workflow `n8n.io_workflow.json` and update paths if needed.

# How is it working
N8n acts as a webhook server and Airtable serves as a database.
Whenever clients access to N8n with a payload (acccess key) N8N search for mapped paths  for this key in Airtable table.