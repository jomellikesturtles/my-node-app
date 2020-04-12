node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("145099743252137218288881570337/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
