@Library("mylibrary")_
pipeline
{
    agent any
    stages
    {
        stage('contDownload')
        {
            steps
            {
                script
                {
                    cicd.gitDownload("maven")
                }
            }
        }
     }
}     
