# LMS


# 📚 Full-Stack Learning Management System (LMS)

A modern, responsive, and scalable Learning Management System (LMS) built with a full-stack JavaScript ecosystem. This project enables course creation, video hosting, student enrollment, progress tracking, and payment processing.

## 🚀 Tech Stack

**Frontend**  
- React 18  
- React Router DOM  
- TailwindCSS & tailwindcss-animate  
- Framer Motion  
- Radix UI components  
- Lucide React (Icons)  
- React Confetti  
- React Player

**Backend**  
- Node.js & Express  
- MongoDB & Mongoose  
- JWT (Authentication)  
- bcryptjs (Password hashing)  
- dotenv (Environment config)  
- cors  
- multer (File upload)  
- cloudinary (Media storage)  
- PayPal REST SDK (Payments)

---

## 📦 Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/lms-project.git
   cd lms-project
   ```

2. **Install server dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Install client dependencies:**
   ```bash
   cd ../client
   npm install
   ```

---

## 🔐 Environment Variables

Create a `.env` file in the `server/` directory and include:

```env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_CLIENT_SECRET=your_paypal_client_secret
```

---

## 🧩 Key Features

- ✅ User Authentication (JWT + bcrypt)
- 📁 Course creation & management
- 🎥 Video uploads via Cloudinary
- 📦 File uploads via Multer
- 🧑‍🎓 Student dashboard with progress tracking
- 💳 Payment integration (PayPal SDK)
- 🌈 Interactive UI with Radix UI + Framer Motion
- 🔥 Fully responsive design

---

## 📸 UI Libraries & Components

- **Radix UI**: Checkbox, Dialog, Dropdown, Label, Select, Switch, Tabs, Toast, etc.
- **Framer Motion**: Smooth animations
- **Lucide Icons**: Modern SVG icons
- **React Player**: Embed video content
- **React Confetti**: Celebration effects on course completion

---

## 🧪 Scripts

Run the **server**:

```bash
cd server
npm run dev
```

Run the **client**:

```bash
cd client
npm start
```

---

## 📂 Project Structure

```
lms-project/
│
├── client/        # Frontend React app
│   ├── src/
│   └── public/
│
├── server/        # Backend Express API
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── utils/
│
└── README.md
```

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome!  
Feel free to check the [issues page](https://github.com/your-username/lms-project/issues).

---

## 📄 License

MIT License

Copyright (c) 2025 Mohammed Maaz Rayeen

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
