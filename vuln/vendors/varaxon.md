# Varaxon
type: vuln

## Varaxon Scan Hub
- id: varaxon_scan_hub
- website: https://varaxontech.com/
- defaultVisible: true

### Features
- cloud: true
- on_premises: false
- hybrid: false
- saas: true
- multi_tenant: true
  > One account holds many clients. Findings, reports and scan history are kept per client.
- api_access: true
  > Upload API: send a scan file from a script and get the report back. Keys can be limited to chosen clients, set to read only, given an expiry date and rotated.
- agent_based: false
- agentless: true
  > Nothing is installed on endpoints. Scan Hub reads results from the scanners you already run.
- asset_inventory: Limited
  > A software inventory per client, built from the scan results.
- vulnerability_scanning: false
  > Not a scanner. It reads exports from Nessus, Greenbone/OpenVAS, Qualys, Rapid7, Nuclei, Burp and Microsoft Defender, plus other CSV, XML and JSON files and PDF scan reports.
- network_scanning: false
- web_app_scanning: false
- scheduled_scanning: Limited
  > No scanning of its own. Connected Microsoft Defender Vulnerability Management and ConnectSecure accounts are checked every day for new results.
- vulnerability_scoring: true
- cvss_support: true
- vulnerability_trending: true
  > Open findings per priority band are tracked across scans for each client.
- vulnerability_aging: true
  > Shows how long each finding has been open.
- vulnerability_correlation: true
  > Results from several scanners are ranked in one list per client.
- exception_management: true
  > A finding can be fixed, ticketed or accepted, and the decision is recorded.
- vulnerability_verification: Limited
  > Proof of fix: a finding counts as fixed only when a later scan shows it gone.
- exploit_availability: true
  > CISA KEV status, ransomware use and the EPSS score are shown for each finding that has a CVE.
- threat_intelligence: Limited
  > CISA KEV and EPSS.
- risk_acceptance: true
  > Clients can sign off accepted risk on a decision page, and the sign-off is kept on record.
- remediation_guidance: true
  > Each finding comes with fix steps in plain words.
- remediation_workflows: true
  > Review the ranked fixes, get the client's decision, raise tickets, then confirm on the next scan.
- remediation_prioritization: true
  > Fixed priority bands: CISA KEV entries used by ransomware first, then other KEV entries, then CVSS 9.0 and above.
- remediation_automation: false
- patch_management: false
- remediation_tracking: true
- remediation_validation: true
  > Each rescan is compared with the previous one to show what was fixed, what is new and what is still open.
- remediation_delegation: Integration
  > Fixes are handed to technicians as ConnectWise PSA or HaloPSA tickets.
- remediation_approval: true
  > PSA tickets are drafted per fix and created only after review and approval. Clients can approve fixes on their decision page.
- executive_reporting: true
  > A plain-language summary for the client, plus a quarterly business review (QBR) PDF per client.
- technical_reporting: true
  > Every finding is listed with its evidence from the scan.
- trend_analysis: true
- comparative_analysis: true
  > Scan-to-scan comparison per client.
- data_export: true
  > Reports as PDF, client decisions as CSV, and a full export of the account's data.
- evidence_collection: true
  > Proof packs gather the scans, fixes and sign-offs for a client into one evidence file for audits and insurers.
- ticketing_integration: true
- psa_integration: true
  > ConnectWise PSA and HaloPSA.
- connectwise_manage: true
- autotask: false
- servicenow: false
- jira: false
- api_integration: true
- data_import_export: true
- slack_integration: false
- teams_integration: false
- role_based_access: true
  > Owner, admin and member roles.
- multi_factor_auth: true
  > Required for every user.
- audit_logging: true
  > An activity log for the account.
- data_encryption: true
  > Encrypted in transit and at rest.
- secure_communications: true
- api_security: true
  > API keys are stored only as a hash and can be scoped, expired, rotated and revoked.
- ip_restrictions: Limited
  > API keys can be limited to chosen IP addresses or ranges.
- data_retention: true
  > Raw scan uploads are deleted within 7 days.
- white_label: true
  > Reports carry the MSP's own branding.
- multi_tenant_management: true
- client_reporting: true
- msp_dashboard: true
  > One clients page shows where every client stands.
- client_isolation: true
  > Each organization's data is kept separate in the database.
- client_portal: Limited
  > A client decision page for approving fixes and signing off risk.
- per_scan: Per report
- tiered_pricing: true
- trial_available: true
  > 14 days, no card needed.
- monthly_billing: true
- subscription_license: true

### Company Information
- parent: Varaxon Technologies LLC
- public_private: Private
- acquisition: None
