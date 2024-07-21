pipeline {
    agent any

    stages {
        stage('Unit Test') {
            steps {
                echo 'Using TestNG'
                echo 'Adharcard Number is $ADHARCARDNUMBER'
            }
        }
        stage('Static Analysys') {
            steps {
                echo 'Using Sonar Cube'
            }
        }
        stage('Build') {
            steps {
                echo 'Using Maven'
            }
        }
        stage('Test') {
            steps {
                echo 'Using Selenium'
            }
        }
    }
}
