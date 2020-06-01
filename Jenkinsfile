#!groovy
@Library('jenkins-pipeline') import com.github.jcustenborder.jenkins.pipeline.DockerPipeline

def pipe = new DockerPipeline()
pipe.imageName = 'jenkins-maven-jdk8'
pipe.majorVersion = 0
pipe.minorVersion = 0
pipe.repositories = [
        'custenborder_docker': 'docker.custenborder.com/jcustenborder'
]
pipe.execute()