# API Testing Project with Postman - Reqres API

This is a simple API Testing project built using [Postman](https://www.postman.com/) and the public [Reqres](https://reqres.in/) API.  
It is designed to showcase manual API testing skills, test documentation, and automation-ready collection design.

## 🔧 Tools Used

- Postman (for API requests and test scripts)
- Reqres API (as a dummy REST API)
- Excel (for manual test cases)
- GitHub (for version control and sharing work)

## 📁 Project Structure

| File | Description |
|------|-------------|
| `API_Test_Cases.xlsx` | Manual test cases for each endpoint (positive + negative) |
| `Reqres_Postman_Collection.json` | Postman collection with all test requests |
| `README.md` | Project summary and documentation (this file) |

## 🧪 API Scenarios Tested

1. Fetch all users - `GET /api/users?page=2`
2. Fetch single user - `GET /api/users/2`
3. Create user - `POST /api/users`
4. Update user - `PUT /api/users/2`
5. Delete user - `DELETE /api/users/2`
6. Successful login - `POST /api/login`
7. Unsuccessful login - `POST /api/login` (Missing password)
8. Successful registration - `POST /api/register`
9. Get users with delay - `GET /api/users?delay=3`

## ✅ Test Execution Status

All test cases were executed in Postman and results were captured in Excel file.  
Requests were also validated for status codes, response bodies, and error handling.

## 📚 How to Run This Project

1. Import the Postman collection (`Reqres_Postman_Collection.json`) into Postman
2. Select the environment or set `{{base_url}}` as `https://reqres.in`
3. Run each request and observe the response
4. Compare with the test cases in `API_Test_Cases.xlsx`

## 💡 Why This Project?

This mini-project is created as part of manual QA preparation to showcase:
- API testing knowledge
- Real-world test case writing
- Postman collection design
- GitHub usage for portfolio building

## 👩‍💻 Author

**Sheema Hamid**  
Manual QA Engineer | Postman API Tester  
📧 Sheemahamid51@gmail.com | https://www.linkedin.com/in/sheema-h-5287b217b/
