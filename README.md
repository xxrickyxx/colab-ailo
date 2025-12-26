# 🧠 Ailo Network

**Decentralized AI Training Platform** - Train neural networks, earn AiloCoin.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-ailo.site-blue)](https://ailo.site)

## 🚀 What is Ailo?

Ailo Network is a decentralized platform that enables distributed training of Large Language Models (LLMs). Instead of relying on centralized datacenters, Ailo harnesses the collective computing power of users worldwide to train AI models collaboratively.

**Key Features:**
- 🧠 **AILO-1B Model** - 899M parameter Transformer (24 layers × 1600d)
- 💰 **Earn AiloCoin** - Get rewarded for contributing compute power
- 🔒 **Privacy-Preserving** - Only gradients are shared, never raw data
- 🌐 **Federated Learning** - Train locally, aggregate globally

## ⛏️ Mining Options

#2. ☁️ Google Colab Miner (FREE)
No hardware required! Use Google's free Tesla T4 GPU.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xxrickyxx/ailo-network/blob/main/colab-client/Ailo_Colab_Miner.ipynb)

### 3. 🌐 Web Miner (Browser)
Mine directly in your browser at [ailo.site/dashboard.html](https://ailo.site/dashboard.html)

## 📁 Project Structure

```
ailo-network/
├── colab-client/         # Google Colab notebook
│   └── Ailo_Colab_Miner.ipynb
├── server/               # Node.js backend server

## 📊 API Endpoints

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/api/status` | GET | Network status |
| `/api/cuda/register` | POST | Register miner |
| `/api/cuda/submit` | POST | Submit gradients |
| `/api/cuda/training-data` | GET | Get training data |
| `/ws/cuda` | WS | Mining WebSocket |

## 💰 Rewards

- **GPU Mining**: ~0.1 ALC per gradient (quality bonuses up to 10x)
- **Inference**: 0.05 ALC per distributed inference request

## 🔗 Links

- **Website**: [ailo.site](https://ailo.site)
- **Dashboard**: [ailo.site/dashboard.html](https://ailo.site/dashboard.html)
- **Documentation**: [ailo.site/documentation.html](https://ailo.site/documentation.html)
- **Whitepaper**: [ailo.site/whitepaper.html](https://ailo.site/whitepaper.html)

## 📄 License

MIT License - See [LICENSE](LICENSE) for details.

---

**Ailo Network** - *The Distributed AI Brain* 🧠
