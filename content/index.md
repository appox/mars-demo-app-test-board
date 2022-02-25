{{ DOC }}
title: Static content test 1
type: NewsChannel
key: root
variation: ContentProject                
{{ /DOC }}

## DevProject
 
 * Startseite, die so nicht mehr sichtar sein sollte. (Navbar)

{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}

## Version Info

{{ MODULE }}
  moduleType: KeyValueStore
  moduleTitle: Data
  data:
    storeKey: versionInfo
    map:
      foo: bar
{{ /MODULE }}