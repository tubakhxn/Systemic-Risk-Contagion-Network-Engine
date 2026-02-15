# 3D Systemic Risk Contagion Engine

A modular Streamlit application to model and visualize financial contagion across assets in 3D.

## Features
- Load real or synthetic asset returns
- Compute correlation/covariance matrices and eigenvalue decomposition
- Build a 3D asset network (nodes=assets, edges=correlations)
- Simulate and animate shock propagation with decay
- Interactive controls for shock, decay, threshold, and time
- Systemic risk metrics: network density, centrality, systemic importance
- Striking dark, institutional-grade 3D visualization

## Systemic Risk Modeling
Systemic risk is the risk of collapse of an entire financial system due to the failure of a single entity or group. This engine models how shocks to one asset can propagate through a network of correlated assets, helping to identify vulnerabilities and systemically important nodes.

## Project Structure
- `app.py`: Streamlit UI entry point
- `data_loader.py`: Data loading/generation
- `network_model.py`: Network construction and layout
- `contagion_engine.py`: Shock propagation logic
- `visualization.py`: 3D Plotly visualization
- `metrics.py`: Systemic risk metrics
- `requirements.txt`: Dependencies
- `README.md`: Project overview
