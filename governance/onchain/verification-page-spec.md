# Credential Verification Page Specification

## Purpose

Defines the public verification page for SydTek University certificates.

## Page Fields

The verification page should display:

- Certificate status
- Program name
- Credential title
- Certification level
- Issue date
- Institution
- Verification hash
- Revocation status

## Page Should Not Display

- Full private assessment notes
- Student contact information
- Recordings
- Private logs
- Sensitive identity data

## Status Types

### Active

Credential is valid.

### Revoked

Credential has been revoked.

### Replaced

Credential was reissued to a new wallet.

### Expired

Credential requires renewal.

## Verification Message

Example:

This credential record was issued by SydTek University and verifies completion of the Certificate in Reciprocal Fluency Lab at the listed certification level.

## Core Principle

Public verification should be simple, clear, and privacy-safe.