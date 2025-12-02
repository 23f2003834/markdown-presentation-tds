---
marp: true
theme: gaia
paginate: true
headingDivider: 1
class: gaia
style: |
  section { font-family: 'Segoe UI', sans-serif; }
  section.lead h1 { color: #1e40af; }
  section::after { content: attr(data-marpit-pagination) ' / ' attr(data-marpit-pagination-total); color: #666; }
  .email { position: absolute; bottom: 20px; right: 30px; font-size: 0.4em; color: #888; opacity: 0.8; }

# Custom Theme for Product Documentation
<!-- _class: lead -->
<!-- _paginate: false -->

### SecureAuth Pro v5.2 Documentation  
**Presented by Technical Writing Team**  
23f2003834@ds.study.iitm.ac.in

<div class="email">23f2003834@ds.study.iitm.ac.in</div>

## Overview of Features

- Multi-factor authentication (MFA)
- Single Sign-On (SSO) with SAML 2.0 & OIDC
- Adaptive risk-based authentication
- Passwordless login via WebAuthn/FIDO2
- Real-time fraud detection engine

<div class="email">23f2003834@ds.study.iitm.ac.in</div>

## Algorithmic Complexity – Risk Scoring Engine
<!-- backgroundColor: #0f172a -->
<!-- _class: invert -->

![bg brightness:0.3](https://images.unsplash.com/photo-1550751827-4bd374c3f58b?q=80&w=2070&auto=format&fit=crop)

### Real-time Risk Scoring Model

$$
\text{RiskScore} = w_1 \cdot \text{LocationAnomaly} + w_2 \cdot \text{DeviceFingerprint} + w_3 \cdot \log(\text{Velocity}) + w_4 \cdot \text{BehavioralScore}
$$

$$
O(n) = \mathcal{O}(\log n)\text{ per request using Merkle trees}
$$

<div class="email">23f2003834@ds.study.iitm.ac.in</div>

## Setup Instructions

```bash
# Install SecureAuth Agent
npm install @secureauth/agent@5.2.1

# Configure in config.json
{
  "tenant": "your-company.secureauth.com",
  "riskThreshold": 0.75,
  "enforceMFA": true
}
