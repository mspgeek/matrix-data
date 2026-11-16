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
  > Findings, reports and scan history are kept per client.
- api_access: Limited
  > Upload API for sending scan files.
- agent_based: false
- agentless: true
  > Nothing is installed on endpoints. Scan Hub reads results from the scanners you already run.
- vulnerability_scanning: false
  > Not a scanner. It reads exports from Nessus, Greenbone/OpenVAS, Qualys, Rapid7, Nuclei, Burp and Microsoft Defender, plus CSV, XML, JSON and PDF reports, and connects directly to Defender Vulnerability Management and ConnectSecure.
- network_scanning: false
- web_app_scanning: false
- patch_management: false
- remediation_automation: false
- vulnerability_scoring: true
- cvss_support: true
- vulnerability_aging: true
- vulnerability_correlation: true
  > Results from several scanners are ranked in one list per client.
- exploit_availability: true
  > CISA KEV and EPSS are shown for each finding that has a CVE.
- threat_intelligence: Limited
  > CISA KEV and EPSS.
- risk_acceptance: true
  > Clients can sign off accepted risk on a decision page.
- remediation_guidance: true
- remediation_prioritization: true
  > Fixed priority bands; CISA KEV entries used by ransomware come first.
- remediation_tracking: true
- remediation_validation: true
  > Each rescan is compared with the previous one to show what was fixed, what is new and what is still open.
- remediation_approval: true
  > PSA tickets are drafted per fix and created only after review and approval.
- executive_reporting: true
- technical_reporting: true
- comparative_analysis: true
- data_import_export: true
- ticketing_integration: true
- psa_integration: true
  > ConnectWise PSA and HaloPSA.
- connectwise_manage: true
- autotask: false
- white_label: true
- client_reporting: true
- client_portal: Limited
  > A client decision page for approving fixes and signing off risk.
- trial_available: true
  > 14 days, no card needed.
- tiered_pricing: true
- monthly_billing: true
- subscription_license: true

### Company Information
- parent: Varaxon Technologies LLC
- public_private: Private
- acquisition: None
