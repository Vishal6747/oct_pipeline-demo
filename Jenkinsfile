pipeline
{
agent any
stages
{ stage ('scm checkout')
   { 
       steps (sh 'echo code-is-downloading') 
    }

   stage ('create deployable package')
   { 
       steps (sh 'echo created-artifacts')
    }

}
}