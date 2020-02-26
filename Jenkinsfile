node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'hanupavan') {

        def customImage = docker.build("aa6432763c11/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}