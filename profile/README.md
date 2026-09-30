<a href="https://gaplessly.com"><img src="https://raw.githubusercontent.com/gaplessly/.github/main/profile/assets/banner.png" alt="Gaplessly: booking software for appointment businesses and hospitality venues" width="100%"></a>

<p align="center">
  <a href="https://gaplessly.com"><b>Website</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://gaplessly.com/docs"><b>API reference</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/gaplessly/mcp"><b>MCP server</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://github.com/gaplessly/cli"><b>CLI</b></a>
  &nbsp;&middot;&nbsp;
  <a href="https://gaplessly.com/pricing"><b>Pricing</b></a>
</p>

<p align="center">
  White-label booking software, built in Sydney. No commission and no per-cover fees, on any plan.
</p>

<p align="center">
  <a href="https://gaplessly.com/openapi.json"><img alt="OpenAPI 3.1" src="https://img.shields.io/badge/OpenAPI-3.1-0d647f?style=flat-square"></a>
  <a href="https://registry.modelcontextprotocol.io/v0.1/servers?search=com.gaplessly/booking"><img alt="MCP Registry: com.gaplessly/booking" src="https://img.shields.io/badge/MCP%20Registry-com.gaplessly%2Fbooking-0d647f?style=flat-square"></a>
  <a href="https://www.npmjs.com/package/@gaplessly/cli"><img alt="npm: @gaplessly/cli" src="https://img.shields.io/npm/v/%40gaplessly%2Fcli?style=flat-square&label=%40gaplessly%2Fcli&color=0d647f"></a>
  <a href="https://gaplessly.com"><img alt="gaplessly.com status" src="https://img.shields.io/website?url=https%3A%2F%2Fgaplessly.com&style=flat-square&label=gaplessly.com&up_color=0d647f"></a>
</p>

<br>

<table>
  <tr>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gaplessly/.github/main/profile/assets/appointments-dark-1440.png">
        <img src="https://raw.githubusercontent.com/gaplessly/.github/main/profile/assets/appointments-light-1440.png" alt="The Gaplessly appointments calendar, one column per staff member" width="100%">
      </picture>
      <p><b>Appointments</b><br>
      Salons, barbers, clinics and studios. A calendar per staff member, real-time availability, reminders, and guests who reschedule for themselves.</p>
    </td>
    <td width="50%" valign="top">
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gaplessly/.github/main/profile/assets/hospitality-dark-1440.png">
        <img src="https://raw.githubusercontent.com/gaplessly/.github/main/profile/assets/hospitality-light-1440.png" alt="The Gaplessly live floor view, tables on a 3D floor plan" width="100%">
      </picture>
      <p><b>Hospitality</b><br>
      Restaurants, cafes and bars. Tables on a real floor plan, lunch and dinner as separate service periods, table combining and a live floor view.</p>
    </td>
  </tr>
</table>

## Open source

| Project | What it does |
|---|---|
| **[gaplessly/mcp](https://github.com/gaplessly/mcp)** | The booking connector for AI assistants. Find free appointment and table times at any Gaplessly venue, then hand the guest a link to finish. Public, read-only, no key. |
| **[gaplessly/cli](https://github.com/gaplessly/cli)** | Command-line client for the Gaplessly API. Read your clients, appointments, reservations and more as JSON. Zero dependencies. |

```bash
# Connect an AI assistant
claude mcp add --transport http gaplessly https://gaplessly.com/api/mcp

# Read your own data (needs an API key from your dashboard)
npx @gaplessly/cli organization
```

## For developers

| Resource | What it is |
|---|---|
| [**API reference**](https://gaplessly.com/docs) | Every public endpoint, with its auth, scopes and status codes |
| [**OpenAPI 3.1**](https://gaplessly.com/openapi.json) | The same reference, machine-readable |
| [**API catalog**](https://gaplessly.com/.well-known/api-catalog) | The three APIs on gaplessly.com, as an RFC 9727 linkset |
| [**Auth and scopes**](https://gaplessly.com/.well-known/oauth-protected-resource) | RFC 9728 metadata. Keys go in an `Authorization: Bearer` header |
| [**llms.txt**](https://gaplessly.com/llms.txt) | The whole product, summarised for language models |

## Contact

[hello@gaplessly.com](mailto:hello@gaplessly.com) &nbsp;&middot;&nbsp; [LinkedIn](https://www.linkedin.com/company/gaplessly/) &nbsp;&middot;&nbsp; [Instagram](https://www.instagram.com/gaplessly/) &nbsp;&middot;&nbsp; Sydney, Australia
