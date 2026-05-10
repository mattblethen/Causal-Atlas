---
type: actor_map
module: American Revolution
status: first_researched_pass
confidence: medium
sources:
  - Source - LOC Journals of the Continental Congress
  - Source - UK National Archives Boston Tea Party
  - Source - Avalon Boston Committee Circular Letter 1774
  - Source - Avalon Massachusetts Circular Letter 1768
  - Source - MHS Boston Pamphlet 1772
  - Source - Avalon Virginia Committee Resolutions 1773
  - Source - Founders Online Continental Association 1774
  - Source - Founders Online Braintree Association 1775
  - Source - NCpedia Committees of Safety Primary Source
  - Source - LOC True Sons Non-Importation Broadside
  - Source - Colonial Williamsburg Sons and Daughters of Liberty
  - Source - Commonwealth Museum Customs Commissioners and Liberty
  - Source - Commonwealth Museum Weight of Occupation
  - Source - LOC Revere Bloody Massacre Engraving
  - Source - MHS Adams Argument Wemms Trial
  - Source - MHS Wemms Trial Verdicts
  - Source - Rhode Island Historical Society Burning of the Gaspee
  - Source - NPS Washington Appointment Commander in Chief
  - Source - NPS Rebellion Minute Man
  - Source - LOC Philipsburg Proclamation
  - Source - LAC Book of Negroes 1783
  - Source - Avalon Townshend Revenue Act 1767
---

# American Revolution Actor Map

```mermaid
flowchart LR
    BE["British Empire"] --> BP["British Parliament"]
    BP --> SUG["Sugar Act"]
    BP --> SA["Stamp Act"]
    BP --> DA["Declaratory Act"]
    BP --> TRA["Townshend Revenue Act"]
    BP --> TA["Tea Act"]
    BP --> COA["Coercive Acts"]
    BP --> BCE["British Customs Enforcement"]
    TRA --> BCE
    BCE --> LIB["Liberty Affair"]
    LIB --> OCC["Boston Occupation"]
    BCE --> GAS["Gaspee Affair"]
    TA --> EIC["East India Company"]
    COA --> BOS["Boston / Massachusetts"]

    CAS["Colonial Assemblies"] --> CR["Colonial Resistance"]
    CAS --> SAC["Stamp Act Congress"]
    SAC --> NIA["Nonimportation Agreements"]
    CAS --> COC["Committees of Correspondence"]
    SOL["Sons of Liberty"] --> CR
    SOL --> NIA
    SOL --> COC
    DOL["Daughters of Liberty"] --> HOME["Homespun Movement"]
    DOL --> NIA
    JD["John Dickinson"] --> FARM["Letters from a Farmer in Pennsylvania"]
    FARM --> MCL["Massachusetts Circular Letter"]
    SA2["Samuel Adams"] --> MCL
    JO["James Otis Jr."] --> MCL
    MCL --> G92["Glorious 92"]
    G92 --> OCC
    SA2 --> COC
    JO --> COC
    TJ["Thomas Jefferson"] --> COC
    MCL --> CR
    NIA --> CR
    PM["Patriot Movement"] --> CR
    CR --> BTP["Boston Tea Party"]
    COC --> FCC
    CR --> FCC["First Continental Congress"]
    FCC --> CA["Continental Association"]
    CA --> COI["Committees of Inspection"]
    COI --> LAE["Local Association Enforcement"]
    LAE --> COS["Committees of Safety"]
    COI --> NIA
    COI -. pressures .-> LOY
    FCC --> SCC["Second Continental Congress"]
    SCC --> DOI["Declaration of Independence"]
    TP["Thomas Paine"] --> CS["Common Sense"]
    CS --> DOI
    G3["George III"] --> OBP["Olive Branch Petition Fails"]
    G3 --> REB["Rebellion Proclamation"]
    OBP --> DOI
    REB --> DOI
    TG["Thomas Gage"] --> LC["Lexington and Concord"]
    BA["British Army"] --> LC
    BA --> OCC
    OCC --> BM["Boston Massacre"]
    PR["Paul Revere"] --> BMA["Boston Massacre Aftermath"]
    JA["John Adams"] --> BMA
    JA --> BMT["Boston Massacre Trials"]
    BM --> BMA
    BMA --> BMT
    MM["Massachusetts Militia"] --> LC
    MPC["Massachusetts Provincial Congress"] --> MM
    LC --> CTA["Continental Army"]
    GW["George Washington"] --> CTA
    CTA --> BH["Battle of Bunker Hill"]
    EA["Ethan Allen"] --> TIC["Capture of Fort Ticonderoga"]
    BA2["Benedict Arnold"] --> TIC
    GMB["Green Mountain Boys"] --> TIC
    TIC --> HK["Henry Knox"]
    HK --> KNOX["Knox Expedition"]
    KNOX --> DH["Dorchester Heights"]
    CTA --> SB["Siege of Boston"]
    DH --> EB
    SB --> EB["Evacuation of Boston"]
    LC --> OBP
    LOY["Loyalists"] -. contests .-> PM
    LD["Lord Dunmore"] --> DUN["Dunmore's Proclamation"]
    DUN --> BL["Black Loyalists"]
    HC["Henry Clinton"] --> PHI["Philipsburg Proclamation"]
    PHI --> BL
    BL --> BLE["Black Loyalist Evacuation"]
    DUN --> DOI

    BP -. conflicts with .-> CAS
    BE -. claims authority over .-> CAS
    SOL -. pressures .-> EIC
```

