pipeline {
    agent any

    stages {
        stage('1. Checkout Code') {
            steps {
                // Git에서 코드를 가져오는 단계입니다.
                // checkout scm이라는 명령어가 자동으로 연결된 Git 저장소를 바라봅니다.
                checkout scm

                // 잘 가져왔는지 파일 목록을 출력해봅니다.
                sh 'ls -al' 
            }
        }

        stage('2. Build Test') {
            steps {
                echo '이곳은 빌드 및 테스트가 진행될 단계입니다.'
                echo '현재는 연결 테스트 중입니다.'
            }
        }
    }
}
