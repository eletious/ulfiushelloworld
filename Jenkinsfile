pipeline {
  agent any
  stages {
	stage('build') {
	  steps {
		echo 'Building - test jenkins'
		sh 'cc -o test helloworldulfius.c /usr/local/lib/libulfius.so'
      }
    }
  }
}
