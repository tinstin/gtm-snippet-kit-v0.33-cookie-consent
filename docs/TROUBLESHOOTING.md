# Troubleshooting
Common issues solved in this build:
- [Type]=template → fixed with uppercase parameter enums.
- ManualConsentOption REQUIRED → removed.
- EventType CONSENT_INITIALIZATION → replaced by DOM Ready.
- measurementIdOverride missing → fixed on all GA4 Event tags.
- Custom event filter must use {{_event}} → enforced.
- gtag() in HTML → removed; uses dataLayer.push instead.
