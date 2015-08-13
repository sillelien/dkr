#dkr [![Experimental](https://img.shields.io/badge/Status-Experimental_or_POC-red.svg?style=flat)](http://github.com/sillelien/dkr)

A command to make life easier when using Docker on the CLI.

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

## Commands

### Clean

To remove all images and containers to free up space:

```
  dkr clean
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

