# 🏅 GitHub Badges Guide

GitHub badges are visual indicators you can add to your README or documentation to communicate project status, metrics, or actions — such as build status, version, license, code coverage, number of stars, and more.

---

## 📌 What Are Badges?

Badges are small visual tags (like shields) that can:
- Indicate status (✅ Build Passing / ❌ Failing)
- Show metrics (⭐ Stars, 🍴 Forks, 📦 Downloads)
- Track progress (📈 Coverage, 🚧 Work In Progress)
- Provide quick links (📄 License, 📂 Docs)

They make repositories more professional, readable, and informative at a glance.

***Please head over to the [templates file](https://github.com/openhorizonrobotics/.github/blob/main/Badges/Templates.md) to find commonly used badges that you can use in your repositories***

---

## 🔍 Where to Use Badges

- At the top of your `README.md` file
- In GitHub Pages documentation
- In issues or pull request descriptions
- Project wikis

---

## 🛠️ How to Create Your Own Badges

### ✅ Step 1: 

Go to **[https://shields.io](https://shields.io)** — the most popular and free badge generator.

---

### 🧷 Static Badge

These badges have fixed text and colors — they **do not update dynamically**.

1. Go to [https://shields.io](https://shields.io)
2. Click on **"Make your own badge"** (or scroll to the form)
3. Fill in:
   - **Label**: What it shows on the left
   - **Message**: What it shows on the right
   - **Color**: Any valid hex or name (like `blue`, `#f03`)
4. Copy the Markdown/HTML snippet provided
5. For more info watch this [video](https://www.youtube.com/watch?v=4cgpu9L2AE8&t=5s)
---

### 🔄 Dynamic Badge (Live Data)
These update automatically with live GitHub data.

Use prebuilt badge templates such as:

| Badge          | URL Format                                                |
| -------------- | --------------------------------------------------------- |
| ⭐ Stars        | `https://img.shields.io/github/stars/<user>/<repo>`       |
| 🍴 Forks       | `https://img.shields.io/github/forks/<user>/<repo>`       |
| 🐛 Issues      | `https://img.shields.io/github/issues/<user>/<repo>`      |
| 🔧 License     | `https://img.shields.io/github/license/<user>/<repo>`     |
| 🚀 Last Commit | `https://img.shields.io/github/last-commit/<user>/<repo>` |

You can find multiple such badge templates on shields.io and customise them.


<img width="249" alt="image" src="https://github.com/user-attachments/assets/037d2d0f-0832-4b65-9f73-2da88186c7e8" />


<img width="275" alt="image" src="https://github.com/user-attachments/assets/4e1ca1b7-5b4a-42b2-90d3-66fed2dc3d04" />


---

**Example**:

![status](https://img.shields.io/badge/status-active-brightgreen)

```markdown
![status](https://img.shields.io/badge/status-active-brightgreen)
```

