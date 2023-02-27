# streamlit-lightweight-charts

Streamlit component for TradingView's performant financial charts built with HTML5 canvas.

## Installation instructions 

```sh
pip install streamlit-lightweight-charts
```

## Usage instructions

```python
import streamlit as st

from st_lightweight_charts import st_lightweight_charts

value = st_lightweight_charts()

st.write(value)
