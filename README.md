# RoutePal UK Address Data

Public data-download repository for RoutePal. The RoutePal application source code remains in a separate private repository.

## Data contents

Regional SQLite address shards are generated from OpenStreetMap address data and are intended to support postcode-area downloads in RoutePal's House Finder.

**Important coverage note:** OpenStreetMap address data is community-mapped and incomplete. It is not an authoritative or guaranteed-complete postal address register. Search results should be treated as best-effort matches and verified where necessary.

## Licensing and attribution

The address text layer is derived from © OpenStreetMap contributors and is available under the Open Database License (ODbL). See https://www.openstreetmap.org/copyright and https://opendatacommons.org/licenses/odbl/.

Each published release should include its own manifest with shard names, sizes, checksums, coverage metadata and licence details. RoutePal should download only the selected postcode-area shard, after the user chooses to download it.

## Releases

Download regional data from the [Releases](https://github.com/danshish/routepal-address-data/releases) page. Do not download the entire repository archive for in-app use.
