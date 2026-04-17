# Problem 3 — Weather (7 days × 3 states)

## Part A — marking events

### 1) Monday is sunny
|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| **S** | X | . | . | . | . | . | . |
| **C** | . | . | . | . | . | . | . |
| **R** | . | . | . | . | . | . | . |

### 2) The weekend (Saturday and Sunday) is rainy
|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| **S** | . | . | . | . | . | . | . |
| **C** | . | . | . | . | . | . | . |
| **R** | . | . | . | . | . | X | X |

### 3) It rains on Wednesday or Friday
|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| **S** | . | . | . | . | . | . | . |
| **C** | . | . | . | . | . | . | . |
| **R** | . | . | X | . | X | . | . |

### 4) There is no rainy day during the week
|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| **S** | X | X | X | X | X | X | X |
| **C** | X | X | X | X | X | X | X |
| **R** | . | . | . | . | . | . | . |

### 5) Thursday is not sunny
|     | Mon | Tue | Wed | Thu | Fri | Sat | Sun |
|-----|-----|-----|-----|-----|-----|-----|-----|
| **S** | . | . | . | . | . | . | . |
| **C** | . | . | . | X | . | . | . |
| **R** | . | . | . | X | . | . | . |

---

## Part B — interpretation

### Case 1
**Event:** Saturday and Sunday are sunny.

### Case 2
**Event:** Every day is either sunny or cloudy, and there is no rainy day during the week.
