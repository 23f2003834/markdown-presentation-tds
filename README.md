---
marp: true
theme: gaia
paginate: true
headingDivider: 1
style: |
  section { font-family: "Segoe UI", sans-serif; }
  section::after { font-size: 0.55em; color: #666; content: attr(data-marpit-pagination) " / " attr(data-marpit-pagination-total); }
  footer { 
    position: absolute; 
    bottom: 15px; 
    left: 0; right: 0; 
    text-align: center; 
    font-size: 0.4em; 
    color: #666; 
  }
---

<!-- _class: lead -->
# SecureAuth Pro v5.2  
Product Documentation

**23f2003834@ds.study.iitm.ac.in**

<footer>23f2003834@ds.study.iitm.ac.in</footer>

---

## Features

- Passwordless FIDO2 login  
- Adaptive MFA  
- Real-time risk engine  
- SAML 2.0 + OIDC

<footer>23f2003834@ds.study.iitm.ac.in</footer>

---

<!-- _class: invert -->
![bg opacity:0.3](https://images.unsplash.com/photo-1558494949-ef010cbdcc31?q=80&w=2236&auto=format&fit=crop)

## Risk Scoring Model

$$
\text{RiskScore} = \sum_{i=1}^{n} w_i \cdot f_i
$$

$$
\mathcal{O}(\log n)
$$

<footer>23f2003834@ds.study.iitm.ac.in</footer>

---

## Setup

```bash
npm install @secureauth/pro@5.2
