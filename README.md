# ndn-DemoApps
Demo Applications for Named Data Networking

used:
	ndn-cxx version 0.3.4 (http://named-data.net/)
	nfd	version 0.3.4 (http://named-data.net/)
	libdash ...


Scenarios:
	Samuel L.  (using placeholder text from http://slipsum.com/ :-D )
		nfd-start
		./producer --prefix /ndn101 --document-root ../res --data-size 100
		./consumer --name /ndn101/samuel.txt/0

![test](https://cloud.githubusercontent.com/assets/16044516/17676830/75647828-6330-11e6-83f5-5bb19d5f9575.png)
