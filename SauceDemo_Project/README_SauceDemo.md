# SauceDemo Manual Testing Project

Manual testing of the e-commerce demo site https://www.saucedemo.com: test planning, test cases, requirement traceability and defect reporting.

## Project Summary
| Item | Detail |
|---|---|
| Application | https://www.saucedemo.com/ |
| Test cases | 29 |
| Requirements covered | 13 (100% mapped in RTM) |
| Bugs reported | 6 |
| Modules | Login, Inventory, Product Detail, Cart, Checkout, Navigation |
| Tester | Aditya Parkar |

## Repository Structure
```
SauceDemo_Project/
├── README.md
├── Test_Plan.docx
├── SauceDemo_Manual_Test_Artifacts.xlsx   (Summary, Test Cases, RTM, Bug Reports)
└── screenshots/                    (evidence for each bug, e.g. BUG-001.png)
```

## Artifacts
- [Test Plan](SauceDemo_Test_Plan.docx)
- [Test Cases, RTM and Bug Reports (Excel)](SauceDemo_Manual_Test_Artifacts.xlsx)

## Defect Summary
| ID | Title | Severity |
|---|---|---|
| BUG-001 | performance_glitch_user: login takes noticeably long | Major |
| BUG-002 | problem_user: all products show the same image | Minor |
| BUG-003 | problem_user: sort dropdown does not re-order products | Major |
| BUG-004 | problem_user: Add to cart / Remove fails for some products | Major |
| BUG-005 | Order can be completed with an empty cart | Major |
| BUG-006 | problem_user: Last Name input fills the First Name field | Critical |

## Tools
Google Chrome, Microsoft Excel, GitHub
