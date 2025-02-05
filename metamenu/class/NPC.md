---
fields:
  - name: Status
    type: Select
    options:
      sourceType: ValuesList
      valuesList:
        "1": Alive
        "2": Unknown
        "3": Dead
    path: ""
    id: 2vfDe7
  - name: Campaign
    type: Select
    options:
      sourceType: ValuesListNotePath
      valuesList: {}
      valuesListNotePath: metamenu/class sources/Campaign List.md
    path: ""
    id: Hhqr3p
  - name: Organization
    type: MultiFile
    options: {}
    path: ""
    id: LWU4Lr
version: "2.45"
limit: 20
mapWithTag: false
icon: user-circle
tagNames: 
filesPaths: 
bookmarksGroups: 
excludes: 
extends: 
savedViews:
  - name: DanseMacabreAlive
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Danse Macabre
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: DanseMacabreAliveOrgs
    children: []
    sorters:
      - id: NPC____Organization
        name: Organization
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Danse Macabre
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: __notEmpty__
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: DanseMacabreDead
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
      - id: NPC____Campaign
        name: Campaign
        query: Danse Macabre
      - id: NPC____Status
        name: Status
        query: Dead
      - id: NPC____Organization
        name: Organization
        query: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: GatewalkersAlive
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Gatewalkers
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: GatewalkersAliveOrgs
    children: []
    sorters:
      - id: NPC____Organization
        name: Organization
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Gatewalkers
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: __notEmpty__
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: GatewalkersDead
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Gatewalkers
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Dead
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: NuclearChromeAlive
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Nuclear Chrome
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: NuclearChromeAliveOrgs
    children: []
    sorters:
      - id: NPC____Organization
        name: Organization
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Nuclear Chrome
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: __notEmpty__
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: NuclearChromeDead
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Nuclear Chrome
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Dead
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: SealOfInfinityAliveOrgs
    children: []
    sorters:
      - id: NPC____Organization
        name: Organization
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Seal of Infinity
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: __notEmpty__
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: SealOfInfinityDead
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Seal of Infinity
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Dead
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: SealofInfinityAlive
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Seal of Infinity
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: StepstoneIslesAlive
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Stepstone Isles
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: StepstoneIslesAliveOrgs
    children: []
    sorters:
      - id: NPC____Organization
        name: Organization
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Stepstone Isles
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: __notEmpty__
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: StepstoneIslesDead
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Stepstone Isles
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Dead
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: StrahdAlive
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Strahd Has Risen from the Grave
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: StrahdAliveOrgs
    children: []
    sorters:
      - id: NPC____Organization
        name: Organization
        direction: asc
        priority: 1
        customOrder: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Strahd Has Risen from the Grave
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Alive, Unknown
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: __notEmpty__
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
  - name: StrahdDead
    children: []
    sorters: []
    filters:
      - id: NPC____file
        name: file
        query: ""
        customFilter: ""
      - id: NPC____Campaign
        name: Campaign
        query: Strahd Has Risen from the Grave
        customFilter: ""
      - id: NPC____Status
        name: Status
        query: Dead
        customFilter: ""
      - id: NPC____Organization
        name: Organization
        query: ""
        customFilter: ""
    columns:
      - id: NPC____file
        name: file
        hidden: false
        position: 0
      - id: NPC____Campaign
        name: Campaign
        hidden: true
        position: 1
      - id: NPC____Status
        name: Status
        hidden: true
        position: 2
      - id: NPC____Organization
        name: Organization
        hidden: false
        position: 3
favoriteView: 
fieldsOrder:
  - Hhqr3p
  - 2vfDe7
  - LWU4Lr
---
