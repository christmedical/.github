# Christ Medical

Open-source EMR for short-term medical mission clinics, built for unreliable connectivity.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/christmedical/christmedical.com/main/docs/assets/architecture-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/christmedical/christmedical.com/main/docs/assets/architecture-light.svg">
    <img alt="Christ Medical architecture" src="https://raw.githubusercontent.com/christmedical/christmedical.com/main/docs/assets/architecture-light.svg" width="100%">
  </picture>
</p>

<p align="center">

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://github.com/christmedical/christmedical.com/blob/main/LICENSE)
[![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)

</p>

## Start here

The active system lives in **[christmedical.com](https://github.com/christmedical/christmedical.com)** — the current mission-clinic EMR (.NET API, Next.js PWA, PostgreSQL, field hub).

Everything else in this org is the **2016 prototype**, kept public as history. Start with the repo above unless you are excavating that earlier stack.

## What it is

Christ Medical is a multi-tenant EMR for short-term mission clinics. Field teams run an offline-tolerant hub with a checkout model: tablets talk to the hub over the local network while connectivity is thin, then a nightly one-way backup carries charts home when the link allows. Calm clinical UI, sunlight-readable tablets, Sanctified Bronze branding — tools built for the field, not a hospital LAN.

## License

[AGPL-3.0](https://github.com/christmedical/christmedical.com/blob/main/LICENSE), with a [commercial option](https://github.com/christmedical/christmedical.com/blob/main/COMMERCIAL-LICENSE.md).

## Get involved

Open an issue on [christmedical.com](https://github.com/christmedical/christmedical.com/issues). Questions or commercial licensing: [jamey@mcelveen.us](mailto:jamey@mcelveen.us).
