node {

stage 'git checkout'
git 'https://github.com/dkaug10/DevOps-Training.git'


stage 'clean'
sh 'mvn clean'

stage 'compile'
sh 'mvn compile'

stage 'test'
sh 'mvn test'

stage 'package'
sh 'mvn package'

stage 'artifacts'
archiveArtifacts 'target/*.war'

}
