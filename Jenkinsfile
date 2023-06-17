pipeline {
    agent any {
        stages {
            stage ('init') {
                steps {
                echo 'Hi. this is Zamoyoni from Ezra'
                echo 'We are starting the Testing'
            }
            }
            stage ('Build') {
                steps {
                echo 'Building sample Maven Project'
            }
            
            }
            stage ('Deploy') {
                steps {
                    echo 'Deploying inn staging Area'
                }
            stage ('Deploy Production') {
                steps {
                    echo 'Deploying in Production Area'
                }
            }
            
        }

    }
}