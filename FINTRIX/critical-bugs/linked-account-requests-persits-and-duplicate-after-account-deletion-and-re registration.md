# Bug Report: Linked Account Requests Persist and Duplicate After Account Deletion & Re-registration

## Platforms

* Android
* iOS

## Severity

Critical

## Priority

High

---

## Title

Linked account requests persist and duplicate after account deletion and re-registration, causing inconsistent linking behavior

---

## Description

There are multiple inconsistencies and data persistence issues in the account linking flow across Android and iOS. When a user deletes their account and re-registers, previously linked account requests are not cleared. Additionally, duplicate and inconsistent linking states appear, especially on iOS.

---

## Preconditions

* User A and User B accounts exist
* (For extended scenario) User C account exists

---

## Steps to Reproduce

### Android

1. User A links account with User B
2. User B links account with User A (link established successfully)
3. User A deletes their account
4. User A re-registers using the same credentials
5. Check User B's linked account requests

---

### iOS

1. User A links account with User B
2. User B attempts to link with User A
3. Observe system message
4. User A deletes their account
5. User A re-registers
6. Check linked account requests
7. User C links account with User B
8. Check User B's linked account request list

---

## Expected Result

* All linked account relationships and requests should be **fully removed** when a user deletes their account
* Re-registered users should be treated as **new users with no previous link history**
* Linking should be **consistent and symmetric** (A ↔ B should behave the same both ways)
* No duplicate or stale requests should appear

---

## Actual Result

### Android

* After User A deletes and re-registers, the previous account link request is still visible in User B’s account

### iOS

* When User B tries to link back to User A, system shows **"account already linked"** even if flow is incomplete or inconsistent
* After User A deletes and re-registers:

  * Old link requests still persist
* When User C links with User B:

  * User A’s old request **reappears or duplicates** in the linked account request list

---

## Impact

* Causes **data inconsistency and duplication**
* Leads to **confusing user experience**
* Breaks expected account lifecycle behavior
* Potential risk of **incorrect account associations**

---

## Possible Root Cause (QA Observation)

* Backend is not clearing relational data on account deletion
* Stale link request records remain in database
* Missing cleanup of:

  * Link mappings (A ↔ B)
  * Pending requests
* Potential caching or sync issue across devices/platforms

---

## Recommendations

* Ensure complete cleanup of:

  * Linked account relationships
  * Pending requests
* Treat re-registered users as new entities (no historical linkage)
* Add validation to prevent duplicate requests
* Sync logic across Android and iOS for consistent behavior

---

## Attachments

* (Add screenshots / logs if available)
