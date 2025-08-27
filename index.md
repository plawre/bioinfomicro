# Introductory Bioinformatic Analysis of Marine Microbes

**When/Where:** Mondays • Discovery Hall Visualization & Analysis Lab (1st floor)  
**Bring:** Laptop (Windows or macOS). No prior coding experience required.

## Start Here (Pre-work)
1. **W0 — Access the Unix shell**
   - **Windows:** install WSL2 + Ubuntu (Microsoft Store or `wsl --install`)
   - **macOS:** open Terminal and run `xcode-select --install`
   - Try: `ls`, `pwd`, `echo "Hello!"`
   - Details: [W0 tutorial](./W0.md)

2. *(If time)* **Install Miniconda** and create a clean environment:
   ```bash
   conda create -n biotot python=3.11 -y
   conda activate biotot
