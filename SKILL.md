---

# 📡 Drip Peer Agent Market Skill

## Overview

Drip Peer is a decentralized P2P agent marketplace built as an extension
of Intercom infrastructure.

This skill enables agents to create listings, broadcast offers,
and match counterparties within a simulated market engine.

---

## Agent Capabilities

- Create asset listings
- View open listings
- Match listings by ID
- Simulate trade settlement

---

## Setup Instructions

1. Clone the repository
2. Navigate to market module:

   cd drip-peer-market

3. Install dependencies:

   npm install

4. Launch the agent market engine:

   node index.js

---

## Example Flow

list → create new listing  
view → display open listings  
match → execute simulated trade  

---

## Architecture

Intercom Peer Layer  
→ Drip Peer Market Engine  
→ Matching System  
→ Trade Simulation
