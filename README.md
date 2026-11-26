Sovereign Enterprise Desktop Suite (SEDS)
> A local-first, cross-platform enterprise workspace engineered for complete data sovereignty, zero cloud lock-in, and high-performance offline execution—anchored by the royalty-free .seds open workbook standard.
> 
Built on Electron.js, Sovereign Enterprise Desktop Suite (SEDS) provides a portal-free desktop workspace for Windows, macOS, and Linux. SEDS operates directly on local file systems and enterprise network drives while integrating a tri-format spreadsheet engine (.seds, .xlsx, and Google Sheets), AI-assisted automation, local-network mobile hardware bridges (wireless camera barcode scanning and rule-based SMS ingestion), and an intelligent data-mapping workbench.
1. Core Value Proposition
 * Complete Data Sovereignty & Zero Vendor Lock-In: All workbooks, JSON configurations, ledgers, and operational artifacts stay strictly on local storage or enterprise network shares—backed by the open, license-free .seds file format alongside full Excel and Google Sheets interoperability.
 * Portal-Free Standalone Distribution: Distributed as native standalone binaries (.exe, .app, AppImage) with built-in offline cryptographic license validation and a Zero-License Viewer Tier for frictionless enterprise-wide report distribution.
 * Macro-Free Security Architecture: Eliminates legacy VBA scripts and macro attack surfaces by executing all business logic through safe, deterministic spreadsheet formulas and administrator-signed extension packages.
 * Local Mobile Hardware Bridge: Pairs directly over local Wi-Fi/LAN with smartphones via a one-time cryptographic QR handshake—turning mobile cameras into wireless POS barcode scanners and parsing transactional SMS alerts straight into accounting ledgers without cloud relays.
2. System Architecture & Deployment Topology
┌─────────────────────────────────────────────────────────────────────────────┐
│                   SEDS Desktop Client (Electron.js Runtime)                 │
│               Windows (.exe)  │  macOS (.app)  │  Linux (AppImage)          │
├─────────────────────────────────────────────────────────────────────────────┤
│  UI & Collaboration Layer                                                   │
│  • Domain Workspaces & Custom Ribbon   • LAN Live Co-Working & Check-Out/In │
│  • In-App Chat, Threads & Alerts       • Visual Data Mapping Workbench      │
├─────────────────────────────────────────────────────────────────────────────┤
│  Core Engines                                                               │
│  • Tri-Format Spreadsheet Engine (.seds / .xlsx / Google Sheets + Pivots)   │
│  • Connected Sheets Linker             • Macro-Free Formula Evaluator       │
│  • AI Automation Engine (OpenAI BYOK)  • JSON Config & Governance Engine    │
├─────────────────────────────────────────────────────────────────────────────┤
│  Connectivity & Local Hardware Bridges                                      │
│  • Enterprise DB / REST ETL / OData    • LAN WebSocket Mobile Companion     │
│  • Outlook Exchange & Gmail Exporters  • Signed Encrypted Plugin Loader     │
└───────┬──────────────────────────┬──────────────────────────┬───────────────┘
        │                          │                          │
        ▼                          ▼                          ▼
┌───────────────────┐    ┌─────────────────────┐    ┌─────────────────────────┐
│ Local File System │    │ Enterprise Systems  │    │ Mobile Companion (LAN)  │
│ & Network Drives  │    │ • SQL / Enterprise  │    │ • QR Handshake Pairing  │
│ • .seds / .xlsx   │    │   Databases         │    │ • Camera Barcode/QR POS │
│ • JSON Settings   │    │ • REST / OData APIs │    │ • Regex SMS Ingestion   │
│ • Signed Licenses │    │ • OpenAI API (BYOK) │    │   (No Cloud Relay)      │
└───────────────────┘    └─────────────────────┘    └─────────────────────────┘

Deployment & Licensing Model
 * Cross-Platform Native Packaging: Single codebase compiled into standalone executables for Windows (.exe), macOS (.app), and Linux (AppImage).
 * Offline Cryptographic Licensing: Independently verifies local license status, validates cryptographic signature files, and tracks workspace file creation without external licensing portals.
 * Two-Tier Access Model:
   * Licensed Author Tier: Full authoring, template creation, data ingestion, integration configuration, and multi-format export capabilities.
   * Zero-License Viewer Tier: Free read/view access across the organization for .seds, .xlsx, and exported reports—enabling zero-cost enterprise distribution.
 * Hybrid Collaboration: Supports real-time synchronous co-working over local area networks (LAN) alongside structured offline checkout/check-in workflows.
