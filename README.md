# AGID Western Europe Index

AGID Western Europe index for Europe country and territory repository coordination.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-europe-western-europe-index`
- Stage: `wave-0-index`
- Data readiness: `index-ready`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and special
region display policy for Europe address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles, or
search indexes.

## Related Repositories

- `agid-country-fr` - France (FR)
- `agid-country-be` - Belgium (BE)
- `agid-country-nl` - Netherlands (NL)
- `agid-country-lu` - Luxembourg (LU)
- `agid-country-mc` - Monaco (MC)

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, and
quality gate metadata. Large geography, hydrographic datasets, building
polygons, OSM/Overture extracts, and generated caches must stay in external
content-addressed packs.

## Overseas And Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Overseas-linked,
disputed, or special regions must carry explicit source, license, canonical
region, and display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.
