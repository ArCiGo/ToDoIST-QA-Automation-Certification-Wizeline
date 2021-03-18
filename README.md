# ToDoIST. QA Automation Certification Wizeline

Basic ToDoIST API Automation Framework

### Requests:

- Get active tasks
- Create a new task
- Get an active task
- Update a task
- Change a task status to 'complete'
- Reopen a task
- Delete a task

### Scenarios covered:

- [x] Status codes
- [x] Content
- [x] JSON schema
- [x] Response time

**Note:** Not all requests returns content or JSON schema

### How to run the project

```console
/* Runs the positive scenarios */
npm run test-API
```

```console
/* Runs the negative scenarios */
npm run test-API-neg
```

**Note:** Don't forget to install the node packages (``npm i``)