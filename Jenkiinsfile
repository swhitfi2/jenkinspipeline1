pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'I am building step one"                

            }
        }
        stage('Test') {
            steps {
                echo Please enter a number?
read number

count=0

while [ $count -le $number ]
do
	echo $count
if [ $(( $count % 2)) -eq 0 ] #count [ $number / 2  | e 0 ]
	then
		echo "this number is even"
	else echo "this number is odd"
	fi
	(( count++ ))
	#echo $count

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
