# 📊 GitHub Timeline Generator

![Tech](https://img.shields.io/badge/Tech-PHP%20%7C%20GitHub%20API%20%7C%20HTML%2FCSS-informational)

> A lightweight PHP-based web application that fetches and displays your GitHub activity as a chronological timeline.

---

## ✨ Features

- ⏱️ Displays public GitHub activity as a timeline  
- 🧠 Shows push events, commits, and repositories  
- 📦 Uses GitHub REST API to fetch data  
- 📄 Clean UI using simple HTML/CSS  
- ⚙️ Easily customizable for any GitHub username  

---

## 🔧 Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: PHP  
- **API**: GitHub REST API  

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/survi09mukherjee/github-timeline.git
cd github-timeline
```

### 2. Configure GitHub Username

Open `index.php` and set your GitHub username:

```php
$username = "survi09mukherjee"; // Replace with your GitHub username if needed
```

(Optional) Add a GitHub Personal Access Token if you hit API rate limits:

```php
$headers = [
  "User-Agent: Timeline-App",
  "Authorization: token YOUR_GITHUB_TOKEN_HERE"
];
```

> ⚠️ Do not expose your token in public repos.

### 3. Run Locally

Use any local server like XAMPP/WAMP or run directly:

```bash
php -S localhost:8000
```

Then open your browser and go to:  
[http://localhost:8000](http://localhost:8000)

---

## 🖼 Screenshot

> 
<img width="1915" height="874" alt="3" src="https://github.com/user-attachments/assets/4645051d-1355-4131-b229-24783b22715e" />
<img width="1826" height="832" alt="2" src="https://github.com/user-attachments/assets/f7a4784e-4cb2-4b9e-8e10-9f1c78b816b2" />
<img width="1874" height="866" alt="1" src="https://github.com/user-attachments/assets/a1929988-3005-4ab3-8416-bcea2a0fb1a9" />


---

## 🛠 To-Do / Future Ideas

- Add filter by event type (e.g., PRs, Issues)  
- Show private repo activity with OAuth  
- Add visual timeline or dark mode UI  
- Deploy online with Heroku/Vercel  

---

## 🙋‍♀️ Author

**Survi Mukherjee**  
🔗 [GitHub Profile](https://github.com/survi09mukherjee)

---

## 🌟 Support

If you like this project, give it a ⭐ and share it!
