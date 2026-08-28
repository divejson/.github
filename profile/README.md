# DiveJSON

An open interchange format for scuba dive logs. One JSON document carries a complete
logbook — dives with full sampled profiles, gas mixtures, trips, dive sites, marine-life
sightings, gear and its service history, certifications — so a diver's data can move
between applications without loss.

- **Site:** <https://divejson.org>
- **Specification, JSON Schema, fixtures, validator:**
  [divejson/divejson](https://github.com/divejson/divejson)
- **Media type:** `application/vnd.dive+json` · file extension `.divejson`

**Status: v1.0 draft.** The format freezes when its reference implementation's
export/import round-trip passes against it. Problems, ambiguities, and proposals are
GitHub issues on the spec repository — a real document the spec mishandles is the most
valuable kind of report.
