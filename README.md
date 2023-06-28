# PowerShell for QNAP

1. Clone this repository

```bash
git clone git@github.com:The-Running-Dev/QNAP-PowerShell.git
```

2. Download Debian package from https://github.com/PowerShell/PowerShell/releases.

3. Extract the .deb package with 7-Zip

4. Extract the ```data.tar.gz``` archive

```bash
tar xvf ./data.tar.gz
```

5. Copy the contents of ```opt\microsoft\powershell\*``` to ```./QNAP-PowerShell/shared/powershell```

6. Make sure that the the entry points are executable:

```bash
cd ./QNAP-PowerShell/shared

chmod +x PowerShell.sh pwsh
```

7. Build with qBuild

```bash
cd ./QNAP-PowerShell

./qbuild
```
