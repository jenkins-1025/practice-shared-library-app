@Library("practice-shared-library@main")_

import sans.jenkins.Output;

pipeline {
    agent any
    stages {
        stage("Hello Sans") {
            steps{
                script{
                    Output.hello(this, "M. Hasan")
                }
            }
        }
        stage("Hello World") {
            steps{
                script{
                    hello.world()
                }
            }
        }
    }
}