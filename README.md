# A3C for Kung Fu Master

This project implements an **Asynchronous Advantage Actor-Critic (A3C)** agent to play *Kung Fu Master* using Gymnasium's Atari environments. The agent learns efficiently across multiple parallel environments using policy and value networks.

![A3C in action](kungfu.gif)

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Connor2452/A3C-Kung-Fu/blob/main/A3C_for_Kung_Fu.ipynb#scrollTo=copy)

---

### How it works
- Preprocesses Atari frames: resize, grayscale, normalize, and stack frames.
- Trains an A3C agent across multiple environments simultaneously.
- Visualizes the trained agent's performance in a playable video.

---

**Notes**
- Designed for **Google Colab** to avoid environment/setup issues on local machines.
- No additional setup needed; all dependencies are installed in the notebook.
