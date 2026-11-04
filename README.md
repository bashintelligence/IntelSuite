# 🕵️‍♂️ IntelSuite — OSINT Platform Feature Catalog

> 🧭 A complete, structured reference of every capability across the platform's **feature categories** — from geospatial live-monitoring and identity intelligence to threat intel, vulnerability analysis, tracking boards, APIs and automation.

## 📊 At a Glance

| 📌 Metric | 🔢 Value |
|---|---|
| 🗂️ Feature categories | **8** |
| ✨ Individual capabilities listed | **618** |
| 🧱 Categories with nested sub-modules | **1** (Feature 1) |

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

**✨ Capabilities (300)**

- 🌍 Interactive world maps and globes
- 🔹 Geographic visualization of available entities
- 🔹 Toggleable intelligence layers
- 🔹 Entity counts and progressive loading
- 🔹 Viewport-aware data loading
- 📍 Click-to-track selected entities
- 🔹 Display entity metadata
- 🔹 Nearby-contact lists
- ⏳ Historical trails and timelines
- 🗺️ Map annotations and geographic drawing tools
- 🔗 Shareable map states and selected-target links
- 📹 Camera-tour recording
- 🗺️ Custom map styles and visualization modes
- 🔹 Keyboard shortcuts and navigation controls
- 📍 Track commercial aircraft
- 📍 Track private aircraft where available
- 📍 Track military aircraft where available
- ✈️ Display aircraft metadata
- 🗺️ View aircraft positions on a map or globe
- ✈️ Follow selected aircraft
- ✈️ Display nearby aircraft
- 🕰️ Show flight trails and historical routes where supported
- 📹 Switch to aircraft-follow camera modes
- ✈️ Render supported aircraft models in 3D
- 📍 Track vessels through supported AIS feeds
- 🚢 Display vessel positions and metadata
- 🗺️ Map global ports
- 🗺️ Map maritime chokepoints
- 🚢 Follow selected vessels
- 🔹 Display nearby maritime contacts
- 🔹 Investigate maritime infrastructure and activity
- 🛰️ Display satellite positions
- 📍 Track orbital objects from supported catalogs
- 🛰️ Display satellite metadata
- 🛰️ Show satellite passes and visibility information where supported
- 🔹 Display space-launch information
- 🔹 Replay supported launch trajectories
- 👁️ Monitor solar weather
- 🛰️ Display satellite imagery and cloud information from supported sources
- 🌋 Display earthquake events
- 🌋 Show earthquake magnitude and location
- 👁️ Monitor active fire hotspots
- 🔥 Display fire perimeters where available
- 👁️ Monitor severe weather events
- 🛰️ Display weather radar and satellite imagery
- 🔹 Visualize wind and temperature information
- 📍 Track cyclones and forecast information
- 🛰️ Compare available satellite imagery across dates
- 🗺️ Map publicly accessible camera feeds
- 📹 Open individual camera streams where available
- 📂 Browse cameras by geographic region
- 📹 Find cameras within a selected area
- 📤 Export supported camera locations as GeoJSON
- 📍 Navigate from tracked entities to nearby cameras where supported
- 📹 Display camera markers and available metadata
- 📹 Link to the original camera operator or feed
- 📹 Estimate camera positions or orientations where exact data is unavailable
- 🔹 Display road networks
- 🚦 Visualize traffic information where available
- 🧪 Simulate vehicle movement along mapped roads where applicable
- 🚆 Display supported public transit vehicles
- 📍 Track buses, trains, trams, subways, and ferries where feeds exist
- 🔗 Show bike-share stations and availability where supported
- 🗺️ Map transportation infrastructure
- 📰 Display live news streams from supported broadcasters
- 📰 Open related news sources
- 🗺️ Map geographically associated news
- ⚔️ Display conflict-zone markers
- 🔹 Classify zones by severity
- 👁️ Monitor selected conflict and tension areas
- 🔹 Display public-source geopolitical information
- 🗺️ Map publicly available Telegram posts when supported
- 🔹 Geoparse public posts using location references
- 🔹 Open the original public post for context
- 🔎 Search supported sanctions lists
- 🔎 Search people, organizations, vessels, and aircraft
- 🚫 Cross-check supported names against sanctions records
- 🪪 Cross-check WHOIS registrant and ASN-owner names where implemented
- 🔎 Search Bitcoin wallet information
- 🔎 Search Ethereum wallet information
- 🔹 Retrieve supported balances and transaction histories
- 👛 Investigate wallet transaction relationships
- 🚫 Match supported addresses against sanctions data
- 💹 Cryptonews: Scrolling live price ticker for BTC, ETH, SOL, PEPE, SHIB, DOGE and XRP with 24h percentage change
- 🔗 Cryptonews: Each ticker entry links to a dedicated coin price page
- ⛽ Cryptonews: Live ETH gas price display (gwei) in the site header
- 🆕 Cryptonews: Latest Crypto News stream with category label and timestamp per article
- ₿ Cryptonews: Bitcoin News
- 🪙 Cryptonews: Altcoin News
- ⟠ Cryptonews: Ethereum News
- ⛓️ Cryptonews: Blockchain News
- 🏦 Cryptonews: DeFi News
- 🖼️ Cryptonews: NFT News
- 📈 Cryptonews: Price Analysis articles (e.g. coin price predictions and market commentary)
- ⭐ Cryptonews: Crypto News Spotlight (editor-highlighted stories with author and date)
- 🗞️ Cryptonews: Archive of more news via “More Latest News” and per-category “More from Category” pages
- 🧭 Cryptonews: Exclusives hub
- ✍️ Cryptonews: Features (long-form articles)
- 💬 Cryptonews: Opinions (contributor commentary)
- 🤿 Cryptonews: Deep Dives section combining features and opinions
- 📑 Cryptonews: Cryptonews Reports (monthly and thematic market-outlook research, e.g. Bitcoin/ETH/altcoin reports)
- 📱 Cryptonews: Short Stories — swipeable Web Stories for quick news summaries
- 🧑‍💻 Cryptonews: Author bylines and a public Authors/Contributors directory (70 international authors claimed)
- 📢 Cryptonews: Press Releases section (hosted on the advertorial subdomain)
- 💼 Cryptonews: Sponsored news section
- 📮 Cryptonews: “Have a Story?” submission channel for tips and stories
- 🤝 Cryptonews: Advertising / media-kit contact page
- 🏆 Cryptonews: Market Cap rankings (coins directory)
- 🪙 Cryptonews: Per-coin price pages (Bitcoin, Ethereum, XRP, Shiba Inu, Cardano, Dogecoin, Solana, Binance Coin, Litecoin, Pepe)
- 📍 Cryptonews: Crypto Price Tracker
- 🔮 Cryptonews: Price Predictions hub
- 📉 Cryptonews: Price Analysis feed
- 🔬 Cryptonews: Market Research reports
- 🛒 Cryptonews: Buy Crypto section and “How to Buy Bitcoin” guide
- ⛽ Cryptonews: Ethereum Gas Tracker
- 🧾 Cryptonews: Crypto Tax Calculator
- 💰 Cryptonews: Crypto Profit Calculator
- 🔄 Cryptonews: Crypto Converter
- 😱 Cryptonews: Fear and Greed Index explainer and usage guide
- 🧰 Cryptonews: Tools hub page
- 🎓 Cryptonews: Beginner-oriented educational library with difficulty level and estimated read time per article
- ⛓️ Cryptonews: Topic: Blockchain Technology (44 articles at time of snapshot)
- 📈 Cryptonews: Topic: Crypto Investing and Trading (43 articles)
- 📚 Cryptonews: Topic: Crypto Fundamentals (55 articles)
- 🏦 Cryptonews: Topic: DeFi — Decentralized Finance (10 articles)
- 🔐 Cryptonews: Topic: Security and Risk Management (12 articles)
- 📖 Cryptonews: Guides such as securing your cryptocurrency, swing trading, crypto types and protocol upgrades explained
- 💎 Cryptonews: Best Crypto to Buy Now
- 🧺 Cryptonews: Top Cryptocurrencies for diversification
- 🚀 Cryptonews: Best Crypto Presales
- 💥 Cryptonews: Next Crypto to Explode
- 🐸 Cryptonews: Best Meme Coins and Best Solana Meme Coins
- 👛 Cryptonews: Best Crypto Wallets (plus anonymous, decentralized, built-in-exchange wallets and a how-to-choose guide)
- 🔑 Cryptonews: Hardware and software wallet reviews (e.g. Ledger Stax, Zengo, Cypherock X1, Tangem, Best Wallet)
- 🏛️ Cryptonews: Best Crypto Exchanges with individual exchange reviews (e.g. Binance, MEXC, Blofin, Margex, edgeX, Coinfutures)
- ⚖️ Cryptonews: Crypto Futures Trading Platforms comparison
- 🛡️ Cryptonews: “Is Your Crypto Safe?” security guide
- ⭐ Cryptonews: Reviews hub
- 🎰 Cryptonews: Crypto gambling section: casino, no-KYC casino, betting site, poker, Ethereum and Solana casino rankings (affiliate-supported; 18+ notice displayed)
- 🎙️ Cryptonews: Cryptonews Podcast with guest-interview episodes
- 🎧 Cryptonews: Listen on Apple Podcasts and Spotify
- 🌐 Cryptonews: Social channels: X, YouTube, LinkedIn, Telegram (cryptonews_official)
- 📧 Cryptonews: Email newsletter delivered every Tuesday and Friday with reCAPTCHA-protected sign-up
- 🌍 Cryptonews: 15 language editions: English, Deutsch, Français, Русский, Türkçe, 日本語, Nederlands, Italiano, 中文, Español, Português, Svenska, Suomi, 한국어, Polski
- 🗺️ Cryptonews: Region selector in the header
- ℹ️ Cryptonews: About Us and Editorial Guidelines
- 👥 Cryptonews: Our Team / Contributors directory
- 📅 Cryptonews: Events page
- 🤝 Cryptonews: Affiliate Disclosure
- ⚠️ Cryptonews: Financial Risk Disclaimer, Terms & Conditions and Privacy Policy
- 📊 Cryptonews: Self-reported audience stats: 2M+ monthly users, 250+ guides and reviews, 8 years on the market
- 📻 Display geolocated internet-radio stations
- 📻 Integrate local RTL-SDR radio input where supported
- 🔹 Integrate local ADS-B receivers
- ✈️ Display locally received aircraft data
- 🗺️ Combine local receiver data with map-based views
- 🗣️ Natural-language questions about mapped intelligence
- 🗺️ Voice-based map navigation
- 🤖 Switch layers through supported AI commands
- 🔎 Search visible entities through natural language
- 🔹 Ask questions about selected intelligence data
- 🔹 Research questions using configured source material
- 🔮 Generate forecasts from sourced information and simulations where supported
- 🔮 Compare forecasts with prediction-market information where implemented
- 🔹 Explore alternative scenarios and outcomes
- 📊 Display source-linked research and report findings
- 🧪 Inject hypothetical events into supported simulations
- 🔗 Share supported research runs
- 🤖 Use configurable AI providers and API keys
- 🗺️ Map live public webcam feeds worldwide
- 📂 Browse cameras by country, city, or region
- 🧹 Filter cameras by category (traffic, weather, landmark, indoor/outdoor)
- 📹 Open individual live camera streams
- 📡 Play, pause, and refresh live feeds
- 📹 Display camera metadata (location, operator, resolution where available)
- 🔎 Search cameras near a specific coordinate or address
- 📹 Bookmark and save favorite camera feeds
- 📹 Detect offline or stale camera feeds
- 📹 Link to the original camera operator or source page
- 📤 Export camera locations as GeoJSON
- 📰 Stream live news broadcasts from supported global sources
- 🔔 Display real-time breaking-news alerts
- 🧹 Filter news by region, topic, or category
- 🗺️ Map geographically tagged news events
- 🔹 Aggregate headlines from multiple outlets
- 📍 Track trending topics and keyword surges
- 👁️ Monitor live press conferences and briefings where available
- 📰 Correlate live news events with other mapped intelligence layers
- 🔎 Archive and search historical news coverage
- 📰 Translate supported non-English news sources
- 🔹 Display real-time global cyberattack visualizations
- 📍 Track live DDoS attack activity where supported
- 🗺️ Map active malware and botnet infection sources
- 🚦 Visualize attacker-to-target traffic flows
- 🔹 Display live honeypot sensor activity
- 👁️ Monitor real-time vulnerability exploitation attempts
- 📍 Track live ransomware activity and leak-site updates
- 📡 Correlate live attack data with threat-intelligence feeds
- 🧹 Filter live attacks by type, origin, target country, or sector
- 🔹 Generate live attack summary statistics
- 🕰️ Replay historical attack activity over time
- 🌋 Display real-time earthquake events as they are detected
- 🔹 Show live magnitude, depth, and epicenter data
- 👁️ Monitor active volcanic activity where supported
- 📍 Track live wildfire hotspots and fire perimeters
- 👁️ Monitor live flood and severe-storm warnings
- 📍 Display live hurricane and cyclone tracking
- 🔔 Show live tsunami alerts where available
- 🛰️ Overlay live weather radar and satellite imagery
- 🔔 Send configurable alerts for new disaster events
- 🕰️ Compare live disaster data against historical baselines


