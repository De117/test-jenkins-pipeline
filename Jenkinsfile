node {
    checkout scm

    stage("Do something") {
        sh "whoami && groups && pwd && ls -al"
        echo "Trying to build another job"
        build(job: 'MobQualityDashboard', propagate: true, quietPeriod: 10, wait: true)
    }
}
