# VirtioFSD quick patch

A quick patch for virtiofsd not working with looking glass kvmfr

## Dependices 
* ```rust```

## Usage
```bash
# Clone the repo
git clone https://github.com/pantae35872/virtiofsd-quick-patch.git 
cd virtiofsd-quick-patch

./run # Start patching

# Replace the existing virtiofsd, usually in /usr/lib/virtiofsd for unix systems
# Important !! Make sure the vm is not running !!
sudo cp virtiofsd-patched /usr/lib/virtiofsd
```
