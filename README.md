# Meal Planning Optimization Tool

This project features a Google Colab notebook that uses **linear programming** (via [PuLP](https://coin-or.github.io/pulp/)) to generate optimized weekly meal plans.



The goal is to design an optimized weekly meal plan that balances **cooking time**, **ingredient availability**, and **menu variety**.

The meal plan aims to:

-  minimize total **daily cooking time**, staying within specified time constraints  
-  prioritize recipes that use **available ingredients** to reduce waste  
-  ensure **diversity** in meals across the week  
-  favor recipes containing a **user-prioritized ingredient**, accommodating preferences

---

## Notebook

- `meal_planner.ipynb`: A Colab-based optimization model that applies linear programming to solve the above problem, using customizable inputs.

---

## Technologies

- Python 3  
- [PuLP](https://coin-or.github.io/pulp/) (for linear programming)
- Google Colab (for easy experimentation)

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run each cell step by step  
3. Customize:
   - Recipe list and time requirements  
   - Ingredient inventory and priority settings  
   - Daily time limits and constraints  

## Future Improvements

- Add a user interface (e.g., Streamlit or Gradio)  
- Allow export to Excel or PDF  
- Introduce nutritional tracking or budget constraints  
