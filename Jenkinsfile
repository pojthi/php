node {
    stage ("execute"){
        bat 'docker build -t apache_image:1.0 . '
        bat 'docker run --name myapache -d -p 80:80 apache_image:1.0'
        bat 'start http://localhost'
    }
}
