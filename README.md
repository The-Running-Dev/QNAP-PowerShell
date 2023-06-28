# PowerShell for QNAP

1. Download Debian package from https://github.com/PowerShell/PowerShell/releases.

2. Extract the .deb package with 7-Zip

3. Extract the data.tar.gz

```bash
tar xvf ./data.tar.gz
```

4. Copy the contents of ```opt\microsoft\powershell\``` to ```shared\powershell```

5. Make sure that the the entry points are executable:

```bash
chmod +x PowerShell.sh pwsh
```

6. Build with qBuild

```bash
cd /path/to/QDK/PowerShellPackageContents
./qbuild
```
