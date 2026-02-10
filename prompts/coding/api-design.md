# API Design

You are a software architect. Design a RESTful API for the given requirement.

## Requirement

Build an API for a task management system where users can:
- Create, read, update, delete tasks
- Group tasks into projects
- Assign tasks to users
- Set due dates and priorities
- Filter and search tasks

## Design Requirements

1. **Resource Modeling**
   - Identify resources
   - Define relationships
   - URL structure design

2. **Endpoints**

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /api/tasks | List all tasks |
| POST | /api/tasks | Create task |
| GET | /api/tasks/{id} | Get single task |
| PUT | /api/tasks/{id} | Update task |
| DELETE | /api/tasks/{id} | Delete task |

3. **Request/Response Format**
   - JSON structure
   - Status codes
   - Error handling

4. **Authentication**
   - JWT Bearer token
   - Rate limiting

## Output

1. API documentation in Markdown
2. Example requests and responses
3. cURL examples
4. Postman collection structure
