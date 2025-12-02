
# Blockchain-Based KYC Verification System for Emerging Markets  
FYP Part 1 – Investigation Report
Nathanael Kangwa Mumba | TP073695 | Asia Pacific University  

## Project Overview
A decentralised, offline-first, biometric-bound KYC wallet for rural Zambia using:
- Flutter (Android)  
- Polygon ID Release 6 + Halo2 zero-knowledge proofs  
- Fuzzy extractors for NRC fingerprint binding  
- Firebase offline persistence with CRDTs  
- did:peer + OOBI QR enrolment (no internet needed)

## Repository Structure (planned for Part 2 Implementation)
/lib
/core          → entities & use-cases
/data          → local SQLite + Firebase adapters
/domain        → credential & proof logic
/presentation  → Flutter screens
/infrastructure → Polygon ID, biometric, QR scanner
/circuits        → ageGreaterThanOrEqual18.circom
/tests           → unit & integration tests
/docs            → architecture diagrams, PIA draft


## Current Status (Part 1)
- Initial commit completed 02 December 2025  
- Repository created for continuous development  
- Full implementation starts May 2026 (FYP Part 2)  
- Target: 187 rural pilot participants (Oct–Dec 2026)

## Quick Start (planned)
```bash
flutter pub get
flutter run
