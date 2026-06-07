# alienware-16-fan-on-off

## 🌪️ The Direct Core Alternative (No Downloading Required)
If git clone continues to fail or experience connectivity issues on your network, you can bypass third-party software altogether. You can trigger your hardware's native high-performance fan modes directly through your built-in Linux system files.
Open your terminal and execute this command to instantly lock your Alienware fans into Performance Mode:

```bash
echo "performance" | sudo tee /sys/class/platform-profile/platform-profile-*/profile
```

When you are done gaming or running demanding pentesting tasks and want the computer to run quietly again, switch it back to Balanced Mode:

```bash
echo "balanced" | sudo tee /sys/class/platform-profile/platform-profile-*/profile
```
------------------------------
## Propose Next Steps
Did the combined single-line command successfully clone the repository this time? If you are still running into any connection or cloning errors, let me know so we can troubleshoot your network settings or try another utility.

