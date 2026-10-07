# Christ Medical

Christ Medical is the patient records system for mission medical clinics.

## What it does

It keeps each patient's medical care and spiritual care in one record, so the team can care for the whole person.

| Medical care | Spiritual care |
|---|---|
| History and allergies, vitals, the reason for the visit, a diagnosis, and a plan for care | Whether a patient has heard the gospel, whether they have shown hope or interest, and notes on spiritual care |

Leaders see both on one dashboard: how many visits are on record, and how many patients have heard the gospel or shown hope or interest. Staff can find a patient even when the name is spelled differently.

Made for short-term mission clinics, starting with a team serving in Belize.

Coming next: new-patient check-in, medications, and prayer and follow-up.

## A clinic day

<p>
  <img alt="Clinic day diagram: arrival and check-in, vitals, exam, medications, spiritual follow-up, and discharge." src="https://raw.githubusercontent.com/christmedical/christmedical.com/main/docs/design/usage-journey.svg" width="100%">
</p>

How a patient is meant to move through the clinic, and which screen serves each step.

## Start here

The active system lives in **[christmedical.com](https://github.com/christmedical/christmedical.com)** — the current mission-clinic EMR (.NET API, Next.js PWA, PostgreSQL, field hub).

Everything else in this org is the **2016 prototype**, kept public as history. Start with the repo above unless you are excavating that earlier stack.

## How it is built

Open-source EMR for short-term medical mission clinics, built for unreliable connectivity.

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="architecture-dark.png">
    <img alt="Christ Medical architecture" src="architecture-light.png" width="100%">
  </picture>

<p align="center">

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://github.com/christmedical/christmedical.com/blob/main/LICENSE)
[![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</p>

Christ Medical is a multi-tenant EMR for short-term mission clinics. Field teams run an offline-tolerant hub with a checkout model: tablets talk to the hub over the local network while connectivity is thin, then a nightly one-way backup carries charts home when the link allows. Calm clinical UI, sunlight-readable tablets, Sanctified Bronze branding — tools built for the field, not a hospital LAN.

## License

[AGPL-3.0](https://github.com/christmedical/christmedical.com/blob/main/LICENSE), with a [commercial option](https://github.com/christmedical/christmedical.com/blob/main/COMMERCIAL-LICENSE.md).

## Get involved

Open an issue on [christmedical.com](https://github.com/christmedical/christmedical.com/issues). Questions or commercial licensing: [jamey@mcelveen.us](mailto:jamey@mcelveen.us).
