node {
    stage('clone') {
        sh label: '', script: 'rm -rf * && git clone https://github.com/Tixness/test2'            }
    stage('build') {
        sh label: '', script: 'cd test2/ && javac Main.java'
        }
    stage('run') {
        sh label: '', script: 'cd test2/ && java Main'
        }
    }
