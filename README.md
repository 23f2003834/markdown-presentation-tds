---
marp: true
theme: gaia
paginate: true
headingDivider: 1
style: |
  section { font-family: "Segoe UI", sans-serif !important; }
  section::after {
    font-size: 0.55em;
    color: #666;
    content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total);
  }
  .email {
    position: absolute;
    bottom: 20px;
    right: 30px;
    font-size: 0.45em;
    color: #888;
    opacity: 0.9;
  }
---

<!-- _class: lead -->
<!-- _paginate: false -->

# SecureAuth Pro v5.2  
Product Documentation

**Technical Writer**  
23f2003834@ds.study.iitm.ac.in

<div class="email">23f2003834@ds.study.iitm.ac.in</div>

---

## Key Features

- Passwordless login (FIDO2 / WebAuthn)  
- Adaptive multi-factor authentication  
- SAML 2.0 & OpenID Connect support  
- Real-time behavioral risk engine  
- Device fingerprinting & geovelocity checks

<div class="email">23f2003834@ds.study.iitm.ac.in</div>

---

<!-- _class: invert -->
![bg opacity:0.25](https://images.unsplash.com/photo-1558494949-ef010cbdcc31?q=80&w=2236&auto=format&fit=crop)

## Risk Scoring Algorithm (Mathematical Model)

$$
\text{RiskScore} = w_1 \cdot \text{Location} + w_2 \cdot \text{Device} + w_3 \cdot \log(\text{Velocity}) + w_4 \cdot \text{Behavior}
$$

$$
\text{Time Complexity} = \mathcal{O}(\log n)\quad \text{(Red-Black tree lookup)}
$$

<div class="email">23f2003834@ds.study.iitm.ac.in</div>

---

## Quick Setup Guide

```bash
npm install @secureauth/pro@5.2.0
