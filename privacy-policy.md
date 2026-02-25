# Privacy Policy for TrueCode/OpenOBD Chrome Extension

**Effective date:** 25 February 2026

This Privacy Policy describes how the **TrueCode/OpenOBD Chrome Extension** (the "Extension") handles information.

## Summary

- The Extension is intended for use on `https://partner.jifeline.com/portal/*`.
- The Extension **does not collect, sell, or share personal data** for advertising or analytics.
- The Extension stores only limited data in Chrome local extension storage that is necessary for functionality.

## What the Extension Accesses

The Extension accesses:

1. **Jifeline portal pages** (`https://partner.jifeline.com/portal/*`) to provide the TrueCodeOnline workflow UI in-page.
2. **TrueCode/OpenOBD API** (`https://oscatruecode-b7fadvgcedcjemc7.ukwest-01.azurewebsites.net/*`) to fetch brands/workflows and start workflows.
3. **Microsoft identity flow** (via Chrome `identity` API) to sign users in and obtain an access token.

## Data Stored Locally

The Extension may store the following in `chrome.storage.local`:

- `entraToken` (authentication token)
- `entraTokenExpiresAt` (token expiry time)
- Optional partner API credentials if configured by the user:
  - `partnerClientId`
  - `partnerClientSecret`

This data is stored **locally in the user’s browser** and used only to operate extension features.

## Data Sharing and Transfer

The Extension sends data only as required to perform its core function:

- To Microsoft identity endpoints during sign-in.
- To the configured TrueCode/OpenOBD API endpoint.
- To Partner/Jifeline API endpoints when resolving ticket/make information.

The Extension does **not**:

- sell user data,
- use data for advertising,
- run third-party analytics or tracking scripts.

## Retention

Locally stored authentication data remains until it expires, is cleared, or the Extension is removed. Users can clear this data by:

- removing extension storage entries, or
- uninstalling the Extension.

## Security

Reasonable measures are used to limit data use to required extension operations. However, no method of transmission or storage is completely secure.

## Children’s Privacy

The Extension is not directed to children.

## Changes to This Policy

This Privacy Policy may be updated from time to time. Material changes will be reflected by updating the effective date above.

## Contact

For privacy questions, contact: **enquiries@osca.online**
