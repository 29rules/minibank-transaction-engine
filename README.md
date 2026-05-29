# MiniBank Transaction Engine

A backend banking simulation built with Java and Spring Boot, modelling core transaction logic used in real financial systems.

## Features
- Account creation and management
- - Fund transfers with balance validation
  - - Transaction history and audit trail
    - - Overdraft protection and error handling
      - - RESTful API endpoints following banking domain patterns
       
        - ## Tech Stack
        - - **Language:** Java 17
          - - **Framework:** Spring Boot
            - - **Database:** MySQL / H2 (in-memory for dev)
              - - **Build tool:** Maven
                - - **API:** REST
                 
                  - ## Getting Started
                  - ```bash
                    git clone https://github.com/29rules/minibank-transaction-engine
                    cd minibank-transaction-engine
                    mvn spring-boot:run
                    ```

                    ## API Endpoints
                    | Method | Endpoint | Description |
                    |--------|----------|-------------|
                    | POST | /accounts | Create account |
                    | GET | /accounts/{id} | Get account details |
                    | POST | /transfers | Transfer funds |
                    | GET | /transactions/{accountId} | Get transaction history |

                    ## Why I built this
                    To apply Java + Spring Boot skills in a domain I know deeply from 5+ years at Scotiabank — financial transaction systems, validation rules, and audit logging.
