> **REVIEW DRAFT — not yet published.** Confirmed public publisher name: **kh_zw**. The effective date will be the actual publication date. UMP configuration, Data Safety approval and live M-Lab verification remain outstanding. The policy URL below is **planned and not live**.

# SignalX Pro — privacy policy publication candidate

**Final-review candidate — not approved or published.** Release: 1.4.0 (12). Effective date: `To be set on publication`. Developer/publisher name matching the Play listing: `kh_zw`. Privacy contact: khzw.apps@gmail.com. Developer website: https://khkh2269-35.github.io/ . The website and its app-ads.txt are live; this policy is still awaiting approval and publication.

SignalX Pro helps you inspect Android cellular observations, save optional coverage sessions, and run an optional Internet speed test. It includes Google AdMob banner advertising and Google's User Messaging Platform (UMP). No account or developer-operated measurement server is required. Advertising and speed-test providers receive data as described below.

## Cellular observations and local records

With your permission, the app reads cellular network information made available by Android: selected SIM/subscription and slot, operator information, serving/neighbor cell details, technology, band/frequency information when available, signal measurements, and timestamps. Android can require phone-state and precise-location permission and enabled device location for CellInfo even when GPS positions are not being recorded. Granting that permission does not itself start GPS recording.

Live histories are maintained on device. Explicitly saved coverage sessions may contain timestamps, subscription/slot references, cell references, radio metrics, notes and optional sampled device latitude/longitude and accuracy. Saved cells, place comparisons, outage observations, alert preferences and complaint drafts are also local features. The app does not send these cellular records, GPS positions or notes to its developer, Google advertising requests, or M-Lab test metadata.

Optional network monitoring is a separate action. It uses a visible foreground notification to continue CellInfo observations for the chosen duration; it does not enable GPS sampling or create a saved coverage session. Position-enabled coverage recording starts only after your explicit session choice and uses a visible location-service notification. A session without positions runs while the app is visible. You can stop these tasks in the app or available notification controls. Android or manufacturer battery controls can interrupt them. No “allow all the time” background-location grant is requested.

## Advertising and privacy choices

Google Mobile Ads collects and shares data such as the device's IP address (which can indicate general location), app/ad interactions, performance diagnostics, and applicable identifiers such as app set ID. This app configuration removes advertising-ID and Privacy Sandbox permissions, requests non-personalized ads and disables publisher first-party ID. These controls do not prevent all SDK data processing. Google uses this information for advertising, analytics and fraud prevention. Personalized, non-personalized or limited advertising behavior depends on your choices, local requirements and the publisher's actual configuration; non-personalized ads do not mean no data is processed. There is no separate developer analytics service.

UMP manages applicable privacy messages and choices. Use the app's privacy-options control when available to revisit choices. Android settings may allow you to reset or delete the advertising ID. Cellular/location permission is used for cellular features, not ad targeting; the app does not supply precise GPS or cell identities to ads. Google's data practices and controls: https://policies.google.com/privacy and https://policies.google.com/technologies/ads. This candidate integrates Google AdMob and UMP directly and includes no mediation adapters or separately added mediation partners. Applicable messages and privacy options depend on your region and the publisher's AdMob configuration. Any addition of advertising partners requires a review of this disclosure before release.

## Optional Internet tests

The speed test runs only when you choose it and accept its separate disclosure. It sends download/upload test traffic over your current Android Internet route, which may be Wi-Fi, mobile data or a VPN. It may consume substantial data and incur provider charges. Server discovery and the test connect to Measurement Lab (M-Lab) infrastructure, exposing your public IP address. M-Lab receives performance results, test time, connection information and protocol/client metadata required by the actual implementation. It publishes research data that can include your public IP address, results and test time. It may infer general location from IP. Precise GPS coordinates and cellular identifiers are not included by this app. Read https://www.measurementlab.net/privacy/ before running a test.

Cancelling stops further app test activity as soon as practicable; it cannot recall information already received by the test provider. Deleting a local result does not delete M-Lab's records or public copies. Requests about M-Lab data go through the contact and rights process in its policy; the app cannot guarantee deletion of those records.

The separate optional HTTPS response check connects to the hostname you confirm. That host and network/DNS services can receive connection information including your IP address and request timing. The host's own policies govern its logs. This response check is different from a throughput test.

Optional speed-test history is off by default. When enabled, it stores up to 50 local results with start/completion times, route category (such as Wi-Fi or VPN), observed download/upload/RTT, counted bytes, duration and phase stop reasons. Older records with unknown route remain unknown. It does not store IP addresses, server names, access tokens or SIM identifiers. Turning history off deletes this local history; it cannot delete M-Lab public records.

## Exporting, retention and deletion

CSV/PDF export and Android sharing occur when you request them. Review included fields and any coordinate option before sharing. Other apps, selected recipients and storage/cloud services handle exported copies under their own policies. The app's local deletion controls do not remove external copies.

Sessions remain in private app storage until you delete them or the app prunes them according to its retention settings and storage limits. Retention is not a guaranteed background deletion deadline. Session deletion and “Delete all sessions & saved cells” apply to the data named in those controls; other local features may have their own deletion controls. Clearing Android app storage or uninstalling removes app-private records and preferences. It does not erase exported files, recipient copies, or provider-held data. System app-data backup is disabled. Google and M-Lab retention/deletion practices are governed by their policies; no fixed third-party retention period is promised here.

## Security, children and contact

Advertising, consent and measurement connections use HTTPS/TLS/WSS transport. Local private storage and Android permission controls limit access, but no security method is absolute. No measurement account is created, so there is no in-app account to delete.

SignalX Pro is intended for adults aged 18 and over, as confirmed by the developer. It is not directed to children.

For questions about app-private data or this policy, contact khzw.apps@gmail.com. If the policy changes, the developer will update this page and its effective date.
