 {
    agent any

    stapipelineges {
        stage('Build') {
            steps {
                echo 'I am building step one'                
            }
        }
        stage('Test') {
            steps {
                
                for i in {1..10}
                    do
                    
                    echo $i
                    done

                
            }
        }
        stage('Deploy') {
            steps {
                echo 'We are deploying our code now'
                
            }
        }
    }
}
