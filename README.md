# coord-selector

Streamlit component that allows you to select a coordinate on an image

## Installation instructions 

```sh
pip install coord-selector
```

## Usage instructions

```python
import streamlit as st

from coord_selector import coord_selector

value = coord_selector()

st.write(value)
