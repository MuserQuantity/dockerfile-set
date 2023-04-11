# dockerfile-set
A bundle of dockerfiles for creating different environments.

## truffle
### environment
* python2 2.7.16
* python3 3.7.3
* nodejs 18.15.0
* truffle@5.8.2
* @truffle/hdwallet-provider@2.1.9
* solc@0.8.4
* @openzeppelin/contracts@4.8.2
### how to run
`docker run -dit -v /path/to/your/workspace/:/etc/truffle/ --name truffle truffle:5.8.2 /bin/bash`