- ⚔️ Display live conflict-zone markers and front-line estimates
- 📍 Track real-time reported military activity where sourced
- 👁️ Monitor live airspace closures and NOTAMs in conflict regions
- 🗺️ Map live reported strikes, shelling, and incident locations
- 📊 Aggregate live open-source conflict reporting
- ⚔️ Classify conflict zones by live severity and escalation level
- 👁️ Monitor live refugee and displacement reporting where available
- 📍 Track live sanctions and diplomatic-response updates
- 📰 Correlate live conflict data with news and geopolitical layers
- 📊 Display source-linked live incident reports

<details>
<summary>🔎 <b>Archive Search and Browsing</b> — 12 capabilities</summary>

- 🔎 Full-text and media search across the 156,000+ documented videos and photos
- 🧹 Filter by verified footage, uncaptioned footage, or text posts
- 🧹 Filter by media type (all media, videos only, photos only)
- ↕️ Sort results (default, newest first, oldest first)
- 🧹 Filter by date range (From / To)
- 📂 Browse all archives across Gaza and the West Bank
- 🔹 Grid and List view modes
- 🔹 Entry detail view showing date and time, media type, topic, source/channel, archive, description, original source links, classification, and file
- 🔹 Flag an entry for review
- 🔗 Share an entry
- ⬇️ Download an entry
- 🔎 Ask the "Iris" search assistant for help navigating the archive

