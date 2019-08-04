node{
  stage('Clone sources') {
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '7d749c70-3473-41a9-897f-c0d43244b2ce', url: 'https://github.com/sushaws/FirstRepo.git']]])
    }
    stage('listing files')
    {
    sh "ls -a"
    }


}
