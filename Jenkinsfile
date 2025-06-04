pipeline
{
agent any
stages
{
 stage('scm checkout') {
            steps {
            git 'https://github.com/chinmay954/12.git'  
            }
        }





 stage('code compile')
 {steps { withMaven(globalMavenSettingsConfig: '', jdk: 'JAVA_HOME', maven: 'MAVEN_HOME', mavenSettingsConfig: '', traceability: true)  {
    sh 'mvn compile'
 } }}


}}
