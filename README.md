# Streamlit Test App

## Quick Start

### Run Locally

1. **Set up your environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**:
   ```bash
   streamlit run app.py
   ```

4. **Open your browser** to `http://localhost:8501`


## Troubleshooting

### Local Development Issues

Common local development solutions:

```bash
# Reinstall dependencies
pip install --upgrade -r requirements.txt

# Check Python version (requires 3.8+)
python --version

# Clear Streamlit cache
streamlit cache clear

# Run with verbose output
streamlit run app.py --logger.level=debug
```





