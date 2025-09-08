# Rust Companies

A curated list of companies using Rust in production, organized by industry.

Inspired by [Elixir's][elixir-companies] and [Elm's][elm-companies] lists.

[elixir-companies]: https://github.com/doomspork/elixir-companies
[elm-companies]: https://github.com/jah2488/elm-companies

### AI

* [Rerun.io](https://rerun.io/)([GitHub](https://github.com/rerun-io/rerun)) - Open source log handling and visualization for spatial and embodied AI.

#### Technology

* [360dialog](http://www.360dialog.com) - Most of our service consumers are written with Rust.
* [Actyx](https://developer.actyx.com) ([GitHub](https://github.com/Actyx)) - Actyx is a peer-to-peer event stream database (a.k.a. reliable durable pub-sub) written completely in Rust
* [Amazon](https://www.amazon.com)([1](https://aws.amazon.com/blogs/opensource/why-aws-loves-rust-and-how-wed-like-to-help/)) - Here at AWS, we love Rust, too, because it helps AWS write highly performant, safe infrastructure-level networking and other systems software.
* [Atlassian](https://www.atlassian.com) - We use Rust in a service for analyzing petabytes of source code.
* [Bencher](https://bencher.dev) ([GitHub](https://github.com/bencherdev/bencher)) - A suite of continuous benchmarking tools designed to catch performance regressions in CI.
* [Brave](https://brave.com)
  ([GitHub](https://github.com/brave/adblock-rust)) - Adblock engine for Brave Browser.
* [Code Input](https://codeinput.com) ([GitHub](https://github.com/CodeInputCorp/cli)) - Developer productivity tools around Git.
* [Canonical](https://canonical.com/) ([1](https://discourse.ubuntu.com/t/carefully-but-purposefully-oxidising-ubuntu/56995), [2](https://discourse.ubuntu.com/t/adopting-sudo-rs-by-default-in-ubuntu-25-10/60583)) - Canonical is a UK-based software company best known for developing and maintaining Ubuntu, a popular open-source Linux distribution. 
* [Discord](https://discordapp.com)
  ([1](https://discord.com/blog/using-rust-to-scale-elixir-for-11-million-concurrent-users), [2](https://discord.com/blog/why-discord-is-switching-from-go-to-rust)) - Communication Platform designed for communities.
* [DungeonFog](https://www.dungeonfog.com/news/project-deios/)
   ([GitHub](https://github.com/dungeonfog))
   ([Discord](https://discordapp.com/invite/Ewtsk7g))- New "Project Deios" map maker tool is written completely in rust, everything we can make opensource is hosted on our github.
* [FifthTry](https://www.fifthtry.com/) ([GitHub](https://github.com/fifthtry)) - Hosting for websites and web apps written in [`fastn`](https://www.fastn.com) language.
* [Figma](https://www.figma.com)([1](https://blog.figma.com/rust-in-production-at-figma-e10a0ec31929)) - Our real-time multiplayer syncing server (used to edit all Figma documents) is written in Rust.
* [Fly](https://fly.io)
  ([GitHub](https://github.com/superfly)) - Globally distributed reverse-proxy and app hosting.
* [Google](https://www.google.com/) ([1](https://security.googleblog.com/2022/12/memory-safe-languages-in-android-13.html?m=1)) - In Android 13, about 21% of all new native code (C/C++/Rust) is in Rust. There are approximately 1.5 million total lines of Rust code in Android across new functionality and components such as Keystore2, the new Ultra-wideband (UWB) stack, DNS-over-HTTP3, Android’s Virtualization framework (AVF), and various other components and their open source dependencies. These are low-level components that require a systems language which otherwise would have been implemented in C++.
* [Huawei](https://www.huawei.com/) - Migrated parts of its codebase to Rust, particularly for telecommunications equipment and infrastructure tools, valuing its performance and security in high-stakes environments and also one of the founding companies of Rust Foundation along with AWS, Google, Microsoft and Mozilla.
* [InfinyOn](https://infinyon.com/) ([GitHub](https://github.com/infinyon/fluvio)) - InfinyOn builds tools for developers who build intelligent data intensive applications which respond to live data. InfinyOn has developed next generation distributed event streaming and stream processing infrastructure using Rust and Web Assembly. Fluvio is the core open source event streaming engine for streaming transport. [Stateful DataFlow](https://github.com/infinyon/stateful-dataflows-examples) is the distributed stream processing framwork built using the WASM component model.
* [Materialize](https://materialize.com)
  ([GitHub](https://github.com/MaterializeInc/materialize)) - An engine for incrementally maintaining database views. Materialize core is a single binary written in Rust.
* [Meta](https://www.facebook.com) ([1](https://github.com/facebookexperimental/eden),[2](https://engineering.fb.com/2022/07/27/developer-tools/programming-languages-endorsed-for-server-side-use-at-meta/)) - Facebook's primary source control system is partially written in Rust.
* [Microsoft](https://www.microsoft.com/) - [windows-rs](https://github.com/microsoft/windows-rs) allows you to call Windows API using Rust. Rust has also been integrated into Windows kernel. There are several Azure services also using Rust, including [Azure IoT Edge](https://github.com/Azure/iotedge) and Kusto, the core query and storage engine for [Azure Data Explorer](https://azure.microsoft.com/en-us/products/data-explorer).
* [Mozilla](https://www.mozilla.org)
  ([GitHub](https://github.com/mozilla), [Servo](https://servo.org)) - Building the Servo browser engine, integrating into Firefox, other projects.
* [Qumulo](https://qumulo.com/)([1](https://qumulo.com/blog/rust-programming-language-at-qumulo/), [2](https://qumulo.com/blog/writing-procedural-macros-in-rust/)) - Hybrid cloud storage.
* [Stackable](https://stackable.tech/)([1](https://github.com/stackabletech/kafka-operator#about-the-stackable-data-platform)) - Creating a modular open source data platform. Rust powers all our operators to help make popular data applications straightforward to run on Kubernetes.
* [Polars](https://pola.rs/) ([GitHub](https://github.com/pola-rs)) - Open-source DataFrame library for data manipulation and analysis. It is implemented in Rust and uses Apache Arrow's columnar memory format for efficient data processing.
* [SurrealDB](https://surrealdb.com/) ([GitHub](https://github.com/surrealdb) - [1](https://surrealdb.com/blog/why-we-are-betting-on-rust)) - Open-source and distributed database.
* [Svix](https://www.svix.com/) ([GitHub](https://github.com/svix/svix-webhooks)) - The enterprise ready webhooks service
* [Zed.dev](https://zed.dev/) ([Github](https://github.com/zed-industries/zed)) - Zed is a next-generation code editor designed for high-performance collaboration with humans and AI.

#### Cryptocurrencies

* [Bitfury](http://bitfury.com)([Exonum](https://exonum.com)) - Exonum is an extensible framework for blockchain projects written in Rust.
* [Cryptape](http://cryptape.com) - Rust makes our permissioned blockchain, CITA, faster and stronger.
* [Fedi](https://fedi.xyz) - Fedi builds on [Fedimint](https://github.com/fedimint/fedimint), a module based system for building federated applications on top of Bitcoin.
* [Libra](https://libra.org)
  ([GitHub](https://github.com/libra/libra)) - A global cryptocurrency built by Facebook.
* [MaidSafe](http://www.maidsafe.net) - Building a decentralised data and communications network.
* [Parity](https://www.parity.io)
  ([GitHub](https://github.com/paritytech)) - Ethereum Client.
* [Solana](https://solana.com) - High performance blockchain, rebuilt for scale.
* [Wildfish](https://wildfish.com) - Fast processing and importing of cryptocurrency market data.

#### Cryptography
* [Zama](https://www.zama.ai)([1](https://github.com/zama-ai)) - Open source cryptographic tools that make protecting privacy easy.

#### Aerospace

* [Cryptosat.io](https://cryptosat.io) ([GitHub](https://github.com/cryptosat)) - Building the Trust Infrastructure for Web3, using satellites, in space.
* [Lechev.space](https://lechev.space) ([GitHub](https://github.com/LechevSpace)) - Building various aerospace-related projects including a Ground station service using Rust.
* [K2Sapce](https://www.k2space.com/) - K2 Space maximizes the amount of power, mass and volume that can be deployed with today's launch vehicle. 

#### Public transport

* [Hove](https://hove.com) ([GitHub](https://github.com/hove-io) - [1](https://github.com/hove-io/transit_model), [2](https://github.com/hove-io/mimirsbrunn), [3](https://github.com/hove-io/loki)) - Navitia API provides ways to query public transport data, including a multi-criteria journey engine

#### Automation | CI/CD

* [Chef](https://www.chef.io)
  ([GitHub](https://github.com/chef/delivery-cli)) - Chef lets you develop, deploy and manage infrastructure, run-time environments and applications.
* [CoreOS](https://coreos.com) - Tools shipped within the Container Linux distribution as well as internal tooling including documentation transformation and validation.
* [EVO](https://evo.company) - We have development tools, containerization, monitoring and orchestration systems in Rust.
* [Gremlin](https://www.gremlin.com) - Safely and efficiently causing controlled chaos.
* [NativeLink](https://nativelink.com) ([GitHub](https://github.com/tracemachina/nativelink)) - Provides remote caching and remote execution functionality for build systems.
* [npm](http://www.npmjs.com)
  ([GitHub](https://github.com/npm)) - Replacing C and rewriting performance-critical bottlenecks in the registry service architecture.
* [OneSignal](https://onesignal.com)([1](https://onesignal.com/blog/rust-at-onesignal)) - High volume, cross platform push notification delivery.
* [Sandstorm](https://sandstorm.io)([1](https://sandstorm.io/news/2016-08-09-collections-app)) - The backend of our Collections app is written in Rust.
* [Sentry](https://sentry.io)([1](https://blog.sentry.io/2016/10/19/fixing-python-performance-with-rust.html)) - JavaScript, Java and iOS event processing and the command-line client for the Sentry API.
* [slowtec](http://www.slowtec.de) - Our robust & reliable automation systems are entirely written in Rust.
* [tCell](https://www.tcell.io)([1](https://www.tcell.io/2017/06/agents-rust/)) - tCell's agent is built using Rust and runs in the app server as a means to collect data and block attacks.
* [TreeScale](https://www.treescale.com) - At TreeScale we are implemented distributed PubSub system using Rust and MIO, which gave us 8x performance on for processing and distributing Container Images.
* [VersionEye](https://www.versioneye.com)
  ([GitHub](https://github.com/VersionEye)) - We are using Rust to implement a command line tool which can identify software dependencies by their SHA values.
* [Windmill](https://www.windmill.dev/) ([Github](https://github.com/windmill-labs/windmill)) - Open-source developer platform and workflow engine

#### Cloud | Hosting

* [Clever Cloud](https://www.clever-cloud.com)([1](https://www.clever-cloud.com/doc/rust/rust/)) - We host Rust web applications, and a part of our infrastructure is developed in Rust.
* [Cloudflare](https://www.cloudflare.com) - We are using Rust as a replacement for memory-unsafe languages (particularly C) and are using it in our core edge logic.
* [Cloudflare Workers](https://workers.cloudflare.com/)([1](https://developers.cloudflare.com/workers/tutorials/hello-world-rust)) Deploy serverless code instantly across the globe with Rust support.
* [Dropbox](https://www.dropbox.com)([1](http://www.wired.com/2016/03/epic-story-dropboxs-exodus-amazon-cloud-empire/), [2](https://dropbox.tech/infrastructure/rewriting-the-heart-of-our-sync-engine)) - Optimizing cloud file-storage.
* [Delimiter](https://www.delimiter.com) - Rust powers our bare metal provisioning system.
* [OVH](https://www.ovh.com)
  ([1](https://www.ovh.com/world/a2202.paas-logs-management-ovh)) - We used Rust to build a high performance, highly available log management system.
* [Ceph](https://ceph.io/)([1](https://github.com/ceph/ceph-rust)) Rust bindings for librbd, an interface into the Ceph storage platform.
* [Tailcall](https://tailcall.run)([1](https://github.com/tailcallhq)) - A cloud native solution to streamline API management across edge, middle, and service layers.
* [Vercel](https://vercel.com/) ([GitHub](https://github.com/vercel) - [1](https://vercel.com/blog/vercel-functions-are-now-faster-and-powered-by-rust), [2](https://vercel.com/blog/finishing-turborepos-migration-from-go-to-rust)) - Cloud platform for static sites and serverless functions.

#### Fintech

* [ANIXE](http://www.anixe.pl) - Building the next generation travel services trading platform in Rust.
* [Braintree](https://www.braintreepayments.com) - Speeding up batch processing and for small command-line utilities.
* [HyperSwitch](https://hyperswitch.io)
  ([GitHub](https://github.com/juspay/hyperswitch)) - An Open Source Financial Switch to make Payments fast, reliable & affordable.
* [Spoqa](https://www.spoqa.com) - Our POS integration SDK is entirely written in Rust.
* [TenX](https://tenx.tech) - Building a secure and scalable distributed payments system in Rust.
* [Kraken](https://kraken.com)([1](https://blog.kraken.com/product/engineering/oxidizing-kraken-improving-kraken-infrastructure-using-rust)) - Cryptocurrency exchange, based in the USA.

#### Machine Learning | AI

* [Algorithmia](https://algorithmia.com)
  ([GitHub](https://github.com/algorithmiaio)) - Rust algorithm development is a first-class citizen of our platform.
* [Autumn](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790) - Machine learning in Rust.
* [craft.ai](http://craft.ai) - Our core machine learning engine is written in Rust.
* [Deepgram](https://deepgram.com)
  ([GitHub](https://github.com/deepgram),[1](https://blog.deepgram.com/why-deepgram-built-its-platform-in-rust/)) - Speech AI Platform for transcription and understanding.
* [Faraday](http://faraday.io)([1](https://github.com/faradayio/credentials_to_env)) - Securely transferring credentials.
* [Hugging Face](https://huggingface.co/)
  ([GitHub](https://github.com/huggingface)) - Many components within the Hugging Face ecosystem for AI, including safetensors, tokenizer, and candle, are implemented using Rust.
* [IamBot](http://iambot.ai) - Our high-performance data acquisition is fully implemented using Rust. Besides that, we are also using Rust for our API endpoints that communicate with internal systems.
* [LanceDB](https://lancedb.com)
  ([GitHub](https://github.com/lancedb)) - Multimodal data platform built in Rust.
* [Routific](https://routific.com) - High performance route optimization software.
* [PolySync](https://polysync.io) - Building safety-critical runtime environments & infrastructure for autonomous vehicles.
* [Snips](https://snips.ai) - AI assistants that are private by design.
* [TensorZero](https://www.tensorzero.com/)
  ([GitHub](https://github.com/tensorzero/tensorzero)) - Open source LLM gateway, observability, optimization, evaluations, and experimentation &mdash; built with Rust.

#### News | Media

* [Amedia](https://www.amedia.no/)[GitHub](https://github.com/amedia)  - Amedia is a foundation-owned media group, and Norway's largest publisher of editorial media. Our personalization platform and the mobile backend is in its entirety written in Rust.

#### Embedded systems | Hardware | IoT

* [49nord](https://49nord.de/rust) - 49nord develops safe and secure Industrial IoT hardware and applications using Rust.
* [Calyptech](http://calyptech.com) - Used for high performance embedded system components as an alternative to C.
* [Espressif](https://www.espressif.com/) ([GitHub](https://github.com/esp-rs/)) - Improving performance of embedded and IoT devices with using Rust in esp products.
* [System76](https://system76.com)
  ([GitHub](https://github.com/system76)) - As a Linux-based computer-manufacture, much of our infrastructure and desktop Linux projects are written in Rust.
* [SmartThings](http://www.smartthings.com)([1](https://www.smartthings.com/how-it-works)) - Memory-safe embedded applications on our SmartThings Hub and supporting services in the cloud.
* [Star Lab](https://starlab.io) - As an embedded security company, Rust allows us to have confidence in the performance and reliability of our products.

#### Internet Service Provider

* [Starry](https://starry.com) - Re-imagining broadband by engineering a new wireless access network and building an ecosystem of products designed to simplify and improve your connected life.
* [Yomura Fiber](https://yomurafiber.com) - Rust powers our GPON provisioning and statistic gathering.

#### Consulting

* [Braun Embedded](https://braun-embedded.com/)
  ([GitHub](https://github.com/braun-embedded)) - Provides firmware development services for ARM Cortex-M microcontrollers.
* [corrode](https://corrode.dev/)
  ([GitHub](https://github.com/corrode)) - Custom Rust consulting and development based in Germany that puts people first.
* [Ferrous Systems](https://ferrous-systems.com)
  ([GitHub](https://github.com/ferrous-systems)) - Rust knowledge. Collected.
* [Immunant](https://www.immunant.com)
  ([GitHub](https://github.com/immunant)) - Immunant specializes in translation from C to Rust and exposing legacy C/C++ through safe Rust interfaces.
* [Integer 32](https://www.integer32.com)
  ([GitHub](https://github.com/integer32llc)) - Integer 32 is a consultancy that delivers high-quality Rust code.
* [Red Iron](https://red-iron.eu/) ([GitHub](https://github.com/orgs/OCamlPro/repositories?q=&type=all&language=rust)) - Red Iron is the Rust division of OCamlPro, a French consultancy specializing in programming languages, formal methods and high reliability software.
* [Rustunit](https://rustunit.com) ([GitHub](https://github.com/orgs/rustunit/repositories?q=&type=all&language=rust)) - Consultancy specialized in all things Rust, Gaming, Distributed Systems and Strategic Consulting.
* [Tweede golf](https://tweedegolf.nl)
  ([GitHub](https://github.com/tweedegolf/)) - Rust and Embedded Rust engineers.

#### Security | Monitoring

* [1Password](https://1Password.com) ([GitHub](https://github.com/1Password)) - The world's most-loved password manager, powering all of our latest desktop and mobile apps with a single shared Rust codebase.
* [AppSignal](https://appsignal.com) - Fast and robust monitoring agent for web applications.
* [Canonical](http://www.canonical.com) - Everything from server monitoring to middleware!
* [Distil Networks](https://www.distilnetworks.com) - We are using Rust in our low latency bot detection and mitigation platform.
* [Firo Solutions](https://firosolutions.com)([1](https://github.com/firosolutions/)) - Firo Solutions is a notification service that notifies the enduser about security vulnerabilities, they parse large amounts of data using rust
* [krypt.co](https://krypt.co)([1](https://github.com/kryptco/ssh-wire), [2](https://github.com/KryptCo/kr/tree/master/pkcs11shim)) - Shared code between iOS and Android for SSH host signature verification as well as a PKCS11 shared library.
* [Oso](https://www.osohq.com) - Oso Cloud is a managed Authorization-as-a-Service provider. Rust allows us to provide end-to-end Authz checks in <10ms.
* [Red Sift](https://redsift.com)
  ([GitHub](https://github.com/redsift/ingraind)) - Container monitoring with eBPF.
* [Shiftleft](https://www.shiftleft.io)([1](http://blog.shiftleft.io)) - ShiftLeft is a Silicon Valley startup employing innovative techniques to bring clarity and rigor to the security space. Our bespoke runtime security agent is written in Rust.
* [ThreatX](https://threat-x.com) - Threat X Web Application Firewall (WAF) and central analysis engine are written in Rust, facilitating real time analysis of high bandwidth web applications.

#### Governments / NGO

* [Fire and Emergency NZ](https://fireandemergency.nz) - The New Zealand Fire Service is using a custom geolocation search engine, built in rust, that runs on embedded hardware within a fire truck to stream hazard information to a fire crew at an incident.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.
