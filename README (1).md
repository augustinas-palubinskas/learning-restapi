# OOP Practice Tasks

## 📋 Prerequisites

- Node.js (v18+)

- Vitest for test runner

- Axios library for doing API calls, just don't use 1.14.0 version as it is corrupted :D

- You could use Fake online Rest server (see Resourses section below). Or install json-server locally and it API will be accessible via http://localhost:3000 This local solution haven't tested, but it should work as both solution uses the same json-server dependency.

- The data that API returns are stored in the db.json file

---


## 📚 Tasks

You will build a **test automation framework** using OOP principles to test the JSON Server API.

## ✅ Test Implementation Tasks

### Task 1: Test User CRUD Operations

Create `tests/users.test.ts` with tests for:
- Get all users


---

### Task 2: Test Product Filtering

Create `tests/products.test.ts` with tests for:
- Get all products
- Filter by category
- Filter by price range
- Filter by stock status
- (Optional) Create, update, delete products

---

### Task 3: Test Orders with Nested Objects

Create `tests/orders.test.ts` with tests for:
- Get all orders
- Verify embedded user object in order
- Verify embedded product objects in order items
- Filter by order status
- Filter by user information
- (Optional) Create, update, delete orders

---

### Task 4: Test Reviews

Create `tests/reviews.test.ts` with tests for:
- Get all reviews
- Filter by rating
- Verify embedded user and product objects
- (Optional) Create, update, delete reviews

---

## 📖 Resources

- [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [Vitest Documentation](https://vitest.dev/)
- [Axios Documentation](https://axios-http.com/docs/intro)
- [Fake online REST server](https://my-json-server.typicode.com/)
- [JSON Server Documentation](https://github.com/typicode/json-server)

---

## 💡 Tips

- Start with the `ApiClient` and `BaseService` - they're the foundation
- Create interfaces before implementing services
- Write one test file at a time
- Use TypeScript generics in `BaseService<T>` to keep code DRY
- Leverage access modifiers (`private`, `protected`, `public`) appropriately
- Think about what should be hidden (encapsulated) vs exposed
- Also use any LLM for tips and tricks/research ect. :D 

---

