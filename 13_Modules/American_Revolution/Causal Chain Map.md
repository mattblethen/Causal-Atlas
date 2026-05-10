---
type: causal_map
module: American Revolution
status: researching
---

# American Revolution Causal Chain Map

```mermaid
flowchart TD
    A["Seven Years' War"] --> B["British Imperial Debt"]
    A --> C["Royal Proclamation of 1763"]
    B --> D["Sugar Act"]
    D --> E["Stamp Act"]
    E --> EA["Stamp Act Congress"]
    EA --> EB["Nonimportation Agreements"]
    E --> F["Declaratory Act"]
    E --> G["Quartering Act"]
    EB --> F
    F --> H["Townshend Acts"]
    G --> H
    H --> HAA["Townshend Revenue Act"]
    HAA --> HA["Letters from a Farmer in Pennsylvania"]
    HA --> HB["Massachusetts Circular Letter"]
    HB --> HBA["Glorious 92"]
    HAA --> HBB["Liberty Affair"]
    HBA --> HBC["Boston Occupation"]
    HBB --> HBC
    HAA --> HC["Boston Non-Importation Agreement"]
    HB --> HC
    HC --> HD["Homespun Movement"]
    HBC --> HBD["Christopher Seider Killing"]
    HBD --> I["Boston Massacre"]
    HBC --> I
    HD --> HBD
    I --> IAA["Boston Massacre Aftermath"]
    IAA --> IAB["Boston Massacre Trials"]
    IAB --> J["Gaspee Affair"]
    J --> JA["Committees of Correspondence"]
    JA --> K["Colonial Resistance"]
    K --> L["Tea Act"]
    L --> M["Boston Tea Party"]
    M --> N["Coercive Acts"]
    N --> O["First Continental Congress"]
    JA --> O
    O --> P["Continental Association"]
    P --> PA["Committees of Inspection"]
    PA --> PB["Local Association Enforcement"]
    PB --> Q["Lexington and Concord"]
    P --> Q
    Q --> AD["Second Continental Congress"]
    Q --> AE["Capture of Fort Ticonderoga"]
    AE --> AF["Knox Expedition"]
    Q --> R["Battle of Bunker Hill"]
    AD --> RAA["Declaration of the Causes and Necessity of Taking Up Arms"]
    R --> RAA
    R --> S["Olive Branch Petition"]
    RAA --> T["Proclamation for Suppressing Rebellion and Sedition"]
    S --> T["Proclamation for Suppressing Rebellion and Sedition"]
    T --> U["Lord Dunmore's Proclamation"]
    RAA --> V["Common Sense"]
    U --> V["Common Sense"]
    U --> UAA["Philipsburg Proclamation"]
    UAA --> UAB["Black Loyalist Evacuation"]
    Q --> W["Siege of Boston"]
    AF --> AG["Dorchester Heights"]
    W --> AG
    AG --> X["Evacuation of Boston"]
    V --> Y["Declaration of Independence"]
    X --> Y
    UAB -. exposes .-> Y

    B -. manifests .-> Z["Imperial Debt"]
    F -. asserts .-> AA["Parliamentary Sovereignty"]
    K -. defends .-> AB["Colonial Autonomy"]
    L -. channels .-> AC["Mercantilism / Atlantic Trade"]
    HA -. circulates .-> AH["Mass Media"]
    AH -. amplifies .-> V
    HD -. politicizes .-> AI["Household Labor / Consumption"]
    JA -. coordinates .-> AH
    PA -. enforces .-> AB
    PB -. localizes .-> AB
```

## Map Notes
- This is now a first-pass researched scaffold, not a final causal proof.
- Strongest supported links so far: Seven Years' War -> British Imperial Debt -> Sugar Act/Stamp Act; Stamp Act -> Stamp Act Congress/nonimportation; Stamp Act -> Declaratory Act -> Townshend Acts/Townshend Revenue Act as a sovereignty and revenue sequence; Townshend Revenue Act -> Farmer letters/Circular Letter/nonimportation/customs conflict; Circular Letter/Liberty Affair -> occupation; occupation -> Boston Massacre -> aftermath/trials; Gaspee/committee networks -> First Continental Congress; Tea Act -> Boston Tea Party -> Coercive Acts; Coercive Acts -> First Continental Congress -> Continental Association -> local enforcement; Lexington/Bunker Hill -> July 1775 petition and war-justification documents -> rebellion proclamation; failed reconciliation and print circulation -> Common Sense -> Declaration; Dunmore/Philipsburg freedom policies -> Black Loyalist evacuation.
- Lexington and Concord remains source-backed as the transition into armed conflict, but the exact first-shot question is intentionally left unresolved.
- Future passes should qualify direct, indirect, and disputed relationships with more specific primary sources.
