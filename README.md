

# 🌐 DevSecOps Campground 3-Tier CI/CD 📦

**Security-first, cloud-ready CI/CD pipeline: Automated build, test, deploy, and protection for the modern Node.js stack.**

***

## 🎯 Project Overview

A robust, cloud-native Yelp Campground app with **fully automated DevSecOps pipeline**—features authentication, image upload, mapping, and secure cloud deployment.

- **Stack:** Node.js, Express, EJS, Bootstrap, MongoDB Atlas, Mapbox, Cloudinary, Docker, Kubernetes, Jenkins, SonarQube, Trivy, AWS
- **Security:** Passport, Helmet, Environment hardening, Trivy & SonarQube scans

***

## 🛡️ Features

| Type               | Details                                                           |
|--------------------|-------------------------------------------------------------------|
| 🏕 Campground CRUD | Add, view, rate campgrounds, search by location                   |
| 🎨 Maps/Images     | Mapbox cluster maps, Cloudinary image storage                     |
| 👤 Auth            | Passport (local strategy), secure registration & login            |
| 🕸️ Security        | Helmet, .env secrets, SonarQube, Trivy scans                      |
| 🚀 DevOps          | Automated CI/CD: build, test, scan, deploy                        |
| 🧑‍💻 Infra          | Docker Compose, k8s manifests, AWS EC2 deploy, MongoDB Atlas      |

***

## 🚦 How to Launch Locally

1. **Create cloud accounts:** Cloudinary, Mapbox, MongoDB Atlas
2. **Make a `.env` file** in the root folder **with:**
    ```
    CLOUDINARY_CLOUD_NAME=yourname
    CLOUDINARY_KEY=yourkey
    CLOUDINARY_SECRET=yoursecret
    MAPBOX_TOKEN=yourmapbox
    DB_URL=yourmongodb
    SECRET=yourcustomsecret
    ```
3. **Start app:**
    ```shell
    docker compose up
    ```
    Automatic: runs the web server, database, and required services.

***

## 📁 Folder Structure

```
DevSecOps-3Tier-CI-CD/
├── Manifests/          # Kubernetes files
├── controllers/        # Route handlers
├── models/             # MongoDB models
├── views/              # EJS templates
├── public/             # CSS, images
├── docker-compose.yml  # Multi-service deployment
├── Dockerfile          # App containerization
├── app.js              # Server entry point
├── .env                # Secrets & cloud tokens
└── README.md           # Docs (you're here!)
```

***

## 💡 Security & DevOps

- **Security-by-default:**  
  - Helmet (HTTP protection)
  - Strong auth, .env secrets
  - Trivy container scanning
  - SonarQube code quality
- **Full Automation:**  
  - Jenkins triggers build, test, scan, deploy
  - Docker images for environment control
  - Kubernetes manifests for scalable cloud deployment
- **Monitoring:**  
  - SonarQube dashboards
  - Trivy scan reports
  - Cloud vendor logging

***

## 🎨 UI & Typography

- **Fonts:** `'Nunito'` for headings, `'Quicksand'` for body—soft, rounded, easy to read
- **Gradient backgrounds** in cards & sections for modern feel
- **Mapbox maps**, Bootstrap-styled forms
- **Pastel blues and mints** for security cues

```css
body {
  font-family: 'Quicksand', 'Nunito', Arial, sans-serif;
  background: linear-gradient(120deg, #e5faff 0%, #deeaff 100%);
}
section, .card {
  background: linear-gradient(98deg, #f7fcff 40%, #f1f8ff 100%);
  border-radius: 20px;
  box-shadow: 0 2px 10px #c1e8ff23;
}
```

***

## 🏆 Highlights

- 🌍 Clustered maps for campgrounds
- 🔒 Robust authentication and authorization
- 🧑‍💻 End-to-end security and automation
- 🚀 Easy cloud deployment

***

## 🤝 Contributing

- **Issues:** [Report or request features](https://github.com/Vishsig/DevSecOps-3Tier-CI-CD/issues)
- **Stars/Fork:** Show support or build on the project!

***

## 📜 License

Distributed under the MIT License (see LICENSE file).

***

## 📫 Contact

For questions or ideas, open an issue or contact [Vishsig](https://github.com/Vishsig).
