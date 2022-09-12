# Morito Ikeda

<img width="300" src="https://moricho.github.io/images/profile.jpg">

## Information
- Github: [https://github.com/moricho](https://github.com/moricho)
- Twitter: [https://twitter.com/\_moricho\_](https://twitter.com/_moricho_)
- SpeakerDeck: [https://speakerdeck.com/moricho](https://speakerdeck.com/moricho)
- Medium: [https://medium.com/@ikeda.morito](https://medium.com/@ikeda.morito)

## Tech Stack
- Go, Rust, React/Next, Solidity
- Terraform, Kubernetes, Docker
- GCP, AWS

## Employment History
- October, 2020 - September 2022: __Software engineer at Mercari__
  - Working at Platform group
    - Develop infrastructure and provide middleware and internal system across organization such as Mercari, Merpay, Mercoin
      - Developed temporary privilege granting system to promote Zero Touch Production. The objective was to reduce failure and security risks by avoiding direct human contact with the production environment, including SREs. Developed Kubernetes custom controller with Go and user interface with React.
      - Designed and developed cost visualization platform to optimize infrastructure resources and monetary costs.
      - Introduced policy audit system to enhance security of our Kubernetes infrastructure. 
- Augast 2020: __Software engineer intern at Cybozu__
  - Designed and implemented an automatic PVC resizer (Kubernetes CustomController) from scratch and publish it as OSS: [pvc-autoresizer](https://github.com/topolvm/pvc-autoresizer)
    -  `pvc-autoresizer` is an automatic volume resizer that edits PVCs if they have less than the specified amount of free filesystem capacity.
    - Implemented a Reconciler. For more detail: [pvc-autoresizer/docs/design.md](https://github.com/topolvm/pvc-autoresizer/blob/master/docs/design.md)
    - Implemented a Prometheus client used in `pvc-autoresizer` to collect logs from kubelet.
- December, 2019 - January, 2020: __Software engineer intern at AbemaTV__
  - Belonged to Ad Association of AbemaTV and participated in launch of a new big feature
  - Developed a few microservices in Go on Kubernetes
  - Improved observability, planned load test and built load environment for more production ready microservice.
    - Observability: introduced distributed tracing(OpenCensus/StackdriverTrace), profiling(pprof) and build monitoring system(Prometheus, Grafana).
    - Load test: made scenarios, prepared the production equivalent data, and got loads on the system with Locust
    - Performance tuning: tuned the performance of the application, Envoy parameter and pod replica size based on the load test
  - Developed a helper application with TypeScript, Cloud Function, Cloud Pub/Sub, Terraform, etc
- September, 2019 - October, 2019: __Software engineer intern at Recruit Technologies__
  - Replaced legacy system to new system using ECS Fargate
  - Build CI pipeline
- Augast, 2018 - January, 2019: __Software engineer intern at BASE__
  - Participated in launch of a new fintech business
  - Developed the API in Go (adopt TDD and Layered Architecture)
  - Introduce golangci-lint
  - Developed the frontend application in Vue.js collaborating with an designer
- __Others (subcontract)__
  - Developed server of blockchain service in Go on Kubernetes (for three months)
  - Developed application server with Django and build data processing system with AWS Lambda, S3, fluentd, etc. (for four months)

## Education
- April, 2016 - March, 2021: __Keio University, Faculty of Science and Engineering__

## OSS

#### Contributions
- __foundry__: [https://github.com/foundry-rs/foundry](https://github.com/foundry-rs/foundry)
- __gVisor__: [https://github.com/google/gvisor](https://github.com/google/gvisor)
  - [Add profiling option for debug](https://github.com/google/gvisor/pull/1951)
  - [Make mount type optional for bind mounts](https://github.com/google/gvisor/pull/2487)
  - [Support Epoller to forward oom score notifications](https://github.com/google/gvisor-containerd-shim/issues/56)
- __Rook__: [https://github.com/rook/rook](https://github.com/rook/rook)
  - [Move to Go Modules](https://github.com/rook/rook/pull/4984)
  - [Fix `codegen` to find boilerplate outside of the $GOPATH](https://github.com/rook/rook/pull/5110)
- __Firecracker__: [https://github.com/firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker)
  - [Remove dumbo's dependency on mmds](https://github.com/firecracker-microvm/firecracker/pull/1813)

## Publications
- Blog posts at Mercari
  - [Promote Zero Touch Production – further features of Carrier](https://engineering.mercari.com/en/blog/entry/20220201-promote-zero-touch-production-further-features-of-carrier/)
  - [Enhance Kubernetes Security with OPA Gatekeeper](https://engineering.mercari.com/en/blog/entry/20201222-enhance-kubernetes-security-with-opa-gatekeeper/)
- I'll publish e-book written about __container runtime__ from __Impress Corporation__. Now writing.
- __「Gopherの休日 2020冬: 第7章 コンテナランタイム自作入門」- 技術書典7__
  - An unpublished magazine. I contributed to __golang.tokyo__ community.

## Talks
- [Enhance Kubernetes Security with Gatekeeper](https://speakerdeck.com/moricho/enhance-kubernetes-security-with-gatekeeper)
  - Mercari Platform Group Tech Talk, 20min session
- I'll talk about `gVisor`, application kernel for containers, at CNDT2020. 20min session.
- [Deep Dive into Runtime Shim](https://speakerdeck.com/moricho/deep-dive-into-runtime-shim)
  - ContainerRuntime Meetup#2, 10min session
- [Recap: Zero Trust Service Mesh with Calico, SPIRE, and Envoy](https://speakerdeck.com/moricho/recap-zero-trust-service-mesh-with-calico-spire-and-envoy)
  - Envoy Meetup Tokyo#2, LT
- [gVisorで実現するこれからのコンテナセキュリティ](https://speakerdeck.com/moricho/gvisordeshi-xian-surukorekarafalsekontenasekiyuritei)
  - KubeFest Tokyo 2020, LT
- [Deep dive into sync.Pool](https://speakerdeck.com/moricho/deep-dive-into-sync-dot-pool)
  - golang.tokyo#29, 20min session
- Others can be found [here](https://speakerdeck.com/moricho)

## Qualifications
- __CKA__ - Certified Kubernetes Administrator

<img width="320" src="https://moricho.github.io/images/cka.png">
