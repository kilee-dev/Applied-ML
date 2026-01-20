# Applied ML & RecSys Engineering Log

This repository serves as a technical knowledge base where I bridge the gap between State-of-the-Art (SOTA) research and production-grade Machine Learning. My focus is on scaling complex model architectures within high-traffic ecosystems.

## 🚀 Professional Snapshot
- **ML Engineer @ TikTok (Social Recommendation):**  Optimizing Story consumption and publishing ecosystems through multi-stage recommendation funnels and large-scale A/B experimentation.
- Production ML Specialist: Focused on delivering end-to-end ML solutions, from designing long-sequence architectures to solving high-scale inference and latency challenges

## 🎯 Focus Areas
- **Graph Neural Networks (GNN):** Leveraging Social Topology and User-to-User interaction for recommendations.
- **Sequential Modeling:** Capturing long/short-term user intent and optimizing attention mechanisms.
- **Systems for ML:** Solving stream-batch joins, signal consistency, and balancing inference latency vs. GPU/CPU cost.

## 📑 Deep Insight Log

| Category | Paper | Core Engineering Insight | Status |
| :--- | :--- | :--- | :--- |
| **GNN** | [Beyond Message Passing: Neural Graph Pattern Machine](https://arxiv.org/abs/2403.11877) | Evaluating subgraph patterns to capture complex social topologies beyond simple message passing. | 🟢 Reading |
| **LTR** | (Upcoming) | - | ⚪️ Todo |
| **ANN** | (Upcoming) | - | ⚪️ Todo |

---

## 💡 Deep Dives

### [GNN] Beyond Message Passing: Neural Graph Pattern Machine
- **Problem:** Conventional GNNs are limited by the WL-test, failing to capture critical structural patterns like 'triangles' or 'cliques' in social networks.
- **Key Takeaway:** By injecting subgraph patterns directly into the network, the model learns structural context that simple neighbor aggregation misses.
- **Applied Thought:** - Translating social interaction data into graph patterns (instead of simple sequences) could significantly refine representation of "relationship depth."
    - **Engineering Constraint:** The primary challenge for productionizing this is managing the computational overhead of pattern extraction at a 1B+ node scale without compromising inference latency.

---

## 📬 Contact
- **Email:** kilee.dev@gmail.com
- **LinkedIn:** http://linkedin.com/in/giunglee
