# Online Voting System — Electoral Simulation

An interactive browser-based **National Voting Simulation** that demonstrates voter lookup, ballot casting, electoral-roll browsing, simulated national turnout analytics, and an election-officer result workflow.

## 📌 Project Overview

This project is an educational voting-system simulation built as a standalone HTML application. It provides two main areas:

- **Cast Your Vote** — find a voter record, verify status, select a candidate, and cast a simulated ballot.
- **Records & Results** — view simulated national-scale election statistics, turnout, state/UT registers, and voter records.

The application uses an **8,000-voter interactive sample** distributed proportionally across Indian states and Union Territories. The national-scale figures are simulated and are not live election data. 

## ✨ Features

### 🗳️ Voter Portal
- Voter ID lookup
- Voter status verification
- Interactive electoral-roll browser
- Search by voter name or ID
- Region and voting-status filters
- Candidate selection
- One-vote-per-voter simulation
- Vote confirmation and timestamp

### 📊 Records & Results Dashboard
- India-scale simulated electorate
- Estimated electorate statistics
- Simulated national turnout
- State and Union Territory register
- Top regions by estimated electorate
- State/UT search and filtering
- Votes-cast and turnout visualizations

### 👮 Election Officer Panel
- Polling status management
- Results remain sealed while polling is open
- Officer PIN verification
- Close polling and declare results
- Reopen-poll simulation

## 🧩 Candidate Options

The simulation contains five ballot options:

- Unity Party
- Progress Party
- People's Front
- New Horizon
- None of the Above (NOTA)

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- SVG/CSS-based visual elements
- Browser Storage API used by the simulation
- Google Fonts: Fraunces, Inter, IBM Plex Mono

## 📁 Project Structure

```text
online-voting-system/
│
├── online voting system.html
├── svg/
│   └── [SVG assets, if used]
└── README.md
```

## ▶️ How to Run

### Option 1 — Directly in a browser

1. Download or clone the project.
2. Keep `online voting system.html` and its `svg` assets in the expected relative locations.
3. Open `online voting system.html` in a modern browser.

### Option 2 — Local development server

For more reliable browser-storage and asset behavior, serve the project through a local HTTP server.

Example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/online%20voting%20system.html
```

## 🔄 Voting Workflow

```text
Enter Voter ID
      ↓
Find Voter Record
      ↓
Check Voting Status
      ↓
Select Candidate
      ↓
Cast Vote
      ↓
Record Vote + Timestamp
      ↓
Lock Voter from Voting Again
```

## 👮 Officer Workflow

```text
Polling Open
     ↓
Party-wise Results Sealed
     ↓
Enter Officer PIN
     ↓
Close Poll
     ↓
Declare Simulated Results
     ↓
Results Become Visible
```

## 💾 Data & Simulation

The application generates fictional voter records and stores the simulation state in shared browser storage. Voter information such as names, addresses, phone numbers, emails, and verification documents is fictional demo data.

The application models national population and turnout using approximate state/UT population shares and simulated turnout values. The interactive electoral roll contains 8,000 sample voters rather than India's full population.

## 🔐 Security Disclaimer

This is an **educational simulation**, not a production electronic voting system and not an official election platform.

It should **not** be used to collect real voter information or conduct real elections.

A production-grade e-voting platform would require substantially stronger controls, including verified identity binding, end-to-end vote encryption, voter-verifiable audit mechanisms, secure key management, independent security audits, threat modeling, and appropriate legal/compliance controls.

## 🎯 Learning Objectives

This project demonstrates:

- Interactive front-end development
- DOM manipulation and event handling
- Client-side state management
- Browser storage
- Form validation
- Search and filtering
- Data visualization
- Simulated election workflows
- Role-based UI behavior
- Responsive dashboard design

## 👨‍💻 Author

**Shivesh Verma**

Computer Science & Engineering  
FinTech • Software Engineering • AI/Data

- GitHub: https://github.com/shivesh9
- LinkedIn: https://linkedin.com/in/shivesh-verma0320
- Email: shiveshv17@gmail.com

## ⚠️ Disclaimer

All voter records, election results, population-scale figures, turnout values, and identity details in this project are simulated or fictional. The project is intended strictly for learning and portfolio demonstration.
