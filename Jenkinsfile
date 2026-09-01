
pipeline {
    // Specifies where the pipeline or specific stages will execute (any available agent/node)
    agent any 

stages {
        stage('build') {
            steps {
             sh 'touc demo.py' 
            }
        }

      stage('test') {
            steps {
             sh 'python3 test.py' 
            }
        }

}
}
