# BlockMesh Node Installation Script

This script automates the deployment process of a BlockMesh node, making it easier to set up and manage your node.

## ⚡ Quick Install

Using curl:
```bash
curl -fsSL https://raw.githubusercontent.com/Galkurta/BlockMesh/main/install.sh -o install.sh && chmod +x install.sh && sudo ./install.sh
```

Using wget:
```bash
wget https://raw.githubusercontent.com/Galkurta/BlockMesh/main/install.sh && chmod +x install.sh && sudo ./install.sh
```

## 🚀 Features

- Easy-to-use menu interface
- Automatic Docker installation
- Docker Compose setup
- Node deployment automation
- Log viewing capability
- System status monitoring

## 📋 Prerequisites

Before running the script, you need:

1. A Linux-based operating system (Ubuntu recommended)
2. Root/sudo privileges
3. A BlockMesh account (Register [here](https://app.blockmesh.xyz/register?invite_code=Galkurta))
4. Active internet connection

## 🔧 After Installation

Once installed, you can run the node manager anytime using:
```bash
sudo ~/.blockmesh/install.sh
```

## 📊 System Status

The script shows real-time status of:
- Docker installation
- Docker Compose installation
- BlockMesh node status (Running/Stopped/Not Deployed)

## 🛟 Troubleshooting

If you encounter any issues:

1. **Docker Installation Fails**
   - Ensure your system is up to date
   - Check internet connectivity
   - Verify system compatibility

2. **Node Won't Start**
   - Verify your credentials
   - Check Docker service status
   - Ensure ports are not in use

3. **Can't View Logs**
   - Confirm node is running
   - Check Docker permissions

## 📁 File Structure

```
~/.blockmesh/
├── install.sh           # Installation script
├── blockmesh-cli.tar.gz # CLI package
└── target/
    └── release/
        └── blockmesh-cli # Executable
```

## 🔐 Security Note

- The script requires root privileges
- Credentials are stored securely in the container environment
- No sensitive data is stored on disk

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## ⚠️ Disclaimer

This is an unofficial installation script. Please use at your own discretion and always verify the source before running scripts with root privileges.

## 💪 Support

If you need help or have questions:
1. Check the [BlockMesh Documentation](https://docs.blockmesh.xyz)
2. Join the [BlockMesh Community](https://discord.gg/blockmesh)
3. Submit an issue in this repository

---
Created with ❤️ for the BlockMesh Community