## Hi, I'm Lukasz

I'm London based, contractor, "Head of Magic and Wizardry" ( because job titles are overrated ).
Dealing with the cloud, kubernetes, microservices, and all the other buzzwords on a daily basis. Responsible for architecture, development, and maintenance of the systems which are running on the edge of the technology.
Most of my code is private ( either mine or business choice ) but bits which are public are free for grabs or contributions.

#### Bit of tech writing

* [Building the best telegram bot](https://itnext.io/building-best-telegram-bot-bbf905d09d74)
* [I broke my kubernetes cluster running on Raspberry Pi](https://itnext.io/i-broke-my-kubernetes-cluster-running-on-raspberry-pi-355234a24d)
* [Kubernetes, microservices and github actions deployments](https://itnext.io/unified-microservices-builds-using-github-actions-3442c4ee175e)
* [Building your home kubernetes cluster on Raspberry Pi](https://itnext.io/building-your-home-raspberry-pi-kubernetes-cluster-14eeeb3c521e)

You can also check out my other [medium articles](https://blog.raczylo.com/).

#### Selected public projects

* [Traefik OIDC plugin](https://github.com/lukaszraczylo/traefikoidc) - **Golang** Traefik OIDC plugin closely following OIDC specification with multi-provider support and enhanced configuration options.
* [Semantic Version Generator](https://github.com/lukaszraczylo/semver-generator) - **Golang** simple tool to generate semantic versioning based on the git history. It can be used as a standalone library or github action, simplifying the process.
* [Go Simple GraphQL library](https://github.com/lukaszraczylo/go-simple-graphql) - **Golang** simple graphql library, optimised for the maximum speed and minimum allocations. Unlike the other libraries - the queries are passed as they are, without types assignment which makes it much easier to use from the development perspective. Projects using this library easily handle tens of thousands of requests per second with minimal resources.
* [Kubernetes Jobs Manager Operator](https://github.com/lukaszraczylo/jobs-manager-operator) - **Golang** kubernetes operator to manage jobs in the kubernetes cluster. Its sole purpose of existence is to allow for advanced workflows to be executed in user specified order and with interlocked dependencies on groups / jobs.
* [GraphQL monitoring proxy](https://github.com/lukaszraczylo/graphql-monitoring-proxy) - **Golang** graphql proxy which allows for the generation of prometheus-friendly statistics on the execute queries. It allows for caching, the RO/RW separation, rate limiting, banning specific users, blocking schema introspection and so on - at the speed of light. It was developed as a protest against the Hasura team putting basic monitoring features behind the paywall, and extended with additional features from the paid version down the line. The proxy is hyper-optimised and running on the real-world production systems, serving tens of thousands of requests per second with 3cpu and 15mb of RAM on Raspberry Pi.
* [kportal - console TUI for port forwarding management](https://github.com/lukaszraczylo/kportal) - **Golang** client for port forwarding management within development environments. Define context / namespaces / services / ports to be forwarded to your local machine via code, start it up and it'll do the rest. It ensures that connections / portforwards are re-established in case pods dying or connection being interrupted for the smooth development experience.

#### Contact me

You can find me on [raczylo.com](https://raczylo.com) or on [linkedIn](https://www.linkedin.com/in/lukaszraczylo/).

#### Github statistics

[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com?user=lukaszraczylo)](https://git.io/streak-stats)

***Includes contributions within private repositories and projects***
