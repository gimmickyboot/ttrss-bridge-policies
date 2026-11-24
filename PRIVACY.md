# ttrss-bridge Privacy Policy

Last updated: 24 November 2026

## Operator and scope

ttrss-bridge is a private, noncommercial Devvit integration operated by the maintainer of this project for personal RSS reading. It has no public signup, commercial users, advertising, or third-party analytics. It is independent of Reddit and Tiny Tiny RSS. Reddit processes data under its own privacy policy and terms. This policy describes the current prototype and the conditions that must be satisfied before any external export is enabled.

## Information and purpose

The prototype reads public submissions from a small configured list of communities. It stores observed Reddit submission IDs in Devvit Redis for 14 days to avoid repeated processing. Operational logs include poll counts, community names and submission IDs. The app does not intentionally collect or store author IDs or usernames, post bodies, comments, private communications, or account profiles. It does not send any information outside Reddit at present.

If Reddit expressly approves external export, the app would send only submission IDs, community names, titles, canonical Reddit links and destination URLs to the operator's private server at `gimmickyboot.com` over authenticated HTTPS to provide a private RSS feed for Tiny Tiny RSS. Titles and links can contain identifying information supplied by the original author; they are not claimed to be anonymous. No data will be sold, made available in public feeds, shared with other recipients or used for profiling or AI training.

## Retention, access and deletion

Seen IDs expire after 14 days; the app does not store exported content in Redis. Reddit controls its platform log retention. Access to the planned receiver and Tiny Tiny RSS will be restricted to the operator. Before export is enabled, both must have minimal retention and a verified process to promptly update or remove data when the corresponding Reddit content is changed, restricted or deleted, when Reddit or the relevant user requests it, or when it is no longer necessary. External data must be deleted when the service stops. The planned external deletion and retention controls are not implemented yet, and export remains disabled until they are.

## Contact and requests

For privacy questions, corrections or deletion requests, email [privacy@gimmickyboot.com](mailto:privacy@gimmickyboot.com). Include a Reddit submission URL or ID where relevant, and provide only the information needed to identify the request. Requests are received privately by the operator; email correspondence and any information supplied are used only to respond to and handle the request and are retained only as needed for that purpose or to meet legal obligations. The operator will respond and remove or correct data as applicable under Reddit's policies and applicable law. Please do not send passwords or other sensitive information.

## Policy changes

This policy will be updated before any material change to the app's data handling or external export. The latest revision date appears at the top of this document.

This policy does not override Reddit's [Privacy Policy](https://redditinc.com/policies/privacy-policy) or [Developer Terms](https://redditinc.com/policies/developer-terms).
