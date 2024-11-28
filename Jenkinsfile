//@Library('Shared')_
pipeline{
    agent any
    
    stages{
        stage("Code clone"){
            steps{
                clone("https://github.com/LondheShubham153/django-notes-app.git","main")
                echo "Cloned successfully"
            }
        }
        stage("Build"){
            steps{
                //dockerbuild("notes-app","latest")
                echo "Build successful"
            }
        }
        stage("Test"){
            steps{
                //dockerpush("dockerHubCreds","notes-app","latest")
                echo "test successful"
            }
        }
        stage("Deploy"){
            steps{
                //deploy()
                echo "Deploy Successful"
            }
        }
        
    }
}
