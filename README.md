// ===============================
// GitHub Profile — Bonly Kimheng
// ===============================

const user = {
  name: "Bonly Kimheng",
  role: [
    "Fullstack Web Developer",
    "Junior DevOps Engineer"
  ],
  location: "Earth 🌍",
  languages: ["JavaScript", "TypeScript", "HTML", "CSS", "Bash"],
  frameworks: [
    "Node.js",
    "Express",
    "React",
    "Next.js"
  ],
  devOps: [
    "Docker",
    "Linux",
    "CI/CD",
    "Nginx",
    "GitHub Actions",
    "AWS (basic)"
  ],
  databases: [
    "MongoDB",
    "PostgreSQL",
    "MySQL"
  ],
  tools: [
    "Git",
    "VS Code",
    "Postman",
    "Figma"
  ],
  mindset: "Always learning, always building 🚀"
};

function aboutMe() {
  console.log(`
  👋 Hi, I'm ${user.name}

  💻 ${user.role.join(" | ")}
  
  🧠 I enjoy building scalable web apps,
  automating workflows, and deploying
  real-world systems.

  🔧 Tech Stack:
  - Frontend: React, Next.js
  - Backend: Node.js, Express
  - DevOps: Docker, CI/CD, Linux

  🚀 Goal:
  Become a strong Fullstack + DevOps Engineer
  who ships reliable, production-ready software.
  `);
}

aboutMe();
