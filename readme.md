## Mermaid Practice ##

this markdown is practice
````mermaid
 
    
    
    erDiagram
          INSTALL }|..|{ SETTINGS : has
          SETTINGS ||--o{ CONNECTED : places
          CONNECTED ||--o{ INVOICE : "liable for"
          DELIVERY-ADDRESS ||--o{ ORDER : receives
          INVOICE ||--|{ ORDER : covers
          ORDER ||--|{ ORDER-ITEM : includes
          PRODUCT-CATEGORY ||--|{ PRODUCT : contains
          PRODUCT ||--o{ ORDER-ITEM : "ordered in"
  


