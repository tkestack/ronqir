`ronqir` - rust implementation of Kubernetes Container Runtime Interface
## What is `ronqir`
`ronqir` is a new implementation for Kubernetes CRI written by rust. It pursues extremely high security and extreme performance, and strives to meet some scenarios with high security and performance requirements. Other similar implementations are cri-o, containerd or podman, which are all writen by golang.

## About the name
`ronqir` is pronounced as `/rɔ:ŋtʃi/`. The inspiration comes from Chinese pingyin `rong qi`, which means container in Chinese language.

## What is the scope
`ronqir` is meant to implement the Kubernetes Container Runtime Interface using rust. *This is not just another cri runtime.* Our vision is to take marvellous advantages of rust to build a runtime with high security, stability and performance.

It uses OCI related projects and libraries for different aspects:
- OCI runtime: youki (an implementation of runtime-spec in Rust, referring to runc, https://github.com/containers/youki)
- container lib in Rust: containrs(a new general purpose container library written in Rust, https://github.com/cri-o/containrs)

## Status of `ronqir`
The project is still in the design and prototype development stage, and a verification version is expected to be released soon.

## License
`ronqir` is licensed under the [Apache License 2.0](./LICENSE) license.
