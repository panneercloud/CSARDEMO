pipeline {
agent any


stages {
stage('Verify GitHub Metadata') {
steps {
sh '''
echo "Repo URL : $GIT_URL"
echo "Branch : $GIT_BRANCH"
echo "Commit SHA : $GIT_COMMIT"
echo "Job Name : $JOB_NAME"
echo "Build Number : $BUILD_NUMBER"
'''
}
}
}
}
