1. Uninstall Docker, Hyper-V, and if installed - the Containers feature. Then reboot.
2. Either through the Control panel, or running powershell as an admin, enable Hyper-V
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Hyper-V -All
3. Reboot, then enable the containers feature either through the control panel or through an
elevated powershell prompt
Enable-WindowsOptionalFeature -Online -FeatureName Containers -All
4. Reinstall Docker
https://docs.docker.com/docker-for-windows/install/#download-docker-for-windows