3. Security & Governance Controls
| Security Control | Implementation Details |
|---|---|
| Local-First Persistence | All .seds workbooks, spreadsheets, and lightweight JSON configuration files reside strictly on local disks or designated enterprise network drives. |
| Thick-Client Protection | Optional user-configured master password required at thick-client startup to protect local workspace access. |
| Macro-Free Execution | Complete elimination of VBA scripts and executable macros; calculations rely exclusively on standardized, deterministic spreadsheet formulas. |
| Signed Extension Governance | Custom UI ribbons, plugins, and domain templates are distributed as encrypted extension bundles issued exclusively by authorized administrators/licensors. |
| Platform Access Governance | Local role definitions, workspace permission boundaries, and controlled authentication (OAuth and Basic Auth) for external data connectors. |
4. Core Data Engine & the .seds Open Sovereign Format
SEDS provides three-way interoperability across open and commercial spreadsheet ecosystems, anchored by its native, royalty-free .seds file standard:
4.1 Native .seds Sovereign Workbook (Free Open Alternative)
 * Zero Proprietary License Dependency: A free, open, self-contained archive format requiring zero Microsoft Office or Google Workspace licenses to create, inspect, automate, or archive.
 * Canonical Internal Structure: Packaged as a standard compressed container (artifact.seds) composed of human-readable, Git-diffable JSON components:
   project-budget.seds
├── manifest.json             # Format spec version, metadata, sheet index & SHA-256 hashes
├── signature.sig             # Optional cryptographic signature & license tier attestation
├── workbook.json             # Sheet grids, cell values, macro-free formulas & styles
├── connected-sources.json    # Connected Sheets links (local files, DB/REST queries, SMS rules)
├── taxonomy-schema.json      # Field types, validation constraints & Mapping Workbench profiles
├── charts-pivots.json        # Portable chart & pivot table definitions
└── collaboration/
    ├── comments.json         # Contextual commenting threads & resolution status
    └── audit-log.json        # Tamper-evident local edit & checkout/check-in history

 * Built-In Integrity & Auditability: Natively embeds SHA-256 tamper verification, checkout/check-in audit trails, and contextual discussion threads directly inside the single portable file.
4.2 Tri-Format Interoperability & Connected Data
 * Lossless Conversion (.seds ↔ .xlsx ↔ Google Sheets): Native read, write, and full structural/visual compatibility for formulas, charts, and pivot tables across all three formats.
 * Connected Sheets: Real-time data linking across multiple .seds workbooks, Excel files, network spreadsheets, and external enterprise data feeds.
 * Lightweight JSON Configuration: Human-readable JSON files govern system settings, contact directories, and enterprise parameter dictionaries.
5. Enterprise Functional Modules
SEDS ships with ready-to-use .seds templates and operational modules across five core business domains:
| Enterprise Domain | Included Modules & Artifact Templates |
|---|---|
| Strategy & Architecture | Business Model Canvas, Value Proposition Design, Enterprise Architecture (EA) Artifacts, Strategy Definition & Execution Tracking, SAFe Agile Product Management. |
| Finance & Human Resources | Country-specific Payroll Calculation Engines, Multi-Jurisdiction Tax Management, Resource Allocation & Capacity Management. |
| Operations & Supply Chain | Point of Sale (POS), Warehouse & Inventory Management, Customer Account Management (CRM), Fleet Management. |
| Communications & Governance | EA Application Data, Application Integration Maps, Infrastructure Portfolios, Configurable Social Media Integration, WhatsApp Business Gateway. |
| Productivity & Workspace | In-app Chat, Contextual Commenting Threads, Real-time In-App Notifications, Outlook Exchange & Gmail Template Exporters with Advanced Filtering. |
6. Mobile Companion & Hardware Bridge (Camera & SMS)
SEDS bridges desktop workflows with mobile hardware over the local network only—eliminating external cloud relays:
 * Zero-Cloud LAN Pairing: Pairs the desktop client with a smartphone over local WebSocket/LAN via a one-time cryptographic QR code handshake.
 * Wireless Camera POS & Warehouse Scanner:
   * Uses the smartphone's native camera as a wireless barcode and QR code scanner.
   * Streams scanned items directly into active desktop POS transaction queues and warehouse picking logs.
 * Rule-Based Mobile SMS Ingestion & Parsing:
   * Selectively ingests targeted SMS threads or transactional sender IDs (bank alerts, payment confirmations, customer orders).
   * Applies configurable Regular Expression (Regex) and rule-based parsers to extract structured parameters (timestamps, amounts, senders, reference codes) and writes them directly into accounting ledgers, POS cash reconciliation sheets, and CRM logs.
