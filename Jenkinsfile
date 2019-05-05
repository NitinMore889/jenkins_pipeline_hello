node {
    stage('build'){
        echo "building"
    }
}
node {
    stage('test'){
        echo "testing"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }
}
stage('Get approval'){
    input "Deploy to Preprod?"
}
node {
    stage('deploy to Preprod'){
        echo "deploying to Prepod"
    }
}
