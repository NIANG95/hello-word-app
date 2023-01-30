pipeline {
agent any
stages {
stage ('Compile Stage') {
steps {
    sh 'mvn --version'
    sh 'mvn clean install'
}
}
}
}