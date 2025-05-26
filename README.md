🚀 HPPD – Hours per Point per Developer

### A practical way to turn story points into real time (and better decisions)

> Have you ever thought about predicting task duration based on difficulty and who will execute it?
> With **HPPD**, that's possible — in a simple, objective, and developer-personalized way.

---

## 💡 What is HPPD?

**HPPD (Hours per Point per Developer)** is a methodology that combines two familiar concepts:

* Story Points (difficulty estimates)
* Actual time spent on tasks

With it, you can predict **how long each task will take**, considering **who will work on it**.

---

## 🧮 How does it work?

1. **Estimate the task in story points** (e.g., 5, 8, 13), as in Scrum.

2. After delivery, record the **actual time spent**.

3. Calculate the developer's **HPP (Hours per Point)**:

   ```
   HPP = Time Spent / Story Points
   ```

4. With multiple tasks, you compute a **weighted average**, favoring the most recent ones:

   ```
   Weighted HPP = (Σ(HPP_i × weight_i)) / Σ(weight_i)
   ```

---

## 🔄 Adaptive estimates per developer

With each dev's HPP, the same task gets **different estimates** depending on the person’s historical performance.

### Practical example:

| Task                   | Points | Dev A (HPP: 0.20) | Dev B (HPP: 0.35) |
| ---------------------- | ------ | ----------------- | ----------------- |
| Create login page      | 8      | 1.6 hours         | 2.8 hours         |
| API integration        | 13     | 2.6 hours         | 4.55 hours        |
| Refactor legacy module | 5      | 1.0 hour          | 1.75 hours        |

This helps the team:

* Allocate tasks more precisely
* Adjust deadlines based on the executor
* Identify bottlenecks and productivity patterns

---

## 📊 Performance analysis too

You can also use it to track productivity by developer or by project:

### By developer:

| Dev   | Avg HPP |
| ----- | ------- |
| Ana   | 0.22    |
| Bruno | 0.30    |

### By project:

| Project  | Avg Dev HPP |
| -------- | ----------- |
| System A | 0.20        |
| System B | 0.35        |

---

## ✅ Advantages

* Based on **real data**
* **Personalized estimates** per developer
* Easy to apply if your team already uses story points
* Improves **forecasting and task allocation**
* Works for both **analysis and planning**

---

## ⚠️ A word of caution

> HPPD is **not for control or punishment**, but for learning and growth.

* Avoid comparing developers out of context
* Ensure consistent story point estimation
* Use with maturity and focus on continuous improvement

---

## ✨ Why I created this

I’m a developer and team lead. Over the years, I noticed that while we estimate tasks using points, we rarely correlate those with real time.

HPPD was born as a simple way to bridge that gap. It’s straightforward, practical, and can help any team make more confident decisions.

---

## 🔧 Next steps

* Build a free spreadsheet template with the formulas
* Share a GitHub repo with sample data
* Test with different teams and contexts

---

## 💬 Want to use or contribute?

Feel free to apply, adapt, or share feedback. And if you know a similar method, let me know — I’m here to learn too. 🙌

* 📎 License: free to use with attribution
* 📩 Contact: [macedojefers@gmail.com](mailto:macedojefers@gmail.com)
* 🔗 [GitHub](https://github.com/jefersonJim/hppd)
