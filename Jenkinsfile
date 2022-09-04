node {
    stage ("execute"){
        bat 'docker build -t Dockerfile . '
        bat 'docker run -dit --name my-running-app -p 8080:80 Dockerfile'   
    }
}
