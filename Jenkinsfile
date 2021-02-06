pipeline
{
        agent any 
        stages
        {
            stage('Stage 1')
            {
                steps
                {
                    echo 'Hello Eli!' 
                }
            }
             stage('Stage 2')
             {
                steps
                {
                    input('do you want to proceed?')
                }
             }
            stage('Stage 3')
            {
                when
                {
					not
					{
						branch "master"
					 }
                }
                steps
                {
                    echo "hello"
                }
            }
    }
}
