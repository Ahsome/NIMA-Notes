*Created on <% tp.date.now(format = "Do MMM YYYY") %>*

---
```toc
```
---

# Information
<%* 
let title = tp.file.title 
if (title.startsWith("Untitled")) { 
title = await tp.system.prompt("Title"); 
} await tp.file.rename(title) -%> 
<% title %> is a...

## Pathophysiology

> [!Important]
- Important point

# History
## Signs
### *Symptoms*

### *Risk factors* 

### *Questions to ask*

## Examination findings
| Key Findings | Result   | Explanation |
| ------------ | -------- | ----------- |
| Test 1       | Result 1 | Exp. 1      | 


| Additional Findings | Result   | Explanation |
| ------------------- | -------- | ----------- |
| Test 1              | Result 1 | Exp. 1            |



## Investigations
| Key Tests | Result |
| --------- | ------ |
| Test 1    | Result       |

| Additional Tests | Result |
| ---------------- | ------ |
| Test 1           | Result       |

---

# Management
## Treatments
### *Acute treatment*

### *Long term*

---

# Complications

---

# Extra
## References:
1. 