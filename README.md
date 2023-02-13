
# Technical test for Ultra with Postman

This repository includes the UI test automation ofhttps://gorest.co.in/ using Postman + Javascript.






## Installation

Prerequisites
```bash
  Postman
  nodejs
```
---
    
## Run Locally

Clone the project

```bash
  git clone https://github.com/kevoshos/ultraPostman.git
```

---
### Execution

#### Prerequisites
Import json collection into Postman


#### Test run

Set your own access token if the one in the collection does not work: https://gorest.co.in/my-account/access-tokens
And get the collection run via the Collection runner, run the endpoint iteratively so you can review the checks per every data driven scenario.



## Suggestions

1. My main suggestion is to use the POISED heuristic this will allow us to have a clear test coverage. POISED stands for Parameters, Output, Interop, Security, Errors, and Data. We should have test on each of these areas to get a reliable api suite.


