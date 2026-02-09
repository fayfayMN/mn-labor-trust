# mn-labor-trust
Minnesota Labor Compliance Trust Infrastructure
The Twin Cities "Safe-Compliance" Initiative

A privacy-first technical layer using Zero-Knowledge Proofs (ZKPs) to bridge the gap between 2026 MN labor mandates and worker protection.

2. The "Why" (Problem Statement)

Dual Crisis: Twin Cities small businesses must meet strict 2026 tracking mandates for 15-minute breaks and 30-minute meals or face $10,000 fines.

The Fear: Immigrant workers fear that traditional employment records will be seized during federal enforcement (ICE raids), which have increased 250% in the region.

Impact: This has led to a 23% labor shortage and a weekly economic loss of $10M–$20M in local cultural districts.

3. The "How" (Solution & Innovation)
We provide a decentralized identity (DID) system where:

Workers prove work authorization via QR codes without revealing their personal identity.

Businesses maintain audit-ready logs for the MN Department of Labor without storing any sensitive personal data.

Privacy-First Architecture: Features include ephemeral data that auto-deletes identity mappings after 24 hours and local-first storage on worker devices.

4. Technical Stack for your GitHub

Frontend: React Native with Expo (using libraries like snarkjs for ZKPs and expo-camera for QR scanning).

Backend: Supabase (PostgreSQL) for encrypted metadata.

Cryptography: did:key methods and Ed25519 signatures for mobile performance.

Hardware: NTAG215 NFC tags and Bluetooth beacons for presence verification.

5. Project Goals (Success Metrics)

Stabilize Economy: Secure $250,000+ in PROMISE Act grants for pilot businesses by providing compliant payroll proof.

Protect Workforce: Support 50+ workers in a pilot phase with 0 personal data points exposed to business owners.

Reduce Fear: Aim for a 60% reduction in worker fear sentiment through cryptographic anonymity
