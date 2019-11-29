node {
    checkout scm

    stage("Do something") {
        sh "whoami && groups && pwd && ls -al"
    }

    stage("Do something else") {
        sh "ls -l /var/lib/jenkins/secrets"
    }
}
