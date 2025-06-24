# <h2 align=center>Nexus Testnet III</h2>

- 👉 Follow me on Twitter: [@0x_jackal_](https://x.com/0x_jackal_)

| **Requirement**         |
|-------------------------|
| 8GB/16GB RAM or higher  |
| 4core/8core CPU or higher |

---

## 1. Install Docker if your VPS Version 22
```bash
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && \
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && \
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && \
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```

## 2. Create Screen
```bash
screen -S nexus
```

## 3. Run Docker Ubuntu 24
```bash
docker run -it ubuntu:24.04 bash
```

## 4. Install Dependencies
```bash
apt update && apt install -y curl wget unzip
```

## 5. Quick Install Nexus
```bash
curl https://cli.nexus.xyz/ | sh
```

## 6. Update PATH
![PATH Screenshot](https://github.com/user-attachments/assets/c033c96c-9df4-4eb0-8b64-3ff6f79c1faa)

If you see `Updated PATH in /root/.profile`, run:
```bash
source /root/.profile
```

Or if using a newer VPS:
```bash
source ~/.bashrc
```

## 7. Run Nexus Testnet III Script
```bash
nexus-network start --node-id your-node-id
```

> Replace `your-node-id` with your actual node ID  
> Example: `nexus-network start --node-id 678512947`

---

## 📍 VPS Version 24 Instructions

### 1. Create screen
```bash
screen -S nexus
```

### 2. Quick install
```bash
curl https://cli.nexus.xyz/ | sh
```

### 3. Update PATH
```bash
source ~/.bashrc
```

### 4. Run Nexus Testnet III Script
```bash
nexus-network start --node-id your-node-id
```

---

## Screen Command Tips

- **Detach screen**: `CTRL + A + D`  
- **Resume screen**: `screen -r nexus`

---

## 🔔 Need Help?
Follow me for updates: [@0x_jackal_](https://x.com/0x_jackal_)
