# Topical Authority — bengkel-las.co.id

## Role and boundary

`bengkel-las.co.id` should be the Indonesian practical reference for welding workshops and metal fabrication: how welded products are specified, fabricated, inspected, maintained, repaired, and procured safely. It serves homeowners and buyers as well as welders, supervisors, fabricators, designers, and facility teams. The geographic scope is Indonesia, with explicit attention to humid and coastal exposure, informal-workshop procurement, field installation, and applicable K3 obligations.

The knowledge layer is educational. Existing service routes such as `/bending/`, `/kanopi/`, `/konstruksi-baja/`, and `/pagar-besi/` own transactional intent, quotation requests, service areas, portfolio proof, warranty, and workshop capability. Articles may explain how to evaluate those services and link to a relevant service route, but must not impersonate a sales page. Structural sizing, load-path approval, welding-procedure qualification, regulated inspection, hot-work authorization, electrical work, pressure-system work, and hazardous repair remain professional tasks.

Other owned domains may independently cover steel, wire, aluminium, stairs, façades, gates, or construction services. That is cross-domain editorial overlap, not cannibalization; only competing intents within this domain are controlled here.

## Evidence audited

Audit date: 2026-07-23. Evidence is repository-local unless a source link is given.

| Evidence | Observed count/finding | Planning implication |
|---|---:|---|
| Sitemap artifacts | 6 XML files | `page-sitemap.xml`, three post sitemaps, `sitemap-complete.xml`, and `update-sitemap.xml` disagree and need one canonical index |
| Sitemap rows | 1,051 rows; 1,049 exact unique URLs | Exact URL totals are inflated by parallel manifests and extension variants |
| Normalized sitemap paths | 586 unique after removing `.html` and trailing slash; 464 duplicate groups | Canonical, redirect, and sitemap consistency must precede content expansion |
| Local HTML files | 475 | Static WordPress export rather than a source-driven content collection |
| Root geography/service files | 428 | 408 bending variants across four services and 20 city variants for ten fabricated products; do not count as editorial depth |
| Local service hubs | 16 | Bending hub plus four material/form hubs and eleven product/fabrication hubs |
| Meaningful update articles | 12 | Mostly short selection/design posts about teralis, railing, stairs, canopies, stainless steel, and coatings |
| Archives and pagination | 11 | Eight category/archive pages plus three blog listing pages; navigation utilities, not authority articles |
| Post-sitemap-only laser routes | 102 city URLs | Referenced in legacy post sitemaps but absent from the local export |
| Page-sitemap routes missing locally | 4 hubs | `/laser-cutting/`, `/cnc-cutter/`, `/cnc-laser-cutting/`, and `/cnc-milling/` have no local page file |
| Redirect configuration | 8 self-referential rules | Four missing machining/cutting routes redirect to themselves and require deployment testing/manual repair |
| Crawl controls | no `robots.txt` found | Add crawl policy only after canonical and sitemap decisions are implemented |

Repository evidence was sampled through HTML titles, H1s, canonical/routes, service directories, all sitemap files, `_redirects`, and git status. The repository is on clean `main` tracking `origin/main`.

Primary-source evidence gates for later drafting:

- Indonesia's JDIH Kemnaker records [Permenaker No. 5/2018 on workplace environment K3](https://jdih.kemnaker.go.id/peraturan/detail/1546/peraturan-menteri-nomor-5-tahun-2018), [Permenaker No. 12/2015 on workplace electrical K3](https://jdih.kemnaker.go.id/peraturan/detail/610/peraturan-menteri-nomor-12-tahun-2015) and its amendment, and [Permenaker No. 37/2016 on pressure vessels and storage tanks](https://jdih.kemnaker.go.id/peraturan/detail/1429/peraturan-menteri-nomor-37-tahun-2016) as in force on the audit date.
- ISO's current records provide the evidence framework for fusion-welding quality requirements in ISO 3834, welder qualification in ISO 9606, weld imperfection quality levels in ISO 5817, and NDT selection in [ISO 17635:2025](https://www.iso.org/standard/85705.html). Exact applicability, edition, acceptance level, and contractual adoption must be verified for each article and project rather than presented as universal Indonesian law.

## Existing coverage and risks

