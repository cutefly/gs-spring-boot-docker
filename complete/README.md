spring boot docker sample

$ docker run -e "SPRING_PROFILES_ACTIVE=development" -p 8080:8080 --name gs-spring-boot-development -t registry.kpcard.co.kr/gs-spring-boot-docker
$ docker run -e "SPRING_PROFILES_ACTIVE=production" -p 8080:8080 --name gs-spring-boot-production -t registry.kpcard.co.kr/gs-spring-boot-docker

$ docker start gs-spring-boot-development
$ docker start gs-spring-boot-production
