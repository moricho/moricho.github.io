# Morito Ikeda

<img width="300" src="https://moricho.github.io/images/profile.jpg">

## Information

- Github: [https://github.com/moricho](https://github.com/moricho)
- Twitter: [https://twitter.com/\_moricho\_](https://twitter.com/_moricho_)
- SpeakerDeck: [https://speakerdeck.com/moricho](https://speakerdeck.com/moricho)
- Medium: [https://medium.com/@ikeda.morito](https://medium.com/@ikeda.morito)
- ENS: m0r1ch0.eth
- Warpcast: [https://warpcast.com/m0r1t0](https://warpcast.com/m0r1t0)

## Tech Stack

- Go, Rust, Node.js/TypeScript, Solidity, React/Next.js
- Terraform, Kubernetes, Docker
- GCP, AWS

## Employment History

- September, 2022 - : Freelance
  - July, 2023 - Current: **Tech Lead at a crypto hedge fund**
    - Designed and developed a high performance and secure trading system using Rust, Solidity and GCP/GKE.
    - CI/CD arrangements to improve development agility
    - Developing Observability infrastructure using Datadog, etc.
    - Project management of a small team and code reviews. Responsible for improving the productivity of the developers and ensuring the quality and speed of the team's output.
    - Researched on MEV/Flashbots and incorporated them into actual strategies. Also doing research on relatively new DeFi protocols such as interest rates and perpetuals.
  - April, 2023 - November, 2023: **Software engineer at [Phi](https://twitter.com/phi_xyz)**
    - Created Quests using Ethers.js/Typescript. Worked on a feature to mint the user's on-chain history as an identity with integrating to smart contracts of other prtocols (DeFi protocols such as Timeswap and sudoswap and other famous projects such as Mirror and Lens).
    - Formulated new feature specifications, designed architecture, and developed using Typescript and AWS.
    - Designed and developed wallet authentication system.
    - Analyzed the effectiveness of the measures by Dune and created a dashboard.
- October, 2020 - September, 2022: **Software engineer at [Mercari](https://www.mercari.com/)**
  - Worked at Platform group
    - Develop infrastructure and provide middleware and internal system across organization such as Mercari, Merpay, Mercoin
      - Developed temporary privilege granting system to promote Zero Touch Production. The objective was to reduce failure and security risks by avoiding direct human contact with the production environment, including SREs. Developed Kubernetes custom controller with Go and user interface with React.
      - Designed and developed cost visualization platform to optimize infrastructure resources and monetary costs.
      - Introduced policy audit system to enhance security of our Kubernetes infrastructure.

### Others

- **AbemaTV**
  - Belonged to Ad Association of AbemaTV and participated in launch of a new big feature
  - Developed a few microservices in Go on Kubernetes
  - Improved observability, planned load test and built load environment for more production ready microservice.
    - Observability: introduced distributed tracing(OpenCensus/StackdriverTrace), profiling(pprof) and build monitoring system(Prometheus, Grafana).
    - Load test: made scenarios, prepared the production equivalent data, and got loads on the system with Locust
    - Performance tuning: tuned the performance of the application, Envoy parameter and pod replica size based on the load test
  - Developed a helper application with TypeScript, Cloud Function, Cloud Pub/Sub, Terraform, etc
- **BASE**
  - Participated in launch of a new fintech business
  - Developed the API in Go (adopt TDD and Layered Architecture)
  - Introduce golangci-lint
  - Developed the frontend application in Vue.js collaborating with an designer

## OSS

- **tparallel**: [https://github.com/moricho/tparallel](https://github.com/moricho/tparallel)
  - Static code analysis tool that finds inappropriate usage of `t.Parallel()` method in your Go test codes
  - Integrated in [golangci-lint](https://github.com/golangci/golangci-lint), which is a most popular linter for Go

#### Contributions

- **alloy-rs/alloy**: [https://github.com/alloy-rs/alloy](https://github.com/alloy-rs/alloy)
  - Transports, Middleware, and Networks for the Alloy project
- **alloy-rs/core**: [https://github.com/alloy-rs/core](https://github.com/alloy-rs/core)
  - High-performance, well-tested & documented core libraries for Ethereum, in Rust
- **foundry-rs/foundry**: [https://github.com/foundry-rs/foundry](https://github.com/foundry-rs/foundry)
  - Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.
- **google-cloud-rust**: [https://github.com/yoshidan/google-cloud-rust](https://github.com/yoshidan/google-cloud-rust)
  - Google Cloud Client Libraries for Rust.
- **google/gvisor**: [https://github.com/google/gvisor](https://github.com/google/gvisor)
  - An application kernel, written in Go, that implements a substantial portion of the Linux system surface. Used in container services in GCP such as Cloud Run and GKE.
- **firecracker-microvm/firecracker**: [https://github.com/firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker)
  - Secure and fast microVMs for serverless computing. Used in container services in AWS such as AWS Lambda.

## Hackathon

- ETH Global Tokyo 2023
  - Granted by Lens and Lit Protocol

## Publications

- Blog posts at Mercari
  - [Promote Zero Touch Production – further features of Carrier](https://engineering.mercari.com/en/blog/entry/20220201-promote-zero-touch-production-further-features-of-carrier/)
  - [Enhance Kubernetes Security with OPA Gatekeeper](https://engineering.mercari.com/en/blog/entry/20201222-enhance-kubernetes-security-with-opa-gatekeeper/)
- I'll publish e-book written about **container runtime** from **Impress Corporation**. Now writing.
- **「Gopher の休日 2020 冬: 第 7 章 コンテナランタイム自作入門」- 技術書典 7**
  - An unpublished magazine. I contributed to **golang.tokyo** community.

## Talks

- [Enhance Kubernetes Security with Gatekeeper](https://speakerdeck.com/moricho/enhance-kubernetes-security-with-gatekeeper)
  - Mercari Platform Group Tech Talk, 20min session
- I'll talk about `gVisor`, application kernel for containers, at CNDT2020. 20min session.
- [Deep Dive into Runtime Shim](https://speakerdeck.com/moricho/deep-dive-into-runtime-shim)
  - ContainerRuntime Meetup#2, 10min session
- [Recap: Zero Trust Service Mesh with Calico, SPIRE, and Envoy](https://speakerdeck.com/moricho/recap-zero-trust-service-mesh-with-calico-spire-and-envoy)
  - Envoy Meetup Tokyo#2, LT
- [gVisor で実現するこれからのコンテナセキュリティ](https://speakerdeck.com/moricho/gvisordeshi-xian-surukorekarafalsekontenasekiyuritei)
  - KubeFest Tokyo 2020, LT
- [Deep dive into sync.Pool](https://speakerdeck.com/moricho/deep-dive-into-sync-dot-pool)
  - golang.tokyo#29, 20min session
- Others can be found [here](https://speakerdeck.com/moricho)

## Qualifications

- **CKA** - Certified Kubernetes Administrator

<img width="320" src="https://moricho.github.io/images/cka.png">

## Education

- April, 2016 - March, 2021: **Keio University, Faculty of Science and Engineering**
