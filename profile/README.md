# Christ Medical

The chart a church clinic team carries to Belize. Medical care and spiritual care in the same visit.

<img alt="A clinic day in Belize: secretary, nurse, doctor, and pastor, with a patient walking the clinic path. One record for medical care and spiritual care." src="clinic-day.png" width="240" align="left">

*Personal project for a short-term church clinic. Not a hospital product.*

Secretary finds the patient even if the name is spelled differently.

Nurse records vitals.

Doctor writes the visit.

Pastor notes hope, interest, and prayer.

Leaders see visits and spiritual care on one dashboard.

Made for short-term mission clinics, starting with a team serving in Belize. Paper summary still goes home with the patient.

<br clear="left">

| <h3>✚ Medical care</h3> | <h3>✟ Spiritual care</h3> |
|---|---|
| History and allergies, vitals, the reason for the visit, a diagnosis, and a plan for care | Whether a patient has heard the gospel, whether they have shown hope or interest, and notes on spiritual care |

<img alt="How a patient moves through the clinic: check-in, vitals, exam, medications, spiritual care, and discharge." src="https://raw.githubusercontent.com/christmedical/christmedical.com/main/docs/design/usage-journey.svg" width="100%">

Coming next: check-in, medications, and prayer and follow-up.

## Start here

The active system is **[christmedical.com](https://github.com/christmedical/christmedical.com)** (.NET API, Next.js PWA, PostgreSQL, field hub).

Other repos in this org are the 2016 prototype.

## How the box stays up when the link dies

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

Tablets talk to the hub on the clinic LAN, then a nightly one-way backup carries charts home.

## License

[AGPL-3.0](https://github.com/christmedical/christmedical.com/blob/main/LICENSE), with a [commercial option](https://github.com/christmedical/christmedical.com/blob/main/COMMERCIAL-LICENSE.md).

## Get involved

Open an issue on [christmedical.com](https://github.com/christmedical/christmedical.com/issues). Questions or commercial licensing: [jamey@mcelveen.us](mailto:jamey@mcelveen.us).
