---
name: qabs
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: YELLOWSTORLLC

---

/* Hero */
.qabs-hero{display:flex;gap:30px;align-items:center;flex-wrap:wrap;padding:30px;border-radius:12px;background:#fff;box-shadow:0 1px 3px rgba(0,0,0,0.04);}
.qabs-hero-media{flex:1;min-height:260px;background-size:cover;background-position:center;border-radius:10px;background-color:#e0e7e4;}
.qabs-hero-content{flex:1;min-width:320px;}
.qabs-hero-title{font-size:36px;color:var(--qabs-dark);margin:0 0 12px;line-height:1.3;font-weight:800;}
.qabs-hero-sub{color:#58606a;margin:0 0 18px;font-size:18px;line-height:1.6;}
.qabs-hero-ctas{display:flex;gap:12px;align-items:center;margin-bottom:18px;flex-wrap:wrap;}

/* Buttons & Links */
.qabs-btn{display:inline-block;padding:12px 22px;border-radius:8px;text-decoration:none;color:#fff;background:var(--qabs-accent);font-weight:600;transition:all 0.2s ease;border:none;cursor:pointer;font-size:16px;text-align:center;}
.qabs-btn:hover{background:var(--qabs-accent-light);transform:translateY(-1px);}
.qabs-btn.primary{background:var(--qabs-accent);}
.qabs-btn.outline{background:transparent;color:var(--qabs-dark);border:1px solid #ccc;}
.qabs-btn.outline:hover{background:#f5f5f5;transform:none;}
.qabs-link{color:#0a6b5a;text-decoration:underline;font-weight:500;transition:color 0.2s;}
.qabs-link:hover{color:#073a2f;}

/* Features List */
.qabs-features{list-style:none;padding:0;margin:10px 0 0;display:flex;gap:18px;flex-wrap:wrap;}
.qabs-features li{background:#f5f6f7;padding:8px 12px;border-radius:8px;color:#333;font-size:14px;}

/* Sections */
.qabs-section{margin-top:40px;}
.qabs-section-title{font-size:24px;color:var(--qabs-dark);margin-bottom:8px;font-weight:700;}
.qabs-section-desc{color:#6b7280;margin-bottom:18px;font-size:16px;}

/* Services Grid */
.qabs-services-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:16px;}
.qabs-service-card{padding:20px;border-radius:10px;border:1px solid #eef0f1;background:#fff;transition:all 0.2s ease;display:flex;flex-direction:column;}
.qabs-service-card:hover{box-shadow:0 4px 12px rgba(0,0,0,0.06);transform:translateY(-2px);}
.qabs-service-icon-wrap{font-size:40px;margin-bottom:12px;}
.qabs-service-content{flex-grow:1;}
.qabs-service-title{margin:0 0 8px;color:#0e4c40;font-size:18px;font-weight:700;}
.qabs-service-desc{margin:0 0 12px;color:#5b6166;font-size:14px;line-height:1.5;}
.qabs-service-sku{display:inline-block;background:#f3f4f6;padding:2px 8px;border-radius:4px;font-size:12px;color:#6b7280;margin-left:4px;}
.qabs-service-price{display:block;font-weight:700;color:var(--qabs-dark);margin-top:4px;font-size:18px;}
.qabs-service-cta{color:var(--qabs-accent);text-decoration:none;font-weight:600;margin-top:12px;align-self:flex-end;transition:color 0.2s;}
.qabs-service-cta:hover{text-decoration:underline;color:#a07420;}

/* Packages */
.qabs-pricing-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;}
.qabs-price-card{padding:20px;border-radius:10px;background:#fff;border:1px solid #ececec;text-align:center;transition:all 0.2s ease;display:flex;flex-direction:column;}
.qabs-price-card:hover{box-shadow:0 4px 12px rgba(0,0,0,0.06);}
.qabs-price-card h4{color:var(--qabs-dark);margin-bottom:8px;font-size:18px;}
.qabs-price-card p{color:#5b6166;margin-bottom:16px;font-size:14px;flex-grow:1;}
.qabs-price-card .qabs-btn{margin-top:auto;}

/* About */
.qabs-about{text-align:center;padding:20px;background:#fff;border-radius:12px;border:1px solid #eef0f1;}
.qabs-about-text{color:#4b5563;line-height:1.7;margin-bottom:16px;max-width:700px;margin-left:auto;margin-right:auto;}

/* Footer Note */
.qabs-footer-note{color:#9aa0a6;font-size:13px;text-align:center;margin-top:30px;border-top:1px solid #eef0f1;padding-top:20px;}

/* Responsive Design */
@media (max-width:768px){
  .qabs-container{padding:20px 15px;}
  .qabs-hero{flex-direction:column;padding:20px;}
  .qabs-hero-media{width:100%;min-height:200px;}
  .qabs-hero-title{font-size:28px;}
  .qabs-hero-sub{font-size:16px;}
  .qabs-services-grid{grid-template-columns:1fr;}
  .qabs-pricing-grid{grid-template-columns:1fr;}
}
