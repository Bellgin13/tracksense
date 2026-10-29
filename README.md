# TrackSense

TrackSense audits e-commerce analytics tracking: it walks a store's purchase flow,
captures dataLayer and GA4 events, and validates them against the GA4 ecommerce spec.
Deterministic rules find the errors; an LLM explains root causes and suggests fixes,
grounded in documentation.
Every claim is measured with an eval set of sessions with known, injected bugs.
