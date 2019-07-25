pipeline {
    agent any
    stages {
        
        stage ('Compile Stage') {
            steps {
                echo "file has been changed"
		echo "This is compile stage"
            }
        }

        stage ('Testing Stage') {
            steps {
                echo "This is test stage"
		echo "This stage has also been changed"
            }
        }


        stage ('Deployment Stage') {
            steps {
                echo "This is deployment stage"
            }
        }
    }
}
