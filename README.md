# Run RL Swarm Node

# Requirements
arm64 or x86 CPU Min. 16GB

OR

GPU (officially supported):
- RTX 3090
- RTX 4090
- A100
- H100

Install Python 
<pre> <code> sudo apt install python3.10-venv </code> </pre>

<pre> <code> sudo apt install -y curl </code> </pre>

Install Node.js (versi LTS)
<pre> <code> curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
sudo apt install -y nodejs </code> </pre>

Cek versi
<pre> <code>  node -v
npm -v </code> </pre>

Install Yarn
<pre> <code> npm install --global yarn </code> </pre>

Cek versi
<pre> <code> yarn -v </code> </pre>



# Install Dependencies
1. Update System Packages
<pre> <code> sudo apt-get update && sudo apt-get upgrade -y </code> </pre>

2. Clone The Repository
<pre> <code> bash git clone https://github.com/gensyn-ai/rl-swarm.git 
  cd rl-swarm</code> </pre>
  
3. Buat dan aktifkan virtual environment:
<pre> <code> python3 -m venv .venv
  source .venv/bin/activate </code> </pre>

4. Instal dependensi
<pre> <code> pip install -r requirements.txt </code> </pre>

5. Jalankan RL Swarm 
<pre> <code>  chmod +x run_rl_swarm.sh
  ./run_rl_swarm.sh </code> </pre>


  Setelah Running, tekan Enter untuk bergabung dengan testnet (pilih opsi Y)

# Login 
