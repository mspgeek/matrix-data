# RMM Product Features

This file contains features specific to Remote Monitoring & Management (RMM) products.

## Company

| ID | Name | Description |
|----|------|-------------|
| last_updated_date | Date last verified or updated |
| parent | Parent | Parent Company |
| emp_size | Employee Size | Size of the company or division |
| founded | Founded | Year the company was founded |
| headquarters | Headquarters | Location of company headquarters |
| public_private | Public/Private | Whether the company is publicly traded or privately held |
| acquisition | Acquisition | Details about any acquisitions |

## Architecture

| ID | Name | Description |
|----|------|-------------|
| cloud | Cloud | Cloud-based deployment option |
> Cloud-based deployments are hosted by the vendor and typically require no infrastructure management.

| on_premises | On Premises | On-premises deployment option |
> On-premises deployments are installed on your own infrastructure and may require more maintenance.

| db_access | On Premises Database Access | Direct access to the database in on-premises deployments |
> Database access can be important for custom reporting and integration with other systems.

| hybrid | Hybrid | Supports both cloud and on-premises deployment options |
| multi_tenant | Multi-Tenant Support | Ability to manage multiple clients/organizations within a single instance |
| white_label | White Label | Ability to rebrand the solution with your own branding |

## Core Features

| ID | Name | Description |
|----|------|-------------|
| patch_management | Patch Management | Ability to deploy and manage patches for operating systems and applications |
> Patch management is a critical security feature for maintaining up-to-date systems.
> Most RMM tools offer some form of patch management, but capabilities can vary significantly.

| remote_access | Remote Access | Ability to remotely access and control devices |
> Remote access allows technicians to troubleshoot and resolve issues without being physically present.

| monitoring | Monitoring | Ability to monitor device health and performance |
> Monitoring capabilities typically include CPU, memory, disk usage, and other system metrics.
> Some tools offer more advanced monitoring features like application-specific monitoring.

| run_scripts | Run Scripts | Ability to run scripts on endpoints |

| mobile_app | Mobile App | Dedicated mobile application for on-the-go access |
| api_access | API Access | Provides API for custom integrations |
| self_service_portal | Self-Service Portal | Portal for end-users to request support or access resources |
| reporting | Reporting | Built-in reporting capabilities |
| automation | Automation | Ability to automate routine tasks and workflows |
| asset_management | Asset Management | Tracking and management of hardware and software assets |
| network_topology | Network Topology | Visual mapping of network infrastructure |
| documentation | Documentation | Built-in documentation capabilities |
| knowledge_base | Knowledge Base | Repository of troubleshooting and support information |

## Scripting/Engine

| ID | Name | Description |
|----|------|-------------|
| powershell | PowerShell Support | Support for PowerShell scripting |
| bash | Bash/Shell Support | Support for Bash/Shell scripting |
| python | Python Support | Support for Python scripting |
| script_library | Script Library | Pre-built script library available |
| script_scheduling | Script Scheduling | Ability to schedule scripts to run at specific times |
| custom_scripts | Custom Scripts | Ability to create and run custom scripts |
| script_templates | Script Templates | Pre-built templates for common scripting tasks |

## Monitoring

| ID | Name | Description |
|----|------|-------------|
| server_monitoring | Server Monitoring | Monitoring capabilities for servers |
| workstation_monitoring | Workstation Monitoring | Monitoring capabilities for workstations |
| network_monitoring | Network Monitoring | Monitoring capabilities for network devices |
| custom_monitors | Custom Monitors | Ability to create custom monitoring checks |
| snmp_monitoring | SNMP Monitoring | Support for SNMP monitoring |
| alert_management | Alert Management | Management and configuration of monitoring alerts |
| threshold_based | Threshold-Based Monitoring | Monitoring based on defined thresholds |
| event_log_monitoring | Event Log Monitoring | Monitoring of system and application event logs |
| service_monitoring | Service Monitoring | Monitoring of Windows/Linux services |
| process_monitoring | Process Monitoring | Monitoring of system processes |
| performance_monitoring | Performance Monitoring | Monitoring of system performance metrics |

## User Application Experience

| ID | Name | Description |
|----|------|-------------|
| app_performance | Application Performance Monitoring | Monitoring of application performance metrics |
| user_experience | User Experience Monitoring | Monitoring of end-user experience metrics |
| synthetic_monitoring | Synthetic Transaction Monitoring | Simulated user interactions to test application performance |
| browser_monitoring | Browser Performance Monitoring | Monitoring of web browser performance |
| session_recording | Session Recording | Recording of user sessions for troubleshooting |
| application_control | Application Control | Control over which applications can run |

## Patching

