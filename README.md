# Unit Testing in Angular

## Introduction

#### Types of Mocks

- Dummies
- Stubs
- Spies
- True mocks

#### Types of Unit Tests in Angular

- Isolated
- Integration
    - Shallow
    - Deep
    
#### Tools

- Used
    - Karma
    - Jasmine
- Others
    - Jest
    - Mocha/Chai/etc
    - Sinon
    - TestDouble
    - Wallaby
    - Cypress
    - End to end tools

#### Writing Good Unit Tests

- Structuring Tests
    - __Arrange__ all necessary preconditions and inputs
    - __Act__ on the object or class under test
    - __Assert__ that the expected results have occurred
- DAMP vs DRY
    - DRY (do not repeat yourself1)
        - Remove duplications
    - DAMP
        - Repeat yourself if necessary
- Tell the Story
    - A test should be a complete story, all within the _it()_
    - You should not need to look around much to understand the test
    - Techniques
        - Move less interesting setup into _beforeEach()_
        - Keep critical setup within the _it()_
        - Include _Arrange_, _Act_ and _Assert_ inside _it()_
    

## Isolated Unit Tests
##### branch: _[isolated-unit-tests](https://github.com/pawtwa/angular-unit-testing/tree/isolated-unit-tests "Isolated Unit Tests")_

## Shallow Integration Tests
##### branch: _[shallow-integration-tests](https://github.com/pawtwa/angular-unit-testing/tree/shallow-integration-tests "Shallow Integration Tests")_

## Deep Integration Tests
##### branch: _[deep-integration-tests](https://github.com/pawtwa/angular-unit-testing/tree/deep-integration-tests "Deep Integration Tests")_

## Testing DOM Interaction and Routing Components
##### branch: _[testing-dom-interaction-and-routing-components](https://github.com/pawtwa/angular-unit-testing/tree/testing-dom-interaction-and-routing-components "Testing DOM Interaction and Routing Components")_

## Async Code Testing
##### branch: _[async-code-testing](https://github.com/pawtwa/angular-unit-testing/tree/async-code-testing "Async Code Testing")_

## Code Coverage
### branch: _[code-coverage](https://github.com/pawtwa/angular-unit-testing/tree/code-coverage "Code Coverage")_

## Summary

