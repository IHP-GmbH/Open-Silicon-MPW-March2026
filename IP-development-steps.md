# IP development steps

Use these steps when working inside the standalone IP repository before requesting
submodule inclusion.

1) Implement the design and keep the directory layout intact.
2) Keep the top cell name aligned with the generated name across all views.
3) Maintain `doc/info.json` with accurate metadata, release paths, and dependencies.
4) Fill the corresponding Technology Readiness Level (TRL) document under `doc/`.
5) Populate `release/<version>/` with production-ready deliverables (GDS, netlist,
   and supporting documentation).
6) Run the verification flow and confirm `doc/info.json` paths resolve to existing
   release files.
