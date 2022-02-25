{{ DOC }}
title: Project
type: NewsChannel
key: mainDocs
{{ /DOC }}

## Project 
 * Project beschreibung
 * Links/Filter auf boards/issues, ...

## Offene Todos (= Filter test)
{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: TeamFilterReference
    teamFilterKey: errorLabelFilter
{{ /MODULE }}


### TODO:
 * WikiLayout -> immer Liste der Children

### content
 
{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}
