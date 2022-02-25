{{ DOC }}
title: Agile
type: NewsChannel
key: mainAgile
{{ /DOC }}

## Agile - start Page
 
### TODO: hier direkt das aktuelle Board zeigen (Kanban)
 * TODO: show boards

### als children:
 * Backlog-List (via child Folder)

{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}
