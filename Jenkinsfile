pipeline{
	agent any
    stages {
       stage('Upload to AWS') {
       stage('Build') {
             steps {
                 sh 'echo "Hello World"'
                 sh '''
					echo "Multiline shell steps works too"
					ls -lah
				 '''
                 }
             }
        }
    }
}