</details>

<details>
<summary>📄 <b>Text Index / Plain-Text Browse</b> — 2 capabilities</summary>

- 🔎 Paginated plain-text index of all 41,065+ documented clips, built for search-engine indexing
- 🔹 Page-by-page navigation through the full clip index

</details>

<details>
<summary>🗂️ <b>Topic Browse</b> — 3 capabilities</summary>

- 📂 Browse by location, each with a clip count (e.g. Gaza City, Khan Younis, Deir al-Balah, Jabalia, Rafah, Nablus, Jenin, Hebron, Ramallah and others)
- 📂 Browse by facility, each with a clip count (named hospitals including Kamal Adwan, Nasser, Al-Aqsa Martyrs, Al-Ahli Baptist, Al-Shifa, Al-Awda, Indonesian, Al-Rantisi Children's, European Gaza and Al-Quds)
- 📂 Browse by event type, each with a clip count (e.g. attacks on children, attacks on hospitals, forced displacement, attacks on journalists, attacks on schools and shelters, attacks on ambulances and medics, detainees and stripped prisoners, attacks on tents and displacement camps, attacks on mosques, sniper attacks, executions and white-flag killings, attacks on aid seekers, attacks on UN and UNRWA sites, white phosphorus, attacks on churches, attacks on bakeries and food)

</details>

<details>
<summary>🕯️ <b>Victims Memorial</b> — 3 capabilities</summary>

- 🔎 Searchable memorial list of identified Palestinians killed in Gaza, as recorded by the Gaza Ministry of Health
- 🔹 Paginated memorial index of all identified names
- 🔎 Search all names

</details>

<details>
<summary>📆 <b>Daily Reports</b> — 5 capabilities</summary>

- 📜 Day-by-day war log numbered by the day of the war (Day 1 = 7 October 2023)
- 🔹 Digest of strikes, casualties, sieges, and West Bank and regional events per day
- ↕️ Sort reports (newest or oldest)
- ⬇️ Download all reports as a single PDF
- ⏳ Reports sourced from Telegram and Discord channels, with coverage gaps marked in the timeline

</details>

<details>
<summary>📌 <b>Geolocation Map</b> — 8 capabilities</summary>

- 🗺️ Interactive map placing archive footage at the location it was filmed
- 🧹 Filter by place, date, and kind of attack
- 🔹 District boundary overlay toggle
- 🗺️ Dark map and satellite map toggle
- 🗺️ Multiple selectable map layers
- 🔹 Location-confidence classification (exact, hospital, awaiting review, approximate building, approximate neighbourhood or town, independent with no footage yet, sources disagree)
- ⬇️ Download the underlying geolocation data
- 🗺️ Ask the "Iris" assistant for help navigating the map

</details>

<details>
<summary>🔗 <b>Node (Event) Graph Map</b> — 17 capabilities</summary>

- 🕸️ Graph view of documented incidents as connected nodes for events, people, places, facilities and named actors
- 🔎 Structured search syntax (e.g. cat:massacre place:rafah, killed:>10, clips:>3, date ranges)
- 🔹 Preset exploration lenses (hospitals, journalists, massacres, children, perpetrators, most sources)
- 🧹 Place-type filters (hospitals, schools, camps, detention, worship sites, towers)
- 🗺️ Selectable layout modes (Default, Rings; Map layout planned)
- 🧹 Corroboration-tier filtering (tiers A through E)
- 🧹 Edge-confidence filtering between established links and possible/dashed leads
- 🔹 Toggle to show or hide inferred (unstated) locations
- 🔹 Adjustable rendering controls for minimum clips, link strength, node size, spin, drift and glow
- 🗣️ Caption-language toggle (English, Arabic, Hebrew)
- 🛰️ Satellite, bright or off basemap toggle
- 🔗 Node detail panel with open-node, add-to-basket, share and report actions
- 📤 Export and import of node-map data
- 🧹 Time-range filter with an "all time" reset
- 🔗 Published methodology describing how clips are clustered into events (video fingerprint matching, shared post URL, matching date and place)
- 🔹 Published list of casualty figures the project examined and rejected, with the reason for rejection
- 🗺️ Ask the "Iris" assistant for help navigating the node map

</details>

<details>
<summary>✅ <b>Verified Sources Directory</b> — 8 capabilities</summary>

- 🔹 Curated list of archive source channels (Telegram, Discord, TikTok-based), each with an item count and description
- 🔹 Curated list of Instagram journalists and photographers, with notable-source flags
- 🔹 Curated list of Telegram channels
- 🔹 Curated list of Twitter/X accounts
- 🔹 Curated list of Reddit communities
- 📰 Curated list of news outlets
- 🔹 Curated list of partner websites, databases and documentation projects
- 🔎 Search within the sources list

</details>

<details>
<summary>💾 <b>Download / Archive Distribution</b> — 6 capabilities</summary>

- 🧲 Signed official torrent releases of the complete curated archive
- 🔹 Open-source website, front-end and server code on GitHub and Codeberg for self-hosting a mirror
- 🧲 Magnet links and .torrent files for each release volume
- 🧲 Full raw source volumes (~2.4 TB) mirrored on DDoSecrets and distributed by torrent
- 🧅 Tor onion-service mirror of the live archive, independent of the clearnet
- 📂 Guidance for connecting via Tor Browser and bridges

</details>

<details>
<summary>🔏 <b>Verification and Integrity</b> — 6 capabilities</summary>

- 🔏 Published GPG signing key and fingerprint
- 🔏 Instructions for installing GPG
- 📥 Instructions for importing the signing key and checking its fingerprint
- 🧲 Per-torrent signature-verification commands
- ⬇️ SHA256 checksum lists and signatures for verifying downloaded files
- 🔹 Guidance for distinguishing official domains and mirrors from unofficial copies

</details>

<details>
<summary>ℹ️ <b>About / Project Information</b> — 5 capabilities</summary>

- 🔹 Statement of the project's mission and methodology
- 👥 Listed recipients of submitted evidence (the International Criminal Court, the Hind Rajab Foundation, and the South African legal team at the ICJ)
- 🔹 Social and contact channels (Twitter/X, Telegram, Instagram, YouTube)
- 👥 Guidance for legal teams, journalists and researchers to request access to non-public archives
- 🔹 Dedicated evidence-submission channel for sources

</details>

<details>
<summary>🛠️ <b>Administration and Review</b> — 4 capabilities</summary>

- 🔹 Admin login
- 🔹 Review dashboard and review queue
- 🔹 Duplicate-detection review
- 🔹 Publish-to-live control

</details>
---

---

## 📧 2. Identity, Breach & Account Intelligence

> 💡 **Overview:** Email and username discovery, breach and infostealer exposure intelligence, identity relationship analysis, and continuous account-exposure monitoring.

**✨ Capabilities (28)**

- 🔎 Search email addresses and usernames
- 🔹 Discover accounts registered across online platforms
- 🧾 Retrieve profile URLs, avatars, names, biographies, and metadata
- 🔹 Correlate accounts that may belong to the same person
- 🔹 Identify account registration information
- 🔹 Enrich identities using public and third-party data sources
- 🔹 Stream lookup results as they become available
- 📧 Perform bulk email and username lookups
- 🔎 Search breach records associated with email addresses
- 🔑 Identify exposed email addresses, names, phone numbers, and password-related records
- 📜 Investigate infostealer-log exposure
- 🔹 Identify compromised cookies, sessions, and device-related data where available
- 🔓 View breach sources, dates, and exposed data categories
- 👁️ Monitor identifiers for new exposures
- 📊 Generate exposure summaries and reports
- 🔓 Visualize connections between emails, usernames, accounts, and breaches
- 🕸️ Build interactive relationship graphs
- 🔗 Trace shared identifiers
- 🧾 Correlate profiles across platforms
- ⏳ Build chronological activity timelines
- 🔹 Add multiple identifiers to an investigation
- 🔹 Annotate findings and preserve investigation context
- 👁️ Monitor email addresses, domains, and usernames
- 🔓 Detect newly discovered breaches and infostealer records
- 📍 Track newly discovered account registrations
- 👁️ Configure monitoring frequency
- 🔔 Receive alerts and supported webhook notifications
- 🔗 Share monitoring workloads across teams

---

---

## 🎯 3. TrackWanted — Wanted-Person and Public-Records Tracking

> 💡 **Overview:** TrackWanted brings wanted-person notices, aircraft tracking, financial activity, arms transfers, emissions and public-record research together in a unified 3D globe and set of dedicated tracking boards.

**✨ Key Features (13)**

- 🌍 Unified interactive 3D globe for exploring tracking categories and geographic context
- 🚨 Public wanted-person notices, indexed cases, location estimates and source-linked case details
- 🛩️ Private-jet tracking with aircraft registration, operator, ownership and route information
- 🎖️ Military and government aircraft tracking, including aircraft details, callsigns and available route histories
- 💸 Financial intelligence covering documented acquisitions, share sales, forfeitures and other reported money movements
- 🌫️ Aviation-emissions estimates, worldwide emitter information and air-quality data with methodology context
- 🔢 Aircraft registration lookup with FAA and Planespotters cross-references
- 🚀 Arms-transfer intelligence covering supplier and recipient countries, equipment categories, reported values and transfer status
- 📇 A-Z directory connecting tracked people, wanted subjects, aircraft operators, callsigns and related records
- 🔍 Search, filtering, sorting and navigation across aircraft, arms-transfer and subject records
- 🧠 Public-source intelligence using notices, registries, news indexes, GDELT, public financial records and other traceable sources
- 📚 Background research pages, daily briefings and dedicated tracking-board references
- 🔄 Source-aware data refresh, registry updates, record corrections and takedown-request channels

---

## 🧲 4. OSINT Collection, Reconnaissance and Web Intelligence

> 💡 **Overview:** Unified OSINT collection and automation, domain and DNS reconnaissance, IP and network intelligence, TLS and certificate analysis, web application discovery, technology fingerprinting, and web security configuration assessment.

**✨ Capabilities (101)**

- 🔹 Automate open-source intelligence collection
- 📍 Discover domains, subdomains, IP addresses, and netblocks
- 📜 Collect DNS, WHOIS, RDAP, ASN, and certificate information
- 📧 Discover email addresses, usernames, URLs, and online references
- 🔎 Query public web sources and search engines
- 🔹 Integrate third-party intelligence services
- 🧱 Configure individual modules or broad scans
- 🗓️ Schedule supported scans and automate workflows
- 🔌 Use command-line and API-based execution
- 🌐 DNS record enumeration
- 🔹 DNSSEC checks
- 🌐 DNS over HTTPS lookups
- 🪪 WHOIS and RDAP registration lookups
- 🌐 Reverse DNS lookups
- 📍 Reverse IP lookups
- 🕰️ Passive DNS history
- 🔹 Nameserver discovery
- 🔹 Subdomain enumeration
- 🔹 Associated-host discovery
- 🔹 Domain reputation checks
- 🔹 Domain registration and infrastructure correlation
- 🔎 Certificate transparency searches
- 🕰️ DNS history and record-change analysis
- 📍 IP address enrichment
- 📍 IP geolocation and ASN information
- 📍 Netblock and IP-range discovery
- 🚪 Open-port discovery
- 🔹 Service and server fingerprinting
- 📍 Reverse IP and associated-host lookup
- 🔹 Network ownership and routing information
- 🔹 BGP route analysis
- 🔹 RPKI route validation
- 📘 Internet Routing Registry analysis
- 🔹 Traceroute and ICMP reachability checks
- 🔹 IPv6 and dual-stack analysis
- 🔹 Network timezone detection
- 🔹 CDN detection
- 🔹 SNMP and NetBIOS checks
- 🔹 UDP service sampling
- 🔹 SSH banner and key fingerprinting
- 🕰️ Port history and network-service history
- 📜 SSL/TLS certificate inspection
- 📜 Certificate-chain validation
- 📜 Certificate-expiration checks
- 🔐 TLS cipher-suite analysis
- 🧪 TLS handshake simulation
- 🔐 TLS session-resumption analysis
- 📜 Certificate transparency log queries
- 📜 Network certificate inventory
- 🔹 JARM fingerprint lookup
- 📜 Rogue-certificate checks
- 🔹 SSL Labs integration
- 📜 Certificate-based infrastructure correlation
- 🔹 Website crawling
- 🔹 Content discovery
- 🔹 Directory discovery
- 🔹 Robots.txt analysis
- 🔹 Sitemap parsing
- 🕰️ Archive history lookup
- 🔹 Broken-link detection
- 🔹 Redirect-chain analysis
- 🔹 Virtual-host discovery
- 🔹 Hidden-parameter discovery
- 🔹 WebSocket endpoint discovery
- 🔌 API schema discovery
- 🕸️ GraphQL introspection checks
- 🔹 File-upload surface discovery
- 🔹 HTTP method enumeration
- 🔹 HTTP/2 and HTTP/3 support detection
- 🔹 CMS detection
- 🔹 Technology-stack identification
- 🔹 Web server fingerprinting
- 🔹 Favicon hashing
- 🔹 JavaScript-file analysis
- 🔹 Static-asset fingerprinting
- 🔹 Third-party dependency discovery
- 🔹 Third-party script risk profiling
- 🔹 Embedded-object discovery
- 🔹 HTML comment extraction
- 🔹 JavaScript obfuscation detection
- 🔹 DOM-sink analysis
- 🔹 HTML5 feature-abuse checks
- 🔹 SEO-abuse detection
- 🔹 Third-party integration discovery
- 🔹 HTTP security-header checks
- 🔹 Content Security Policy analysis
- 🔹 CORS misconfiguration detection
- 🔹 Clickjacking checks
- 🔹 Cookie security analysis
- 🔹 Session-cookie lifetime checks
- 🔹 Cookie scope comparison across subdomains
- 🔹 Autocomplete configuration checks
- 🔹 Open-redirect discovery
- 🗄️ Cache-behavior analysis
- 🔹 HTTP method inspection
- 🔹 Rate-limit and WAF testing
- 🔹 Security.txt checks
- 🔹 Privacy and GDPR compliance checks
- 🔹 SSL pinning checks
- 🔹 SPF, DKIM, and DMARC validation
- 📧 Email configuration analysis

---

---

## 🧪 5. Threat, Malware, Exposure and Infrastructure Intelligence

> 💡 **Overview:** Consolidated threat intelligence, IOC enrichment, threat-actor and campaign analysis, phishing and malware investigation, exposed-resource and cloud checks, hosting-provider and registrar intelligence, and AttackCapture file analysis.

**✨ Capabilities (64)**

- 🔎 Search indicators of compromise
- 📍 Enrich suspicious IP addresses, domains, URLs, and file hashes
- 🦠 Identify infrastructure associated with malware and phishing
- 🔹 Investigate command-and-control infrastructure
- 🔎 Search threat-intelligence feeds
- 📍 Check IP and domain reputation
- 🔹 Correlate indicators with known threat activity
- 🔹 Investigate threat actors and aliases where data is available
- 📜 Connect related hosts, certificates, and infrastructure
- ⏳ Build investigation timelines
- 📊 Produce structured attack reports
- 🔹 Reduce false positives through contextual enrichment
- 🔎 Search threat-actor profiles
- 🔹 Identify known aliases
- 🔹 Examine associated infrastructure and indicators
- 🔹 Correlate indicators across campaigns
- 📍 Track activity over time
- 🔎 Search enriched threat signals
- 🩹 Investigate relationships between actors, infrastructure, and vulnerabilities
- 📤 Export supported investigation findings
- 🎣 Identify phishing-related domains and infrastructure
- 🦠 Investigate malware-associated hosts
- 🔎 Search malware and phishing indicators
- 🔹 Discover suspicious scripts and files
- 🔎 Search exposed files and directories
- 🔹 Identify potentially malicious payloads
- 🔹 Inspect supported file metadata and content
- 🔎 Search file names, extensions, and SHA-256 hashes
- 🔹 Analyze JavaScript files for malicious characteristics
- 🔹 Correlate files with infrastructure and other indicators
- 👁️ Monitor supported paste and leak sources
- 🔹 Discover publicly accessible directories
- 🔎 Search exposed environment files
- 🌿 Identify exposed Git repositories
- ☁️ Check cloud-bucket exposure
- ☁️ Enumerate supported cloud services
- 🔌 Discover exposed API endpoints
- 🔹 Identify exposed configuration artifacts
- 🔹 Classify captured files by likely intent or function
- 🔹 Preview supported file contents
- 🔹 Inspect supported archives
- 🔹 Correlate exposed resources with suspicious infrastructure
- 📍 Identify hosting providers associated with IP addresses
- 🔹 Correlate domains with hosting infrastructure
- 🔹 Investigate providers associated with suspicious activity
- 🔎 Search domain registrar information
- 👁️ Monitor newly registered domains where supported
- 🔹 Detect unusual domain-provisioning activity
- 🔹 Group indicators by provider
- 🔹 Discover related hosts and infrastructure clusters
- 🔹 Investigate suspicious hosting patterns
- 🔹 Discover exposed directory listings
- 🔎 Search indexed files and code
- 🧹 Filter by file name, extension, host, port, and available tags
- 🧹 Filter by malware, IOC, package type, function, and intent where supported
- 🔹 Preview supported file contents
- 🔹 Highlight relevant keywords
- 🔹 Retrieve available file metadata and headers
- 🔹 Inspect supported archives
- 🔎 Search by SHA-256 hash
- 🔹 Classify files using available automated categorization
- 💥 Discover exploit-related files
- 🔹 Cluster similar artifacts
- 📤 Export supported findings


---

## 🩺 6. Vulnerability Assessment and Exploit Intelligence

> 💡 **Overview:** Host/service discovery, vulnerability and CVE identification, security configuration audits, CVSS prioritization, KEV monitoring, exploit artifact discovery and classification, infrastructure correlation, remediation guidance and reporting.

**✨ Capabilities (25)**

- 🔹 Discover reachable hosts and services
- 🩹 Identify known vulnerabilities and CVEs
- 🔹 Detect missing security patches
- 🔹 Identify outdated and unsupported software
- 🔹 Check insecure service configurations
- 🔹 Perform authenticated and unauthenticated assessments
- 🧾 Audit supported operating systems and applications
- 🔹 Assess network devices and supported server software
- 🧾 Perform security configuration audits
- 🔹 Prioritize findings by severity
- 🔹 Use CVSS and supported risk-prioritization metrics
- 🔹 Provide remediation recommendations
- 📊 Generate vulnerability reports
- 🔹 Compare supported scan results over time
- 🔎 Search CVE records
- 🩹 Navigate related vulnerability information
- 🩹 Identify vulnerabilities highlighted as weaponized
- 👁️ Monitor Known Exploited Vulnerabilities updates where supported
- 💥 Discover exploit-related files in exposed directories
- 💥 Classify exploit artifacts
- 💥 Group similar exploit files
- 🔎 Search exploit files by SHA-256 hash
- 📤 Export supported exploit-file hashes
- 💥 Correlate exploit artifacts with infrastructure
- 🩹 Produce vulnerability and threat summaries

---

---

## 🧮 7. SQL-Based Threat Hunting

> 💡 **Overview:** SQL-based hunting across IP, HTTP, malware, phishing and WHOIS datasets.

**✨ Capabilities (11)**

- 🧮 Query supported intelligence datasets using SQL
- 🧹 Filter and correlate data across supported tables
- 🔎 Search IP, HTTP, malware, phishing, WHOIS, and related datasets where available
- 🕰️ Review query history
- 🔹 Rerun saved or previous queries
- 🔹 Stream query results
- 🔹 Paginate large result sets
- 🔹 Generate histograms
- 🔹 Visualize events over time
- 📤 Export supported results
- 🔹 Execute queries programmatically through available APIs

---

---

## 📥 8. Threat Feeds and External Integrations

> 💡 **Overview:** C2, phishing and IOC feeds with filters, SIEM/SOC integration and webhooks; REST/OpenAPI access, bulk enrichment and remote MCP integration; saved investigations, exports, team sharing, permissions, audit logs and SSO; interactive CLI with module management, profiles, concurrency and logging controls; data collection, normalization, correlation, caching, import/export and attribution; web dashboards, Docker deployment, custom modules and self-hosting.

**✨ Capabilities (76)**

- 📡 C2 infrastructure feeds
- 🎣 Phishing intelligence feeds
- 🧪 IOC feeds
- 📡 Custom intelligence feeds
- 🧹 Configurable feed filters
- 🔹 Third-party threat-intelligence integrations
- 🔌 API-based indicator enrichment
- 🔹 Bulk indicator processing
- 🔹 SIEM/SOC integration options where supported
- 🔹 OEM intelligence integrations
- 🔔 Webhook-based alert delivery where available
- 🔌 REST API access
- 🔹 OpenAPI specifications
- 🔌 API-based threat enrichment
- 🔎 Programmatic IOC searches
- 🔹 Bulk indicator extraction
- 🔹 Bulk enrichment
- 🧮 SQL query execution through supported endpoints
- 📤 Supported report and data exports
- 🔹 Remote Model Context Protocol integration
- 🤖 AI-client access to supported intelligence tools
- 🔌 OAuth and scoped API-key support where available
- 🔌 Configurable API limits and permissions
- 🔹 Save investigations and scan results
- 📤 Export reports in supported formats
- 📊 Generate PDF reports where available
- 📤 Export supported results as CSV, JSON, or text
- 🔗 Share investigation graphs and reports
- 🔹 Add notes and annotations
- 🔎 Review search and query history
- 🔗 Share workspaces with teams
- 🎟️ Pool lookup quotas where supported
- 👥 Configure team permissions
- 🧾 Maintain audit logs on eligible plans
- 🪪 Use enterprise SSO/SAML where available
- 📊 Customize report branding where supported
- ⌨️ Interactive command-line interface
- 🔎 List and search available modules
- 🧱 Display module help and options
- 🔹 Set and unset targets
- 🔹 Configure scan options
- 🧱 Run individual modules
- 🧱 Run module categories
- 🧱 Run favorite modules
- 🧾 Save and apply configuration profiles
- 🕰️ Review recent module history
- 🧱 Rerun the last module
- 🔎 Search cached output
- 🧵 Configure concurrency and thread limits
- 🔹 Configure timeouts and retries
- 🔹 Set request headers and user-agent strings
- 🔹 Configure logging levels and destinations
- 🔹 Clear console and reset supported settings
- 🔹 Collect data from public and configured sources
- 🔹 Normalize supported data types
- 🔹 Correlate entities across datasets
- 🔎 Filter and search collected results
- 🔹 Stream results where supported
- 🗄️ Cache supported results
- 📤 Export findings in supported formats
- 📥 Import supported user-provided data
- 🔹 Process lists of indicators in bulk
- 🔹 Maintain source attribution and timestamps where available
- 🔹 Web-based dashboards
- ⌨️ Local command-line execution
- 🔹 Python-based tooling where applicable
- 🐳 Docker and Docker Compose deployment where supported
- 🔌 API-based integrations
- 🔹 Configurable external data sources
- 🔌 Optional API-key configuration
- 🧱 Custom modules and transforms where supported
- 🗺️ Configurable map layers
- 🔹 Custom visualization styles
- 🔹 Extensible data-source architecture
- 🔹 Local deployment and self-hosting where supported
- 🔹 Configurable scan and data-refresh settings

---

## 🧾 Notes & Conventions

- 🧩 Phrases such as *“where supported”*, *“where available”* and *“where implemented”* indicate capabilities that depend on the underlying data source, feed or deployment configuration.
- 🔗 Feature 1 includes the external archive **archivegenocide.com**; Feature 3 (TrackWanted) draws on public sources including Interpol notices, the FAA registry, Planespotters, GDELT and ICIJ Offshore Leaks.
- 🔄 Refresh cadences noted in Feature 3: wanted board & money trail **twice daily**, aircraft registry index **weekly**, air-quality readings **every 10 minutes**.
- 📰 The Cryptonews.com capabilities listed at the end of Feature 1 were compiled from the cryptonews.com homepage and site navigation (snapshot of 2 Nov 2026); article counts, prices and audience stats are point-in-time or self-reported by the site.
- ⚖️ Source attribution, confidence indicators and correction/takedown channels are built into the tracking modules.
