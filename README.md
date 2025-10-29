# Certified Cloud Native Platform Engineering Associate — Mock Exam

![Docker](https://img.shields.io/badge/docker-ready-blue)
![License](https://img.shields.io/badge/license-MIT-green)

<p align="center" width="100%">
    <img width="35%" src="./app/public/your-logo-here.jpeg">
</p>

This repository provides a single-page web app for practicing Certified Cloud Native Platform Engineering Associate (CNPA) exam questions. The app is built with Node.js and serves a quiz interface with multiple-choice questions.

---

## 🚀 Features

- Multiple-choice questions based on the official CNPA practice exam
- Instant feedback and explanations
- Sectioned questions for focused study
- Dockerized for easy deployment

---

## 📁 Project Layout

```bash
cnpa-mock-exam/
├── Dockerfile
├── .dockerignore
├── app/
│   ├── package.json
│   ├── server.js
│   ├── public/
│   │   ├── index.html
│   │   ├── app.js
│   │   ├── styles.css
│   ├── data/
│   │   ├── questions.json
```

---

## 🛠️ Usage

### Run the pre-build container

```sh
docker run --name cnpa-mock-exam -p 3000:3000 hiddevg/cnpa-mock-exam:latest
```

## 💻 Development usage

### Build the Docker image

```sh
docker build -t cnpa-mock-exam:latest .
```

### Run the container (port 3000)

```sh
docker run --rm -p 3000:3000 cnpa-mock-exam:latest
```

Open [http://localhost:3000](http://localhost:3000) in your browser to start practicing.

---

## 📝 Contributing

Pull requests and suggestions are welcome! Feel free to submit new questions, improvements, or bug fixes.

---

## 📄 License

This project is licensed under the MIT License.
