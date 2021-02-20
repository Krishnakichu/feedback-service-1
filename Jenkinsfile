node {
    checkout scm

        def customImage = docker.build("krishcode/feedback-service1:${env.BUILD_ID}")

        /* Push the container to the custom Registry */
        customImage.push()
}