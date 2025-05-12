# 🗂️ File Metadata Microservice

The **File Metadata Microservice** is an API that allows users to upload a file and receive metadata about the file, such as its name, type, and size.

## 📖 Learning Journey
This project was built while following [freeCodeCamp's Back End Development and APIs Course](https://www.freecodecamp.org/learn/back-end-development-and-apis).

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS
- **Backend:** Node.js (Express.js)
- **File Upload:** Multer

## 🎯 Features
- Accepts a file upload via the `/api/fileanalyse` route.
- Returns metadata about the uploaded file:
  - `name`: The name of the file.
  - `type`: The MIME type of the file.
  - `size`: The size of the file in bytes.

## 🚀 Usage Examples

### Request: Upload a File
POST `/api/fileanalyse` 

**Form Data:**
- `file`: (The file to be uploaded)

**Response:**
```json
{
  "name": "example.jpg",
  "type": "image/jpeg",
  "size": 123456
}
```

## 📦 Installation & Setup
1. **Clone the repository:**
  ```sh
  git clone https://github.com/calvinbayaua/boilerplate-project-filemetadata.git
  cd boilerplate-project-filemetadata
  ```
2. **Install dependencies:**
  ```sh
  npm i
  ```
3. **Start the server**
  ```sh
  npm run start
  ```
