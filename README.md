# Facility Digital Handoff

*The operating record a MokuLab project container hands to the organization
that owns it.*

Every facility on the shared map belongs to a place — its moku — and to an
organization: the people who own it, run it, and answer for it.
[Mokunet](https://mokunet.org) keeps those organization records;
[MokuLab](https://mokulab.io) is where a project for that facility is designed,
built, and operated on one open, governed model. This repository is the shape
of what comes out the far end: the **handoff package** — the record a
facility's own staff hold when the project closes out.

## Who owns a container

A MokuLab project container — a cloud project with its model, storage, drawing
set, and checks, bound to one facility — is **held by the organization that
owns the facility**, through the role that subscribes to it on the network.
Any organization with a record on the network can be that owner:

- a public or charter school, with its complex area
- a farm, a producer cooperative, or a shared processing facility
- a community hub, a learning center, or a research site
- a county or state facility, or the nonprofit that runs one

Schools are the first cohort listed here, not the definition. The organization
names the roles that operate its container — owner, facilities manager,
designer, contractor — and can take the record with it at any time.

## What the handoff package is

At closeout, the container's model, drawing set, checks, and operating data
are packaged as a static, version-controlled record that the facility's own
staff hold:

- usable offline and in air-gapped settings
- for inspections, audits, repair planning, and operations and maintenance
- as the long-term record of the building, with every change traceable —
  who, where, when
- readable by the facilities-management tools and dashboards the organization
  already uses

Every record points back to the facility's place on the shared map and to the
authoritative sources that describe it. We honor the official lines; we don't
redraw them.

## What this repository holds today

- [`data/SchoolList.json`](data/SchoolList.json) (and the same list as
  `.xlsx`) — the 292 Hawaiʻi Department of Education public and charter
  schools (256 public, 36 charter) across seven islands, with school code,
  address, complex area, DOE school district, and island: the first cohort of
  facilities whose organizations can hold a container.

**Stage, honestly:** project containers and the handoff package are being
built on MokuLab, and the organization records that hold a subscription are
being built on the platform. The school list is data; the package layout it
will feed is not yet published here. Nothing here is presented as further
along than it is.

## Where to go

- **[mokunet.org](https://mokunet.org)** — the network's public home;
  [Community](https://mokunet.org/community) is where organization records
  live.
- **[Moku Data Governance Hub](https://hawaii.mokunet.us)** — the platform
  app: records grounded in place, access scoped to your kuleana — your role,
  and where you stand.
- **[MokuLab](https://mokulab.io)** — Systems Lab for Design-Build workflows:
  where a facility's project is designed, built, and operated on one model.

---

Stewarded by [Āina Design Corp](https://ainadesign.org), which designs,
builds, and operates the network. Official records stay with the agencies
that hold them.
