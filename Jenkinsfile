
    node{
    stage('code checkout from github'){
        echo "Fetching code from git repo to jenkins directory"
        git 'https://github.com/mitranmukesh/CI-with-Jenkins-in-AWS-Demo.git'
    }
    stage('zip package'){
    echo "ZIP"
    zip zipFile: 'Test.zip'
    echo "END - ZIP"
    }
    } 
