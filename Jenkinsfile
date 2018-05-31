pipeline {

 

    agent any

               parameters {

        string(defaultValue: "", description: 'What environment?', name: 'Environment')

        // choices are newline separated

        choice(choices: 'US-EAST-1\nUS-WEST-2', description: 'What AWS region?', name: 'region')

    }

    tools {

        maven 'Your Maven Name'

        jdk 'Your JDK Name'

    }

    stages {

        stage ('Checkout'){

            steps

                                                {

                                                                git (

                                                                                url: 'https://github.com/sreedhar2/sample.git',

                                                                                credentialsId: 'daee74e7-4459-429a-a658-8c1f79849e01'

                                                                )

                                                }

                                               

            }

                               

    }

}