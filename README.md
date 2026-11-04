# Awesome Field Sales Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of field sales, sales force automation (SFA), beat planning and route planning software for teams whose reps visit dealers, retailers and customers in person.

Grouped by **how you pay and who owns the system**, because for a field team that decision matters more than any single feature.

> **Disclosure:** this list is maintained by the makers of Beatplan (listed under "Buy once, own the source"). Every other entry is independent. Corrections and additions are welcome by pull request.

## Contents

- [How to choose](#how-to-choose)
- [Subscription SaaS: door-to-door and territory sales](#subscription-saas-door-to-door-and-territory-sales)
- [Subscription SaaS: CPG / FMCG distribution and retail execution](#subscription-saas-cpg--fmcg-distribution-and-retail-execution)
- [CRM add-ons with field features](#crm-add-ons-with-field-features)
- [Buy once, own the source](#buy-once-own-the-source)
- [Open source building blocks](#open-source-building-blocks)
- [Building your own](#building-your-own)
- [Buyer guides](#buyer-guides)
- [Glossary](#glossary)

## How to choose

| If you need... | Look at |
|---|---|
| Route planning and lead tracking for door-to-door or territory reps | Door-to-door and territory sales |
| Beat plans, dealer orders, collections and retail audits for a distributor | CPG / FMCG distribution |
| Field features inside a CRM you already pay for | CRM add-ons |
| To own the system, avoid per-user fees, or resell it to clients | Buy once, own the source |
| A free base and an in-house developer | Open source building blocks |

Questions worth asking any vendor: Does it work **offline**? Can reps **check in with GPS and photos**? Does it record **payments / collections**, not just orders? Who owns the **data model**? What does it cost at **your** headcount in year three?

## Subscription SaaS: door-to-door and territory sales

- [SPOTIO](https://spotio.com) - Field sales engagement: territory mapping, route planning, lead tracking. Per-user subscription.
- [Badger Maps](https://www.badgermapping.com) - Route planning and mapping for outside sales reps. Per-user subscription.
- [Map My Customers](https://mapmycustomers.com) - Map-based CRM for field sales teams. Per-user subscription.
- [SalesRabbit](https://salesrabbit.com) - Door-to-door sales app for canvassing teams. Per-user subscription.
- [Lystloc](https://www.lystloc.com) - Field employee tracking and attendance. Per-user subscription.

## Subscription SaaS: CPG / FMCG distribution and retail execution

- [Repsly](https://www.repsly.com) - Retail execution and merchandising for CPG brands. Subscription.
- [BeatRoute](https://beatroute.io) - Retail sales, distribution and beat planning for consumer brands. Subscription.
- [Bizom](https://bizom.com) - Retail intelligence and distributor management for FMCG. Subscription.
- [FieldAssist](https://www.fieldassist.com) - Sales force automation and DMS for CPG distribution. Subscription.
- [Pepperi](https://www.pepperi.com) - B2B commerce and retail execution with offline mobile ordering. Subscription.
- [Skynamo](https://www.skynamo.com) - Field sales app for wholesalers and manufacturers. Subscription.
- [SimplyDepo](https://simplydepo.com) - Distribution management, B2B ordering and retail execution. Subscription.
- [Unolo](https://unolo.com) - Field force management, attendance and beat plans. Subscription.
- [Delta Sales App](https://deltasalesapp.com) - Sales force automation for field employees. Subscription.

## CRM add-ons with field features

- [Salesforce Maps](https://www.salesforce.com/sales/maps/) - Territory planning and routing inside Salesforce. Add-on licence.
- [Zoho CRM](https://www.zoho.com/crm/) - CRM with mobile check-ins and territory management. Per-user subscription.
- [Vtiger Field Sales](https://www.vtiger.com) - Beat plans and visit tracking within Vtiger CRM. Subscription.

## Buy once, own the source

- [Beatplan field sales app](https://beatplan.app) - Complete field sales and fleet system for distributors: day/beat plans, GPS-verified dealer visits with photos, collections against targets, dealer orders through dispatch, company car odometer and expenses, director dashboards. Expo (iPhone, Android, web, offline queueing) + Supabase. One-time licence from $2,900. Commercial and white-label agency licences available. Setup guide written for AI coding assistants (Claude Code, Codex). [Live demo](https://beatplan-demo.netlify.app). *(Maintainer's product.)*

## Open source building blocks

General-purpose systems with sales modules that a developer can extend toward field sales:

- [Odoo Community](https://github.com/odoo/odoo) - ERP and CRM suite; field service is in the paid Enterprise edition. LGPL-3.0.
- [ERPNext](https://github.com/frappe/erpnext) - Open source ERP with sales, stock and a mobile-friendly UI. GPL-3.0.
- [EspoCRM](https://github.com/espocrm/espocrm) - Lightweight, customizable CRM. AGPL-3.0.
- [SuiteCRM](https://github.com/salesagility/SuiteCRM) - Open source CRM forked from SugarCRM. AGPL-3.0.
- [Twenty](https://github.com/twentyhq/twenty) - Modern open source CRM. AGPL-3.0.

## Building your own

Stacks and guides that come up repeatedly in field app builds:

- [Expo](https://expo.dev) - One React Native codebase for iPhone, Android and web.
- [Supabase](https://supabase.com) - Postgres, auth, storage, row-level security and edge functions.
- [WatermelonDB](https://github.com/Nozbe/WatermelonDB) - Offline-first local database for React Native.
- [An offline-first field sales app on Expo and Supabase: lessons from a year in production](https://dev.to/shaoor_ahmad_f9ab22689b95/an-offline-first-field-sales-app-on-expo-and-supabase-what-a-year-of-daily-production-use-taught-me-40jd)
- [A Supabase row-level security checklist for multi-role apps](https://dev.to/shaoor_ahmad_f9ab22689b95/a-supabase-row-level-security-checklist-for-multi-role-apps-from-a-163-policy-production-schema-4dlf)

## Buyer guides

- [SPOTIO, Badger Maps and Repsly alternatives you pay for once (2026)](https://medium.com/@shaoorahmadmlt/spotio-badger-maps-and-repsly-alternatives-you-pay-for-once-2026-86bddfb53714)
- [Beat plan app for FMCG distributors: what it must do, and how to own one](https://medium.com/@shaoorahmadmlt/beat-plan-app-for-fmcg-distributors-what-it-must-do-and-how-to-own-one-instead-of-renting-5b87245e71fd)
- [White-label field sales app for agencies](https://beatplan.hashnode.dev/white-label-field-sales-app-for-agencies-deliver-a-proven-sfa-system-to-clients-instead-of-building-one)
- [Buying SFA app source code: a technical checklist](https://beatplan.hashnode.dev/buying-sales-force-automation-sfa-app-source-code-a-technical-checklist)
- [BeatRoute, Bizom, FieldAssist, Delta Sales App and Pepperi pricing (2026)](https://medium.com/@shaoorahmadmlt/beatroute-bizom-fieldassist-delta-sales-app-and-pepperi-pricing-2026-offline-order-taking-81ee593dc6c2)
- [White-label field sales app pricing for resellers and agencies (2026)](https://medium.com/@shaoorahmadmlt/white-label-field-sales-app-pricing-for-resellers-and-agencies-2026-per-user-reseller-source-f0b50afe8cca)
- [Field sales app source code you can buy and rebrand: CodeCanyon scripts vs production systems](https://beatplan.hashnode.dev/field-sales-app-source-code-you-can-buy-and-rebrand-codecanyon-scripts-vs-production-systems-2026)
- [Field sales automation (SFA) app source code with a one-time licence: beat plan, order booking and cash/cheque collection](https://dev.to/shaoor_ahmad_f9ab22689b95/field-sales-automation-sfa-app-source-code-with-a-one-time-licence-beat-plan-order-booking-and-e36)
- [SFA source code for field sales order booking and collection: CodeCanyon vs ERPNext/Odoo vs a production app](https://dev.to/shaoor_ahmad_f9ab22689b95/sales-force-automation-sfa-source-code-for-field-sales-order-booking-and-collection-codecanyon-49e6)
- [Field sales app pricing per user (2026): BeatRoute, Bizom, FieldAssist, Delta Sales App vs a one-time licence](https://dev.to/shaoor_ahmad_f9ab22689b95/field-sales-app-pricing-per-user-2026-beatroute-bizom-fieldassist-delta-sales-app-vs-a-3a8o)

## Glossary

- **Beat plan** - A rep's fixed, repeating schedule of outlets or dealers to visit, common in FMCG distribution.
- **SFA (sales force automation)** - Software for planning, recording and reviewing field sales activity.
- **DMS (distributor management system)** - Software for a distributor's orders, stock, schemes and billing.
- **Retail execution** - Checking shelf placement, stock and promotions in stores.
- **Collections** - Payments a rep collects from dealers against invoices or targets.

## Contributing

Pull requests welcome. Please keep descriptions factual, one line, and state the pricing model.
