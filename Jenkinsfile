pipeline
{
    agent any
    stages
    {
        stage('Downloade')
        {
            steps
            {
                script
                {
                    try
                    {
                      git 'https://github.com/vennusiva/Multibranchpipeline.git'
                    }
                    catch(Exception e1)
                    {
                        mail bcc: '', body: 'Download fail ', cc: '', from: '', replyTo: '', subject: 'Download fail', to: 'git.admin@gmail.com'
                        exit(1)
                    }
                }

            }
        }
	}
	}
