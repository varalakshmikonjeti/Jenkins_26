pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/varalakshmikonjeti/Jenkins_26.git"
              }
}
        stage('run')
        {
         steps
            {
             sh "java Demo.java"
             sh "python3 main.py"
             }
        }
       
      }//stages
      }//pipeline
