# On-Chain Certificate Verification

## Purpose

Defines how SydTek University certificates may be verified using blockchain records without making the blockchain the source of academic truth.

---

## Core Rule

The institution issues the certificate.

The blockchain verifies the record.

---

## What Goes On-Chain

Only minimal verification data should go on-chain:

- Certificate ID
- Student wallet address
- Program ID
- Certification level
- Issue date
- Verification hash
- Issuer wallet

---

## What Does Not Go On-Chain

Do not place private student data on-chain.

Do not place:

- Full legal name
- Student age
- Email
- Recordings
- Assessment details
- Private session logs
- Personal documents

---

## Verification Hash

The verification hash may represent:

- Certificate PDF
- Assessment record
- Issuer approval
- Timestamped credential metadata

---

## Wallet Binding

A certificate may be bound to:

- Student wallet
- Institutional wallet
- Issuer wallet

---

## Revocation

If fraud is discovered, the institution may publish a revocation record.

The original record remains visible, but the credential status changes to revoked.

---

## Core Principle

Blockchain proves that a credential record existed.

It does not replace institutional judgment.