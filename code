
pipeline {
    agent any
    environment {
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
    }
    stages{
        stage('git clone') {
            steps{
                git 'https://github.com/Nawabu-Sujatha/maven-web-app.git'
            }
        }
        stage('build maven') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage('build docker image') {
            steps{
                sh 'docker build -t poharvasavi/pipeline:$BUILD_NUMBER .'
            }
        }
        stage('login to dockerhub') {
            steps{
                sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
            }
        }
        stage('push image') {
            steps{
                sh 'docker push poharvasavi/pipeline:$BUILD_NUMBER'
            }
        }
        stage('create a container') {
            steps{
                sh 'docker run -itd --name pipeline-cont -p 80:80 6845e29d4e5b'
            }
        }
    }
}pipeline {
    agent any
    environment {
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
    }
    stages{
        stage('git clone') {
            steps{
                git 'https://github.com/Nawabu-Sujatha/maven-web-app.git'
            }
        }
        stage('build maven') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage('build docker image') {
            steps{
                sh 'docker build -t poharvasavi/pipeline:$BUILD_NUMBER .'
            }
        }
        stage('login to dockerhub') {
            steps{
                sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
            }
        }
        stage('push image') {
            steps{
                sh 'docker push poharvasavi/pipeline:$BUILD_NUMBER'
            }
        }
        stage('create a container') {
            steps{
                sh 'docker run -itd --name pipeline-cont -p 80:80 6845e29d4e5b'
            }
        }
    }
}pipeline {
    agent any
    environment {
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
    }
    stages{
        stage('git clone') {
            steps{
                git 'https://github.com/Nawabu-Sujatha/maven-web-app.git'
            }
        }
        stage('build maven') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage('build docker image') {
            steps{
                sh 'docker build -t poharvasavi/pipeline:$BUILD_NUMBER .'
            }
        }
        stage('login to dockerhub') {
            steps{
                sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
            }
        }
        stage('push image') {
            steps{
                sh 'docker push poharvasavi/pipeline:$BUILD_NUMBER'
            }
        }
        stage('create a container') {
            steps{
                sh 'docker run -itd --name pipeline-cont -p 80:80 6845e29d4e5b'
            }
        }
    }
}pipeline {
    agent any
    environment {
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
    }
    stages{
        stage('git clone') {
            steps{
                git 'https://github.com/Nawabu-Sujatha/maven-web-app.git'
            }
        }
        stage('build maven') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage('build docker image') {
            steps{
                sh 'docker build -t poharvasavi/pipeline:$BUILD_NUMBER .'
            }
        }
        stage('login to dockerhub') {
            steps{
                sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
            }
        }
        stage('push image') {
            steps{
                sh 'docker push poharvasavi/pipeline:$BUILD_NUMBER'
            }
        }
        stage('create a container') {
            steps{
                sh 'docker run -itd --name pipeline-cont -p 80:80 6845e29d4e5b'
            }
        }
    }
}pipeline {
    agent any
    environment {
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
    }
    stages{
        stage('git clone') {
            steps{
                git 'https://github.com/Nawabu-Sujatha/maven-web-app.git'
            }
        }
        stage('build maven') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage('build docker image') {
            steps{
                sh 'docker build -t poharvasavi/pipeline:$BUILD_NUMBER .'
            }
        }
        stage('login to dockerhub') {
            steps{
                sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
            }
        }
        stage('push image') {
            steps{
                sh 'docker push poharvasavi/pipeline:$BUILD_NUMBER'
            }
        }
        stage('create a container') {
            steps{
                sh 'docker run -itd --name pipeline-cont -p 80:80 6845e29d4e5b'
            }
        }
    }
}pipeline {
    agent any
    environment {
        DOCKERHUB_CREDENTIALS = credentials('dockerhub')
    }
    stages{
        stage('git clone') {
            steps{
                git 'https://github.com/Nawabu-Sujatha/maven-web-app.git'
            }
        }
        stage('build maven') {
            steps{
                sh 'mvn clean package'
            }
        }
        stage('build docker image') {
            steps{
                sh 'docker build -t poharvasavi/pipeline:$BUILD_NUMBER .'
            }
        }
        stage('login to dockerhub') {
            steps{
                sh 'echo $DOCKERHUB_CREDENTIALS_PSW | docker login -u $DOCKERHUB_CREDENTIALS_USR --password-stdin'
            }
        }
        stage('push image') {
            steps{
                sh 'docker push poharvasavi/pipeline:$BUILD_NUMBER'
            }
        }
        stage('create a container') {
            steps{
                sh 'docker run -itd --name pipeline-cont -p 80:80 6845e29d4e5b'
            }
        }
    }
}
