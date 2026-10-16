# Awesome-Appointment-Scheduling

# Top Appointment Scheduling Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Booking Infrastructure, Calendar Sync & Team Routing*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Appointment Scheduling**. These tools enable individuals and teams to share availability, automate booking flows, and manage calendars—from simple personal booking pages to enterprise routing engines that qualify leads before they book.

**Examples** include Calendly, Doodle, Acuity Scheduling, Setmore, Chili Piper, YouCanBookMe, Square Appointments, HubSpot Meetings, OnceHub, and Cal.com (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, calendar ownership, and open scheduling infrastructure—ideal for developers, privacy-conscious teams, and organizations seeking transparent, vendor-independent booking systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Calendly](https://calendly.com/)**  
  **The most widely adopted scheduling platform** with client self-scheduling and custom availability settings . **Free tier** supports one event type and one bookable calendar—no payments, no automated reminders . **Standard at $10/user/month**, Enterprise at $15,000/year for large companies . **The default choice** for individuals and small teams wanting quick setup.

- **[Chili Piper](https://www.chilipiper.com/)**  
  **Enterprise-grade inbound conversion engine**—leads book demos directly from forms or emails in under 30 seconds at the moment of intent . **Deep Salesforce and HubSpot integration** routes based on territory, account ownership, ICP fit, and rep availability . **Customers report 30-50% conversion lifts** on inbound demo flows . **Pricing starts at $15,000/year**—inaccessible to startups and SMB teams . **Annual-only contracts** with $45-50 per additional seat per month .

- **[YouCanBookMe](https://youcanbook.me/)**  
  **The most customizable small-business scheduler** with branded booking pages, 40+ languages, and deep form customization . **Free tier**: 1 calendar connection, 1 booking page . **Individual at $7.20/month**, Professional at $10.40/month, Teams at $14.40/member/month . **Stripe payments** with Apple Pay and Google Pay support . **6,000+ Zapier integrations** .

- **[Doodle](https://doodle.com/)**  
  **The original group scheduling tool** with free group polls, booking pages, and sign-up sheets . **Professional at $15/month** adds calendar sync, branding, ad-free experience, and participant tracking . **Team at $8.95/user/month** (annual) adds admin console, roles, custom branding, and Stripe payments . **Enterprise starts at $15,000/year** for 50+ employee orgs .

- **[Acuity Scheduling](https://acuityscheduling.com/)**  
  **The standard for consultation-based businesses**—astrologers, tarot readers, business consultants, and wellness practitioners . **Automations for reminders, follow-ups, and re-booking** are frequently praised . **Note**: No longer a standalone product—**requires a paid Squarespace account** to operate . **Pricing is high** for small businesses and non-profits .

- **[Setmore](https://www.setmore.com/)**  
  **Free plan with unlimited appointments** for solo practitioners. **Pro at $12/user/month** (monthly) or **$5/user/month** (annual) adds text reminders, Zoom/Google Meet integration, Google Reviews, recurring appointments, and 2-way calendar sync . **The most affordable paid tier** among major scheduling platforms.

- **[Square Appointments](https://squareup.com/appointments)**  
  **Free tier for single location** with unlimited calendars and mobile app . **Plus at €19/month** adds Google Calendar sync, automated confirmations, no-show protection, and multiple staff . **Premium at €49/month** adds resource management, time tracking, commissions, and Advanced Access . **The most integrated option** if you already use Square for payments.

- **[HubSpot Meetings](https://www.hubspot.com/)**  
  **CRM-native scheduling** with round-robin and group meeting availability . **Free with HubSpot CRM**. **Custom booking forms** with contact properties, CAPTCHA, and free email domain blocking . **Best for teams already using HubSpot** for sales and marketing.

- **[OnceHub](https://www.oncehub.com/)**  
  **Scheduling platform with strong calendar management and online booking** . **Starting at $10/month**. Reviewers note it can be a **powerful tool once you get used to the system**, but usability was a dealbreaker for some .

## Open-Source GitHub Projects

- **[Cal.com](https://github.com/calcom/cal.com)**  
  **The open-source scheduling infrastructure** (AGPL-3.0) . **The leading self-hosted Calendly alternative** with **full data ownership**—booking data, calendar credentials, and customer info stay on your infrastructure . **Feature parity with Calendly at the core layer**: event types, custom availability, buffers, minimum notice, time-zone detection, round-robin and collective scheduling . **Routing forms** qualify leads before they book . **Extensive app ecosystem**: Zoom, Google Meet, Teams, Stripe, PayPal, Salesforce, HubSpot, webhooks, Zapier, Make, and REST API . **Self-hosted is free**—pay only for your server (a Contabo VPS from EUR 4.28/month handles it) . **The best choice when you need full ownership, white-labeling, or GDPR-compliant data residency** .

- **[NextAppointments](https://github.com/ajdichmann/NextAppointments)**  
  **Self-hosted, open-source appointment scheduling built with Next.js and TypeScript** . **Features**: smart scheduling with customizable availability, buffer times, and booking rules; client communication via email and SMS; customizable branding with logo, colors, and custom domain; responsive design for desktop, tablet, and mobile . **Premium integrations** include CRM sync (Salesforce, HubSpot), payment processing (Stripe, PayPal), and calendar sync (Google, Outlook) . **Tech stack**: Next.js, React, TypeScript, Node.js/Express, PostgreSQL/MySQL/MongoDB . **Deploy via Vercel, Docker, or custom hosting** .

- **[Cal.com DIY (cal.diy)](https://github.com/calcom/cal.diy)**  
  **The self-hosting distribution of Cal.com**—the open-source Calendly alternative . **Full setup documentation** including PostgreSQL configuration, Prisma schema migration, and MailHog for development email testing . **`yarn workspace @calcom/prisma db-migrate`** initializes the database schema . **Windows/PowerShell users** have specific guidance for environment variable injection . **The practical path to running Cal.com on your own infrastructure** .

- **[Cal.com (GitHub)](https://github.com/calcom/cal.com)**  
  The main repository. See Cal.com above.

### Additional Strong Open-Source Options

- **Calendso** — The original name of Cal.com before rebranding. Historical references may point here.
- Community **n8n** workflows for booking automation and calendar sync orchestration.

**Frameworks for building custom systems**: Combine **Cal.com** for production-ready self-hosted scheduling with **NextAppointments** for a lighter Next.js-native alternative, **PostgreSQL** for persistence, and **Stripe** for payments—creating a fully self-hosted, enterprise-grade appointment scheduling platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Appointment scheduling tools handling personal data must comply with data protection regulations (GDPR, CCPA, etc.) and calendar provider terms of service.
- **Open-source scheduling is mature and production-ready.** Cal.com provides feature parity with Calendly at the core layer while offering **full data ownership**—the decisive advantage for GDPR-conscious teams and regulated industries . **Self-hosting can save thousands of dollars per year for teams of 10+ users** .
- **Calendly's free tier is limited.** One event type, one bookable calendar, no payments, no automated reminders . **The paid tiers unlock the features most businesses actually need.**
- **Chili Piper is a different category.** It's not a booking tool—it's an **inbound conversion engine** that qualifies leads and routes them to the right rep at the moment of intent . **$15K/year is the price of enterprise conversion optimization** .
- **Acuity requires Squarespace.** The standalone product no longer exists—**you must have a paid Squarespace account** . This is a significant change that affects small businesses and non-profits.
- Self-hosted open-source solutions require proper security hardening, database management, and ongoing maintenance. **Calendar credentials are sensitive**—encryption at rest and access controls are essential.

---

**Made for developers, small business owners, and operations teams building transparent scheduling solutions.**  
Let's make Appointment Scheduling more open, data-driven, and calendar-independent.
