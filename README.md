A quick patch for virtiofsd not working with looking glass kvmfr

## Dependices 
* ```rust```

## Usage
```bash
# Clone the repo
git clone https://github.com/pantae35872/virtiofsd-quick-patch.git 
cd virtiofsd-quick-patch

./run # Start patching

# replace the existing virtiofsd, usually in /usr/lib/virtiofsd for unix systems
sudo cp virtiofsd-patched /usr/lib/virtiofsd
```