| Existing URL/pattern | Observed role/problem | Decision | Destination/owner | Verification needed |
|---|---|---|---|---|
| `/bending/` and four child hubs | Legitimate commercial service taxonomy | keep | Existing commercial routes | Verify unique service scope, canonical, response code, and internal links |
| `bending-{besi,pipa,plat,stainless-steel}-{city}.html` and extensionless variants | 408 location-swapped pages with little evidence of locality | manual review | National service hub plus only substantiated local landing pages | GSC demand, backlinks, leads, local proof, canonical target, and content uniqueness |
| Ten `{product}-{surabaya,sidoarjo}.html` patterns | Local commercial routes for fabricated products | manual review | Corresponding product service hub | Retain only where service area, proof, logistics, and conversion value are real |
| `/laser-cutting-*.html` in post sitemaps | 102 sitemap-only location URLs absent locally | remove | Correct canonical sitemap | Confirm live status and external equity before removing from manifests |
| `/laser-cutting/`, `/cnc-cutter/`, `/cnc-laser-cutting/`, `/cnc-milling/` | Listed in page sitemap but missing from repository | manual review | Restore a real service page or remove route and self-loop redirect | Live response, Cloudflare deployment source, business capability, redirect loop |
| `_redirects` self-target rules | Can loop or do nothing for missing CNC/cutting routes | remove | Explicit destination chosen after route audit | Test deployed responses before replacement |
| `/update/pengertian-stainless-steel/` | Thin broad material definition competing with future material hub | expand | WLD-02-A04 | Preserve URL if indexed; add fabrication-specific scope |
| Two anti-rust/metal-paint posts | Likely outline overlap | merge | WLD-12-A04 | Compare GSC, backlinks, and actual body copy before choosing canonical URL |
| Three teralis selection/design/material posts | Useful seeds but overlapping buyer intent | merge | WLD-13-A03 and WLD-15-A02 | Keep a design gallery only when imagery is original/licensed and materially useful |
| Railing/tangga/kanopi inspiration posts | Thin listicles adjacent to service hubs | expand | WLD-13-A04, WLD-13-A05, WLD-13-A06 | Check whether each can support measurements, drawings, safety constraints, and original visuals |
| `/update/tips-memilih-bengkel-las-profesional-dan-berpengalaman/` | Commercial-support seed with generic claims | expand | WLD-15-A02 | Replace self-claims with auditable vendor-evaluation evidence |
| `/category/**`, `/blog/page/**` | Archive/pagination duplication | noindex | Navigation archives | Confirm canonical and whether archive search demand exists |
| `/sample-page/` | WordPress boilerplate | remove | none | Confirm no links or intentional content |
| `/wp-content/uploads/wpforms/cache/` and backup/plugin paths | Technical/internal paths appear in sitemap | remove | none | Security review, deployed accessibility, sitemap generator exclusions |
| Multiple sitemap families and `.html` versus extensionless URLs | Indexation split and duplicate discovery | canonicalize | One URL convention and one sitemap index | Live redirect matrix, canonical tags, internal links, GSC selected canonicals |

Primary risks are mass doorway-like geography, inconsistent URL variants, missing or looping service routes, technical/plugin paths in the sitemap, thin legacy articles, and safety advice published without qualified review. A large catalog must not be published automatically.

## Coverage matrix

