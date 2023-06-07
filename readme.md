## Mermaid Practice ##

this markdown is practice
````mermaid
 
    
    
    erDiagram
          INSTALL }|..|{ SETTINGS : plugin
          SETTINGS ||--o{ CONNECTED : query
          CONNECTED ||--o{ WOOCOMERCE-SURVEY : "amd"
          WOOCOMERCE-SURVEY ||--o{ LAB-EURECAT : "out of moodle"
          LAB-EURECAT ||--|{ WOOCOMERCE-SURVEY : "save DB"
          WOOCOMERCE-SURVEY ||--|{ SETTINGS : "In case false"
          WOOCOMERCE-SURVEY ||--|{ SAVE-DB : "true"
          ORDER ||--|{ ORDER-ITEM : includes
          PRODUCT-CATEGORY ||--|{ PRODUCT : contains
          PRODUCT ||--o{ ORDER-ITEM : "ordered in"
  


