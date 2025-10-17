# SuperCore

**Letest Version:** 2.0  
**Developer:** @NacDevs  
**Git Repo:** [GitHub](https://github.com/yuvrajmodz/SuperCore)

SuperCore is a Python CLI tool to easily create and start Supervisor-managed processes in Linux.

## Installation & Usage

```bash
pip install supercore --break-system-packages
supercore <command>
```

## Version Checking

```bash
supercore --v
```

## Usage Examples

```bash
supercore python3 app.py
supercore node app.js
```

## Optional installation

```bash
sudo apt update -y
sudo apt install supervisor -y
```