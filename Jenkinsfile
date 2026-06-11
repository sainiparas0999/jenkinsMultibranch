pipeline{
    agent{
        label 'worker'
    }
    stages{
        stage('sending email'){
            steps{
                mail(
                    to: 'paras000@sharklasers.com',
                    subject: 'hello',
                    body: 'Aur bhai kya haal chal hai'
                )
            }
        }
    }
}
