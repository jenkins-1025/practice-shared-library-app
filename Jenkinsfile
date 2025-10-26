@Library("practice-shared-library@main")_

import sans.jenkins.Output;

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
                    echo(author.name())
                    echo(author.address())
                }
            }
        }
    }
}