#!groovy​

stage 'stage 1'
	echo 'bla1'

stage 'stage 2.1'
	parallel firstBranch: {
		echo '2.1 firstBranch'
	}, secondBranch: {
		echo '2.2 secondBranch'
	},
	failFast: true
stage 'stage 2.2'
	echo 'bla2'
