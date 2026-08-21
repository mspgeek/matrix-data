# PSA Product Features

This file contains features specific to Professional Services Automation (PSA) products.

## Company

| ID | Name | Description |
|----|------|-------------|
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
| cloud_native | Cloud-Native | Built only cloud-accessible. "Microservices" or similar architecture. |
| on_premises | On Premises | On-premises deployment option |
> On-premises deployments are installed on your own infrastructure and may require more maintenance.
| db_access | On Premises Database Access | Direct access to the database in on-premises deployments |
> Database access can be important for custom reporting and integration with other systems.
| cloud_db | Cloud DB Access | Direct Access to the database in a cloud-deployment |
| hybrid | Hybrid | Supports both cloud and on-premises deployment options |
| white_label | White Label | Ability to rebrand the solution with your own branding |


## Core Functionality

| ID | Name | Description |
|----|------|-------------|
| multi_tenant | Multi-Tenant Support | Ability to manage multiple clients/organizations within a single instance |
| mobile_app | Mobile App | Dedicated mobile application for on-the-go access |
| api | API Access | Provides API for custom integrations |
| multi_timezone | Multi-Timezone Support | The ability to support multiple (global) timezones all at once from the end-user to the technician. |
| multi_language_support | Multi-Language Support | Supports multiple languages or the ability to create your own language pack. |
| global_search | Global Search | Search globally from any area of the application, with options to filter down specifics. |


## Ticketing

| ID | Name | Description |
|----|------|-------------|
| ticketing | Ticketing | Core ticketing functionality |
| ticket_status_custom | Ticket Status Customization | Ability to customize ticket statuses |
| scheduled_tickets | Scheduled / Recurring Ticket Creation | Create tickets on a schedule or recurring basis |
| threaded_conversations | Threaded Conversations | Threaded conversation support in tickets |
| email_to_ticket | Email to Ticket creation | Create tickets from incoming emails |
| automatic_replies | Automatic Replies | Automated responses to tickets |
| agent_calendar | Agent Calendar Integrations | Calendar integration for technicians |
| dispatch | Dispatch / Ticket Assigning | Assign and dispatch tickets to technicians |
| auto_dispatch | Automated Dispatch / Assigning | Assign and dispatch tickets automatically based on different types (Round Robin/Capacity) |
| ticket_areas | Ticket Area Type (Boards, Teams) | Organize tickets by boards or teams |
| time_tracking | Time Tracking | Track time spent on tickets |
| timesheet_approval | Timesheet Approval | Submit and approve technician timesheets before they are billed |
| action_work_types | Action Based Work Types / Automatic Adjustments | Action-based billing or automatic adjustments of time entries to properly match to the business.  (After-Hours Calcs, Proper workrole billing) |
| sla | Service Level Agreements | Support for service level agreements |
| custom_sla | Custom SLA's (Per client, per contact) | Client or contact-specific SLAs |
| sla_options | SLA Options (Impact / Urgency) | Configure SLAs based on impact and urgency |
| ola | Operational Level Agreements | Support for operational level agreements |
| change_control | Change Control System | System for managing changes |
| knowledge_base | Knowledge Base / Internal Documentation | Knowledge base for internal documentation |
| services_catalog | Services Catalog | Catalog of available services |
| opportunity_ticketing | Opportunity Ticketing / Sales Ticketing | Ticketing for sales opportunities |
| attachments | Attachments | Support for file attachments in tickets |
| ticket_relationships | Ticket Merging/Childing/Linking/Splitting | Ability to relate tickets to each other |
| task_lists | Task Lists / Check List | Task lists or checklists within tickets |
| canned_responses | Canned Response Templates | Pre-defined response templates |
| work_roles | Work Role / Work Type | Define different work roles or types |
| ticket_types | Ticket Type / SubType | Categorize tickets by type and subtype |
| follow_tickets | Follow Ticket(s) | Ability to follow or watch tickets |
| ticket_priorities | Ticket Priorities | Define and set ticket priorities |
| custom_fields | Custom Fields | Add custom fields to tickets |
| add_products | Add Products to Ticket | Associate products with tickets |
| custom_ticket_info | Custom Ticket Information | Customize new ticket forms |
| rmm_integration | Deep RMM Integration | Perform RMM actions from tickets |
| email_integration | Email Integration | Connect a mailbox for sending and receiving from within the platform |
| accounting_integration | Accounting Integration | Sync invoices and payments with an accounting package |
| ai_ticketing | AI In Ticketing | AI assistance in ticketing in general |
| ticket_notes | Public Notes / Private Notes | Support for public and private notes |