| Completeness lens | Topic owner(s) | Coverage decision |
|---|---|---|
| Definition, vocabulary, history, process taxonomy | WLD-01 | Core beginner hub; distinguish joining, cutting, bending, brazing, and soldering |
| Anatomy, equipment, mechanisms, measurements | WLD-01, WLD-07, WLD-08 | Equipment diagrams and parameter tables without unsafe machine modification |
| Materials, metallurgy, consumables, corrosion | WLD-02, WLD-12 | Separate weldability from finish and service-environment durability |
| Need, survey, requirements, design, comparison | WLD-03, WLD-13, WLD-15 | Reader paths for engineers, workshop buyers, and homeowners |
| Budget, procurement, quotation, contract | WLD-15 | Explain cost components without inventing price lists |
| Preparation, fit-up, welding, handover | WLD-07, WLD-08, WLD-09, WLD-14 | Lifecycle sequence with hold points and records |
| Operation, inspection, maintenance, repair, replacement | WLD-09, WLD-16 | Symptoms link to inspection and repair-versus-replace decisions |
| Workshop versus field and new versus retrofit | WLD-10, WLD-13, WLD-16 | Occupied-site, lifting, access, fire-watch, and temporary-support constraints |
| Stakeholders and building types | WLD-10, WLD-13, WLD-15 | Home, commercial, industrial, structural, and decorative paths |
| Geography and climate | WLD-12, WLD-13 | Humidity, rain, coastal corrosion, drainage, and maintainability; no city swaps |
| Scale, quality level, manual versus automated | WLD-03, WLD-14, WLD-17 | Quality requirement follows risk and contract, not price labels |
| Electrical, arc, fire, hot-work, working-at-height safety | WLD-04 | Stop conditions and permit/competence gates |
| Fumes, gases, radiation, noise, ergonomics, PPE | WLD-05, WLD-06 | Controls hierarchy; PPE does not replace source control |
| Pressure cylinders and oxy-fuel | WLD-06 | Storage, handling, flashback, leak response, and qualified equipment care |
| Failure modes, defects, inspection, NDT | WLD-09, WLD-16 | Never infer structural fitness from appearance alone |
| Standards, regulation, qualifications, traceability | WLD-03, WLD-09, WLD-14 | Verify current project-applicable documents before exact clauses |
| Environmental impact and waste | WLD-12, WLD-17 | Coatings, consumables, scrap, energy, repairability, and ventilation tradeoffs |
| Fundamentals, how-to, comparison, diagnosis | WLD-01–WLD-17 | Every procedural brief includes prerequisite, stop condition, and verification |
| Calculation, checklist, visual reference, case study | WLD-03, WLD-07, WLD-09, WLD-15, WLD-17 | Calculators state assumptions; case studies require real documented evidence |
| Commercial support | WLD-13, WLD-15 | Educational buyer support links selectively to existing service pages |
| News and trends | WLD-17 | Only durable process or equipment changes worth maintaining |

## Topical map

