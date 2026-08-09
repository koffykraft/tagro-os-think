# TAGRO OS Domain Model v0.1

Status: WORKING
Version: 0.1
Purpose: Shared model for AI, contracts, architecture and implementation across TAGRO OS domains.

## 1. Governing chain
REALITY → OBSERVATION → EVIDENCE → KNOWLEDGE → PLANES → DESIGN/DECISION → IMPLEMENTATION → OPERATION → NEW REALITY.

There is no final state. Flux is normal.

## 2. Root entities
### Mothership
The durable host: farm, business, branch, machine, project or other operational whole.

### Dock
A capability/domain attached to the mothership, e.g. irrigation, soil, crop, labour, machinery, finance, service, sales. Docks must be replaceable and must not duplicate mothership reality.

### Place
A spatial or logical place: farm, plot, block, room, field, route, basin, machine position, etc. A place may begin approximate and improve over time.

### Object
A persistent thing: plant, pump, pipe, valve, worker, machine, customer, building, well, road, account, product.

### Observation
What a person, device, map, photo, document or system reports.

### Evidence
The supporting source for an observation or assertion, with provenance and confidence.

### Fact / Knowledge Item
A currently accepted statement about reality. It is versioned and can be superseded.

### Event
Something that happened or changed. Events are the primary cause of state change.

### State
A derived current condition of an entity at a point in time.

### Relationship
A typed link between entities. No significant object is isolated.

### Plane
A context-specific interpretation of shared reality: water, crop, finance, labour, weather, irrigation, maintenance, etc.

### Decision
A chosen course based on available knowledge at a time.

### Design
A versioned arrangement of proposed or accepted components and relationships.

### Implementation
What has actually been installed, executed or committed in reality.

### Ripple
The set of dependent entities/states/calculations that must be reconsidered after an event.

### Shadow
Reusable institutional memory of a failure pattern, design defect or harmful assumption. Shadows are deduplicated by family; repeated evidence strengthens an existing shadow rather than spawning equivalents.

## 3. Provenance states
Every material assertion or design object should support one of:
OBSERVED · MEASURED · DESCRIBED · INFERRED · CONFIRMED · PROPOSED · ACCEPTED · INSTALLED · SUPERSEDED · RETIRED.

AI inference must never silently become CONFIRMED.

## 4. Stability / flux
The system may internally classify information as relatively stable, design-current, or flux-prone. Users need not see those labels. The purpose is to know what can remain valid when something else changes.

## 5. Dependency rule
A change recalculates the smallest affected scope first, then propagates only through declared relationships.

Example: emitter change → lateral demand → submain demand → main demand → operating group → pump/head check → materials/time.

Unrelated plots remain valid unless the relationship graph says otherwise.

## 6. Replaceability rule
Maps, tiles, UI components, colors, layout, database, AI provider, drawing engine, calculation engine, storage and integrations are adapters. Domain truth must not be trapped inside an adapter.

## 7. Shadow rule
Before creating a new shadow:
1. identify the event/failure pattern;
2. search existing shadow families;
3. attach evidence to an existing family when materially equivalent;
4. create a new shadow only when the failure mechanism is distinct;
5. record the prevention/test that should stop recurrence.

## 8. AI consumption rule
An AI working on a TAGRO build must:
1. read current doctrine/model/schema first;
2. distinguish source fact, inference and proposal;
3. declare affected relationships when changing a model or design;
4. preserve history rather than overwrite it invisibly;
5. consult shadows before repeating a pattern;
6. treat existing implementation as evidence, not authority.