## Company/Contacts/Assets

| ID | Name | Description |
|----|------|-------------|
| company_management | Company Management | Manage client companies |
| child_companies | Child Companies | Support for parent-child company relationships |
| site_management | Site Management | Manage multiple client sites |
| company_grouping | Grouping of Companies | Group companies by vertical or team |
| contact_management | Contact Management | Manage client contacts |
| duplication_handling | Duplication issues | Handle duplicate contacts or companies |
| company_imports | Automated Company Imports | Import companies automatically |
| contact_imports | Automated Contact Imports | Import contacts automatically |
| crm | CRM | Customer relationship management features |
| asset_management | Asset Management | Track and manage client assets |
| asset_assigning | Asset Assigning | Assign assets to clients or users |
| automated_asset | Automated Asset Intake/Retire | Automate asset lifecycle management |
| client_portal | Client Portal | Portal for client access |
| portal_customization | Client Portal Customization | Customize the client portal |
| portal_forms | Custom Client Portal Forms | Create custom forms for the client portal |
| inventory_management | Inventory Management | Track and manage inventory |
| proration_billing | Proration Billing | Support for prorated billing |

## Contracts/Billing/Invoicing

| ID | Name | Description |
|----|------|-------------|
| contract_support | Contract / Agreement Support | Support for client contracts and agreements |
| contract_creation | Contract Creation | Create new contracts with customizable fields |
| contract_templates | Contract Templates | Pre-defined templates for common contract types |
| contract_types | Contract Types | Define different types of contracts (Service, Support, Maintenance, etc.) |
| contract_status | Contract Status | Track contract status (Draft, Active, Expired, Terminated, etc.) |
| contract_categories | Contract Categories | Categorize contracts by type or department |
| contract_dates | Contract Dates (Start / End) | Set contract start and end dates |
| contract_renewal | Contract Renewal | Manage contract renewal process |
| auto_renewal | Auto-Renewal | Automatic contract renewal options |
| renewal_notifications | Renewal Notifications | Alerts for upcoming contract renewals |
| contract_termination | Contract Termination | Process for terminating contracts |
| contract_versions | Contract Versioning | Track different versions of contracts |
| contract_search | Contract Search | Search and filter contracts |
| contract_compliance | Contract Compliance | Ensure contract compliance |
| contract_sync | Contract Synchronization | Sync contract data across devices |
| contract_import_export | Contract Import/Export | Import/export contract data |
| charge_codes | Charge Codes / Billing Types | Define different billing rates for work types |
| billing_rates | Billing Rates | Set hourly rates for different work types |
| rate_schedules | Rate Schedules | Different rate schedules for different clients |
| rate_tiers | Rate Tiers | Tiered pricing structures |
| rate_discounts | Rate Discounts | Apply discounts to billing rates |
| product_contracts | Product / Addition to Contracts | Add products, services or other contracts to contracts |
| product_billing_dates | Product Billing Start/End Dates | Set billing dates for products |
| auto_product_updates | Automatic Updates to Product/additions | Automatically update product information |
| product_billing | Product Billing | Bill for products and services |
| product_pricing | Product Pricing | Set pricing for products and services |
| product_discounts | Product Discounts | Apply discounts to products |
| product_markups | Product Markups | Apply markups to product costs |
| product_taxes | Product Taxes | Calculate taxes on products |
| product_shipping | Product Shipping | Handle shipping costs and logistics |
| product_inventory | Product Inventory | Track product inventory levels |
| product_availability | Product Availability | Check product availability |
| product_ordering | Product Ordering | Order products from suppliers |
| product_receiving | Product Receiving | Receive and process product orders |
| product_returns | Product Returns | Handle product returns and refunds |
| product_warranty | Product Warranty | Track product warranty periods |
| product_distribution | Product Sourcing & Pricing | Sourcing of products, pricing and availability built-in (Etilize) |
| general_ledger | General Ledger Configuration | Configure general ledger settings |
| break_fix | Break-Fix (T&M) | Time and materials billing |
| ayce | AYCE W/Additions | All-you-can-eat contracts with additions |
| block_hours | Block Hours | Pre-purchased block hour contracts |
| flat_fee | Flat Fee / Single Price | Flat fee billing |
| bill_to_company | Bill To Company | Bill to the client company |
| bill_to_different | Bill To Different People | Bill to different contacts or sites |
| billing_periods | Billing Periods | Support for different billing periods |
| expense_tracking | Expense Tracking | Record and bill expenses against tickets, projects or agreements |
| recurring_billing | Recurring Billing | Automatically bill agreements on a repeating schedule |
| custom_taxing | Custom Taxing | Configure taxes by location |
| custom_bill_date | Custom Bill To Date | Set custom billing dates |
| bill_types | Bill Types | Support for different billing types |
| proration_options | Proration Options | Options for prorated billing |
| multiple_billing_hours | Multiple "Billing Hours" / Work Hours | Define different billing hours |
| invoice_templates | Custom Templates for Invoices | Customize invoice templates |
| invoicing_review | Invoicing Review | Review invoices before sending |
| invoice_creation | Invoice Creation | Create new invoices |
| invoice_customization | Invoice Customization | Customize invoice appearance and content |
| invoice_fields | Invoice Fields | Customize fields on invoices |
| invoice_totals | Invoice Totals | Calculate invoice totals |
| invoice_subtotals | Invoice Subtotals | Calculate invoice subtotals |
| invoice_taxes | Invoice Taxes | Calculate taxes on invoices |
| invoice_discounts | Invoice Discounts | Apply discounts to invoices |
| invoice_markups | Invoice Markups | Apply markups to invoices |
| invoice_currency | Invoice Currency | Support for multiple currencies |
| invoice_consolidation | Invoice Consolidation | Consolidate multiple invoices |
| invoice_voiding | Invoice Voiding | Void invoices |
| invoice_reversal | Invoice Reversal | Reverse invoices |
| invoice_credit | Invoice Credit | Create credit invoices |
| invoice_debit | Invoice Debit | Create debit invoices |
| invoice_adjustment | Invoice Adjustment | Adjust invoice amounts |
| invoice_correction | Invoice Correction | Correct invoice errors |
| invoice_email | Invoice Email | Email invoices to clients |
| invoice_notes | Invoice Notes | Add notes and comments to invoices |
| invoice_approvals | Invoice Approvals | Approval workflows for invoice decisions |
| invoice_import_export | Invoice Import/Export | Import/export invoice data |
| invoice_permissions | Invoice Permissions | Granular permissions for invoice access |
| invoice_audit_trail | Invoice Audit Trail | Track all changes and activities in invoicing |
| payment_processing | Payment Processing | Process payments from clients either built-in or through third-party |
| payment_gateways | Payment Gateways | Integration with payment gateways |
| payment_automation | Payment Automation | Automate payment processing |
| payment_scheduling | Payment Scheduling | Schedule payment processing |
| payment_notifications | Payment Notifications | Notifications for payment events |
| payment_notes | Payment Notes | Add notes and comments to payments |
| payment_import_export | Payment Import/Export | Import/export payment data |
| payment_security | Payment Security | Security controls for payment access |
| payment_audit_trail | Payment Audit Trail | Track all changes and activities in payments |

