pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Renu-Kumar-M/jenkins3.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python -m py_compile app.py'
                echo 'Build successful: app.py compiled with no syntax errors'
            }
        }

       stage('Build') {
    steps {
        bat '"C:\\Users\\YourUser\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" -m py_compile app.py'
    }
}

    }
}