| Topic ID | Parent topic | Reader outcome | Required subtopics/questions | Evidence/formats | Boundary | Article target |
|---|---|---|---|---|---|---:|
| WLD-01 | Welding fundamentals and process selection | Understand what welding does and choose a process family for a real fabrication constraint | Welding versus brazing/soldering; arc and heat source; SMAW, GMAW/MIG-MAG, GTAW/TIG, FCAW, SAW, resistance and oxy-fuel overview; polarity; current type; positions; joint vocabulary; process history; selection by material, thickness, access, productivity, and environment | Process decision tree, arc diagram, terminology table, qualified expert review | Does not prescribe qualified parameters or procedures; WLD-03 owns WPS and WLD-08 owns execution control | 6 |
| WLD-02 | Metals, weldability, filler, and metallurgy | Match base metal and consumable while recognizing heat-affected-zone and cracking risks | Carbon and low-alloy steel; stainless families; aluminium; cast iron; galvanized/coated metal; material identification; filler/electrode classification; shielding gases; hydrogen, hardening, sensitization, dilution, galvanic pairs; storage and traceability | Metallurgy diagrams, manufacturer data, consumable matrix, lab/expert review | Does not choose coating systems after fabrication; WLD-12 owns corrosion and finish | 6 |
| WLD-03 | Joint design, drawings, WPS, and qualification | Translate functional requirements into a controllable welded-joint specification | Joint types and symbols; load path; throat and effective length concepts; access; tolerances; WPS, PQR/WPQR and welder qualification; essential variables; mockups; design review; codes and contract hierarchy | Annotated drawings, responsibility matrix, primary standards, engineer and welding-coordinator review | No structural sizing or code approval for a live project; `/konstruksi-baja/` owns service conversion | 6 |
| WLD-04 | Arc, electrical, fire, and hot-work K3 | Recognize fatal hazards and establish safe authorization and stop conditions | Electric shock; arc radiation; burns; sparks and slag; combustible isolation; hot-work permits; fire watch; confined/occupied spaces; grounding/return path; wet conditions; equipment inspection; emergency response; work at height | Current Kemnaker sources, hazard-control checklist, permit workflow, K3 expert review | Not a substitute for site risk assessment, permit issuer, licensed electrical work, or emergency plan | 6 |
| WLD-05 | Welding fumes, ventilation, PPE, and occupational health | Apply the hierarchy of controls to fume, gas, noise, radiation, heat, and ergonomic exposure | Fume generation; material/coating contaminants; source capture and general ventilation; respirator program; face/eye protection; clothing; hearing; heat stress; ergonomics; exposure monitoring; symptoms and medical escalation | Permenaker 5/2018, SDS, exposure-control diagram, industrial hygienist review | Does not diagnose illness or prescribe PPE from an article alone; site assessment owns selection | 6 |
| WLD-06 | Gas cylinders, oxy-fuel, and compressed-gas safety | Store, move, connect, use, and isolate cylinders and oxy-fuel equipment without normalizing dangerous shortcuts | Identification; upright securing and segregation; valve/regulator compatibility; hoses; flashback arrestors; leak checks; lighting/shutdown; oxygen cleanliness; transport; fire exposure; empty cylinders; emergency isolation | Permenaker 37/2016, supplier manuals, cylinder layout, K3 specialist review | No cylinder repair, valve modification, refilling, or improvised fittings; authorized suppliers own those tasks | 6 |
| WLD-07 | Cutting, edge preparation, fit-up, and distortion planning | Prepare parts so the intended joint can be welded within tolerance | Saw, shear, plasma, laser, oxy-fuel and machining interfaces; bevels and root condition; cleaning; jigs and fixtures; gaps and alignment; tack welds; sequence; pre-set; shrinkage and distortion; measurement; hold points | Preparation diagrams, tolerance checklist, measurement plan, original workshop photos | Does not own machining/bending sales intent; `/bending/` and validated cutting/CNC routes own services | 6 |
| WLD-08 | Welding execution and parameter control | Understand how controlled variables produce repeatable welds and when work must stop | Travel speed, current/voltage, wire feed, arc length, heat input concept, preheat/interpass, shielding, electrode handling, starts/stops, cleaning, multi-pass sequence, positional limits, weather, welder technique, log records | WPS-linked parameter sheet, visual sequence, instrument checklist, qualified welder review | No universal settings table; qualified WPS and manufacturer data govern production | 6 |
| WLD-09 | Weld defects, inspection, NDT, and acceptance | Identify indications, choose inspection methods, and separate detection from acceptance | Discontinuity versus defect; cracks, porosity, lack of fusion/penetration, undercut, overlap, inclusions, burn-through, distortion; VT, PT, MT, UT, RT; timing; calibration; sampling; acceptance levels; reports; repair cycle | ISO 17635 and project standards, defect atlas, NDT decision matrix, certified inspector review | Images cannot certify fitness; acceptance belongs to the applicable code, contract, engineer, and qualified inspection personnel | 6 |
| WLD-10 | Structural steel fabrication and field erection | See the end-to-end controls needed for load-bearing welded steelwork | Shop drawings; material certificates; cutting/drilling; assembly; WPS; inspection points; bolted/welded interfaces; lifting; temporary stability; field welding; weather; fire protection interface; as-built handover | Process map, ITP example, engineer review, real documented case study only | Does not provide member sizing or approve structural modifications; `/konstruksi-baja/` owns commercial scope | 6 |
| WLD-11 | Sheet, plate, pipe, bending, and precision fabrication | Choose forming and cutting processes and specify tolerances for fabricated parts | Plate/sheet thickness; bend allowance and springback; tube/pipe ovality; section bending; kerf/HAZ; laser/plasma/oxy-fuel; CNC milling; holes and slots; datum and tolerance; nesting; fabrication sequence | Process comparison, tolerance drawing, bend/kerf calculator with assumptions, metrology checklist | Service quotes remain at `/bending/` and any restored CNC/cutting hub; WLD-07 owns weld-edge preparation | 6 |
| WLD-12 | Corrosion control, surface preparation, and finishing | Select a finish compatible with metal, exposure, fabrication, appearance, and maintenance | Rust mechanisms; coastal/humid exposure; design for drainage; blast/mechanical/chemical preparation; primers and topcoats; galvanizing; powder coating; stainless finishing/passivation; aluminium isolation; weld cleanup; DFT concept; repair and inspection | Exposure/finish decision table, coating manufacturer data, photos, field measurement, corrosion specialist review | Does not promise coating life or specify regulated chemicals without project data and SDS | 6 |
| WLD-13 | Residential and architectural fabricated products | Specify safe, maintainable gates, grilles, railings, stairs, canopies, doors, and furniture | Function; dimensions; guards and openings; access/egress; load and anchorage; drainage; sharp edges; child safety; corrosion; operation; maintainability; aesthetic pattern; site survey; handover | Product checklists, annotated details, original galleries, engineer review for safety-critical items | Product service pages own quote and portfolio intent; articles do not publish universal dimensions without verified applicable requirements | 6 |
| WLD-14 | Workshop quality system, traceability, and equipment care | Build repeatability from enquiry through records, calibration, maintenance, and handover | Contract review; responsibility; material and consumable control; WPS/welder records; traveler/ITP; nonconformance; calibration; machine, cable, torch, extraction and fixture maintenance; document retention; quality levels | ISO 3834 framework, workflow, sample forms, audit checklist, welding coordinator review | Does not claim certification or regulatory compliance from templates alone | 6 |
| WLD-15 | Survey, quotation, vendor selection, and contracting | Scope a job, compare offers fairly, and procure evidence rather than vague promises | Site measurements; use/load/environment; drawings; quantity; material grade; finish; access; exclusions; lead time; payment; warranty; inspection; qualifications; subcontracting; change control; acceptance and handover | Survey form, quote comparison matrix, BOQ anatomy, red-flag checklist | Does not publish invented prices or guarantee a vendor; commercial routes own requests for quotation | 6 |
| WLD-16 | Maintenance, troubleshooting, repair, and replacement | Diagnose visible symptoms cautiously and decide when to isolate, inspect, repair, reinforce, or replace | Rust, loose anchors, cracks, distortion, binding, coating failure, water traps, fatigue, impact, fire exposure; temporary controls; repair planning; crack removal; reinspection; retrofit; end of life | Symptom decision tree, stop-condition checklist, field photos, engineer/inspector review | No DIY repair of load-bearing, pressure, lifting, fire-damaged, or unknown-alloy components | 6 |
| WLD-17 | Automation, productivity, environment, and future practice | Evaluate improvements without sacrificing quality, safety, or maintainability | Positioners and mechanization; robotic/cobot welding; digital WPS/traceability; sensors; fixtures; nesting; rework metrics; energy and shielding-gas use; scrap; fume extraction; repairability; additive/hybrid processes; adoption economics | Process map, bounded ROI model, emissions/resource ledger, vendor-neutral comparison, documented pilot | Not product news or vendor promotion; no fabricated ROI or environmental claims | 6 |