## Dashboards/Reports/KPIs

| ID | Name | Description |
|----|------|-------------|
| executive_reports | Executive Reports | Reports for executives |
| standard_reports | Standard Reports | Built-in, out-of-the-box report library |
| invoicing_reports | Invoicing Reports | Reports on invoicing |
| sla_reports | SLA Reports | Reports on SLA performance |
| dashboards | Dashboards | Dashboards for key metrics |
| custom_reporting | Custom Reporting | Create custom reports |
| custom_dashboarding | Custom Dashboarding | Create custom dashboards |

## Automations

| ID | Name | Description |
|----|------|-------------|
| new_ticket_notifications | New Ticket Notifications | Notifications for new tickets |
| ticket_updated_notifications | Ticket Updated Notifications | Notifications for ticket updates |
| ticket_closed_notifications | Ticket Closed Notifications | Notifications for closed tickets |
| sla_notification | SLA Notification | Notifications for SLA breaches |
| ticket_moving | Ticket Moving/Reassigning | Automatically move or reassign tickets |
| email_parsing | Email Parsing/Automation | Parse and automate based on emails |
| add_update_ticket | Add Update to Ticket | Automatically add updates to tickets |
| assign_to_ticket | Assign To Ticket | Automatically assign tickets |
| email_end_user | Email End User | Automatically email end users |
| email_company_contact | Email Company Contact | Automatically email company contacts |
| email_custom | Email Custom | Custom email automations |
| update_sla | Update SLA | Automatically update SLAs |
| change_status | Change Status | Automatically change ticket status |

