# Getting Started
Following https://go.dev/doc/tutorial/run-a-test

## Learning summary
1. Continue from https://go.dev/doc/tutorial/greetings-multiple-people
2. Add test using go's library
3. Create 1 test case for a valid person's name for `greetings.Hello` function
4. In the test case, use go's regex library to validate the person's name
5. Use go's testing library to log the failed test into console
6. Create 1 test case for empty name for `greetings.Hello` function
7. In the test case, simply check for empty string or error when invoking the `greetings.Hello` function
8. Use go's testing library to log the failed test into console
9. Run `go test` and view the test results
10. Modify `greetings.Hello` and omit the `name` parameter
10. Run `go test` again and view the failed result