Total planned articles: **102**.

## Related-domain opportunities

| Domain/topic context | Useful collaboration | Independence rule |
|---|---|---|
| Steel, wire, aluminium, glass, floors, façades, stairs, gates, and construction-service properties | Cross-reference material behavior, interfaces, anchorage, corrosion, maintenance, or project sequencing when a real editorial relationship exists | Each domain may publish its own full explanation; do not suppress a bengkel-las.co.id article because another domain targets a similar query |
| Cutting, machining, bending, and fabrication service properties | Share neutral terminology and measurement conventions, then link only if the destination helps the reader complete a task | Within bengkel-las.co.id, one article or service route must own each intent |
| Safety and fire properties | Offer deeper fire-prevention or emergency-system context | Welding hot-work articles retain welding-specific control and stop conditions |

No sitewide reciprocal network, hidden links, or fixed cross-domain footer links are proposed.

## Consolidation plan

1. Export GSC performance, backlinks, leads, and selected canonicals for all location, `.html`, extensionless, and legacy article URLs.
2. Choose one URL convention. Redirect every alternate variant in one hop, update canonical tags and internal links, and publish one canonical sitemap index.
3. Remove missing laser/CNC routes from sitemaps unless a real supported service page will be restored. Replace self-loop redirect rules only after the destination is known.
4. Keep geography pages only where unique local proof, service logistics, capacity, and reader value exist. Consolidate unsupported variants into a national service hub without mass one-to-one doorway recreation.
5. Reconcile the 12 update posts with catalog owners. Preserve useful URLs and history; merge overlapping coating and teralis posts after evidence review.
6. Noindex non-useful archive/pagination pages and remove sample, cache, backup, plugin, and technical upload paths from sitemaps.
7. Publish the first cluster before expanding later waves. Every safety or structural asset passes its evidence gate.

## Internal-link architecture

