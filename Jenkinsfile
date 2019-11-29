node {
    checkout scm

    stage("Do something") {
        sh "whoami && groups && pwd && ls -al"
    }

    stage("Do something else") {
        sh "ls -al /var/lib/jenkins/secrets"
        sh "cat /var/lib/jenkins/secrets/master.key | wc"
    }
}
