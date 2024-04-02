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
  - April, 2023 - November, 2023: **Software engineer at [Phi](https://twitter.com/phi_xyz)**
    - Created Quests using Ethers.js/Typescript. Quests - a feature to mint the user's on-chain history as an identity integrating with other protocol's contracts.
    - Formulated new feature specifications, designed architecture, and developed using Typescript and AWS.
    - Designed and developed wallet authentication system.
    - Analyzed the effectiveness of the measures by Dune and created a dashboard.
- October, 2020 - September, 2022: **Software engineer at Mercari**
  - Worked at Platform group
    - Develop infrastructure and provide middleware and internal system across organization such as Mercari, Merpay, Mercoin
      - Developed temporary privilege granting system to promote Zero Touch Production. The objective was to reduce failure and security risks by avoiding direct human contact with the production environment, including SREs. Developed Kubernetes custom controller with Go and user interface with React.
      - Designed and developed cost visualization platform to optimize infrastructure resources and monetary costs.
      - Introduced policy audit system to enhance security of our Kubernetes infrastructure.
- You can see more my engineering experience at [Subcontract section](###Subcontract)

### Experience in web3

- Frontend and backend development for a fashion NFT launchpad
  - Designed and developed contracts and web frontend, built AWS infrastructure, etc.
- Backend development for a BCG
  - Developed game backend, built an indexer to sync on-chain data, etc.
- Backend development for a wallet service

### Subcontract

- **Cybozu**
  - Designed and implemented an automatic PVC resizer (Kubernetes CustomController) from scratch and publish it as OSS: [pvc-autoresizer](https://github.com/topolvm/pvc-autoresizer)
    - `pvc-autoresizer` is an automatic volume resizer that edits PVCs if they have less than the specified amount of free filesystem capacity.
    - Implemented a Reconciler. For more detail: [pvc-autoresizer/docs/design.md](https://github.com/topolvm/pvc-autoresizer/blob/master/docs/design.md)
    - Implemented a Prometheus client used in `pvc-autoresizer` to collect logs from kubelet.
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

## Education

- April, 2016 - March, 2021: **Keio University, Faculty of Science and Engineering**

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