- `/blog/` becomes the editorial directory linking to all topic hubs rather than a paginated chronology alone.
- Each WLD topic has a hub that defines the reader journey and links to its six children; every child links back to its hub.
- Lifecycle path: WLD-01 and WLD-02 → WLD-03 and WLD-15 → WLD-07 and WLD-08 → WLD-09 and WLD-14 → WLD-16.
- Safety path: every procedural page links to WLD-04, WLD-05, or WLD-06 as applicable, with stop conditions placed in the body rather than hidden in a generic disclaimer.
- Product path: WLD-13 educational pages link to WLD-12 for durability, WLD-15 for procurement, and WLD-16 for maintenance. A link to a service route appears only after the reader's decision task is answered.
- Diagnostic path: WLD-09 defect pages link to prevention in WLD-07/WLD-08 and repair decisions in WLD-16.
- Structural path: WLD-10 links to WLD-03, WLD-09, and WLD-14; it never routes around engineering or inspection gates.
- Related links are chosen per article from the catalog. No article receives a copied generic block, and no planned page is orphaned.

## Evidence and editorial standards

- Classify every claim as stable explanation, manufacturer-specific data, project assumption, current regulation/standard, or field observation.
- Recheck JDIH, BSN/SNI, ISO, project specifications, and manufacturer documents on the publication date. State whether a source is law, standard, contract requirement, guidance, or editorial recommendation.
- Never invent a standard clause, acceptance criterion, filler compatibility, exposure limit, welding setting, price, qualification, test result, case study, or service location.
- Structural, pressure, lifting, gas, fire-damaged, and life-safety topics require named qualified review appropriate to the project.
- K3 procedure articles use the hierarchy of controls, prerequisites, authorization, stop conditions, emergency response, and verification. PPE is not treated as the only control.
- Welding settings must be tied to a qualified WPS or clearly labeled manufacturer/example data; generic parameter tables cannot authorize production welding.
- Defect imagery must be original, licensed, or sourced within its terms. A visual indication is not labeled acceptable or rejectable without the governing criteria.
- Calculators show formulas, units, input limits, assumptions, worked examples, and cases where engineering review is required.
- Commercial claims require traceable proof: material certificates, qualification scope, inspection records, equipment capability, warranty wording, or documented project evidence.
- AI may help structure drafts, but technical facts, route ownership, links, and same-domain overlap require human verification.

## First bounded publication cluster

Publish these 12 assets first:

1. WLD-01-A01 — Welding versus brazing and soldering.
2. WLD-01-A02 — Process-selection decision tree.
3. WLD-02-A01 — Identifying base metal before welding.
4. WLD-03-A03 — WPS, qualification record, and welder qualification.
5. WLD-04-A01 — Hot-work permit and fire watch.
6. WLD-04-A02 — Electric shock and safe welding return path.
7. WLD-05-A02 — Ventilation and local exhaust for welding fumes.
8. WLD-06-A01 — Cylinder storage and handling.
9. WLD-07-A02 — Fit-up and tack-weld inspection checklist.
10. WLD-09-A01 — Weld discontinuity and defect atlas.
11. WLD-13-A01 — Safe railing and guard specification.
12. WLD-15-A01 — Site-survey checklist for fabricated metalwork.

The cluster connects fundamentals, a buyer task, four high-risk controls, preparation, inspection, and one common safety-critical product. It can improve weak legacy content without requiring mass URL creation.

Monitor indexation and selected canonicals, impressions grouped by intent, task completion for checklists/decision tools, engaged navigation into related articles, qualified quote requests from relevant pages, and query/page pairs that indicate cannibalization. Review after enough impressions accumulate; do not judge success from rank alone.

## Definition of done

- One canonical sitemap index lists only live canonical URLs; `.html`/extensionless conflicts and self-loop redirects are resolved.
- Unsupported city variants, technical paths, archives, sample pages, and missing service routes have evidence-based keep/merge/redirect/noindex/remove decisions.
- All 17 hubs and 102 briefs have unique intent, title, slug, explicit boundary, valid related IDs, and no unresolved same-domain collision.
- Each applicable completeness lens and lifecycle stage has an owner.
- Every article links to its hub and at least one contextually useful next step; no planned page is orphaned.
- Safety, health, structural, gas-cylinder, inspection, and regulatory claims pass the stated qualified-review and primary-source gates.
- The first 12-asset cluster is published and measured before later waves are authorized.
- Commercial pages remain distinct from educational articles and use only substantiated capability, service-area, warranty, and project claims.
