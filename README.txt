JT Bottle Weigh Mini v31

Base: user-supplied v29.

Research integrated into the existing Mini without replacing its core interface:
- Scan -> Identify -> Weigh -> Save -> Next remains primary workflow
- Configurable local scale bridge with manual fallback
- Bottle Intelligence observation history and confidence A-D
- Saved shelf/rail physical count order per venue/location
- Live events: Spill, Breakage, Kitchen Use, Transfer, Comp/Staff, Other
- Automatic user/location/timestamp capture for events
- Inventory lifecycle: OPEN -> COUNTING -> SUBMITTED -> MANAGER REVIEWED -> LOCKED
- Locked-session correction reason requirement
- Audit trail
- JSON backup/restore of operational data
- Owner review summary includes events/audit/state
- Existing v29 product catalog, UPC library, master data, images and reports preserved

Commercial architecture fields are preserved behind Mini so Professional can later consume the same product/location/movement/event/person records. POS, invoices, purchasing and theoretical variance remain Professional functions rather than cluttering Mini.


v31 FORMULA / RESEARCH UPDATE
- Primary bottle math now uses tare + liquid density + nominal bottle volume.
- Full sealed weight remains a fallback/reference rather than the only calculation method.
- Category density defaults: spirits 0.9755 g/mL; sugar/liqueur/syrup 1.0200; bitters/beer/wine 1.0000.
- Scale Read takes 5 samples and flags moving/unstable weight when range exceeds 0.08 oz.
- Raw gross, tare, density, liquid mL and calculation method are preserved with count records.
- Bottle Intelligence flags tare outliers while retaining raw observation history.
- Existing v30 localStorage keys are intentionally retained so upgrades preserve v30 data.
