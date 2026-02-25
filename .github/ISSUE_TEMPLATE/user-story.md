---
name: Final
about: Describe this issue template's purpose here.
title: ''
labels: ''
assignees: ''

---

As a catalog manager
I need the ability to create a product in the catalog
So that new items can be added with name, price, and description 
   
### Details and Assumptions
* [x] Product data includes: name (string), price (decimal), description (text)  
* [x] POST /products endpoint accepts JSON payload  
* [x] Returns 201 Created with product ID  
* [x] Validation: name required, price > 0  
* [ ] Authentication required for managers  
* [ ] Max description length: 500 chars  

### Acceptance Criteria
**Given** I am a catalog manager and the catalog is accessible  
**When** I send POST /products with valid data  
**Then** product created, 201 response with ID  
 ```
