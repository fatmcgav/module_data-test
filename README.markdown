# Test puppet structure for Puppet module_data

Run the following to test:
```
$ git clone https://github.com/fatmcgav/module_data-test.git

$ cd module_data-test

$ librarian-puppet install --path modules

$ puppet apply -v --modulepath modules --hiera_config hiera/hiera.yaml manifests/test.pp
```
