#dkr

A command to make life easier when using Docker on the CLI, it is designed as a development tool and therefore makes some assumptions about your development environment.

Only tested on my Mac laptop so:

Pull requests and Issues welcome!

## Install
```
sudo curl -L https://raw.githubusercontent.com/sillelien/dkr/master/dkr > /usr/local/bin/dkr && sudo chmod 755 /usr/local/bin/dkr
```

## Use

```bash
dkr help
```

To get the latest version of the script

```bash
dkr update
```

##
## Commands

### Clean

To remove all images and containers to free up space:

```
  dkr clean
```  


To remove all images and containers even if they are in use to free up space:

```
  dkr fcn
  dkr force-clean
```  

### Build Docker Image from this Directory

```
    dkr bld
```    

### Run Image built with `bld`

```
    dkr rn
    dkr drun
```    

### Build and Run

```
    dkr do
    dkr build-run
```
    
### Open browser at port and path
    
```
    dkr open 8080
    dkr open 8080 subdir/file.html
```

### Run Bash Shell

```
    dkr bsh
    dkr bash
    dkr bash -v /var/run/docker.sock:/var/run/docker.sock debian:jessie
```    


### Fix Problems with docker-machine 

```
    dkr fix-mac
```    

### Bash Shell

To run a bash shell in Ubuntu (maybe to check how a command works or something).

```
   dkr bash
```   


## Contributing

Please fork and switch to the dev branch and create PRs from their.

To test the dev branch:

```
sudo curl -L https://raw.githubusercontent.com/sillelien/dkr/dev/dkr > /usr/local/bin/_dkr && sudo chmod 755 /usr/local/bin/_dkr
```

Then use the _dkr command instead of dkr for testing.

