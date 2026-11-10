# 🕵️‍♂️ IntelSuite — OSINT Platform Feature Catalog

> 🧭 A structured reference of the platform's **feature categories** — from geospatial live-monitoring and identity intelligence to threat intel, vulnerability analysis, tracking boards, APIs and automation.

## 📊 At a Glance

| 📌 Metric | 🔢 Value |
|---|---|
| 🗂️ Feature categories | **8** |
| ✨ Individual capabilities listed | **168** |
| 🧱 Categories with nested sub-modules | **0** |

## 🧱 Platform Pillars

| 🏛️ Pillar | 🔢 Categories |
|---|---|
| 🌍 Geospatial & Live Monitoring | 1 |
| 🕊️ Humanitarian Documentation | 1 |
| 💰 Finance, Sanctions & AI Forecasting | 1 |
| 👤 Identity, Breach & Account Intelligence | 2 |
| 🎯 Public-Records & Wanted/Aircraft/Arms Tracking | 3 |
| 🌐 Infrastructure, Recon & Web Analysis | 4 |
| 🧪 Threat, Malware, Exposure & Infrastructure Intelligence | 5 |
| 🩺 Vulnerability & Exploit Intelligence | 6 |
| 🔌 Feeds, API, Automation & Deployment | 8 |

## 📑 Table of Contents

