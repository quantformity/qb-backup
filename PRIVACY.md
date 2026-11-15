# LocalBookBackup — Privacy Policy

**App:** LocalBookBackup  
**Operator:** quantformity-sync  
**Version:** 1.0

This policy describes the intended local-only operation of LocalBookBackup, a private utility for exporting data from authorized QuickBooks Online companies. It does not cover Intuit, GitHub, independently modified copies, or third-party hosting services. Before deploying a version with different data handling, the operator must update this policy to reflect that handling.

## 1. Information accessed

With your authorization, the App may access:

- QuickBooks company identifiers and company information.
- Accounting records, such as invoices, expenses, purchases, bills, payments, journal entries, and related transactions.
- Related customer, vendor, employee, account, and item information where exposed by the API and required for the export. Records may contain names, contact details, addresses, and other personal information.
- Invoice PDFs and available uploaded attachments, including receipts, which may contain financial or personal information.
- OAuth credentials and tokens needed to authenticate requests and maintain authorized access.
- Operational information needed to track exports, such as record identifiers, timestamps, download status, and error details.

The actual data accessed depends on the implemented export features, your permissions, and the information Intuit makes available. The App does not require you to provide your QuickBooks password directly to it; sign-in and consent take place through Intuit.

## 2. Purpose of access

The App uses this information to authenticate with Intuit, retrieve authorized accounting data and documents, save local exports, and identify incomplete or failed downloads. It is intended for internal backup and record-export purposes, not advertising, profiling, or selling personal information.

QuickBooks Online's accounting authorization scope can permit both reads and writes. The App's intended behavior is limited to read and download operations.

## 3. Storage and recipients

In the intended local-only deployment, exported files, credentials, tokens, and export logs are stored on the computer or storage location selected by the person operating the App. There is no separate quantformity-sync hosted collection service for these exports in this deployment. The person running the App, and anyone they authorize to access that storage, may access those files.

The App communicates with Intuit to authenticate and retrieve data. Intuit processes those requests under its own policies and terms. Local exports are not intended to be sent to advertising, analytics, or unrelated third-party services.

If you place files in a cloud-synced folder, network drive, or external backup system, that system may receive copies according to your configuration and its policies. If you run the App on another person's computer or hosted infrastructure, the administrator of that environment may have access. These arrangements are your responsibility to assess.

## 4. Retention and deletion

You control how long local exports, logs, and credentials are retained. This policy does not establish an automatic deletion period. Keep data only as long as necessary for your authorized purposes and applicable accounting, tax, or legal obligations.

To remove stored information, delete the relevant exports, logs, and credential files, together with any copies in backups, synced storage, and trash or recycle bins as appropriate. Deleting local files does not delete the original QuickBooks records. Revoking authorization does not automatically delete existing exports.

## 5. Authorization and your choices

You can stop running the App at any time and revoke its access using QuickBooks Online's connected-app management controls. Revocation prevents further authorized access through that connection but does not erase previously downloaded information.

Only connect companies you own or are authorized to access. If exported records concern other people, you are responsible for having a lawful basis to process them, providing any required notices, and responding to applicable privacy-rights requests.

For requests concerning the original accounting records or copies held by a company using the App, contact that company's administrator or data controller. Where applicable law provides rights to access, correct, delete, restrict, or object to processing, or to receive a portable copy, requests should be directed to the party controlling the relevant records. Rights may be subject to legal retention obligations and other lawful exceptions.

## 6. Security

Accounting exports and OAuth tokens are sensitive. The operator should restrict file access, use appropriate device and storage encryption, protect backups, and keep dependencies current. Do not commit credentials, tokens, receipts, logs containing sensitive data, or accounting exports to a public repository.

Local storage alone does not guarantee security, and no transmission or storage method is completely secure. This policy does not claim that the App automatically encrypts exported files or removes all sensitive content from logs.

If credentials may have been exposed, revoke the affected connection, rotate applicable credentials, and review access to stored copies. The party responsible for the affected data must assess any legally required notifications.

## 7. Public repository and support

Source documents and support issues may be hosted on GitHub, which processes visitor and account information under its own privacy statement. A public repository or issue is not a private support channel. Do not submit personal financial records, tokens, credentials, or other confidential information in issues.

Any information you choose to post publicly may be visible to others. For general privacy questions, use the contact below without including sensitive details. If private communication is necessary, request a suitable private channel first.

## 8. Changes to this policy

Updates will be published in this repository with a new version identifier. Material changes to data handling should be reflected in this policy before they take effect, with additional notice or consent where legally required.

## 9. Contact

**Operator:** quantformity-sync  
**App:** LocalBookBackup  
**General privacy inquiries:** https://github.com/quantformity/qb-backup/issues

This issue tracker is public. Never include credentials or confidential financial or personal information.
