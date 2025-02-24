## Week 6: Large-Scale & Distributed Systems + Advanced Topics

### Goal
- Gain insight into how FAANG-scale companies handle ML with big data.
- Learn about distributed training (Spark, Horovod, PyTorch Lightning, or TensorFlow MirroredStrategy).
- Explore data engineering pipelines (Kafka, streaming, or big data ingestion).

### Monday: Data Engineering for Big ML
**Topics:**
- Data pipelines, streaming vs. batch, storing large datasets (HDFS, S3).
- Feature stores (e.g., Feast), basics of ETL at scale.

**Notebook (06_large_scale_distributed.ipynb):**
- Outline how you’d design an end-to-end pipeline for a large dataset (conceptual).

### Tuesday: Distributed Training & Parallelization
**Topics:**
- Horovod, PyTorch Distributed, TensorFlow Distributed.
- HPC considerations (GPUs, TPUs).

**Notebook Task:**
- Show a simple code snippet or tutorial that demonstrates multi-GPU training (if you have the resources).
- Otherwise, read a tutorial and summarize.

### Wednesday: Big Data Tools (Spark MLlib, Dask)
**Topics:**
- Spark MLlib for large-scale data, Dask for parallel computing in Python.

**Notebook Tasks:**
- Show a minimal Spark or Dask job for a large CSV.
- Summarize how it differs from scikit-learn.

### Thursday: Advanced/Latest Research Insights
**Topics:**
- Foundation models (GPT-3, PaLM, LLaMA), their scaling, data needs.
- Hugging Face for large language models.

**Notebook Tasks:**
- Summarize the concept of large language models, fine-tuning vs. prompt engineering.
- Optional: a small “prompt engineering” example with a smaller GPT model.

### Friday: Reflections & Real-World Applications
**ADHD Tip:** Summarize in bullet points.
**Industry Context:** Where FAANG uses big data + distributed ML (e.g., Netflix recommendations, Google search ranking, Amazon product suggestions).

### Weekend
**Mini-Implementation:** If possible, attempt a small distributed training or large data ingestion pipeline on a free tier cloud environment or local cluster.
- Document in your notebook how you overcame scaling challenges.
