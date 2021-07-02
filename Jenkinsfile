try{
    node{
    stage('code checkout from github'){
        echo "Fetching code from git repo to jenkins directory"
        git 'https://github.com/mitranmukesh/batch10-1.git'
    }
    stage('zip package'){
    echo "ZIP"
    zip zipFile: 'Test.zip', dir:'\\workspace'
    echo "END - ZIP"
    }
    
}
