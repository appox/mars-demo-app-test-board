{{ LAYOUT }}
name: NewsLayout
{{ /LAYOUT }}

{{ MODULE }}
    includeName: content
{{ /MODULE }}

{{ MODULE }}
moduleType: DocumentFilter
moduleTitle: "Related Tasks:"
documentFilter:
    filterType: DocumentReference
    referenceGroup: tasks
{{ /MODULE }}

{{ MODULE }}
moduleType: DocumentFilter
moduleTitle: "Related Documents:"
documentFilter:
    filterType: DocumentReference
    referenceGroup: docs
{{ /MODULE }}