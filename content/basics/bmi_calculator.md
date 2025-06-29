---
title: Bmi Calculator
date: 2025-06-30
author: Your Name
cell_count: 5
score: 5
---

```python
import streamlit as st
```


```python
st.title("⚖️ BMI Calculator")
```

    2025-06-29 18:18:21.810 WARNING streamlit.runtime.scriptrunner_utils.script_run_context: Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.090 
      [33m[1mWarning:[0m to view this Streamlit app on a browser, run it with the following
      command:
    
        streamlit run C:\Users\HP\miniconda3\envs\py312\Lib\site-packages\ipykernel_launcher.py [ARGUMENTS]
    2025-06-29 18:18:22.092 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.093 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    




    DeltaGenerator()




```python
weight = st.number_input("Enter your weight (kg)", 1.0)
height = st.number_input("Enter your height (m)", 0.1)
```

    2025-06-29 18:18:22.116 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.120 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.122 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.125 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.128 Session state does not function when running a script without `streamlit run`
    2025-06-29 18:18:22.132 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.133 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.135 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.136 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.137 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.139 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.142 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.143 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.144 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:22.146 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    


```python
if st.button("Calculate"):
    bmi = weight / (height ** 2)
    st.write(f"Your BMI is: `{round(bmi, 2)}`")
    if bmi < 18.5:
        st.warning("Underweight")
    elif bmi < 24.9:
        st.success("Normal")
    elif bmi < 29.9:
        st.warning("Overweight")
    else:
        st.error("Obese")
```

    2025-06-29 18:18:41.799 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:41.800 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:41.801 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:41.801 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:41.802 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:18:41.803 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    


```python

```


---
**Score: 5**