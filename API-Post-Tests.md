# API Test Suite: JSONPlaceholder
Verified the "POST" functionality to ensure resources can be created correctly.

### Test Case: Create New Post
- **Endpoint:** `https://jsonplaceholder.typicode.com/posts`
- **Method:** `POST`
- **Request Body:**
  ```json
  { "title": "QA Test", "body": "Portfolio verification", "userId": 1 }

# Automated Validation
pm.test("Status code is 201", function () {
    pm.response.to.have.status(201);
});
