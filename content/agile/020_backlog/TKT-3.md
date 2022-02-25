{{ DOC }}
title: "backlog issue"
key: TKT-3
keyName: TKT-3
ticketStatusKey: wip
type: Card
labels:   
  - error
references:
    - 
      documentKey: TKT-2     
      group: related   
authorsKeys:
- "dev1"         
{{ /DOC }}

{{ USE_LAYOUT }}
  name: IssueLayout
{{ /USE_LAYOUT }}

{{ LAYOUT_CONTENT name="content" }}

{{ MODULE }}
  moduleType: DocContent  
  moduleKey: labels    
  docContent:
    docContentType: LabelPublic
{{ /MODULE }}

{{ MODULE }}
  moduleType: Text
  moduleKey: description
  text:
    type: Markdown
  {{ TEXT }}
Ticket *description*.
This is a test.
  {{ /TEXT }}
{{ /MODULE }}

{{ MODULE }}
  moduleType: ImageList  
  moduleKey: assets
  imageList:
    images:
        - image:
            asset: team/backgroundImage.jpg
{{ /MODULE }}

{{ MODULE }}
  moduleType: ListSelection  
  moduleKey: selections
  listSelection:
    items:
        - 
            text: "do some stuff."
            selected: true   
        - 
            text: "other stuff"
            selected: false               
{{ /MODULE }}

{{ MODULE }}
  moduleType: DocContent  
  moduleKey: related    
  docContent:
    docContentType: DocumentReference
{{ /MODULE }}

{{ /LAYOUT_CONTENT }} 

