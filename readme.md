## Mermaid Practice ##

this markdown is practice
````mermaid
 
    
    
    erDiagram
          INSTALL }|..|{ SETTINGS : plugin
          SETTINGS ||--o{ CONNECTED : query
          CONNECTED ||--o{ WOOCOMERCE-SURVEY : "amd"
          WOOCOMERCE-SURVEY ||--o{ LAB-EURECAT : "Activate"
          WOOCOMERCE-SURVEY ||--|{ SAVE-DB : "true"
          WOOCOMERCE-SURVEY ||--|{ SETTINGS : "false"
          
          
          ORDER ||--|{ ORDER-ITEM : includes
          PRODUCT-CATEGORY ||--|{ PRODUCT : contains
          PRODUCT ||--o{ ORDER-ITEM : "ordered in"
  


