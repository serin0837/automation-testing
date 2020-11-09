unit
intergration
end-to-end(E2E)
what is Automated Testing?

https://www.youtube.com/watch?v=Nd31XiSGJLw

recommendation

70 % unit
20% integration
10 % end- to -end

https://www.testingxperts.com/blog/test-automation-guide

cypress - software
automation automation

# Testing pyramid

Static Code Analysis

unit tests- fast feedbadk, fast to run, small, isolated
intergration tests? blurry boundry
E2E- slower to run / Test what the use DOES

how do we structure unit tests?

    1. AAA(Arrange Act Assert)

    2. Given, When, Then
    Given some system state, When I do something, Then the system should...

## Cypress

`npx cypress open`
in browser we can do test!

1. visit duckduckgo.com
2. Type anything
3. press enter

`cy.visit("url")`
find the search bar
cy.get() //exactly same syntax as query selector
id could be change so write input separately?
but for now just stick with id

query selector and getElementbyId again study

cy.get().type(+{enter})

what will user do ?end-to -end

add word show actually
social media

check automated testing!!!! with ned
