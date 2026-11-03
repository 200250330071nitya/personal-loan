# personal-loan-platform

Structure:-
loan-service/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/bank/loanservice/
│   │   │
│   │   │   ├── LoanServiceApplication.java
│   │   │
│   │   │   ├── controller/
│   │   │   │   └── LoanController.java
│   │   │
│   │   │   ├── service/
│   │   │   │   └── LoanApplicationService.java
│   │   │
│   │   │   ├── repository/
│   │   │   │   └── LoanRepository.java
│   │   │
│   │   │   ├── entity/
│   │   │   │   └── LoanApplication.java
│   │   │
│   │   │   ├── dto/
│   │   │   │   ├── LoanRequest.java
│   │   │   │   └── LoanResponse.java
│   │   │
│   │   │   ├── client/
│   │   │   │   ├── CustomerClient.java
│   │   │   │   ├── DocumentClient.java
│   │   │   │   └── NotificationClient.java
│   │   │
│   │   │   ├── exception/
│   │   │   │   └── LoanNotFoundException.java
│   │   │
│   │   │   └── config/
│   │   │       └── RestTemplateConfig.java
│   │
│   │   └── resources/
│   │       └── application.yml
│
│   └── test/
│       └── java/
│           └── LoanControllerTest.java
│
├── Dockerfile
├── Jenkinsfile
├── .dockerignore
├── .gitignore
├── pom.xml
└── README.md
