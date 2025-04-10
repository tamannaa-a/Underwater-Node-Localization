# Underwater-Node-Localization
Designed a prototype of Node localization in UWSN (underwater wireless sensor network) using NS-3

Key Features
- Implementation of DV-Hop algorithm for UWSNs in NS-3
- Integration of ML models (e.g., SVR, Random Forest) to refine hop distance estimation
- Simulation and visualization of underwater node mobility
- Comparative performance analysis between DV-Hop, TDoA, and ML-enhanced DV-Hop

Technologies Used
- **Simulator**: NS-3 (Network Simulator 3)
- **Visualization**: NetAnim
- **Programming Languages**: C++, Python
- **Machine Learning Models**: Support Vector Regression, Random Forest, Neural Networks

Machine learning models are used to:
- Predict average hop distances more accurately
- Minimize localization errors due to irregular topologies
- Adapt to node movement caused by underwater currents
