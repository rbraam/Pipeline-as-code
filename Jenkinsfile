#!groovy​

parallel 'para1':{
	node(){
		stage 'stage 1.1'
			echo 'bla2'
		stage 'stage 1.2'
			echo 'bla2'
	}
}, 'para2':{
	node(){
		stage 'stage 2.1'
			echo 'bla2'
		stage 'stage 2.2'
			echo 'bla2'
	}
}