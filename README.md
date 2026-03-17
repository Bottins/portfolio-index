# Portfolio Progetti - Index

Raccolta dei miei progetti principali in Data Science, Machine Learning e Computer Vision.

## Progetti

### 1) Leaf Detection with YOLOv8
- **Repo**: [Leaf_Yolo_tuning](https://github.com/Bottins/Leaf_Yolo_tuning)
- **Mini abstract**: End-to-end computer vision pipeline for automated leaf detection using YOLOv8. Includes dataset preparation, model training/fine-tuning, TensorFlow Lite export for edge deployment, and comprehensive evaluation metrics (mAP 0.70, precision 0.684).
- **Stack**: Python, PyTorch, Ultralytics YOLOv8, OpenCV, TensorFlow Lite, Pandas.

### 2) Analisi VOCs (PTR-MS)
- **Repo**: [analisi-vocs](https://github.com/Bottins/analisi-vocs)
- **Mini abstract**: Standalone analytical pipeline for Volatile Organic Compound (VOC) data from PTR-MS instruments. Performs time-series analysis, anomaly detection, blank subtraction, replicate aggregation, and PCA for experimental VOC datasets.
- **Stack**: Python, Pandas, NumPy, SciPy, scikit-learn, Matplotlib.

### 3) PINN Inverse per Gray-Scott
- **Repo**: [pinn-gray-scott-inverse](https://github.com/Bottins/pinn-gray-scott-inverse)
- **Mini abstract**: Inferenza inversa dei parametri del modello Gray-Scott con Physics-Informed Neural Networks, più confronto con approcci data-driven (CNN/LSTM).
- **Stack**: Python, PyTorch, NumPy, Matplotlib.

### 4) Transportation Pricing ML
- **Repo**: [pricing-trasporti-ml](https://github.com/Bottins/pricing-trasporti-ml)
- **Mini abstract**: End-to-end machine learning system for predictive transportation pricing. Six-stage pipeline with feature engineering, inflation adjustment, order-quote matching, and model benchmarking (Linear, RF, GB, XGBoost). Achieves R² 0.86 on freight pricing forecasts.
- **Stack**: Python, Pandas, scikit-learn, XGBoost, Matplotlib.

### 5) Topological-Adam Optimizer
- **Repo**: [topological-adam-optimizer](https://github.com/Bottins/topological-adam-optimizer)
- **Mini abstract**: Experimental PyTorch optimizer extending Adam with topology-aware learning rate scaling based on graph structural metrics (centrality, degree distribution). Designed for Graph Neural Networks with 1.5x convergence speedup on benchmark graphs.
- **Stack**: Python, PyTorch, NetworkX, NumPy.

### 6) Insect Behavioral Tracking
- **Repo**: [tracking-insetti-bees-pipeline](https://github.com/Bottins/tracking-insetti-bees-pipeline)
- **Mini abstract**: Computer vision pipeline for automated multi-object tracking and behavioral quantification of insects from video. Kalman filter-based tracking, spatial heatmaps, velocity/acceleration metrics, and interaction detection. 94% track continuity on benchmark videos.
- **Stack**: Python, OpenCV, FilterPy, SciPy, Pandas, Matplotlib.

### 7) Market Score (AI Financial Research Platform)
- **Repo**: [market-score](https://github.com/Bottins/market-score)
- **Mini abstract**: AI-powered financial research platform analyzing ~100 tickers per run. Automated pipeline for market data ingestion, quantitative metrics calculation (Sharpe, Sortino, RSI, momentum), news context aggregation, and LLM-generated structured analysis via OpenAI Batch API. Includes FastAPI backend and React dashboard.
- **Stack**: Python, FastAPI, Pandas, NumPy, scikit-learn, OpenAI API, React, Vite, Recharts, yfinance.

### 8) Scientific ML LLM Fine-Tuning
- **Repo**: [LLM_tuning](https://github.com/Bottins/LLM_tuning)
- **Mini abstract**: Production-ready pipeline for fine-tuning large language models (Qwen3) on Scientific Machine Learning Q&A datasets. Supports single-GPU training with 4-bit QLoRA and multi-node distributed training with FSDP (16+ GPUs). HPC-ready with PBS job scripts for CINECA supercomputing cluster.
- **Stack**: Python, PyTorch, Hugging Face Transformers, PEFT, Accelerate, BitsAndBytes.
---

## Note

- **Documentation Language**: All repository READMEs are written in professional English for international accessibility
- **Data Privacy**: Large datasets and sensitive data are not included in public repositories
- **Repository Contents**: Each repository includes comprehensive README, project structure, and data loading instructions
- **CV-Ready**: All documentation is formatted for professional portfolio and CV presentation


