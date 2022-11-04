Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                fileOperations([fileCopyOperation(
                excludes: '',
                flattenFiles: false,
                includes: 'C:\\TP\\QueryCSV\KL02.parquet',
                targetLocation: "C:\\TP\\training_website"
                )])
            }
        }
    }
}
