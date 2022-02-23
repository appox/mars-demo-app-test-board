{{ DOC }}
title: Static content test 1
type: NewsChannel
key: root
variation: ContentProject                
{{ /DOC }}

## Board - start Page
 * nach den changes

{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}

{{ MODULE }}
  moduleType: KeyValueStore
  moduleTitle: Data
  data:
    storeKey: versionInfo
    map:
      foo: bar
{{ /MODULE }}