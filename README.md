# Customized ServiceNow Connector

This connector is a modified version of the original ServiceNow Connector from the Elastic Connectors repository.

I've added a number of tables that can be indexed from ServiceNow using this customized connector code.

## Added Tables

The following tables have been added to the connector:

- `incident`: ["admin", "sn_incident_read", "ml_report_user", "ml_admin", "itil"]
- `kb_knowledge`: ["admin", "knowledge", "knowledge_manager", "knowledge_admin"]
- `change_request`: ["admin", "sn_change_read", "itil"]
- `cmn_location`: ["admin"]
- `cmn_department`: ["admin"]
- `u_executive_owner`: ["admin"]
- `core_country`: ["admin"]
- `u_regions`: ["admin"]
- `cmdb_ci`: ["admin"]
- `cmdb_ci_application`: ["admin"]
- `rm_release`: ["admin"]
- `problem`: ["admin"]
- `u_integration`: ["admin"]
- `cmdb_ci_business_app`: ["admin"]
- `core_country.u_change_country_cluster`: ["admin"]
