# 🌐 **HushTag - A Modern Social Media Web App**

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react) 
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.0-7952B3?style=for-the-badge&logo=bootstrap) 
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge) 
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge)  
![Netlify Status](https://img.shields.io/netlify/12345abcde?style=for-the-badge)  
![Maintenance](https://img.shields.io/maintenance/yes/2025?style=for-the-badge)  

## 🌟 **Introduction**  
Welcome to **HushTag** - a dynamic, user-friendly, and modern social media platform built using **React**. Whether you're looking to share your thoughts, explore trending content, or simply connect with others, HushTag provides a streamlined experience designed for modern users.  

### 🔗 **Live Demo:** [HushTag on Netlify](https://hushtag.netlify.app)  
### 💻 **GitHub Repository:** [HushTag on GitHub](https://github.com/trivickram/HushTag)  

---

## 💡 **Motivation**  
In an age where social media platforms are cluttered with overwhelming features, **HushTag** emerges as a minimalist and straightforward alternative. Our goal is to create a space where users can effortlessly share content without the distractions of ads or unnecessary features. HushTag emphasizes simplicity and functionality while maintaining a sleek and intuitive interface.  

---

## 🏗️ **Architecture**  
HushTag follows a **component-based architecture** powered by React and Vite. The application is divided into modular components for ease of maintenance and scalability.  
- **Frontend:** React for UI, Bootstrap for styling  
- **State Management:** Context API with custom hooks  
- **Data Handling:** DummyJSON API for demonstration  
- **Build Tool:** Vite for a fast and optimized development experience  
- **Deployment:** Netlify for hosting and continuous deployment  

---

## ✨ **Core Features**  

### 📢 **Post Creation:**  
- Users can create posts by filling out a simple form.  
- Each post contains the following attributes:  
  - **User ID:** Unique identifier of the author  
  - **Title:** Brief description of the post  
  - **Content:** Main body of the post  
  - **Number of Views:** Automatically generated  
  - **Tags:** Categorizations for easy filtering  
- On submission, the post is sent to the **DummyJSON API** endpoint:
  POST  ```https://dummyjson.com/posts/add```

---

### 📄 **Post Listing:**  
- Displays all available posts in a neat, card-based layout.  
- Uses the **PostListProvider** context to manage the state and keep posts synchronized.  
- Efficient state management using `useReducer` to handle:  
- Adding new posts  
- Deleting existing posts  
- Initializing posts on page load  

---

### 🗑️ **Post Deletion:**  
- Each post features a **Delete** button with an intuitive trash icon (🗑️).  
- Clicking the button prompts the user for confirmation before permanently deleting the post.  
- The `deletePost` function ensures smooth and immediate removal from the UI.  

---

### ⚡ **Performance Optimizations:**  
- **Lazy Loading:** Components are loaded only when needed.  
- **Code Splitting:** Uses dynamic imports to reduce bundle size.  
- **Optimized State Management:** Uses the Context API efficiently to minimize re-renders.  

---

## 🎨 **Visual Interface**  
- **Navbar:** Top navigation for quick access  
- **Sidebar:** Filter and category navigation  
- **Main Feed:** Dynamic list of posts with interactive buttons  
- **Footer:** Links and contact information  

### 🖼️ **Screenshots:**  
| Home Page                       | Create Post                        | Post List                        |
|--------------------------------|------------------------------------|---------------------------------|
| ![Home](./path/to/homepage.png) | ![Create](./path/to/createpost.png) | ![List](./path/to/postlist.png)  |  

---

## 🚀 **Getting Started**  

### **Prerequisites:**  
- **Node.js** (v18+)  
- **pnpm** (v7+)  

### **Installation:**  
1. Clone the repository:  
 ```bash
 git clone https://github.com/trivickram/HushTag.git
 cd HushTag
```
2. Install dependencies:
```bash
   pnpm install
```
3. Start the development server:
```bash
pnpm run dev
```
4. Open the app at:
```bash
http://localhost:3000
```
---

## 🌱 **Usage Scenarios:**  
1. **Content Sharing:** Users can quickly create posts to share thoughts or ideas.  
2. **Community Interaction:** View and interact with posts from other users.  
3. **Personal Space:** Maintain a curated list of posts by deleting irrelevant content.  
4. **Content Discovery:** Explore posts based on tags and popularity.  

---

## 📝 **Contributing:**  
We appreciate your interest in contributing to HushTag!  
- Fork the repository  
- Create a new branch:  
  ```bash
git checkout -b feature/my-new-feature
```
- Commit your changes:

```bash
git commit -m "Add new feature"
```

- Push the branch:
```bash
git push origin feature/my-new-feature
```
- Open a Pull Request

**For more details, check the CONTRIBUTING.md file.**
---

## 🛡️ **Security:**  
For any security issues or vulnerabilities, please check our [SECURITY.md](./SECURITY.md).  

---

## 🗺️ **Future Enhancements:**  
- **User Authentication:** Enable login and signup functionality  
- **Commenting System:** Allow users to interact with posts  
- **Post Reactions:** Like and dislike buttons  
- **Post Sharing:** Share posts with unique links  
- **Enhanced Filtering:** Advanced search by tags and keywords  

---

## 📄 **License:**  
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.  

---

## 💬 **Connect with Us:**  
Have questions, suggestions, or feedback? Feel free to open an issue or start a discussion on GitHub.  
Let's make **HushTag** the next big thing in social media! 🌟  

