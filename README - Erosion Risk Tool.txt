PATH: A COASTAL EROSION RISK TOOL — WALKTHROUGH (README)
========================================================

A single web page (this .html file) that turns coastal-erosion findings into clear
vulnerability and risk maps. It runs offline in a browser; nothing is uploaded.

STEP 1 — SUMMARY
  Overview and this walkthrough.

STEP 2 — ASSET INVENTORY GENERATOR (Community Administrator)
  - List each community asset: name, latitude, longitude (decimal degrees) and
    consequence (Low / Moderate / High). Optionally set the three time horizons.
  - Download TWO blank sheets: the asset inventory (for the record) and the transect
    sheet (for the consultant). They are separate files.

STEP 3 — CONSULTANT / ENGINEER (offline)
  - Fills the transect sheet: for each transect along the shore, its present-day
    coordinates, its orientation (the compass bearing the shoreline recedes toward),
    and the projected shoreline recession (m) for a Baseline and a High scenario at
    each time horizon. Transects should span far enough along the shore to cover every
    asset. Returns the file.

STEP 4 — EROSION HAZARD INPUT (Community Administrator)
  - Upload BOTH sheets (asset inventory + transect sheet).
  - The tool draws the shoreline through the transect points and the receded shoreline
    by moving each point inland along its bearing. Maps are shore-aligned (sea at the
    bottom, north arrow rotated).
  - For each time horizon: a vulnerability-envelope map, a 3x3 risk matrix, and a
    High/Moderate/Low/Not-at-Risk banding; plus recession-over-time maps and
    when-vulnerable bandings for each scenario. Download them all as a PDF.

HOW RISK IS SCORED
  An asset is exposed when it falls inside a recession envelope.
  Likelihood: inside the Baseline envelope = High(3); inside only the High envelope =
  Moderate(2); within the buffer beyond the High envelope = Low(1); beyond = 0.
  Consequence: Low(1) / Moderate(2) / High(3).  Risk = Likelihood x Consequence (1-9).

NOTE
  The shoreline is drawn through the transect points, smoothed and extended to the map
  edges — schematic, not surveyed. Read alongside Inuit Qaujimajatuqangit and local
  knowledge.