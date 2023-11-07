pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                dir('C:/Users/sqwjng/Desktop/Jenkins/Day2/build.bat') {
                    /* execute commands in the scripts directory */
                }
            bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/build.bat'
            }
        }
        stage('Test') {
            steps {
                dir('C:/Users/sqwjng/Desktop/Jenkins/Day2/test.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/test.bat'
            }
        }
      stage('Package') {
            steps {
                dir('C:/Users/sqwjng/Desktop/Jenkins/Day2/publish.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/publish.bat'
            }
        }
        stage('Deploy') {
            steps {
                dir('C:/Users/sqwjng/Desktop/Jenkins/Day2/publish.bat') {
                    /* execute commands in the scripts directory */
                }
                bat 'C:/Users/sqwjng/Desktop/Jenkins/Day2/publish.bat'
            }
        }
    }
}
