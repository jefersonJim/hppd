# HPPD – Hours per Point per Developer

![HPPD Cover](./hppd-cover.png)

**HPPD** is a simple and effective methodology to estimate task duration based on difficulty (story points) and the specific developer executing the task.

It bridges the gap between story point estimation and real delivery time using actual historical data.

---

## 🚀 What is HPPD?

**HPPD** stands for **Hours per Point per Developer**. It's a lightweight, data-driven approach to improve planning accuracy in software teams.

- Predict task duration per developer
- Analyze productivity per person or project
- Adapt effort estimates to individual pace

---

## 🧮 How It Works

1. Estimate a task using story points (e.g., 5, 8, 13)
2. Log the actual time taken to complete it
3. Calculate:

```text
HPP = Hours Spent / Story Points
```

4. Use a weighted average to reflect recent performance:

```text
Weighted HPP = (Σ(HPP_i × weight_i)) / Σ(weight_i)
```

---

## 🔄 Adaptive Estimates Example

| Task                    | Points | Dev A (HPP: 0.20) | Dev B (HPP: 0.35) |
|------------------------|--------|-------------------|-------------------|
| Create login page      | 8      | 1.6 hours         | 2.8 hours         |
| API integration        | 13     | 2.6 hours         | 4.55 hours        |
| Refactor legacy module | 5      | 1.0 hour          | 1.75 hours        |

---

## ✅ Benefits

- Real-time-based estimates
- Developer-specific predictions
- Easy to integrate with existing agile processes
- Encourages data awareness, not judgment

---

## 🔧 Next Steps

- [ ] Share a Google Sheets template
- [ ] Build browser-based tools or CLI version
- [ ] Create plugins for task managers (Jira, Trello, ClickUp...)

---

## 📄 License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

**Attribution required:** Please credit "Jeferson Macedo" and link back to this repository.

Full license text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## 📫 Contact

Created by **Jeferson Macedo**  
📧 macedojefers@gmail.com  
🔗 [medium.com/@macedojefers](https://medium.com/@macedojefers)
