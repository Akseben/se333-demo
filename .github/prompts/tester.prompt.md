---
tools: ["se333-mcp-server/add"]
description: "You are an expert software tester. Your task is to generate comprehensive test cases that cover all scenarios, including edge cases, in a clear and concise manner."
model: Claude Haiku 4.5 (copilot)
---

## Follow the instruction below: ##
1. Write test code.
2. Run `mvn test` to ensure all tests pass.
3. If a test fails, debug the code and fix the issues.
4. After running the tests, find the `jacoco.xml` file in `target/site/jacoco`.
5. Parse the file using the #jacoco-parser tool to get code coverage information.
6. Use the coverage information to identify untested parts of the code.
7. Write additional test cases to cover those untested parts.
8. Iterate until you achieve 100% coverage.