## Reading the Map
- Parliament is the legal mechanism for imperial policy.
- The Townshend Revenue Act links Parliament directly to customs enforcement and colonial assembly resistance.
- The East India Company is a commercial actor whose crisis became political through the Tea Act.
- Colonial assemblies, resistance networks, and Congress represent escalating forms of colonial coordination.
- Nonimportation, homespun, and circular-letter politics show resistance infrastructure before the First Continental Congress.
- The occupation path shows British customs and army presence creating a military-public-opinion crisis in Boston.
- The John Adams path separates the courtroom defense and verdicts from the broader Patriot and Loyalist media battle.
- The committees path shows information networks becoming Association enforcement through local inspection committees.
- Local enforcement links boycott practice to committees of safety and militia-adjacent governance.
- Black Loyalists show enslaved people's freedom seeking inside British military strategy and Loyalist evacuation.
- The Patriot movement is an umbrella note, not a single institution.

## Sources
- [[Source - LOC Journals of the Continental Congress]]
- [[Source - UK National Archives Boston Tea Party]]
- [[Source - Avalon Boston Committee Circular Letter 1774]]
- [[Source - Avalon Massachusetts Circular Letter 1768]]
- [[Source - MHS Boston Pamphlet 1772]]
- [[Source - Avalon Virginia Committee Resolutions 1773]]
- [[Source - Founders Online Continental Association 1774]]
- [[Source - Founders Online Braintree Association 1775]]
- [[Source - NCpedia Committees of Safety Primary Source]]
- [[Source - LOC True Sons Non-Importation Broadside]]
- [[Source - Colonial Williamsburg Sons and Daughters of Liberty]]
- [[Source - Commonwealth Museum Customs Commissioners and Liberty]]
- [[Source - Commonwealth Museum Weight of Occupation]]
- [[Source - LOC Revere Bloody Massacre Engraving]]
- [[Source - MHS Adams Argument Wemms Trial]]
- [[Source - MHS Wemms Trial Verdicts]]
- [[Source - Rhode Island Historical Society Burning of the Gaspee]]
- [[Source - NPS Washington Appointment Commander in Chief]]
- [[Source - NPS Rebellion Minute Man]]
- [[Source - LOC Philipsburg Proclamation]]
- [[Source - LAC Book of Negroes 1783]]
- [[Source - Avalon Townshend Revenue Act 1767]]