1. [Interactive Intelligence Dashboards](#interactive-intelligence-dashboards)
2. [Identity, Breach & Account Intelligence](#identity-breach-account-intelligence)
3. [TrackWanted — Wanted-Person and Public-Records Tracking](#trackwanted-wanted-person-and-public-records-tracking)
4. [OSINT Collection, Reconnaissance and Web Intelligence](#osint-collection-reconnaissance-and-web-intelligence)
5. [Threat, Malware, Exposure and Infrastructure Intelligence](#threat-malware-exposure-and-infrastructure-intelligence)
6. [Vulnerability Assessment and Exploit Intelligence](#vulnerability-assessment-and-exploit-intelligence)
7. [SQL-Based Threat Hunting](#sql-based-threat-hunting)
8. [Threat Feeds and External Integrations](#threat-feeds-and-external-integrations)

---

## 🗺️ 1. Interactive Intelligence Dashboards

> 💡 **Overview:** Interactive maps/globes that fuse every intelligence layer into one explorable, shareable workspace.

**✨ Capabilities (57)**

- 🌍 Interactive world maps and globes with toggleable intelligence layers
- 📍 Click-to-track entities with metadata, nearby contacts and historical trails
- 🔗 Shareable map states and selected-target links
- 🗺️ Map annotations and drawing tools
- 📹 Camera-tour recording

- ✈️ Track commercial, private and military aircraft with metadata, nearby aircraft, flight trails and follow-camera mode
- 🚢 Track vessels through AIS feeds with metadata and follow mode
- 🗺️ Global ports and maritime chokepoints
- 🛰️ Satellite and orbital-object positions with metadata and pass visibility
- 🚀 Space-launch information with trajectory replay
- ☀️ Solar-weather monitoring
- 🛰️ Satellite imagery and cloud information with date-to-date comparison

- 🌋 Real-time earthquakes and volcanic activity with magnitude, depth and epicenter
- 🔥 Wildfire hotspots and fire perimeters
- 🌀 Severe weather, floods, cyclones/hurricanes and tsunami alerts
- 🛰️ Weather radar and satellite overlays, with wind and temperature visualization
- 🔔 Configurable alerts for new disaster events

- 🗺️ Public webcam mapping, browsable by region and filterable by category
- 📹 Live camera streams with metadata and links to the original operator
- 🔎 Find cameras near a coordinate or address
- 📤 Export camera locations as GeoJSON

- 🚦 Road networks and traffic information
- 🚆 Public-transit vehicles and bike-share stations

- 📰 Live news streams with region/topic filters, geotagged event mapping and breaking-news alerts
- 📍 Trending topics and keyword surges
- 🔎 Searchable historical news archive with translation of non-English sources

- ⚔️ Conflict-zone markers with severity classification, reported strikes/incidents and airspace closures/NOTAMs
- 🗺️ Geoparsed public Telegram posts with links to the original
- 📊 Source-linked incident reports

- 🔹 Live global cyberattack visualization: DDoS, botnet infections, honeypot activity, exploitation attempts and ransomware leak-site updates
- 🧹 Filter live attacks by type, origin, target country or sector
- 📡 Correlate live attack data with threat-intelligence feeds
- 🕰️ Replay historical attack activity

- 🚫 Sanctions-list search across people, organizations, vessels and aircraft, including WHOIS-registrant and ASN-owner cross-checks
- 👛 Bitcoin and Ethereum wallet lookup: balances, transaction histories, relationship analysis and sanctions matching

- 💹 Cryptonews: live price ticker with 24h change and ETH gas tracker
- 📰 Cryptonews: news by category (Bitcoin, Altcoin, Ethereum, Blockchain, DeFi, NFT), price analysis and price predictions
- 🏆 Cryptonews: market-cap rankings and per-coin price pages
- 🧰 Cryptonews: converter, profit calculator, tax calculator and Fear & Greed Index guide
- 🎓 Cryptonews: educational library and security guides
- 🏛️ Cryptonews: wallet and exchange reviews

- 📻 Geolocated internet-radio stations
- 📻 Local RTL-SDR and ADS-B receiver integration, displayed alongside map layers

- 🗣️ Natural-language and voice map control: questions about mapped data, layer switching and entity search
- 🔮 Source-linked research and forecasting with scenario exploration, hypothetical-event injection, prediction-market comparison and shareable runs
- 🤖 Configurable AI providers and API keys

- 🔎 Full-text and media search across the documented video and photo archive, filterable by verification status, media type and date
- 📂 Browse by location, facility and event type, each with a clip count
- 🔎 Searchable memorial list of identified victims
- 📜 Day-by-day war log with PDF download
- 🗺️ Geolocation map placing footage where it was filmed, with location-confidence classification and data download
- 🕸️ Incident node-graph with structured search syntax, preset lenses, corroboration-tier filtering and published clustering methodology
- 🔎 "Iris" search assistant for navigating the archive
- 🔹 Curated directory of archive sources, journalists, channels, outlets and partner projects
- 🧲 Signed torrent releases, GPG/SHA256 verification and a Tor onion-service mirror
- 🔹 Mission, methodology, evidence-submission channel and legal-team access requests
- 🔹 Admin review queue with duplicate detection and publish-to-live control

---

## 📧 2. Identity, Breach & Account Intelligence

> 💡 **Overview:** Email and username discovery, breach and infostealer exposure intelligence, identity relationship analysis, and continuous account-exposure monitoring.

**✨ Capabilities (12)**

- 🔎 Email and username search with account discovery across online platforms
- 🧾 Profile retrieval: URLs, avatars, names, biographies and metadata
- 🔹 Correlation of accounts likely belonging to the same person, with identity enrichment
- 📧 Bulk email and username lookups with streamed results
- 🔓 Breach search by email: sources, dates and exposed data categories
- 📜 Infostealer-log exposure, including compromised cookies and sessions
- 🕸️ Interactive relationship graph linking emails, usernames, accounts and breaches
- ⏳ Chronological activity timelines
- 🔹 Multi-identifier investigations with annotations
- 👁️ Continuous monitoring of emails, domains and usernames for new breaches, infostealer records and account registrations
- 🔔 Alerts and webhook notifications with configurable frequency
- 📊 Exposure summaries and reports

---

## 🎯 3. TrackWanted — Wanted-Person and Public-Records Tracking

> 💡 **Overview:** TrackWanted brings wanted-person notices, aircraft tracking, financial activity, arms transfers, emissions and public-record research together in a unified 3D globe and set of dedicated tracking boards.

**✨ Key Features (9)**

- 🌍 Unified interactive 3D globe for exploring tracking categories
- 🚨 Public wanted-person notices with location estimates and source-linked case details
- 🛩️ Private-jet tracking with registration, operator, ownership and route information, plus FAA and Planespotters registration lookup
- 🎖️ Military and government aircraft tracking with callsigns and route histories
- 💸 Financial intelligence on documented acquisitions, share sales, forfeitures and other reported money movements
- 🌫️ Aviation-emissions estimates and air-quality data
- 🚀 Arms-transfer intelligence: supplier/recipient countries, equipment categories, values and status
- 📇 A-Z directory connecting tracked people, subjects, operators, callsigns and related records
- 🔄 Source-aware data refresh, record corrections and takedown-request channels

---

## 🧲 4. OSINT Collection, Reconnaissance and Web Intelligence

> 💡 **Overview:** Unified OSINT collection and automation, domain and DNS reconnaissance, IP and network intelligence, TLS and certificate analysis, web application discovery, technology fingerprinting, and web security configuration assessment.

**✨ Capabilities (36)**

- 🔹 Automated OSINT collection across domains, subdomains, IPs, netblocks, emails, usernames and URLs
- 🔹 Third-party intelligence integrations with configurable modules and broad scans
- 🗓️ Scheduled scans and automated workflows via CLI and API

- 🌐 DNS record enumeration, DNSSEC checks and DNS-over-HTTPS lookups
- 🪪 WHOIS and RDAP lookups
- 🌐 Reverse DNS and reverse IP lookups
- 🕰️ Passive DNS history and record-change analysis
- 🔹 Subdomain enumeration, nameserver and associated-host discovery
- 🔹 Domain reputation checks

- 📍 IP enrichment: geolocation, ASN, ownership, and netblock/IP-range discovery
- 🚪 Open-port discovery with service, server and SSH fingerprinting
- 🔹 BGP route analysis with RPKI validation and IRR lookups
- 🔹 Traceroute and ICMP reachability checks
- 🔹 IPv6/dual-stack analysis and CDN detection
- 🕰️ Port and network-service history

- 📜 SSL/TLS certificate inspection with chain validation and expiration checks
- 🔎 Certificate transparency searches and rogue-certificate checks
- 🔐 TLS cipher-suite, handshake and session-resumption analysis
- 🔹 JARM fingerprint lookup
- 📜 Certificate-based infrastructure correlation and certificate inventory

- 🔹 Website crawling with content and directory discovery, robots.txt and sitemap parsing
- 🕰️ Archive history lookup
- 🔹 Virtual-host and hidden-parameter discovery
- 🔌 API schema discovery, including GraphQL introspection and WebSocket endpoints
- 🔹 Redirect-chain analysis

- 🔹 CMS, technology-stack and web-server fingerprinting
- 🔹 Favicon hashing
- 🔹 JavaScript-file analysis, including obfuscation and DOM-sink detection
- 🔹 Third-party dependency and script risk profiling

- 🔹 HTTP security-header and Content Security Policy analysis
- 🔹 CORS misconfiguration and clickjacking checks
- 🔹 Cookie security analysis: flags, lifetime and scope
- 🔹 Open-redirect discovery
- 🔹 Rate-limit and WAF testing
- 📧 SPF, DKIM and DMARC validation
- 🔹 Security.txt checks

---

## 🧪 5. Threat, Malware, Exposure and Infrastructure Intelligence

> 💡 **Overview:** Consolidated threat intelligence, IOC enrichment, threat-actor and campaign analysis, phishing and malware investigation, exposed-resource and cloud checks, hosting-provider and registrar intelligence, and AttackCapture file analysis.

**✨ Capabilities (18)**

- 🔎 IOC and threat-feed search with enrichment of suspicious IPs, domains, URLs and file hashes
- 📍 IP and domain reputation checks
- 🔹 Correlation of indicators with known threat activity and contextual enrichment to reduce false positives
- 🦠 Identification of malware, phishing and command-and-control infrastructure
- 🔹 Threat-actor profiles with aliases, associated infrastructure and indicators, and cross-campaign correlation
- 📜 Relationship mapping between actors, hosts, certificates, infrastructure and vulnerabilities
- ⏳ Investigation timelines and structured attack reports

- 🔹 Discovery of suspicious scripts, files and potentially malicious payloads, including JavaScript analysis
- 🔎 Exposed-file and directory search by name, extension and SHA-256 hash
- 🔹 File preview, metadata and archive inspection
- 🔹 Classification of files by likely intent or function, with clustering of similar artifacts
- 👁️ Paste and leak-source monitoring
- 🔎 Exposed environment files, Git repositories, configuration artifacts and API endpoints
- ☁️ Cloud-bucket exposure checks and cloud-service enumeration
- 🔹 Correlation of exposed resources with suspicious infrastructure

- 📍 Hosting-provider identification by IP, with indicators grouped by provider
- 🔎 Domain registrar search and newly registered domain monitoring
- 🔹 Discovery of related hosts and infrastructure clusters

---

## 🩺 6. Vulnerability Assessment and Exploit Intelligence

> 💡 **Overview:** Host/service discovery, vulnerability and CVE identification, security configuration audits, CVSS prioritization, KEV monitoring, exploit artifact discovery and classification, infrastructure correlation, remediation guidance and reporting.

**✨ Capabilities (9)**

- 🔹 Host and service discovery
- 🩹 Vulnerability and CVE identification, including missing patches and outdated software
- 🧾 Security configuration audits of operating systems, applications and network devices, authenticated and unauthenticated
- 🔹 CVSS-based prioritization with remediation recommendations
- 📊 Vulnerability reports with scan-over-scan comparison
- 🔎 CVE record search
- 👁️ Known Exploited Vulnerabilities monitoring and weaponized-vulnerability flags
- 💥 Exploit-artifact discovery, classification, grouping and SHA-256 search
- 💥 Correlation of exploit artifacts with infrastructure

---

## 🧮 7. SQL-Based Threat Hunting

> 💡 **Overview:** SQL-based hunting across IP, HTTP, malware, phishing and WHOIS datasets.

**✨ Capabilities (6)**

- 🧮 SQL queries across IP, HTTP, malware, phishing and WHOIS datasets with cross-table correlation
- 🕰️ Query history with rerun of saved or previous queries
- 🔹 Streamed and paginated results for large result sets
- 📊 Histograms and events-over-time visualization
- 📤 Result export
- 🔌 Programmatic query execution through the API

---

## 📥 8. Threat Feeds and External Integrations

> 💡 **Overview:** C2, phishing and IOC feeds with filters, SIEM/SOC integration and webhooks; REST/OpenAPI access, bulk enrichment and remote MCP integration; saved investigations, exports, team sharing, permissions, audit logs and SSO; interactive CLI with module management, profiles, concurrency and logging controls; data collection, normalization, correlation, caching, import/export and attribution; web dashboards, Docker deployment, custom modules and self-hosting.

**✨ Capabilities (21)**

- 📡 C2, phishing, IOC and custom intelligence feeds with configurable filters
- 🔹 Third-party threat-intelligence and SIEM/SOC integrations
- 🔔 Webhook-based alert delivery

- 🔌 REST API with OpenAPI specifications
- 🔌 Bulk indicator enrichment and programmatic IOC search
- 🔹 Remote Model Context Protocol integration for AI clients
- 🔌 OAuth and scoped API keys with configurable limits and permissions

- 🔹 Saved investigations with notes and annotations
- 📤 Report and data export as PDF, CSV, JSON or text
- 🔗 Shared graphs, reports and team workspaces with configurable permissions
- 🧾 Audit logs and enterprise SSO/SAML on eligible plans

- ⌨️ Interactive CLI: search and list modules, set targets and options, run individual modules, categories or favorites, rerun last module
- 🧾 Saved configuration profiles
- 🧵 Concurrency, timeout/retry, request-header and logging controls
- 🔎 Cached-output search

- 🔹 Data collection from public and configured sources, with normalization, cross-dataset correlation and caching
- 📥 Import of user-provided data and export in supported formats
- 🔹 Source attribution and timestamps

- 🔹 Web dashboards
- 🐳 Docker and Docker Compose deployment, with local self-hosting
- 🧱 Custom modules, transforms and extensible data sources with optional API-key configuration

---

## 🚧 Problems IntelSuite Fixes

IntelSuite addresses the following underserved problems in existing OSINT, threat-intelligence and attack-surface intelligence workflows:

1. **Fragmented Intelligence Collection** — Analysts must use multiple platforms, APIs, feeds and manual searches to assemble a complete intelligence picture.
2. **Incomplete Attack Surface Discovery** — Discovered internet-facing assets can be difficult to attribute to their actual owners, business relationships and wider exposure.
3. **Poor Cross-Source Visibility** — Related signals about the same threat or entity are spread across forums, messaging channels, malware samples, code repositories, DNS records and other sources.
4. **Weak Historical Infrastructure Intelligence** — Investigators may lack a unified view of how IP addresses, domains, certificates, servers, ownership and hosting relationships have changed over time.
5. **Limited Autonomous Investigation** — Analysts still spend significant time manually connecting findings across sources and building investigation reports.
6. **Weak Threat Actor Attribution** — Aliases, shared infrastructure, false flags and misleading indicators make it difficult to attribute activity reliably.
7. **Disconnected Vulnerability and Threat Context** — Vulnerability records are not always connected to observed exploitation, threat actors, campaigns, affected technologies and an organization's actual exposure.
8. **Fragmented Campaign Reconstruction** — Evidence about infrastructure, malware, victims, tactics, techniques and procedures is scattered across indicators, reports and feeds.
9. **False Positives and Unreliable Intelligence** — Indicators can be stale, reassigned, benign, misclassified or deliberately misleading, reducing confidence in intelligence findings.
10. **Intelligence That Does Not Translate Into Action** — Findings may identify suspicious activity without clearly informing prioritization, remediation, detection or response.
11. **Third-Party and Supply-Chain Blind Spots** — Organizations can lack visibility into security exposures across vendors, SaaS providers, subsidiaries, dependencies and other connected infrastructure.
12. **Reactive Rather Than Predictive Intelligence** — Investigations often begin after an indicator or incident is detected, limiting visibility into emerging patterns and developing campaigns.
13. **Difficult Intelligence Querying** — Analysts must navigate different search syntaxes, filters, query languages and platform-specific workflows to investigate across sources.

---

## 🧾 Notes & Conventions

- 🧩 Phrases such as *“where supported”*, *“where available”* and *“where implemented”* indicate capabilities that depend on the underlying data source, feed or deployment configuration.
- 🔗 Feature 1 includes the external archive **archivegenocide.com**; Feature 3 (TrackWanted) draws on public sources including Interpol notices, the FAA registry, Planespotters, GDELT and ICIJ Offshore Leaks.
- 🔄 Refresh cadences noted in Feature 3: wanted board & money trail **twice daily**, aircraft registry index **weekly**, air-quality readings **every 10 minutes**.
- 📰 The Cryptonews.com capabilities in Feature 1 were compiled from the cryptonews.com homepage and site navigation (snapshot of 2 Nov 2026).
- ⚖️ Source attribution, confidence indicators and correction/takedown channels are built into the tracking modules.
