@Library("practice-shared-library@main")_

//import sans.jenkins.Output;

//mavenPipeline()

sansPipeline([
    type: "maven"
])

/*
pipeline {
    agent any
    stages {
        stage("Hello World") {
            steps{
                script{
                    hello.world()
                }
            }
        }
        stage("Hello Sans") {
            steps{
                script{
                    Output.hello(this, "M. Hasan")
                }
            }
        }
        stage("Global variable") {
            steps{
                script{
                    echo(author())
                    echo(author.name())
                    echo(author.address())
                }
            }
        }
        stage("Maven Build") {
            steps{
                script{
                    maven("clean compile")
                }
            }
        }
        stage("Maven Lists") {
            steps{
                script{
                    maven.list(["clean","compile","test"])
                }
            }
        }
        stage("Map Parameter") {
            steps{
                script{
                    person.person([
                        firstName: "M.",
                        lastName: "Hasan"
                    ])
                }
            }
        }
        stage("Library Resource") {
            steps{
                script{
                    def config = libraryResource("config/build.json")
                    echo(config)
                }
            }
        }
    }
}
*/