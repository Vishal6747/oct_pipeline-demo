pipeline
{
agent any
stages
{ stage ('scm checkout')
   { 
      steps {sh 'echo code-is-downloading'}
    }

   stage ('create deployable package')
   { 
      steps {sh 'echo created-artifacts'}
    }
 stage('create devlopment')
 { 
    steps{sh 'echo development'}
 }
 stage('create qa')
 {
     steps{sh 'echo qa'}
 }

}
}
