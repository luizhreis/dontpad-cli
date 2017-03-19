# dontpad-cli

A minimal tool for Dontpad's users under CLI.

**Warning**: This app isn't a Dontpad official software.

## Quick start

```bash
go get github.com/nettoclaudio/dontpad-cli
${GOPATH}/bin/dontpad-cli /my-first-folder/annotations
```

or

```bash
mkdir -p ${GOPATH}/src/github.com/nettoclaudio
cd ${GOPATH}/src/github.com/nettoclaudio
git clone https://github.com/nettoclaudio/dontpad-cli.git
cd dontpad-cli
make
./bin/dontpad-cli /my-first-folder/annotations

# Optional - Put the executable in your PATH
sudo make install
dontpad-cli /my-first-folder/annotations
```
## TO DO

+ ~~View a folder~~
+ Edit a folder
+ Show a list of folder's children
+ Backup a folder(and subfolders)

Made with ~~Dontpad~~love.
