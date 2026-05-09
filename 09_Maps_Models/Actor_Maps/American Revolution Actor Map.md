---
type: actor_map
module: American Revolution
status: first_researched_pass
confidence: medium
sources:
  - Source - LOC Journals of the Continental Congress
  - Source - UK National Archives Boston Tea Party
  - Source - Avalon Boston Committee Circular Letter 1774
  - Source - Rhode Island Historical Society Burning of the Gaspee
  - Source - NPS Washington Appointment Commander in Chief
  - Source - NPS Rebellion Minute Man
---

# American Revolution Actor Map

```mermaid
flowchart LR
    BE["British Empire"] --> BP["British Parliament"]
    BP --> SUG["Sugar Act"]
    BP --> SA["Stamp Act"]
    BP --> DA["Declaratory Act"]
    BP --> TA["Tea Act"]
    BP --> COA["Coercive Acts"]
    BP --> BCE["British Customs Enforcement"]
    BCE --> GAS["Gaspee Affair"]
    TA --> EIC["East India Company"]
    COA --> BOS["Boston / Massachusetts"]

    CAS["Colonial Assemblies"] --> CR["Colonial Resistance"]
    SOL["Sons of Liberty"] --> CR
    PM["Patriot Movement"] --> CR
    CR --> BTP["Boston Tea Party"]
    CR --> FCC["First Continental Congress"]
    FCC --> DOI["Declaration of Independence"]
    TP["Thomas Paine"] --> CS["Common Sense"]
    CS --> DOI
    G3["George III"] --> OBP["Olive Branch Petition Fails"]
    G3 --> REB["Rebellion Proclamation"]
    OBP --> DOI
    REB --> DOI
    TG["Thomas Gage"] --> LC["Lexington and Concord"]
    BA["British Army"] --> LC
    MM["Massachusetts Militia"] --> LC
    MPC["Massachusetts Provincial Congress"] --> MM
    LC --> CTA["Continental Army"]
    GW["George Washington"] --> CTA
    CTA --> BH["Battle of Bunker Hill"]
    CTA --> SB["Siege of Boston"]
    SB --> EB["Evacuation of Boston"]
    LC --> OBP
    LOY["Loyalists"] -. contests .-> PM
    LD["Lord Dunmore"] --> DUN["Dunmore's Proclamation"]
    DUN --> BL["Black Loyalists"]
    DUN --> DOI

    BP -. conflicts with .-> CAS
    BE -. claims authority over .-> CAS
    SOL -. pressures .-> EIC
```

## Reading the Map
- Parliament is the legal mechanism for imperial policy.
- The East India Company is a commercial actor whose crisis became political through the Tea Act.
- Colonial assemblies, resistance networks, and Congress represent escalating forms of colonial coordination.
- The Patriot movement is an umbrella note, not a single institution.

## Sources
- [[Source - LOC Journals of the Continental Congress]]
- [[Source - UK National Archives Boston Tea Party]]
- [[Source - Avalon Boston Committee Circular Letter 1774]]
- [[Source - Rhode Island Historical Society Burning of the Gaspee]]
- [[Source - NPS Washington Appointment Commander in Chief]]
- [[Source - NPS Rebellion Minute Man]]
