pipeline {
 agent any
  
  stages {
  stage('Maven Install') {
    steps {
      withMaven(globalMavenSettingsConfig: '--- Use system default settings or file path ---', jdk: '--- Use system default JDK ---', maven: '--- Use system default Maven ---', mavenSettingsConfig: '--- Use system default settings or file path ---') {
       sh 'mvn clean install'
}
    }
  }

}

}
