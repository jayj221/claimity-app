# Claimity

Claimity helps Employees' Provident Fund (EPF) members understand why a claim stopped or was rejected, which records do not match across offices, and what to correct next.

Built for OpenAI's Build What Moves India hackathon (2026); placed in the top 250 of 13,500+ entries.

**Live demo:** https://jayj221.github.io/claimity-app/

## What it does

- **Record-mismatch check.** Compares a member's EPFO, Aadhaar, PAN and bank records field by field and names the exact field that differs, instead of a bare pass or fail. Each difference opens a correction desk with the form already filled from the member's records.
- **Claim-Scan.** Scans a claim before it is filed and shows where it would stop. After a correction, the member re-runs Claim-Scan and sees the finding clear.
- **Medical-priority route.** For medical claims, Claim-Scan asks for the hospital admission slip and the doctor's prescription instead of the usual four records, and helps the member prepare a priority review request.
- **Claim tracking.** Tracks which office has actually received a claim, rather than showing a status word.
- **Multilingual.** The interface is available in English, Hindi, Marathi, Bengali, Tamil and Telugu, with read-aloud in each language through the browser's speech synthesis.

## Run it

Open the [live demo](https://jayj221.github.io/claimity-app/), or clone the repo and open `index.html` in a browser. It is a single static page with no build step and no server.

## Disclaimer

Independent prototype. Not affiliated with EPFO or the Government of India, and it does not connect to EPFO systems. All member records in the app are synthetic, and service behaviour is simulated.
