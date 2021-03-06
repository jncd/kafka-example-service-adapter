# kafka-example-service-adapter

This project relies on the Pivotal Services SDK, available to customers and partners for download at [network.pivotal.io](http://network.pivotal.io)

---

An example of an [on-demand broker](http://docs.pivotal.io/on-demand-service-broker) service adapter for Kafka.

[Example BOSH release](https://github.com/pivotal-cf-experimental/kafka-example-service-adapter-release) for this service adapter.

**This is intended as an example and should not be used in production.**

---

## Development

1. If you haven't already arrived in this repository as a submodule of [its bosh release](https://github.com/pivotal-cf-experimental/kafka-example-service-adapter-release), then `go get github.com/pivotal-cf-experimental/kafka-example-service-adapter`
1. Install [Ginkgo](https://onsi.github.io/ginkgo/) if you haven't already: `go get github.com/onsi/ginkgo/ginkgo`
1. `cd $GOPATH/src/github.com/pivotal-cf-experimental/kafka-example-service-adapter`
1. `./scripts/run-tests.sh`

---

README - PIVOTAL SDK - MODIFIABLE CODE NOTICE

The contents of this GitHub repository available at https://github.com/pivotal-cf-experimental/kafka-example-service-adapter are licensed to you
under the terms of the Pivotal Software Development Kit License Agreement ("SDK EULA")
and are designated by Pivotal Software, Inc. as "Modifiable Code."

Your rights to distribute, modify or create derivative works of all or portions of this
Modifiable Code are described in the Pivotal Software Development Kit License Agreement
("SDK EULA") and this Modifiable Code may only be used in accordance with the terms and
conditions of the SDK EULA.

Unless required by applicable law or agreed to in writing, this Modifiable Code is
provided on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either
express or implied. See the SDK EULA for the specific language governing permissions and
limitations for this Modifiable Code under the SDK EULA.
