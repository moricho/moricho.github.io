# Morito Ikeda

<img width="300" src="https://moricho.github.io/images/kuma.jpeg">

## Information
- Github: [https://github.com/moricho](https://github.com/moricho)
- Twitter: [https://twitter.com/\_moricho\_](https://twitter.com/_moricho_)
- SpeakerDeck: [https://speakerdeck.com/moricho](https://speakerdeck.com/moricho)
- Medium: [https://medium.com/@ikeda.morito](https://medium.com/@ikeda.morito)

## Employment History
- Augast 2020: __software engineer intern at Cybozu__
  - designed and implemented an automatic PVC resizer (Kubernetes CustomController) from scratch and publish it as OSS: [pvc-autoresizer](https://github.com/topolvm/pvc-autoresizer)
    -  `pvc-autoresizer` is an automatic volume resizer that edits PVCs if they have less than the specified amount of free filesystem capacity.
    - implemented a Reconciler. For more detail: [pvc-autoresizer/docs/design.md](https://github.com/topolvm/pvc-autoresizer/blob/master/docs/design.md)
    - implemented a Prometheus client used in `pvc-autoresizer` to collect logs from kubelet.
- December, 2019 - January, 2020: __software engineer intern at AbemaTV__
  - belonged to Ad Association of AbemaTV and participated in launch of a new big feature
  - developed a few microservices in Go on Kubernetes
  - improved observability, planned load test and built load environment for more production ready microservice.
    - observability: introduced distributed tracing(OpenCensus/StackdriverTrace), profiling(pprof) and build monitoring system(Prometheus, Grafana).
    - load test: made scenarios, prepared the production equivalent data, and got loads on the system with Locust
    - tuning: tuned the performance of the application, Envoy parameter and pod replica size based on the load test
  - developed a helper application with TypeScript, Cloud Function, Cloud Pub/Sub, Terraform, etc
- September, 2019 - October, 2019: __software engineer intern at Recruit Technologies__
  - replaced legacy system to new system using ECS Fargate
  - build CI pipeline
- Augast, 2018 - January, 2019: __software engineer intern at BASE__
  - participated in launch of a new fintech business
  - developed the API in Go (adopt TDD and Layered Architecture)
  - introduce golangci-lint
  - developed the frontend application in Vue.js collaborating with an designer
- __Others (subcontract)__
  - developed server of blockchain service in Go on Kubernetes (for three months)
  - developed application server with Django and build data processing system with AWS Lambda, S3, fluentd, etc. (for four months)

## Education
- April, 2016 - Current: __Keio University, Faculty of Science and Engineering__

## OSS

#### contributions
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
- I'll publish e-book written about __container runtime__ from __Impress Corporation__. Now writing.
- __「Gopherの休日 2020冬: 第7章 コンテナランタイム自作入門」- 技術書典7__
  - Just a unpublished magazine. I contributed to __golang.tokyo__ community.

## Talks
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
