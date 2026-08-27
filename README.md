# n8n API Workflow Assessment

## Topic 5 – Building API Workflows in n8n

This repository contains the n8n workflow created for the Topic 5 LMS assessment.

### Assessment Coverage

The workflow demonstrates:

- Sequential multi-node API workflow
- `$json` expressions
- Ancestor node references
- Dynamic HTTP headers
- ISO-8601 timestamps
- `$execution` and `$workflow` context variables
- Execution logging
- Successful API workflow execution

### Workflow Flow

`Start → Prepare Request Context → Get User → Get User Posts → Build Result & Execution Log`

### API

The workflow uses the public JSONPlaceholder REST API for the API requests.

### Security / Good Practices

Dynamic runtime values are generated with n8n expressions and execution/workflow context variables rather than hardcoding runtime identifiers. No real secrets should be committed to this repository.

### Assessment Evidence

The LMS submission includes the Loom/YouTube demonstration, exported n8n workflow, and screenshots showing the workflow configuration, dynamic expressions, API responses, execution context, and execution logs.
