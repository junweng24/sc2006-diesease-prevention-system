# 2006-SCEC-I4
As there's a storage limit, kindly upload all deliverables format in .pdf and .jpeg format.

**All lab deliverables are listed in the [Index of Deliverables](INDEX.md).**

# Group Members 
1. YIM ZHENG RONG (Leader)
2. SHAUN CHEONG JIA YONG
3. PODDAR DEVANSH
4. POE PYI ZAW
5. CHOW JUN WENG

# Project Proposal 
To design and implement a disease prevention application

# Disease Prevention Application 
A centralized web-based application designed to monitor, report, and manage public health outbreaks, such as dengue clusters, within Singapore. This platform bridges the communication gap between the public and health authorities.  

# Key Features 
Public Dashboard: Residents can view live disease hotspots on an interactive map, report potential vector breeding sites, and register for community volunteering drives.  
Health Alerts: Users can opt-in to receive critical health advisories via SMS or email.  
Official Admin Portal: A secure dashboard for government and health officials to verify user reports, coordinate volunteer deployments, and broadcast public alerts.  

# Demo Video
▶️ **[Watch the demo video on YouTube](https://youtu.be/WiZzTxnBXd0)**

# Running the Application
The source code is in [`source-code/lab4-source-code.zip`](source-code/lab4-source-code.zip). Unzip it, then from the `source-code` folder run:

```
npm run setup     # once: installs the server and client, creates the database with demo data
npm run dev       # starts the API (localhost:3000) and the website (localhost:5173)
```

Full instructions are in `README.md` inside the zip.

# Team Contributions
| Area | Contributions | Team member(s) |
|---|---|---|
| Project management | Planned the project and split the tasks across the labs; arranged team meetings and kept the meeting minutes; set up and managed the GitHub repository | |
| Requirements (Lab 1) | Wrote the SRS: functional and non-functional requirements, business rules and glossary; collected and checked the external data sources (data.gov.sg dengue clusters, clinic data) | |
| Use Case Model | Drew the use case diagram; wrote the use case descriptions and the requirements traceability table | |
| Analysis and design models | Drew the class diagrams (key classes and entity classes); drew the dialog maps (public site and officials' portal); designed the system architecture (boundary, control, entity and repository layers) | |
| Front end: public site | Home page and public alert details; disease hotspot map; report a hotspot, with photo upload and address search; volunteer activities and registration; subscribe to and unsubscribe from alerts; nearest clinic locator | |
| Front end: officials' portal | Login and protected routes; dashboard; hotspot report review and hotspot management; publishing public alerts; volunteer activity management | |
| Back end | Server set-up and API routes; control classes (reports, hotspots, alerts, subscriptions, volunteering, clinics, authentication); entity classes, repositories and database; input validation and photo sanitising | |
| External services | data.gov.sg dengue cluster and clinic data; map and address search; SMS and email notification channels | |
| Testing (Lab 4) | Black-box tests (input validation); white-box basis path tests (login, report review); unsubscribe tests and the end-to-end smoke test | |
| Final deliverables (Lab 5) | Updated the SRS, class diagrams and dialog maps to match the code; demo presentation slides; live demo; demo video | |

The same table is in Appendix D of the [SRS](docs/SRS_Disease_Prevention_System.pdf).
