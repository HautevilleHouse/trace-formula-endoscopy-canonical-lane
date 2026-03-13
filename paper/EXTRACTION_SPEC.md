# Extraction Spec

Framework: `trace_formula_endoscopy`

Required constants:

- `kappa_trace`
- `sigma_stable`
- `kappa_compact`
- `rho_rigidity`
- `endoscopic_transfer`
- `eps_coh`
- stitch key `sigma_star_can`

All constants are extracted from explicit formulas in `artifacts/constants_extraction_inputs.json`, promoted into the registry and stitch files, then consumed by the closure guard.