## Project Management

| ID | Name | Description |
|----|------|-------------|
| project_management | Overall Project Management Module | Comprehensive project management functionality |
| project_types | Project Types | Define different project types |
| project_templates | Project Templates | Templates for common project types |
| project_creation | Project Creation | Create new projects with customizable fields |
| project_status | Project Status Management | Track and manage project status (Planning, Active, On Hold, Completed, etc.) |
| project_priorities | Project Priorities | Set and manage project priority levels |
| project_categories | Project Categories | Categorize projects by type or department |
| project_budgeting | Project Budgeting | Set and track project budgets |
| budget_tracking | Budget Tracking | Monitor actual vs. planned project costs |
| budget_alerts | Budget Alerts | Alerts when project approaches or exceeds budget |
| project_timeline | Project Timeline | Visual timeline view of project milestones and deadlines |
| project_scheduling | Project Scheduling | Schedule project tasks and milestones |
| gantt_charts | Gantt Charts | Visual project timeline with dependencies |
| critical_path | Critical Path Analysis | Identify critical tasks and dependencies |
| resource_planning | Resource Planning | Plan and allocate resources for projects |
| resource_availability | Resource Availability | Check technician availability for project tasks |
| resource_utilization | Resource Utilization | Track how resources are being utilized across projects |
| project_phases | Project Phases | Break projects into manageable phases |
| phase_templates | Phase Templates | Templates for common project phases |
| phase_dependencies | Phase Dependencies | Define dependencies between project phases |
| project_milestones | Project Milestones | Define and track project milestones |
| milestone_tracking | Milestone Tracking | Track progress toward project milestones |
| milestone_notifications | Milestone Notifications | Notifications for milestone deadlines and completions |
| project_tasks | Project Tasks | Create and manage tasks within projects |
| task_management | Task Management | Comprehensive task creation, assignment, and tracking |
| task_dependencies | Task Dependencies | Define dependencies between project tasks |
| task_assignments | Task Assignments | Assign tasks to specific technicians or teams |
| task_priorities | Task Priorities | Set priority levels for individual tasks |
| task_status | Task Status | Track task status (Not Started, In Progress, Completed, etc.) |
| task_estimation | Task Estimation | Estimate time and effort for project tasks |
| task_tracking | Task Tracking | Track progress on individual tasks |
| task_completion | Task Completion | Mark tasks as complete with completion notes |
| subtasks | Subtasks | Break down tasks into smaller subtasks |
| task_templates | Task Templates | Pre-defined templates for common tasks |
| kanban_views | Kanban Views | Kanban board views for project tasks |
| project_boards | Project Boards | Visual board interface for project management |
| board_customization | Board Customization | Customize board columns and workflows |
| project_dashboards | Project Dashboards | Dashboards showing project metrics and status |
| project_reports | Project Reports | Generate reports on project progress and performance |
| project_analytics | Project Analytics | Analytics and insights on project performance |
| project_metrics | Project Metrics | Track key project metrics (time, cost, quality) |
| project_kpis | Project KPIs | Key performance indicators for projects |
| project_health | Project Health | Overall project health indicators |
| project_risks | Project Risk Management | Identify and manage project risks |
| risk_assessment | Risk Assessment | Assess and categorize project risks |
| risk_mitigation | Risk Mitigation | Plan and track risk mitigation strategies |
| project_issues | Project Issues | Track and manage project issues |
| issue_tracking | Issue Tracking | Comprehensive issue tracking within projects |
| issue_resolution | Issue Resolution | Track issue resolution progress |
| project_change_management | Project Change Management | Manage changes to project scope, timeline, or budget |
| change_requests | Change Requests | Formal process for requesting project changes |
| change_approval | Change Approval | Approval workflow for project changes |
| project_communication | Project Communication | Centralized communication for project stakeholders |
| project_notes | Project Notes | Add notes and comments to projects |
| project_documents | Project Documents | Store and manage project-related documents |
| document_versioning | Document Versioning | Version control for project documents |
| project_collaboration | Project Collaboration | Tools for team collaboration on projects |
| stakeholder_management | Stakeholder Management | Manage project stakeholders and their involvement |
| project_approvals | Project Approvals | Approval workflows for project decisions |
| project_sign_off | Project Sign-off | Formal sign-off process for project completion |
| project_lessons_learned | Lessons Learned | Capture and document lessons learned from projects |
| project_post_mortem | Project Post-Mortem | Post-project analysis and review |
| project_archiving | Project Archiving | Archive completed projects for future reference |
| project_duplication | Project Duplication | Duplicate existing projects as templates |
| project_import_export | Project Import/Export | Import/export project data |
| project_integration | Project Integration | Integration with other business systems |
| project_api | Project API | API access for project management functionality |
| project_mobile | Project Mobile Access | Mobile access to project management features |
| project_offline | Project Offline Access | Work on projects when offline |
| project_sync | Project Synchronization | Sync project data across devices |
| project_backup | Project Backup | Backup project data and configurations |
| project_restore | Project Restore | Restore project data from backups |
| project_security | Project Security | Security controls for project access and data |
| project_permissions | Project Permissions | Granular permissions for project access |
| project_audit_trail | Project Audit Trail | Track all changes and activities within projects |
| project_time_tracking | Project Time Tracking | Track time spent on project tasks |
| project_billing | Project Billing | Bill clients for project work |
| project_invoicing | Project Invoicing | Generate invoices for project work |
| project_products | Project Products | Associate products with projects |
| project_contracts | Project Contracts | Link projects to client contracts |
| project_quotations | Project Quotations | Generate quotations for project work |
| project_proposals | Project Proposals | Create and manage project proposals |
| project_estimates | Project Estimates | Create detailed project estimates |
| project_scope | Project Scope Management | Define and manage project scope |
| scope_creep | Scope Creep Management | Track and manage scope changes |
| project_quality | Project Quality Management | Ensure project deliverables meet quality standards |
| quality_checklists | Quality Checklists | Checklists for quality assurance |
| project_deliverables | Project Deliverables | Track and manage project deliverables |
| deliverable_approval | Deliverable Approval | Approval process for project deliverables |
| project_handover | Project Handover | Formal handover process for completed projects |
| project_warranty | Project Warranty | Track warranty periods for project deliverables |
| project_maintenance | Project Maintenance | Ongoing maintenance for project deliverables |