| ID | Name | Description |
|----|------|-------------|
| windows_patching | Windows Patching | Automated patching for Windows systems |
| third_party_patching | Third-Party Patching | Patching for third-party applications |
| patch_approval | Patch Approval Workflow | Workflow for approving patches before deployment |
| patch_scheduling | Patch Scheduling | Ability to schedule when patches are applied |
| os_patching | Non-Windows OS Patching | Patching for non-Windows operating systems (macOS, Linux) |
| patch_reporting | Patch Reporting | Reporting on patch status and compliance |
| patch_testing | Patch Testing | Ability to test patches before deployment |
| patch_rollback | Patch Rollback | Ability to roll back problematic patches |

## Security

| ID | Name | Description |
|----|------|-------------|
| antivirus | Antivirus | Built-in or integrated antivirus capabilities |
| backup | Backup | Built-in or integrated backup capabilities |
| vulnerability_scanning | Vulnerability Scanning | Scanning for security vulnerabilities |
| disk_encryption | Disk Encryption Management | Management of disk encryption solutions |
| mfa | MFA Support | Multi-factor authentication support |
| ransomware_detection | Ransomware Detection | Detection of ransomware activity |
| endpoint_protection | Endpoint Protection | Comprehensive endpoint security features |
| firewall_management | Firewall Management | Management of firewall settings |
| security_policies | Security Policies | Enforcement of security policies |
| compliance_reporting | Compliance Reporting | Reporting on security compliance |
| siem_integration | SIEM Integration | Integration with Security Information and Event Management systems |

## PSA Integration

| ID | Name | Description |
|----|------|-------------|
| built_in_psa | Built-In PSA | Single system with PSA functionality |
| connectwise_manage | ConnectWise Manage Integration | Integration with ConnectWise Manage PSA |
| datto_autotask | Datto Autotask Integration | Integration with Datto Autotask PSA |
| halo_psa | HaloPSA Integration | Integration with HaloPSA |
| kaseya_bms | Kaseya BMS Integration | Integration with Kaseya BMS |
| syncro | Syncro Integration | Integration with Syncro PSA |
| tigerpaw | Tigerpaw Integration | Integration with Tigerpaw PSA |
| atera | Atera Integration | Integration with Atera PSA |
| servicenow | ServiceNow Integration | Integration with ServiceNow |
| accelo | Accelo Integration | Integration with Accelo PSA |
| computicate | Computicate Integration | Integration with Computicate PSA |
| harmony | Harmony Integration | Integration with Harmony PSA |
| n-able_msp_manager | N-able MSP Manager Integration | Integration with N-able MSP Manager PSA |

## Backup & Disaster Recovery

| ID | Name | Description |
|----|------|-------------|
| file_backup | File Backup | Backup of individual files and folders |
| image_backup | Image Backup | Full system image backup capabilities |
| cloud_backup | Cloud Backup | Backup to cloud storage |
| local_backup | Local Backup | Backup to local storage |
| backup_scheduling | Backup Scheduling | Scheduling of backup jobs |
| backup_monitoring | Backup Monitoring | Monitoring of backup job status |
| backup_reporting | Backup Reporting | Reporting on backup status and compliance |
| disaster_recovery | Disaster Recovery | Comprehensive disaster recovery capabilities |
| backup_testing | Backup Testing | Testing of backup integrity and recoverability |

## Mobile Device Management

| ID | Name | Description |
|----|------|-------------|
| mdm | Mobile Device Management | Management of mobile devices |
| byod_support | BYOD Support | Support for Bring Your Own Device policies |
| mobile_app_management | Mobile App Management | Management of mobile applications |
| mobile_security | Mobile Security | Security features for mobile devices |
| mobile_monitoring | Mobile Monitoring | Monitoring of mobile device health and performance |
| mobile_remote_control | Mobile Remote Control | Remote control of mobile devices |
| mobile_wipe | Mobile Wipe | Ability to remotely wipe mobile devices |

## Reporting & Analytics

| ID | Name | Description |
|----|------|-------------|
| standard_reports | Standard Reports | Pre-built standard reports |
| custom_reports | Custom Reports | Ability to create custom reports |
| scheduled_reports | Scheduled Reports | Scheduling of report generation and delivery |
| executive_reports | Executive Reports | High-level reports for executive review |
| client_reports | Client Reports | Reports designed for client consumption |
| dashboard | Dashboard | Customizable dashboard for key metrics |
| business_intelligence | Business Intelligence | Advanced analytics and business intelligence features |
| report_export | Report Export | Export of reports to various formats |

## Pricing & Licensing

| ID | Name | Description |
|----|------|-------------|
| per_device | Per Device Pricing | Pricing based on number of devices |
| per_user | Per User Pricing | Pricing based on number of users |
| per_technician | Per Technician Pricing | Pricing based on number of technicians |
| tiered_pricing | Tiered Pricing | Pricing tiers based on features or usage |
| all_inclusive | All-Inclusive Pricing | Single price including all features |
| free_trial | Free Trial | Availability of free trial |
| money_back | Money-Back Guarantee | Availability of money-back guarantee |
| contract_required | Contract Required | Whether a contract is required |
| minimum_commitment | Minimum Commitment | Minimum commitment period or device count | 