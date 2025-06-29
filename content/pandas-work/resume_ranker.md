---
title: Resume Ranker
date: 2025-06-29
author: Your Name
cell_count: 6
score: 5
---

```python
import streamlit as st
    

```


```python
st.set_page_config(page_title="Resume Ranker", layout="wide")
st.title("📄 Resume Ranker")
```

    2025-06-29 18:16:24.949 WARNING streamlit.runtime.scriptrunner_utils.script_run_context: Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:24.952 WARNING streamlit.runtime.scriptrunner_utils.script_run_context: Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.405 
      [33m[1mWarning:[0m to view this Streamlit app on a browser, run it with the following
      command:
    
        streamlit run C:\Users\HP\miniconda3\envs\py312\Lib\site-packages\ipykernel_launcher.py [ARGUMENTS]
    2025-06-29 18:16:25.407 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.408 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    




    DeltaGenerator()




```python
skills_required = ["python", "machine learning", "pandas", "sql"]

```


```python
resume_text = st.text_area("Paste your resume content here:")
```

    2025-06-29 18:16:25.452 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.455 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.456 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.460 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.462 Session state does not function when running a script without `streamlit run`
    2025-06-29 18:16:25.463 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.465 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:25.470 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    


```python
if st.button("Check Score"):
    matched = [skill for skill in skills_required if skill.lower() in resume_text.lower()]
    score = len(matched) / len(skills_required) * 100
    st.write(f"### Match Score: `{round(score)}%`")
    st.write("Matched Skills:", matched)
```

    2025-06-29 18:16:28.984 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:28.984 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:28.985 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:28.986 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:28.986 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:16:28.987 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    


```python

```


---
**Score: 5**