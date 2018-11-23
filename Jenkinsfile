pipeline {
    # agent { docker { image 'maven:3.3.3' } }

  agent any

            stages {
                stage('one build') {
                  steps {
                sh 'mvn --version'
                        }
                                }

                                stage('two test') {
                                  steps {
                                sh 'mvn --version'
                                        }
                                                }
                                                stage('3 prod') {
                                                  steps {
                                                sh 'mvn --version'
                                                        }
                                                                }




                    }


}
