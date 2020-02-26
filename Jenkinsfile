node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'hanupavan') {

        def customImage = docker.build("hanu/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}