7. Intelligent Data Import & Field Mapping Workbench
 * Universal Bulk Import: Imports external raw data from .seds, .csv, .xlsx, and Google Sheets exports into standardized enterprise templates (project portfolios, asset registers, customer directories).
 * Heuristic Auto-Mapping: Automatically scans incoming column headers and semantically matches them to target template schema fields (e.g., mapping Proj_Name or Project Title to internal schema fields).
 * Visual Mapping Workbench: Interactive drag-and-drop and dropdown mapping interface allowing users to review, override, and define custom data transformation rules.
 * Pre-Commit Validation Engine: Flags missing required fields, data-type/formatting mismatches, and duplicate primary keys before committing records.
8. Integrations & AI-Driven Automation
Enterprise Connectivity
 * Universal Data Connectors: Direct enterprise database connectors, REST API ETL pipelines, and Open Data feed ingestion.
 * Standardized Authentication: Full support for OAuth and Basic Authentication protocols.
AI Intelligence (BYOK OpenAI Integration)
Configured via secure local environment variables or Bring-Your-Own-Key (BYOK) management:
 * Automated Data Entry: AI-assisted form completion and structured data ingestion to minimize manual transcription.
 * Executive Summary Analysis: Automated synthesis of complex financial ledgers, operational metrics, and enterprise architecture portfolios.
 * Predictive Forecasting: Built-in predictive modeling algorithms embedded directly into financial ledgers, resource capacity matrices, and project execution timelines.
9. Repository Structure
seds-desktop-suite/
├── build/                          # Electron Builder packaging configs (.exe, .app, AppImage)
├── config/
│   ├── settings.schema.json        # JSON application configuration schema
│   ├── dictionaries/               # Parameter dictionaries & country tax/payroll rules
│   └── sms-parsers/                # Regex & rule definitions for SMS ingestion
├── extensions/                     # Signed & encrypted admin plugin/ribbon packages
├── src/
│   ├── main/                       # Electron main process, file I/O, license & crypto verifier
│   │   ├── licensing/              # Offline signature validation & zero-license viewer mode
│   │   ├── lan-bridge/             # Local WebSocket server for QR pairing, Camera & SMS
│   │   └── connectors/             # DB, REST ETL, OData, Exchange/Gmail & WhatsApp gateways
│   ├── engine/
│   │   ├── seds-format/            # .seds container packer, SHA-256 verifier & XLSX/Sheets bridge
│   │   ├── spreadsheet/            # Macro-free formula evaluator, pivots, charts & Connected Sheets
│   │   ├── mapping-workbench/      # Heuristic column matcher & pre-import validator
│   │   └── ai/                     # OpenAI BYOK client, auto-entry, summaries & forecasting
│   └── renderer/                   # Cross-platform desktop UI, ribbon, chat & domain workspaces
├── templates/                      # Out-of-the-box .seds domain templates (EA, Finance, POS, CRM)
└── docs/
    ├── SRS-Architecture.md         # Full Software Requirements Specification
    └── SEDS-Format-Spec.md         # Open .seds Workbook File Format Specification

10. Getting Started
Prerequisites
 * Node.js 20+ and npm / pnpm
 * OS Targets: Windows 10/11, macOS 13+, or Linux (Ubuntu 22.04+ / Fedora)
 * (Optional) Local OPENAI_API_KEY for AI automation features
 * (Optional) Same-subnet Wi-Fi/LAN for Mobile Companion pairing
Local Development Setup
# 1. Clone the repository
git clone https://internal.git.enterprise/seds/seds-desktop-suite.git
cd seds-desktop-suite

# 2. Install dependencies
npm install

# 3. Bootstrap local JSON configuration
cp config/settings.example.json config/settings.json
# Optional: export OPENAI_API_KEY="sk-..." for AI automation

# 4. Launch SEDS in development mode
npm run dev

Packaging Standalone Binaries
# Build portal-free standalone executables
npm run build:win     # Generates Windows .exe installer/portable binary
npm run build:mac     # Generates macOS .app bundle
npm run build:linux   # Generates Linux AppImage

11. Quick Operational Workflows
 * Initialize Sovereign Workspace: Launch the SEDS binary, validate your local cryptographic license (or launch directly in Zero-License Viewer mode), and optionally configure a thick-client startup master password.
 * Create or Convert Workbooks: Author new macro-free workbooks natively in the royalty-free .seds format, or open/convert existing .xlsx and Google Sheets files with full chart and pivot table fidelity.
 * Import & Map Legacy Data: Open the Visual Mapping Workbench, drop a .csv, .xlsx, or .seds dataset, review heuristic column mappings, resolve validation warnings, and commit records to your target template.
 * Pair Mobile Companion Over LAN: Click Pair Mobile Device to generate a one-time QR code, scan it with the smartphone companion app, and stream wireless barcode scans into POS or parse SMS payment alerts directly into accounting sheets.
 * Collaborate & Distribute: Co-work live over LAN or use offline checkout/check-in, export filtered views via Outlook Exchange/Gmail templates, or share native .seds files across the enterprise for viewing with zero license cost.
