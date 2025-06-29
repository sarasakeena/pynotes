---
title: Sentiment Analysis
date: 2025-06-30
author: Your Name
cell_count: 5
score: 5
---

```python
import streamlit as st
from textblob import TextBlob
```


```python
st.title("😊 Sentiment Analyzer")
```

    2025-06-29 18:09:29.122 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.127 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.132 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    




    DeltaGenerator()




```python
text = st.text_area("Write something to analyze...")
```

    2025-06-29 18:09:29.162 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.164 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.165 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.166 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.167 Session state does not function when running a script without `streamlit run`
    2025-06-29 18:09:29.169 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.173 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.174 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    


```python
if st.button("Analyze"):
    blob = TextBlob(text)
    sentiment = blob.sentiment.polarity

    if sentiment > 0:
        st.success("Positive 😊")
    elif sentiment < 0:
        st.error("Negative 😠")
    else:
        st.info("Neutral 😐")
    
    st.write(f"Polarity Score: `{sentiment}`")
```

    2025-06-29 18:09:29.190 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.192 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.194 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.197 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.199 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    2025-06-29 18:09:29.225 Thread 'MainThread': missing ScriptRunContext! This warning can be ignored when running in bare mode.
    


```python

```


---
**Score: 5**