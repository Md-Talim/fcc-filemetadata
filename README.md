# 📂 File Metadata Microservice  

This is a simple **file metadata microservice** built with **Node.js and Express**. It allows users to upload a file and returns metadata such as the file name, type, and size.  

## 🚀 Features  
✅ Upload a file using a form  
✅ Get file metadata (name, type, size) in JSON format  
✅ Uses **multer** for handling file uploads  
✅ Supports CORS for cross-origin requests  

## 🛠 Tech Stack  
- **Node.js**  
- **Express.js**  
- **Multer** (for file uploads)  
- **Cors** (for handling cross-origin requests)  

## 📦 Installation & Usage  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/file-metadata-microservice.git
cd file-metadata-microservice
```

### 2️⃣ Install dependencies  
```bash
npm install
```

### 3️⃣ Run the app  
```bash
npm start
```

The server will start on **http://localhost:3000**  

## 📝 API Endpoint  

| Method | Endpoint           | Description                    |
| ------ | ------------------ | ------------------------------ |
| `POST` | `/api/fileanalyse` | Upload a file and get metadata |

### Example Response  
```json
{
  "name": "example.png",
  "type": "image/png",
  "size": 34567
}
```
