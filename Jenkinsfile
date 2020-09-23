node {
stage ('git clone') {
checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'd1a55f22-4541-4155-9704-27d7097066a2']]])
}
}
