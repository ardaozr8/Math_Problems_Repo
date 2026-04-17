# 🌦️ Problem 3 — Weather (7 Days × 3 States)

## 📌 Introduction
In this problem, we analyze possible weather conditions over a week.  
Each day can be in one of three states:

- **S** — Sunny  
- **C** — Cloudy  
- **R** — Rainy  

We represent events using tables where:
- Columns = days of the week  
- Rows = weather states  
- **X = allowed/selected condition**

---

# 🟦 Part A — Marking Events

## 1) Monday is sunny
This means only Monday must be sunny.

|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| S   | X   | .   | .   | .   | .   | .   | .   |
| C   | .   | .   | .   | .   | .   | .   | .   |
| R   | .   | .   | .   | .   | .   | .   | .   |

---

## 2) The weekend is rainy
Both Saturday and Sunday must be rainy.

|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| S   | .   | .   | .   | .   | .   | .   | .   |
| C   | .   | .   | .   | .   | .   | .   | .   |
| R   | .   | .   | .   | .   | .   | X   | X   |

---

## 3) It rains on Wednesday or Friday
Rain must occur on at least one of these days.

|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| S   | .   | .   | .   | .   | .   | .   | .   |
| C   | .   | .   | .   | .   | .   | .   | .   |
| R   | .   | .   | X   | .   | X   | .   | .   |

---

## 4) There is no rainy day
Rain never occurs during the week.

|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| S   | X   | X   | X   | X   | X   | X   | X   |
| C   | X   | X   | X   | X   | X   | X   | X   |
| R   | .   | .   | .   | .   | .   | .   | .   |

---

## 5) Thursday is not sunny
Thursday can only be cloudy or rainy.

|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| S   | .   | .   | .   | .   | .   | .   | .   |
| C   | .   | .   | .   | X   | .   | .   | .   |
| R   | .   | .   | .   | X   | .   | .   | .   |

---

# 🟩 Part B — Interpretation

## 🔹 Case 1
**Event:**  
Saturday and Sunday are sunny.

👉 This means the weekend must be sunny regardless of other days.

---

## 🔹 Case 2
**Event:**  
Every day is either sunny or cloudy, and there is no rain during the week.

👉 In other words:
- Rain is completely excluded  
- Only S and C are allowed for all days  

---

# ✅ Conclusion
This exercise demonstrates how logical conditions can be translated into structured representations.  
By using tables, we clearly visualize constraints on possible outcomes and interpret them as events.
