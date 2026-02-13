# Overtime Tracking & Billing Dashboard

## Overview
Excel dashboard that automatically detects unbilled overtime charges by comparing actual in-car time vs scheduled pickup time. Eliminates manual reservation-by-reservation checking.

## Problem
- Overtime verification was done manually, one reservation at a time
- Unbilled overtime charges were frequently missed
- No systematic way to identify extra hours across all services

## Solution
Automated dashboard that:
- Imports CSV data from LimoAnywhere and transforms it using Power Query
- Compares "In-Car Time" vs "PU Time" to detect overtime automatically
- Flags reservations requiring overtime billing ("Requer hora extra")
- Enables filtering by fleet type (in-house vs vendor), state, and city

## Key Features
- **Automatic overtime detection** through time comparison logic
- **Multi-filter interface**: Type (FARM_OUT/IN_HOUSE), Status, State, City
- **Billing reconciliation**: Shows corrected vs uncorrected charges
- **Financial summary chart**: Displays recovered overtime revenue

## Technical Stack
- Excel + Power Query
- CSV data transformation
- Formula-based time comparison
- Dynamic filtering and pivot tables

## Impact
- ✅ 100% overtime detection (vs manual checking)
- ✅ R$ 720 recovered in January 2026 alone
- ✅ Eliminated manual reservation-by-reservation process
- ✅ Real-time billing accuracy with audit trail

## Screenshots

### Overtime Detection Table
<img width="1301" height="740" alt="image" src="https://github.com/user-attachments/assets/7b9b89a6-5f48-4030-af73-ac4f7e9ea9cb" />

### Billing Summary
<img width="1547" height="824" alt="image" src="https://github.com/user-attachments/assets/412aed45-85b0-43f0-b5dc-f57eca939dcc" />
