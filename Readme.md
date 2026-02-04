Nice, setting up collab projects is a power move 💪
Here’s the clean, real-world way to do it on **GitHub**.

---

## 🧱 1️⃣ Create a New Project (Repository)

1. Go to **github.com**
2. Click **+ (top right)** → **New repository**
3. Fill in:

   * **Repository name** (e.g., `my-awesome-app`)
   * Description (optional)
   * Choose **Public** or **Private**
4. ✅ Check **Add a README**
5. Click **Create repository**

Boom — project created.

---

## 👥 2️⃣ Add Collaborators (People Who Can Work on It)

> You can add people only to **your own repo** or if you’re an **admin** of an org repo.

1. Open your repository
2. Click **Settings** (top menu)
3. In the left sidebar → **Collaborators & teams**
4. Click **Add people**
5. Enter their **GitHub username or email**
6. Choose role:

| Role         | What they can do        |
| ------------ | ----------------------- |
| **Read**     | View only               |
| **Triage**   | Manage issues           |
| **Write**    | Push code               |
| **Maintain** | Manage repo (no delete) |
| **Admin**    | Full control            |

👉 For teammates, usually **Write** is enough.

They’ll get an email invite → once accepted, they can push code.

---

## 🔄 3️⃣ How Collaborators Work on the Code

Each collaborator does this:

```bash
git clone https://github.com/Chandramouli2022/ai_insurance_advisor.git
cd ai_insurance_advisor
```

Create a branch (BEST PRACTICE):

```bash
git checkout -b alok-branch
git checkout -b mouli-branch
```

Make changes → then:

```bash
git add .
git commit -m "v001 - commit discription"
git push origin alok-branch
```

Then open a **Pull Request (PR)** on GitHub to merge into `main`.

---

## 🧠 4️⃣ Pro Team Workflow (Recommended)

✔ Never push directly to `main`
✔ Use **feature branches**
✔ Use **Pull Requests** for review
✔ Enable **branch protection** (Settings → Branches → Add rule)

---

## 🏢 If This Is for a Team or Company

Better way:

1. Create a **GitHub Organization**
2. Create **Teams** (Frontend, Backend, etc.)
3. Add people to teams
4. Give team access to repos

This scales better than adding people one by one.

---

## 🚀 Bonus: Use GitHub Projects (Task Board)

Inside the repo:

1. Go to **Projects**
2. Click **New Project**
3. Choose **Board**
4. Create columns like:

   * Todo
   * In Progress
   * Done

Now your collab project has task tracking too 🔥

---

If you tell me:

* personal project or company project?
* how many collaborators?

…I’ll suggest the **best permission setup** for your case.
