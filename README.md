# Vagrant





##### To be able to run vagrant, turn hypervisor off.
```cmd
bcdedit /set hypervisorlaunchtype off
```

##### To be able to run docker, turn hypervisor on.
```cmd
bcdedit /set hypervisorlaunchtype auto
```