# Quora RESTful API

A simple Quora-inspired web application built using **Node.js, Express.js, and EJS**. This project demonstrates CRUD (Create, Read, Update, Delete) operations for managing posts.

## 🚀 Features

- **Create Posts:** Add new posts with a username and content.
- **View All Posts:** Display all available posts.
- **View Individual Posts:** View details of a specific post using its unique ID.
- **Edit Posts:** Update the content of an existing post.
- **Delete Posts:** Delete a specific post.
- **Unique IDs:** Generate unique post IDs using UUID.
- **Method Override:** Support PATCH and DELETE HTTP methods through HTML forms.

## 🛠️ Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- UUID
- Method-Override
- HTML
- CSS

## 📂 Project Structure

```text
QuoraRestfulAPI/
│
├── public/
│   ├── style.css
│   └── ScreenShot/
│       └── image.png
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── edit.ejs
│   └── show.ejs
│
├── index.js
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation and Setup

**1. Clone the repository**

```bash
git clone https://github.com/Sonu-Jha12/QuoraRestfulAPI.git
```

**2. Navigate to the project directory**

```bash
cd QuoraRestfulAPI
```

**3. Install dependencies**

```bash
npm install
```

**4. Start the server**

```bash
node index.js
```

Or, if Nodemon is installed:

```bash
nodemon index.js
```

**5. Open in your browser**

```text
http://localhost:8080/posts
```

## 🔗 Application Routes

| HTTP Method | Route | Description |
|---|---|---|
| GET | `/posts` | Display all posts |
| GET | `/posts/new` | Show the new post form |
| POST | `/posts` | Create a new post |
| GET | `/posts/:id` | View a specific post |
| GET | `/posts/:id/edit` | Show the edit form |
| PATCH | `/posts/:id` | Update an existing post |
| DELETE | `/posts/:id` | Delete a post |

## 📸 Application Screenshot

![Quora RESTful API Screenshot](public/ScreenShot/image.png)

## 📚 Learning Outcomes

Through this project, I learned:

- Understanding RESTful API principles.
- Implementing CRUD operations using Express.js.
- Working with dynamic routes and route parameters.
- Using EJS for dynamic page rendering.
- Handling form submissions using Express.
- Using UUID for unique identification.
- Implementing PATCH and DELETE methods using Method Override.

## ⚠️ Note

This project currently uses an in-memory array to store posts. Therefore, posts are reset to their initial state whenever the server restarts. Database integration can be added in future improvements.

## 👨‍💻 Author

**Sonu Jha**

MCA Student | IIIT Vadodara

GitHub: [Sonu-Jha12](https://github.com/Sonu-Jha12)

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!
