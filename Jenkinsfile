pipeline {
    agent any

    stages {

        stage('Cleanup') {
            steps {
                echo 'heloo'
            }
        }


        stage('Pause for Demo (Blue Live)') {
            steps {
                input message: '🔵 Blue is live! Check http://localhost. Click "Proceed" to switch to Green.'
            }
        }

    }
}
