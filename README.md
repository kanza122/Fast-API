# 🧪 FastAPI Full Stack Application — QA Testing Project

This is a **simple full-stack FastAPI web application** that I used for **in-depth QA testing**.  
I performed **manual functional testing**, **UI validation**, and **API testing using Postman**.  

---

## 📁 **Project Structure**

| Folder | Description |
|--------|--------------|
| 🧩 **code/** | Contains the full-stack FastAPI application (backend + frontend) |
| 🧪 **testcases/** | Contains detailed manual test cases in Excel format |
| ⚙️ **postman_api/** | Contains Postman collection and environment files used for API testing |

---

## 🎯 **Testing Overview**

- Verified **end-to-end flow** of user management:
  - Register new user  
  - Login  
  - Forgot password & reset  
  - Update profile  
  - Delete user account  
- Tested **Items module**:
  - Add, Edit, Delete items  
  - Validation messages and error handling  
- Checked **UI/UX behavior** and **response times**
- Performed **API automation** using **Postman test scripts**

---

## 🧪 **API Testing Tools Used**
- **Postman** for API request validation  
- **Newman** for batch collection execution  
- **Environment variables** for token handling  
- **JavaScript test scripts** inside Postman for:
  - Status code validation  
  - Access token verification  
  - Field-level response checks  

---

## 📊 **Test Artifacts**

| File | Description |
|------|--------------|
| `testcases/FastAPI_TestPlan_and_Cases_New.xlsx` | Complete manual test cases |
| `postman_api/FastAPI_Test_Collection.json` | Postman collection with API requests |
| `postman_api/FastAPI_Env.json` | Postman environment for base URLs & tokens |

---

## 🖼️ **Application Screenshots**

### 🔐 **Login Page**
![Login Page](https://drive.google.com/file/d/1lffdg8iECEYR-x_Ygkj7VZ3A_wZTjBjr/view?usp=sharing)
> Used for user authentication with email and password validation.

---

### 📝 **Sign Up Page**
![Sign Up Page](./img/a2f07f30-4d31-4e09-947f-5ea9258af21a.png)
> User registration with validation for email, password, and confirmation field.

---

### 🏠 **Dashboard**
![Dashboard](https://github.com/kanza122/Fast-API/blob/main/Dashboard.png)
> Displays welcome message and navigation menu.

---

### 📦 **Items Management Page**
![Items Management](./img/64539813-ddd2-45c3-9eff-c61e999ff951.png)
> Allows creating, editing, and deleting items with validation for title and description.

---

### ⚙️ **User Settings → Profile Tab**
![User Settings - Profile](./img/a18f7f16-75af-43c5-b47e-4cb313e667d3.png)
> Shows user details (full name and email) with an edit option.

---

### 🔑 **User Settings → Password Tab**
![User Settings - Password](./img/5e9f393b-fc0d-4de6-a5f7-a7db11f87da8.png)
> Enables changing password with validation for current, new, and confirm password fields.

---

### 🎨 **User Settings → Appearance Tab**
![User Settings - Appearance](./img/85a462d4-4635-421b-af9c-7808a425d424.png)
> User can switch between light, dark, and system theme modes.

---

### 🚨 **User Settings → Danger Zone**
![User Settings - Danger Zone](./img/2c207a92-cf1e-44c6-a190-4c7522fa2291.png)
> Permanently delete account and all associated data.

---

## ⚙️ **How to Run the Project Locally**

### 1️⃣ Clone the repository
```bash
git clone https://github.com/kanza122/Fast-API.git
cd Fast-API/code
