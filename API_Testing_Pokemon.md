# API Testing Project: PokeAPI
This project demonstrates my ability to perform automated API testing and validation using Postman.

## Test Case 1: GET Pikachu Data
- **Endpoint:** `https://pokeapi.co/api/v2/pokemon/pikachu`
- **Method:** GET
- **Validation:** - Verified Status Code is 200 OK.
    - Verified "base_experience" is 112.

## Automated Scripts (Postman)
In the `Scripts > Post-response` tab, I implemented the following JavaScript assertion:
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
