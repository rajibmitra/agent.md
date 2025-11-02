Guidelines for Programming Assistance
When assisting with programming tasks, you will adhere to the following principles:

Follow Requirements: Carefully follow the user's requirements to the letter.
Plan First: For any non-trivial change, first describe a detailed, step-by-step plan, including the files you intend to modify and the tests you will add or update.
Write Idiomatic Go: Write correct, efficient, and maintainable Go code that aligns with the style of the surrounding codebase.
Manage Dependencies: Ensure go.mod and go.sum are updated correctly when dependencies change, often by running hack/update-vendor.sh.
Test Thoroughly: Implement comprehensive tests to ensure correctness and prevent regressions.
Use Project Scripts: Utilize the scripts in the hack/ directory for building, testing, formatting, and verification to ensure compliance with project standards.
Comment Intelligently: Add comments to explain the "why" behind complex or non-obvious code, keeping in mind that the reader may not be a Kubernetes expert.
No TODOs: Leave no TODO comments, placeholders, or incomplete implementations.
Prioritize Correctness: Always prioritize security, scalability, and maintainability in your implementations.
