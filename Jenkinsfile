pipeline{
    agent any

    triggers{
        pollSCM('* * * * *')
    }
        stages{

            stage('whoami'){
                steps{
                    echo "my name is kira"
                    touch file.txt
                }
            }
            stage('how old'){
                steps{
                    echo "I am 23 years old"
                }
            }

            stage('what i want'){
                steps{
                    echo "Alll i want is to be so rich that i can go where i want"
                }
            }
        }
    
}