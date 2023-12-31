# COMDEX hackathon 2023

![logo](./resources/logo.jpg)

> **Boost blockchain economy to the new level by eliminating user fragmentation, enhancing liquidity, and unifying markets across the entire web3!**

* [easypay.network](https://easypay.network) - a web-site/dapp that clearly shows how you can work with EasyPay Network.
* [github.com/easypay-network](https://github.com/easypay-network) - github project repository, which contains all the developments of this project during **Hackathon 2023**.
<blockquote style="font-style: italic;"> We want to emphasize that the code developed for the hackathon was a rapid prototype, created with a focus on showcasing the concept. While it effectively served its purpose for the hackathon, it should be noted that it is not intended for production use. It was a quick and functional demonstration of our ideas, and as we move forward, we will build a production-ready solution from the ground up.
</blockquote>

## Content
* [Content](#Content)
* [Interface](#Interface)
* [Architecture](#Architecture)
* [Database](#Database)
* [Protocol](#Protocol)
* [Repositories](#Repositories)

## Interface

### Catalog
CATEGORIES                          |  ITEMS MINI                         |  ITEMS DETAILED                     |
:----------------------------------:|:-----------------------------------:|:-----------------------------------:|
![](./resources/screenshots/1.png)  |  ![](./resources/screenshots/2.png) | ![](./resources/screenshots/10.png) |
|                                   |  ![](./resources/screenshots/3.png) | ![](./resources/screenshots/11.png) |

### Login
NO ONE                              |  ALL                                |
:----------------------------------:|:-----------------------------------:|
![](./resources/screenshots/4.png)  |  ![](./resources/screenshots/5.png) |

### Swap
INITIAL PAGE                        |  PATH EXAMPLE                        | APPROVE                            |
:----------------------------------:|:------------------------------------:|:----------------------------------:|
![](./resources/screenshots/7.png)  |  ![](./resources/screenshots/6.png)  | ![](./resources/screenshots/8.png) |
|                                   |                                      | ![](./resources/screenshots/9.png) |

### BY SERVICE CODE & REFERENCE NUMBER
SEARCH OPTIONS                      |  FINDED ITEM                         |
:----------------------------------:|:------------------------------------:|
![](./resources/screenshots/12.png) |  ![](./resources/screenshots/13.png) |



### REPORTS
TYPES                                |  TIMELINE                            | STUB                                |
:-----------------------------------:|:------------------------------------:|:-----------------------------------:|
![](./resources/screenshots/14.png)  |  ![](./resources/screenshots/15.png) | ![](./resources/screenshots/16.png) |


### INVOICES
CONSTRUCTOR                          |  LIST                                | DETAILS                             | PAYMENT                             |
:-----------------------------------:|:------------------------------------:|:-----------------------------------:|:-----------------------------------:|
![](./resources/screenshots/17.png)  |  ![](./resources/screenshots/18.png) | ![](./resources/screenshots/19.png) | ![](./resources/screenshots/20.png) |

### INVOICE PAYMENT
REQUIREMENTS                          |  PROCESSING MODAL                    | SUCCESS MODAL                       | PAYMENT                             | EXPLORER                            |
:-----------------------------------:|:------------------------------------:|:-----------------------------------:|:-----------------------------------:|:-----------------------------------:|
![](./resources/screenshots/20.png)  |  ![](./resources/screenshots/21.png) | ![](./resources/screenshots/22.png) | ![](./resources/screenshots/23.png) | ![](./resources/screenshots/24.png) |





## Architecture

![logo](./resources/architecture.jpg)

## Database

> **Graph database Neo4j with pathfinding algorithm**

![logo](./resources/database.png)

## Protocol

## Repositories

* [easypay-network/COMDEX-2023](https://github.com/easypay-network/COMDEX-2023) - EasyPay Network project root documentation repository
* [easypay-network/hackathon-frontend](https://github.com/easypay-network/hackathon-frontend) - dApp for interacting with our EasyPay Network Payment System.
* [easypay-network/hackathon-server](https://github.com/easypay-network/hackathon-server) - server-side component that connects the graph database and the pathfinder with the frontend client. This component handles the core business logic, ensuring that transactions are executed seamlessly and securely.
* [easypay-network/hackathon-database](https://github.com/easypay-network/hackathon-database) - cypher scripts for neo4j database
