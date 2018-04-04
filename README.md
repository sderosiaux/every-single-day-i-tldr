# *Almost* every single day I TLDR!

Here, I list all the articles, blog posts, pages I've read, or videos I've watched, that I found interesting. It's like a huge shared bookmarks registry with y'all! Or it's like a daily newsletter without newsletter.

I'm reading mostly about Scala, Data Engineering, Java, Javascript, Big Data, DDD, and technology. :muscle:

> Note for my past/current/future employer: this is stuff I'm reading mostly off work of course. :see_no_evil:

# 04-04-2018

- https://www.youtube.com/watch?v=JFbYQGG2Nb4 Monix's Observable and Iterant
- https://www.youtube.com/watch?v=JH_Ou17_zyU Bartosz Milewski's Category Theory crash course, he's very good at teaching.
- https://cloudplatform.googleblog.com/2018/04/new-ways-to-manage-and-automate-your-Stackdriver-alerting-policies.html New API to manage Stackdriver alerting policies. Surprised it didn't existed before.

# 03-04-2018

- https://www.youtube.com/watch?v=3a5oE3p3jDA about SIP-35 / opaque types. Could replace Option and such "easy" type, also provide type tagging without overhead at runtime.
- https://www.youtube.com/watch?v=JMP6gI5mLHc Parallels between Category Theory definition (+ Functors) and languages (mostly Java)
- https://blog.cloudflare.com/cloudflare-workers-unleashed/ JavaScript "lambdas" on Cloudflare with Workers
- https://www.youtube.com/watch?v=HTmaTCLdb_U event sourcing composability with monads
- https://zeit.co/blog/multi-dc now.sh is now multi-dc (sf + brussels)
- https://www.youtube.com/watch?v=jrOS_UrIQI0 Building a serverless app with fnproject.io
- https://www.youtube.com/watch?v=2oXqbLhMS_A Going from blocking to non-blocking with Netty and RxJava. Pros and cons.
- https://typelevel.org/blog/2017/12/20/who-implements-typeclass.html More on typeclasses
- https://medium.com/anyjunk/fstring-string-lengths-at-compile-time-81f811750e9e Using types (as Nat from shapeless) to ensure a String maxLength (at compile-time)
- https://blog.sessionstack.com/how-javascript-works-a-comparison-with-webassembly-why-in-certain-cases-its-better-to-use-it-d80945172d79 WebAssembly improvements over JavaScript
- http://korban.net/posts/postgres/2017-11-02-the-case-against-orms/ Case against ORMs (yeah)
- https://github.com/lampepfl/dotty/pull/4153 Hot debate about Typeclass implemented with subtyping proposal in Scala
- https://medium.com/@nex3/pubgrub-2fb6470504f Resolving package dependencies graph is far from trivial; here nice explanations about a new method implemented in the Dart package manager.
- http://www.scanamo.org/ DynamoDB Scala wrapper

# 02-04-2018

- https://www.youtube.com/watch?v=YXDm3WHZT5g Devoxx Belgium 2017, Plain Functional Programming by Martin Odersky; example using Kleisli (for config) against implicit types (incoming)
- https://github.com/mikolak-net/travesty Generating diagram for akka streams
- https://alistapart.com/article/coding-with-clarity Single responsability principle, low coupling/high cohesion, with analogies to real-world example
- http://akaptur.com/blog/2017/11/12/love-your-bugs/ Bits flip are real. Use feature flags. Don't DDOS yourself.
- https://medium.com/dailymotion-engineering/a-brief-history-of-apis-at-dailymotion-3c2c16001717 Quick post from Dailymotion explaining the switch of their API to GraphQL (mostly for performance purpose, less round-trip)
- https://embano1.github.io/post/scratch/ Study of the "FROM scratch" image and explanations of the differences between the container image and one of its instance (OCI runtime specification)
- http://highscalability.com/blog/2018/4/2/how-ipdata-serves-25m-api-calls-from-10-infinitely-scalable.html Very cool feedback and archi about by ipdata (using aws gateway, dynamo, lambdas, kinesis, cloudwatch)
- https://levelup.gitconnected.com/how-to-use-technical-debt-in-your-favor-98bae475ba68?ref=hn322 Dealing with technical debt: always start naive, then refactor the past when it's more clear and patterns emerge
- https://medium.com/databasss/on-disk-io-part-1-flavours-of-io-8e1ace1de017 Multiple posts explaining how ios work, very interesting to get the base

# 01-04-2018

- https://alligator.io/graphql/graphql-yoga/ An easy way to spin-up a GraphQL server
- https://medium.com/capital-one-developers/blazing-fast-data-lookup-in-a-microservices-world-dd3ae548ca45 Using a bloom filter to filter out bad emails
- http://fluentbit.io/ A lightweight fluentd written in C container oriented?
- https://medium.com/@adirmashiach/partition-index-selective-queries-on-really-big-tables-795fea737570 Maintaining a index table to know which partition to read (for a given PK) instead of doing a full scan
- https://blog.cloudflare.com/announcing-1111/ 1.1.1.1 as (privacy-respected) DNS resolver ! (unfortunately, does work with Orange in France yet...)
- https://www.apache.org/dist/kafka/1.1.0/RELEASE_NOTES.html Kafka 1.1.0 out; few new features but tons of fix and improv

# 31-03-2018

- https://graphcms.com/blog/gatsby-graphcms-plugin/ Combining Gatsby and GraphCMS (to host content) because Gatsby can fetch GraphQL endpoints to grab content
- http://shiroyasha.io/transaction-isolation-levels-in-postgresql.html Time to refresh what are the different transaction isolation levels
- http://lucidsoftware.github.io/relate/ Relative: another blazing fast Scala SQL "framework" sql"SELECT xx".asList { _.string("name") }
- https://cloud.google.com/blog/big-data/2017/12/analyzing-tweets-using-cloud-dataflow-pipeline-templates Creating a Dataflow template and launching it regularly via an appengine app + cron
- https://slack.engineering/scaling-slacks-job-queue-687222e9d100 Kafka in front of Redis for queuing jobs to ensure resilience, sustain workload, better decoupling.
- https://medium.com/@abinoda/how-teams-get-microservices-wrong-from-the-start-51777c99c059 Each team should define what a "microservice" is and what are the pros/cons of switching to it. (future replacement? teams organization? productivity boost? delivery boost?)
- http://highscalability.com/blog/2017/12/4/the-eternal-cost-savings-of-netflixs-internal-spot-market.html Netflix: creating a cloud inside their cloud
- http://openjdk.java.net/projects/amber/LVTIstyle.html Guidelines for when to use "var" in Java

# 30-03-2018

- https://medium.com/activewizards-machine-learning-company/top-15-scala-libraries-for-data-science-in-2018-4b2cb5c5367e Some nice pointers for data science in scala: Breeze (Analysis, NLP), Saddle (Analysis), Breeze-vis (dataviz), Vegas (dataviz), Smile (ML), and Spark stuff
- https://cloudplatform.googleblog.com/2018/01/why-you-should-pick-strong-consistency-whenever-possible.html Spanner and its "external consistency" (strongly consistent + serializability): no trade-off in the apps!
- https://www.youtube.com/watch?v=BgcJnurVFag Building a 400TB PostgreSQL clusters: tips and tricks
- https://www.youtube.com/watch?v=v3msiBIny6s Nice talk about the pure push/pull flaws that lead to create Reactive Streams, and Akka Streams is one implementation. Here nicely presented by Viktor Klang.
- https://thenewstack.io/microservices-running-containers-need-streaming-platform/ Microservices, Containers, and the upcoming of Streaming Platforms to handle all the technicals points (communication, pubsub, storage, failures etc.)
- https://hackernoon.com/thorough-introduction-to-apache-kafka-6fbf2989bbc1 A large and clear overview of the Kafka streaming platform
- https://medium.com/netflix-techblog/distributing-content-to-open-connect-3e3e391d4dc9 Netflix is now using a smarter Consistent Hashing technique based on multiple weights to distribute resources into their heterogeneous servers
- https://www.youtube.com/watch?v=h48kuflGEDw Scala 2.12 (tech refactor) /13 (library refactor) /14 (remove features)/15 (to dotty) evolutions and improvements
- https://www.slideshare.net/cloudera/performance-of-apache-impala Impala misc optimizations: codegen, smart joins + create bloomfilter if needed, preaggregation, cache hits
- https://reactjs.org/blog/2018/03/29/react-v-16-3.html An official "context" API! Better ref management; and lifecycle methods deprecations/new
- https://www.lightbend.com/blog/the-six-questions-architects-ask-about-using-akka-in-production Some points of why using Akka. It misses the part "why NOT".
- https://github.com/envoyproxy/envoy/issues/2852 Sending req/res into Kafka within Envoy?
- https://github.com/scala-native/scala-native/releases/tag/v0.3.7 Scala Native 0.3.7 and sbt-crossproject to compile a project to js/native/jvm

# 29-03-2018

- https://www.youtube.com/watch?v=9Wp_riP8LQw Implicit FunctionTypes soon in Scala? basically type Gimme[E] = implicitly Int => E, implicit is part of the type (for easy reusability)
- https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a An ode to the functional data engineering: how to "data engineer" with functional principles
- https://gtoonstra.github.io/etl-with-airflow/index.html A very good and complete documentation about Airflow and ETLs in general
- https://github.com/confluentinc/schema-registry/pull/680/files It's now possible to save record using different Avro (without union, totally disjoint) records in one topic and let the SR knows about it
- https://medium.com/serialized-io/apache-kafka-is-not-for-event-sourcing-81735c3cf5c Some interesting points (challenged in the comments, to read) why Kafka does not fit event sourcing constraints.
- https://developers.google.com/web/updates/2018/01/paintapi CSS Paint API in Chrome: a dedicated js to register which can be referred in "background-image: paint(toto)" to return the content (using the canvas api). This fills a gap, nice.
- https://sleeplessinslc.blogspot.fr/2018/02/inventory-microservice-example-with.html Sleepless in Salt Lake City: Inventory Microservice example with Kafka Streams and CQRS
- https://coreos.com/etcd/docs/latest/learning/why.html etcd vs. other key-value stores
- http://www.landoop.com/blog/2018/01/mqtt-influxdb/ Landoop showing off its (good) Lenses platform (a centralized UI to deal with Kafka*, query endpoints, see topology etc.), and using it to ingest (Kafka Connect) from some MQTT to InfluxDB
- http://www.landoop.com/blog/2018/03/cassandra-to-kafka-part-2/ Cassandra to Kafka using Connect (and a polling strategy)
- https://cloudplatform.googleblog.com/2018/03/how-we-used-Cloud-Spanner-to-build-our-email-personalization-system-from-Soup-to-nuts.html An interesting feedback of a company going from HBase+Hive to Spanner, why & takeaways
- https://cloudplatform.googleblog.com/2018/03/introducing-Stackdriver-APM-and-Stackdriver-Profiler-Distributed-tracing-debugging-and-profiling-for-your-performance-sensitive-applications.html GA: Stackdriver Profiler to analyze application cpu, mem etc. through flame charts; Debugger to easily debug (breakpoint) and log in prod (without redeploying); Trace to do trace (spans) analysis through the services (à la OpenTracing, with propagation, latency etc.).

# 28-03-2018

- https://blog.apnic.net/2018/01/29/measuring-quic-vs-tcp-mobile-desktop/ QUIC (by Google) vs TCP: QUIC is globally faster (and Chrome users use it when contacting Google!) except in some conditions (packets out-of-order, mobiles where resources are limited)
- https://blog.hasura.io/an-exhaustive-guide-to-writing-dockerfiles-for-node-js-web-apps-bbee6bd2f3c4 Good practices on how to write Dockerfiles for nodejs webapps
- https://www.datanami.com/2018/02/07/erasure-coding-changes-hadoop-storage-economics/ Changing how HDFS store its data to make it more economic, causing a bit more network and cpu processing. Also leaving behind the "storage and compute" paradigm.
- https://banzaicloud.com/blog/kafka-on-etcd/ Kafka fork using etcd instead of zk
- https://www.confluent.io/blog/write-user-defined-function-udf-ksql/ Create and package UDFs in ksql
- https://blog.godatadriven.com/doobie-monix-jdbc-example Nice examples using Doobie to sql in Scala
- https://cloudplatform.googleblog.com/2018/03/introducing-Cloud-Text-to-Speech-powered-by-Deepmind-WaveNet-technology.html Awesome Text-to-Speech + wavenet variation (en only) available on GCP
- https://the-composition.com/why-you-need-a-software-delivery-machine-85e8399cdfc0 Tons of details about Atomist: why, how it works, which events it reacts to, how does it evolve etc. Support a project from scratch to delivery 100%.
- https://www.youtube.com/watch?v=O-LWbSUaEQU Property-Based testing overview, why, how

# 27-03-2018

- https://jakubstransky.com/2018/02/03/jvm-code-friendly-to-jit-optimisation/ Using jitwatch to analyze bytecode and inlining tips
- https://www.youtube.com/watch?v=wZ7cxcU4iPE Long hexagonal arch explanation with examples
- https://streaml.io/blog/pulsar-effectively-once/ Effectively(exactly)-once semantics in Apache Pulsar
- https://eng.uber.com/queryparser/ To handle some columns migration, Uber parses all SQL querying their datawarehouse. They inspect the (anti-)patterns, notify the right users in case of changes on the tables (according to who uses them), determine the table lineage for incident purpose (RCA), and better understand how their DWH is used for optimization. All that in Haskell.
- https://blog.cloudflare.com/how-cloudflare-analyzes-1m-dns-queries-per-second/ Cloudflare DNS queries serialized into Kafka (Cap'n Proto), then ingested into ClickHouse and visualize with Superset (ad-hoc) and Grafana (monitoring)
- https://v8project.blogspot.fr/2018/03/background-compilation.html V8 compiles more into a background thread now, letting the main thread free = better perf
- https://banzaicloud.com/blog/prometheus-application-monitoring/ Relabeling (crappy) metrics name at scrape time with Prometheus. It is nice because it avoids to do it repeatly in Grafana for instancec.
- http://www.landoop.com/blog/2018/03/kafka-elasticsearch-kubernetes-iot/ From Spark Streaming to Kafka Connect on k8s
- https://medium.com/fullstack-academy/better-js-cases-with-sum-types-92876e48fd9f Very cool long article about sum and product types, comparing the feature in different nice languages (and js).
- https://cloudplatform.googleblog.com/2018/03/kubernetes-engine-private-clusters-now.html Deploy GKE in a VPC to get a better isolation
- https://medium.com/@richard534/getting-started-with-data-engineering-3d2e728d0c1f All the things about Data Engineering

# 26-03-2018

- https://inviqa.com/blog/lagom-tutorial-using-event-sourcing-create-online-shopping-cart Small Lagom tutorial, properly explained from scratch
- https://www.imperva.com/blog/2018/03/deep-dive-database-attacks-scarlett-johanssons-picture-used-for-crypto-mining-on-postgre-database/ A nice explanation of a wonderful hack through PostgreSQL to mine minero
- https://www.sqreen.io/checklists/saas-cto-security-checklist The SaaS CTO Security Checklist
- https://docs.google.com/presentation/d/17opE2U2aIe1TFYJgr0Z8Dd2fJhy2x0YbReCVeCz6uhA/edit#slide=id.g137428a63f_2_75 BigGraphite by Criteo: Graphite backed up by Cassandra
- https://databricks.com/blog/2018/03/20/low-latency-continuous-processing-mode-in-structured-streaming-in-apache-spark-2-3-0.html Continuous Processing mode: finally true streaming in Spark?
- https://blog.clairvoyantsoft.com/guide-to-using-apache-kudu-and-performance-comparison-with-hdfs-453c4b26554f Starting with Kudu, and Performance comparison with HDFS (generallly better)
- https://medium.com/@adirmashiach/apache-impala-my-insights-and-best-practices-8e0507089935 Impala vs the world, and best practices
- https://kudu.apache.org/releases/1.7.0/docs/release_notes.html Kudu 1.7.0, tons of features and improvements
- https://github.com/gkossakowski/kentuckymule/issues/6#issuecomment-375949236 Smart idea of how to detect cycles using queues (kentuckymule is a experimental fast Scala type-checker)

# 25-03-2018

- http://beckje01.com/talks/greach-2018-zipkin-light.html Small presentation about Zipkin, screenshots, demos
- https://quickbooks-engineering.intuit.com/lessons-learnt-from-netflix-keystone-pipeline-with-trillions-of-daily-messages-64cc91b3c8ea Wow, immutable infra to the end. "Handling Config Changes as simulated failure: Changes to the Kafka cluster (code upgrades, topic scale up or scale down, moving partitions) are handled by failover to a new Kafka cluster." 
- https://medium.com/beingprofessional/understanding-functor-and-monad-with-a-bag-of-peanuts-8fa702b3f69e Functors and monads explained with peanuts, you _will_ understand
- https://typelevel.org/cats-effect/datatypes/io.html The Cats Effect's IO documentation is phenomenal. So many possibilities!

# 24-03-2018

- https://blog.ycombinator.com/congratsdropbox/ Dropbox goes public. A small message from ycombinator, because it's dropbox's origin (2007!), impressive.

# 23-03-2018

- http://blog.christianposta.com/how-a-service-mesh-can-help-with-microservices-security/ make microservices communications secured (tls, jwt) using istio to manage all that, and not the apps
- http://www.edc4it.com/blog/scala/io-monad-and-monad-transformers-for-rookies.html A simple example of using IO and EitherT monads
- http://degoes.net/articles/kill-data Don't prematurely commit to specific datastructures
- https://corecursive.com/009-throw-away-the-irrelevant-with-john-a-de-goes Interesting podcast with John A De Goes about functional programming in general, why is this useful, advantages (smaller scope to think about; more extensible than OOP with typeclasses) stacking monads is a perf-blow (and we should use MonadError, MonadState instead)

# 22-03-2018

- https://functional.works-hub.com/learn/avoid-pattern-matching-with-list-in-scala-01c8e Careful of pattern matching List/Seq
- https://slidr.io/mathiasbynens/what-s-new-in-es2018 ES2018: async generators and a demo to "act like" RxJs's Observable (fromEvent, filter, etc.), regexes, spread (finally!), finally in promise
- http://seg.phault.net/blog/2018/03/async-iterators-cancellation/ cancelling async iterators 

# 21-03-2018

- https://en.wikipedia.org/wiki/Quine_(computing) TIL about Quines and Multiquines. Programs that produce a copy of their own source code.
- https://www.infoq.com/presentations/microservices-data-centric Very nice talk about microservices management and techniques of migration
- https://shipilev.net/blog/2014/safe-public-construction/ Double-checked locking in Java (quite subtle!), applied to the Singleton Factory pattern
- http://wiki.jvmlangsummit.com/images/1/1e/2011_Goetz_Lambda.pdf JVM Strategy to convert lambdas to bytecode
- https://www.youtube.com/watch?v=kglEJ5x8xR8 problèmatiques de scheduling à criteo, de lobster à cuddle: lib à embed, plein de "connectors" (sh, yarn, clouds, etc.), démo UI, backfilling
- https://typelevel.org/blog/2016/09/30/subtype-typeclasses.html implicit resolutions and subtyping loopholes (think cat theory, functor etc.) and solutions (define levels of subtypes exposing the implicits to change the priorities; used in cats, scalaz etc.)
- https://typelevel.org/blog/2016/10/26/edsls-part-2.html Introducing MonadError and MonadState
- https://medium.com/google-cloud/understanding-kubernetes-networking-ingress-1bc341c84078 Services, nodeport, lb, ingresses
- https://shipilev.net/blog/2014/heapdump-is-a-lie/ JVM objects size (JOL being the single source of truth)
- http://blogs.perl.org/users/ovid/2010/08/what-to-know-before-debating-type-systems.html static and dynamic type systems (sound, perf, doc, analysis, correctness, more or less verbose); explicit vs inference; structural typing; duck typing; what is a type finally? "a label used by a type system to prove some properties of the program behavior"
- http://mail.openjdk.java.net/pipermail/announce/2018-March/000247.html JDK 10 GA, tons of new features but mainly type inference and Graal (`-XX:+UnlockExperimentalVMOptions -XX:+UseJVMCICompiler`)  (no pattern matching :()
- https://github.com/scala/scala/releases/tag/v2.12.5 scalac -release 9 !!
- https://www.youtube.com/watch?v=wfWYm0MYj_8 Java 10:  Panama (replace JNI, use JIT to generate the C layer), Amber: type inference, '_', pattern matching (+ scalaish sealed ADTs and extractors)
- https://cloudplatform.googleblog.com/2018/03/understand-your-spending-at-a-glance-with-Google-Cloud-Billing-reports-beta.html GCP Billing reports: group by project and product (gae, bq, pubsub etc.) to see the trends, nice

# 20-03-2018

- http://lptk.github.io/programming/2018/03/02/a-dual-to-iterator.html Compute any aggregations in one pass using for-comp syntax
- https://www.dropbox.com/s/qmuwo7z0v9jmnwi/NEScala2018.pdf "Composing programs": explaining why the composition is the essence of functional programming. Also discuss some category theory elements (kleisli, functors, monads).
- https://github.com/plokhotnyuk/jsoniter-scala ultra-fast JSON codecs in Scala
- https://rossabaker.github.io/boston-http4s/ Really great slideshow about http4s evolutions from simple stuff to Kleisli of Task/IO
- https://www.opsian.com/blog/java-on-docker/ Java 10 will be easier to manage when Docker'ed
- https://qconlondon.com/system/files/presentation-slides/how_events_are_reshaping_modern_systems_-_qcon_london.pdf Event-first design and event logging advantages
- http://psy-lob-saw.blogspot.fr/ All the posts are amazing, dealing with JVM performances and profiling, read some of them, but lost a bit my way into ahah.
- http://psy-lob-saw.blogspot.fr/2013/05/using-jmh-to-benchmark-multi-threaded.html False sharing problem using jmh
- https://github.com/jvm-profiling-tools/honest-profiler Profiling JVM apps without waiting for safepoints (+ lower overhead)
- http://psy-lob-saw.blogspot.fr/2018/01/what-difference-jvm-makes.html?spref=tw G1GC is the default in Java 9, that could lead to tremendous changes in benchmarks, as seen here; g1gc added locks to handle memory barriers
- https://www.slideshare.net/RednaxelaFX/green-teajug-hotspotintrinsics02232013 Intrinsic Methods in HotSpot VM
- https://monix.io/blog/2018/03/20/monix-vs-cats-effect.html Monix vs cats-effect, and some history about Monix and cats-effect and misc (cancellability, reactive streams, scalaz's Task, optimizations, monix's Iterant)
- https://medium.com/@muuki88/follow-the-stacktraces-jvm-performance-profiling-3c371d323e5f Lesson learned: Never use exceptions for control flow in your hot code path
- https://cloudplatform.googleblog.com/2018/03/introducing-the-ability-to-connect-to-Cloud-Shell-from-any-terminal.html We can now access the Cloud Shell (was in-browser only before) from "gcloud alpha cloud-shell" command now (it comes with preinstalled stuff, to avoid polluting the local env)

# 19-03-2018

- https://cloudplatform.googleblog.com/2018/03/automatic-serverless-deployments-with-Cloud-Source-Repositories-and-Container-Builder.html Mirror git source into GCP Repo, and write a "build trigger" (yaml) in Container Builder to be triggered when source changes
- https://github.com/GoogleCloudPlatform/skaffold In the "same" vein, skaffold auto-runs the whole build/deploy pipeline on code change
- https://jenkins.io/blog/2018/03/19/introducing-jenkins-x/ Jenkins X: CI/CD with a new cli "jx" to create apps and handle the whole ci/cd cycle automatically (versioning, envs, builds (jenkinsfile, dockerfile, helm chart), deployments, pull requests, issues..). A sub-project of Jenkins.
- http://jpetazzo.github.io/2018/03/13/appswitch-hyperlay-network-stack-future/ AppSwitch looks like a service mesh for anything (ie: outside containers), cross-machines, tiny overhead, very simple. Will it happen?
- https://hackernoon.com/how-graphql-replaces-redux-3fff8289221d A simple but useful revelation: querying using graphql can prevent you to code tons of Redux reducers and async stuff querying classic rest endpoints.
- https://github.com/atlassian/react-beautiful-dnd/releases/tag/v6.0.0 v6 of react-beautiful-dnd, just an amazing work
- https://meta.plasm.us/slides/circe/algebra/ Experimental circe-algebra: splitting decoding from interpreting (think Free), and using cursors.
- http://www.softwaredaily.com/ Software Daily podcasts
- http://debezium.io/blog/2018/03/08/creating-ddd-aggregates-with-debezium-and-kafka-streams/ An aggregate user+addresses built with Debezium and Kafka Streams
- https://images.guide/ The most complete guide to image optimization you can find. Very informative to be aware of every possibilities to optimize our pictures because #perfmatters.
- https://insights.stackoverflow.com/survey/2018/ Stack Overflow Developer Survey 2018
- https://community.akamai.com/community/web-performance/blog/2016/06/22/understanding-how-the-http2-protocol-is-negotiated Understanding how the HTTP/2 protocol is negociated
- https://medium.com/@duhroach/improving-cloud-function-cold-start-time-2eb6f5700f6 GCP boot time: reduce dependencies, have 1 version of them (cached), lazy load them if possible (not needed at boot time).
- http://benjiweber.co.uk/blog/2018/03/03/representing-the-impractical-and-impossible-with-jdk-10-var/ "var" in JDK10 is useful to define previously impossible types (mixes of interfaces or structural types)
- https://www.linkedin.com/pulse/nightmare-letter-subject-access-request-under-gdpr-karbaliotis/ The (great) Nightmare Letter: A Subject Access Request under GDPR.
- https://cloudplatform.googleblog.com/2018/03/introducing-GCPs-new-interactive-CLI.html CLI are some ubiquitous right now, gcloud offers a better alternative: "gcloud alpha interactive --update-cli-trees"
- https://www.nginx.com/blog/nginx-1-13-10-grpc/ gRPC support in nginx
- https://chrome.google.com/webstore/detail/personal-blocklist-by-goo/nolijncfnkgaikbjbdaogikpmpbdcdef?hl=en Google's own extension to block some websites to appear in search results. But the last Chrome version makes it useless, #willfixlater ?

:ski:

# 09-03-2018

- https://lwn.net/Articles/679786/ Understanding cgroup v2
- https://gist.github.com/odersky/f91362f6d9c58cc1db53f3f443311140 Some notes about metaprogramming in Scala by odersky. If you're brave.
- http://blog.christianposta.com/microservices/the-hardest-part-of-microservices-calling-your-services/ Insightful post about microservices constraints and failures to deal with (latencies, timeouts., retries, routing, observability)
- https://github.com/shekhargulati/hands-on-serverless-guide/tree/master/01-aws-lambda-serverless-framework A trully wonderful guide about building a pure serverless app using AWS api gateway -> lambdas -> ses for emails + dynamodb and its streams + s3 (with presigned urls)
- https://engineering.instagram.com/open-sourcing-a-10x-reduction-in-apache-cassandra-tail-latency-d64f86b43589 Rockssandra, a combinaison of RocksDB and Cassandra to greatly improve (and stabilize) r/w latencies
- https://github.com/druid-io/druid/releases/tag/druid-0.12.0 Druid 0.12.0 out!

# 08-03-2018

- https://stripe.com/blog/operating-kubernetes Stripe extensively testing k8s mainly to run tons of cronjob, fixing bugs, and best "practices", the "game" day. Know how k8s behaves in case of different failures. Beware of etcd. Improve monitoring, 
- https://community.monzo.com/t/resolved-current-account-payments-may-fail-major-outage-27-10-2017/26296/95 Outage caused by 2 bugs: a bug in k8s and etcd client; and another with k8s Service without pods + linkerd "old" version (bug was fixed in next versions)
- http://blog.erratasec.com/2018/03/some-notes-on-memcached-ddos.html Find the vulnerable memcached instances using masscan and how to deal with it
- http://degoes.net/articles/blockchain-myths You Know Nothing!
- https://cloud.google.com/blog/big-data/2017/10/separation-of-compute-and-state-in-google-bigquery-and-cloud-dataflow-and-why-it-matters BigQuery and Dataflow use Google storage services instead of instance-attached storage to scale out easily and it leads to a better arch (better perf and reliability)
- https://www.facebook.com/business/gdpr how Facebook handles GDPR (both a data controller & processor)
- http://dotty.epfl.ch/blog/2018/03/05/seventh-dotty-milestone-release.html Better enum semantics, "erased" term to remove stuff at compile time (just used to type-check), better GADT support
- https://cloudplatform.googleblog.com/2018/03/optimizing-your-Cloud-Storage-performance-Google-Cloud-Performance-Atlas.html Some smart advices when using gsutil to improve up/download speed (parallelism -m, auto "chunkage" -o GSUtil:parallel_composite_upload_threshold=150M)

# 07-03-2018

- http://docs.scala-lang.org/sips/pending/inline-meta.html SIP-2[89], a new block to replace macro: meta {... }; meta annotations; "inline" achieves guaranteed inlining, regardless of the backend (contrary to @inline); will whiteboxing will stay? (bring tons of complexity)
- https://begin.com/ A Slack bot to declare on what you're working on and create task list other can see. Not sure it's the right way to go (Slack becoming a first class tool of your workflow?) but it can help i guess!
- https://github.com/Kanaka-io/play-monadic-actions Simplify (monadify) how to write Play! actions when dealing with services calls/http responses
- https://www.youtube.com/watch?v=AGztKw580yQ Good talk about why Istio and several demos using plain JDK client/server (circuit breakeing, lb, force failure, a/b testing, monitoring, tracing)
- https://failex.blogspot.fr/2017/04/the-high-cost-of-anyval-subclasses.html Value classes overhead VS tagged types (no overhead, 2 types = 1 class)
- https://docs.google.com/spreadsheets/d/17bZrKTk8dOx5nomLrD1-93uBfajK5JS-v1o-nCLJmzE/edit#gid=0 Kubernetes Features OSS tracking board (1.10 release)
- https://githubengineering.com/ddos-incident-report/ DDoS through the open misconfigured memcached over the world.
- https://github.com/typelevel/machinist Avoid implicit class wrapping

# 06-03-2018

- https://www.youtube.com/watch?v=hzf3hTUKk8U A 2014 talk about why functional programming is good! composability, modularity, genericity, less strain, happiness. But code could be complicated (yeah).
- https://github.com/estatico/scala-newtype Haskell's "newtype" for Scala (to replace value classes and their undesired effects)
- https://github.com/mathiasbynens/dotfiles useful dotfiles to use on macosx (tune them!). I discovered some nice shortcuts and tools in there.
- https://github.com/kelseyhightower/kubernetes-the-hard-way Bootstraping Kubernetes manually on GCP, using GCE, VPC, subnetworks etc. Good if you truly wanna know how it works underneath
- http://blog.effectivemessaging.com/2017/06/load-balancing-grpc-connections-in.html lb gRPC in k8s with Linkerd and Istio. I had this link for a while; now Istio is way more mature and even integrated in GCP: https://cloud.google.com/kubernetes-engine/docs/tutorials/istio-on-gke
- https://medium.com/google-cloud/bigquery-performance-tips-searching-for-text-8x-faster-f9314927b8d2 Interesting BigQuery performance tips when using like '%x%'. Use regexp_contains or convert to bytes for better perf. (for now)
- https://virtuslab.com/blog/mechanics-unboxed-union-types-scala/ A sweet article about understanding "how to make a union type" in Scala (without Either), and using contravariance
- https://medium.com/netflix-techblog/scaling-time-series-data-storage-part-i-ec2b6d44ba39 From Cassandra, to Cass+Cache, to compression/parallelization/chunkages to get better r/w latency, less Cass maintenance, less data size.
- https://www.reoptimize.io/ Control you GCP billing
- https://medium.com/google-cloud/understanding-kubernetes-networking-services-f0cb48e4cc82 kube-proxy is the "hidden" gem in k8s that manages internal traffic packets routing (using netfilter and iptables in kernel space to do the routing)

# 05-03-2018

- https://medium.com/google-cloud/this-week-in-google-cloud-platform-datastore-backups-configurable-ssl-a-new-billing-api-and-52cd3aeba9a2 Parquet with BigQuery is available! and other GCP-related gems
- http://alistair.cockburn.us/Hexagonal+architecture The Hexagonal architecture. Basically, ports (what is exposed) and adapters (what is provided). Explicit the dependencies and get the ability to create mocks (of a repository for instance). Think by feature, not by tech.
- https://medium.com/nick-tune-tech-strategy-blog/managing-complexity-in-complex-adaptive-systems-with-domain-driven-design-eb79f0ca37bb Help modelling subdomains: Event Storming, Domain Story telling, Business Model Canvas
- https://www.youtube.com/watch?v=5bgxzaHCyCs A talk by Nick Tune if you don't want to read its book :) (04-03-2018 designing-autonomous-teams-and-services)
- https://www.iravid.com/posts/resource-management.html ManagedT, or how to compose resource management. Very useful and slick. Even works with a Monoid[ResourceType].
- https://kasma1990.gitlab.io/2018/03/04/why-rust-has-macros/ Type of macros in rust: function and attributes (derive to create boilerplate, and a more generic way, still in alpha). Why use them.

# 04-03-2018

- https://blog.envoyproxy.io/envoy-threading-model-a8d44b922310 Envoy threading model – locks, logging, stats, and.. i didn't got everything!
- https://akka.io/blog/news/2018/02/23/akka-2.5.10-released Many updates in Akka: Akka Typed is there, StreamRefs (RS over the network, finally!), Artery with TCP/TLS, not production ready but still.
- http://the-paper-trail.org/blog/exactly-not-atomic-broadcast-still-impossible-kafka/#more-660 Theorical consensus can't be solved (thus no atomic broadcast, thus no exactly-once), but partial consensus can be, so Kafka can be.
- https://barryoreilly.com/2015/12/14/lean-pmo-explore-vs-exploit/ Balance exploring new business with exploiting proven existing business models – and how to transition businesses successfully between these domains
- https://barryoreilly.com/2016/01/13/lean-pmo-managing-the-innovation-portfolio/ Good post about the necessity of having a business Portfolio. Explore/Exploit/Sustain/Retire features and products. Classify them and act. Beware of the Feature Fallacy. (more features does not have necessary add value)
- http://www.oreilly.com/programming/free/designing-autonomous-teams-and-services.csp Very interesting ebook. Helps you to get insights how to break down a company business into autonomous teams and bounded contexts; identify bottlenecks; all sort of schemas to pinpoint knowledge, boundaries, and organizational behavior.

# 03-03-2018

- https://cloudplatform.googleblog.com/2018/03/queue-based-scaling-made-easy-with-new-stackdriver-per-group-metrics.html Create a pool of workers on GCE which will scale according to the lag of a pubsub subcription, and easily monitor within StackDriver

# 02-03-2018

- http://openjdk.java.net/jeps/326 JEP 326: Raw String Literals using \`...\`, handle multilines ! \o/
- https://www.prismagraphql.com/ Define your GraphQL entities, let Prisma do the rest
- https://www.infoq.com/minibooks/emag-streaming-architecture This ebook contains several topics about streaming: dataflow, dynamicdb streams, confluent, and 2 case studies, the more interesting! One from Netflix migrating batch jobs to Flink, providing tons of advices and feedbacks. As they said: "batch failures have to be addressed urgently; streaming failures have to be addressed immediately" (a perfect monitoring and alerting is needed)
- https://blogs.dropbox.com/tech/2018/03/meet-bandaid-the-dropbox-service-proxy/ A very interesting post about Dropbox's service proxy, with explications about requests dispatching strategies it handles
- https://www.wired.com/story/github-ddos-memcached/ A 1.3Tbs DDoS hit GitHub on wednesday, the largest yet recorded; using memcached amplification.

# 01-03-2018

- https://www.youtube.com/watch?v=k9rwU8G1Oi0 A quick talk about typed actors, enough to get it. Actors are becoming "Behavior" following a protocol. The root ActorSystem also has get behavior now.
- http://www.lambdadays.org/static/upload/media/1519663154528176valentinkasasthese10000classesineverwrote.pdf A truly impressive case study using recursion schemes, ana/cata to build a hylomorphism, and convert parquet<->avro<->json<->anything in a generic way with the least possible code, with validation
- https://mtlynch.io/why-i-quit-google/ A ex-Googler talking about promotion in Google, metrics oriented instead of actual work-oriented
- https://fsfe.org/freesoftware/basics/comparison.en.html Free Software, Open Source, FOSS, FLOSS - same same but different
- https://contributors.scala-lang.org/t/the-state-of-then/1638/8 Are we gonna get "then" in Scala?
- https://vimeo.com/224636602 Excellent court talk sur comment trouver sa valeur en tant qu'indépendant. D'une estimation à 150€ (en regardant son net/j), on passe facilement à 500€ pour garder le même niveau de vie (à cause des avantages qu'on avait grâce à l'employeur)
- https://cloudplatform.googleblog.com/2018/02/announcing-SSL-policies-for-HTTPS-and-SSL-proxy-load-balancers.html Create and link an SSL policy (custom or predefined) to a LB
- https://cloudplatform.googleblog.com/2018/02/fully-managed-export-and-import-with-Cloud-Datastore-now-generally-available.html Export and import with Cloud Datastore now GA!
- http://www.scalactic.org/user_guide Scalactic, originated from ScalaTest, is a small lib providing simple and useful structures such as "Or" and "Every" to type like: "String Or One[Error]", left biased; provides some "===" and neat stuff.

# 26-02-2018

- https://www.cnbc.com/2018/02/26/apple-confirms-it-uses-google-cloud-for-icloud.html So Apple iCloud is using Google Storage ? -_-
- http://www.wired.co.uk/article/google-chrome-ad-blocker-filter-how-works-coalition-ads "Chrome is removing ads from websites that don't meet standards laid out by the Coalition for Better Ads, of which Google is a founding member and has a seat on the board."
- https://support.google.com/adwords/answer/7544674 New strategy in adwords: parallel tracking. The user is directly redirected to the adservertiser website, no more redirect, better conversion
- https://developers.google.com/speed/docs/insights/rules Basic checklist to ensure website speed

# 25-02-2018

- https://adtoken.com/uploads/white-paper.pdf adChain, a protocol around the ethereum blockchain and its smart contract
- https://medium.com/@anicolaspp/java-optional-is-complicated-d6dc5c061e57 Yeah, Java Optional is crap, no surprise.
- https://lists.apache.org/thread.html/a9186930d46eba8136e6f2d29646efab33390b213515b76deea71c57@%3Cgeneral.incubator.apache.org%3E Druid into the Apache Incubator !
- https://medium.com/swlh/effective-time-management-how-to-byo-productivity-system-ae3ac3672149 Time Management tips

# 24-02-2018

- http://www.bluemintmarketing.com/blog/remarketing/ A crazy long long about Remarketing, mostly using Adwords/GA
- http://cockpit-project.org/ Easy administration of Linux servers via web browser
- http://cloudplatform.googleblog.com/2018/02/how-Google-Cloud-Storage-offers-strongly-consistent-object-listing-thanks-to-Spanner.html Google Cloud Storage offers strongly consistent object listing thanks to Spanner

# 23-02-2018

- https://stripe.com/atlas/guides/business-of-saas A wonderful article about SaaS business models
- https://blog.riseml.com/benchmarking-googles-new-tpuv2-121c03b71384 Google’s TPUv2 are faster, more expensive, but more cost efficient in the end (Tensorflow related)

# 22-02-2018

- https://medium.com/codefx-weekly/no-free-java-lts-version-b850192745fb Java 10.0.2 (July 2018) will be the last free Oracle JDK.
- https://www.youtube.com/watch?v=cCOL7MC4Pl0 Probably the best talk about javascript requestAnimatinFrame/tasks/micro-tasks processing
- https://dzone.com/articles/deploying-java-apps-with-kubernetes-and-the-ambass Using ambassador.io on k8s to manage microservices communication

# 21-02-2018

- https://dzone.com/articles/why-developers-should-bet-big-on-streaming Streaming is becoming main-stream (!)
- https://www.troyhunt.com/ive-just-launched-pwned-passwords-version-2/ 500M passwords from previous breach to download, and an free API to check if some pwd was already leaked (nice!)
- https://medium.com/actualize-network/modern-css-explained-for-dinosaurs-5226febe3525 I haven't write any css since a while but come on, it hasn't changed at the speed JS is changing at least ;-)
- https://www.youtube.com/watch?v=Txf7swrcLYs Parsing a language using Monoid (in haskell here): how, and difficulties. Very insightful.

# 20-02-2018

- https://medium.com/google-cloud/tcp-bbr-magic-dust-for-network-performance-57a5f1ccf437 TCP BBR for a better throughput in congestioned/lossy networks
- https://cloudplatform.googleblog.com/2017/11/5-steps-to-better-GCP-network-performance.html GCP: the more cpus, the greater network throughput; use internal ips when you can
- https://typelevel.org/blog/2017/02/13/more-types-than-classes.html Types are compile-time, and classes are runtime.

# 19-02-2018

- https://blogs.oracle.com/java/jdbc-next%3a-a-new-asynchronous-api-for-connecting-to-a-database Async JDBC incoming?
- https://fosdem.org/2018/schedule/event/zgc/attachments/slides/2211/export/events/attachments/zgc/slides/2211/ZGC_FOSDEM_2018.pdf The Z Garbage Collector - Bet: less than 10ms pauses, no matter the heap
- https://www.youtube.com/watch?v=qBQtbkmURiQ Shenandoah GC: less STW (not on young gen), generational hypothesis is not needed, bigger mem footprint (fwdptr), more barriers, lower throughput
- http://mrale.ph/blog/2018/02/03/maybe-you-dont-need-rust-to-speed-up-your-js.html Optimizing Javascript and V8 to get a 4x speedup, impressive profiling and fixes
- https://github.com/funfix/funfix The great author of monix is writting a fp library for js/ts inspired by monix and cats. Pretty sure it's a good quality!

# 16-02-2018

- https://randomascii.wordpress.com/2018/02/04/what-we-talk-about-when-we-talk-about-performance/ A 90% reduction in time is a ten-times speedup. We often say "90% faster" (because we optimized something and get a 90% reduction in time) when it's truly 900% faster. So we should never use this formulation.
- https://www.confluent.io/ksql-in-action-real-time-streaming-etl-from-oracle-transactional-data A wonderful article about using KSQL to create and exploit streams of data

# 15-02-2018

- https://techcrunch.com/2018/02/13/amp-for-email-is-a-terrible-idea/ AMP for email is a terrible idea; goal: ads!
- https://ops.tips/blog/nginx-http2-server-push/ Nginx now deals with HTTP2 Server Push! As a proxy, it transform h2 to http1 only (no h2 forwarding)
- https://github.com/propensive/efflorescence A nice tiny lib to deal with Google DataStore properly: ie: transparently and strongly-typed
- https://staltz.com/promises-are-not-neutral-enough.html JS Promises are like Futures in Scala. BAD! (well, Promises are worst)
- https://cloud.google.com/blog/big-data/2017/06/introducing-cloud-dataflow-shuffle-for-up-to-5x-performance-improvement-in-data-analytic-pipelines I didn't noticed before but Google has an experimental mode for Dataflow shuffling, to run it outside our the Dataflow machine to reduce its strain.

# 14-02-2018

- http://blog.xebia.fr/2016/03/16/perennisez-votre-metier-avec-larchitecture-hexagonale/ L'architecture hexagonale ftw !
- https://github.com/propensive/kaleidoscope/ A new lib from propensive, to compile-time check strings in pattern matching
- http://www.scylladb.com/2017/10/05/io-access-methods-scylla/ Different I/O access methods; mmap; sync/async direct io; tradeoffs with kernel, scheduling, cache control
- http://xcorpion.tech/2016/09/10/It-s-all-about-buffers-zero-copy-mmap-and-Java-NIO/ Some reminders about zero-copy and mmap

# 13-02-2018

- https://alexn.org/blog/2018/02/12/in-defense-oofp.html OO+FP. A regard on Scala Collection. I didn't get the whole code (when dealing with the Suspendable thing) but I get the idea.
- https://medium.com/@leventov/comparison-of-the-open-source-olap-systems-for-big-data-clickhouse-druid-and-pinot-8e042a5ed1c7 A comparaison between ClickHouse, Druid and Pinot (OLAP dbs)

# 12-02-2018

- https://www.opsian.com/blog/top-3-java-performance-improvements/ More to Java 10+: Value type "Valhalla" to avoid object reference (think C struct) and primitive specialization à la Scala; new GCs: Shenandoah and ZGC (low pauses on large heaps); and maybe NIO API improvements
- http://joelgrus.com/2016/05/23/fizz-buzz-in-tensorflow/ Hilarious -fake- job interview of a person implementing fizzbuzz with tensorflow
- http://www.lihaoyi.com/post/PrinciplesofAutomatedTesting.html Considerations and opinions about testing strategies in general, test should respects the same rules of quality and review as non-test code, dsls, unit vs integration (means nothing truly), example vs bulk (ie: scalacheck, prod data)

# 11-02-2018

- https://ordina-jworks.github.io/microservices/2016/04/22/Lagom-First-Impressions-and-Initial-Comparison-to-Spring-Cloud.html Lagom's impression... in 2016! The Java version is just so verbose. :(
- https://techbeacon.com/project-management-surefire-way-kill-your-software-product Sweet post critizing project management for being centered on the project, not the product. Projects metrics are not a measure of success. Product metrics (with customers) are. Guesstimate is useless.
- https://www.pluralsight.com/blog/software-development/java-9-new-features Java 9: modules with proper resolution at startup (Jigsaw); jlink to create minimal image; jshell; new collections and stream methods; interface private methods; new HttpClient (handle h2) to replace HttpURLConnection; no more jre/ in jdk/.
- http://openjdk.java.net/jeps/282 JEP 282: jlink: The Java Linker— Nice to package "only what you need"; it relies on Java 9 modules
- https://security.googleblog.com/2018/02/a-secure-web-is-here-to-stay.html The fateful date is coming: July 2018: HTTP = "Not secure"

# 10-02-2018

- https://thoughts.t37.net/migrating-a-130tb-cluster-from-elasticsearch-2-to-5-in-20-hours-with-0-downtime-and-a-rollback-39b4b4f29119 Migrating a 130TB Cluster from Elasticsearch 2 to 5, interesting insights
- https://github.com/elastic/elasticsearch-migration/tree/2.x A migration check tool for elastichsearch clusters
- http://scala-lang.org/blog/2018/02/09/collections-performance.html Performance about the "new" view-based Collections; also with some StrictOptimized* version
- http://scala-lang.org/blog/2017/11/28/view-based-collections.html view based collections (lazy by default) for the new Scala collection

# 09-02-2018

- http://www.bigeng.io/elasticsearch-scaling-multitenant/ A very interesting post about optimizing elasticsearch in a multitenant environment
- https://velotio.com/blog/2017/7/5/http-load-balancing-in-kubernetes-with-ingress Simple Ingress on GCP
- https://www.confluent.io/blog/enabling-exactly-kafka-streams/ How Exactly-Once works in Kafka Streams
- https://github.com/milessabin/docs.scala-lang/blob/c6092426d3a8978613ce109d50026a9a0b496aeb/_sips/sips/2017-09-20-opaque-types.md Scala Value classes are sometimes not unwrapped at compile-time. opaque types to the rescue!
- https://www.youtube.com/watch?v=VaWgOCDBxYw More JMH evil
- https://www.youtube.com/watch?v=Bi0E7w1ZFFA Quick intro to JMH powa
- https://www.youtube.com/watch?v=YgGAUGC9ksk Very good talk about String methods, optimizations and tradeoffs
- https://www.youtube.com/watch?v=wIyeOaitmWM Aleksey Shipilëv on Compact Strings; some parts are quite advanced, and it seems to be a real mess to optimize those Strings :)
- https://shipilev.net/talks/devoxx-Nov2012-perfMethodology.pdf A very good ("old" but still relevant) recap of how to monitor/understand/fix performance issues

# 08-02-2018

- https://trac.webkit.org/changeset/228266/webkit native .flatmap now in webkit! Soon, the monads.

# 07-02-2018

- https://zeit.co/blog/streaming-server-rendering-at-spectrum Streaming SSR content ftw
- https://manuel.bernhardt.io/2017/07/26/a-new-adaptive-accrual-failure-detector-for-akka/ Another adaptive accrual failure detector for Akka
- https://www.confluent.io/blog/handling-gdpr-log-forget/ No magic: compacted topics, CDC
- https://speakerdeck.com/ianlewis/kubernetes-security-best-practices Kubernetes Security Best Practices

# 06-02-2018

- http://enear.github.io/2016/09/27/bits-of-shapeless-2/ Generic Derivation in shapeless. The little tour about literal types is almost absolete thanks to the native integration in Scala 2.13!
- https://github.com/graphcool/prisma easily implement a graphql server over any database
- https://blog.mozilla.org/security/2018/01/31/preventing-data-leaks-by-stripping-path-information-in-http-referrers/ Firefox will automatically add a "Referrer Policy" to avoid leaking querystring and hash to third parties
- https://tech.travelaudience.com/bigtable-storing-protobuf-bytes-in-one-column-vs-splitting-the-content-into-column-families-c231bdff8db7 Storing protobuf into one col (instead of splitting in numerous cols) uses less cpu (on bigtable) and is easier to deal with read pattern modification and evolution
- https://markmanson.net/how-to-let-go Life is a long series of losses. Think about it.

# 05-02-2018

- https://gravitational.com/blog/kubernetes-release-cycle/# The full-time job of keeping up with Kubernetes
- https://github.com/facebook/osquery A damn good idea: query all your system parts using SQL
- https://www.cakesolutions.net/teamblogs/demystifying-the-blocking-construct-in-scala-futures A complete post about the "blocking" in Scala. Only works with the global ExecutionContext (or you need to DIY)

# 04-02-2018

- http://www.corbinstreehouse.com/blog/2018/01/code-reviews-part-1-dont-do-them/ Surprising opinion: "Code reviews: don't do them"

# 03-02-2018

- https://www.youtube.com/watch?v=_Cct8b8OO2E Measure everything with Kamon (1.0.0) + prom + spans (opentracing)
- https://hackernoon.com/part-2-how-to-stop-me-harvesting-credit-card-numbers-and-passwords-from-your-site-844f739659b9 How to secure sensitive pages: csp is not enough: iframe, another domain, postMessage (iframe -> parent)
- http://www.tomanthony.co.uk/blog/googlebot-javascript-random/ Identifying Googlebot by checking random() which is deterministic in its case

# 02-02-2018

- https://github.com/Gabriel439/slides/blob/master/bigtechday/slides.md Everything is a monoid
- https://www.emnify.com/2018/02/01/monitoring-with-kamon-1-0/ kamon and prometheus ftw
- https://developer.lightbend.com/blog/2018-02-01-sbt-1.2-roadmap/ sbt 1.2.0 roadmap
- https://docs.scala-lang.org/sips/42.type.html Literal-types in Scala 2.13, useful for refined types or typed-key records (product types without case classes, hlist for instance)
- https://docs.google.com/presentation/d/1_dxtzcBaf8OfYGM-vsAJnXUJvDgmFWZJM0tmtDJoVGU/ Feedback from Algolia about scaling up
- https://www.troyhunt.com/streamlining-data-breach-disclosures-a-step-by-step-process/ Nice "guide" about contacting a company to reveal a data breach
- https://sap1ens.com/blog/2018/01/03/message-enrichment-with-kafka-streams/ Very good post about message enrichment with Kafka Streams
- https://github.com/lihaoyi/sourcecode Scala implicits to get source code metadata (filename,line, method name..)

# 01-02-2018

- https://github.com/jsverify/jsverify ScalaCheck/QuickCheck in JS :-) Property-based testing
- http://www.dwmkerr.com/the-death-of-microservice-madness-in-2018/ Some feedback and interrogation to ask yourself when dealing with microservices
- http://www.rigacci.org/wiki/lib/exe/fetch.php/doc/appunti/linux/sa/iptables/conntrack.html how conntrack works (connections state in a memory state), use within iptables
- https://queue.acm.org/detail.cfm?id=3096459 The Calculus of Service Availability - interesting insights from a Googler about SLO/SLA formula, dependencies, thresholds

# 31-01-2018

- http://www.securityweek.com/microsoft-disables-spectre-mitigations-due-instability Spectre mitigations causing instabilities is disabled -_-
- https://github.com/esimov/caire A "content aware way" to resize an image (by altering the content itself, without "losing" content)
- https://github.com/google/xi-editor A new future awesome text (code?) editor (in Rust!) ?
- https://github.com/developit/greenlet Multithreading made very easy and not verbose in js (ww)

# 27-01-2018

- https://github.com/akka-js/akka.js Akka compliant to Scala.js Oo
- https://emails.hteumeuleu.com/email-accessibility-in-action-f7f9d945cf67 Add relevant alt on imgs, role="presentation" on <tables> used for layout (emails!), lang="xx" 
- http://co.ntextu.al/ Write string interpolators with custom checks; provides classic ones such as email, hex, regex
- https://to-ithaca.github.io/libra/ A dimensional analysis lib, to check if addition/product on types makes sense ("mass + speed" ?!). Basically: don't deal with simple Doubles everywhere.
- https://contributors.scala-lang.org/t/whitebox-def-macros/1210 Debate about whitebox def macros, lots of good insights

# 25-01-2018

- https://v8project.blogspot.fr/2018/01/speedometer-2.html Optimization in V8 are quite remarkable
- https://medium.com/@devongovett/parcel-v1-5-0-released-source-maps-webassembly-rust-and-more-3a6385e43b95 Parcel has such a huge momentum. Now includes: Source Maps, WebAssembly, Rust. No Config at all ! 
- https://facebook.github.io/prophet/docs/quick_start.html Prophet forecasts data with uncertainty intervals (Python and R apis)
- https://github.com/MfgLabs/akka-stream-extensions Some great Akka Stream extensions for postgresql, elasticsearch, shapeless, s3
- http://di-in-scala.github.io/ Compile-time DI is so much better! No more Java runtime stuff stupidities.
- http://anthonycros.com/turn-scala-into-spark/ Very strong similitude between a plain Scala program using the stdlib and its Spark equivalent

# 24-01-2018

- https://adriaanm.github.io/reveal.js/scala-2.13-beyond.html#/7 Scala 2.14 will be so good! simpler, faster, stronger!
- http://marxsoftware.blogspot.fr/2018/01/schopenhauers-law-immutability.html In Java, things are not Immutable but _Unmodifiable_ 
- http://mail.openjdk.java.net/pipermail/jmh-dev/2018-January/002723.html JMH 1.20 out! fixes and impro, better java9 compat, perfasm on osx
- https://medium.com/actualbudget/balancing-product-and-technology-e525dd82c05a Some feedback on product and technologu from a great developer. Looks like DDD.

# 23-01-2018

- https://github.com/developit/karmatic Automatic (headless) browser testing. Karma/Webpack/Jasmine. 0 config tools are the best.
- https://twitter.com/DasSurma/status/955484341358022657 Deep copying a JS object with clever means: the history API, or the MessageChannel for workers x_x
- https://www.youtube.com/watch?v=CUVOBANHzpo Why Akka streams rocks for high throughput
- https://dzone.com/articles/microprofile-enhances-microservices-for-java MicroProfile is a project to make jvm microservices-oriented (config, fault tolerance, health check, metrics, auth)
- https://www.thoughtworks.com/radar ThoughtWorks has a really great tech radar split in several domains (techniques, tools, platforms, languages)
- https://en.fabernovel.com/insights/tech-en/akka-typed Another example of using Akka typed. Much more verbose but at least, it's compile-time type-checked!
- https://medium.com/@ericsimons/introducing-turbo-5x-faster-than-yarn-npm-and-runs-natively-in-browser-cc2c39715403 Loading lazily packages instead of being eager: way less to dl=faster, and can work in a web browser now

# 22-01-2018

- https://github.com/etaty/scalacheck-magnolia generate random instances of case classes / ADT with ScalaCheck, priceless!
- https://www.youtube.com/watch?v=KaLROwp-VDY "How to get productive in a project in 24h": look at tests, coverage, cyclomatic complexities, git often changes files

# 21-01-2018

- https://blog.openai.com/scaling-kubernetes-to-2500-nodes/ "Scaling Kubernetes to 2,500 Nodes" Issues with etcd fluentd kubedns docker image pulls and arp caches
- http://blog.kubernetes.io/2017/10/using-rbac-generally-available-18.html RBAC GA since Kubernetes v1.8
- https://www.youtube.com/watch?v=JHGkaShoyNs Great talk by Greg Young about CQRS and Event Sourcing
- https://www.slideshare.net/quipo/nosql-databases-why-what-and-when/ Very good slides from 2011 about consistency, distributed strategies, bigtable, nosql dbs..

# 20-01-2018

- https://www.youtube.com/watch?v=EDLAdgAVyFU Functional Foundation of Event Sourced Application (from Lagom team)
- https://www.youtube.com/watch?v=__zuECMFCRc From basic API to functional API
- https://developer.lightbend.com/blog/2018-01-17-akka-multidc/ Akka Multi-DC: Akka persistence replicas across different DCs
- http://docs.scala-lang.org/sips/pending/static-members.html.html SIP 25 - @static fields and methods in Scala objects
- http://debezium.io/blog/2018/01/17/streaming-to-elasticsearch/ MySQL to elastic and postgres, using debezium and kafka-connect
- https://www.blog.google/topics/google-cloud/cloud-automl-making-ai-accessible-every-business/ Cloud AutoML available, starting with Vision !
- https://towardsdatascience.com/how-to-create-data-products-that-are-magical-using-sequence-to-sequence-models-703f86a231f8 seq2seq models to predict github issues title from content
- https://martinfowler.com/bliki/IntegrationTest.html Integration tests vs end-to-end tests
- https://hacks.mozilla.org/2018/01/making-webassembly-even-faster-firefoxs-new-streaming-and-tiering-compiler/ Streaming and tiering WebAssembly compiler in Firefox
- http://kamon.io/teamblog/2018/01/18/kamon-1.0.0-is-out/ Kamon 1.0 is out! More Prometheus and Open Tracing oriented <3
- https://intoli.com/blog/not-possible-to-block-chrome-headless/ Bypassing the Chrome Headless detector tests

# 19-01-2018

- https://jakubstransky.com/2017/11/27/structure-of-java-virtual-machine-jvm/ Structure of Java Virtual Machine (JVM)
- https://www.confluent.io/blog/put-several-event-types-kafka-topic/ Martin Kleppmann on "Should You Put Several Event Types in the Same Kafka Topic?": it's rarely the case
- http://highscalability.com/blog/2018/1/16/monolith-or-microservices-which-should-you-start-with.html Monolith or Microservices: Which should you start with? Some very good advices. You know with it if you know them \o/
- https://github.com/benjojo/dnsfs dnsfs: Store your data in others DNS revolvers cache
- https://www.buzzfeed.com/tomphillips/twitterstorm-2018 This is a funny must-read. It traces how a twitterstorm appears from a tiny thing and gets totally out of control. (it's fake but so "plausible" ahah)

# 18-01-2018

- https://github.com/GoogleChrome/dialog-polyfill I didn't even remembered HTML had a <dialog> !
- https://github.com/Chymyst/curryhoward Generate code for full parametric functions (through macros) automatically from the function signature :o
- https://github.com/NervJS/nerv Another "blazing fast React alternative"

# 16-01-2018

- https://github.com/scala/collection-strawman/pull/342 New immutable hash set and map in Scala's collection-strawman (using CHAMP)

# 15-01-2018

- https://www.youtube.com/watch?v=STKCRSUsyP0 The Many Meanings of Event-Driven Architecture - Martin Fowler
- http://blog.ploeh.dk/2018/01/15/unit-isomorphisms/ Unit isomorphisms
- https://github.com/boopathi/babel-time-travel "Time travel through babel transformations one by one." Interesting to see the "way"
- https://building.coursera.org/blog/2016/12/01/should-engineering-managers-write-code-wrong-question/ "Should engineering managers write code? Wrong question." => "Where to write code?"
- https://rreverser.com/writing-complex-macros-in-rust/ Writing complex macros in Rust: Reverse Polish Notation
- https://www.washingtonpost.com/news/post-nation/wp/2018/01/14/hawaii-missile-alert-how-one-employee-pushed-the-wrong-button-and-caused-a-wave-of-panic/?utm_term=.cc967e072831 "Hawaii missile alert: How one employee ‘pushed the wrong button’ and caused a wave of panic" That's nuts

# 12-01-2018

- https://craftsmen.nl/memory-usage-6-popular-rest-server-frameworks-compared/ Comparing memory usage of Spring/Play/Vertex/Jersey/..
- https://github.com/emilwallner/Screenshot-to-code-in-Keras a NN to convert mockups to actual HTML \o/

# 10-01-2018

- https://www.youtube.com/watch?v=gH5mPaLU8_g Quelques raisons pour coder du Rust venant de Scala :-)
- https://webkit.org/blog/8048/what-spectre-and-meltdown-mean-for-webkit/ What Spectre and Meltdown Mean For WebKit

# 09-01-2018

- https://jobs.zalando.com/tech/blog/why-we-do-scala/ All the things we like using  Scala <3
- https://zalando.github.io/tech-radar/ Zalando has a public "tech radar", awesome company !
- https://letsencrypt.org/2017/12/07/looking-forward-to-2018.html Free wildcard certifs for all \o/
- https://www.smashingmagazine.com/2018/01/visual-studio-code/ Yeah, VSCode is a great editor full of features
- http://blackswanfarming.com/cost-of-delay/ Thinking about cost and delay: what are they, how to know the impact of time on the outcomes
- http://kroah.com/log/blog/2018/01/06/meltdown-status/ Meltdown and Spectre Linux kernel status - <3 to the kernel developers
- https://techcrunch.com/2018/01/08/james-damore-just-filed-a-class-action-lawsuit-against-google-saying-it-discriminates-against-white-male-conservatives/ James Damore just filed a class action lawsuit against Google, saying it discriminates against white male conservatives | It' a must read, especially the official lawsuit document. Tons of screenshots and discussions.
- https://www.ultimategdprquiz.com/ The Ultimate GDPR Quiz— Not easy to get 10/10 :x
- https://www.youtube.com/watch?v=s3ljANN80R4 Speedup .scala compilation with Hydra (stil early access)
- https://shipilev.net/jvm-anatomy-park/20-fpu-spills/ SSE instructions and xmm registers used as fast storage thanks the UseFPUForSpilling jvm flag (enablde by default): it avoids to use the "slower" L1 cache

# 08-01-2018

- http://boristyukin.com/benchmarking-apache-kudu-vs-apache-impala/ According to the author Kudu >> Parquet with Impala with some "minor" catches. Not the xp I got (size in kudu was ++, kudu couln't remove deleted data from disk, kudu was sometimes stuck and needed weekly reboot (despite plenty of mem)..)
- https://washingtonmonthly.com/magazine/january-february-march-2018/how-to-fix-facebook-before-it-fixes-us/ How to Fix Facebook—Before It Fixes Us.  "Fear and anger produce a lot more engagement and sharing than joy." "The result is that everyone sees a different version of the internet tailored to create the illusion that everyone else agrees with them" Trump's Russia-gate.
- https://www.youtube.com/watch?v=jd5e71nFEZM This was a very good explanation about monad transformers

# 07-01-2018

- https://lwn.net/Articles/741897/ Demystifying container runtimes
- https://hackernoon.com/im-harvesting-credit-card-numbers-and-passwords-from-your-site-here-s-how-9a8cb347c5b5 A definitely realistic post about the "easiness" of injecting any code on "any" website that uses npm packages. (thus stealing anything it wants)
- https://github.com/0xAX/linux-insides Wonderful bits about Linux kernel. More than 800 pages of "bits" already.
- https://www.youtube.com/watch?v=qwYs0J7xp78 type-safety in CQRS (linked model to events and commands types)
- https://www.youtube.com/watch?v=778znDnjROg gRPC with ScalaPB newbie talk
- https://www.youtube.com/watch?v=Z6_Nd7lu2PI Event Sourcing and CQRS using Lagom

# 06-01-2018

- http://psy-lob-saw.blogspot.fr/2013/05/know-thy-java-object-memory-layout.html TIL about False Sharing (adding padding in object to keep values in cache)
- https://www.youtube.com/watch?v=wi97X8_JQUk Monix talk by Monix creator
- https://www.youtube.com/watch?v=hr3UdktX-As Akka anti-patterns (use a hierarchy! supervision is there for this. never block, use pipe. never pass outside mutable state. etc.)
- https://gist.github.com/djspiewak/7a81a395c461fd3a09a6941d4cd040f2 Good to know: the type parameters we expect users to vary should be declared the right-most.
- https://developer.lightbend.com/blog/2018-01-05-kafka-streams-scala-goodies-part-2/ Provide a simili-global state from any node
- https://github.com/raphaelsc/Am-I-affected-by-Meltdown Proof-of-concept / Exploit / checks whether system is affected by Variant 3: rogue data cache load (CVE-2017-5754), a.k.a MELTDOWN.
- https://developer.lightbend.com/blog/2018-01-05-kafka-streams-scala-goodies-part-1/ If Lightbend has a Scala wrapper on top of kafka streams java, that means it will be maintained! +1
- https://www.raspberrypi.org/blog/why-raspberry-pi-isnt-vulnerable-to-spectre-or-meltdown/ No speculative execution on Rasp: no attack possible \o/
- https://font-display.glitch.me/ getting control of font appearance when font is not downloaded yet, using "font-display"

# 05-01-2018

- https://support.google.com/faqs/answer/7625886 Google providing Retpoline: a software construct for preventing branch-target-injection
- https://blog.statsbot.co/deep-learning-achievements-4c563e034257 Deep Learning achievements over 2017: this is nuts
- https://www.youtube.com/watch?v=IhVdU4Xiz2U A nice talk comparing Free monads and tagless final
- https://kwark.github.io/refined-in-practice/ Refinement Types looks very interesting. The drawbacks are not important enough compared to the advantages! (basically validation on the type level)

# 04-01-2018

- https://googleprojectzero.blogspot.fr/2018/01/reading-privileged-memory-with-side.html Interesting details about the current global bug to read privileged memory with a side-channel. It's basically based on speculative execution+cache+timing to evaluate if 0 or 1
- http://pepegar.com/hammock/ Hammock is like sttp, a generic http client with different backends. And is also functional oriented (Free, IO) <3

# 03-01-2018

- https://www.youtube.com/watch?v=WscozkoXLHM Very good talk about exactly once kafka semantics
- https://www.youtube.com/watch?v=ewe3-mUku94 ASLR kernel attack using Javascript: performance.now() and SharedArrayBuffer. Unfortunately, the speaker is not good at all.
- http://pythonsweetness.tumblr.com/post/169166980422/the-mysterious-case-of-the-linux-page-table The story of the "Address Space Layout Randomization" kernel attack; could lead to hypervisor privileges escalation
- https://www.zachaysan.com/writing/2017-12-30-zero-width-characters Fingerprinting with Zero-Width Characters and homoglyths. Love it!

# 02-01-2018

- https://github.com/javascript-obfuscator/javascript-obfuscator JS obfuscators are getting back

# 01-01-2018

- https://minnenratta.wordpress.com/2017/01/25/things-i-have-learnt-as-the-software-engineering-lead-of-a-multinational/ a 36-bullet point that makes quite sense, to rea for any developer/software lead

# 31-12-2017

- https://code.facebook.com/posts/1478526992216557/migrating-a-database-from-innodb-to-myrocks/ How Facebook migrates from InnoDB to MyRocks (mysql backed by rocksdb)
- https://www.youtube.com/watch?v=Tkjg179M-Nc Talk about "Stream I/O" by Andre 'Staltz' Medeiros, where cycle.js idea comes from
- https://www.slideshare.net/mpilquist/scalaz-13068563 A very nice prez on Scalaz, now I understand everything :-)

# 30-12-2017

- https://softwaremill.com/applicative-functor/ Another explanation about the applicative functors
- https://www.youtube.com/watch?v=1bNOO3xxMc0 Queue theory reminds me of reactive programming. Need to handle backpressure. Queues are everywhere. Gather metrics (queues, threads pools). Plan your app for "too much data".
- https://www.wsj.com/articles/the-worst-job-in-technology-staring-at-human-depravity-to-keep-it-off-facebook-1514398398 Content moderators on social networks: clearly not an easy job that can totally mess you up
- https://github.com/lllyasviel/style2paints Any sketch images colorized and painted :o (CNN)

# 29-12-2017

- https://gist.github.com/rondy/af1dee1d28c02e9a225ae55da2674a6f A very nice review of the book: the Effective Engineer
- https://www.iravid.com/posts/contravariant-functors.html contravariant functors and contravariant applicatives
- https://gist.github.com/djspiewak/464c11307cabc80171c90397d4ec34ef JVM optim: define the hot path, don't allocate in there, identity boxing, keep things monomorphics
- https://medium.com/@fwbrasil/quill-spark-a-type-safe-scala-api-for-spark-sql-2672e8582b0d A type-safe Scala API for Spark SQL
- https://www.iravid.com/posts/fp-and-spark.html Using Monix Task and cats StateT into Spark to make it more functional.
- https://github.com/findify/scala-packed an interesting concept where classic Scala collections type are backed by bytes (to avoid case class overhead, header etc.), bytes efficient.
- https://siliconangle.com/blog/2017/07/12/lightbend-startup-behind-scala-programming-language-bags-15m Lightbend raises $15M. More Scala! <3

# 28-12-2017

- https://blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc Service mesh data plane vs. control plane. Thanks! Now i get it.
- https://shipilev.net/jvm-anatomy-park/18-scalar-replacement/ HotSpot's Escape Analytics analyzed
- http://slides.com/pdolega/slick-101#/ A nice presentation about Slick features, with monads and applicatives comparaison

# 27-12-2017

- https://www.youtube.com/watch?v=B37UbzPlSzw is IOTA the future "blockchain" err, "blockdag"? scalable, quantum resistant, no fees..
- https://www.youtube.com/watch?v=1eg0ahHtxcQ Microservices & DDD
- https://banzaicloud.com/blog/spark-monitoring/ Monitoring Apache Spark with Prometheus on Kubernetes. Buzzzzing!
- http://blog.cloudera.com/blog/2017/12/faster-performance-for-selective-queries/ Combining partitioning+clustering (sort by (x, y, ..) in create ddl) for maximum partition pruning, very useful!
- https://cloud.google.com/blog/big-data/2017/12/busting-12-myths-about-bigquery Busting 12 myths about BigQuery. I wasn't aware of the point-in-time snapshot feature. But it makes sense, because bq is bigtable behind the scene.
- http://highscalability.com/blog/2015/3/9/the-architecture-of-algolias-distributed-search-network.html Algolia’s architecture explained (from 2015), quite interesting
- https://medium.com/@addyosmani/a-tinder-progressive-web-app-performance-case-study-78919d98ece0 Very nice case study to review all what makes a performant webapp
- https://danluu.com/input-lag/ Keyboard to screen latency, from 1977 to 2017. We didn't really improve /o\
- https://www.theguardian.com/world/2017/apr/14/what-is-the-historical-evidence-that-jesus-christ-lived-and-died Always question believers facts
- https://www.youtube.com/watch?v=o7wtlMb_Qv0 Microservices, talk by Vaughn Vernon
- https://www.youtube.com/watch?v=v7b4J2INq9c Microsoft Quantum Development Kit: Introduction

# 26-12-2017

- https://lemire.me/blog/2017/12/26/personal-reflections-on-2017/ More VR, more AI, data engineering is currently a mess, perf & latency greatly sucks (surprisingly), and other interesting stuff
- https://blog.alexellis.io/the-state-of-netbooting-raspberry-pi/  netbooting RPi is cool but full of terrors (unstable at boot, docker containers can't work because of its CoW filesystem which doesn't work through NFS..)
- https://shipilev.net/jvm-anatomy-park/15-just-in-time-constants/ JIT constants optimized
- https://github.com/akarnokd/async-enumerable asynchronous enumerable: moveNext() returns a Future[Boolean] and not just a Boolean
- https://medium.com/@arschles/go-experience-report-generics-in-kubernetes-25da87430301 Apparently, k8s simulates some kind of genericity in its codebase through the usage of a custom "runtime.Object" that looks like Java's Object?
- https://shipilev.net/jvm-anatomy-park/14-constant-variables/ eager "final" vars value is inline, lazy final values are not
- https://medium.com/bread-and-circuses/how-i-got-paid-0-from-the-uber-security-bug-bounty-aa9646aa103f Uber Security Bug Bounty program looks like a joke. Dude found several important flaws and earned 0$.
- https://github.com/aboul3la/Sublist3r subdomains enumeration tool for penetration testers
- https://www.sans.org/reading-room/whitepapers/tools/os-application-fingerprinting-techniques-1891 OS and Application Fingerprinting Techniques

# 25-12-2017 :christmas_tree:

- https://medium.com/@domagojk/patterns-for-designing-flexible-architecture-in-node-js-cqrs-es-onion-7eb10bbefe17 A nice presentation with code in JS of CQRS+ES
- https://softwaremill.com/reactive-streams-in-scala-comparing-akka-streams-and-monix-part-3/ This time, comparing with "load balancer" pattern. I prefer Akka Streams on this one, it's way more explicit and clear
- http://blog.soat.fr/2017/07/pourquoi-et-sous-quel-condition-utiliser-les-microservices/ microservices, microservices!
- http://highscalability.com/blog/2017/12/11/netflix-what-happens-when-you-press-play.html Netflix: What Happens When You Press Play? Video starts.
- http://www.michaelnygard.com/blog/2017/12/the-entity-service-antipattern/ The Entity Service is an antipattern in the sense that the services are not autonomous (not context bound)

# 24-12-2017

- https://github.com/spotify/featran A nice and small Scala feature transformation library for ML
- https://www.youtube.com/watch?v=1dchSsac3T4 Spotify's Scio
- https://goo.gl/mn6ZJB Prepack now understands React components and can inline them (alpha)
- http://www.chriskrycho.com/2017/chrome-is-not-the-standard.html Friendly reminder: Chrome is not the standard. The web platform is managed by several actors.
- https://dzone.com/articles/reactive-spring-5-and-application-design-impact Reactive Spring 5: the reactive parts
- https://blogs.windows.com/msedgedev/2017/12/19/service-workers-going-beyond-page/#Omf2eUtrEwXV06i0.97 Edge finally handle SWs by default, and they did a nice recap' of why SWs are useful

# 23-12-2017

- http://larahogan.me/blog/desk-moves/ Interesting insights over human emotions when managing them (here: around desk moves task). Belonging. Improvement/Progress. Choice. Equality/Fairness. Predictability. Status.
- http://2ality.com/2017/11/about-reasonml.html A nice series of post to discover ReasonML

# 21-12-2017

- https://github.com/ballercat/walt Walt is a cool idea to write JavaScript-like syntax to be compiled to WebAssembly without the LLVM overhead
- https://www.youtube.com/watch?v=g_jP47HFpWA Daniel Spiewak talking about IO monad, very good
- https://www.confluent.io/blog/ksql-december-release KSQL or writing streamers with SQL, love it!
- https://www.youtube.com/watch?v=aWI7iU36qv0 Let's put a happy music in the background to explain microservices \o/
- https://www.geekbench.com/blog/2017/12/iphone-performance-and-battery-age/ Apple strategy: underclocking phone's cpu according the battery age
- https://www.forbes.com/sites/thomasbrewster/2017/12/19/120m-american-households-exposed-in-massive-consumerview-database-leak/#1a73d6f07961 This is nuts. The company trying to minimize the impact of such leak.. what a shitty behavior.
- https://blog.cloudflare.com/this-is-strictly-a-violation-of-the-tcp-specification/ Very informative article about localhost loophole congestion
- https://www.propublica.org/article/facebook-ads-age-discrimination-targeting Is it not better to prevent ppl you wouldn't hire to apply anyway?

# 20-12-2017

- https://www.slideshare.net/HadoopSummit/hadoop-3-in-a-nutshell Basically Hadoop 3 in a cleanup of codebase and a big YARN refacto
- https://www.justinobeirne.com/google-maps-moat A damn good article on the evolution of Google Maps quality

# 19-12-2017

- https://swizec.com/blog/blockchain-backed-redux-clone-105-lines-code/swizec/7980 blockchain in the new TODO
- https://codeburst.io/the-future-of-javascript-will-be-less-javascript-cea373eb57fd Nobody will "do" true JS, but all will compile to JS (as today..) because it's the "VM" browsers undertand (well, and wasm is coming too)
- http://woz.posthaven.com/what-orms-have-taught-me-just-learn-sql Benefits and drawbacks of ORMs (+simplity/+complexity)
- http://jonasboner.com/bla-bla-microservices-bla-bla/ "Asynchronous Communication, Isolation, Autonomicity, Single Responsibility, Exclusive State, and Mobility. These are the core traits of Microservices."
- https://v8project.blogspot.fr/2017/12/v8-release-64.html V8 still adding some optimizations (bind, Weak*, slice/filter) and smaller memory footprint
- https://staltz.com/a-plan-to-rescue-the-web-from-the-internet.html Is the future is mobile mesh networks?
- https://github.com/Jam3/math-as-code a cheat-sheet for mathematical notation in code form, quite straight-forward

# 17-12-2017

- https://www.youtube.com/watch?v=H28QqxO7Ihc Tagless final using Free applicatives
- https://www.youtube.com/watch?v=MvQxNm5gn8g Quite clear explanations about the usage of the category theory, from a Scala programmer perpective
- https://kubernetes.io/case-studies/blablacar/ BlaBlaCar case study of its k8s usage
- http://blog.kubernetes.io/2017/12/kubernetes-19-workloads-expanded-ecosystem.html Kubernetes 1.9 out. Apps Workloads GA and Expanded Ecosystem

# 16-12-2017

- https://github.com/facebook/Docusaurus Documentation made easy on gh-pages

# 15-12-2017

- https://developers.google.com/web/tools/chrome-user-experience-report/#best-practices A new public dataset on bigquery that exposes measurements of metrics across web (features, connections type, ...)
- https://github.com/pauljamescleary/scala-pet-store An implementation of some classic store using http4s/doobie/circe
- https://www.lyranthe.org/presentations/http4s_doobie_circe.pdf A presentation on http4s/doobie/circe used together

# 14-12-2017

- https://stackshare.io/dubsmash/dubsmash-scaling-to-200-million-users-with-3-engineers Dubsmash: Scaling To 200 Million Users With 3 Engineers, many technologies used + Amazon and Gcloud, very good team!
- https://getstream.io/blog/switched-python-go/ "Why We Switched from Python to Go", perf; easier to keep it simple; go/chan; compile time; grpc
- https://www.nytimes.com/2017/12/14/technology/net-neutrality-repeal-vote.html Net Neutrality is down. That's a very bad news and the beginning of many problems.
- https://nd4j.org/index.html Dealing with N-dimensional arrays in Java, supporting CUDA for some hyper-quick GPU computing
- https://www.youtube.com/watch?time_continue=2&v=Bbw1ki-U-QY overview of AI Starcraft(s) bots techinics

# 10-12-2017

- https://blog.scalac.io/2016/06/02/overview-of-free-monad-in-cats.html This was an nice completary post to the cats Free doc. (note: the code in the post is based on a old cats version)
- https://github.com/mil-tokyo/webdnn with webdnn, we can execute DNN pipelines in the browser
- http://make.girls.moe/ An anime characters generators based on NN (we can pickup lots of aspects and ask for generation). 
- https://medium.com/4iqdelvedeep/1-4-billion-clear-text-credentials-discovered-in-a-single-database-3131d0a1ae14 clear passwords are the biggest mistake in IT
- https://github.com/fosskers/scalaz-and-cats Comparisons and usage examples between Scalaz and Cats
- https://kerpanic.wordpress.com/2017/12/10/macbook-pro-2016-1-year-later-from-a-devs-perspective/ No GPU-accelerated Tensorflow on macbooks :-( (no nvidia)

# 09-12-2017

- https://brianmckenna.org/blog/constraints_are_for_methods A point in Scala explaining that Type constraints are for methods, not data (ie: not on the class itself)
- https://gist.github.com/staltz/08bf613199092eeb41ac8137d51eb5e6 People seems to forget about the "state" part in React to manage internal updates, interesting problematic inside anyway

# 08-12-2017

- https://www.youtube.com/watch?v=Y-cPVQaXlMw&list=PLjkHSzY9VuL8hRtytRxvO5gheXHWWdU9A&index=6 A really good FR talk about free monads and cooking
- https://groups.google.com/a/chromium.org/forum/#!msg/blink-dev/MbXp16hQclY/bQjegyrbAgAJ dev will have the ability to "async" image processing to get better responsiveness.
- https://ipdata.co/index.html a (free) IP Geolocation API, always good to have one
- https://github.com/sindresorhus/refined-twitter Simple but useful (can be done through Stylish too): simplify Twitter UI \o/

# 07-12-2017

- https://cloud.google.com/blog/big-data/2016/07/using-the-cloud-natural-language-api-to-analyze-harry-potter-and-the-new-york-times A very nice intro and easy usage of Google NLP API
- https://www.washingtonpost.com/news/the-switch/wp/2017/12/07/amazon-wants-a-key-to-your-house-i-did-it-i-regretted-it/ I was not aware such a thing exist: electronic keys+cam for delivery guy to drop packages into the house
- https://medium.com/airbnb-engineering/recent-web-performance-fixes-on-airbnb-listing-pages-6cd8d93df6f4 Airbnb optimizing its React rendering
- https://arxiv.org/pdf/1712.01815.pdf AlphaZero has learn to perfectly play chess within a few hours this time

# 06-12-2017

- http://syncfree.github.io/antidote/index.html a new CRDT HA database 
- https://reactos.org/project-news/reactos-047-released ReactOS continues its evolution, mirroring Windows but as FOSS (nothing to do with ReactJS eh)

# 05-12-2017

- https://parceljs.org/ Parcel is a html/js/css/xxx module bundler with 0 config and just need the html as source. Mostly made for hyper fast build-test-loop.
- https://blog.doit-intl.com/replacing-mixpanel-with-bigquery-dataflow-and-kubernetes-b5f844710674 Catchy title, i like it ! Mixpanel, BQ, Dataflow, k8s.
- https://github.com/spotify/apollo microservices tiny framework used by spotify

# 04-12-2017

- https://labs.spotify.com/2017/11/20/autoscaling-pub-sub-consumers/ Spotify had some troubles with autoscaling on GCS with Pub/Sub Consumers (not using Dataflow ?!)
- https://marcan.st/2017/12/debugging-an-evil-go-runtime-bug/ This is a impressive and crazy Go bug debugging lecture
- https://calendar.perfplanet.com/2017/animated-gif-without-the-gif/ Very interesting with good pointers. s/gifs/mp4/
- https://docs.google.com/document/d/1yRYfYR1DnHtgwC4HRR04ipVVhT1h5gkI6yPmKCgJkyQ/edit#heading=h.elxj4igk4k81 w3c proposal: "Hero Element Timing API" to be aware of when some critical elements (hero elements) are displayed on screen
- http://www.stephendiehl.com/posts/haskell_2018.html Good post overviewing what happened in the Haskell world in 2017. So many things! Time to get in?
- https://medium.com/learning-rust Bookmark that when the time's come!
- https://github.com/wanqizhu/pyfuck python using only those chars: [(+travels')]. yeah, whatever

# 03-12-2017

- https://www.youtube.com/watch?v=4PgX3yBJEyw "Authenticating service-to-service calls with Google Cloud Endpoints"
- https://www.infoq.com/news/2017/12/webassembly-browser-support WebAssembly is definitely going to spread faster and faster !
- https://www.michielrook.nl/2016/11/strangler-pattern-practice/ The Strangler pattern in practice
- https://www.martinfowler.com/bliki/StranglerApplication.html The Strangler Pattern—Or how to rewrite a legacy app iteratively

# 02-12-2017

- https://blog.softwaremill.com/akka-streams-pitfalls-to-avoid-part-2-f93e60746c58 Akka Streams pitfalls to avoid — part 2 – WAY more interesting than part 1
- https://blog.chromium.org/2017/11/reducing-chrome-crashes-caused-by-third.html It's not about third-party cookies this time, but third-party softwares!
- https://arstechnica.com/science/2017/12/after-37-years-voyager-has-fired-up-its-trajectory-thrusters/ We did some great tech bach then! "After 37 years, Voyager 1 has fired up its trajectory thrusters."

# 01-12-2017

- https://cloudplatform.googleblog.com/2017/11/introducing-an-easy-way-to-deploy-containers-on-Google-Compute-Engine-virtual-machines.html a new gcloud command to deploy containers into a GCE vm "create-with-container"
- https://www.lesnumeriques.com/tv-televiseur/que-va-changer-hdmi-2-1-n69037.html Ne pas oublier de se tenir au courant de l'audio-visuel aussi! HDMI 2.1 incoming! du 4k en 120Mhz.
- http://scala-lang.org/blog/2017/11/30/bloop-release.html "bloop", a"build loop" tool. A CLI over Zinc and nailgun.
- https://dailycodingproblem.com/2017/11/30/random-element.html The Reservoir Algorithm
- https://norasandler.com/2017/11/29/Write-a-Compiler.html Writing a C Compiler from scratch
- https://www.erikheemskerk.nl/ddd-persistence-recorded-event-driven-persistence/ Writing DDD repositories with an event driven design
- https://blog.sourcerer.io/writing-a-simple-linux-kernel-module-d9dc3762c234 Always interesting to see how to write a Linux Kernel Module

# 30-11-2017

- https://andreas.github.io/2017/11/29/type-safe-graphql-with-ocaml-part-1/ Type-Safe GraphQL with OCaml
- http://nickdrane.com/build-your-own-regex/ A very simple"regex" engine in Javascript, as a starter.
- https://blog.jetbrains.com/idea/2017/11/intellij-idea-2017-3-smarter-coding-assistance-better-debugger-run-dashboard-frameworks-support-and-more/ IntelliJ IDEA 2017.3: Smarter Coding Assistance, Better Debugger, Run Dashboard, Frameworks Support ! Installed.
- https://www.bloomberg.com/news/articles/2017-11-29/uber-s-third-quarter-loss-is-said-to-widen-to-1-46-billion Uber in trouble, causing early investors to sell
- https://www.confluent.io/blog/toward-functional-programming-analogy-microservices/ Analogy between functional programming and microservices

# 29-11-2017

- https://speakerdeck.com/bobbycalderwood/commander-better-distributed-applications-through-cqrs-event-sourcing-and-immutable-logs How to go to CQRS+Event Sourcing using Kafka Streams
- https://www.confluent.io/confluent-cloud/ Confluent Platform as a managed service now "Confluent Cloud"
- http://steve-yegge.blogspot.fr/2007/06/rich-programmer-food.html everybody should know how compilers work because it's always useful one day or another
- https://design.google/library/evolving-google-identity/ An old post from 2015 when Google redesigns its logo and style. Nice explanations.

# 27-11-2017

- https://dzone.com/refcardz/continuous-delivery-with-jenkins-workflow A very nice intro to Jenkins Pipeline
- https://carlossg.github.io/presentations/2017-11_agiletestingdays/#/ k8s and Jenkins (Workflow) = <3
- https://blog.csanchez.org/2017/05/31/running-a-jvm-in-a-container-without-getting-killed/ Beware of JVM running inside memory-limited containers, they do not respect it by default!
- http://blog.erratasec.com/2017/11/a-thanksgiving-carol-how-those-smart.html A surprising story about unconfirmed twitter account that keeps receiving stuff for years without being email-confirmed
- https://www.youtube.com/watch?v=Pu_WTjjmm-E Ben Sigelman: OpenTracing and its Applications

# 23-11-2017

- https://www.developpez.com/actu/174643/Mozilla-a-silencieusement-deploye-la-fonctionnalite-First-Party-Isolation-empruntee-a-Tor-pour-endiguer-le-profilage-des-regies-publicitaires/ FPI (First Party Isolation) pour isoler les cookies thid-party par domaine first-party: plus d'aggrégation possible côté third.
- https://blog.cloudflare.com/get-started-with-warp/ ngrok on CloudFlare?
- https://stackoverflow.blog/2017/11/13/cliffs-insanity-dramatic-shifts-technologies-stack-overflow/ Dramatic Shifts in Technologies on Stack Overflow: swift, tensorflow, angular (!)
- http://tldr.sh/ If you don't enjoy man pages because they are too long, you will love tldr !

# 20-11-2017

- http://www.lihaoyi.com/post/SowhatswrongwithSBT.html "What's wrong with SBT?" Everything! It's so meta, as explained here.
- https://towardsdatascience.com/google-colaboratory-simplifying-data-science-workflow-c70059386323 Ask for your invite at Google Colaboratory !
- https://medium.com/unsplash-unfiltered/scaling-unsplash-with-a-small-team-fbdd55571906?ref=reddit Very good article by the splash team showing their architecture, their choices. Very lean, love it. "Have you tried throwing money at it?"

# 19-11-2017

- https://blog.alexellis.io/introducing-functions-as-a-service/ OpenFaas, serverless on top on containers (docker swarm, k8s)
- http://nats.io/about/ A messaging system for native cloud application developement, with connectors to tons of softwares 
- https://www.youtube.com/watch?v=e59pTjaVPCs Some FaaS demos using Amazon/GCP/Azure. Nice stuff about Azure are bindings (js var bound to databases).
- http://blog.cleancoder.com/uncle-bob/2017/10/03/TestContravariance.html Reduce coupling between tests and production code (X doesn't mean there is XTest). Tests should be independent, seen as a client of the api.
- https://postverta.com/ An online IDE for nodejs apps, dealing with deployment, easy and all-managed
- https://www.slideshare.net/szaheer/dimensional-modelling-basic-concept Example of DM (identify business (source), the grain (what does 1 row means?), the dim, and the facts
- https://en.wikipedia.org/wiki/Dimensional_modeling Dimensional modeling is a design technique for databases intended to support end-user queries in a data warehouse (how to design a star/snowflake schema)
- https://medium.freecodecamp.org/the-rise-of-the-data-engineer-91be18f1e603 Interesting insights about what is a "Data Engineer" nowadays
- https://www.elastic.co/guide/en/elasticsearch/reference/6.0/removal-of-types.html More details about mapping types removal and a way to migrate using the reindex api
- https://www.elastic.co/blog/elasticsearch-6-0-0-released Globally faster, and mapping types indices are deprecated :o
- http://heydonworks.com/revenge_css_bookmarklet/ Bookmarklet to wrap any malformed/deprecated html structures with a pink border in the current page <3
- https://github.com/dotnet/corefxlab/blob/master/docs/specs/span.md Span<T>: a new .NET structure to avoid copying internally every time. Abstraction: it can reference managed/native/stack mem. Performance!

# 18-11-2017

- https://lemire.me/blog/2017/11/10/how-should-you-build-a-high-performance-column-store-for-the-2020s/ Technics to encode and compress data to get faster, and referencing Apache Arrow for good column store perf
- https://en.wikipedia.org/wiki/AOS_and_SOA Are you more Array of Structures or Structure of Arrays? Interesting question!
- https://github.com/apache/kudu/blob/master/docs/design-docs/tablet.md#mvcc-mutations-in-memrowset Very well written design doc about Kudu's tablets, explaining the how mvcc works, the different places data are stored, the compactions, and advantage/drawback compared to others db such as bigtable, vertica, pg
- https://www.nytimes.com/2017/11/02/magazine/how-facebooks-oracular-algorithm-determines-the-fates-of-start-ups.html A passionant story about a startup using Facebook's Ads to get started: how to succeed and pitfalls
- https://www.lrb.co.uk/v39/n16/john-lanchester/you-are-the-product A super interesting review about Facebook: from where, to where, the dangers, the advertisers, the humans, the product
- https://www.confluent.io/blog/transactions-apache-kafka/ High overview of how transactions works in Apache Kafka 

# 17-11-2017

- https://www.youtube.com/watch?v=evaMpdSiZKk React made "easy and simple" with Next.js; presenting the different associated babel-plugins (talk a bit confusing though)
- https://github.com/sbt/sbt-fresh plugin to create an opinionated fresh sbt project, "sbt fresh" and done!
- https://0patch.blogspot.fr/2017/11/did-microsoft-just-manually-patch-their.html When you lost source code, just patch the existing binary; as Microsoft did.
- https://www.lucidchart.com/techblog/2017/11/16/converting-600k-lines-to-typescript-in-72-hours/ Converting 600k lines to TypeScript in 72 hours by Lucidchart; very very awesome :-)

# 15-11-2017

- http://www.zdnet.com/article/linux-totally-dominates-supercomputers/ Today, all 500 of the world's top 500 supercomputers are running Linux.
- https://github.com/Heydon/REVENGE.CSS REVENGE CSS | A CSS bookmarklet that puts pink error boxes (with messages in comic sans) everywhere you write bad HTML.

# 12-11-2017

- http://blog.ploeh.dk/2016/03/18/functional-architecture-is-ports-and-adapters/ Ports and Adapters—Business logic should be contained into pure functions
- https://blog.samebug.io/creating-a-todo-application-using-akka-http-and-slick-chapter-1-24f77394a481 Creating a TODO application using Akka HTTP and Slick
- http://www.gwern.net/Ads Banner Ads Considered Harmful (Here): he estimates AdSense reduces its traffic by ~14%
- https://www.slideshare.net/etorreborre/specs2-from-starters-to-dessert-and-a-look-in-the-kitchen Specs2, never used it, i think i won't
- https://blog.timescale.com/time-series-data-postgresql-10-vs-timescaledb-816ee808bac5 TimescaleDB, an extension in PostgreSQL, aims to be better as timeseries db than good ol' vanilla PostgreSQL, even with declarative partitioning
- https://blog.timescale.com/scaling-partitioning-data-postgresql-10-explained-cd48a712a9a1 PostgreSQL 10 introduces declarative partitioning
- https://www.youtube.com/watch?v=a4PX8vksBFU The story of the world's first webcam. It was used to know if the coffee was ready.

# 11-11-2017

- https://www.youtube.com/watch?v=b_pEevMAC3I&list=PLoz-W_CUquUlnvoEBbqChb7A0ZEZsWSXt&index=29 PromCon 2017: optimizations done in Prometheus 2.0, benchmarks, just mad results
- https://prometheus.io/blog/2017/11/08/announcing-prometheus-2-0/ Prometheus 2.0, storage and perfs revisited
- http://esr.ibiblio.org/?p=7711 An ode to the end of C, by a C programmer. New language taking its place: Go, Rust
- https://alexn.org/blog/2017/11/10/minitest-no-crap-scala-library.html a KISS Scala testing lib, by monix's author
- https://blog.chromium.org/2017/11/expanding-user-protections-on-web.html More protection from abusive redirects on the web
- http://status.ovh.net/?do=details&id=15162#comment18119 The reasons of the OVH outage: SBG power grid is totally flawed and will be fixed

# 06-11-2017

- http://tonsky.me/blog/chrome-intervention/ Silent breaking change from Chrome team (on addEventListener..! by default, is "passive" (a new option) to improve perf)
- https://sevagh.github.io/post/8months/ A "jq" for protobuf data: "pq" :-)
- https://techcrunch.com/2017/11/03/snap-metamarkets/ Snap has acquired Metamarkets (Druid)

# 05-11-2017

- https://www.youtube.com/watch?v=bBC-nXj3Ng4 Best video? to explain how Bitcoin actually works
- https://research.googleblog.com/2017/11/automl-for-large-scale-image.html AutoML was applied for image classif and object detection, and it works really great
- https://research.googleblog.com/2017/05/using-machine-learning-to-explore.html ML to create better NN architecture
- http://tim.hibal.org/blog/alpha-zero-how-and-why-it-works/ How works AlphaGo Zero: Monte-Carlo tree search with an neural net expert policy to avoid too much exploration "these AI's will only be human-level for a brief instant before blasting past us into superhuman territories"
- https://www.youtube.com/watch?v=Fbhhc4jtGW4 Nice talk about doing micro-services with nodejs/docker/k8s/helm/prometheus/zipkin
- https://medium.com/the-node-js-collection/news-node-js-8-moves-into-long-term-support-and-node-js-9-becomes-the-new-current-release-line-74cf754a10a0 nodejs 9 is starting. V8 integrates nodejs compat tests now.
- https://dexecure.com/blog/how-to-create-http2-static-file-server-nodejs-with-examples/ Simple HTTP/2 server in nodejs, with its http2 api.

# 04-11-2017

- https://www.cakesolutions.net/teamblogs/typesafety-101-knowing-your-types To resume: Option.get should not exists :-). Never break out from the original type.
- http://www.scalaformachinelearning.com/2017/10/reinforcement-learning-in-scala.html Reinforcement learning in Scala
- https://slack.engineering/rebuilding-slack-com-b124c405c193 Interesting insights and experience sharing from Slack.com redesigning their website
- https://github.com/sksamuel/scapegoat an alternative to FindBugs or checkstyle, to do static code analysis
- https://serverjs.io/ server.js looks like a good and easy alternative to expressjs/koa
- https://blemoine.github.io/scala-io-effects/ Very good talk about managing side effects in Scala. Option, Either, Monad transformers, Eff monad.

# 03-11-2017

- https://speakerdeck.com/markus1189/let-the-compiler-help-you Very good talk explaining how to let the compiler help us (by writing smarter code) to check for errors at compile-time): from Exceptions to Eithers to Phantom Types to Refined lib
- https://medium.com/@peggyrayzis/why-i-cancelled-my-reactiveconf-talk-3a463bf14bd8 "Why I cancelled my ReactiveConf talk"—A bit too much; but clearly, communication is key, when organizers lacks of, it's never a good sign.
- https://www.ifixit.com/Teardown/iPhone%2BX%2BTeardown/98975 iPhone X "internals", truly a masterpiece of dense tech inside

# 02-11-2017

- https://www.slideshare.net/PierreLaporte/pimp-my-gc Pimp my gc, old 2013 pres' from ScalaIO talking about GC tuning (quite high level)
- https://docs.google.com/presentation/d/1TPrLLcVpmQf5ajSV9KuWGYUzkauy9tK2J0dmQ13-v98/ An alpakka presentation at ScalaIO 2017
- http://notes.burke.libbey.me/metarepo/ Monorepo, Manyrepo, Metarepo

# 01-11-2017

- https://opensource.com/article/17/9/seven-stages-becoming-go-programmer 7 stages of becoming a Go programmer, from "oop to goroutines to interfaces to channels to wtf to zen attitude"
- https://hackernoon.com/how-awesome-engineers-ask-for-help-93bcb2c7dbb7?gi=a46da5c1e544 Very inspiring article about how we should request for help
- https://github.com/Microsoft/vscode/wiki/Roadmap VS Code Roadmap 2018: better perfs, better workflow, better languages integrations, better extensions
- https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/ An awesome list of 12 points to know if you're properly developing softwares, love it!
- https://en.wikipedia.org/wiki/Interprocedural_optimization Interprocedural optimization "IPO", compiler methods to optimize code globally
- http://danluu.com/programmer-moneyball/ A ex-Google-and-other-tech-company talks about tech companies hiring (bad) strategy for most (focusing on trendy ppl only)
- https://www.confluent.io/blog/apache-kafka-goes-1-0/ Apache Kafka 1.0 out, now stable and back-compat? :-D

# 30-10-2017

- https://www.troyhunt.com/the-6-step-happy-path-to-https/ HTTPS: tips, and mostly about using HSTS and CSP upgrade unsecured requests + rely on CloudFlare to do this for you
- https://squawker.org/technology/blockchain-just-became-obsolete-the-future-is-hashgraph/ Hashgraph, a evolution of BlockChain? But not open-sourced, and will be patented, so..
- https://staltz.com/the-web-began-dying-in-2014-heres-how.html Interesting recap about Google FB and Amazon evolution, trends, and goal; way beyond the "web"
- https://chriszetter.com/blog/2017/10/29/splitting-strings/ Interesting to know that .split does not behave the same in different languages (python and ruby here) when "".split("x") => ?

# 29-10-2017

- https://open.nytimes.com/https-open-nytimes-com-the-new-york-times-as-a-tor-onion-service-e0d0b67b7482 The New York Times is Now Available as a Tor Onion Service
- https://www.infoq.com/presentations/reactive-events-streaming-api Talk about Akka (persis, cluster, streams) to get from old-school app to a reactive system with micro-services
- https://www.youtube.com/watch?v=YqOhBezMx1o Quick talk about v8 arch, from Crankshaft to Ignite+TurboFan, why
- https://github.com/Microsoft/napajs Napa.js is a multi-threaded JavaScript runtime from Microsoft, built on top of V8. 
- https://medium.com/@caspervonb/why-i-still-use-vim-67afd76b4db6 Atom and Code are so bad at resource consumption,like x100 than vim or sublime.
- https://dzone.com/articles/disruptive-changes-to-gc-logging-in-java-9 The GC logging totally changed in Java 9, old options +PrintXXX are removed or deprecated

# 28-10-2017

- https://developer.couchbase.com/documentation/server/5.0/introduction/whats-new.html Couchbase 5 is out, with tons of new features and improvements (n1ql, text search, secu..)
- https://www.infoq.com/news/2017/10/azure-functions-java Azure Functions now supports Java. Only GCP CF are not now. :(
- https://reasonml.github.io/community/blog/#reason-3 Reason 3 is out. Lots of syntax changes to feel more natural
- https://medium.freecodecamp.org/lets-enhance-how-we-found-rogerkver-s-1000-wallet-obfuscated-private-key-8514e74a5433 Super interesting post about finding a private key from a blurred QR code to grab some bitcoins

# 24-10-2017

- https://medium.com/@giuseppemaggiore/a-react-journey-from-vanilla-to-type-safe-to-monadic-41beaa386910 Quickly read this one. React from vanilla, to type-safe, to monadic (using monadic-react lib). Not fan of the "syntax" overall.
- https://jepsen.io/analyses/hazelcast-3-8-3 Jepsen testing Hazelcast, and strongly recommand to use it only for non-critical data, because HZ can lose data, create duplicates, "mis-lock" locks and so on
- https://www.smashingmagazine.com/2015/06/efficient-image-resizing-with-imagemagick/ got a way smaller image size with custom imagemagic tuning than with classic tools
- https://cloud.google.com/dataproc/docs/concepts/configuring-clusters/init-actions with DataProc, it's possible to install softwares (kafka, dbs..) automatically (master and slaves are distincts) through some .sh scripts
- https://blog.fuzzing-project.org/60-Optionsbleed-HTTP-OPTIONS-method-can-leak-Apaches-server-memory.html Optionsbleed: HTTP OPTIONS method can leak Apache's server memory
- https://akka.io/blog/news/2017/10/23/native-akka-streams-in-spring-web-and-boot-via-alpakka Akka Streams in Spring via Alpakka, just by adding a simple module, very nice!
- https://github.com/grafeas/grafeas The associated repo:" Cloud artifact metadata CRUD API and resource specifications"
- https://cloudplatform.googleblog.com/2017/10/introducing-grafeas-open-source-api-.html Grafeas: An open-source API to audit and govern software supply chain

# 23-10-2017

- https://stackify.com/java-thread-pools/ Java Thread Pool models revisited, FJP and classic TP.
- https://www.confluent.io/blog/ranking-websites-real-time-apache-kafkas-streams-api/ Another usage of Kafka Streams running on AWS to compute page ranks.
- https://labs.spotify.com/2017/10/16/big-data-processing-at-spotify-the-road-to-scio-part-1/ Spotify reexplaining how/why they used Dataflow and their scio framework (basically dataflow api in scala)
- https://deepmind.com/blog/alphago-zero-learning-scratch/ a strong feat: algorithms learning from scratch are smarter than learning from humans
- https://blogs.windows.com/msedgedev/2017/10/18/documenting-web-together-mdn-web-docs/ A good decision: msdn now redirects 7k pages to mdn (mozilla dev network), less repetitions, more centralization
- https://buildazure.com/2017/10/20/swagger-is-now-the-openapi-specification/ Swagger is now the OpenAPI Specification

# 22-10-2017

- http://blog.ploeh.dk/2015/05/07/functional-design-is-intrinsically-testable/ Functional programming is very good for unit testability
- https://zwischenzugs.wordpress.com/2017/10/15/my-20-year-experience-of-software-development-methodologies/ An interesting feedback about software methodologies applications in companies.. not that easy, according to who is there.
- https://webkit.org/blog/7675/intelligent-tracking-prevention/ Intelligent Tracking Prevention: cookies and website data from the sites a user does NOT interacts with (first party) and tracking data will be removed
- https://vimeo.com/233975012 "Nature-inspired algorithms", a talk presenting some genetic algorithms and particle-swarm optimization, and the problem that the solvers are "blind", and often difficult to tune
- https://hackernoon.com/why-isnt-agile-working-d7127af1c552 Basically, Agile needs lean, devops cultures, xp programming, and iterativity a LOT
- https://www.mocky.io/ A new online tool to mock http response, always useful
- https://cloudplatform.googleblog.com/2017/10/API-design-choosing-between-names-and-identifiers-in-URLs.html A page _should_ have a "human" friendly url, and a fixed permalink with ids
- https://www.theverge.com/platform/amp/2017/10/19/16503076/oracle-vs-google-judge-william-alsup-interview-waymo-uber A Judge writing QuickBasic is obviously in a good position to judge tech cases <3
- https://blogs.dropbox.com/dropbox/2017/10/new-plan-dropbox-professional/ New tools to "showcase" a work, basically create a "landing" page to organize some Dropbox content

# 15-10-2017

- https://blog.softwaremill.com/the-case-against-annotations-4b2fb170ed67?token=79fT3F-khJEaf3KX Great post explaining why we should probably not use annotations too much.
- https://hackernoon.com/whats-new-with-server-side-rendering-in-react-16-9b0d78585d67 React 16 is a complete release, with massive improvements.
- https://blog.kontena.io/event-sourcing-microservices-with-kafka/ Nothing new but just another perpective about Kafka for event sourcing

~~ Holidays exist to make a break, right? ~~

# 16-09-2017

- https://developers.google.com/web/updates/2017/08/devtools-release-notes Chrome 62 is there. Can await in the console, youhou.
- https://adoptopenjdk.net/index.html?variant=openjdk9-openj9 Another "enterprise" JVM "OpenJ9" in the OpenJDK distrib, from IBM.
- https://github.com/AaronJackson/vrn Construct a 3D visage from a 2D photo, impressive.
- https://ma.tt/2017/09/on-react-and-wordpress/ React's patents continue to affect projects, here Wordpress decide to not use it anymore. (Apache did the same)
- https://caddy.community/t/the-realities-of-being-a-foss-maintainer/2728/4 Caddy, an open-source auto-HTTPS server goes commercial, and that provokes good but mostly bad reactions. Matt Holt, a maintainer, decided to step up.
- https://techcrunch.com/2017/09/15/why-dropbox-decided-to-drop-aws-and-build-its-own-infrastructure-and-network/ Dropbox, 1500 employees, 500PB to move from AWS to home-made.
- https://www.confluent.io/blog/okay-store-data-apache-kafka/ Storing all the data into Kafka. It's scary for some reasons. This post tries to remove some doubts.
- https://hacks.mozilla.org/2017/09/building-the-dom-faster-speculative-parsing-async-defer-and-preload/ Just "preload" everything. https://github.com/chtefi/guidelines-to-create-a-strong-website
- https://medium.com/@maximilianofelice/builder-pattern-in-scala-with-phantom-types-3e29a167e863 A cool article about Scala Phantom types. Make up your pizza.
- http://norswap.com/fast-java-reflection/ In Java8, it's possible to use reflection as fast as direct calls, thanks to the new API LambdaMetafactory.
- https://blogs.dropbox.com/tech/2017/09/optimizing-web-servers-for-high-throughput-and-low-latency/ Many optimizations from hardware to high-level nginx. Many stuff i'll never used. :-D

# 13-09-2017

- http://www.sublimetext.com/blog/articles/sublime-text-3-point-0 Sublime Text 3 is OUT OF BETA§ Unfortunately, I'm more fluent on VSCode since a while :-( (except for huge files)
- https://blog.sessionstack.com/how-javascript-works-memory-management-how-to-handle-4-common-memory-leaks-3f28b94cfbec Never reference an external var from a closure, use arguments.
- https://medium.com/@mikeal/modern-modules-d99b6867b8f1 Take away: use async/await, it's future-proof. Use r2 instead of request. 
- https://v8project.blogspot.fr/2017/09/elements-kinds-in-v8.html JavaScript only knows "number", but the engine behind is smarter and packs numbers in array optimally. SMI: Small Integer. "Nowadays, the performance of both for-of and forEach is on par with the old-fashioned for loop."
- http://jackhiston.com/2017/9/4/the-wonderful-world-of-webpack/ Quick notes on what the webpack purpose is
- https://jakearchibald.com/2017/lazy-async-svg/ A new feature in Chrome61: Zoomable lazy-rendered tiled SVG. Improve perf if the page plays a lot with SVGs.

# 11-09-2017

- http://www.scala-lang.org/blog/2017/09/11/scalafix-v0.5.html Linting tool for Scala! And also some codemods for sbt (sbt-fix).
- https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-101 and https://www.oreilly.com/ideas/the-world-beyond-batch-streaming-102 Wonderful posts about batch and streaming engines, related to Apache Beam/Google Dataflow.
- https://github.com/pureconfig/pureconfig Load typesafe configs into case classes easily and safely.
- https://beachape.com/blog/2017/05/24/rust-from-scala/ Feedback from a Scala dev writing Rust. Quite positive!

# 09-09-2017

- http://jroweboy.github.io/c/asm/2015/01/26/when-is-main-not-a-function.html Excellent. Doing a C program using `const int main[] = {..}` Not conventional!
- https://blog.campvanilla.com/javascript-the-curious-case-of-null-0-7b131644e274 null >= 0 is true because null < 0 is false
- https://leanpub.com/fpmortals/read "Functional Programming for Mortals" in Scala please. To read!
- http://thoughts.davisjeff.com/2009/08/02/what-is-the-deal-with-nulls/ omg, NULL in SQL is like the most unconsistent and wary thing

# 07-09-2017

- https://code.facebook.com/posts/274518539716230 Yarn 1.0 is out! Performance, workspaces (multi-projects in monorepo)
- https://www.confluent.io/blog/simplest-useful-kafka-connect-data-pipeline-world-thereabouts-part-3/ Kafka implemented simili-Flume's interceptors to do simple stuff in the pipeline, without coding anything. (SMTs)
- https://github.com/AssemblyScript/assemblyscript A subset of Typescript, compiling to webasm, good stuff, future is here.
- https://medium.com/@dwalsh.sdlr/using-graphql-why-facebook-now-owns-you-3182751028c9 An analysis of the GraphQL patent
- https://github.com/nginx/unit nginx made easy?

# 06-09-2017

- https://github.com/mr-mig/every-programmer-should-know Good list of things to know, and most to forget, but well..
- http://infiniteundo.com/post/25326999628/falsehoods-programmers-believe-about-time Sorry, I don't believe all this crap, hopefully
- https://code.facebook.com/posts/357056558062811/logdevice-a-distributed-data-store-for-logs/ Facebook diving into its LogDevice: a distributed data store for logs. Use-cases, some technical notes, but nothing concrete. OS in 2017, possibly.
- https://github.com/facebook/buck I wonder if Buck could bring something truly useful on java non-android mvn projects (too bad it does not handle scala!) (from Google)
- https://docs.bazel.build/versions/master/getting-started.html And what bout Bazel actually? Buck is based on it.
- http://www.hanshq.net/eprime.html Several technics to find the first 10-digit prime in the digits of E (and computing E with billion of digits too..) Taylor and C inside!
- https://www.confluent.io/blog/publishing-apache-kafka-new-york-times/ How NYT deals with Kafka. Interesting. 1 partition on the main topic to get total ordering. Kafka Streams, ES, and GCP/GCE/GKE inside.

# 04-09-2017

- https://github.com/satwikkansal/wtfpython#-examples JS is not the only one to be fucked up
- http://www.reactos.com/project-news/reactos-046-released "14,238,159 unit test cases, failing just 18,419"
- https://www.youtube.com/watch?v=A45uRzJiv7I KSQL: Streaming SQL for Kafka. Easy and powerful. Create tables from topics. Can't stop thinking about scaling? (when joining tables of millions?). It's backed up by Kafka Streams. The associated blog post: https://www.confluent.io/blog/ksql-open-source-streaming-sql-for-apache-kafka/
- https://code.facebook.com/posts/357056558062811/logdevice-a-distributed-data-store-for-logs/ https://github.com/apache/incubator-pulsar http://bookkeeper.apache.org/ We all know Kafka. But what about logdevice (fb), pulsar (yahoo), distributedlog/bookkeeper (twitter) ?

# 31-08-2017

- https://www.javagists.com/stack-walking-api-java-9 Simple article about the new Java9 stacktrace walking api. Quite rare to use it, but good to know.
- https://www.confluent.io/blog/blogthe-simplest-useful-kafka-connect-data-pipeline-in-the-world-or-thereabouts-part-2/ Kafka to ES, made easy (with Kafka connect)
- https://beam.apache.org/blog/2017/08/16/splittable-do-fn.html Easier to write custom sources in Beam thanks to SDF (Splittable DoFn)
- https://blogs.msdn.microsoft.com/typescript/2017/08/31/announcing-typescript-2-5/ Typescript introducing some method refactorings (finally..) in VSCode
- https://medium.com/the-node-js-collection/async-hooks-in-node-js-illustrated-b7ce1344111f Not a clear post i find. Anyway, a new API to register callbacks tracking the lifetime of asynchronous resources created inside a Node.js. Useful to create "span" to analyse where the time is spent and what is going on behind the hood. 
- https://code.facebook.com/posts/357056558062811/logdevice-a-distributed-data-store-for-logs/ A new distributed logs storage on its way, by Facebook.

# 29-08-2017

- https://blog.alaskaair.com/alaska-airlines/solar-eclipse/ Alaska Air explaining how they planned to see the eclipse from one of their plane, it is not that easy. Incredible.
- https://underscore.io/blog/posts/2016/12/05/type-lambdas.html Why the kind projector exists in Scala
- https://typelevel.org/cats/datatypes/functionk.html ~> in cats is equivalent to A => B for higher kinded types: F[_] => G[_] <=> F ~> G.
- https://typelevel.org/cats/datatypes/freemonad.html You need to work with Free monads to understand them truly.
- https://medium.com/towards-data-science/gradient-descend-with-free-monads-ebf9a23bece5 A very interesting Free monads usage: to compute a gradient descent
- https://medium.com/@taitems/how-i-replicated-an-86-million-project-in-57-lines-of-code-277031330ee9 We can find so many great stuff in open source now, licence plate recognition here
- https://thenextweb.com/google/2017/08/28/google-japan-internet-blackout/ And they said the internet is decentralized.
- https://blog.buildo.io/data-driven-scala-programming-e50f07c4db35 Analyzing the errors you get when working, interesting to get insights about things you barely realize.

# 24-08-2017

- https://medium.com/@kentcdodds/introducing-downshift-for-react-b1de3fca0817 A React autocomplete component without UI at all, just the logic. Kinda like this idea! Separation of concerns, ftw.
- https://medium.com/@gkossakowski/a-note-on-kentucky-mule-and-twitters-scala-compiler-announcement-3294b5baf2ea More details about the Kentucky Mule POC (ultra-fast scala typechecking)
- https://thenewstack.io/node-js-forked-complaints-repeated-harassment/ nodejs forked again. iojs, the come-back: "ayo". because of repeated infringements to the code of conduct by some high-members https://github.com/ayojs/ayo 
- https://handmade.network/forums/wip/t/2363-implementing_a_basic_png_reader_the_handmade_way A dude just wrote down a PNG reader in 300 lines, fully explained. Very nice.
- https://dzone.com/articles/integrating-unmanaged-services-in-lagom-with-scala Tiny article about interacting with external services (unmanaged) in Lagom.
- https://dzone.com/articles/akka-message-delivery-at-most-once-at-least-once-a No surprise, the at-most-once strategy is rarely voluntary used.
- http://www.ssw.uni-linz.ac.at/Research/Papers/Marr/manlang17-grimmer-et-al-applying-optimizations-for-dynamically-typed-languages-to-java.pdf A big work using Truffle on GraalVM, to, mostly, avoid auto-boxing (caused by generics) by optimizing bytecode, to improve perfs.
- https://advancedweb.hu/2017/03/01/jvm_optimistic_optimizations/ A very good article about Java inlining optimizations (x-morphic, branch prediction, and NPE impacts)

# 22-08-2017

- https://www.youtube.com/watch?v=oeE2tuspdHg Always interesting to see how people codes live. Here, a React app using Vx (d3) to draw a bitcoin chart.
- http://www.businessinsider.fr/us/employee-retention-rate-top-tech-companies-2017-8/ It seems 2 years is the avg time before getting bored in any company
- http://degoes.net/articles/scalaz8-is-the-future Is scalaz8 is going to be more Intellij and compilation friendly? In any case, it seems to be a good revamp!
- https://github.com/sksamuel/elastic4s A very good Scala library with DSL to use elasticsearch. Also provide a reactive streams impl.

# 19-08-2017

- https://medium.com/@yaypie/cloudflare-thinks-they-can-be-neutral-they-cant-b46857f21c9a Where is the limit between hosting, and judging/acting about what you host.
- http://www.oracle.com/technetwork/oracle-labs Oracle labs has some nice projects: a polyglot runtime for the JVM, GraalVM (that can interpret scripting languages such as Javascript, Ruby, R, and transforms them to a common AST Graal works with, thus provides all the JIT techniques), a Graph processing lib (Parallel Graph AnalytiX (PGX)) 
- https://www.slideshare.net/martintoshev/jvm-the-graal-vm A recap of Graal. And Graal.js, 1.5x faster than V8 ?
- https://yoric.github.io/post/binary-ast-newsletter-1/ The interesting future of Javascript being written directly to a binary AST to be sent over the wire
- https://michael.stapelberg.de/Artikel/golang_favorite An opinion of why Go is great: code style, compilation speed, a good std lib, the associated tools

# 17-08-2017

- https://ponyfoo.com/articles/investigating-performance-object-prototype-to-string-es2015 A fast way to implement toString in JS
- http://formidable.com/blog/2017/introducing-electron-webpack-dashboard/ A terrible tron-ish dashboard for webpack compilation
- https://thenewstack.io/github-goes-kubernetes-tells/ Experience of GitHub slowly switching to k8s
- https://www.confluent.io/blog/simplest-useful-kafka-connect-data-pipeline-world-thereabouts-part-1/ Using Kafka Connect to do some CDC with MySQL
- https://benedikt-bitterli.me/reverse/ Reverse engineering some malicious javascript. He could just have used jsnice and prepack to greatly simplify and evaluate the thing ;-)
- https://blogs.msdn.microsoft.com/typescript/2017/08/17/announcing-typescript-2-5-rc/ Typescript is pursuing its way, 2.5 incoming, with some "try" improvements and misc internal fixes
- https://github.com/twitter/reasonable-scala Twitter is working on a blazing fast Scala compiler. Come on, we already have Dotty incoming, and there is also Typelevel Scala compiler..
- https://machinelearning.apple.com/2017/07/07/GAN.html Apple playing with eyes, and trying to improve the realism of synthetic images
- https://www.sigmainfy.com/blog/protocol-buffers-encoding-and-message-structure.html Looking at Protobuf binary encoding (varint, zigzag..)

# 16-08-2017

- http://developer.lightbend.com/blog/2017-08-14-cinnamon-2-5-with-akka-http-support/index.html Cinnamon (commercial feature) usage with HTTP metrics, OpenTracing and MDC.
- http://developer.lightbend.com/guides/k8-akka-cluster/ Deploying a Akka cluster app to kubernetes and setting up proper env config
- https://blog.figma.com/figma-2-0-now-with-prototyping-and-developer-handoff-1b309a5d025c Figma is a really good collaborative design tool for designers, on the web.
- https://medium.com/@yonatanzunger/so-about-this-googlers-manifesto-1e3773ed1788 A frankly good resume and answer to the famous leaked Googler manifesto.
- https://dev.to/kyle/a-first-look-at-google-cloudplatform A quick comparaison between AWS and GCP, mostly on the organization, the security, the storage and the nosql db.
- https://www.youtube.com/watch?v=aFtpIShV60I A quick intro to Træfɪk: Load Balancing microservices 

# 14-08-2017

- https://medium.com/@sbichenko/the-wrong-fizzbuzz-81cb8e67ef4a "Don’t implement the spec. Implement the logic behind the spec."
- https://blog.godatadriven.com/practical-airflow-tutorial A useful recap about installing and setup some jobs in airflow
- https://medium.com/@criccomini/so-you-want-to-build-a-kafka-connector-source-edition-357dce7d55f4 All the subtilities to handle when dealing with database CDC
- http://debezium.io/ Another system to deal with CDC (à la bottledwater-pg). Distributed, and based on Kafka Connect.

# 12-08-2017

- https://www.troyhunt.com/passwords-evolved-authentication-guidance-for-the-modern-era/ The good rules of how to deal with passwords, from a client and application side. Mostly based on https://www.ncsc.gov.uk/guidance/password-guidance-simplifying-your-approach. Microsoft has also a nice guide https://www.microsoft.com/en-us/research/wp-content/uploads/2016/06/Microsoft_Password_Guidance-1.pdf
- https://www.youtube.com/watch?v=PorfLSr3DDI "Give me 15 minutes & I'll change your view of GDB"
- https://www.confluent.io/resources/kafka-the-definitive-guide/ A definitive great resources to grab :)
- https://databricks.com/blog/2017/07/11/introducing-apache-spark-2-2.html A recap about Spark 2.2 features

# 11-08-2017

- https://github.com/atlassian/react-beautiful-dnd Beautiful, accessible drag and drop for lists with reactjs
- https://github.com/aksakalli/gtop a nodejs blessed "top" !
- http://eu.battle.net/sc2/fr/blog/20944009 IA research were ongoing using Starcraft. Blizzard understood and creates a proper API for Starcraft 2 with full support!
- http://save418.com/ 
- https://medium.com/@rowillia/tautology-tests-7dabd81ade30 Be aware of how you are testing things, do not rewrite the impl in the test.
- https://medium.com/@cindysridharan/small-functions-considered-harmful-91035d316c29 writing small functions is always a good point, but sometimes: wrong abstraction, hard to follow, loss of locality (functions dispatched all over files)
- https://richardstartin.com/2017/07/23/still-true-in-java-9-handwritten-hash-codes-are-faster/ Unroll your array/string/collection hashCode custom method to be faster and remove some dependencies between iterations.

# 09-08-2017

- https://www.ctheu.com/2017/08/07/looking-at-kafka-s-consumers-offsets/ I wrote that
- https://medium.com/@mariusandra/kea-vs-setstate-redux-mobx-dva-jumpstate-apollo-etc-4aa26ea11d02 "kea" a new way of doing things, based on redux, made for React
- https://sentheon.com/blog/git-cheat-sheet.html A lot of "simple" git commands to know
- https://gist.github.com/paf31/adfd15fbb1ac8b99fc68be2c9aca8427 "Why You Should Use PureScript" .. "hire remote PureScript developers (and be willing to train them if necessary) and you will have no shortage of qualified candidates." Well, i wonder what the bosses would think about that.
- https://github.com/shekhargulati/building-java-web-apps-checklist The start of a checklist to create java front/back apps


# 08-08-2017

- http://antoinevastel.github.io/bot%20detection/2017/08/05/detect-chrome-headless.html Detecting Chrome Headless in Javascript
- https://code.facebook.com/posts/289921871474277/transitioning-entirely-to-neural-machine-translation/ Super interesting transition from ML to DL for languages translation
- https://plugins.jetbrains.com/plugin/9792-key-promoter-x A damn good plugin to learn the shortcut of the things we used to click
- https://www.ebayinc.com/stories/news/marko-ebays-cutting-edge-ui-tool-is-open-source-and-newly-updated/ "Marko". another UI framework, another dsl. By ebay. A mix of react and vuejs, kinda.
- http://www.lihaoyi.com/post/ScalaVectoroperationsarentEffectivelyConstanttime.html Scala Vector ops are not "Effectively Constant" time. Some bigO and log operations to demonstrate we can't say that.
- http://raganwald.com/2017/07/22/closing-iterables-is-a-leaky-abstraction.html the VERY importance of closing iterators that opens resources (and that need to be closed). by implementing "return" on iterator. It's called by for..of, destructuring automatically, but that's it. Must .return() explicitely otherwise.
- https://martinfowler.com/articles/rise-test-impact-analysis.html analyzing the call-graph of the source code to work out which tests should be run after a change

# 05-08-2017

- http://www.jetbrains.org/ring-ui/README.html JetBrains has open-sourced some UI components. Angular1 style :( But very nice nonetheless!
- https://github.com/Palindrom/JSONPatcherProxy Creating JSON-Patch (RFC6902) by observing objects through Proxies
- https://softwaremill.com/sttp-streaming-uri-interpolator/ More details about the streaming capabilities of sttp (an http-api that can work with different backends)
- https://blog.kowalczyk.info/article/wN9R/experience-porting-4.5k-loc-of-c-to-go-facebooks-css-flexbox-implementation-yoga.html Boring but useful. Experience porting 4.5k loc of C to Go. Translating the next commits to the original repo will be a pain.
- https://blog.buildo.io/http-routes-at-buildo-1424250c41d3 Replacing static routes + bindings, with Scala macros and a unique decl+def in the code itself. https://buildo.github.io/wiro/ was born. "A Scala library for writing HTTP routes"
- https://developers.google.com/web/updates/2017/07/devtools-release-notes Chrome 61 is out
- http://typelevel.org/blog/2017/08/04/cats-1.0-mf.html cats almost 1.0.0! New types available ReaderWriterStateT, and existing updated to be stack-safe
- http://virtuslab.com/blog/zinc-sbt-friendly-code/ Recap: never let unused imports, not use wildcard imports.
- http://www.beyondthelines.net/programming/introduction-to-tagless-final/ This is just a wonderful article about the "tagless final" technique. Basically, you never hardcode which monad you use in your trait, and just work with HKT.

# 02-08-2017

- https://medium.com/@Pinterest_Engineering/the-case-against-kotlin-2c574cb87953 A useful review about Kotlin, its lack and oddities (learning curve, build times, tools stability, static analysis tools..) but Google is behind!
- https://github.com/atomashpolskiy/bt bittorrent lib + cli in Java
- https://expo.io/tools From scratch to publish React Native app, Expo XDE make it easy to develop them
- https://www.confluent.io/blog/messaging-single-source-truth/ A good post Event Sourcing in general, why it's useful, how to, the impact, the way of thinking
- http://underscore.io/blog/posts/2014/07/27/readerwriterstate.html Using Reader and Writer monad to better manage the scope of things
- https://github.com/humanmade/tachyon An interesting stack using lambdas and s3 to generate thumbnails on demand. Less powerful than https://github.com/thumbor/thumbor but way more lighter
- https://github.com/alex/what-happens-when "... you type google.com into your browser's address box and press enter?" From the push on the key to the rendering.
- https://github.com/akka/akka/pull/23367 A Akka Flow can know be restarted (by producing a new Flow)
- https://peterbeshai.com/beautifully-animate-points-with-webgl-and-regl.html WebGL using a JS lib: regl.

# 01-08-2017

- https://github.com/blog/2409-build-a-game-in-13kb-or-less-with-js13kgames Impressive JS games in less than 13kB, totally crazy awesome.
- https://tenso.rs/demos/fast-neural-style/ Style-transfer neural network in the browser! (tensorflow)
- https://github.com/sivel/speedtest-cli Command line interface for testing internet bandwidth using speedtest.net. To automatize the thing!
- https://forum.sublimetext.com/t/rfc-default-package-control-channel-and-package-telemetry/30157 A sublime plugin sending metrics to a startup :(
- http://blog.scalyr.com/2014/05/searching-20-gbsec-systems-engineering-before-algorithms/ Searching in raw logs? Brute Force! It makes sense and simplify a lot the model.
- https://www.confluent.io/blog/chain-services-exactly-guarantees/ Another good post about Kafka transactions (valid inside Kafka, not outside, ofc)

# 29-07-2017

- https://manuel.bernhardt.io/2017/07/26/a-new-adaptive-accrual-failure-detector-for-akka/ Benchmarking failure detection algorithms with Akka
- https://github.com/graphcool/chromeless Run chrome automation in a lambda !
- https://stateofjs.com/ 2017 is there!
- https://medium.com/@duhroach/internal-ip-vs-external-ip-performance-76f15a650356 Never use public interfaces
- https://github.com/scala/scala/releases/tag/v2.12.3 Scala 2.12.3 out ! Mostly around performance, yeah.
- http://developer.lightbend.com/blog/2017-07-28-sbt-1-0-0-RC3-and-sbt-0-13-16/ and sbt 1.0 there in 2 weeks !
- http://szelei.me/rpc-benchmark-part1/ "rpclib" is based on msgpack, very performant
- https://fpj.me/2017/07/04/no-consensus-in-exactly-once/ Comparing Exactly once and consensus. Idempotence and transactions (with rollback) can provide exactly once.
- https://github.com/micrometer-metrics/micrometer The slf4j of the metrics in Java :-)
- https://about.sourcegraph.com/go/grpc-in-production-alan-shreve A nice recap of the features provided by gRPC, with lots of Go code

# 27-07-2017

- https://cloudplatform.googleblog.com/2017/07/three-steps-to-Compute-Engine-startup-time-bliss-Google-Cloud-Performance-Atlas.html
- https://github.com/rikschennink/fitty Fit text in a particular area
- https://www.theguardian.com/environment/2017/jul/25/google-enters-race-for-nuclear-fusion-technology Google is everywhere.
- https://medium.com/@djo/obsession-service-client-captain-train-cb0b91467fd9 Excellent article sur le service cli d'über qualité de captain train.
- https://github.com/github/brubeck brubeck is a simpler statsd
- https://techblog.bozho.net/concerns-blockchain-technology/ Are blockchains gonna change the world?

# 24-07-2017

- https://speakerdeck.com/thesandlord/kubernetes-best-practices Kubernetes Best Practices. non root. readonly fs. dumb-init. labels. istio, linkerd (service mesh).
- https://github.com/Duhemm/sbt-errors-summary I didn't know we had a sbt plugin to have those nicer errors (was not added to the original sbt to not break compat with emacs ..)
- https://www.reddit.com/r/scala/comments/6p550d/scalajs_vs_kotlin_compiled_to_javascript/ Some interesting point about Scala.js vs Kotlin/js. Scala.js way better for now. (interop, compat, )
- https://github.com/google/pik Another lossy format image by Google. No more info still.
- https://github.com/brannondorsey/wifi-cracking Always useful to know!
- https://github.com/danielmiessler/SecLists A damn crazy repo with tons of passwords list, fuzzy words
- http://pzemtsov.github.io/2017/07/23/the-slow-currenttimemillis.html currentTimeMillis() slow in Linux, ultra fast on Windows.

# 21-07-2017

- https://blog.scalac.io/improving-akka-dispatcher.html A new ExecutorService, lock-free, supposely faster, with a better core cache locality management
- http://www.beyondthelines.net/computing/akka-streams-patterns/ An interesting and not so long presentation of akka streams, with clear points
- https://medium.com/@drboolean/laziness-with-representable-functors-9bd506eae83f _Representable Functors_ and Reader monad
- http://goldbergyoni.com/checklist-best-practice-of-node-js-in-production/ 
- https://dev-blog.apollodata.com/the-next-step-for-realtime-data-in-graphql-b564b72eb07b Subscriptions spec incoming in GraphQL
- https://www.confluent.io/blog/real-time-financial-alerts-rabobank-apache-kafkas-streams-api/ Managing notifications and alerting using Kafka Streams
- https://groups.google.com/forum/#!msg/redis-db/5Kh3viziYGQ/58TKLwX0AAAJ Redis 4.0 out !!

# 19-07-2017

- https://blog.nightly.mozilla.org/2017/07/17/preview-storage-api-in-firefox-nightly/ "The global limit is calculated as 50% of free disk space"
- https://twitter.com/svensauleau/status/887281075294281733 Pattern Matching in JS
- https://www.confluent.io/blog/upgrading-apache-kafka-clients-just-got-easier/ Forward compat' between Kafka clients and brokers
- https://medium.com/the-node-js-collection/simple-server-side-cache-for-express-js-with-node-js-45ff296ca0f0 Caching http pages in nodejs. Hello, my name is varnish, or even nginx do that. :/
- https://blog.jetbrains.com/idea/2017/07/intellij-idea-2017-2-is-here-smart-sleek-and-snappy/ 
- https://hire.google.com/ New Google Service to manage people hiring in a company (integration with calendar, gmail.) Only US
- https://github.com/xori/gamblers-dice Excellent! A dice that respects the gambers fallacy dice. (the past alters the future)
- https://www.byte.nl/blog/dont-run-this-on-any-system-you-expect-to-be-up-they-said-but-we-did-it-anyway Upgrading 2000 ubuntu servers from 12 to 16. Fully automatized.
- https://www.confluent.io/blog/build-services-backbone-events/ https://www.confluent.io/blog/apache-kafka-for-service-architectures/ https://www.confluent.io/blog/building-real-time-streaming-etl-pipeline-20-minutes/ Confluent has really good articles about their platform and streaming in general. (and kafka ofc)

# 17-07-2017

- https://blog.tendigi.com/starbucks-should-really-make-their-apis-public-6b64a1c2e923 Starbucks API is now open :-)
- https://github.com/databricks/scala-style-guide Tips from Databricks about coding in scala
- https://www.atlantbh.com/blog/using-firebase-provide-real-time-notifications/ Using Firebase To Provide Real-Time Notifications on web (RealTime Database) and mobile (with Firebase Cloud Messaging)
- http://www.scala-sbt.org/1.0/docs/sbt-1.0-Release-Notes.html So may changes in sbt 1.0.0-RC2. Lots of deprecated and removed stuff, performance..
- http://scala-lang.org/blog/2017/07/12/second-dotty-milestone-release.html And Dotty is releasing 0.2.0-RC1
- https://react-etc.net/entry/apache-foundation-bans-use-of-facebook-bsd-patents-licensed-libraries-like-react-js ASF projects not allowed to use Facebook licensed software
- http://www.beyondthelines.net/computing/scala-future-and-execution-context/ Deep inside Scala's Futures and ExecutionContexts
- http://august.nagro.us/jvm-startup.html TLDR: Nailgun to preload all the jars separately.
- https://www.kernel.org/doc/html/latest/process/coding-style.html Linux kernel coding style with a lot of notes, some of them hilarious
- https://github.com/Kristories/awesome-guidelines A new awesome repo, guidelines for languages, api, rest, json, ...

# 12-07-2017

- https://github.com/segmentio/ksuid Kind of UUIDs orderable by time, hm (timestamp first)
- https://en.wikipedia.org/wiki/Heat_death_of_the_universe Scary future. We won't be there to assist to that anyway.
- https://segment.com/blog/exactly-once-delivery/ A very nice article about using kafka+rocksdb to eliminate duplicates inputs
- https://github.com/shieldfy/API-Security-Checklist A useful list, that will probably grow, to check when designing an API
- https://github.com/chtefi/checklists Needed to be done
- http://www.bbc.com/news/business-40504764 An awesome story every IT dev want to do :-) "The man who built a $1bn firm in his basement"
- https://qz.com/1019928/i-went-from-sedentary-academic-to-100-mile-marathon-runner-thanks-to-the-science-of-self-control/ A motivating post about self-control, and mental strength
- https://seashells.io/ This is a win. Pipe output from any command to the interweb, and have a live-console in the browser, with an anonymous link to share.
- https://randomascii.wordpress.com/2017/07/09/24-core-cpu-and-i-cant-move-my-mouse/ The more core you have, the slower is it! Amdahl's law.
- https://thehackerblog.com/the-io-error-taking-control-of-all-io-domains-with-a-targeted-registration/ This is demential.

# 09-07-2017

- https://www.addthis.com/blog/2013/04/16/building-a-distributed-system-with-akka-remote-actors/ An old feedback about Akka Remote (when Akka Cluster was not even out)
- https://github.com/EnterpriseQualityCoding/FizzBuzzEnterpriseEdition A wonderful example of #abstractAllTheThings to write a fizzbuzz program (almost 2k lines)
- https://medium.com/@rdsubhas/10-modern-software-engineering-mistakes-bc67fbef4fc8 Don't overengineer things.
- https://danluu.com/startup-options/ A long post talking about the "options" business in startup. It's quite complex, and basically, you're often screwed. :-D
- https://gist.github.com/alexandru/55a6038c2fe61025d555/2bfa0e28b7b69fa0a7007b0c5d4fa6447b431d5f A reflection about Monix's Task, by its creator
- https://www.youtube.com/watch?v=rwqwwn_46kA MobX into a state tree. New state management? https://github.com/mobxjs/mobx-state-tree
- https://thenewstack.io/identifying-collecting-container-data/ Tools for monitoring containers (docker stats, cadvisor, prometheus, grafana, (c)sysdig, datadog, dynatrace..)
- https://fullstackmark.com/post/11/better-software-design-with-clean-architecture A good intro to the Clean Architecture

# 08-07-2017

- https://www.howtogeek.com/168145/how-to-use-ssh-tunneling/ I totally forgot about that, a must read
- https://github.com/blog/2392-introducing-code-owners Auto notifying the right people to do code reviews (based on file type, folders etc.)
- http://whatthefuckisethereum.com/ explained differently according to who you are :) basically: you run program (on theplatform ethereum) on your comp', we pay you in ether.
- https://medium.freecodecamp.org/lessons-from-my-first-year-of-live-coding-on-twitch-41a32e2f41c1 Describing her experience to write open-source in front of everyone. Interesting, if you want to give a try!
- https://medium.com/@anicolaspp/simplified-testing-with-scalatest-and-custom-matchers-bd5297128ebc A nice reminder that we should write custom matchers in tests
- https://jvns.ca/blog/2017/07/05/linux-tracing-systems/ one thing to remember: perf trace.
- https://mapr.com/blog/performance-tuning-kafka-spark-streaming-telecom/ Some tips about improving performance of a kafka/ignite/spark streaming workflow.
- https://apacheignite.readme.io/docs/jvm-and-system-tuning Tuning Apache Ignite beucase it's important! Will definitely use it.
- http://jcommander.org/ A really great Java cli parser library, based on annotations.

# 06-07-2017

- https://briansteffens.github.io/2017/07/03/google-sheets-virtual-machine.html Making a virtual machine in Google Sheets. Create some registers, some memory, some instructions, and let gsheets execute it :o
- https://adexchanger.com/international/china-challenge-lessons-criteos-quiet-exit/ China market: too closed, too secret, they don't want to share, Criteo out!
- https://blog.mozilla.org/security/2017/06/28/analysis-alexa-top-1m-sites/ The security best practices is _very_ slowly being taken into account on the web
- https://www.gatsbyjs.org/blog/gatsby-v1/ !! I can update my blog with this now. edit: migration path sucks :( No codemods, damnit!
- https://blog.risingstack.com/mastering-async-await-in-nodejs/ Come on, async/await in JS is already so old.
- https://blog.expo.io/expos-website-2680a1ac1a7 A builder of mobile React native apps

# 04-07-2017

- https://www.nasa.gov/sites/default/files/files/E_Christiansen-MMODriskOverview.pdf Space is dangerous, yeah.
- https://github.com/patrick-steele-idem/morphdom An interesting way of patching the DOM, without virtual dom (just real dom against real dom)
- https://github.com/yoshuawuyts/choo A simple and fast frontend framework that uses morphdom behind the scene
- https://www.ianvisits.co.uk/blog/2017/06/10/cooling-the-tube-engineering-heat-out-of-the-underground/ Super interesting article about cooling the london tube. note: the heat is mostly caused by the brakes
- https://github.com/ashleymcnamara/learn_to_code All the resources needed to learn any language
- https://github.com/minio/minio Minio is an open source object storage server compatible with Amazon S3 APIs
- https://github.com/edenhill/kafkacat an alternative to kafka console consumer/producer
- https://stevesloka.com/2017/05/19/access-minikube-services-from-host/ Access kubernetes service ClusterIP types from outside by IP or service name. ie:  route add 10.0.0.0/24 $(minikube ip)
- http://rancher.com/ A platform to manage containers. Similar to openshift. Can work with k8s. "Container as a Service"
- http://blog.octo.com/la-ruee-vers-le-conteneur/ A fr article about Rancher
- https://github.com/weaveworks/cortex A multitenant, horizontally scalable Prometheus as a Service, currently in beta

# 30-06-2017

- http://swreflections.blogspot.fr/2013/06/automated-tests-as-documentation.html Are tests are enough as documentation? As least, they're up to date!
- http://www.enterpriseintegrationpatterns.com/ramblings/google_cloud_functions.html Using google cloud functions to listen/publish from/to pubsub
- https://www.spantree.net/blog/2017/06/26/scala-native-for-cli-tools.html A few Scala Native learnings: %%%, and random is not random (!)
- https://softwaremill.com/reactive-streams-in-scala-comparing-akka-streams-and-monix-part-2/ A small comparaison between akka streams and monix, some use-cases.
- http://cloudmark.github.io/FSM/ Good post about Akka FSM (finite state machine) and impl of a "at most once" basic system)

# 27-06-2017

- https://github.com/ChALkeR/notes/blob/master/Gathering-weak-npm-credentials.md Glorious "attack" on npm credentials
- https://dribbble.com/shots/3605964-Airbnb-AR-Map-Concept an awesome design that uses augmented reality, maybe soon at airbnb's?
- https://github.com/prettier/prettier/releases/tag/1.5.0 Who is not using Prettier yet?
- https://coreos.com/blog/prometheus-and-kubernetes-up-and-running.html Just playing with prometheus, grafana, k8s. Loving stack.
- https://kubernetes.io/docs/user-guide/kubectl-cheatsheet/ Title says all!

# 26-06-2017

- https://cloud.google.com/free/docs/map-aws-google-cloud-platform https://cloud.google.com/free/docs/map-azure-google-cloud-platform Map of Google services against AWS and Azure.
- https://cloud.google.com/apis/design/ 
- http://opentracing.io/documentation/ Create traces and "spans" of a request accross all the services (impls: jaeger, zipkin)
- https://www.alexkras.com/i-decided-to-disable-amp-on-my-site/ interesting feedback and learnings about Google AMP
- https://eng.uber.com/distributed-tracing/ I really need to use Jaeger, seems so great to monitor internals!
- https://github.com/kubernetes/heapster Monitoring kubernetes nodes and containers (and sending the metrics anywhere)

# 25-06-2017

- http://docs.scala-lang.org/overviews/macros/overview.html it's time to dive into scala macros!
- https://cloud.google.com/solutions/reliable-task-scheduling-compute-engine a "cron" system using pubsub to convey a message to trigger some functions
- https://shinesolutions.com/2017/03/23/triggering-dataflow-pipelines-with-cloud-functions/ Triggering dataflow pipelines with cloud functions triggered by putting some files on google cloud storage
- https://verylegit.link/ generate safe links from any url such as "http://not.verylegit.link/3R~.QuJR_Do>LR;og122virus)javaexploit.js.docm" ahah
- https://blog.mozilla.org/blog/2017/06/21/2-million-prize-decentralize-web-apply-today/ Got an idea? $2M !
- https://stackoverflow.com/a/32534239/529398 Oauth explained with donuts and a bank.
- https://github.com/scalajs-css/core we have css in js, and now we have css in scalajs!
- https://var.ci/ A new fresh github bot. Its commands are described through a .yml, can merge stuff etc.
- https://lists.debian.org/debian-devel/2017/06/msg00308.html important bug found in opcodes of skulake & kaby lake, leading to unpredctable system behavior
- https://github.com/alexandru/scala-best-practices i read them a long while ago, still useful to read them now :)
- https://github.com/LMAX-Exchange/disruptor exchanging messages between thread, in a pub-sub fashion, with controlled latency (ie: how to wait)
- http://blog.stackstate.com/the-container-monitoring-problem stackstate is a platform to monitor your containers, no matter the orchestration system (mesos, k8s, docker swarm..)
- https://www.youtube.com/watch?v=yLbdw06tKPQ Awesome talk about scala cake pattern, how and why, and also covers its big issues (lots of fucked up things with scalac, order of evaluations, deadlocks;;)

# 23-06-2017

- https://shipilev.net/jvm-anatomy-park/6-new-object-stages/ Optim: call functions after settings the var in the ctor, or you get a penalty (2 inits, one at 0, one at the value set in the ctor)
- http://www.brendangregg.com/blog/2016-08-09/gdb-example-ncurses.html A very great guide to gdb
- https://www.lightbend.com/blog/lightbend-podcast-play-2-6-is-coming-and-its-faster-than-ever Play 2.6, akka http, jwt, twirl DI inside, https://playframework.com/documentation/2.6.x/Highlights26

# 22-06-2017

- https://www.youtube.com/watch?v=RZIkFuDpV20 A very cool review on the new Twitter's design
- https://github.com/ThoughtWorksInc/each It can be quite handy hmm it converts imperative syntax to scalaz's monadic expressions
- http://www.luna-lang.org/ A visual language, converted to text, and functional. I wonder if it's scale on a real project.
- https://cloud.google.com/vision/docs/fulltext-annotations Detect text in pictures thanks to Google Vision
- https://martinfowler.com/articles/refactoring-external-service.html Refactoring step by step, in a bahavior-preserving way.
- http://www.cakesolutions.net/teamblogs/pitfalls-of-an-ungroomed-backlog Backlog Grooming, definitely necessary! You often clean up crap here :)
- https://www.47deg.com/blog/fp-for-the-average-joe-part-1-scalaz-validation/ ValidationNel, a very nice monad to accumulate errors, Scalaz
- https://blog.scalac.io/2017/05/25/scala-specialization.html I've never applied @specialized, i probably should have.


# 21-06-2017

- http://evelinag.com/blog/2017/06-20-stackoverflow-tabs-spaces-and-salary/index.html Tabs, spaces and salary. Part 2.
- https://en.wikipedia.org/wiki/Synesthesia "neurological phenomenon in which stimulation of one sensory or cognitive pathway leads to automatic, involuntary experiences in a second sensory or cognitive pathway"
- https://github.com/BranislavLazic/akka-cqrs-activator This inspires me to write some akka persistence thingy. #scala
- https://medium.com/webpack/webpack-3-official-release-15fd2dd8f07b Webpack 3 with hoisting (finally); and dynamic import bundle naming
- https://blog.teller.io/2017/06/12/the-api-for-your-bank-account-is-here.html An standard API over different Bank systems, glorious!
- http://www.summaread.com/ a site with TLDRs only! I should have done it first, damn :)
- https://www.confluent.io/product/connectors/ So many connectors in Kafka Connect now. Just need to use their Schema Registry to enjoy ;(
- https://fymhotsauce.rocks/blogs/news/my-uber-driver-robbed-me-so-i-took-uber-to-court-and-won Just use Uber to return from party, and you won't have troubles.
- https://speakerdeck.com/jboner/without-resilience-nothing-else-matters Be and live with resilience.
- https://shipilev.net/jvm-anatomy-park/7-initialization-costs/ Another super interesting article about jmh options, and JVM object initialization speed and optimization (through unsafe).

# 18-06-2017

- https://github.com/boltdb/bolt A popular embedded key/value database for Go.
- https://www.youtube.com/watch?v=-4Yp3j_jk8Q Write TLA+ (or PlusCal) specs (mathematically) of the code you're about to write, it can find subtle cases
- https://github.com/kailashahirwar/cheatsheets-ai Many many cheatsheets about ML and DL (tensorflow, keras, numpy, pandas, sckikit-learn, pyspark..)
- https://medium.com/front-end-hacking/being-rxjs-subjects-savvy-4aec5c8da99e Intro to rx subjects, publish/refcount, cold/hot obs. The article reminds me exactly of Andre Stalz's videos.
- https://softwaremill.com/reactive-streams-in-scala-comparing-akka-streams-and-monix-part-1/ a VERY tiny intro to comparing akka streams and monix.
- https://softwaremill.com/interval-based-rate-limiter/ implementing a rate limiter with akka streams
- https://ratpack.io/ https://github.com/pledbrook/lazybones Ratpack is a set of Java libraries for building modern HTTP applications.. It's very good, not verbose, reactive, modular, has some spring, guice, rxjava, jackson, hystrix modules

# 17-06-2017

- https://www.youtube.com/watch?v=8_DfwEpHE88 Martin Kleppmann - Conflict Resolution for Eventual Consistency (CRDTs)
- http://scala-lang.org/blog/2016/10/24/scalafix.html Codemods for Scala to Dotty
- https://www.youtube.com/watch?v=2ghtw7Bp0ME Colossus is a very performant scala microservice framework (tumblr)
- https://www.infoq.com/presentations/event-sourcing-jvm Not really JVM, but mostly Event Sourcing presentation
- https://www.infoq.com/presentations/reactor-3-java8 Reactor3, design, structure, reactive-streams, comparaison with RxJava, implementation in JS
- https://developers.google.com/web/updates/2017/05/devtools-release-notes Lots of nice update in Chrome 60 (lighthouse, rt code coverage,  async debug by default, third party badges (ads!))
- http://www.atrato.io/blog/2017/05/28/apex-kudu-output/ Writing into Kudu from Apache Apex
- https://www.youtube.com/watch?v=NvCcNM2vp3k Optics (not profunctors eh!) with Monocle, with Scala https://github.com/julien-truffaut/Monocle

# 16-06-2017

- http://developer.lightbend.com/blog/2017-06-12-faster-scala-compiler/ Yes! More scalac speed.
- https://12factor.net/ The Twelve-Factor App, some very nice and useful tips to apply in any project
- http://developer.lightbend.com/blog/2017-06-15-sbt-1-0-beta2/ sbt 1.0 beta2 !
- https://stackoverflow.blog/2017/06/15/developers-use-spaces-make-money-use-tabs/ I have no idea what am i using, because of auto indentation.
- https://www.erikheemskerk.nl/c-sharp-7-2-and-8-0-uncertainty-awesomeness/ C# is becoming more javascript'ish and scala'ish :D
- https://github.com/schemasafe/troy csql statically checked via macro in Scala. It reminds me of https://github.com/spotify/scio which does the same but with BigQuery.

# 15-06-2017

- https://codewithoutrules.com/2017/06/14/how-to-name-your-software/ _how not to name your software_
- https://github.com/gatsbyjs/gatsby/issues/419 gatsby 1.0 is coming, slowly
- https://softwaremill.com/akka-monitoring-with-kamon-part-2/ A good part 2 post about Kamon features and akka-http.
- https://github.com/scalalandio/chimney A small and maybe useful Scala lib to copy fields from one case class to another one (without specifying all field names), thanks to macros.
- http://www.lurklurk.org/linkers/linkers.html Interesting explanations about the linkers logic (C/C++), unix and windows
- http://blog.interviewing.io/what-really-matters-in-technical-interviews-we-analyzed-thousands-of-interviews-on-everything-from-language-to-code-style-heres-what-we-found/ 

# 14-06-2017

- http://sortbenchmark.org/NADSort2016.pdf The famous 100TB CloudSort benchmark, done in 3000s, for 150$ on Alibaba Cloud
- https://blog.risingstack.com/moving-node-js-from-paas-to-kubernetes-tutorial/ A nice intro to running a nodejs in kubernetes
- https://github.com/eBay/parallec 
- https://github.com/propensive/magnolia Magnolia is a generic macro for automatic derivation of typeclasses #scala
- http://blog.colinbreck.com/ A very good blog, with inspiring article about scala, akka streams, and self introspection.
- https://github.com/alibaba/react-intl-universal Another lib for i18n for React (but also vanilla it seems, who cares)

# 07-06-2017

- https://databricks.com/blog/2017/05/31/top-5-reasons-for-choosing-s3-over-hdfs.html After reading that, why would we use HDFS over S3 ? ;)
- https://medium.com/@kennyalive/quake-3-vulkanized-245cc349fdcf A dude reimplemented the rendering of Quake 3 with the Vulkan rendering API in barely 3 months! the "next" OpenGL
- https://blog.bradfieldcs.com/you-are-not-google-84912cf44afb Really like the "list" to resolve any problem: understand the problem domain, enumerate candidate solutions, read paper for one candidate, know why/when it was created, its context; advatages against disadvantages; then think if you use it, what happens, and what could change your mind?
- https://aadrake.com/command-line-tools-can-be-235x-faster-than-your-hadoop-cluster.html "Command-line Tools can be 235x Faster than your Hadoop Cluster" Catchy title of the Year. And I'm totally for this! We don't always need impala or spark or mapreduces. to process files.
- https://dev.office.com/fabric I really like the Office component library, and they also "offers" best practices about how/when to use each component.
- https://github.com/lloydmeta/enumeratum A better Scala enum? with name/value modifiers, macros that generates json boilerplates for any lib,. (play-json etc.)
- https://github.com/theiterators/kebs in the same vein, kebs offers macros to replace boilerplates for [slick, play-json, akka-http] serde

# 05-06-2017

- https://github.com/ThoughtWorksInc/feature.scala Nice Scala utilities. Through implicit, get the Caller of any function, create a Factory from any type
- http://blog.panoply.io/redis-vs-mongodb High level comparaison between Redis (speed, stable size) and MongoDB (scale, query model). 
- https://www.youtube.com/watch?v=9lWrt6H6UdE "What's Different In Dotty" Scala 3.0 in 2019 !.
- http://www.anishathalye.com/2017/06/04/testing-distributed-systems-for-linearizability/ Very interesting article about testing Linearizability (through linearization points)
- https://vimeo.com/170796168 Nice code talk about Slick. From 0 to some queries, everything explained, good!
- http://szymonkaliski.com/blog/2017-05-31-exploring-reasonml/ Dude exploring ReasonML to draw some balls :)
- https://www.slideshare.net/HadoopSummit/working-with-the-scalding-type-safe-api Criteo working with the Scalding type safe API
- https://vincent.bernat.im/fr/blog/2014-tcp-time-wait-state-linux A very interesting article about tcp time-wait connections (tcp_tw_reuse and tcp_tw_recycle effects)

# 04-06-2017

- https://github.com/phenomic/phenomic A gatsbyjs like project, to generate a static website from markdown pages+some reactjs code
- https://docs.microsoft.com/en-us/cognitive-toolkit/reasons-to-switch-from-tensorflow-to-cntk Microsoft abandonning TensorFlow in profit of their CNTK, for various reasons. (speed, accuracy, interop, ..)
- https://community.qlik.com/blogs/qlikviewdesignblog/2017/05/31/who-do-the-kudu-that-you-do Qlik now has a Kudu connector!
- https://zeit.co/tv zeit now centralize its videos (conf, tech talks..)
- http://schd.ws/hosted_files/apachebigdata2016/fd/Introduction%20to%20Apache%20Kudu.pdf an "old" (0.8) presentation of Apache Kudu, but still valid and interesting
- https://github.com/uber/react-map-gl Nice wrapper to do draggable maps with React, adding some layers etc.
- http://2ality.com/2017/05/util-promisify.html util.promisify is a bit more than just a simple wrapper
- http://uber.github.io/deck.gl/blog/2017/introducing-deckgl-v4 deckgl, a component when we can put inside a react-map-gl but not always!
- https://adriaanm.github.io/reveal.js/scala-2.12-2017.html Scala 2.12 & Beyond. Avoid Python 3! :-)

# 02-06-2017

- http://www.infoworld.com/article/3199186/javascript/nodejs-8-brings-sanity-to-native-module-dependencies.html A recap about nodejs 8 (v8 upgrade, turbofan+ignition, native deps, buffers, whatwg url (new URL(..)), npm5, util.promisify to remove those crappy callbacks(err, success).
- https://github.com/yandex/ClickHouse ClickHouse is a free analytic DBMS for big data. https://clickhouse.yandex
- https://nodesource.com/blog/getting-started-with-vs-code-for-node-js-development How to start properly with VSCode, which plugins to install etc. to do some js
- https://github.com/criteo/socco Create nice html page from commented source files
- https://github.com/prettier/prettier/releases/tag/1.4.0 Typescript and CSS support, and tons of enhancement for Javascript formatting

# 01-06-2017

- https://softwaremill.com/akka-monitoring-with-kamon-part-1/ Akka and Kamon, perfect match!
- http://underscore.io/blog/posts/2017/05/29/why-we-open-sourced-our-books.html underscore (good scala consulting company) opened source its books (about scala, cats, play, slick..), nice gesture
- http://www.scala-lang.org/blog/2017/05/31/first-dotty-milestone-release.html New cool features in Dotty, mostly about types (intersection, union), and true enums.
- https://github.com/OpenHFT/SmoothieMap A better and more latency-consistent-less-garbage HashMap

# 31-05-2017

- https://www.youtube.com/watch?v=EdFDJANJJLs V8 = TurboFan (perf) + Ignition (interpreter) pipeline. + WebAssembly compliant.
- https://status.github.com/ Today GitHub had some issues, 89.6194% of availability!
- https://github.com/rgbkrk/covfefe covfefe
- https://www.youtube.com/watch?v=EAaweXzUVh4 We should encode our password with Argon2, because it's damn slow to compute, takes CPU and memory. npm i secure-password. https://github.com/emilbayes/secure-password
- https://download.libsodium.org/doc/ The native crypto library used undernealth
- https://yarnpkg.com/blog/2017/05/31/determinism/ npm5 now does its own lock file, no interop with yarn
- http://kubernetesbyexample.com/ Some basic and clear explanations about the different items in kubernetes

# 29-05-2017

- https://medium.com/styled-components/announcing-v2-f01ef3766ac2 Style your components with.. style! Very good lib to do css-in-js (React)
- https://hnpwa.com/ Tons of Hacker News reader implementation, as Progressive Web Apps (React, Preact, Angular, Vue..) and their Lighthouse score
- https://github.com/facebook/jest/pull/3668/files How to switch jest from jasmine to a custom test runner
- https://www.amazon.fr/4-Hour-Workweek-Expanded-Updated-Cutting-Edge/dp/0307465357 "The 4-Hour Workweek" I heard it's a must-read, to think about ourselves! By Tim Ferris.
- https://jaxenter.com/know-your-scala-trivia-134395.html A tiny but interesting quizz around Scala
- https://www.scala-lang.org/blog/2017/04/01/announcing-skala.html A funny easter egg about Scala with a proposal to switch the keywords to German and misc.
- https://storybook.js.org/examples/ Tons of React components easily browseable, love it
- http://scala-lang.org/blog/2017/05/30/tribulations-canbuildfrom.html Good reminder about breakOut when transforming collection, I rarely think about it :(
- https://jakearchibald.com/2017/h2-push-tougher-than-i-thought/ HTTP/2 Push seems so complicated because of the implementation differences :(
- https://logrocket.com/ Another system to track client-side Javascript errors 
- https://nodejs.org/en/blog/release/v8.0.0/ That's a shitload of commits!
- https://martinfowler.com/articles/continuousIntegration.html I couldn't live without continuous integration :-)
- https://www.youtube.com/watch?v=EdFDJANJJLs V8 = TurboFan (perf) + Ignition (interpreter) pipeline. + WebAssembly compliant.
- https://www.cs.princeton.edu/~rs/talks/AC11-Cardinality.pdf Cardinality Estimation. Very interesting slidedown talking about some algo to estimate a cardinality in a stream (exact or approx), finishing by the HyperLogLog and HyperBitBit.

# 28-05-2017

- https://reviewable.io/ A review to help reviewing GitHub PRs. Looks like the advantage is it shows what changed since we last time we looked.
- https://medium.freecodecamp.com/so-whats-this-graphql-thing-i-keep-hearing-about-baf4d36c20cf A very good article/recap with pointers about GraphQL and its impls.
- https://medium.com/@abhiaiyer/top-5-recompose-hocs-1a4c9cc4566 Some usage of recompose, all HoC for React functional components
- http://www.lihaoyi.com/post/WartsoftheScalaProgrammingLanguage.html Enumerating some warts in Scala
- https://medium.com/styled-components/announcing-v2-f01ef3766ac2 Style your components with.. style! Very good lib to do css-in-js (React)

# 27-05-2017

- http://www.schveiguy.com/blog/2017/05/how-to-report-a-bug-to-microsoft/ Funny blog post about a guy desperate to have a competent person from the Microsoft support. He won't.
- https://blogs.msdn.microsoft.com/oldnewthing/20080324-00/?p=23033 Difference between .COM and .EXE, good ol' times!
- https://github.com/gitpitch/gitpitch AMAZING! add a file "PITCHME.md" (+.yaml for config) in your repo and use https://gitpitch.com/user/repo to get the corresponding generated slideshow.
- https://github.com/yhatt/marp Markdown presentation writer using Electron. Slideshow in .md, nice! Then using gitpitch to show them anywhere :)
- https://www.youtube.com/watch?v=aVuor-VAWTI Javascript Dates and Time APIs, and proposal for the future to fix all the existing crap
- https://toddmotto.com/rxjs-observables-observers-operators Another simple and clear implementation of Observable, as a tutorial

# 26-05-2017

- http://viktorklang.com/blog/Futures-in-Scala-protips-1.html Some simple tips about Future and ExecutionContext in Scala
- https://github.com/ory/editor?branch=master A very nice WYSIWYG on top of slatejs (React)
- https://github.com/ianstormtaylor/slate Rich Text Editor in React
- https://medium.com/@ktruong008/absolute-imports-with-create-react-app-4338fbca7e3d No more ../../.. using NODE_PATH with create-react-app
- https://flowartstation.com/2017/05/10/hilarious-winners-of-the-first-annual-comedy-wildlife-photography-awards/
- https://web.archive.org/web/20070222084110/http://destraynor.com/serendipity/index.php?/archives/102-Programming-Theorems.html "The likelihood of Perl being involved in a system is directly proportional to the length of time the system has been in maintenance."
- https://chadaustin.me/2017/05/writing-a-really-really-fast-json-parser/ really fast!
- https://chao-tic.github.io/blog/2017/05/24/dirty-cow Deep explanation about Dirty Cow, and why it's named like this. https://dirtycow.ninja/
- https://andreasgal.com/2017/05/25/chrome-won/ Not a surprise, but some graphs
- http://mattwarren.org/2017/05/25/Lowering-in-the-C-Compiler/ Lowering means "desugaring". Even apparents simple expressions can be actually sugar.
- https://www.reddit.com/r/javascript/comments/6dgdqv/is_it_yarn_still_in_demand_after_the_npm_release/ npm5 greatly improved since. Very good http://blog.npmjs.org/post/161081169345/v500
- http://www.nearform.com/nodecrunch/self-detect-memory-leak-node/ npm i memwatch-next heapdump 
- http://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/ Let's hack with tmux now! I'm so often ssh'ing anywhere and working on different stuff, that could help.

# 24-05-2017

- https://github.com/diegomura/react-pdf Easily create a pdf from some React components, very nice
- https://blogs.msdn.microsoft.com/bharry/2017/05/24/the-largest-git-repo-on-the-planet/ Part 2 of the GVFS story for huge git repo, by Microsoft.
- https://csswizardry.com/2017/05/little-things-i-like-to-do-with-git/ Some useful git aliases
- https://watabou.itch.io/medieval-fantasy-city-generator A medieval city generator, good stuff
- https://blog.heptio.com/ksonnet-intro-43f6183a97a6 "ksonnet: Simplify working with Kubernetes configurations" Generate the yaml config from a way simpler description http://ksonnet.heptio.com/ it also has a VisualStudioCode plugin

# 23-05-2017

- https://blog.risingstack.com/packing-a-kubernetes-microservices-with-helm/ I didn't know this Helm thing, quite interesting! "The Kubernetes Package Manager"
- https://github.com/spark-jobserver/spark-jobserver Start Spark jobs just by calling a REST API and retrieve results the same way, + jobs can share contexts and (named)rdds
- https://www.chrisstucchio.com/blog/2013/hadoop_hatred.html Not being able to use excel is no reason to use Hadoop, indeed ^^
- https://hackernoon.com/integrate-structor-with-create-react-app-3e8be15bc395 Structor, a WYSIWYG for React Components
- https://github.com/wulkano/kap A nice and slick screen recorder for OSX!
- https://medium.com/@kevinj_50886/a-progressive-web-application-with-vue-js-webpack-material-design-part-2-a5f19e70e08b Using Vue and Firebase
- https://blog.risingstack.com/getting-started-with-aws-lambda-and-node-js/ Creating a tiny nodejs lambda on AWS with "Serverless" https://github.com/serverless/serverless (generic to cloud providers, AWS, Google, Azure)

# 22-05-2017

- https://vimeo.com/165922572 Monix: to compose async programs. Tasks.
- http://symfony.com/blog/an-open-source-web-platform-for-the-new-president-of-france Finally, a website about politics using modern technology in France!
- https://github.com/sindresorhus/copy-text-to-clipboard A simpler and lighter! way to do a copy in modern browser (tiny tiny!)
- https://egghead.io/lessons/rxjs-convert-rxjs-subjects-to-observables Tips by Andre Staltz on RxJS
- https://developer.github.com/v4/guides/ GitHub API going GraphQL
- https://manuel.bernhardt.io/2017/05/22/akka-streams-notused/ At first, I was "wtf is dat" too. Not anymore.
- https://github.com/ipselon/structor A UI builder in React? Tried it, not very fan (not a good ux)
- https://formidable.com/open-source/spectacle-editor/ Stumbled upon their editor to create nice powerpoint prez in React
- https://github.com/tj/react-batch Batch actions to avoid overflowing the syncness of current React (using a "Batch" component)
- https://nickcraver.com/blog/2017/05/22/https-on-stack-overflow/ SO and all its sub/domains now full HTTPS: the story, and the mistakes
- https://hpbn.co/ "High Performance Browser Networking" by Igor Grigorik. Need to read that one day :(
- https://shipilev.net/jvm-anatomy-park/12-native-memory-tracking/ Track where the JVM memory goes (the heap is just a tiny part). Flags involved!
- http://www.adaltas.com/en/2016/11/14/hive-calcite-and-druid/ Druid in Hive, can't wait to try that :-) But still a lot of ticket to do it seems https://cwiki.apache.org/confluence/display/Hive/Druid+Integration

# 21-05-2017

- https://github.com/react-toolbox/react-toolbox Nice React components toolkit that follows Google Material Design specs.
- https://github.com/glenpike/npm-g_nosudo Never install something globally, done. :P
- http://www.midnightdba.com/Jen/2017/05/employers-let-people-work-home Definitely! I'm already enjoying this, 1d/week generally. Good enough.
- https://daringfireball.net/linked/2017/05/20/gilbertson-amp Against Google AMP
- https://medium.com/the-astronomer-journey/airflow-and-the-future-of-data-engineering-a-q-a-266f68d956a9 Airflow next Apache release and its future
- https://www.microsoft.com/en-us/research/blog/p-programming-language-asynchrony/ https://github.com/p-org/P "P" is a new language by Microsoft. The program describes a events and state machines, is message-driven, and compile down to C. (and there is also P#)
- https://dzone.com/refcardz/reactive-programming-akka Another intro to Akka's principles.. In Java
- https://blog.cloudflare.com/standing-up-to-a-dangerous-new-breed-of-patent-troll/ Cloudflare pissed off about patent trolls company will retaliate.
- https://github.com/lampepfl/dotty/issues/2491 Proposal by @odersky to implement an indentation-based parser for Scala
- https://www.twitch.tv/sentdex A neural network playing GTA5, wonderful

# 20-05-2017

- https://aboveintelligent.com/using-tensorflow-to-classify-hotdogs-8494fb85d875 Using TensorFlow to classify hotdogs (Silicon Valley style)
- https://customvision.ai/ By Microsoft: upload image with labels (or let Custom Vision add some), let it train, and use its REST API to evaluate. Crazy good stuff.
- https://zeit.co/blog/next3-preview#next-export Next now support build without server to serve it (just plain static), and it will handle lazy components loading on the fly thanks to dynamic imports.
- https://medium.com/@julsimon/create-your-own-basquiat-with-deep-learning-for-much-less-than-110-million-314aa07c9ba8 Basquiat is a painter. Use a neural network to create the same style for any picture.
- https://github.com/developit/preact-cli PWA made easy! Seems so good to start a small perfect project. Every needed useful features bundled automatically.
- https://github.com/prettier/prettier/pull/1636 Prettier will soon support css
- https://github.com/stylelint/stylelint Never used this one. The css linter!
- https://scastie.scala-lang.org/ Scastie out of beta! It was announced in Feb.
- https://facebook.github.io/react/blog/2017/05/18/whats-new-in-create-react-app.html This update (1.0.0) motivated me to update an existing app, cool new features!
- https://yarnpkg.com/blog/2017/05/12/introducing-yarn/ "yarn create x y", just a shortcut for "yarn global add create-x; create-x y;"
- https://www.clever-cloud.com/blog/engineering/2015/05/20/why-auto-increment-is-a-terrible-idea/ Against integers pk, use uuid instead. I kinda agree! Let API generate the uuid.
- http://www.brendangregg.com/blog/2016-12-27/linux-tracing-in-15-minutes.html ftrace, execsnoop, kprobe, the perf-tools and bpf tools !
- https://shipilev.net/jvm-anatomy-park/11-moving-gc-locality/ Very interesting: the GC also reorganize memory to facilitate data sequential readings (better locality)

# 18-05-2017

- https://aiexperiments.withgoogle.com/drum-machine Using ML to sort similar sounds, interesting experiment!
- https://panic.com/blog/stolen-source-code/ TLDR: always be on your guard when your os asks you security question :(
- https://medium.com/@contact_16315/firebase-costs-increased-by-7-000-81dc0a27271d No thanks to Firebase. Never code against a particular service, abstraction please.
- https://github.com/gmattie/Data-Pixels Pixel art made easy
- http://www.hipstercode.com/blog/31/ "What I think of the ELM Programming Language" He find it useless. No end game usefulness. Not a ELM expert but disagreeing a bit. It will prevent losing time later and you must code right at least (functional!)
- https://github.com/snowplow/scala-forex A lib to perform exchange rate lookups using openexchangerates.org ($$)
- http://pyroclast.io/blog/2017/05/17/the-future-of-event-stream-processing.html The story was great: from database centric to log centric arch.
- https://open.dgraph.io/post/badger/ A (better?) RocksDB (key-value store) ? In Go, specialized for SSDs.
- https://adexchanger.com/platforms/dsps-ssps-clean-cut-off/ One can always play with auctions! DSP SSP AdExchanges.
- http://blog.isquaredsoftware.com/2017/05/idiomatic-redux-tao-of-redux-part-1/ 
- https://hackernoon.com/react-europe-2017-551961487403 A nice TLDR of React Europe confs
- https://www.postgresql.org/about/news/1749/ PostgreSQL 10 incoming. Better scaling (replica, partitioning, parallelism, )
- https://github.com/yandex/gixy Nginx configuration static analyzer. Always useful!

# 17-05-2017

- https://medium.com/airbnb-engineering/democratizing-data-at-airbnb-852d76c51770 Airbnb talks about its Dataportal tool, for employees to discover any datasource they can access, metadata, which user is using it, with what it is generally joined etc. Neo4j and ES in da place.
- https://litmus.com/community/discussions/6489-using-css-grid-for-the-latest-litmus-newsletter-layout Using css grid in emails. In not supported, fallback to one column one. Very cool.
- https://github.com/amark/gun Stumbled once again upon this db; I will definitely try to use it in a side project.
- https://github.com/brysgo/graphql-gun Querying Gun with GraphQL, that's even better
- http://blog.octo.com/vers-une-usine-de-developpement-2-0/ Les usines de développement. Bonne présentation.
- https://github.com/knowbody/crra Create Reason React App ! Reason, reason.. should we "learn" it?
- https://github.com/paulp/psp-std An alternative to the scala standard lib. (more lazy)

# 15-05-2017

- https://tools.ietf.org/html/rfc7807 How to deal with errors for HTTP APIs
- https://www.rewritinghistorycasts.com/ Dude rewriting old (or not) C program such as cat, and git.
- https://www.malwaretech.com/2017/05/how-to-accidentally-stop-a-global-cyber-attacks.html By registereing a domain, the ransomware worm stops. Such tech.
- https://www.youtube.com/watch?v=2742pWdUm6c A nice dive into Scalac, learned some stuff about the phases, good and funny talk.
- https://www.youtube.com/watch?v=H28QqxO7Ihc "Move Over Free Monads: Make Way for Free Applicatives! — John de Goes" A bit complicated when you don't use them often :(
- https://twitter.com/leeb/status/863903474576007169 Lee Byron asking if big companies are using GraphQL. Big companies' employee answer massively, yes!
- https://github.com/fantasylandinst/fcop A Code Of Conduct. "Fantasyland [Institute] Code of Professionalism" for professional communities
- https://medium.com/airbnb-engineering/rearchitecting-airbnbs-frontend-5e213efc24d2 AirBnb being transparent about their stack's updates and cleanup to react/redux/graphql, from RoR.

# 12-05-2017

- http://typelevel.org/scala/ Typelevel's Scala compiler is like babel stage 0 of the officiel Lightbend Scala compiler
- https://www.youtube.com/watch?v=qwOyZifmi3Q Tuning Query Performance with N1QL in Couchbase => multidimensional scaling MDS (+ duplicate indexes), index service: more ram! for cache. explain the query, hint about indexes, create indexes. If mass update: use view query instead (not real time, batched). Ask for stale data if possible. Limit N to shortcut quickly.
- https://fr.wikipedia.org/wiki/Jeddah_Tower The future tallest tower in the world. 1km.
- https://kierantie.com/a/burnout/ A feedback about getting burnout.
- https://lcamtuf.blogspot.fr/2014/11/pulling-jpegs-out-of-thin-air.html Generating JPG by a "fuzzer" http://lcamtuf.coredump.cx/afl/ ("use genetic algorithms to automatically discover clean, interesting test cases that trigger new internal states in the targeted binary")

# 11-05-2017

- https://blog.cloudflare.com/anonymity-and-abuse-reports/ Cloudflare's transparency about their changing abuse reports model
- https://developer.couchbase.com/documentation/server/current/architecture/services-archi-multi-dimensional-scaling.html Multi dimensional scaling with Couchbase. (scale its different services, differently)
- https://developer.lightbend.com/blog/2017-05-08-cinnamon-2-4-with-opentracing-integration/ "Easy" tracing of Akka actors interactions. Seems so great. Would like to give a try! with Jaeger(uber) or Zipkin (UIs)
- http://blog.colinbreck.com/patterns-for-streaming-measurement-data-with-akka-streams/ Nice tips about Akka Streams
- https://www.confluent.io/blog/optimizing-apache-kafka-deployment/ A good whitebook about kafka producer/broker tuning
- http://www.thedailybeast.com/articles/2017/05/10/u-s-to-ban-laptops-in-all-cabins-of-flights-from-europe Title says all. Da hell.
- http://blog.cloudera.com/blog/2017/05/hail-scalable-genomics-analysis-with-spark/ Spark can work with tremendous amount of data; here, DNA, with a special wrapper "Hail".
- https://blog.acolyer.org/2017/05/02/corfu-a-distributed-shared-log/ Another append-only log software. Logs are mapped directly to the storage itself, you don't pass through a master, but just grab a token to know where to write and you do. https://github.com/CorfuDB/CorfuDB
- https://github.com/pathikrit/scalgos Classic algos properly implemented in scala <3
- https://dzone.com/articles/java-9-besides-modules Useful recap on java9 (no jigsaw)
- https://medium.com/@qix/how-i-wasted-a-whole-day-trolling-with-assembly-32a3bbbc2d60 Funny trolling using asm, quite interesting and some nice "tips" in there
- http://fluent.microsoft.com/ I don't know. A "design system".
- https://sourcemaking.com/ Very nice website listing and resuming tons of designs pattenrs, antipatterns, refactoring techniques
- https://www.techempower.com/benchmarks/ Round 14 of TechEmpower's web framework benchmarks

# 10-05-2017

- https://github.com/Microsoft/TypeScript-React-Starter TS + React good starter guide
- https://www.bloomberg.com/news/articles/2017-05-10/tesla-s-solar-roof-is-finally-ready-for-you-to-buy Tesla solar roof is just so great, because it can be textured, and is "cheap".
- https://github.com/facebook/yoga Totally forgot about this project. "Implement" the flex norm to be used for anything outside css.
- http://codepen.io/jlongster/pen/YVejaV A simple button, but neat idea: it skews according to where you click on it.
- https://css-tricks.com/easing-linear-gradients/ Never noticed that linear-gradient actually sucks because there is no ease.
- https://docs.microsoft.com/en-us/azure/cosmos-db/introduction On paper, CosmosDB seems just like the perfect DB. Running on Azure.
- https://www.cockroachlabs.com/blog/cockroachdb-1-0-release/ CockroachDB seems very promising too. Distributed SQL.
- https://en.wikipedia.org/wiki/PACELC_theorem Broader than CAP: "Else Consistency", or "Else Latency" (tradeoff when running normally). AP are trading off Latency (give up consistency for lower latency), CP are trading off Consistency (give up latency for consistency)
- https://appelsiini.net/2017/reverse-engineering-location-services/ Interesting Reverse Engineering of the Location services from Apple. Protobuf inside. 
- http://blog.hovland.xyz/2017-04-22-stop-overusing-interfaces/ DI using concrete class. Yes, same here, hopefully. Good read if you're using Ixxx everywhere.
- https://www.infoq.com/articles/rest-anti-patterns Old article, but still valid, about REST anti-patterns to be aware of. 
- http://blog.akka.io/typed/2017/05/05/typed-intro Akka typed!!!!!!!!!!!! Not fan of the "new" syntax. The untyped is so lighter, arg.

# 09-05-2017

- https://cherubini.casa/why-i-shut-down-wizards-town-and-left-mastodon-6d4e631346b3 Porn on Mastodon is a complex story.
- https://www.nytimes.com/2017/05/09/sports/polish-climbers-to-scale-deadly-k2-peak-in-winter.html Very interesting climbing stories.
- https://github.com/benalexau/rpc-bench gRPC against Aeron and KryoNet. Aeron wins easy.
- https://jcp.org/en/jsr/results?id=5959 No Jigsaw in Java9! (modules)
- http://www.brendangregg.com/blog/2017-05-09/cpu-utilization-is-wrong.html CPU usage is composed of cpu instruction per cycle IPC (between 0 and 4/5 generally) + CPU stalled cycles (STL) (memory bound)
- http://www.brendangregg.com/blog/2016-11-30/linux-bcc-tcplife.html Get tcp connection lengths (lifespan)
- http://stackoverflow.com/questions/2669690/why-does-google-prepend-while1-to-their-json-responses prepending json resp by some js code (while(1); for(;;)) to prevent Json hijacking
- http://www.reuters.com/article/us-uber-tech-crime-exclusive-idUSKBN1802U1 "The technology was used partly to prevent fraud and protect drivers from harm, the company blog post said. If a ride request was deemed illegitimate, Uber's app showed bogus information and the requester would not be picked up, the employees told Reuters." Nice!

# 06-05-2017

- http://charlesleifer.com/blog/your-idea-sucks/ About the difficulty of managing an open-source project
- http://formidable.com/blog/2017/infinite-state-composition-with-freactal/ Nice article about Freactal, a new state management system, based on FP, allowing composition, and is all-async (Promise).
- https://github.com/chtefi/couchbase-bucket-listener Worked on this, fix some bugs, and added some features.
- http://devteams.at/stop_the_daily_standup_meeting I like his solution: to find out if you need the standup, just stop it and see, instead of trying to find alternative means.

# 05-05-2017

- https://twitter.com/pomeranian99/status/858856994438094848 The only situation where you don't care of memory leaks: when the device is gonna explode!
- https://akrzemi1.wordpress.com/2017/04/27/a-serious-bug-in-gcc/ Learned about the RAII resource management (ctor+dtor)
- https://www.nasa.gov/aero/nasa-issues-a-challenge-to-speed-up-its-supercomputer-code "NASA is looking for qualified people who can ... analyze the performance bottlenecks" Fortran FTW!
- http://www.cakesolutions.net/teamblogs/typelevel-1-typeclasses Another intro to typeclasses in Scala
- https://stuff-gil-says.blogspot.fr/2017/05/zing-hits-trifecta.html The Azul JVM seems so good. Very fast optimized startup. Now backed by LLVM and its intrinsic optimisations.
- http://blog.joda.org/2017/04/java-se-9-jpms-modules-are-not-artifacts.html Java Modules don't need external tools to manage dependencies. It's just about modules (namespaces), packages, classes, methods.. No group, organization, or version.
- https://alexandrnikitin.github.io/blog/high-performance-dotnet-by-example/ Really like this article about optimisation. Multiple techniques are used, API redesign, data structure changes, hashing technique (open addressing strategy), no division, caches optim. unsafe sections

# 04-05-2017

- https://blog.timescale.com/time-series-data-why-and-how-to-use-a-relational-database-instead-of-nosql-d0cd6975e87c Introduction to timescaledb, a timeseries db on top of PostgreSQL.
- https://github.com/scala/pickling Ser/deser ("pickle") anything with a generic Scala abstraction.
- http://www.rankred.com/nasa-coding-rules/ I always try to apply the "Declare Data Objects at Smallest Level of Scope".
- https://medium.com/webpack/webpack-and-rollup-the-same-but-different-a41ad427058c Reminder: Webpack for apps, Rollup for libs.
- https://softwaremill.com/comparing-scala-relational-database-access-libraries Wonderful and useful comparaison between Slick, Doobie, Quill, and ScalikeJDBC. Favor into Slick and Doobie, clearly.

# 03-05-2017

- http://waitbutwhy.com/2017/04/neuralink.html A HUGE story about the new Elon Musk's company Neuralink and mostly about brain/systems interactions. Explanations from the beginning.
- https://github.com/facebook/prepack Again, Facebook released what looks like a awesome program, that evaluates what it can in a JS program to reduce the bundle size at the end and improve perf (because less things to evaluate for the browser).
- https://github.com/danielstjules/swaddle Thanks to JS Proxy, automatically query an API by typing pure javascript methods (that does not really exist), but intercepted by the Proxy
- https://medium.com/missive-app/45-faster-react-functional-components-now-3509a668e69f 45% better perf on functional components, just by not using JSX/React.createElement. Bam.
- http://tpolecat.github.io/2017/04/25/scalac-flags.html Flags for Scalac, I love them!
- http://latkin.org/blog/2017/05/02/when-the-scala-compiler-doesnt-help/ Never linked this type generalization neither. Causes only bugs..

# 02-05-2017

- https://staltz.com/why-we-actually-built-xstream.html To get hot obs only and and keep it small.
- http://50linesofco.de/post/2017-02-06-javascript-in-parallel-web-workers-transferables-and-sharedarraybuffer Very good post about Web Workers and communication with them, using SharedArrayBuffer.
- http://kazet.co/2016/04/29/temporary-hacks.html All code is temporary. And I never write "XXX".
- https://docs.google.com/presentation/d/1kd2OluTSpqSW8HxmtIge7TLopYkw1DrtrI5m0UIVcUg/edit#slide=id.ge31b4dbb6_0_0 "A practical guide to monitoring and alerting with time series at scale"; by Google
- https://medium.com/@cindysridharan/what-is-devops-5b0181fdb953 DevOps is not a person, but a philosophy.
- http://blog.octo.com/etat-de-lart-des-solutions-cross-platform-mobile/ State of the art about mobile cross-platforms
- https://capnproto.org/news/2017-05-01-capnproto-0.6-msvc-json-http-more.html Cap'n Proto 0.6 out! It's been a while.
- https://youtube.com/new New Youtube style, again! Using polymer this time.
- http://blog.sqlizer.io/posts/sql-43/ SQL, 43 years of existence! The Whys.
- https://github.com/basecamp/handbook/blob/master/benefits-and-perks.md Basecamp is so good. What is it hiding?
- https://medium.com/@mbostock/a-better-way-to-code-2b1d2876a3a0 Looks awesome! A jupiter with JS. Not sure about real work, some command would need to be delegated to a server, but it seems okay anyway!

# 01-05-2017

- https://medium.com/smyte/streaming-similarity-search-for-fraud-detection-64d7476953d4 I love Smyte technical article! Smart peeps.
- https://github.com/alexanderepstein/Insomnia Notify the dev to go to sleep before it's too late!
- http://www.ybrikman.com/writing/2014/04/09/six-programming-paradigms-that-will/ Some langages are not common and based on lesser-known paradigms.
- https://medium.com/@tarkus/getting-started-with-relay-modern-for-building-isomorphic-web-apps-ae049e4e23c1 An interesting post resuming why/how to use Relay in a React app
- https://medium.com/@wesharehoodies/simple-beginner-guide-for-webpack-2-0-from-scratch-part-ii-66beb5dbccc2 A simple intro to webpack 2 and its loaders.
- https://www.youtube.com/watch?v=zbGiOcSeq1Y "Let the Scala compiler work for you" Some tips about scala types and implicits.
- https://stefanheule.com/blog/how-many-x86-64-instructions-are-there-anyway/ I was sure it was complicated!
- http://samsy.ninja/morphin/index.html An impressive canvas js demo
- https://speakerdeck.com/aemcknig/image-performance-good-for-your-users-good-for-your-business Engineer from Etsy talking about reducing image size for better conversions.
- http://typelevel.org/blog/2017/05/02/io-monad-for-cats.html A long post about casts-effect and the introduction of the "IO" monad, its purpose, usage and examples.
- https://databricks.com/blog/2017/01/19/real-time-streaming-etl-structured-streaming-apache-spark-2-1.html Spark Streaming 2 How To
- https://databricks.com/blog/2017/02/23/working-complex-data-formats-structured-streaming-apache-spark-2-1.html Playing with data types, structure, and streaming (api exploration)
- http://blog.xebia.fr/2017/04/19/agile-smells-sprint-retrospective/ Bad smells in Agile retrospectives
- https://developers.google.com/web/updates/2017/04/headless-chrome How to use the new headless Chrome
- https://medium.com/@WebReflection/javascript-dynamic-import-export-b0e8775a59d4 Props to bring Javascript async exports (async import are already on its way https://www.chromestatus.com/feature/5684934484164608)


# 28-04-2017

- http://blog.xebia.fr/2017/04/18/devoxx-france-2017-retour-sur-les-conferences-du-jour-3/
- http://bfmbusiness.bfmtv.com/entreprise/cette-fois-amazon-commence-vraiment-a-inquieter-google-et-facebook-1141702.html Amazon, the new ads competitor? It knows what we really buy.
- https://hackernoon.com/the-javascript-phenomenon-is-a-mass-psychosis-57adebb09359 JS is full of crap, yes we know and we like it!
- https://blog.intracto.com/paying-technical-debt-how-to-rescue-legacy-code-through-refactoring "Paying Technical Debt - How To Rescue Legacy Code through Refactoring" Some tips and step-by-step how to
- https://github.com/airbnb/react-sketchapp Airbnb's open-sourced its lib to render React components to Sketch http://airbnb.io/react-sketchapp/
- https://www.quora.com/Should-I-fire-a-software-engineer-for-always-working-on-his-side-projects-during-office-hours "Should I fire a software engineer for always working on his side projects during office hours?"
- https://www.troyhunt.com/reckon-youve-seen-some-stupid-security-things-here-hold-my-beer/ Some very, very stupid user/password security issues on (big) websites..
- Too much Stepmania

# 19-04-2017

- https://github.com/citycide/babel-plugin-partial-application Scala _'s in JS, transformed by babel into lambda. Woot!
- https://blogs.msdn.microsoft.com/oldnewthing/20170418-00/?p=95985 "a customer reported an error in the map used by Flight Simulator" Poor Microsoft and stupid people.
- https://battle.net/download/getInstallerForGame?os=WIN&version=LIVE&gameProgram=STARCRAFT We can download Starcraft + Broodwar for free now!
- http://cr.openjdk.java.net/~briangoetz/amber/pattern-match.html An overview of what the Java pattern matching would be (unofficial)
- https://blogs.windows.com/msedgedev/2017/04/19/modernizing-dom-tree-microsoft-edge The interesting evolution of IE/Edge and the DOM, speed, performance.
- https://tech.zalando.com/blog/achieving-3.2x-faster-scala-compile-time/ Interesting compile time optimisation in Scala with Hydra https://triplequote.com/hydra/ 
 - https://blog.docker.com/2017/04/introducing-the-moby-project/ The Moby Project: a standard framework for container. docker/docker is now moby/moby !
- http://scala-lang.org/news/releases-1Q17.html Scala 2.11.11 is now the last of the 2.11 series! 2.13 in progress.
- https://stackoverflow.blog/2017/04/19/programming-languages-used-late-night/ Funny and interesting study about people, stackoverflow, programmers: looking at pattern to find out when which langage is worked outside of business hours, as hobby, which hours, etc.

# 18-04-2017

- https://medium.com/@DmitrySoshnikov/regexp-tree-a-regular-expressions-parser-with-a-simple-ast-format-bcd4d5580df6 A RexExp parser to get the AST of a regex
- https://github.com/gabru-md/StarMe-Bro/commit/1a56d120d2d7185d949df103a32f2ade64041a19 A simple JS code to register Github "bot". Basically, there is no capcha, no email check, so it's quite straightforward.
- http://nibblestew.blogspot.fr/2017/04/why-dont-you-just-rewrite-it-in-x.html spoiler: Because it's very slow, boring, time consuming, and the business value is around 0.
- https://mondaynote.com/apples-new-file-system-who-cares-3ba440cd4d84 I didn't even know their system was called APFS.
- https://www.simple.com/engineering/a-change-data-capture-pipeline-from-postgresql-to-kafka Using CDC to push data to Redshift in their case. Compares to Bottledwater &lt3.
- http://blog.cloudera.com/blog/2017/04/apache-kudu-read-write-paths/ Some insights about how Kudu works (WAL and scan)
- https://medium.com/@mngrwl/everything-about-self-driving-cars-explained-for-non-engineers-f73997dcb60c As the title says! Deep learning, computer vision, robotics, navigation, explained with words.
- https://motherboard.vice.com/en_us/article/princetons-ad-blocking-superweapon-may-put-an-end-to-the-ad-blocking-arms-race Using computer vision to block ads. Provides a Chrome extension but couldn't see it in action..
- https://mathoverflow.net/questions/81960/the-dzhanibekov-effect-an-exercise-in-mechanics-or-fiction-explain-mathemat This is the famous effect observed in space where a rotating piece suddenly rotates on another axis by 180deg.
- https://techiedelight.quora.com/500-Data-structures-and-algorithms-interview-questions-and-their-solutions To bookmark! So many algorithms and data structures.
- https://blog.chromium.org/2017/04/real-world-javascript-performance.html Better measuring performances to improve performances.
- http://thehackernews.com/2017/04/computer-in-prison.html Title says all: "Prison Inmates Built PCs from e-Waste and Connected Online Using Prison Network" Good guy!
- https://publishers.brave.com/ If you own a website, you can set up yourself to brave, to get money!
- https://blog.scottnonnenberg.com/better-git-configuration/ Some git tips, how to configure our .gitconfig
- https://github.com/druid-io/druid/releases/tag/druid-0.10.0 Druid 0.10.0 out !! built-in sql query interface, and better perf in general.
- https://balamaci.ro/kafka-streams-for-stream-processing/ A very good post about Kafka Streams, its processors, its states, some Rx references
- https://www.cloudbees.com/blog/fileinputstream-fileoutputstream-considered-harmful For apps with lots of IO, better to use Files.newInput/OutputStream to avoid GC pressures, created by the old API.
- https://www.confluent.io/blog/stories-front-lessons-learned-supporting-apache-kafka/ Nice sharing of 3 support ticket Confluentinc answers about Kafka underreplication, liveness check, moving of data

# 11-04-2017

- https://github.com/antirez/kilo "A text editor in less than 1000 LOC with syntax highlight and search." and a crazy walkthought to code it, step by step (in C). http://viewsourcecode.org/snaptoken/kilo/index.html
- https://blog.getbotmetrics.com/150x-speedup-in-real-time-dashboards-with-postgres-9-5-2e987a5b906e Scaling by rolling up data, here with postgresql and triggers
- https://github.com/tootsuite/mastodon A GNU Social-compatible microblogging server 
- https://staltz.com/an-off-grid-social-network.html "Scuttlebutt", a p2p social system. With https://github.com/ssbc/patchwork to use it.
- https://medium.freecodecamp.com/the-time-i-had-to-crack-my-own-reddit-password-a6077c0a13b4 Funny story about finding out a password based on a search engine.
- http://www.pscheidl.cz/javaee/java-ee-fatjars-docker/ Fatjars, docker, and Java EE apps
- https://github.com/thoughtbot/laptop A shell script which turns your macOS laptop into an awesome web development machine.
- https://github.com/scala/bug/ Scala bugs were imported from Jira into Github !

# 06-04-2017

- Back from holidays!
- https://github.com/brendangregg/perf-tools
- https://www.youtube.com/playlist?list=PL055Epbe6d5ZsQVJRV2FQQvsgDt0Ci5Zy Strata + Hadoop World 2017 videos
- https://www.slideshare.net/benstopford/the-power-of-the-log Nice slides about the immutable append-only logs strategy, and its sequential access, with optimisation to know where to read
- https://github.com/luanfujun/deep-photo-styletransfer Georgeous Deep Photo Style Transfers

# 24-03-2017

- http://angularjs.blogspot.be/2017/03/angular-400-now-available.html Angular 4 is here!
- https://github.com/lagom/lagom/pull/618/files/522fda54f10a1d952be9464e23880892c448163c Tons of fresh docs for Lagom
- https://npf.io/2017/03/3.5yrs-500k-lines-of-go/ A recap of a guy that worked a lot with Go.
- http://fabiensanglard.net/Compile_Like_Its_1992/index.php Compiling Wolfenstein 3D in DoxBox using Borland C++, yikes.
- https://gsuiteupdates.googleblog.com/2017/03/updates-in-g-suite-to-streamline-hangouts-and-gmail.html Bye Google Talk. I even forgot you existed actually.
- https://stackoverflow.com/insights/survey/2017/ The famous StackOverflow yearly survey about developers

# 21-03-2017

- https://eng.uber.com/hoodie/ Parquet + Avro regular recompaction to parquet to keep the best usage of Parquet and simplify the data flow, love it. https://uber.github.io/hoodie/
- https://github.com/jiaweihli/git-workflow-strategies-example Made me realize I'm always advocating rebase over merge, but actually, the best is both :), but with --no-ff!
- http://www.edumobile.org/linux/best-15-unix-command-line-tools/ I learned some tools! ncdu, apropos
- http://vertx.io/blog/scala-is-here/ Vert.x has now a Scala API for every modules, that's great news! One more Scala Reactive Framework.
- https://lwn.net/SubscriberLink/717076/4c3593aa4cad8e66/ time_t (int, 32bits) will fail in 2038.

# 20-03-2017

- https://github.com/akarnokd/jmh-compare-gui Compare JMH results in an UI
- https://www.youtube.com/watch?v=LhGq4HlozV4 The Eff Monad in Scala. DI at its best.
- http://akarnokd.blogspot.fr/2016/12/the-reactive-scrabble-benchmarks.html Comparaison of Reactive Streams frameworks (Rx*, Akka Streams, Reactor..)
- http://akarnokd.blogspot.fr/2017/03/java-9-flow-api-asynchronous-integer.html Using Java 9 Flow API to create a async integer range source. Not that straightforward.

# 19-03-2017

- https://whatwebcando.today/ An overview of the device integration HTML5 APIs. Very good stuff to be up to date.
- http://manishearth.github.io/blog/2017/03/05/understanding-git-filter-branch/ More about git filter-branch command
- http://programtalk.com/java/java-9-new-features/ Another recap about Java9 features. Modules, reactive API, collections, jshell, better Process: ProcessHandler, HTTP/2 client (incubator), Stack-walking API. Local-var type inference in Java 10 only.
- https://www.lucidchart.com/techblog/2017/02/22/upgrading-play-framework-2-3-play-2-5/ Very nice feedback about migrating apps from Play 2.3 to Play 2.5. I've been there but it was more simpler.
- https://github.com/adamw/macwire Dependency Injection at compile time in Scala. Next project, I'll use it!
- https://www.cockroachlabs.com/blog/living-without-atomic-clocks/ CockroachDB serializability explanations, vs Google Spanner linearizability using TrueTime.

# 18-03-2017

- http://mfglabs.github.io/akka-stream-extensions/ Some extensions to Akka Streams dealing with PostgreSQL, elasticsearch, AWS, Shapeless.
- https://research.googleblog.com/2017/03/announcing-guetzli-new-open-source-jpeg.html Guetzli, the new open source jpeg encoder from Google. https://github.com/google/guetzli
- https://erikbern.com/2017/03/15/the-eigenvector-of-why-we-moved-from-language-x-to-language-y.html Studying Google results to know from which language we are moving to which one, in general. Interesting :)
- https://erikbern.com/2017/03/15/the-eigenvector-of-why-we-moved-from-language-x-to-language-y.html
- https://www.linkedin.com/pulse/2-years-scala-microservices-galera-ansible-jason-paige 2 years doing Scala, making a small review about it: it rocks but it can get messy.
- https://lkml.wtf/ A weekly roundup of Linux Kernel Mailing List threads but with a lot more sarcasm. Some are really great, thanks Linus.
- https://blog.discordapp.com/how-discord-indexes-billions-of-messages-e3d5e9be866f Nice details given by the discord team about their infra (elastic, redis, cassandra) and how they handled the search part.
- https://bold.co/public/why-y-combinator-made-all-the-zvgxjl A very interesting story of a company growing up with Y-Combinator
- https://arstechnica.com/security/2017/03/hack-that-escapes-vm-by-exploiting-edge-browser-fetches-105000-at-pwn2own/ Exploit: From a website, to Edge, to Windows in a VM, to the host system. Wow!
- https://www.youtube.com/watch?v=1EGk2rvZe8A Throw a missile to the person who broke the Jenkins' build :)

# 15-03-2017

- https://backchannel.com/google-fiber-was-doomed-from-the-start-a5cdfacdd7f2 No more Google Fiber, because bad ROI. Go Wireless.
- https://1vwjbxf1wko0yhnr.wordpress.com/2015/08/10/overclocking-tools-for-nvidia-gpus-suck-i-made-my-own/ Reverse engineering overclocking tools to make his own, nice.
- https://medium.com/@robaboukhalil/a-tale-of-two-clouds-amazon-vs-google-4f2520516a38 AWS vs GCP. GCP wins.
- http://ithare.com/tcp-peculiarities-as-applied-to-games-part-ii/ Nice explanations over TCP options
- https://github.com/bugvm/bugvm Compiles JVM bytecode to native machine code, really
- http://www.nurkiewicz.com/2014/11/executorservice-10-tips-and-tricks.html Some tips about ExecutorService in Java
- http://www.rspective.com/blog/hunting-network-errors Funny story. Looking deeply into the network just to find the "bug" is due to a random generator in the code.
- https://www.youtube.com/watch?v=O_2J6dPSHSo Akka Streams live demo, parsing files and inserting them in Cass'

# 14-03-2017

- https://github.com/ParallelSSH/parallel-ssh Asynchronous parallel SSH client library in Python
- https://github.com/akumuli/Akumuli Another time-series database, no preconfigured rollup.
- https://traefik.io/ HTTP reverse proxy and locad balancer to use with microservices, hm!
- https://github.com/nodejs/node/issues/11835 node --install !?!?
- http://blog.samaltman.com/keep-the-internet-open net neutrality in danger?
- https://githubengineering.com/a-formal-spec-for-github-markdown/ the Spec of the GitHub flavored Markdown
- https://www.graph.cool/ PaaS to create a GraphQL backend quickly with a proper interface to create and edit the schemas
- https://lists.gnu.org/archive/html/emacs-devel/2017-03/msg00222.html one person is responsible for 10% of the 18500 Emacs bug reports
- https://github.com/bcicen/ctop A "top" cli for containers. Very cool stuff, better than docker ps eh.
- https://www.scala-lang.org/blog/2017/03/14/scala-native-0.1-is-here.html Exciting time for Scala :-)
- https://paragonie.com/blog/2017/03/jwt-json-web-tokens-is-bad-standard-that-everyone-should-avoid tldr: jwt is not secured, do not use it.

# 13-03-2017

- https://ponyfoo.com/articles/observables-coming-to-ecmascript: rxjs is already enough, a lib can move faster than a browser impl; but js will reinvent a broken wheel again
- http://pandoc.org/ This tool can convert any markup file to another markup format. markdown, reST, HTML, LaTeX, ...
- https://github.com/donnemartin/data-science-ipython-notebooks#scikit-learn A lot of interesting notebooks dealing with classic problems to solve. Very interesting for datascientists!
- http://www.javaworld.com/article/3172570/java-language/oracle-preps-developers-for-java-9-upgrade.html Java9 is coming!!!
- http://docs.oracle.com/javase/9/migrate/toc.htm So much cleanup and things removed in Java9, impressive.
- https://medium.com/@thejameskyle/react-loadable-2674c59de178 react-loadable, a very nice library to load asynchronously components https://github.com/thejameskyle/react-loadable

# 12-03-2017

- https://blog.codinghorror.com/password-rules-are-bullshit/ Rules about passwords. Good to bookmark for reuse
- http://www.eurogamer.net/articles/2017-03-10-inside-the-most-evil-rollercoaster-tycoon-park-ever-created  A crazy dude how made a astoning maze in RCT to see how guests are doing https://imgur.com/gallery/rgJmW 
- https://github.com/tuan3w/visual_search That's definitely interesting/ Elasticsearch + tensorflow to have a Google Image's like, where you search from a picture and a confidence ratio.
- https://www.youtube.com/watch?v=uOxEvqNLWuA Some tips about IntelliJ IDEA features
- https://neilonsoftware.com/2017/03/10/my-response-to-how-to-never-complete-anything/ "standing instructions to my wife is that if the office door is closed, only open it if the house is on fire and you have reason to believe I would not survive it. This is what I know I need to get things done."

# 09-03-2017

- https://www.reddit.com/r/scala/comments/5y6sjo/microservices/ If you're starting with microservices in Scala
- https://github.com/rtimush/sbt-updates Display SBT project's dependency updates.
- https://github.com/japgolly/scalajs-react ReactJS with Scala.js. I should definitely try that, instead of outputing some raw html in my server ahah.
- https://wikileaks.org/ciav7p1/cms/page_1179773.html "CIA Hacking Tools Revealed" "Git Tips & Tricks"
- https://www.linux.com/blog/stageless-deployment-pipelines-how-containers-change-way-we-build-and-test-software This story about staging servers is so true. codefresh.io
- https://pagghiu.github.io/dev/A-Node-Like-Api-for-C++-en/ A company writing a nodejs API in C++ for platform support reasons, controled perfs, low level.
- https://medium.com/@marin_m/how-i-found-a-5-000-google-maps-xss-by-fiddling-with-protobuf-963ee0d9caff An interesting bug found on Google Maps in JS, based on their Protobuf serialization that let us make some XSS.
- https://github.com/donnemartin/system-design-primer 4k stars! Lots of details about designing large scale systems.
- https://www.confluent.io/blog/log-compaction-highlights-apache-kafka-stream-processing-community-march-2017/ Confluent is a great company moving on quickly on their platform, nice
- https://data-artisans.com/drivetribe-cqrs-apache-flink/ Interesting reading about Kafka+Flink and CQRS, and blue/green architecture

# 07-03-2017

- https://blog.risingstack.com/writing-a-javascript-framework-the-benefits-of-custom-elements/ Should we care about custom elements? (web components)
- https://github.com/reddit/reddit The code that powers reddit.
- https://medium.com/hacking-and-gonzo/how-reddit-ranking-algorithms-work-ef111e33d0d9 Some interesting explanations around reddit's ranking algorithm
- https://portworx.com/lcfs-speed-up-docker-commit/ A nice performant storage driver system for Docker, built specifically for containers
- https://medium.com/@lhartikk/a-blockchain-in-200-lines-of-code-963cc1cc0e54 A blockchain in 200 lines of code in JS
- https://harishnarayanan.org/writing/artistic-style-transfer/ It's always impressive to see that: style transfer with a photo and a painting. Deep learning, convolutional neural networks, 
- https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A I stumbled upon this dude w-who creates a lot of content about TensorFlow, will definitely watch them someday!
- https://github.com/tensorflow/tensorflow I think I need to get into all this excitation.
- http://reedbeta.com/blog/programmers-intro-to-unicode/ Unicode is so unique. Nice dataviz of the unicode planes.
- http://www.michaelpollmeier.com/ A nice blog about Scala and Akka mostly &lt;3
- http://stackoverflow.com/questions/3912303/boolean-hashcode TIL the hashCode of Boolean: 1231 and 1237.
- https://github.com/couchbaselabs/dcp-documentation Couchbase maintains some nice documentation about DCP
- https://github.com/hseeberger/akka-sse Ahh, I love Akka and SSE to make quick stuff.

# 03-03-2017

- https://www.confluent.io/blog/confluent-3-2-apache-kafka-0-10-2-now-available/ Aggregate events into sessions based on periods of inactivity, a killer feature. Its KIP https://cwiki.apache.org/confluence/display/KAFKA/KIP-94+Session+Windows
- https://advancedweb.hu/2017/03/01/jvm_optimistic_optimizations/ JVM and JIT! Resume: small methods for better inlining. No megamorphism.
- https://medium.com/the-node-js-collection/a-brief-history-of-node-streams-pt-1-3401db451f21 .pipe nodejs streams
- https://shipilev.net/jvm-anatomy-park/1/ Interesting debugging/testing of the "lock coarsening and loops", to see how the JVM deals with it. 
- https://aws.amazon.com/message/41926/ Summary of the Amazon S3 Service Disruption in the Northern Virginia (US-EAST-1) Region. It all started with an human.
- https://www.stev.org/post/shootingyourselfintheheadwiththreads Threads are bad, use Actors! _unrelated_
- http://blog.codepipes.com/hosted-ci-comparison/hosted-ci-comparison.html That's an awesome complete CI products comparaison page. Thanks.
- https://www.manning.com/books/java-testing-with-spock Hm, I should take a look at Spock, it seems way better than JUnit for Java projects. 
- http://kompose.io/ Convert/run Docker Compose ymls to Kubernetes
- https://cambridgespark.com/content/tutorials/interactively-analyse-100GB-of-JSON-data-with-Spark/index.html Analyse 100GB of JSON data with Spark with Amazon EMR and Zeppelin

# 01-03-2017

- https://hacks.mozilla.org/2017/02/using-neutrino-for-modern-javascript-development/ This Neutrino tool seems useful to start quickly and focus on the app, instead of the config.
- https://medium.com/dev-channel/progressive-web-app-libraries-in-production-b52cad37d34 Yes, service workers we know, GA offline, sw-cache, and Autotrack for more analytics client-side.
- https://hacks.mozilla.org/category/a-cartoon-intro-to-webassembly/ Nice cartoons into about WebAssembly
- https://youtrack.jetbrains.com/issue/SCL-11406 Scala in Intellij in one-click, need votes!
- http://www.scala-lang.org/blog/2017/02/28/collections-rework.html So much work on Scala 2.13 new collections API
- https://github.com/scalacenter/scastie Got my access to scastie! A scala playground
- https://cwiki.apache.org/confluence/display/KAFKA/KIP-129%3A+Streams+Exactly-Once+Semantics Some explanations about the new mode "exactly_once" in Kafka Streams.
- https://code.visualstudio.com/updates/v1_10 Update of Visual Studio Code; Nothing huge but a lot of visual improvements and options.
- https://blog.ycombinator.com/dilution/ Some tips about seed round and Series A/B, when dealing with investors
- https://github.com/cs01/gdbgui/ A sublime UI for gdb, impressive
- https://blog.cloudflare.com/quantifying-the-impact-of-cloudbleed Cloudflare very transparent about Cloudbleed.  
- https://making.pusher.com/redis-pubsub-under-the-hood/ Some nice explanations about the pubsub system in Redis, with reference to the original commit in redis, interesting!
- http://lemire.me/blog/2017/02/28/how-many-floating-point-numbers-are-in-the-interval-01/ "How many floating-point numbers are in the interval [0,1]?" or taking a close look at IEEE754 :)

# 26-02-2017

- https://plus.google.com/+LinusTorvalds/posts/7tp2gYWQugL Linux about git and SHA1.
- https://github.com/git/git/blob/master/Documentation/RelNotes/2.12.0.txt Git 2.12 release notes
- http://www.2ality.com/2017/02/babel-preset-env.html babel-preset-env: configure the necessary polyfill needed for a targeted browser
- http://blog.felipe.rs/2017/02/25/id-software-programming-principles/ Never break the build, kiss, don't dev a full feature framework at first, ship the game code.
- http://brianknapp.me/software-engineer-best-skill/ "As a software engineer, what's the best skill set to have for the next 5-10 years?" I know, I know! Continuous learning.
- https://github.com/scalameta/scalameta/blob/master/changelog/1.6.0.md Scala.meta 1.6.0 release! New typelevel family of dialects
- https://bugs.chromium.org/p/project-zero/issues/detail?id=1139 "Cloudflare Reverse Proxies are Dumping Uninitialized Memory"
- https://jmnarloch.wordpress.com/2016/07/06/spring-boot-hystrix-and-threadlocals/ Hystrix and ThreadLocals (an HystrixCommand is run inside its own thread pool, so..)
- http://thehackernews.com/2017/02/cross-browser-tracking.html Nothing new, fingerprinting using only OS and graphite card (cross browser therefore) https://github.com/Song-Li/cross_browser

# 23-02-2017

- https://getintodevops.com/blog/how-the-hell-do-i-exit-a-beginners-guide-to-vim vim classic shortcuts
- http://www.zdnet.com/article/google-and-mozillas-message-to-av-and-security-firms-stop-trashing-https/ That's nuts. Remove your antivirus, it does more harm than good because they intercept https and resend crappy certs
- https://medium.com/underdog-io-engineering/create-a-build-system-for-your-react-app-in-5-minutes-or-less-91c501a30b1d ReactJS, Webpack and Babel in 5minutes
- http://www.nature.com/news/these-seven-alien-worlds-could-help-explain-how-planets-form-1.21512 7 not-far-away-Earth-sized planets 
- https://security.googleblog.com/2017/02/announcing-first-sha1-collision.html SHA1 collision on demand \o/

# 21-02-2017

- http://codegolf.stackexchange.com/questions/110485/leak-memory-in-as-few-bytes-as-possible Title says all!
- https://blog.poki.com/from-monolith-to-microservices-b16bae1d6c9d Monolith to microservices. Kubernetes, AWS, Scaling, Orchestrability, gRPC, 
- https://medium.freecodecamp.com/bill-gates-and-elon-musk-just-warned-us-about-the-one-thing-politicians-are-too-scared-to-talk-8db9815fd398 "45% of all US jobs could be automated away within the next 20 years"
- https://contributors.scala-lang.org/t/introducing-scastie-an-interactive-playground-for-scala/494 "Scastie - An interactive playground for Scala" by the Scala Center team!
- https://posativ.org/isso/ An alternative to disqus, using markdown yumyum
- https://zneak.github.io/fcd/2017/02/19/divisions.html Explaning a assembly CLANG code of a simple "a/19". That does not use "div" but only right shift and mul, ah!
- http://callingbullshit.org/syllabus.html#Spotting Bullshit.

# 19-02-2017

- https://yokota.blog/2017/02/17/dont-settle-for-eventual-consistency/ Basically AP databases are as available as CP databases in general, but are more complex to handle; so go with CP.
- http://ablagoev.github.io/linux/adventures/commands/2017/02/19/adventures-in-usr-bin.html So many unknown tools in /usr/bin thanks!
- https://www.wired.com/2017/02/spanner-google-database-harnessed-time-now-open-everyone/ Spanner, spanner, spanner! Need to POC it.
- https://gamedevelopment.tutsplus.com/tutorials/a-beginners-guide-to-coding-graphics-shaders--cms-23313 A Beginner's Guide to Coding Graphics Shaders. A shader can only returns (r,g,b,a).
- https://code.facebook.com/posts/1692857177682119/machine-learning-scale-2017-recap/ Videos of Machine Learning @Scala Facebook conf.
- https://github.com/oci-pronghorn/GreenLightning An über fast http server in Java?  
- https://www.susanjfowler.com/blog/2017/2/19/reflecting-on-one-very-strange-year-at-uber Uber's image is a bit tarnished after reading that. Women in tech they said.

# 18-02-2017

- https://v8project.blogspot.fr/2017/02/high-performance-es2015-and-beyond.html Nice post about V8 project working hard to improve its ES6 perf compared to ES5.
- https://gist.github.com/aleksey-bykov/1273f4982c317c92d532 Another nice git cheat sheet
- https://medium.com/airbnb-engineering/superset-scaling-data-access-and-visual-insights-at-airbnb-3ce3e9b88a7f Nice update to Superset, the SQL Lab.
- http://engineering.skybettingandgaming.com/2017/01/23/streaming-architectures/ Streaming? Decided to use kafka streams, kafka connect, and akka streams for non-kafka channels.
- https://github.com/streamsets/datacollector Streamsets, A UI to design big data "streaming" interface and run them (lots of connectors).
- https://github.com/SirCmpwn/evilpass A so good idea. A password strength tester that checks your email/pwd combinaison on popular websites to prevent password reuse!

# 16-02-2017

- https://lorenzoongithub.github.io/nudge4j/ A snippet to expose a HTTP endpoint to evaluate javascript in your java program
- https://github.com/MinhasKamal/CreepyCodeCollection Weird snippets that does awesome things, in C, Java, Ruby.
- https://github.com/twitter/ospriet A bot made by Twitter to make a given account centralizes questions posted by ppl (for a talk or a conf)
- https://github.com/Ahnfelt/react4s Scala.js + React.js
- https://github.com/Song-Li/cross_browser cross-browser fingerprint
- https://github.com/pshihn/rough I like this lib, wondering why it doesn't have more star (maybe an demo drawing app would have been nice). Create hand-drawn shapes in javascript, on a canvas.
- https://www.reddit.com/r/programming/comments/5ue632/the_myth_of_using_scala_as_a_better_java/ omg, the comments about this scala snippet https://github.com/m50d/tierney/blob/master/free/src/main/scala/tierney/free/package.scala about recursion scheme and free monads. It's a bit.. complicated.
- https://jaxenter.com/ibm-bans-remote-work-131612.html "Remote work treated as the root of all evil at Yahoo and Reddit"
- http://www.theregister.co.uk/2017/02/15/think_different_shut_up_and_work_harder_says_linus_torvalds/ Shut up and work.

# 14-02-2017

- https://www.ctheu.com/2017/02/14/all-the-things-we-can-do-with-jmx/ It is out! All the things we can do with JMX.
- https://github.com/tuhdo/os01 Another interesting repo to write an OS from scratch! With a book and all.
- https://www.worldpressphoto.org/collection/photo/2017 Many, many beautiful photos from the world events..
- https://cloudplatform.googleblog.com/2017/02/introducing-Cloud-Spanner-a-global-database-service-for-mission-critical-applications.html Cloud Spanner is out. ACID, CP, SQL, scaling.
- http://htmlreference.io/ A better HTML reference than w3schools :D
- http://aakinshin.net/en/blog/dotnet/mono-and-65535interfaces/ Go find this bug, tests failed because more than 65536 interfaces were created (mono)
- http://degoes.net/articles/destroy-all-ifs Pass lambdas instead of writing ifs+booleans
- https://semaphoreci.com/community/tutorials/testing-topologies-in-kafka-streams Testing Kafka Streams with "Mocked Streams" https://github.com/jpzk/mockedstreams

# 13-02-2017

- https://dzone.com/articles/is-software-development-really-a-dead-end-job-afte "Is Software Development Really a Dead-End Job After 35-40?" Stupid coding tests, again.
- http://www.economist.com/news/science-and-technology/21716891-nasty-chemicals-abound-what-was-thought-untouched-environment-worlds When you think a zone on earth is pristine, it's totally the contrary that happens..
- https://github.com/yavorsky/auto-github-topics A nice extension to set github tags from package.json tags directly
- https://gist.github.com/scottfrazer/094a0f1d048cc3b8deeac4cf29266f62 "Go vs. Scala (Akka) Concurrency" but actually the writer mixes Akka and Scala (like jquery and js), and seems to not know well Scala so it leads to wrong statements. But at least, I learned about Go stuff.
- https://github.com/lampepfl/dotty/issues/1970 "enum" keyword propal in Dotty. More powerful than the Java "enum", can be used to define G/ADTs.
- http://metrics20.org/ A standard for timeseries metrics?

# 12-02-2017

- http://udidahan.com/2009/12/09/clarified-cqrs/ Long post about CQRS and how it works, how to handle it, with tons of interesting comments.
- https://www.nytimes.com/interactive/2017/02/11/obituaries/smullyan-logic-puzzles.html Logic Puzzles time! By a great mathematician how past away a few days ago, Raymod M. Smullyan.
- https://olivierpieters.be/blog/2017/02/11/designing-a-business-card-in-latex Need a business Card? Here is a nice LaTeX one.
- https://twitter.com/djspiewak/status/830561958252466176 Don't use Scala's mutable.Map.
- http://www.hydrogen18.com/blog/finding-content-in-html.html Some heuristic to retrieve the useful content of any webpage
- http://bigocheatsheet.com/ Stumbled upon this again, need to print it!
- https://webkit.org/blog/7122/introducing-riptide-webkits-retreating-wavefront-concurrent-garbage-collector/ Description of the new GC "Riptide" in Webkit. Quite long article.
- https://aboullaite.me/docker-hacks/ A nice bunch of Docker CLI tips
- https://github.com/JonasCz/How-To-Prevent-Scraping A very interesting list of things to do to prevent website scraping


# 09-02-2017

- https://twitter.com/gitlabstatus/status/829680989538492416 GitLab suffering of another issue: Redis split brain this week!
- https://nmatpt.com/blog/2017/02/09/scala-2.12-future-transform/ Future.transform is smarter in Scala 2.12
- https://blog.thingsboard.io/2017/02/load-testing-of-mqtt-servers-using-java.html Gatling &lt;3
- http://www.snappydata.io/blog/joining-billion-rows-faster-than-apache-spark This SnappyData thing seems interesting. Will definitely test it on a real job. https://github.com/SnappyDataInc/snappydata/blob/master/docs/quickstart.md
- https://www.ckl.io/blog/reactivex-and-async-programming/ Another Rx happy user
- https://read.acloud.guru/5-things-i-learned-in-2-years-as-a-backend-developer-d55fe913fc81

# 08-02-2017

- https://danluu.com/web-bloat/ Most of the web really sucks if you have a slow connection
- https://kilianvalkhof.com/2011/javascript/annoying-js-how-to-be-an-asshole/ A nice JS lib with tons of annoying JS functions to provoke a bad UX.
- http://david.li/paint/ Ok that's totally awesome. We can paint on a canvas really "realistically", impressive.
- https://blogs.msdn.microsoft.com/oldnewthing/20170208-00/?p=95395 I never noticed that "all Windows drivers dated June 21, 2006". There is a reason: priority with manufacturer-provided driver.
- https://code.visualstudio.com/blogs/2017/02/08/syntax-highlighting-optimizations Visual Studio Code explaining the syntax hightlightning and its latest optimizations, good stuff.
- https://www.reddit.com/r/programming/comments/5st3dy/all_of_twitters_mobile_web_traffic_thats_like_a/ Twitter's dropping some Scala in favor of nodejs (supposely). Debate!
- https://blog.jcoglan.com/2013/11/15/why-github-is-not-your-cv/ Clearly, most of us don't work with OSS..
- https://www.lightbend.com/company/news/lightbend-closes-second-acquisition-in-9-months-buys-opsclarity-for-most-advanced-monitoring-in-modern-distributed-application-stack Lightbend acquires OpsClarity for a better and complete stack monitoring
- https://philipwalton.com/articles/the-google-analytics-setup-i-use-on-every-site-i-build/ Superb and useful article on how to use Google Analytics for developers.
- http://finagle.github.io/blog/2017/02/06/finagle-loves-netty4/ Finagle and Netty4
- https://github.com/typelevel/scala/blob/typelevel-readme/notes/2.12.1.md Scala 2.12.1 update. Nice addons about implicits, kind-polymorphism, match exhaustivity, trailing commas!

# 07-02-2017

- https://rethinkdb.com/blog/rethinkdb-joins-linux-foundation/ RethinkDB has reborn
- https://techcrunch.com/2017/02/06/google-fixes-a-big-problem-with-amp-now-lets-you-view-and-share-publishers-own-links/ Google AMP and the sharing link issue
- https://myopsblog.wordpress.com/2017/02/06/why-databases-is-not-for-containers/ Databases and Docker containers.
- http://flink.apache.org/news/2017/02/06/release-1.2.0.html Tons of improvements and fixes in Flink 1.2.0
- http://techblog.netflix.com/2017/02/introducing-hubcommander.html A new Slack bot to manage github repos by Netflix &lt;3 https://github.com/Netflix/hubcommander
- https://reflets.info/le-gendarme-et-les-darquenettes/ Le Dark Web dans Internet :)
- https://medium.com/@pschanely/computed-state-the-model-view-problem-9cbe8cf8486f A general thinking about model<->view sync
- https://blog.risingstack.com/concurrency-and-parallelism-understanding-i-o/ For once, this one was more interesting than stupid JS tricks.
- https://jepsen.io/analyses/mongodb-3-4-0-rc3 Jepsen test and MongoDB 3.4.0rc3
- http://carlmartensen.com/immutability-made-easy-in-java-9 Finally, a non-verbose syntax to create immutable set/list. Unfortunately, they still have .put .add etc. that throws an exception. Stupid (from the interface).

# 05-02-2017

- http://www.theregister.co.uk/2017/01/16/google_reveals_its_servers_all_contain_custom_security_silicon/ Small bits of info about how Google handle servers security
- https://research.googleblog.com/2017/02/using-machine-learning-to-predict.html Google trying to predict parking difficulties
- http://www.popularmechanics.com/science/health/a3093/the-science-of-bruce-lees-one-inch-punch-16814527/ The one-inch punch of Bruce Lee explained. Wow.
- https://zeit.co/blog/github Deploying a github repo with now directly
- http://www.linusakesson.net/programming/tty/ What is and How TTY works on Unix.
- http://nothings.org/games/minesweeper/ Minesweeper strategies and probabilities :)
- http://blog.ploeh.dk/2017/02/02/dependency-rejection/ DI sucks, cause side-effects, causes impure-ness, is not functional. Defer IO the maximum. Use IO monad.
- https://kelvinpompey.me/tempted-to-abandon-react-native-for-native-android/ Abandoning React Native for native because of poor debug and optimization tools.
- https://ian.pw/posts/2017-02-04-lock-striping-in-scala.html A lock strategy in Scala based on a bucketed list of locks.
- http://www.slate.com/articles/technology/webhead/2004/11/nullsoft_19972004.html The story of nullsoft (winamp) creator at AOL.
- https://anders.com/blockchain/ Video about how blockchain works. Very informative.
- https://medium.com/airbnb-engineering/streamalert-real-time-data-analysis-and-alerting-e8619e3e5043 New tool by airbnb: StreamAlert. RT alerts at scale.

# 02-02-2017

- http://www.lesnumeriques.com/casque-realite-virtuelle/oculus-condamne-a-verser-500-millions-dollars-a-editeur-zenimax-n60093.html $500M from Oculus to Zenimax :(
- https://github.com/Powerspace/akka-streams-utils Some open source from us
- https://medium.com/@francoisvasnier/popchef-comment-livrer-1-plat-toutes-les-5-secondes-ae85959498cd Un post transparent sur la manière dont la logistique de Popchef (livraison plats préparés)
- https://www.youtube.com/watch?v=e1VEEtAvQ9E Very good talk from Netflix about their Kafka infra in the Cloud. They have fronts Kafka which data are sent to another Kafka clusters for consumation by anyone. (the front kafka being critical, noone can consume from them). And he explains the failover strategy (start a new kafka cluster and dynamically switch the endpoint of the producer!)
- https://commitprint.com/ Print a poster of your git contribs Oo
- http://blog.2ndquadrant.com/dataloss-at-gitlab/ The response of a postgresql main committer to GitLab issues.

# 01-02-2017

- http://www.lesnumeriques.com/vie-du-net/google-marque-mieux-valorisee-monde-n60063.html Apple's "brand value" decreasing a lot. Google just in front.
- https://docs.google.com/document/d/1GCK53YDcBWQveod9kfzW-VCxIABGiryG7_z_6jHdVik/pub "... decides to remove the directory. After a second or two he notices he ran it on db1.cluster.gitlab.com, instead of db2.cluster.gitlab.com". "it’s too late. Of around 310 GB only about 4.5 GB is left ".
- http://howfuckedismydatabase.com/ Are you using PostgreSQL, MySQL, MSSQL, Oracle, SQLite, MS Access, or NoSQL? FUCKED.
- https://github.com/ro31337/libretaxi LibreTaxi, a free and open source Uber/Lyft Oo 
- http://blog.samaltman.com/time-to-take-a-stand A call to tech community to take a public stance against Trump
- https://github.com/bahmutov/game-of-github The game of life in the github's contributions table. What an idea!
- https://facebook.github.io/watchman/ Oh, Facebook built a file watching service.
- https://ponyfoo.com/articles/setting-up-angular-2-development-environment A nice tuto about the ng cli and misc things to create an angular app.
- https://www.infoq.com/news/2017/01/java9-rampdown-phase-start Java 9 incoming! In July. No HTTP/2 standard client for now.
- https://blog.risingstack.com/cqrs-explained-node-js-at-scale/ Small article about what is CQRS.
- https://dump.01alchemist.com/2016/12/31/future-webhpc-parallel-programming-with-javascript-the-new-era-about-to-begin/ SharedArrayBuffer to be used with webworkers and avoid data copy. That's a big step. And TurboScript "Super charged JavaScript for parallel programming and WebAssembly" https://github.com/01alchemist/TurboScript
- http://thecodebarbarian.com/a-nodejs-perspective-on-mongodb-34-decimal.html 128bits decimals to avoid IEEE754 crap.
- https://github.com/GoogleChrome/preload-webpack-plugin Automatically add preload or prefetch link with webpack and its html plugin.

# 31-01-2017

- https://www.ctheu.com/2017/01/29/how-to-communicate-between-micro-services-part-3-circuit-breakers/ Did a big job on this, with the Hystrix part!
- https://techcrunch.com/2017/01/31/google-open-sources-chrome-for-ios/ Chrome is now full Blink on all platform.
- https://github.com/bevacqua/sixflix Nice code by Netflix to detect if the browser supports es6 mostly
- https://github.com/david-gpu/deep-makeover Deep learning project to transform male portraits into female and vice versa, would love to see that :D unfortunately, the model is not included..
- http://making.duolingo.com/rewriting-duolingos-engine-in-scala Scala won over Python. Not too hard eh.
- https://softwaremill.com/bring-some-color-to-scala-compiler/ Colors in scala output, nice. addSbtPlugin("com.softwaremill.clippy" % "plugin-sbt" % "0.5.0")
- https://index.scala-lang.org/search?scalaVersions=2.12&q=&page=1 Scala 2.12 compat' is slowly growing
- https://github.com/nrinaudo/kantan.csv Another parse CSV lib in Scala.
- https://playingscala.wordpress.com/2017/01/29/scala-value-classes/ Value classes yes. Was not aware of the "universal trait" name. (only def, not initilization: but creates an alloc, contrary to extension methods;
- https://github.com/miguno/akka-mock-scheduler Mocking the akka scheduler to test things
- https://alexn.org/blog/2017/01/16/iterator.html Iterator in Scala (from Java) causes side-effects, code duplication, and fat interface.

# 28-01-2017

- https://tech.small-improvements.com/2017/01/25/how-to-migrate-an-angularjs-1-app-to-react/ Migrating an angular 1 app to ReactJS.
- https://arxiv.org/pdf/1701.02405v1.pdf Super interesting study about Twitter "Star Wars bots". 350k!
- https://github.com/dmnd/dedent Strip front spaces in multi-line strings, very useful
- https://github.com/salesforce-ux/portion-control "Badge to quickly communicate project values" 
- https://github.com/outr/scribe another logging infra based on Scala macros. Compat with scalajs.
- http://adnanahmed.info/blog/2017/01/28/elasticsearch-search-as-you-type/ Very good explanation how to setup an autocomplete search with elasticsearch
- http://highscalability.com/blog/2016/10/12/lessons-learned-from-scaling-uber-to-2000-engineers-1000-ser.html Microservices allows you to scale (people) up easier and faster. Multiple languages. Hard to share code sometimes. RPC conventions? logging conventions? Who has the big picture?
- http://zipkin.io/ distributed tracing system by Twitter. Looks good! Integration with cassandra, mysql (storage), akka, dropwizard (http) and multiple languages (java, js) much more
- https://underscore.io/blog/posts/2017/01/24/finch-functional-web-development.html Good recap and some code about Finch, functional http framework by Twitter

# 26-01-2017

- https://gopherize.me/ An avatar generator (golang mascot)
- https://github.com/dustinvtran/ml-videos A repo with nice ML videos, for the day I want to get more into it!
- https://security.googleblog.com/2017/01/the-foundation-of-more-secure-web.html HTTPS's becoming the fundamental techno to connect to Google's services. "Google Trust Services" https://pki.goog/
- https://github.com/wtsxDev/Amazing-Java-List A crazy good list about Java frameworks, love it
- https://community.risingstack.com/the-worlds-fastest-javascript-memoization-library/ the fastest JS memoization. oddly relying on JSON.stringify
- https://www.kinto-storage.org/ Mozilla did a parse and firebase equivalent, Kinto, good to know.
- http://staltz.com/what-happens-when-you-block-internet-giants.html Blocking Google and Facebook from your /etc/hosts, using Tor, refusing cookies. Aah.
- https://github.com/StevenBlack/hosts/ So many hosts to block!
- http://martin.kleppmann.com/2017/01/26/data-loss-in-large-clusters.html The bigger cluster (talking >1000 nodes), the highest probably of losing 3x replicated data. Higher partitions rate help (1000 partitions per node = small partitions = distributed all over the nodes that can rebuild a replica quickly)
- https://www.confluent.io/kafka-summit-2016-keynote-kafka-and-uber-the-worlds-realtime-transit-infrastructure/ Interesting and short talk about how Uber is using Kafka and evolving its architecture

# 25-01-2017

- https://github.com/Powerspace/kudu-from-avro Updated our tool to create Kudu table from avro or sql scripts
- https://www.reddit.com/r/javascript/comments/5pxxi1/does_anyone_use_sencha_anymore/ Ah, Sencha! I remember. It's been a while.
- http://blog.strml.net/2017/01/chrome-56-now-aggressively-throttles.html Chrome 56 Will Aggressively Throttle Background Tabs - it will affect many websites.
- https://github.com/facebook/react/issues/8854 Next versions of React will cleanup the old APIs and optimize the bundle size
- https://github.com/skidding/illustrated-algorithms Algorithm illustrations for children
- https://github.com/fluxcapacitor/pipeline End-to-End, Continuous Spark ML + Tensorflow AI Data Pipelines. They teach a bunch of nice tools. Spark, Zeppelin, Tensorflow. Hystrix. Kafka. Flink. Cassandra, ES... and particularly into the ML.
- https://github.com/Microsoft/TypeScript/issues/1213 Higher-kind type in Typescript proposal \<3
- https://danielmiessler.com/blog/google-amp-not-good-thing/ Because the app is hosted on Google's servers (centralization)
- https://blog.google/products/google-voice/ringing-2017-updates-our-google-voice-apps/ Never used "Google Voice" hm!
- https://github.com/mohebifar/konsul Funny things we can do in the console with this
- https://movio.co/blog/migrate-Scala-to-Go/ Another team migrated from Scala to Go. I think I should really take a look at Go. But not fan of the syntax :( But like the no JVM !!
- https://www.confluent.io/blog/confluent-delivers-upgrades-clients-kafka-streams-brokers-apache-kafka-0-10-1-1/ Kafka brokers, streams, clients improvements!
- https://e.xtendo.org/monad#89 Why Monad make people scared of Haskell. Understanding the Monad concept is not even necessary.

# 23-01-2017

- https://github.com/roytenberg/brilliant-bash/blob/master/.bashrc I like the "plz" alias to sudo the last cmd
- https://github.com/davisonio/awesome-gif everything about gifs is in there
- http://ivanjov.com/working-with-http-streams-with-cycle-js/ been a while i didn't look at a cycle tuto, love it.
- http://www.slideshare.net/Lightbend/lessons-learned-from-paypal-implementing-backpressure-with-akka-streams-and-kafka A high performance crawler using Akka Streams and Kafka. The blog post here: https://www.lightbend.com/blog/lessons-learned-from-paypal-implementing-back-pressure-with-akka-streams-and-kafka
- https://github.com/paypal/squbs Akka/Spray for Large-Scale Production Deployments.

# 22-01-2017

- https://www.ctheu.com/2017/01/18/how-to-communicate-between-micro-services-part-1/ Wrote this the past few days :)
- https://www.ctheu.com/2017/01/22/how-to-communicate-between-micro-services-part-2-retryers/ And this!
- https://blog.twitter.com/2017/the-infrastructure-behind-twitter-scalepop Lots of technicals things about Twitter infra: network optims, DCs traffic, storage, cache, puppet at scale, cleaning codebase, monitoring
- https://github.com/rthor/cra-generate Generate components from the CLI, based on templates
- https://amethyste16.wordpress.com/2013/08/05/les-modeles-anemiques/ An amenic model: when you code something about an entity outside of it (like in a service), wrong pattern.
- https://www.expeditedssl.com/aws-in-plain-english The true name of AWS services
- https://github.com/ericelliott/speculation Another JS promise cancellation way. Simpler?
- http://lemire.me/blog/2017/01/20/how-quickly-can-you-remove-spaces-from-a-string/ The uglier the syntax the faster, using SIMD intructions.
- https://fossbytes.com/googles-ai-codes-own-machine-learning-software/ AI coding ML

# 18-01-2017

- https://github.com/mozilla/Fira I didn't know Fira was some Mozilla. Nice font.
- https://firebase.googleblog.com/2017/01/FabricJoinsGoogle17.html Google acquires Fabric (build mobile apps, from Twitter)
- https://github.com/dragos/dragos-vscode-scala Scala in VSCode, using Ensime
- https://anvaka.github.io/common-words/#?lang=scala common words used in code base, per language!
- http://vmokshagroup.com/blog/gatling-gun-is-now-a-prospecting-tool-for-testers/ Yes Gatling is very good.
- https://slackhq.com/threaded-messaging-comes-to-slack-417ffba054bd This going to be great! Threads in Slack, finally.
- https://perlmaven.com/the-default-variable-of-perl TIL about the implicit "$\_" variable in PERL. I can't stand this language for some reasons.
- https://emmanuelbernard.com/presentations/inverted-index/ A presentation about Inverted Index (b-tree, TF/IDF, Lucene)
- http://mutanatum.com/posts/2017-01-12-Browser-FP-Head-to-Head.html JavaScript vs Elm vs PureScript vs GHCjs. Comparing their functional aspects, pros and cons.
- http://www.defstartup.org/2017/01/18/why-rethinkdb-failed.html Cofounder of RethinkDB give details about why RethinkDB failed unfortunately. The company focused on wrong metrics and try to work on too many things at once.

# 17-01-2017

- http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf Any fellow datascientists should love this! Approved.
- https://blog.appcanary.com/2017/http-security-headers.html
- http://pantsbuild.github.io/ Heard this name before but never used it. A build system mainly for repo with multiple projects in it. Multiple languages supported.
- https://support.google.com/youtube/answer/7277005?hl=en "background-color: yellow". This is Youtube Super Chat.
- https://blog.appcanary.com/2017/http-security-headers.html Another detailed recap about HTTP security headers.
- https://medium.com/webpack/webpack-2-2-the-final-release-76c3d43bf144 Webpack 2 almooost the default.
- http://rea.tech/business-friendly-functional-programming-part-1-asynchronous-operations/ Didn't get the whole thing, but it's similar to the "async" Scala library except it's using scalaz behind the scene.
- https://github.com/legomushroom/mojs Very good animation library in Javascript
- https://blog.risingstack.com/node-js-async-best-practices-avoiding-callback-hell-node-js-at-scale/ async lib, co, and async/await keywords

# 16-01-2017

- https://jeena.net/why-i-switchedfrom-osx-to-linux Switching from OSX to Linux, some tips and comparaison
- https://youexec.com/dev/2017/1/14/google-facebook-ads-traffic-is-useless Comparing user session with Fullstory, users from Ads do nothing and leave quickly.
- https://www.ckl.io/blog/dont-blame-the-framework-angularjs-and-reactjs/ React deals with the view, Angular with the whole. That's it.
- https://hackernoon.com/how-i-built-a-super-fast-uber-clone-for-mobile-web-863680d2100f Nice tips about how to improve an application speed using Lightroom as kpi. (code splitting, ssr, compression, caching, preload)
- http://ithare.com/packet-loss-for-an-app-level-developer-part-i-router-failures-bgp-convergence-time-aqm-traffic-shapers/ Why we are losing packets and how traffic failures are handled
- https://github.com/google/guava/wiki/Release21 Guava 21 requires Java 8 now, nice!
- http://www.sohamkamani.com/blog/2017/01/16/web-security-essentials/ Web Security for newcomers
- https://www.reddit.com/r/scala/comments/5oc93x/scala_code_refactoring/ An interesting ask for refactoring tips and some nice pointers
- https://github.com/wartremover/wartremover Because we want to write the best Scala code, we can apply this linter and pray to have less than hundred fixes.
- https://victorops.com/blog/akka-heart-ammonite/ Using Ammonite shell to connect to distant Akka actors and alter them
- https://blog.codecentric.de/en/2017/01/hello-grpc-scalapb/ gRPC in Scala
- https://alexn.org/assets/pdfs/Akka-Monix.pdf 2 good presentations in one: Akka, and Monix

# 15-01-2017

- https://byrslf.co/the-man-who-gave-us-all-the-things-e83ab612ce5c The emotional story of Levi Felix, co-founder of Camp Grounded, spending his life as he wanted, with friends all around, helping others.
- http://campgrounded.org/ the concept: several days between adults, with tons of activities. To disconnect and reconnect.
- https://medium.freecodecamp.com/what-i-learned-from-analyzing-the-top-253-medium-stories-of-2016-9f5f1d0a2d1c How To Succeed With Medium: personal titles, talk about motivation, add images, 7min length.
- https://medium.com/@WebReflection/a-case-for-js-classes-without-classes-9e60b3b5992 Another "class" framework in JS, because ES6 classes transpilation does not always work.
- http://eta-lang.org Haskell-ish on the JVM. Pure, Lazy, Strongly Typed, interop.
- https://microsoft.github.io/windows/ Windows is on the good way to go. Those are its projects Github powered.

# 14-01-2017

- https://gist.github.com/mandubian/dfd670f7740f47a1a2a7b662f828aac6 ""Monad is a monoid in the category of endofunctors" evidence using trivial sample of Scala Kind-Polymorphism PoC" except all the greek characters, yes, it makes sense.
- http://seriouslyjs.org/ quite awesome. change the video style in real-time. using webgl.
- https://github.com/alibaba/rax another serious competitor of React has emerged :)
- https://github.com/palmerhq/backpack a kind of create-react-app for nodejs backend apps
- http://www.vanityfair.com/news/2017/01/a-hacker-just-proved-that-apple-may-have-been-right-about-the-fbi so they cracked the iphone and somebody cracked them to know how to. Smart.
- https://cwiki.apache.org/confluence/display/KAFKA/KIP-66%3A+Single+Message+Transforms+for+Kafka+Connect Kafka Connect has now the ability to have lightweight "serializer" (map, filter) à la flume.
- https://1-minute-modem.branchable.com/ What happen on the website when you have a 56k modem
- http://meta.stackoverflow.com/questions/340960/a-post-mortem-on-the-recent-developer-story-information-leak SO leaked phone number and emails by putting them in the HTML source.
- http://www.thepublicdiscourse.com/2017/01/18093/ A law professor getting an traffic ticket he shouldn't have get goes to trial.
- http://mattwarren.org/2017/01/13/Analysing-Pause-times-in-the-.NET-GC/ Some knowledges about .NET GC. Finishing by using unsafe off-heap for no GC.
- https://alexn.org/blog/2017/01/13/traversable.html Traversable (.foreach) in Scala is the dual of Iterable. (.iterator => { .hasNext, .next }), and has no way to signal completion of failure (like Observer)
- https://medium.freecodecamp.com/the-mind-blowing-ai-announcement-from-google-that-you-probably-missed-2ffd31334805 A dude too much excited about the new Google Translate (cf comments), but good stuff anyway!
- https://reflect.io/blog/github-aws-data-pipeline/ How Reflect use AWS to make their backend.
- https://yahooeng.tumblr.com/post/155765242061/open-sourcing-screwdriver-yahoos-continuous ScrewDriver, a tool with UI by Yahoo! to to Continous Delivery http://screwdriver.cd/
- https://www.oreilly.com/ideas/scaling-scala The place and evolution of Scala + its big projects, and Cats VS ScalaZ

# 11-01-2017

- https://github.com/jlongster/prettier Another prettify JS, seems better? to avoid inconsistent formatting. and its blog http://jlongster.com/A-Prettier-Formatter
- https://vimeo.com/85490944 This is an amazing video by Spotify about their culture. Just awesome and a must-watch.
- https://medium.com/@mweststrate/mobx-3-released-unpeeling-the-onion-ca877382f443 MobX is getting its API cleaner and smarter
- https://medium.com/swlh/lets-talk-about-self-driving-cars-387cd5adb834 So many questions when it comes to cars automation. I like this quote "Everything that moves will go autonomous".
- https://blog.oz-code.com/analyzing-github-linq-usage-the-results/ It's always nice to see how a framework is used by analyzing Github projects. Here LINQ, no surprising results.
- https://openai.com/blog/GTA-V-plus-Universe/ Training real AI agents using GTA V !
- https://github.com/sindresorhus/get-range A lazy (yield) range iterator useable with "for of"
- https://github.com/pathikrit/better-files Never heard of this library. It's strongly recommanded when dealing with Files in Scala. The API seems excellent and complete.
- http://v8project.blogspot.fr/2017/01/speeding-up-v8-regular-expressions.html RegExp += Speedup(100%)

# 09-01-2017

- https://techcrunch.com/2017/01/09/atlassian-acquires-trello/ $425M for Trello. The price of the user-base!
- http://sciabarra.com/book/starters/ Very quick start in diff Scala framework
- https://www.reddit.com/r/scala/comments/5mtlhq/stds_considered_harmful_or_slicks_marvelous_api/ A dude pissed off at Slick's ugly syntax.
- https://blog.redelastic.com/work-stealing-what-makes-the-play-framework-fast-4b71fa7758d5 Some basic explanation about work stealing threading with Play!
- http://www.dmst.aueb.gr/dds/sw/dgsh/ I heard good things about this dgsh but having a hard time to be interested.
- http://www.jowanza.com/post/155606607974/what-is-alluxio-and-will-it-help-my-spark-jobs A very quick post about Alluxio and Spark. Very quick.

# 08-01-2017

- https://medium.com/@subhojit20_27731/apache-spark-and-amazon-s3-gotchas-and-best-practices-a767242f3d98 Spark and S3. Many tips to know.
- https://www.mapr.com/blog/monitoring-real-time-uber-data-using-spark-machine-learning-streaming-and-kafka-api-part-2 Spark, Kafka, K-means, Uber.
- https://engineering.linkedin.com/blog/2017/01/asynchronous-processing-and-multithreading-in-apache-samza--part Samza refactored its internals and implemented the callback hell to support any type of Promise/Future/Task to follow a full async model.
- https://hackernoon.com/why-dataproc-googles-managed-hadoop-and-spark-offering-is-a-game-changer-9f0ed183fda3 DataProc seems awesome to handle Spark jobs on "hot" clusters (created on the fly).
- https://news.ycombinator.com/item?id=13259575 25k servers every day on GCP.
- https://thehftguy.com/2016/06/15/gce-vs-aws-in-2016-why-you-should-never-use-amazon/ GCE vs AWS in 2016: Why you shouldn’t use Amazon 
- https://thehftguy.com/2016/10/20/building-an-analytics-pipeline-in-2016-the-ultimate-guide/  Building an Analytics Pipeline in 2016. Alooma, RedShift, Looker.

# 07-01-2017

- https://www.bleepingcomputer.com/news/security/ultrasound-tracking-could-be-used-to-deanonymize-tor-users/
- https://blog.plan99.net/the-science-of-westworld-ec624585e47
- https://twitter.com/i/moments/817537697535250432 The CES was not so great it seems, a bunch of stupid things.
- https://elementary.io/ A viable alternative to OSes: ElementyOS. Very simple but does the job well it seems. (based on Ubuntu)
- http://www.vidarholen.net/contents/blog/?p=479 dd is a file reader/file writer, deal with it. It should have been called "cc" but taken so was named "dd". An X comes from "Window". W+1. Mind blow.
- http://www.cgl.uwaterloo.ca/smann/IceCream/humor.html A story to read. "Car allergic to vanilla ice cream"
- https://medium.com/@david.gilbertson/master-web-development-with-these-9-985-weird-tricks-77c71d1d96f3 A checklist of all the features CSS/HTML/JS/DOM features, 10k features.
- http://www.bbc.com/future/story/20170101-a-new-tomb-for-the-most-dangerous-disaster-site-in-the-world Impressive project realized across decades.
- https://media.ccc.de/v/33c3-8022-memory_deduplication_the_curse_that_keeps_on_giving Abuses of memory deduplication (used in VMs context)
- http://blog.orange.tw/2017/01/bug-bounty-github-enterprise-sql-injection.html?m=1 Explanation about a bounty bug (SQL Injection) in GitHub Enterprise VM (ie: Ruby sucks). Good reading.
- http://www.vox.com/science-and-health/2017/1/6/14184094/scientists-predict-stars-colliding Come back in 2022.
- http://arstechnica.co.uk/security/2017/01/more-than-10000-online-databases-taken-hostage-by-ransomware-attackers/ Good thing. They removed all the unsecured mongod from the Internet, ahah.

# 05-01-2017

- https://labs.spotify.com/2016/03/03/spotifys-event-delivery-the-road-to-the-cloud-part-ii/ PubSub, 2M/s on one DC, validated.
- https://www.confluent.io/blog/log-compaction-highlights-apache-kafka-stream-processing-community-january-2017/
- https://spark.apache.org/releases/spark-release-2-1-0.html A small recap of the new things
- http://flink.apache.org/news/2016/12/19/2016-year-in-review.html Flink's git commits yearly review!
- http://dimafeng.com/2017/01/04/sbt/ SBT making things complex for no reason. whereas Gradle is easier.
- https://spring.io/blog/2017/01/04/spring-batch-4-0-0-m1-is-now-available More builder patterns, less XML in the doc (java first, finally!!)
- https://www.kennethreitz.org/essays/the-reality-of-developer-burnout Interesting and short story about dev burnout. 

# 04-01-2017

- https://github.com/stevennL/Snake AI of snake game, fill the screen!
- http://www.nature.com/news/google-reveals-secret-test-of-ai-bot-to-beat-top-go-players-1.21253 Google put AlphaGo into the online tournament of Go and beat'em all
- https://www.youtube.com/watch?v=LBJPIgNXUDI Let artist draw into an infinite space using VR. Quite impressive.
- https://blog.medium.com/renewing-mediums-focus-98f374a960be Medium is firing 1/3 of its people. It will try to "define a new model for writers and creators to be rewarded, based on the value they’re creating for people"
- https://github.com/cDima/Aerial Apple TV's screensavers on Windows, awesomely great. And the other repo for macs: https://github.com/JohnCoates/Aerial. I put both :)
- https://philna.sh/blog/2017/01/04/git-back-to-the-future/ Never had to use the reflog yet, never did any mistake.. yet.
- https://kev.inburke.com/kevin/leap-seconds/ Another story about leap second in Go
- https://franklinpearsall.com/getting-started-with-akka-and-akka-http-building-a-mock-traffic-monitoring-system/ An example of Akka HTTP app

# 03-01-2017

- http://www.madhur.co.in/blog/2016/12/25/batch-api-framework-nodejs.html Batch API calls in nodejs.
- http://www.rankred.com/whats-new-in-html-5-1-added-features/ Some nice HTML5 features not everybody is aware of
- https://probablydance.com/2016/12/27/i-wrote-a-faster-sorting-algorithm/ The Radix Sort. A globally faster algo than QuickSort/Heapsort and concors, that surprisingly "nobody" uses.
- https://github.com/scala/collection-strawman The redesign of the Scala collections has begun
- https://www.youtube.com/watch?v=lTDGWaiczV0 Nice FR video about the developer competence, and why IT is becoming a commodity, as electricity.
- https://www.infoq.com/articles/java9-osgi-future-modularity Java Platform Module System (JPMS); a simpler concept than OSGi. OSGi was originally built (16yo) for IoT (highly constrained). Jigsaw provides the impl of the JPMS in Java9.
- http://iteratrlearning.com/java/2016/12/26/pipes-and-filters-actors-akka-java.html Sorry, but Akka in Java.. Moreover, an actor to encapsulate a one-liner. One should use functional programming?
- https://github.com/scalikejdbc/scalikejdbc A tidy SQL-based DB access library for Scala developers. Async version over there https://github.com/scalikejdbc/scalikejdbc-async
- http://ahogrammer.com/2016/11/15/deep-learning-enables-you-to-hide-screen-when-your-boss-is-approaching/ Title says all, awesome and funny article
- http://co.ntextu.al/ simple and typesafe interpolated strings, checked at compile-time, in Scala

# 02-01-2017

- https://googleblog.blogspot.fr/2011/09/time-technology-and-leaping-seconds.html Instead of the :60s, Google changes its ntp servers to send progressively tiny updates (delta) to match the time after the leap second transparently. "leap smear"
- https://github.com/bluejamesbond/FlameChart.js a &lt;FrameChart&gt; as powerful as the DevTools' one
- http://www.lefigaro.fr/secteur/high-tech/2017/01/02/32001-20170102ARTFIG00110-pour-lutter-contre-le-piratage-des-emails-donald-trump-preconise-le-retour-au-courrier.php Stop sending emails, send mails !
- https://blog.cloudflare.com/how-and-why-the-leap-second-affected-cloudflare-dns/ tldr: never store a timestamp into a signed integer.
- http://www.jowanza.com/post/155264974829/the-how-and-why-of-spark-and-couchbase Some intro to spark and couchbase combined together.
- https://fail0verflow.com/blog/2016/console-hacking-2016-postscript/ Porting Linux on PS4
- https://github.com/zeit/release another semver github release tool. straghtforward, does the job.
- http://www.spacex.com/news/2016/09/01/anomaly-updates SpaceX, transparent about the loss of the rocket launched on 1-sep. "one of the three composite overwrapped pressure vessels (COPVs) inside the second stage liquid oxygen (LOX) tank failed."
- https://blog.xinhong.me/post/sublime-text-vs-vscode-vs-atom-performance-dec-2016/ we can't compare Atom and VSCode to Sublime perfs :)
- http://docs.datastax.com/en/archived/cassandra/2.0/cassandra/architecture/architectureIntro_c.html good and clear into to Cassandra's parts
- https://github.com/jakearchibald/navigation-transitions Proposal to add some transition API between pages in a tab.
- https://www.hakkalabs.co/articles/how-cassandra-stores-data More general info about Cassandra
- https://www.stephanboyer.com/post/122/does-google-execute-javascript YES!
- http://blog.xebia.fr/2017/01/02/dotjs-2016-notre-compte-rendu/ Rien de bien transcendent à priori, généraliste.
- https://dzone.com/articles/introduction-apache-cassandras Another intro to Cassandra
- https://media-glass.es/portainer-the-ui-for-docker-d067f6335f23 a UI for Docker engine
- https://pavelfatin.com/typing-with-pleasure/ Measuring delay between a keystroke and its appearance, under mult. conditions.  Atom, Idea, subl, emacs, etc.
- https://hackernoon.com/the-programmers-guide-to-booking-a-plane-11e37d610045 Scrape and plot your airplane tickets price to get the lowest price, great

# 31-12-2016

- http://www.journaldugeek.com/2016/12/30/twitter-aimerait-autoriser-ledition-de-tweets-mais-cest-vraiment-complique/ Twitter listening to its users
- http://www.lesnumeriques.com/appli-logiciel/microsoft-windows-10-p21948/windows-10-mode-dedie-jeu-a-compter-debut-2017-n58773.html "Gamer mode" in Windows10?
- https://hackernoon.com/im-sticking-with-react-for-now-47b792be555d Preact and other "adapters" have still some issues. React has a tremendous inertia recruiting top developers. Hard to beat.
- https://github.com/google/eslint-config-google I knew Airbnb style, here is the Google style.
- https://github.com/jxnblk/cxs Really like the different format of generic css classnames
- http://danielearwicker.github.io/MobX_Like_React_but_for_Data.html Funny to see it's talking about KnockoutJS, an old framework (I used it!) with observable-ish. MobX is just barely the same idea.
- http://www.thymeleaf.org/doc/articles/fromhtmltohtmlviahtml.html A recap of HTML history. XHTML5 exists!
- https://github.com/tidwall/tile38 A specialized geolocation datastore. Following REdisSerializationProtocol.
- https://github.com/ageitgey/show-facebook-computer-vision-tags#show-facebook-computer-vision-tags-chrome-extension Display tags Facebook identified on its picture (put on alt)
- https://blog.knoldus.com/2016/12/30/migration-from-spark-1-x-to-spark-2-x/ quickstart to update a spark1.6 program to 2.0
- https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536 basis of functional programming, a quite verbose guide.

# 29-12-2016

- http://www.xautoworld.com/tesla/autopilot-radar-tech-predicted-accident/ Impressive usage of predictive technology by Tesla
- https://github.com/arun-gupta/docker-images Useful repo of images to start misc things (couchbase, jdk, some dbs..)
- https://www.hidefsoftware.co.uk/2016/12/25/the-caching-antipattern/ Talking about cache strategies.
- http://gafferongames.com/networking-for-game-programmers/udp-vs-tcp/ TIL TCP and UDP should not be used together. TCP will "damage" UDP transit.
- https://databricks.com/blog/2016/12/29/introducing-apache-spark-2-1.html A better streaming, a better SparkSQL.

# 28-12-2016

- http://joebergeron.io/posts/post_two.html a bootloader in ~hundred simple instruction (asm eh)
- https://github.com/andywer/leakage Memory leak testing for nodejs, that's another good chunk of tests to do
- https://blog.knoldus.com/2016/12/27/testing-rejection-handling-in-akka-http/ Learned about route.seal() to test a route that throws, in akka http
- https://ponyfoo.com/articles/var-let-const Don't need to read why const is better.
- https://medium.com/@anicolaspp/akka-streams-a-story-of-scalability-5d9e7c2d3ac3 Using Akka PubSub +Cluster instead of Akka Streams for big jobs.
- http://mrcoles.com/demo/markdown-css/ CSS to make HTML markup look like plain-text markdown. Then you can copy paste it inside a .md. Oo
- http://www.lihaoyi.com/post/ImplicitDesignPatternsinScala.html Scala's implicits more powerful than you think. Good explanations and examples.
- http://blog.threatstack.com/ramping-up-on-finch-avoiding-common-gotchas I'm surprisingly not attracted by Finch.
- https://medium.com/@octskyward/modern-garbage-collection-911ef4f8bd8e Some explanation about different GCs behaviors. "Garbage collection is a hard problem".
- http://djcordhose.github.io/flow-vs-typescript/flow-typescript-2.html Flow just seems more appropriate. (incremental, better checks)
- https://www.confluent.io/blog/data-dichotomy-rethinking-the-way-we-treat-data-and-services/ Stateful Stream Processing

# 27-12-2016

- https://github.com/mobxjs/mobx/blob/mobx3/CHANGELOG.md#300 Some nice API churn in MobX and better pattern (immutability)
- https://github.com/start-runner/start A very simple Gulp (task runner). Tons of plugins for cross-env.
- https://github.com/dhparkdh/resume-for-web-developer a nice cv template to modify as we want
- https://github.com/mishudark/dropbox-password "Securely stores your passwords as Dropbox do" a function in Go to hash a password as we should. AES256+pepper+bcrypt+salt+sha512
- https://logs.now.sh/ Funny experience "à la now" where you can register to any output of a running nodejs process with just a string (a secret string)
- https://www.reddit.com/r/scala/comments/5kk9bc/my_problems_with_akka/ Interesting question to ask difference between futures and akka. Basically: Akka if you want states and failure management.
- http://slick.lightbend.com/doc/3.1.0/database.html#database-thread-pool the thread pool for async actions needs for be properly tune
- https://www.amazon.com/gp/product/0133846830?sa-no-redirect=1&pldnSite=1 "Reactive Messaging Patterns with the Actor Model: Applications and Integration in Scala and Akka" what about buying this book? (Vaughn Vernon inside)
- https://medium.com/@shahinism/for-gods-sake-secure-your-mongo-redis-etc-4f310cf1bed2 Reminder that mongo and redis are not secured at all by default
- https://ponyfoo.com/articles/terrible-code-sane-people A post with a tons of good advices that can help to do some introspection. "When a measure becomes a target, it ceases to be a good measure. - Goodhart’s law" "it takes a lot of self-control to focus on delivered quality and ignore juicy metrics such as commit rate or issues closed."
- https://www.entrepreneur.com/article/285444 Google will index page thinking mobile-first. A very interesting choice. Better quality website for everyone?
- https://medium.com/@areai51/the-4-stages-of-perf-tuning-for-your-angular2-app-922ce5c1b294 Not only Angular2: Tree shaking (remove useless things from bundle), "universal" js (ssr, careful, not always the best solution), web workers (leave UI thread alone), and service workers (instant loading, offline, cache)
- https://cloudncode.wordpress.com/2016/07/22/msa-getting-started/ Don't do nano services. Group by feature. Service Discovery. Document APIs. Circuit-breaker. Communication between services: HTTP/Queues. Authentication, Authorization. Scaling. If not many calls: AWS Lambda (serverless).
- https://www.openapis.org/ ~> Swagger https://github.com/OAI/OpenAPI-Specification 

# 25-12-2016

- https://swizec.com/blog/animating-svg-nodes-react-preact-inferno-vue/swizec/7311 the new "perf" demo compared between react, preact, inferno, angular, cyclejs
- https://en.lichess.org/blog/WFvLpiQAACMA8e9D/learn-from-your-mistakes
- http://www.thevelop.nl/blog/2016-12-25/ThreadTone/ Cool idea. An image converted to "threads" in a circle.
- https://medium.com/the-mission/this-10-minute-routine-will-increase-your-clarity-and-creativity-7ce61b11c2f9 "Your subconscious never rests and is always on duty because it controls your heartbeat, blood circulation, and digestion." When you realize this, we are amazing. Write down the things you’re trying to accomplish before going to sleep. You'll have answer on the morning.
- https://hackernoon.com/10-things-i-learned-making-the-fastest-site-in-the-world-18a0e1cdf4a7 Lots of tips for a better time to first meaningful paint, tti, libraries sizes..
- http://www.scala-sbt.org/0.13/docs/Cached-Resolution.html lots of modules, sbt starts to suck. Cache dag to fix it.
- https://m.signalvnoise.com/why-you-should-argue-with-your-employees-ab8189fcd1c4 "It’s not about ego — it’s about the outcome. You want the outcome that’s best for the company"

# 22-12-2016

- https://github.com/Swizec/react-fractals React doesn't like when every element moves (no sCU optim)
- http://www.cakesolutions.net/teamblogs/improving-workflow-with-local-sbt-files create a custom global sbt that is not commited with the projects
- https://gist.github.com/non/ec48b0a7343db8291b92 "Static typing is most useful in large, shared codebases" "a scientist's main concerns are probably mathematical errors (most of which the type system won't catch)... unlikely to maintain code for very long periods of time or share codebases."
- http://www.re-cycledair.com/0-to-1-million-scaling-my-side-project-to-1-million-requests-a-day mongodb -> compose.io. classic file storage -> s3. 3 nodejs in front of 2 nginx (1M queries per day, one nodejs would be enough :D)
- https://www.smashingmagazine.com/2016/12/gpu-animation-doing-it-right/ classic reminder: animate opacity and transform only (another composite layer). And more tips.
- https://blog.superhuman.com/architecting-a-web-app-to-just-work-offline-part-1-8697f316c0eb offline app: local queue -> async backend save. handle connection status.
- https://aerotwist.com/blog/when-everything-is-important-nothing-is/ SSR=higher Time To Interactive. C(client)SR=opposite of SSR. "Progressive Booting" >> SSR or CSR. Critical first. Do not forget about requestIdleCallback.
- https://www.reddit.com/r/linusrants/ A reddit for that, not surprising.
- http://x-team.com/2016/12/forc-fear-of-removing-css/ FORC: fear or removing CSS. Definitely true when in decoupled .css files.
 
# 20-12-2016

- http://www.nytimes.com/2016/12/20/technology/twitters-chief-technology-officer-to-leave-company.html COO gone, CTO gone.
- https://jenkins.io/projects/blueocean/ brb installing awesomeness
- https://blog.cloudflare.com/a-very-webp-new-year-from-cloudflare/ "Polish". WebP for everyone. Replaces png, jpg, gif.
- https://www.youtube.com/watch?v=NpN9NzO4Mo8 Nobody wants to steal his phone. Until..
- http://stackoverflow.com/questions/4313139/how-to-use-scalas-this-typing-abstract-types-etc-to-implement-a-self-type this.type or type parameter / type member in Scala can be particularly helpful.
- https://github.com/devongovett/regexgen Can't wait to test this with a real regex. Enough charabia in the desc to make it very good.
- https://github.com/keonkim/awesome-bits a new way to obfuscate our code. Using binary operations all over.
- https://blogs.windows.com/msedgedev/2016/12/20/introducing-brotli-compression/ Brotli in Edge. Good. (20% better http compression)

# 19-12-2016

- http://amir.rachum.com/blog/2016/12/18/debugging-with-humility/ "I have a bug blabla because blabla" "May I take over your keyboard? I don't listen to you anyway" ahah, it always happening like that.
- http://blog.professorbeekums.com/2016/12/beware-of-developers-who-do-negative.html the conclusion says enough: "..the pressure of tight timelines, but hiring in desperation won’t solve that problem...Bad developers will not only slow you down..can cause your great developers to leave your company. "
- https://changelog.com/posts/one-sure-fire-way-to-improve-your-coding "If you want to dramatically increase your programming skills you need to be reading other people’s code." Personally, I read a lot of Druid's source code and learned a lot :)
- https://github.com/tc39/proposal-cancelable-promises Canceled! Seems like a smart decision.
- http://blog.dynamicdrive.com/detecting-adblock-on-your-site-and-logging-it-to-google-analytics/ Indeed, why not use GA to store that, good idea.
- http://www.jowanza.com/post/154680354949/a-gentle-intro-to-udafs-in-apache-spark Never wrote a UDAF (aggregate function, like a reduce) in Spark, good to know
- http://filippodeluca.com/programming/2016/12/09/akka-eventsourcing-done-right You persist the command and not the state after the command (business logic). Your logic changes: you lost the command to reprocess: command sourcing
- https://github.com/FezVrasta/popper.js I was wondering what is a "popper", now it makes sense.

# 17-12-2016

- http://www.dw.com/en/galileo-navigation-satellite-system-goes-live/a-36422029 Precision: 4m! A centimeters for commercial and gov.
- http://cube20.org/ Every position of Rubik's Cube can be solved in twenty moves or less. A cube has 43,252,003,274,489,856,000 positions. !!
- https://github.com/andrew/github-inbox A better github notifications manager. It's in ruby, sorry
- https://medium.com/@bhatt.shashwat/bye-2k16-and-bye-angular-ca627861839 Omg, been a while I didn't read something about the flux architecture. So 2015.
- https://github.com/lihaoyi/sourcecode get source code metadata in the code itself (implicits and macros at compile time)
- https://medium.com/webpack/webpack-performance-budgets-13d4880fbf6d The PR I was talking a few days ago is merged. Webpack have some options to warn us if the assets are too big.
- https://medium.com/dropbox-design/design-words-with-data-fe3c525994e7 Good tips about how to write. Use "Sign in". "Version History".

# 16-12-2016

- https://github.com/gatsbyjs/gatsby Spent a lot of time on this, I always wanted to remove my wordpress with this kind of static generator. I'll need a week I think, I'm updating/rewritting/reorganizaing all the articles one by one. Lots of work. :star:
- https://thefeedbackloop.xyz/stroustrups-rule-and-layering-over-time/ "For new features, people insist on LOUD explicit syntax. For established features, people want terse notation." Stroustrup's Rule.
- https://github.com/toddmotto/angular-pizza-creator 
- https://coryrylan.com/blog/angular-multiple-http-requests-with-rxjs "forkJoin" ok that's just "zip". I don't like when ppl names things differently. edit: actually it is not the same, AT ALL! 
- http://reactivex.io/documentation/operators/zip.html Expand the RxJs part. There is zip, zipArray, and forkJoin. forkJoin deals with the last element of each streams.
- https://medium.freecodecamp.com/why-i-studied-full-time-for-8-months-for-a-google-interview-cc662ce9bb13 
- https://grundlefleck.github.io/2013/06/23/using-scala-will-make-you-less-productive.html For me, it's compilation/dependencies resolution time -_-
- http://stackoverflow.com/questions/3490383/java-compile-speed-vs-scala-compile-speed/3612212#3612212 Scalac does mmuch more things because of the features of Scala. But it parses less code.. !
- http://tempsreel.nouvelobs.com/en-direct/a-chaud/31358-tele-russie-meurtre-cette-nouvelle-emission-realite-russe.html Russian are crazy too.

# 15-12-2016

- https://9to5mac.com/2016/12/14/twitter-excluded-from-trump-tech-meeting-over-emoji/ And that seems to be for real. This man is not living in the real world, or is it just me?
- https://medium.com/@garycoby/twitter-restricts-trump-eb7e48ccf5ff The complete story, and the emoji sample, ahah
- https://developer.github.com/changes/2016-12-14-profile-snyks-journey-from-cli-to-github/ it was just a CLI, now it's a bot to automatically PR a vulnerability fix
- https://en.wikipedia.org/wiki/Second-system_effect "the tendency of small, elegant, and successful systems to be plagued with feature creep due to inflated expectations" Nice to say that in a conv! "
- https://www.microsoft.com/en-us/diversity/training/default.aspx Original "course" about unconscious bias with nice short videos about a team working together. tldr: do your own introspection, always be open, shutdown your bias towards others. Appearance means nothing.
- http://v8project.blogspot.fr/2016/12/v8-nodejs.html debugger into v8 (for node to integrate with it), better perfs overall.
- https://github.com/MicheleBertoli/react-fix-it Simple but useful. It writes a sample test with the stacktrace along in the console (actually the useful part comes from react-component-errors)
- http://www.lemonde.fr/sciences/article/2016/12/15/des-souris-beneficient-d-une-cure-de-jouvence-transgenique_5049640_1650684.html in 50 years, we'll got it ! Hurry up.
- http://patrick.louys.ch/2016/12/11/open-closed-principle/ instead of A :> B :> C, it can be nice to work with Z[C] :> C (a composition with an inner list for instance)
- https://github.com/auchenberg/volkswagen 5k stars now :) (make the tests to always pass, remember?)
- https://jaxenter.com/whats-new-in-akka-130643.html Flow in Java9. Alpaka (Camel). Artery (Remote with Aeron). Akka typed.
- https://github.com/couchbaselabs/java-dcp-client I gave a try, it's quite nice. Use case: listen to expirations and send to a kafka topic.
- http://blog.couchbase.com/2016/october/pokemon-go-scaling-profile-services-with-couchbase--nosql Title says all
- https://blog.heroku.com/kafka-data-pipelines-frp-node an nodejs example of: Twitter stream -> Kafka -> Kafka Processing -> Dashboard (websockets).
- https://mrotaru.wordpress.com/2015/05/20/how-migratorydata-solved-the-c10m-problem-10-million-concurrent-connections-on-a-single-commodity-server/ Super interesting. How they tune the kernel to handle 10M connections.
- http://highscalability.com/blog/2016/12/13/a-scalable-alternative-to-restful-communication-mimicking-go.html in the same vain, but building a autocomplete service this time
- https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/ just good sense.

# 14-12-2016

- https://hackernoon.com/who-said-javascript-easy-f4a1d5b399b8 I like this kind of post, JS is messed up, we know it and we like it.
- https://gist.github.com/akras14/3d242d80af8388ebca60 a nice git cheat sheet. Hopefully, when you use it daily, you know the whole sheet.
- https://github.com/cloudson/gitql recap: git ql "select date, message, author from commits where date > '2016-10-10'
- http://blog.triplebyte.com/does-it-make-sense-for-programmers-to-move-to-the-bay-area yes. salaries >> upper cost.
- https://github.com/ccadllc/cedi-config i think i'll use that next time ! parse a typesafe config into a case class directly.
- http://staltz.com/libraries-shouldnt-support-everything.html monolith is the way
- https://blogs.msdn.microsoft.com/dotnet/2016/08/24/whats-new-in-csharp-7-0/ A simple form of pattern matching, tuple à la scala, deconstruction
- https://manu.ninja/functional-reactive-game-programming-rxjs-breakout An arkanoid with RxJS, nicely done
- https://techcrunch.com/2016/12/14/yahoo-discloses-hack-of-1-billion-accounts/ yahoo still in trouble..
- https://outwatch.github.io/ scalajs and observables, so good. I can't stop to think about the bundle size. 412KB for the HelloWorld. :/ Definitely needs some tree-shaking.
- https://egghead.io/courses/natural-language-processing-in-javascript-with-natural to quickly watch later
- http://reactivesocket.io/ another project that implements reactivestreams. javascript and java impl.
- https://blogs.msdn.microsoft.com/kaushal/2013/08/02/ssl-handshake-and-https-bindings-on-iis/ ssl hanshake low level details.
- https://softwaremill.com/reader-monad-constructor-dependency-injection-friend-or-foe/ monad reader impact when using it for DI

# 13-12-2016

- https://github.com/Tenchi2xh/Scurses It's always impressive to get this kind of dashboard with charts etc. in a console!
- https://toddmotto.com/building-tesla-range-calculator-angular-2-reactive-forms
- https://github.com/720kb/ndm neat! i don't remember seeing a interface for installed nodejs packages. now it exists!
- https://github.com/mathiasbynens/tpyo i think he did a tpyo. using es6 proxies.
- http://www.slideshare.net/SparkSummit/spark-summit-eu-talk-by-michael-nitschinger Spark and Couchbase, a love story
- https://www.joelonsoftware.com/ Bored? "Over the last 16 years I’ve written 1114 articles on this site about software development, management, business, and the Internet."

# 12-12-2016

- http://blog.cloudera.com/blog/2016/12/achieving-a-300-speedup-in-etl-with-spark/ comparing bash pipes to spark, right.
- https://github.com/zeit/hyper/releases/tag/1.0.0 I can finally install hyperterm on windows; wouhou. No more cmder?
- https://github.com/chtefi/how-to-make-a-good-website/blob/master/README.md Still more details!
- https://github.com/bestiejs/benchmark.js A benchmarking library. As used on jsPerf.com
- https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/locks/ReadWriteLock.html Some refreshment over the Java ReadWriteLock
- https://medium.com/@rajaraodv/the-inner-workings-of-virtual-dom-666ee7ad47cf How "virtual dom" works generally. Lots of diagrams, didn't read the whole thing, i don't need to know the implementation, just make IT FAST.
- http://techblog.netflix.com/2016/12/netflix-conductor-microservices.html a distributed airflow with a json dsl and explicits i/o. Reading the doc, I didn't find where we set the process to start itself. I think I missed something.
- https://marketplace.visualstudio.com/items?itemName=capaj.vscode-exports-autocomplete Auto-imports package in ES6 sources, awesome?
- http://survivejs.com/blog/inferno-interview/ some tips why/how inferno is so fast.
- http://degoes.net/articles/easy-monads talking about free monads using a ConsoleIO example, without saying it's about free monads in Scala, good article
- https://www.ideals.illinois.edu/bitstream/handle/2142/34816/fase2013_submission.pdf "Why Do Scala Developers Mix the Actor Model with Other Concurrency Models?"

# 11-12-2016

- https://www.washingtonpost.com/news/capital-weather-gang/wp/2016/12/09/the-polar-vortex-is-coming-heres-what-that-means-and-how-cold-it-could-get/ I didn't know the term "polar vortex". Just meaning it's going to get blazing cold.
- https://medium.com/@mbostock/command-line-cartography-part-2-c3a82c5c0f3 More cli manipulation to transform data to a map svg
- https://m.signalvnoise.com/how-to-have-an-honest-one-on-one-with-an-employee-24bbddeb0f47 Nice tips for interviewing employees about what could be better, what is wrong etc. ie: never ask "how is this going?" but more personal questions: "When have you felt frustrated/enthousiast in the past year?"
- http://getoptimage.com/ this tool optimizes image weight a lot without losing any quality. good for the web :)
- https://github.com/ImageOptim/ImageOptim his free friend (less performant it seems according to some comments)
- https://github.com/tpolecat/doobie Very interesting project, a functional JDBC layer in Scala. Uses scalaz or cats, shapeless..
- https://www.scalawilliam.com/essential-sbt/#print-all-bbc-news-headlines excellent short guide using only shell commands to demonstrate how to use sbt
- https://www.youtube.com/watch?v=ecekSCX3B4Q SF Scala: Martin Odersky, Scala -- the Simple Parts
- https://github.com/brettchalupa/developer-interview-questions the other side: what questions should a dev ask to the interviewer
- https://www.youtube.com/user/shiffman/videos Impressive dude doing so many programming videos in javascript
- https://github.com/jsoma/tabletop Google spreadsheets connector in javascript
- https://blog.sindresorhus.com/macos-tips-tricks-13046cf377f8 Some tips on OSX
- http://ternjs.net/ type analysis and inference in javascript. Integrates with all editors.
- https://github.com/plasma-umass/browsix a javascript kernel-like, written in typescript, using webworkers for "processes"
- http://blog.octo.com/en/scylladb-vs-cassandra-towards-a-new-myth/ Scylla VS Cassandra. Cassandra "wins", despite having a lesser throughput, but because it's more stable, steady, and its driver handle backpressure. BUT, this article is 1yo, so probably not true anymore.
- http://blog.octo.com/compte-rendu-du-spark-summit-2016/ Pour ceux qui n'ont pas pu aller au Spark Summit (moi, moi!), super intéressant, beaucoup de pointeurs.
- http://www.slideshare.net/SparkSummit/spark-summit-eu-talk-by-simon-whitear Sparklint, a very nice UI to analyze the load of a job
- http://spark.apache.org/docs/latest/structured-streaming-programming-guide.html Explanation of the programming model behind unbound Dataframe in Spark Streaming (window, join, sinks..)
- https://github.com/OpenHFT/Chronicle-Map key-value store off heap (mmapped file) in-process with replication over network (distributed, CRDT), UDP+TCP. Impressive scalability. No TTL. Commercial offer to more features.

# 10-12-2016

- https://en.wikipedia.org/wiki/Satisfiability_modulo_theories i dunno
- https://lists.freedesktop.org/archives/dri-devel/2016-December/126684.html amd pissed off by linux team that does not want to integrate their code. (iiuc)
- http://blog.octo.com/les-strategies-de-gestion-de-pression-partie-i/ some details about backpressure management
- https://github.com/miloszpp/scala-ts case classes to typescript!
- http://blog.octo.com/docker-en-production-la-bataille-sanglante-des-orchestrateurs-de-conteneurs/ Docker Swarm VS Kubernetes (03-2016). Kubernetes wins.
- http://www.slideshare.net/JoshBaer/shortening-the-feedback-loop-big-data-spain-external Spotify big data evolution -> from hadoop to google cloud
- http://blog.akka.io/artery/2016/12/05/aeron-in-artery Aeron (SBE) in Akka Artery (remote). Using UDP undernealth
- http://www.cakesolutions.net/teamblogs/genetic-programming-in-scala Nice and clean. Generate polynomial expressions and check their fitness to keep the best match.
- https://www.youtube.com/watch?v=S4ez739fles Rapidly Iterating on Microservices using Docker, Kubernetes, and Node.js

# 09-12-2016

- https://en.wikipedia.org/wiki/Jacque_Fresco Thanks to this guy, I discovered the "Venus Project". A model of a sustainable future society
- https://www.npmjs.com/package/egghead-downloader way more practical :-)
- https://bl.ocks.org/mbostock/8fe6fa6ed1fa976e5dd76cfa4d816fec d3 internals in a d3 chart ! d3ception
- https://medium.com/@dtinth/immutable-js-persistent-data-structures-and-structural-sharing-6d163fbd73d2 Immutability are using persistent data structure (such as trie), hopefully! The perf would be catastrophic otherwise
- https://zeit.co/oss clear page about the oss zeit does. very good projects (micro, next, hyper NO WINDOWZ BUILD)
- https://github.com/zeit/micro interesting. a wrapper to node http server. The straight minima to start a http server with async/await support. 
- https://javascript30.com/ "Build 30 things in 30 days with 30 tutorials" Nice! But I won't do it.
- https://pixelambacht.nl/2016/font-awesome-fixed/ technique to reduce font-awesome size. Pretty useless cause of cdn and browser cache actually, but good to know the techniques!
- https://peteris.rocks/blog/exotic-http-headers/ exotic http headers. Already in my repo, but had nice tips about them :) https://github.com/chtefi/how-to-make-a-good-website
- https://github.com/webpack/webpack/issues/3216 webpack will soon warn about "big" js bundle (>250KB). The web is going mobile 3G.
- https://istacee.wordpress.com/2013/09/18/kent-beck-i-get-paid-for-code-that-works-not-for-tests/ Kent Beck : “I get paid for code that works, not for tests” (he invented xp, tdd..)
- http://shivankaul.com/blog/2016/12/07/clean-your-desk-yet-another-amazon-interview-experience.html okay this amazon interview is definitely screwed up, impressive
- https://lukasa.co.uk/2016/12/Debugging_Your_Operating_System/ Another post about calloc in like 2 weeks?! An an unexpected behavior on osx, nicely done

# 08-12-2016

- https://github.com/petehunt/rust-benchmark Rust to JS or wasm.
- https://www.drift.com/ Another customer messaging in-browser solution
- http://blog.xebia.fr/2016/12/08/revue-de-presse-xebia-2016-50/ Scala 2.12, Amazon Go, Craftmanship: building a test infrastructure
- http://pedrorijo.com/blog/scala-enums/ Comparing Scala Enums and other ways to simulate them (because they suck a bit)

This was a late meetup day :-)

# 07-12-2016

- https://github.com/krausest/js-framework-benchmark wow, a lots of app doing the same thing but with a lot of existing frameworks (ie: benchmarking them)
- https://en.wikipedia.org/wiki/Kiritimati UTC+14:00 yikes. I'd like to go into holidays there, very peaceful. Just need a sat connection eheh.
- https://blog.docker.com/2016/12/docker-acquires-infinit/ Docker bought a startup from Paris to deal with the long-waited container storage solution
- https://www.youtube.com/watch?v=M1qm-AWWu-M "Netflix JavaScript Talks - Transpilers: Bridge to the Future" I like the "test for lying browser" that really rely on the browser js behavior. Basically, they will ship ES6 not converted to ES5 if not needed. Polyfill only when needed.
- http://launchaco.com/build/ generate a typical startup landing page, sublime
- https://cwiki.apache.org/confluence/display/MAVEN/POM+Model+Version+5.0.0 wow, POM files are going to evolve! Dawn of a new age.
- https://github.com/erikbern/git-of-theseus I applied that on my company's projects, that's amazing :)
- https://www.baldurbjarnason.com/notes/is-js-more-fragile/ "There’s no reason why a set of simple forms on a government website should be implemented in Angular when they could be implemented more reliably and with greater reach using built-in features of HTML and CSS" Because dev wants to be bleeding-edge (well, not with Angular :p), that's it. 
- https://babeljs.io/blog/2016/12/07/the-state-of-babel big recap of babel past, present and future. Note: a babel cli is a good idea
- http://www.scala-lang.org/blog/2016/12/07/implicit-function-types.html Scala is getting one more implicit feature to "simplify" things. Implicits type! A reusable type that "contains" an implicit parameter. Less visible implicits across the code.

# 06-12-2016

- http://jetbus.io/index.html collaborative apps using websockets, done easily with jet
- https://www.prerender.cloud/blog/2016/12/03/chrome-memory-54-vs-55 Chrome 55 uses ~30% less memory than Chrome 54
- https://www.amazon.com/b?node=16008589011 Love the principle, just amazing (woopsy unemployment incoming). Supermarket, no lines, no checkout. Computer vision (picture), deep learning, sensor fusion (fused several sensors data to analyze).
- http://www.ericponto.com/blog/2016/12/05/teaching-rxjs/ knowing the subject, i think it's very clearly explained to begin with, good stuff
- https://www.confluent.io/blog/log-compaction-highlights-in-the-apache-kafka-and-stream-processing-community-december-2016/ Lots of good KIP. Newer client will be able to talk to older brokers, exactly-once implementation (only at least once right now, because of retrials)
- https://github.com/andywer/webpack-blocks use predefined functions to create a webpack config, instead of everybody doing the same, good idea, functional ffs
- https://draft.li/blog/2016/11/28/javascript-engines-hidden-classes/ a new property on an object = 1 new hidden class. a same function form a linked link of hidden class (each of them "inherits" another)
- http://www.java-allandsundry.com/2016/11/spring-kafka-producerconsumer-sample.html i dunno, i don't like Spring. Don't like the naming "KafkaTemplate" wtf, it's a KafkaProducer. "ConcurrentKafkaListenerContainerFactory"... I find all the pieces more complex to understand than the raw.
- http://www.slideshare.net/Couchbase/streaming-operational-data-with-kafka-confluent Confluent platform, Kafka Streams, Schema Registry. High Level.
- https://github.com/takari/polyglot-maven-examples/blob/master/scala/minimal-scala/pom.scala No more pom.xml that's a win. WOW. Most of the mapping done. I hate xml.
- https://blog.jetbrains.com/idea/2016/11/intellij-idea-2016-3-ga-java-8-and-es6-debugger-and-ui-improvements-and-a-ton-more/ Intellij Idea, best IDE ever, since forever.

# 05-12-2016

- https://github.com/zeit/styled-jsx Another solution to handle style with React
- https://medium.com/@dkomanov/scala-stringbuilder-vs-java-stringbuilder-performance-3167a96abfc2
- https://dkomanov.github.io/scala-serialization/ dude is benchmarking everything. Here, some serde library. PB/Boo/classic java
- https://medium.com/@dkomanov/scala-string-interpolation-performance-21dc85e83afd last but not least: the string interpo is a nice feature in scala, but slow as hell. I didn't know it was using a java.util.StringBuilder instead of the Scala one, funny?
- https://medium.com/@thejameskyle/dear-javascript-7e14ffcae36c Yes. We can't imagine being at the place of the big project maintainers. motto: Always be positive.
- http://techblog.netflix.com/2016/12/netflixoss-announcing-hollow.html a new surprising cache system living in the jvm heap. One producer create snapshots on a storage (disk, s3, dynamo..), consumers reads it from time to time (ro). Resilient. No cold cache. Data indexes. Hot data identifier.
- http://www.modulecounts.com/ package manager: nodejs 500/d, mvn: 181/d 
- https://github.com/simeji/jid Love this idea! Inspect a JSON file through a CLI, very very nicely done
- https://www.webworldwide.io/ connectivity stats all over the world, all countries listed?
- https://vorpus.org/blog/why-does-calloc-exist/ interesting to know about calloc. Its implementation may vary and use copy-on-write instead of allocating the whole buffer.
- https://github.com/juliangruber/review easy and slick. an app to render any website with any format, and combine the whole into a page. Nice to monitor (browser updates..) or just to monitor competitors :)
- http://blog.bugreplay.com/post/153861574674/fkadblock-how-publishers-are-defeating-ad blocking adblockers: a few techniques
- http://calendar.perfplanet.com/2016/http2-push-the-details/ h2 push is very complicated to put in place and use. push or resource hints? tcp slow start. (tcp send small packets, then increase to test the network). It's not production ready yet, the gain does not seem really great, use-cases are not clear..
- https://www.youtube.com/watch?v=jaqDA7Btm3c styled-components in React. Build a pure UI component just from css written in a tagged template literal. Then wrap any other component around.

# 04-12-2016

- http://mrale.ph/blog/2015/11/02/crankshaft-vs-arguments-object.html tldr: do not use "arguments", and write monomorphic functions.
- http://raganwald.com/2016/11/30/anamorphisms-in-javascript.html super interesting. separating structure traversal from processing. generators, using tree algorithms (depth first, breadth first..) and more.
- https://www.reddit.com/r/javascript/comments/5g4bmu/anamorphisms_in_javascript/ ana+cata: create a hylo to avoid intermediate structure (array). but because it's using generators in-between, you don't have any structure in-between, so hylo is not necessary.
- https://github.com/mathisonian/premonish track the mouse movements to determine where it's going to be/click after
- https://www.helpnetsecurity.com/2016/11/30/exploited-de-anonymize-tor-browser-users/ js exploit to deanonimized tor browser users! wow. Getting access to kernel32.dll/VirtualAlloc, wtf is wrong. https://gist.github.com/kristovatlas/e03be5f10e48801aec88b0e23f00a3d7
- https://github.com/kristovatlas/osx-config-check YES to this. Will run it asap. Ensure a lot of crap is disabled on your system.
- https://engineering.footballradar.com/taming-awful-legacy-data-feeds-using-akka/ interesting approach using Akka fsm to handle an ugly feed/protocol
- http://hodoripsum.com/ no comment
- https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca?hl=en if i didn't already have a new tab, that would be it!
- http://gearaward.com/inspiration.html Sublime codepens. "Talented web artists exhibit code-driven art"
- https://www.tuftandneedle.com/mattress/ Nice idea, design, packaging, and transparency about the whole thing! Too bad, USA only.
- http://v8project.blogspot.fr/2016/12/v8-release-56.html es6 native features are getting a bit faster (still way behind es5 equivalent)
- http://ben.balter.com/2016/09/13/seven-habits-of-highly-effective-githubbers/ Those I like: Ship early, ship often, Always be willing to help.
- http://tech.kinja.com/how-not-to-pull-from-s3-using-apache-spark-1704509219 I wonder if that's style the case. Basically, textFiles behaves badly with S3 and need to switch to the original S3 client to parallelize work on workers.
- https://github.com/lord/slate I hope i'll need that one day! Generate a beautiful static documentation for an API. Too bad it needs ruby :/
- https://drill.apache.org/blog/2016/11/29/drill-1.9-released/ Better Parquet compat in Drill
- https://github.com/poly/stdlib definitely to watch. microservices library. Looks like Lagom!
- http://data-artisans.com/stream-processing-myths-debunked/ Why Lambda Architecture is dead. (hey Kappa)

# 03-12-2016

- http://scaldi.org/ An alternative for DI in Scala, with a proper Scala DSL. Extension for Play, and Akka.
- https://www.youtube.com/watch?v=0ZZquVylLEo GTA in real life. Very impressive. And the music is wonderful.
- https://www.crypto101.io/ introductory course on crypt. pdf of 250pages. I'll read it, one day.
- https://sqlite.org/testing.html sqlite: 116kLOC. test code: 92MLOC. WAT.
- https://npm-stat.com/ download charts from any npm package, daily/weekly/monthly/yearly. nice.
- https://anonscm.debian.org/cgit/collab-maint/procps.git/tree/proc/whattime.c the "uptime" program source. It even handles "decades".
- https://peteris.rocks/blog/htop/ htop details and.. a lot of details about linux processes in general, nice
- https://peteris.rocks/blog/parsing-malformed-json/ a malformed to well formed json "rewriter" 
- https://www.oo-software.com/en/shutup10 a tool of flags to enable privacy back in Windows ;-)

# 02-12-2016

- https://medium.com/swlh/how-to-deal-with-your-overflowing-inbox-7214c3937b6 Super guide how to cleanup your inbox. No, just kidding. I remember i had cleanup inbox during a while, then started to get late in my NL.. a bit, a bit more, and crap, i have like 100 NLs to read now.
- https://meebleforp.com/blog/36/angular-2-is-terrible RxJS sucks, TypeScript sucks, Angular2 HTML crap sucks (true). Not sure I agree :D
- https://dev.to/jackmarchant/no-excuses-write-unit-tests Yes to tests!
- https://djen.co/ Incredible tool to create music by customizing the type of rights, instruments, speed etc. WebAudio FTW.
- https://reshape.ml/ for those who still writes html, this can come in handy to add some kind of macro in the html and transform them through plugins
- https://gigaom.com/2014/06/30/the-dark-side-of-io-how-the-u-k-is-making-web-domain-profits-from-a-shady-cold-war-land-deal/ .io belongs to the Chagossians and they don't get their due, "thanks" to UK
- http://refresh-sf.com/ what's with this name? anyway, a good JavaScript/CSS/HTML Compressor to quickly check or show stuff without cli
- https://annoying.dog/ no need of a desc. you know nyan cat ? it's not that.
- https://moat.com/advertiser/nutella?report_type=display Ask for ads of a given brand to check what's its strategy is. Interesting!
- https://github.com/AdoptOpenJDK/mjprof Inspect jstack trace with a nice console tool. Easier than to read the Java full stack traces in an editor
- https://blog.data.gov.sg/how-we-caught-the-circle-line-rogue-train-with-data-79405c86ab6a Crazy story about identifying a rogue train that causing issues to the other trains. Identified by cleaning up and creating models around the data.
- https://github.com/joshaven/string_score you don't need elasticsearch, you need this in your JS! rank a string matching. ("toto".score("t") == 0.6))
- https://github.com/blakeembrey/code-problems answer to code problems interviews (mostly in js)
- https://www.youtube.com/watch?v=__b6k2pR3Tg now and next from zeit. now can serve and deploy Dockerfile/html/package.json based project. (static). Immutable subdomain. SSR and frontend rendering with getInitialProps({req,query}). Would like to approach the webcomponents way.
- https://medium.com/swlh/mozs-accidental-journey-to-40m-f3a4ebc8ee24 Interesting story about how Moz was built
- http://tachyons.io/ "functional" css. basically, a css class for every css prop ;D (ie:  .tc { text-align: center }) Supposely easier to manage, and way lighter to transfer over the wire (class="f6 f5-ns fw6 dib ba b--black-20 bg-blue white ph3 ph4-ns pv2 pv3-ns br2 grow no-underline" ahah)


# 01-12-2016

- http://adventofcode.com/ it will unlock at 6am here, wth, it's already 1st december here, come on! ;) Not sure what it will do. One challenge a day? edit: yes!
- https://cloudplatform.googleblog.com/2016/11/making-every-leap-second-count-with-our-new-public-NTP-servers.html "we'll run the clocks 0.0014% slower across the ten hours before and ten hours after the leap second"
- https://www.youtube.com/watch?v=LnX3B9oaKzw interesting and short lesson about functional prog and haskell. ref transparency, immutability, easy concurrency, 
- https://wiki.haskell.org/Introduction_to_QuickCheck1 the equivalent of scalacheck is quickcheck in haskell. reminder: check a property invariance.
- https://github.com/phaistos-networks/TANK yet another distributed log service. In C++, very high performance wanted.
- http://www.slideshare.net/BrendanEich/int64 Int64 will land in JS Int64(0) or 0L
- https://en.wikipedia.org/wiki/Cosmic_ray_visual_phenomena So, astronauts see flashes even eyes closed, thanks? to some cosmic ray
- https://softwaremill.com/beautiful-folds-in-scala/ very interesting, Fold pushed to the limit by combining it to different structures: Monoids, Lens, Futures, some cats in there.
- https://github.com/non/kind-projector avoid "({type L[A] = Either[Int, A]})#L" and use "Either[Int, ?]". Better right?
- http://underscore.io/blog/posts/2016/11/24/value-discard.html Always add compiler's warnings, it saves lifes.
- https://aws.amazon.com/athena/ query data in s3 from with a sql layer. 5$/TB (better use parquet!)
- https://github.com/depcheck/depcheck Good nodejs project: "how each dependency is used, which dependencies are useless, and which dependencies are missing from package.json." Can serve as a core for a bigger project (like watching modifications)
- https://github.com/knitjs/knit another monorepo "organizer", à la lerna. using yarn and depcheck.
- https://eev.ee/blog/2016/12/01/lets-stop-copying-c/ it's true that a lot of crappy syntax comes from C!
- https://medium.com/product-hunt/product-hunt-angellist-%EF%B8%8F-c408bfe5d68 Product Hunt has been acquired
- https://www.youtube.com/watch?v=2vFrZXWiwIc position: fixed: avoid. just "will-change: tranform" can fix junk.
- https://app.tinyletter.com/ good stuff if you want to create a newsletter, free, quick, slick, and painless. provide a link to share or iframe for integration.
- https://www.washingtonpost.com/graphics/national/maps-of-american-infrastrucure/ "infrastrucure" very interesting when you're not living in the usa.
- https://www.softwaremill.com/implementing-a-custom-akka-streams-graph-stage/ Very good article about how create a custom GraphLogic in akka streams
- http://githubengineering.com/glb-part-2-haproxy-zero-downtime-zero-delay-reloads-with-multibinder/ TIL multiple processes can listen on the same port (SO_REUSEPORT)
- http://blog.ippon.fr/2016/11/30/scala-2-12-lambda-expression/ Scala 2.12 is now using invokedynamic to deal with functional interface of Java8
- https://github.com/cvogt/cbt cbt is the next sbt :))

# 30-11-2016

- https://developers.google.com/web/progressive-web-apps/checklist Progressive web app checklist by Google, What to Test, and How to fix if it fails
- https://github.com/MaximAbramchuck/awesome-interview-questions#scala nice questions/answers, you can actually learn stuff!
- https://www.youtube.com/watch?v=D31_L3LMDe0 Criteo technique to serve ads images. bandwich: 3GB/s, SLA99.99%, 30ms latency, JMagick, Finagle, Mesos, Twitter Server for admin.

# 29-11-2016

- https://github.com/chtefi/ultra-slim-play-scala Starting a Play! http server with the bare minimum.
- https://liftweb.net/ it's seems to be a scala web framework very powerful but.. the doc is just ugly, all over the place, no proper quickstart with some proper code etc. don't want to go deeper
- https://verizon.github.io/ Nice page with all verizon open-source projects. Good stuff in there.
- https://github.com/venukanaparthy/topk-users-bloomfilter-spark/blob/master/src/main/scala/com/esri/spark/BFSpark.scala Bloomfilters and Spark, using Algebird
- https://github.com/tonsky/FiraCode I now have this font with ligatures in my Intellij, wonderful :-)
- https://www.reddit.com/r/scala/comments/5f5049/http4s_vs_finch_vs_akkahttp_vs/ http4s, finch, or akka-http. http4s is going to cats (instead of scalaz). finch is twitter ecosystem (they reimplement some lib existing stuff..), akka-http is good overall, but brings its own junk.
- http://stackoverflow.com/questions/999489/invalid-signature-file-when-attempting-to-run-a-jar i stumbled upon this error, due to new dependencies that packaged their own signed stuff. You have to remove the signature from the fat jar at assembly time, boom!
- https://www.youtube.com/watch?v=wewAC5X_CZ8 Jenn Shiffer "funny" talk about her satires and the tech culture. Sweet voice! ;D
- https://github.com/WICG/content-size a propal to enforce content size limit on &lt;iframe&gt;, that's bold Oo
- https://github.com/node-modules/detect-port nodejs project to get a random port or detect if one is already listening. it's funny, because it simply opens a socket server on the (or each +1 +1) port to know if occupied or not
- http://doc.akka.io/docs/akka/snapshot/dev/multi-jvm-testing.html sbt-multi-jvm plugin, to start tests on different JVM at test time
- https://medium.com/@anicolaspp/akka-cluster-in-docker-a-straight-forwards-configuration-b6deea32752d Some troubles running an akka cluster in a scaling docker compose environment
- https://webpack.js.org/guides/migrating/ nice and stairghtforward migration to webpack 2
- http://www.lihaoyi.com/post/OldDesignPatternsinScala.html Pattern useless in Scala: Builder (named args), Singleton (object), Adapter (implicits), Chain Of Responsability (linked list of "processors") actually still used but in a different way (no successor, but an immutable list), Interpreter still ok (a parser of expr),  Observer yeah! but you will mostly use Rx or Futures for that.

# 28-11-2016

- http://thenewstack.io/a-brief-comparison-of-mesos-and-kubernetes/ Mesos seems to be adapted for big clusters. Kubernetes, which is a container management/scheduler, is more for lightweight clusters, quick scaling, and needs less resources. Kubernetes is like Marathon (which deal with containers) for Mesos.
- http://labs.criteo.com/about/ 37 billions request / day. 37PB of storage.
- http://blog.tmorris.net/posts/refactoring-filter/ you thought .filter(fn) was easy to implement? WRONG. Look this Haskell impl.
- http://jedesah.logdown.com/posts/282944-dont-use-scalaz-task-like-i-did Scalaz Tasks have referential transparency, Scala's Futures do not.
- https://github.com/jeffposnick/create-react-pwa create-react-app patched to handle progressive web app (using sw-precache to generate the serviceworker.js from the static files)
- https://github.com/facebookincubator/create-react-app/pull/1101 the error red box is back into create-react-app (note: Chrome bug: window.onerror's Error object stack is truncated. The fix being: Error.stackTraceLimit = Infinity;)
- https://www.stacktracejs.com get the error stacktrace in a nice objects array
- http://www.reactnativeexpress.com/ a nice website to learn react-native components in the browser
- https://fhinkel.github.io/six-speed/ ES6 features against their ES5 counterpart (es6 features are mostly slower :D)
- https://blog.cloudflare.com/hpack-the-silent-killer-feature-of-http-2/ HPACK: a algorithm to compress headers efficiently in http2.  It's like the headers now takes as much as the content, funny.
- https://www.youtube.com/watch?v=GtVStvEywzU npm ecosystem has exploded. apps has >100 deps. ~14% of all packages are vulnerables. Crazy vulnerabilities to access /etc/password with /%e2%e2/%e2%e2/%e2%e2/etc/password in the url (../../../etc/password) ! some xss. Use snyk.io to check your packages.
- http://javers.org/documentation/diff-examples i was looking for a lib to diff java objects, found!
- http://www.regular-expressions.info/catastrophic.html trying to match (x+)+y in "xxxxxxxxxxxxxxxxxxxx" : it's gonna explode, because it can't find y, so it's try all possible combinaisons of (x...)(x...) multiple times because of backtracking tests (when it can't match, it backtracks the previous group, something like that)
- http://blog.xebia.fr/2016/11/28/testez-vos-invariants-avec-scalacheck/ Scalacheck to test if an invariant "holds". (basically it generates random data structured as you want, and test if all cases pass)

# 27-11-2016

- https://blog.insightdatascience.com/isee-removing-eyeglasses-from-faces-using-deep-learning-d4e7d935376f remove eyeglasses from faces. then after, you can "try" different other eyeglasses styles without removing yours
- https://github.com/xviniette/FlappyLearning an AI learning how to play Flappy Bird (neural network). Generation 82 was the winning one for me.
- https://m.signalvnoise.com/the-tool-we-built-to-keep-everyone-in-the-loop-at-basecamp-69bc58312014 moaar basecamp. All people in async mode.
- https://mural.co/ simple concept but nicely done. have a wall of postit (mostly :D), and organize them as group of ideas. Mostly a dashboard with widgets linked together.
- https://medium.com/@ageitgey/the-new-macbook-pro-is-kind-of-great-for-hackers-64c1c577a4d2 ok the title is a clickbait. But some good points in there, the new mbp is using USB-C, which is an open standard. The adapters are therefore reusable with any devices. (almost. due to power supply difference, and some odd differences according to the comments)
- https://github.com/clauderic/react-sortable-hoc sortable list in react, very nicely done
- https://github.com/chriso/validator.js check any string and sanitize in javascript
- https://academy.datastax.com/courses/ i will definitely follow those courses about Cassandra. Seems to be of very good quality
- http://www.ebaytechblog.com/2012/07/16/cassandra-data-modeling-best-practices-part-1/ Think denormalization (read++). Adapt the structure of the data from the query patterns.
- https://gist.github.com/chtefi/a39448da750c9f8815fa44b36e29e0e7 some of my deambulations with cats and scalaz
- https://github.com/lloydmeta/slim-play build a simple Play app without boilerplate code, without routes/ etc. Looks nicer.
- https://github.com/finagle/finch build finable http services
- http://blog.erratasec.com/ just discovered this nice blog. Guy seems like a good expert in networks.
- http://blog.erratasec.com/2016/11/how-to-teach-endian.html endianness teaching (big endian: "human", little endian: reverse bytes: was more efficient to process by circuits a long time ago)
- http://blog.erratasec.com/2016/10/configuring-raspberry-pi-as-router.html i suck at networking and iptabling. interesting to reproduce @home
- https://www.techempower.com/benchmarks/ wanna pick a http framework? this can help.
- https://holidayhole.com/ "To celebrate Black Friday, Cards Against Humanity is digging a tremendous hole in the earth." and they accept donation. They raised $100k. That's it, no deeper meaning. A video of the digging. Wtf.
- http://techblog.netflix.com/2015/11/linux-performance-analysis-in-60s.html Quick review of some classic linux tool to use when debugging sys perf

# 26-11-2016

- https://www.youtube.com/watch?v=fxZuzos7Auk explaining how bugs are working in Super Mario Bros 3
- https://github.com/lipp/hackernews a hackernews reader using next.js (react, server side) ans js generators
- https://github.com/marcelduran/webpagetest-api automatise webpagetest calls with this wrapper, lots of options
- https://www.reddit.com/r/scala/comments/5eu9if/intellij_vs_ensime/ should i try ensime with subl instead of intellij? it's true that something, it drives me nuts, cpu 100% for a few minutes, wtf. edit: I tried to set it up in my subl, didn't work, couldn't find why quickly, trashed it, sorry.
- https://github.com/mikeal/dropub WebRTC to share files, nice and clean webpage https://dropub.com/
- http://mrale.ph/blog/2016/11/23/making-less-dart-faster.html create a custom lexer instead of using rexexp when not needed (performance oriented). Comparison and fixes about .substring in V8 and Dart
- http://akka.io/news/2016/11/22/akka-http-10.0.0-released.html lots of related projects: cors, sse, session (cookies, headers, local sto, JWT). The full doc will be restyled soon. Not experimental anymore :)
- https://github.com/TypeStrong/ts-node a "node xxx.ts" to code server side in typescript without additional piping
- https://www.neos.io/blog/react-snippets-debug-component-performance-with-es7-annotations.html dead simple but super useful. An annotation to display the delta between previous and new React [props, state, context].
- https://medium.com/@anicolaspp/yet-another-sbt-docker-introduction-2d9fb99fe367 very cool intro to sbt docker plugin with a real use-case and real problems they got
- https://github.com/stanch/reftree already known, this cool stuff, but never needed it :D Generate an image from an immutable data structure to understand what the underlying structure (think Trie, nodes reutilization..)
- https://medium.com/@anicolaspp/purely-functional-data-structures-and-jmh-197636f3b19e JMH usage to compare DIET structure between dogs and scalaz, cool stuff
- https://medium.com/@anicolaspp/how-to-log-in-apache-spark-a-functional-approach-e48ffbbd935b the Monad Writer from cats. I might use this one, very appealing!
- http://learnyouahaskell.com/for-a-few-monads-more Looking for the writer monad, i stumbled upon this. The monad writer seems made to log stuff "aside". It supports monoidal accumulation.
- https://s3-us-west-2.amazonaws.com/book-sample/advanced-scala-preview-with-full-toc.pdf Found this one: Preview: Advanced Scala with Cats, 50 pages, seems very accessible
- https://github.com/OlegIlyenko/graphiql-workspace Nice additions to GraphiQL ui that was indeed, pretty light.
- http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html Some functional types explained with great pictures

# 25-11-2016

- https://projects.lukehaas.me/regexhub/ listing common regexes for js. neat idea. 
- http://haseebq.com/farewell-app-academy-hello-airbnb-part-ii/ from 120k to 250k$ going to Airbnb. Awesome dude.
- https://www.flickr.com/photos/mwichary/sets/72157677060922185 So many old video games logo/posters :)
- https://www.destroyallsoftware.com/talks/wat WAT moments when coding. Ruby and JS takes their parts.
- https://dply.co/how Funny. Create a Linux VM, 2h free. Auto-delete at the end.
- http://datanerds.io/post/WAT-cassandra-1/  WAT moments with Cassandra
- http://datanerds.io/post/cassandra-no-row-consistency/ Discover a bug (ie: a feature), where 2 updates on the same row causes a weird resolution: "if there are two updates, the one with the lexically larger value is selected.", and moreover, on the CELL level, not the row level. Aberrant situation.
- https://blog.cloudera.com/blog/2015/08/how-apache-spark-scala-and-functional-programming-made-hard-problems-easy-at-barclays/ some optimization with Spark and functional features. I learned about |+| from Scalaz and tested it. I'll definitely use this one when I can.
- http://ai.stanford.edu/~zayd/why-is-machine-learning-hard.html Code is algorithm+impl. ML has a LOT of factors to determine why it doesn't work as expected.
- https://github.com/drduh/macOS-Security-and-Privacy-Guide I installed Little Snitch thanks to that. And that's crazy scary all the connections made outside by your OS (Sierra) and all the apps :(
- http://anzorb.com/we-dont-need-your-polyfills/ not sure it's not over-engineered.. (polyfills are generally tiny) but: import in the browser only the needed polyfills, thanks to webpack2 code splitting System.import feature.
- https://tobiastom.name/notes/7a79eed0 Homebrew connects to GA!

# 24-11-2016

- https://github.com/vhf/v8-bailout-reasons Some odd code bits where v8 lose its thing and deoptimizes because it surrenders (ie: slow)
- http://globocom.github.io/megadraft built on top of draft.js to provide a nice editor. unrelated: wtf its hamburger menu
- http://www.npr.org/sections/alltechconsidered/2016/11/23/503146770/npr-finds-the-head-of-a-covert-fake-news-operation-in-the-suburbs fake news is a good business. >~$20k/month
- http://highscalability.com/blog/2016/11/16/the-story-of-batching-to-streaming-analytics-at-optimizely.html going from hbase+druid to hbase with samza to aggregate in RT sessions data (and batch writes into hbase), with RockDB as the state db behind samza.
- https://github.com/staltz/matrixmultiplication.xyz an original method to multiply matrices visually, in cyclejs
- http://cssreference.io/ a modern webpage to see most of the css property usage, visually

# 23-11-2016

- https://medium.com/@Shapiro/introducing-libscore-com-be93165fa497 3rd party libraries analysis on 1 million website
- https://www.youtube.com/watch?v=iWkl2TSflDE A company should have a test strategy (TU a lot (fast) / TI a bit less (not too slow) / UI a bit lesser (slower)). Performance tests, load tests, security tests. Exploratory tests, usability tests, acceptance tests. BDD tests everywhere (orthogonal notion)
- http://youmightnotneedjquery.com/ remember this one?
- https://github.com/WPO-Foundation/webpagetest did you know you can run https://www.webpagetest.org/ in local? i didn't
- https://www.go.cd/  Just tried it. A jenkins with a more complex UI and still at XML old time? :^
- https://medium.freecodecamp.com/mark-zuckerberg-is-the-most-powerful-person-on-earth-but-is-he-responsible-5fbcaeb29ee1 Facebook is locking down the web. Innovation is stuck, you have to play by it rules.
- http://stackoverflow.com/users/story/join just got a email from them. Develop Story. "Our latest addition, Developer Story" wtf; i know it exists since months
- https://blog.risingstack.com/node-js-at-scale-node-js-garbage-collection/ tiny into to why GC exist
- https://umaar.com/dev-tips/121-css-coverage/ CSS coverage in Chrome Devtools, nice?!
- https://medium.com/@olivercameron/20-weird-wonderful-datasets-for-machine-learning-c70fc89b73d5 datasets for ML practice
- https://blog.sketchapp.com/an-iconic-new-look-and-more-4191df5ce8d7#.560rsv2e1 Always thinking about the Sims.
- https://medium.com/@rajaraodv/functional-programming-in-js-with-practical-examples-part-1-87c2b0dbc276 Yes to functional in JS. But please, use TS at least, it really needs types.
- https://hackernoon.com/19-things-i-learnt-reading-the-nodejs-docs-8a2dcc7f307f Lot of not-so-known tips about nodejs
- https://en.wikipedia.org/wiki/Abstract_nonsense Category theory = abstract nonsense. Good.

# 22-11-2016

- http://reactstudio.com/ Sketch to React. Awesome. Coding is overengineering.
- https://github.com/ParhamP/Speech-Hacker Make a speaker say anything you want by splitting/concatenating bits, didn't try (i hate python, and there are a few steps to do..).
- https://www.youtube.com/watch?v=pXCjzo-L_94 very interesting talk about web tracking, how it works (quickly)
- https://github.com/dataiku/wt1 a web tracker anyone can install
- https://thehftguy.com/2016/11/18/google-cloud-is-50-cheaper-than-aws/ GCE way less expensive than AWS (GCE is the second generation of cloud computing, and they have their own network hardware). Big SSDs are more expensive on GCE btw.
- https://thehftguy.com/2016/09/12/250-gbday-of-logs-with-graylog-the-good-the-bad-and-the-ugly/ Graylog + ES for 250GB/d logs "Log retention MUST be based on size." "mongodb is the worst database in the universe"
- https://www.youtube.com/watch?v=7EQWNiwgT4o More explanations about Free monads, some good points to understand better
- https://www.youtube.com/watch?v=J2dOTKBoTL4 Advanced Service Worker usage. for await (const value of (await fetch(url)).body) { ... }. TextDecoder to read a stream. Readable Streams. Transform Streams. PWA != SPA. foreignFetch/ background fetch. Page Transitions.
- https://github.com/facebookincubator/create-react-app/pull/816/files execSync("lsof -i:...") or execSync("ps -o...") yeah, very cross-env proof. No pure nodejs equivalent? :/
- http://blog.higher-order.com/assets/trampolines.pdf At first, it's okay to understand, then it degrades slowly.
- https://gist.github.com/chtefi/0cccae634ff7130425ab8ae87b24a709 Some notes I took

# 21-11-2016

- https://medium.com/javascript-scene/why-native-apps-really-are-doomed-native-apps-are-doomed-pt-2-e035b43170e9 native apps because native apps are most costly
- https://m.signalvnoise.com/if-you-ask-for-my-permission-you-wont-have-my-permission-9d8bb4f9c940 "don't ask, do". yes, but that could be a bit too bold.
- https://engineering.creditkarma.com/data/solving-high-throughput-akka-streams/ just used akka streams instead of custom code :)
- https://medium.com/@localvoid/how-to-win-in-web-framework-benchmarks-8bc31af76ce7 front-env ui framework benchmark are biaised
- https://www.youtube.com/watch?v=nPUvzn3CTQc super interesting, International Space Station bathroom tour by  Samantha Cristoforetti 
- https://www.troyhunt.com/ad-blockers-are-part-of-the-problem/ a tiny &lt;span&gt; with a proper message adblocked for no reason. Just because someone didn't like it and added it to some list. Pissed off.
- https://github.com/aaronshaf/shaf-chart Write a classic &lt;table&gt; with number, wrap it into a &lt;shaf-chart&gt;, boom, you have a chart. Nice. (webcomponent)
- https://www.youtube.com/watch?v=1ikAnYoSZJU Snowden talking about privacy, society, democracy.. Inspiring.
- https://github.com/Avaq/Fluture a Future implementation (monadic) in front the the js Promise
- http://tsunanet.net/~tsuna/async/1.0/com/stumbleupon/async/Deferred.html For some reason, i don't really like this Deferred thing. Give me Future or Observables.
- http://reactore.com/repository-patterngeneric-dao-implementation-in-scala-using-slick-3 Slick is not an ORM. But Slick is great to do repositories and queries in Scala. (note: you can generate the code from an existing db)
- http://reactore.com/generic-rest-api-services-using-akka-http/ I love the approach. Defining repositories with Slick. Then generic rest over them (get, post:id etc.), then using akka streams and the reactive-streams spec (slick implements it), to publish db changes to websocket (akka-http). Gorgeous.

# 20-11-2016

- https://github.com/sylvainpolletvillard/postcss-grid-kiss Define your (grid) layout using ascii art, awesome
- https://m.signalvnoise.com/status-meetings-are-the-scourge-39f49267ca90 standups are useless, replace them with async communication, and a cron to email ppl.
- https://medium.com/@sinisalouc/variance-in-java-and-scala-63af925d21dc some revisions about covariance/contravariance
- https://github.com/StevenBlack/hosts consolidate your hosts file to block a TONS of things
- https://i.stack.imgur.com/KjDLw.png contravariance and covariance in one picture
- http://blog.kamkor.me/Covariance-And-Contravariance-In-Scala/ another post about variances, maybe better explained
- https://medium.com/@shahata/why-i-wont-be-using-fetch-api-in-my-apps-6900e6c6fe78 comparing axios to fetch. fetch being way more low level, have restrictions by default (cors, no cookies), can have an unexpected behavior (404 is success). Conclusion: always have a lib to do the abstraction
- http://codegolf.stackexchange.com/questions/28821/regex-that-only-matches-itself/31863#31863 a regex that match only itself. it's possible, WTF
- http://sciencebulletin.org/archives/7723.html "solves Rubik’s Cube in 637 milliseconds" 637ms.
- https://github.com/kamkor/akka-http-mdc-logging-kamon keeping MDC context through different threads, here with akka-http and kamon
- https://github.com/joewalnes/greendots missing up your github contributions and write nice message (thinking: HIRE ME ahah)
- https://thehftguy.wordpress.com/2016/10/03/haproxy-vs-nginx-why-you-should-never-use-nginx-for-load-balancing/ nginx (free) offers no metrics at all on the load balancing status. HAProxy has >70, parseable, and good integration in monitoring system (datadog).
- https://medium.com/@cdn77/why-the-internet-is-broken-4962cdbbd664 internet is broken because of isps limiting streaming rate. He proposes a webrtc solution to share the streaming (same source) but from p2p and the cdn at the same time (to share the connection)

# 19-11-2016

- https://www.theguardian.com/science/2015/jul/23/john-horton-conway-the-most-charismatic-mathematician-in-the-world Conway seems like a nice guy! Love the date game aspect.
- https://en.wikipedia.org/wiki/Monstrous_moonshine i don't understand any sentence in there. And no idea why it exists.
- https://www.washingtonpost.com/news/monkey-cage/wp/2016/11/17/this-researcher-programmed-bots-to-fight-racism-on-twitter-it-worked/ Dude created bots to reply to racist tweets. "Tweets from white bots with 500 followers did not cause a significant change in these users’ behavior, but tweets from black bots with few followers actually caused an increase in the use of racist slurs."
- http://www.2ality.com/2016/11/proxying-builtins.html JavaScript and this, a love story.
- https://moz.com/blog/meta-referrer-tag TIL about the meta "referrer"
- https://m.signalvnoise.com/how-we-set-up-our-work-cbce3d3d9cae No "sprint" but "cycle". 6 weeks cycle then 2 weeks rest (pet projects, fixes..). Teams of 3. A feature request needs a Pitch document that explain the why, why right now it's not possible, a solution. No sync communication, only async. (like this one)
- https://hackernoon.com/did-slack-really-not-see-it-coming-a011cd840e5b Back to the Slack letter to Microsoft. Oh noes, a big competitor!
- https://urchin.biz/urchin-software-corp-89a1f5292999 Nice story about Urchin (Google Analytics now)
- https://developers.google.com/web/fundamentals/performance/prpl-pattern/ PRPL is well known and applied nowaydays in the JS community i think. 
- https://flywaydb.org/ Handle your SQL database evolutions "easily". Like Play's Evolutions. There is also a plugin to replace Evolutions by Flyway https://github.com/flyway/flyway-play.
- https://sketchboard.io/ quite nice to quickly draw and share some "hand-style" (software) diagram, bookmarked. The UI/UX could be better through.
- http://seiferteric.com/?p=356 make computers talking using screens, webcams, and qrcodes. it works!
- https://github.com/moklick/frontend-stuff Many many resources to do anything on a website (pickers, loaders, social buttons, functional, animation, scrolling, canvas, tables, maps...)
- https://github.com/WickyNilliams/headroom.js auto hide the page header when scrolling down, show it back when scrolling up (as many websites does now), I like that.
- http://aroc.github.io/side-comments-demo/ add medium-like side comments à la Medium &lt;3
- https://connoratherton.com/loaders Yeah loaders are cool.. but we should never wait! ;-)
- https://leungwensen.github.io/svg-icon/ looking for an (optimized) svg icon, it's there
- https://github.com/gztchan/awesome-design So many links about design, come on (7k stars)
- https://ifttt.com/search/services A simpler zapier. Links between (so many...) services. IFTTT: "If This Then That" "Send an SMS if the fridge door is left open too long" "Start brewing coffee when your FitBit registers you're awake" "Automatically tweet Medium stories that you recommend"
- https://status.zapier.com/#app-status So. Many. Services.
- https://getawesomeness.herokuapp.com/ The awesome list of awesome lists. Gosh.
- https://github.com/ripienaar/free-for-dev Ok, this one is a mandatory bookmark. List of any free (or free tier capable) *aaS and misc tools, to quickly (or not) rely on 3rd party services. Amazing.
- http://blog.higher-order.com/blog/2013/11/01/free-and-yoneda/ Free monads, IO monad, Coyoneda. "type IO[F[_],A] = Free[({type λ[α] = (F[I], I => α) forSome {type I}})#λ, A]". YES!
- http://blog.higher-order.com/assets/scalaio.pdf Free Monads impls are still a bit beyond me. It will come.
- https://github.com/functional-streams-for-scala/fs2 Compositional, streaming I/O library for Scala (previsouly scalaz-stream)
- https://github.com/krasserm/streamz akka streams (Source, Flow, Sink) to fs2 streams (Stream, Pipe, Sink) + fs2 streams camel integration
- https://kwangyulseo.com/2014/05/21/scala-option-fold-vs-option-mapgetorelse/ Never noticed we could do .fold on an Option to handle both None/Some get cases. And fold forces the same returned type, good point.
- https://github.com/ryanjay0/miles-deep a neural network to edit video and keep only ... porn scenes ! :-D Smarter than the recent Yahoo network that identify only nude or not, here it identify why "type" of sexual scene, and will probably do more soon (identify positions..)
- https://github.com/n1trux/awesome-sysadmin very good list about sysadmin stuff, to bookmark. I've stumbled upon so many links -_-
- https://healthchecks.io https://pushover.net/ combining those two to get mobile notifications if some checks fails. (pushover: 5$ fee after 7d trial)
- http://blog.higher-order.com/blog/2013/11/01/free-and-yoneda/ Free Monads and Yoneda/CoYoneda. Trying, trying..
- http://www.drmaciver.com/2008/03/existential-types-in-scala/ a bit deprecated, F[_] is working fine now. Except for this case where existential type is useful: var l : List[Class[T]] forSome{type T} = List(classOf[Int],classOf[String]) # ERROR! the subtype must be the same
- https://www.implicitdef.com/2015/11/19/comparing-scala-http-client-libraries.html Play WS wins by its simplicity and good api. (the post focuses on how to make a http call easily)

# 18-11-2016

- https://github.com/pelotom/effectful write monadic code with anything, and without for comprehension (effectful being way less verbose)
- https://www.visualstudio.com/vs/visual-studio-mac/ VS is a very good IDE, nice move!
- http://arstechnica.com/information-technology/2016/11/spacex-plans-worldwide-satellite-internet-with-low-latency-gigabit-speed/ 4,425 satellites at 800 miles high (a normal sat is 10k high).
- https://www.troyhunt.com/8-million-github-profiles-were-leaked-from-geekedins-mongodb-heres-how-to-see-yours/ another leak. github is against commercial use of its public user data
- http://nypost.com/2016/11/17/facebooks-ad-metric-problem-is-becoming-zuckerbergs-headache/ weekly and monthly reach of marketers’ posts, which got inflated by 33 percent and 55 percent, respectively,
- https://hackernoon.com/an-ode-to-async-await-7da2dd3c2056 async/await in JS should become mainstream! Did a little gist to implement it in Scala, with async/await lib https://gist.github.com/chtefi/9eed93d0da287b37138fb9492348145e
- http://khamrakulov.de/get_insights_of_your_play_framework_application_with_dropwizard_metrics/ some work with Play and metrics using codehale/dropwizard (and not kamo) allowing to export metrics elsewhere than just to a controller. (console, graphite)
- https://medium.com/@yumenohosi/visualizing-regular-expressions-regexper-com-dade9ae3f0ab talk about regex interpretation and reference to this website that tremendously help  https://regexper.com/#%5E!%3Fh*(%3F%3Di)%7B2%2C3%7Dcase
- http://virtuslab.com/blog/akkapaint-simplicity-and-power-of-akka/ Akka Cluster, Persistence, Play, Websocket. Definitely something to master. Fantastic project.
- https://medium.com/@paulbreslin/why-you-probably-dont-need-yarn-5711ee40006f wrong arguments.
- https://blogs.msdn.microsoft.com/jdbcteam/2016/11/17/open-source-jdbc-maven/ the sql server jdbc connector on github and maven central, gg
- https://code2flow.com/ I... I love this thing ??? live generate a decision chart from some pseudo code (if, while, goto..) ULTRA useful to explain something to someone or ourself.
- https://doorbell.io/ provide a feedback widget to put in your app. desktop and mobile. super top when you start. 9$/month basic plan is cheap enough.
- http://gmvault.org/index.html backuping my gmail? let's go! 100k emails. 10h of sync according to gmvault.

# 17-11-2016

- https://dev.to/naveen/how-to-write-an-object-oriented-program-that-doesnt-suck some good advices to do better object oriented programming. The point being one class == one responsability. That's mostly true but not always necessary.
- https://medium.com/javascript-inside/an-introduction-into-lenses-in-javascript-e494948d1ea5 lenses in js is quite easy to do ourself (mostly), understand and use, thanks to the dynamic aspect of js. It's a very cool functional feature i never used.
- https://cdn.logrocket.com/LogRocket.min.js send your redux state over the wire to replay then as you want
- http://www.2ality.com/2016/11/concat-array-literal.html wtf is the point of this post. "[].concat[1,2,3]" = "[].concat[3]" and if you set [].concat on its proto to [1,2,3], then you're done. but, wtf.
- http://www.lesnumeriques.com/vie-du-net/microsoft-rejoint-conseil-administration-linux-foundation-n57361.html Microsoft has a better image than 2 years ago, gj
- http://boredzo.org/pointers/ Ahh, C pointers! brings back some memories. Always loved C
- https://twitter.com/villeimmonen/status/799267958291832832 I didn't even know "mktemp", great scripting tool `mktemp -d temp-XXXXX` => "/tmp/temp-Fa1vz"
- https://medium.com/the-mission/8-things-every-person-should-do-before-8-a-m-70cce8f22fe7 i have a true debate inside me. if i sleep more, would i be able to do more techno watch? not sure. so i sleep less. :/. And about that cold shower, come on.
- https://shift.newco.co/im-sorry-mr-zuckerberg-but-you-are-wrong-65dbf8513424 some says FB played a role in the election, because of its news (with sensational title as the web needs..)
- https://hackernoon.com/an-ode-to-async-await-7da2dd3c2056 another async/await is better
- https://github.com/scala/async Very cool, async/await à la JS or .NET in Scala

# 16-11-2016

- http://demos.algorithmia.com/colorize-photos/ Again, deep learning usage. Colorize a black and white photo, not bad AT ALL
- https://github.com/gritzko/swarm stumbled upon that again. It seems to have evolve quite a bit :-) basically, a online/offline distributed in-sync reactive data storage for webapps (javascript) (think collaboration, offline work..) CRDT model
- https://hstspreload.appspot.com/ the Chromium HSTS preload list where we can submit our website
- https://cs.chromium.org/chromium/src/net/http/transport_security_state_static.json the list of preload HSTS websites, in the source itself
- https://medium.freecodecamp.com/the-code-im-still-ashamed-of-e4c021dff55e tldr: don't forget ethics when coding. think about human impact if applicable.
- http://google.github.io/tracing-framework/ #perfmatters
- https://facebook.github.io/react/blog/2016/11/16/react-v15.4.0.html not that many new features, mostly stabilization, cleaning up, and debugging features
- https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying a very good quality link about distributed logs systems
- https://realm.io/news/first-object-database-realm-node-js-server/ object data for web or nodejs (mobile-first)
- http://rxmarbles.com/#combineLatest only the marbles of reactivex
- http://www.slideshare.net/Couchbase/nosql-for-java-developers couchbase and its rxjava client, basic
- https://github.com/ReactiveX/RxScala/blob/0.x/examples/src/test/scala/examples/RxScalaDemo.scala 2000 lines of RxScala examples, nice
- https://quickdraw.withgoogle.com/ lose your productivity with this neural network (pictionary)
- http://exploringjs.com/es6/ch_callables.html#sec_function-names Super interesting, the norm around the function name in Javascript.
- https://github.com/davidkpiano/RxCSS RxJs and CSS --crappy-var :) nice anyway
- https://worldchess.com/2016/11/12/world-championship-game-2-draw/ chess players are so damn good
- http://thisdavej.com/creating-node-js-microservices-with-ease-using-stdlib/ this stdlib has nothing to do with the Great C stdlib. Here, it's a framework to deal with and host microservices with a registry. no mention of comm/dependencies between microservices, too bad.

# 15-11-2016

- https://github.com/leebyron/ecmascript-iterator-hof Adding a left-to-right Iterator wrapper for Arrays, Maps, Sets etc. to get HOF
- https://stackoverflow.com/company/salary/calculator Wow, the salary at Stack Overflows are quite nice :D (even in France!). Talking about their "Developer Story" thing and Ads. Stack Overflow Enterprise.
- https://databricks.com/blog/2016/11/14/setting-new-world-record-apache-spark.html another record for the "sort 100TB" using $144.22. (cloud ofc). In 2013, 2100 hadoop nodes were needed, for 72min, woo! The new record used "only" 394 nodes for 50min, using Spark 2. And because its performance were largely enhanced (Thungsten, Catalyst, code gen), it is much more very efficient. http://sortbenchmark.org/NADSort2016.pdf the official report
- http://grafana.org/blog/2016/11/09/grafana-4.0-beta-release/ The alerting is finally available in Grafana, woot!
- https://www.mozilla.org/en-US/firefox/50.0/releasenotes/ FF50! (Chrome is 55beta :P)
- https://commits.io/ Create a poster containing... your github code
- https://github.com/underscoreio/shapeless-guide Shapeless lib guide and mini book. Definitely something I'll read later on
- https://www.reddit.com/r/scala/comments/5csfn3/as_of_212_how_fast_is_scala_now_also_what_is/ Developing a game in Scala, indeed, why not? Never through about it.
- http://benchmarksgame.alioth.debian.org/u64q/scala.html Scala (2.12) VS Java (8) micro benchmarks. Java almost always wins.
- https://blog.jetbrains.com/scala/2016/11/11/intellij-idea-2016-3-rc-scala-js-scala-meta-and-more/ Intellij is just the best IDE for Scala and its ecosystem. Scalajs, scala-meta (replacement of macros), akka-*
- https://github.com/WebAssembly/design/issues/112 For fun, WebAssembly (WASM) looking for a logo. Those topics are always cool, just looking at the pictures.
- http://timperrett.com/2014/07/20/scalaz-task-the-missing-documentation/ Scalaz Tasks VS classic Futures.
- https://en.wikipedia.org/wiki/Algebraic_data_type ADT algebraic data type = product types (tuples and records) and sum types (A | B). We can do easy pattern matching with this.
- https://gist.github.com/tpolecat/a0b65e8ffdf5dc34a48f a step-by-step gist that uses \/ and EitherT from Scalaz to abstract the typical case : Future[Either[Failure, Success]]
- http://bellard.org/jslinux/ a CPU emulator in JS, and a terminal. It downloads a true linux compiled kernel (&lt;2MB) and starts it.
- http://stackoverflow.com/questions/1732348/regex-match-open-tags-except-xhtml-self-contained-tags Never ever use a regex to parse html. This is why. TH̘Ë͖́̉ ͠P̯͍̭O̚​N̐Y̡ H̸̡̪̯ͨ͊̽̅̾̎Ȩ̬̩̾͛ͪ̈́̀́͘ ̶̧̨̱̹̭̯ͧ̾ͬC̷̙̲̝͖ͭ̏ͥͮ͟Oͮ͏̮̪̝͍M̲̖͊̒ͪͩͬ̚̚͜Ȇ̴̟̟͙̞ͩ͌͝S̨̥̫͎̭ͯ̿̔̀ͅ
- https://news.ycombinator.com/item?id=12961666 Neo4J testing: "max out write throughput, then pull the power cord, then pull the powercord again while it recovers"
- http://hmarco.org/bugs/CVE-2016-4484/CVE-2016-4484_cryptsetup_initrd_shell.html "The attacker just have to press and keep pressing the [Enter] key at the LUKS password prompt until a shell appears" 'nough said.
- https://www.cockroachlabs.com/blog/cockroachdb-stability-from-1-node-to-100-nodes/ cockroachlabs being very transparent about the stability problems they had and how they fixed it. TLDR: never delay stability
- http://timperrett.com/2014/07/20/scalaz-task-the-missing-documentation/ started to get a bit more of scalaz..

# 1[1234]-11-1016

Sometimes, you need a break and go on holidays. :airplane:

# 10-11-2016

- https://tech.zalando.com/blog/comparing-akka-streams-actors-and-plain-futures/ Akka Streams, Akka Streams! I definitely don't like infix notation here :/
- http://blog.akka.io/integrations/2016/08/25/simple-sink-source-with-graphstage only a crazy cookie would use Java with Akka Streams. Custom impl of GraphStage, quite useful to know.
- https://medium.com/js-dojo/4-things-vue-js-got-right-10820cc84004 meh post talking about Vue with a jquery image.
- https://code.facebook.com/posts/864213503715814/introducing-backpack-our-second-generation-modular-open-switch/ I'll just retain 100Gbit/s network impl. Not my domain.
- http://blog.akka.io/streams/2016/07/30/mastering-graph-stage-part-1
- http://blog.akka.io/streams/2016/07/06/threading-and-concurrency-in-akka-streams-explained

# 09-11-2016

- https://slackhq.com/some-of-the-ways-we-use-emoji-at-slack-a21be5030815 red/blue/green circle before a msg to indicate priority. I could definitely use that. nice visual cue
- https://medium.freecodecamp.com/using-fetch-as-google-for-seo-experiments-with-react-driven-websites-914e0fc3ab1 yes google is a smart cookie and can interpret js (react here), but with react-router it fails!
- https://medium.com/hillary-for-america/its-been-an-amazing-journey-here-s-what-i-ll-always-remember-b526f1b06429 Bye Hillary !
- https://medium.com/@shijuvar/building-high-performance-apis-in-go-using-grpc-and-protocol-buffers-2eda5b80771b Can't wait to test gRPC in a project
- http://www.shortlist.com/news/president-donald-trump-first-day-in-office-white-house omg that's incredible. USA, you're going to have a bad time.
- http://www.gamasutra.com/view/news/285149/Epic_Games_chief_pays_15M_to_protect_7000_acres_of_North_Carolina_wilderness.php Buy landscape to protect it. Awesome person.
- https://github.com/dhamaniasad/HeadlessBrowsers Some many headless browsers! It's always useful to know some, always a email with generated chart images to send :D
- http://blog.akka.io/streams/2016/07/06/threading-and-concurrency-in-akka-streams-explained Akka Streams is great
- http://doc.akka.io/docs/akka/2.4/scala/stream/stream-composition.html I mean it's awesome

# 08-11-2016

- https://dev.to/isaacandsuch/developer-driven-development/ Nice story about how it's working in its company. Some nice things about sharing, working on anything, the bus problem, "code review" before coding.
- https://www.youtube.com/watch?v=NYVjIjBMx6o troubles with the new mac book pro. a livestream by a well know dude. seems like a piece of shit unfortunately (look the video).
- https://github.com/jxnblk/repng react component to png. using generate the static markup then use datauri (markup to  https://github.com/sindresorhus/pageres that using phantomjs..!
- https://www.reddit.com/r/scala/comments/5bq57z/translate_reddit_source_to_scala/ someone is going to write reddit in scalajs, to follow!
- https://medium.com/@boxed/a-small-dive-into-and-rejection-of-elm-8217fd5da235 elm seems still incomplete for serious business (and still lacking of good use-cases resources unfortunately)
- http://www.catb.org/jargon/html/Z/Zero-One-Infinity-Rule.html i learned a new software rule! "Zero-One-Infinity Rule" (never put random limit just because, like 22 in scala)
- http://reasonablypolymorphic.com/blog/elm-is-wrong elm was just destroyed. solid args.
- https://edge.akamai.com/ec/us/highlights/keynote-speakers.jsp#edge2016futureofcommercemodal AliExpress improve its page load time by 36%: +10% orders, +30% conversions (in one country he told but we get the idea!): win! thanks to Akamai Site Acceleration & ESI
- https://www.youtube.com/watch?v=e-5obm1G_FY if you know nothing about functional programming, this is the video to watch, succinct, clear, and good speaker: Anjana Vakil (JSUnconf 2016)
- https://hackernoon.com/so-you-think-you-know-c-8d4e2cd6f6a6 ahah, C and all its pitfalls
- https://comments.network/ "<comment-box hackernews="11850599"></comment-box>" and boom, you have HN comments on your blog/page
- http://www.bbc.com/news/technology-37908915 Hyperloop (700mph) between Duabai and Abu Dhabi incoming
- https://datastudio.google.com/#/org//reporting/0B_U5RNpwhcE6ckdmZEJ0ZDJXUnM/page/VgD nice adwords (ctr, conversions, cpc, campaigns..) dashboard in datastudio, by Google.

# 07-11-2016

- https://github.com/faergeek/remove-medium-hash Remove the ugly hash medium.com auto-adds at the end of the url :) it messes up with the bookmarks otherwise
- http://c2fo.io/c2fo/spark/aws/emr/2016/07/06/apache-spark-config-cheatsheet/ Spark excel (lol) cheatsheet to configure some props (cpu, mem, overhead..) according to a cluster typology
- https://www.lightbend.com/platform/production i was looking for intel about conductr, google drop me here, but no *visible* reference to conductr, BAD UX ;)
- https://conductr.lightbend.com/docs/1.1.x/Home I had to look at the source to find this link eheh "solution for managing Lightbend Reactive Platform applications across a cluster of machines. " Commercial only iiuc.
- https://www.youtube.com/watch?v=jHoIzOdUn4c 1h of Martin Odersky resuming what's going on with Scala and Dotty. Quick notes: 2.12: java8, 2.13: scala libraries/collections (with some Spark'y methods (reducebyKey and so on)); split Scala stdlib to: core (what the compiler always need) + platform (containing community efforts, like a common json serde thing); scala.js production ready; Scala Native on LLVM; Scala Center: education, package "manager" (to find a scala package doing x). dotty: based on DOT. faster than nsc (scalac). New piece in Dotty: TASTY: T_AST_Y (optim AST). No more Macros.. but a replacement! (scala.meta) and more new features. ELM error messages incoming :). MVP Spring 2017. A new "pure" arrow function -&gt; (=&gt; would still exist). No null by default, need to "Object?". No more 22 :)) :heart:
- http://sciencebulletin.org/archives/7440.html -273.135°C. The electrons in a electric current appear individually. 0.0015k above absolute 0.
- https://hyper.sh/ already seen, but again, deploy on the cloud with docker behind, yeah cool. a bit expensive still. (21$/m 2cores/2gb ram)
- https://github.com/mbasso/react-decoration tons of annotations for AOP. some are practicals, some are useless (@componentWill/Did*(cb) wtf? type the method and be done)
- https://techcrunch.com/2016/09/26/zenly-raises-225-million-from-benchmark-for-its-location-sharing-app/ French startup, youhou. Know where your friends are.
- https://medium.com/startup-grind/how-i-went-from-being-a-stranger-to-having-a-network-in-silicon-valley-8cf7ac5fed thing i retain: figure out your goal. I think I have troubles with that, want to know a shitload of things, but what's the point eh? Manage, better coder.. make my startup i guess? All the code, boum.
- https://github.com/byteclubfr/copycast a simple tool to connect browsers for them to see the updates someone is doing in one folder (uh)
- https://ponyfoo.com/articles/making-time-for-side-projects Making Time for Side Projects: A Daily Habit. "Each and every morning, I do something to push my side projects forward". ok, no.
- http://highscalability.com/blog/2016/11/7/the-quickbooks-platform.html Quickbooks has a really nice culture according to their list :) 



# 06-11-2016

- https://en.wikipedia.org/wiki/Mariana_Trench deepest part of the oceans, -11km, 1000bars. James Cameron got there.
- http://www.slideshare.net/heidiannhoward/flexible-paxos-reaching-agreement-without-majorities "Flexible Paxos: Reaching agreement without majorities" I don't get everything, consensus logic is kinda complicated
- http://hal.upmc.fr/inria-00555588/document "A comprehensive study of Convergent and Commutative Replicated Data Types" CRDT. I'll read that later. (2011)
- https://github.com/chubin/wttr.in "curl wttr.in/Paris" to get the weather.
- http://www.ip2location.com/web-service ip to info: http://api.ip2location.com/?ip=216.58.208.206&key=demo&package=WS10
- http://blog.andrewlang.net/post/152805939304/tumblr-xss-exploit "xss is a feature, not a bug!" ;-)
- https://blog.risingstack.com/node-js-at-scale-understanding-node-js-event-loop/ microtasks and macrotasks quickly explained
- https://www.youtube.com/watch?v=uQ1zhJHclvs Andre Staltz nice talk where he "recreates" a tiny RxJS 
- https://www.mturk.com/mturk/welcome Have a remote workforce to do "human" stuff for you and rewards them. Uh, like a job.
- http://tryhaskell.org/ I Know Haskell
- http://underscore.io/blog/posts/2015/04/14/free-monads-are-simple.html wanted to learn more about Free Monads but err, too much scalaz still. One day.
- http://underscore.io/blog/posts/2015/11/09/sbt-commands.html Useful non-basic tricks in sbt
- https://zapier.com/app/explore Zapier looks useful when it comes to join 2 apps. The connectors list is quite impressive.
- https://zapier.com/learn/the-ultimate-guide-to-remote-working/ Wanna create/work in a remote company? Read this.
- https://slackhq.com/slack-101-onboarding-247454704155 How tu use Slack, by Slack
- https://blog.madewithenvy.com/getting-started-with-webpack-2-ed2b86c68783 Clear startup guide about webpack (2)
- https://github.com/LeadDyno/intercooler-js lean idea. we have `<a href="..">` why not post? `<button ic-post-to="/there">` with misc attrs to alter the payload.
- https://facebook.github.io/react/contributing/codebase-overview.html Some nice notes about how react codebase is structured. Tried to read the implementation notes but eh, too specialized for me, i don't need to know.!
- http://www.ibm.com/developerworks/java/library/j-jtp05236/index.html Great article about thread interruption in Java

# 05-11-2016

- https://webpack.js.org/ new website for webpack (original is https://webpack.github.io/)
- https://www.ampproject.org/ AMP Project. Definitely something to use when developing a mobile (or not only mobile i guess) webapp. Rules and constraints to make the pages ultra fast.
- https://www.youtube.com/watch?v=cfekj564rs0 How AMP achieves its speed - Google I/O 2016
- https://en.wikipedia.org/wiki/List_of_child_prodigies Another world. "built ... a nuclear fusion reactor at age 14"
- https://www.youtube.com/watch?v=kq3FopGY6Fc Tanishq Abraham at a TED talk. "By the age of 9 years, he became the youngest to attend and speak at a NASA conference"
- http://blog.arungupta.me/docker-container-anti-patterns/ Some classic things to do/avoid when using Docker
- https://github.com/turbo/js to do fast massive parallel numeric computing, one should use turbojs in a webworker (it uses GLSL,OpenGL Shading Language, GPU oriented!)
- https://m.signalvnoise.com/lets-chart-stop-those-lying-line-charts-60020e299829 spline charts are lying
- https://github.com/Jasonette/JASONETTE-iOS create a native app just with json, no code. cool stuff !
- https://gist.github.com/chtefi/7c9d287c19d69cea18e3ec70a1f6cfaa i wanted to understand a bit more "switchMap" in Rx.
- http://thedailywtf.com/articles/the-inner-json-effect A funny story about some weird crappy enterprise framework "JDSL" using SVN to do shit. Whatever. WTF.
- http://leaverou.github.io/contrast-ratio/ know your color contrast ratio (text vs background) and ensure you got >=AA (WCAG)
- http://jgthms.com/web-design-in-4-minutes/ nice demo page going to "just text" to a "full" styled body step by step
- http://blog.cloudera.com/blog/2016/09/apache-spark-2-0-beta-now-available-for-cdh/ Oh nice, I didn't noticed! No more need of a custom install
- https://issues.apache.org/jira/browse/AMBARI-17981 Druid is coming to Ambari. Come on Cloudera!
- https://www.kickstarter.com/projects/2029950924/holovect-holographic-vector-display Very cool, but we can see it comes with big constraints too
- https://medium.freecodecamp.com/what-programming-language-should-i-learn-first-ʇdıɹɔsɐʌɐɾ-ɹǝʍsuɐ-19a33b0a467d javascript he said, even if it's all quirky
- https://en.wikipedia.org/wiki/Malbolge Nice intro: "Malbolge was so difficult to understand when it arrived that it took two years for the first Malbolge program to appear. Indeed, the author himself has never written a single Malbolge program. The first program was not written by a human being" 
- https://medium.com/swlh/the-unintended-ways-self-driving-cars-will-change-our-world-3b15d1db9026 self driving cars will save us
- https://knox.apache.org/ "REST API Gateway for interacting with Apache Hadoop clusters." didn't really understood its usage. I guess it's because I'm not used to hadoop security
- http://openjdk.java.net/jeps/260 "JEP 260: Encapsulate Most Internal APIs" except ultra used APIs such as sun.misc.Unsafe, sun.misc.Cleaner for nio direct buffers mem cleanup
- https://building.coursera.org/blog/2014/02/18/why-we-love-scala-at-coursera/ Coursera is using Scala and Play Framework more and more
- https://jaxenter.com/wp-content/uploads/2016/10/JAX-Magazine-5.16.pdf jaxmagazine, talking about reactive programming, scala, lagom, microservices, akka

# 04-11-2016

- https://github.com/flumedb/flumedb another flume. A DB based on Observables.
- https://deepmind.com/blog/deepmind-and-blizzard-release-starcraft-ii-ai-research-environment/ Starcraft 2 as a deep learning playground, awesome future
- http://tothestars.io/blog/2016/11/2/serverless-mapreduce i never used aws lambda, seems nice to scale a map-reduce (hence the "serverless" part) in python here. And a reference architecture "biglambda". https://github.com/awslabs/lambda-refarch-mapreduce
- https://medium.com/@elliotjaystocks/one-week-with-the-google-pixel-f43e6647906f iPhone to Pixel. He doesn't regret it it seems, despite some lacks.
- https://sidbala.com/h-264-is-magic/ a few h264 tricks explained using simple comparaisons (quantization (remove details), Chroma Subsampling (simplify colors), Motion compensation (save delta only), Entropy Coder (generic compression algo))
- http://www.slideshare.net/JiangjieQin/producer-performance-tuning-for-apache-kafka-63147600 Kafka Producer tuning, how-to find contention and tune the good parameters
- https://thehftguy.wordpress.com/2016/11/01/docker-in-production-an-history-of-failure/ ahah, rants against Docker and their "don't care about backwards-compat" policy and misc bugs. I didn't know Docker pushed a bad package in June 2016 that broke every docker installations ahah (https://github.com/docker/docker/issues/23203) 
- https://github.com/docker/distribution a Docker registry in a Docker image, quite meta (for private usage)
- https://github.com/drathier/stack-overflow-import `from stackoverflow import quick_sort` funny! someone will do it for javascript, for sure
- http://meowni.ca/posts/web-fonts/ a reminder: import webfonts asynchronously to avoid FOUC/FOIC. Anyway, test your pages by simulating a 2G connection for instance. Reduce the TTFP (Painting).
- https://sandstorm.io/news/2016-09-30-fiber-bomb-debugging-story TLDR: never monkey patch (especially Promises)
- https://softwaremill.com/kafka-streams-how-does-it-fit-stream-landscape/ kafka streams? use it for kafka to kafka :) otherwise reactive-kafka (akka-streams), or if sql/ml/graph spark streaming or flink

# 03-11-2016

- https://www.confluent.io/blog/confluent-contributions-to-the-apache-kafka-client-ecosystem Kafka has a ton of client in a lots of language, not all of them are of the best quality. Confluent tries to base them on the best client: librdkafka in C
- https://www.lightbend.com/blog/scala-2-12-released Scala 2.12! Scala 2.12! Moar java8 compabitility and optimization integrated in scalac (lambda bytecode)
- https://techcrunch.com/2016/11/02/linkedin-plots-a-place-on-the-economic-graph-launches-salary-to-chart-what-we-earn/ that's going to be depressing? France is not even in the list for now.
- http://bestof.js.org/tags/framework/trending/this-month discovered this website ranking github repos per stars/day
- http://meta.stackoverflow.com/questions/313960/introducing-the-developer-story didn't know this was a thing. it seems ppl didn't liked it. me neither. linkedin baby.
- https://www.confluent.io/blog/bloglog-compaction-highlights-in-the-apache-kafka-and-stream-processing-community-november-2016/ update to kafka. to most notable being a special delete flag instead of a (key,null) to remove a record (on compaction)
- https://medium.com/the-hoard/how-kafkas-storage-internals-work-3a29b02e026 quick and clean. Kafka's storage quickly explained. And basically, zero-copy is the thing that allows Kafka to be ultra fast.
- http://www.javaslang.io/ a Java a bit more scala-ish also. Less .stream() crap, a true Option<>, Try<>, some pattern matching api
- https://github.com/skatejs/skatejs web component library. Incremental DOM. 4k mingz.
- https://www.pathwright.com/two some long vertical scroll page with tons of smooth controls animations (using tweens https://github.com/gilbox/react-imation)
- https://github.com/nodejs/readable-stream/pull/238 a debate to know if the licence to copy a js one-liner should be kept. ehm
- http://www.slideshare.net/Odersky/implementing-higherkinded-types-in-dotty slides from martin odersky. too complicated for me :D
- http://www.lottejackson.com/learning/supports-will-change-your-life @supports in css to avoid using Modernizr and js for css feature detection
- http://www.cyberciti.biz/faq/linux-tcp-tuning/ Some network tuning with linux kernels. Will be useful, maybe one day.
- https://www.infoq.com/presentations/akka-streams akka-streams by Viktor Klang

# 02-11-2016

- http://blog.bugreplay.com/post/152579164219/pornhubdodgesadblockersusingwebsockets as the title says: "pornhub dodges adblockers using websockets" extensions can't intercept websocket traffic (for now), so it sends the base64 of the image. But it seems adblockers found some tricks to block them anyway. (wrapping WebSocket api)
- https://www.bugreplay.com/ Nice thing to save a browsing session (requests/responses, javascript, console) and share it for other ppl to replay and check what's going on
- https://vimeo.com/189901272 Piper by Pixar. Beautiful 6:06.
- https://swizec.com/blog/a-tiny-es6-fetch-wrapper/swizec/7177 meh, a tiny wrapper to fetch to convert a object to a FormData.. yeah.
- https://facebook.github.io/react/contributing/implementation-notes.html Long page with lots of code snippets to explain React's internal. I'll read it carefully later. ;)
- https://articles.microservices.com/microservices-the-accidental-architecture-926e6d8762c1 Splitting a monolith to microservices success story
- https://articles.microservices.com/scaling-up-microservices-with-nio-and-simplereact-b2e8f41fdd68 AOL released SimpleReact (cyclops-react)
- http://cyclops-react.io/ Avoid low level threading in Java. Scalable and performant asynchronous non-blocking streams. When using IO apis, the Java8 stream.parallel looks completely useless compared to this. https://github.com/aol/cyclops-react/issues/67 40000ms to 97ms.
- https://github.com/hrldcpr/pcollections better immutable and persistent collections for Java8, à la Scala..! Better use Scala then eh
- https://github.com/jOOQ/jOOL tupleN, FunctionN, Seq, unchecked streams for Java8
- http://stackoverflow.com/questions/6155951/whats-the-difference-between-deadlock-and-livelock Deadlock ok. Livelock? A deadlock where threads are alive but continuously block each other, are released, and do the same blocking later, over and over.
- https://github.com/ScalaWilliam/git-watch react a push on a github/bitbucket repo, without anything to do except start a program
- https://github.com/fabienbk/pixi-scala-js pixi in scalajs, nice! remind me of Phaser, to develop webgames.
- http://stackoverflow.com/questions/5598085/where-does-scala-look-for-implicits A complete answer to what types of implicits do exist in Scala and how are they resolved
- https://github.com/ensime/ensime-sublime Definitely must use Ensime to enjoy Scala with SublimeText 3
- http://www.niemanlab.org/2016/10/slate-and-the-new-yorker-dump-outbrain-and-taboola-links-but-way-more-publishers-still-use-them/ Finally, dumping some crappy ads
- https://techcrunch.com/2016/11/02/microsoft-teams/ Microsoft Teams, aka Slack competitor
- https://github.com/UKHomeOffice/posters/tree/master/accessibility Some "posters" about accessibility best practices
- https://blog.chromium.org/2016/10/making-chrome-on-windows-faster-with-pgo.html Chrome way faster thanks to Microsoft PGO technology, that enhances the binary by optimizing hotspots and uncaching "coldspots"
- https://concept.research.microsoft.com/Home/Introduction impressive project by Microsoft. Associate appropriate concepts to words and sentences
- https://medium.com/@sachagreif/a-study-plan-to-cure-javascript-fatigue-8ad3a54f2eb1 for newcomers, tldr
- https://journal.designinc.com/how-to-make-a-logo-for-free-in-about-5-minutes-a4f409176a8e Now I know how to make a logo in 5min B)

# 01-11-2016

- http://v8project.blogspot.fr/2016/10/webassembly-browser-preview.html webassembly on the road
- http://webassembly.org/demo/ let's give a try (still the ooold demo)
- out

# 31-10-2016

- https://medium.com/charged-tech/apple-just-told-the-world-it-has-no-idea-who-the-mac-is-for-722a2438389b A trending medium that shows Apple is lost.
- http://mashable.com/2016/10/27/microsoft-better-apple Microsoft innovates more than Apple those days
- https://uxplanet.org/pull-to-refresh-ui-pattern-42a85f671cdf pull-to-refresh ui pattern, when to use, when to not use
- https://vanwilgenburg.wordpress.com/2015/10/06/spark-streaming-backpressure/ This is not a true back-pressure.
- https://medium.freecodecamp.com/seo-vs-react-is-it-neccessary-to-render-react-pages-in-the-backend-74ce5015c0c9 Google can index SPA not even rendered server-side, he's a smart cookie.
- http://www.slideshare.net/kpciesielski/reactive-kafka-with-akka-streams Really good slides about akka-streams-kafka (api has already changed since but well..)
- https://blog.minocacorp.com/minoca-os-a-new-open-source-operating-system-4bb7998df3a7 An OS from scratch, trying some new philosophies, compatible with existing tools, POSIX
- https://github.com/minoca/os Its repo
- https://www.cnet.com/special-reports/jony-ive-talks-about-putting-the-apple-touch-on-the-macbook-pro/ Fucking crazy 120MB of content page. Nuts.
- https://github.com/sgoeschl/java-image-processing-survival-guide Nice slides about Java image processing libs userland. Magick (crappy, old, JNI unmaintained), and TwelveMonkeys (extensions to Java ImageIO)
- http://blog.mgechev.com/2016/08/14/ahead-of-time-compilation-angular-offline-precompilation/ Angular 2's AOT. Basically html to js. :D
- https://github.com/ReactiveX/RxJava/wiki/What's-different-in-2.0 Compliance to reactive-streams spec
- https://github.com/akka/reactive-kafka/blob/master/OLD_README.md When you use a kafka 0.9 broker, you can't use akka-stream-kafka but need to use an old version when it was still under com.softwaremill.reactivekafka :(

# 30-10-2016

- http://blog.akka.io/integrations/2016/08/23/intro-alpakka Akka Streams is going Camel.
- http://www.latimes.com/business/technology/la-fi-tn-soylent-recall-20161027-story.html The famous Soylent having trouble with some of its products.
- http://blog.fosketts.net/2016/10/29/total-nightmare-usb-c-thunderbolt-3/ USB-C and Thunderbolt 3 complex issues about compabitility. Scary.
- https://medium.com/i-m-h-o/dont-go-to-art-school-138c5efd45e9 $245,816 = 4y art school cost
- https://www.kernel.org/pub/software/scm/git/docs/giteveryday.html Kernel ppl don't use git as we do (email, signatures..)
- https://www.google.com/doodles/halloween-2016 their halloween doodle game is very great :)
- https://github.com/rijs/examples/tree/master/10000-modules  benchmarking importing module (<link rel="import" href="xxx.html">). They are very slow. But Ripple is way faster.
- https://github.com/rijs/fullstack this is Ripple "Ripple is a set of simple modules that compose to form a modular framework. "
- https://github.com/facebookincubator/create-react-app/pull/898 yarn being added to create-react-app 
- http://williampross.com/became-hackerrank-1-two-hours/ ahah, just copied/pasted the answer from the comments, gg.
- https://github.com/VoLuong/Master-Latex-in-minutes Straight to the point!
- http://www.nextplatform.com/2016/10/10/memory-next-platform/ Doing computation directly in the memory. Hybrid memory cube HMC. Faster, less consuming.
- http://www.nextplatform.com/2016/09/07/next-wave-deep-learning-architectures/ Intel buying companies interested in Deep learning, don't want to miss the turn.
- https://medium.com/google-cloud/15-awesome-things-you-probably-didnt-know-about-google-bigquery-6654841fa2dc Interesting compilation. BigQuery: secured, concurrency resilient (with the famous Redshift #22 comparaison, ahah), "small" cost, self-optimizing, HA, cached queries (reduces cost), Batch, Streaming, Sharing, Scale.
- https://thoughts.t37.net/abusing-an-innocent-elasticsearch-cluster-for-a-mass-reindex-without-disturbing-your-clients-360384fca105 A log post about they architectured their elasticsearch clusters to reindex massive amount of data without disturbing clients
- https://blog.netsil.com/a-comparison-of-time-series-databases-and-netsils-use-of-druid-db805d471206 Netsil powered by Druid. They compared with other solution (cass, opentsdb, influx, ES..). It's an Infrastructure monitoring and alerting platform, for devops and SREs.
- http://www.warp10.io/introduction/platform/ not sure what i am looking at. A platform to collect, store, and manipulate sensor data. Not very well explained, lots of stuff.
- https://docs.google.com/presentation/d/1Gf790m27NNAGOGjNwjpQb7LXM2ZDVJvkPXNk6duVNEg "Bref, j'ai essayé de faire du reactive kafka" avec akka-streams. Préz sympa en fr (passée à la scalaio?)
- https://medium.com/@kvnwbbr/diving-into-akka-streams-2770b3aeabb0 Nice intro to akka-streams
- https://medium.com/reactive-programming/what-is-reactive-programming-bc9fa7f4a7fc Just remember: Responsive -> Resilient + Scalable -> Message Driven
- https://medium.com/@kvnwbbr/a-journey-into-reactive-streams-5ee2a9cd7e29 Nice recap with some akka-streams example about Reactive Streams spec

# 29-10-2016

- https://vivatiffany.wordpress.com/2016/10/27/academia-love-me-back/ "This is not your word". All that because she used the word "hence" in her essay. I had no idea it was a "high-quality" word.
- https://github.com/ptmt/react-native-touchbar it begins!
- https://github.com/alexjc/neural-enhance impressive. do CSI picture enhancer. in real. thanks to neural network.
- https://www.youtube.com/watch?v=LhF_56SxrGk "Let's Enhance" Love this clip :)
- https://www.html5rocks.com/en/tutorials/security/content-security-policy/ Good recap about Content-Security-Policy
- http://twitter.github.io/heron/ A realtime, distributed, fault-tolerant stream processing engine from Twitter
- http://www.xebia.fr/data/techtrends/techtrends-xebia-craft.pdf Craftsmanship movement
- http://www.confluent.io/blog/apache-flink-apache-kafka-streams-comparison-guideline-users/ Flink: cluster based, KafkaStreams: microservice (standalone app)
- https://groups.google.com/forum/m/#!topic/golang-dev/Ab1sFeoZg_8 Go is going to get &lt;100 microseconds worst-cases STW gc. Nothing more.
- http://blog.akka.io/integrations/2016/08/23/intro-alpakka Akka Streams is going Camel.

# 28-10-2016

- https://icon.now.sh/ link to svgs icon (+1200!) with custom color, size, direction. Really cool. But.. SLA ?
- https://github.com/blog/2273-incident-report-inadvertent-private-repository-disclosure "... error that resulted in a small number of Git requests retrieving data from the wrong repositories." WTF
- https://zeit.co/blog/now-static "now" now determines if it publishes a static website (show the list of files using zeit list) or an app
- https://www.reddit.com/r/javascript/comments/59tbl3/very_strange_line_in_some_code_could_someone_help/ TIL parseInt(n, 0) assumes the radix depends on n. ("0x..", "0..")
- https://en.wikipedia.org/wiki/Four_color_theorem WOW, such theorem, wow. "Given any separation of a plane into contiguous regions, ..., no more than four colors are required to color the regions of the map so that no two adjacent regions have the same color." Proven by a computer.
- https://github.com/facebook/react/issues/7942 more details about React Fiber. I still have no idea what's going except a "full" revamp of React?
- http://programming.witheve.com/ "Eve: Programming designed for humans" Some... sorcery is going on. WHAT? "An IDE like Medium" "search @system [#memory available] available < 200 * 1024 * 1024"
- http://www.lesnumeriques.com/ordinateur-portable/nouveaux-macbook-pro-touch-bar-touch-id-toujours-plus-fins-n56943.html Les nouveaux mbp &lt;3 sauf le prix.
- https://blog.devteam.space/new-macbook-pro-is-not-a-laptop-for-developers-anymore-d0d4b1b8b7de No escape, no more than 16GB. blah.
- https://research.googleblog.com/2016/10/supercharging-style-transfer.html I find this totally crazy and awesome. A neural network that learned how to merge different pictures styles
- https://github.com/systemjs/systemjs/blob/master/docs/module-formats.md esm, cjs, amd, global, System modules explained

# 27-10-2016

- http://www.bbc.com/news/technology-37788052 Bye bye Vine!
- https://youtu.be/6m_E-mC0y3Y using lighthouse to measure page perf (differents metrics). Measure (performance.mark/measure, and look into the flame chart, "User Timing"), Profile (Chrome Debugger), Diagnose, Identify, Attempt.
- https://docs.npmjs.com/getting-started/scoped-packages I never published scoped packages "@toto/core"
- http://www.catb.org/esr/faqs/hacker-howto.html ahah, i like that: "Hacker: How To"
- http://openjdk.java.net/jeps/295 AOT in Java9, so cool ! only for java.base for now, but will extend to anything later. Compile with a new tool: "jaotc", then add it to the "AOT classpath": "java -XX:AOTLibrary=./libHelloWorld.so HelloWorld"
- http://www.history.com/news/9-things-you-may-not-know-about-the-pentagon 2min video about the Pentagon structure, "good" to know
- https://aws.amazon.com/fr/blogs/big-data/fact-or-fiction-google-big-query-outperforms-amazon-redshift-as-an-enterprise-data-warehouse/ TLDR BigQuery < RedShift (and is more predictable, and is SQL ANSI compliant, BigQuery is not)
- https://betterhumans.coach.me/cognitive-bias-cheat-sheet-55a472476b18 Our brain is lazy and not focused.
- https://web-animations.github.io/web-animations-demos/#expandoboard/ Web Animations API is very great. Was totally unaware of this thing.. or I forgot! same result.
- http://blog.octo.com/analyse-predictive-en-temps-reel-machine-learning-avec-storm-et-scikit-learn/ Sometimes, going back to older system is interesting, here, Storm!
- http://blog.octo.com/kafka-streams-encore-un-framework-de-stream-processing/ Some explanations how Kafka Streaming is working, with examples
- https://www.indiehackers.com/businesses/instapainting interesting, and to bookmark! the story of a guy who did instapainting. how did he, what would he would have done differently etc.

# 26-10-2016

- https://cors.now.sh/ Public reverse-proxy to add CORS on any url (https://cors.now.sh/&lt;url&gt;)
- https://www.microsoft.com/en-us/surface/devices/surface-studio/surface-studio this is some serious "PC" by Microsoft, for designers mostly. $2,999 at least.
- https://medium.freecodecamp.com/what-i-learned-from-reading-the-redux-source-code-836793a48768 Ultra basic. Basically, some tips to write better code.
- https://medium.freecodecamp.com/three-ways-to-return-largest-numbers-in-arrays-in-javascript-5d977baa80a1 for, reduce, or math.max. 
- https://github.com/staltz/comver semver without Patch. (ie: MAJOR.MINOR) to speak only about backward-compat. For some reasons, that does not interest me. It's for people that does not know how to use semver and determine what the version they should increase. Good for them. But clearly, that simplifies the versioning if you don't care about communication of fixes.
- http://slides.com/vanessayuenn/augury-ngeurope ok, angury is the equivalent of the react chrome extension.
- https://medium.com/@bartobri/applying-the-linus-tarvolds-good-taste-coding-requirement-99749f37684a good point: the less conditions, the better the code. BUT, good points in comments: beware of cache misses.
- http://seriot.ch/parsing_json.html As the title says: "parsing json is a minefield". Every parsers has its own set of "extensions" and does not respect the full json specs (because the specS themselves are messy and contradictory).
- https://ateev.in/react-js-achieving-20ms-server-response-time-with-server-side-rendering-1ea80e420d88 lol, ok, basically, put Redis for the API (and deal with cache invalidation)
- http://www.confluent.io/blog/unifying-stream-processing-and-interactive-queries-in-apache-kafka/ this is so great. kafka streams with querying logic. The example is a bit complex to handle. (https://github.com/confluentinc/examples/tree/master/kafka-streams/src/main/java/io/confluent/examples/streams/interactivequeries/kafkamusic) Using Jersey &lt;3
- https://github.com/ogirardot/typesafe-kafka-streams Scala-like compatible KStreams &lt;3
- https://www.lightbend.com/lagom Framework to simplify (a lot) the management and deployment of microservices (handle the persistence part, the links between then, and the async communication between them)

# 25-10-2016

- http://faehnri.ch/have-fun/ "main(){printf(&unix["\021%six\012\0"], (unix)["have"]+"fun"-0x60);}" output:"unix". "A lot to unpack from such little code, and plenty to learn."
- https://www.bloomberg.com/news/articles/2016-10-25/twitter-said-to-plan-hundreds-more-job-cuts-as-soon-as-this-week That sucks.
- https://zeit.co/blog/next hmm a bit like create-react-app (handle libs, nothing to set up), except you just write components, and you have way more features (hr, ssr, code splitting, css in js, add a new method "async getInitialProps({res})")
- https://www.youtube.com/watch?v=HeLbtltuB5g&app=desktop Man get sucked into jet engine. and survived.
- http://slatestarcodex.com/ i dont know. "AI PERSUASION EXPERIMENT RESULTS"
- http://www.theuselessweb.com/ i got trapped
- https://en.wikipedia.org/wiki/Wikipedia:Unusual_articles come on, again
- https://github.com/threepointone/glamor seems like an excellent css in js lib
- https://www.propublica.org/article/google-has-quietly-dropped-ban-on-personally-identifiable-web-tracking bigbro is in da place. https://myactivity.google.com/myactivity

# 24-10-2016

- http://spacedashboard.com/ This is what a live dashboard is. Btw: "people in space: 8".
- https://www.theearthawaits.com/ 600 cities across the world. A budget. Different filters. Awesome beautiful website.
- https://www.exploratorium.edu/blogs/tangents/we-got-phished-2 A nice story about being phished
- https://killscreen.com/articles/doom-map-300-hours-make/ Love this game.
- https://www.madewithtea.com/released-mocked-streams-for-apache-kafka.html Testing Kafka Streams without Kafka broker nor Zookeeper
- https://github.com/blog/2268-top-open-source-launches-on-github That's tiptop. I was not aware of some of the top 10 best-star-in-one-week projects, such as anime.js
- http://anime-js.com/ awesome animation lightweight lib in JS
- http://www.bbc.com/news/technology-33442419 17yo and already so many hacking behind him, credit card frauds, he will definitely be hired by some security companies.
- https://github.com/npm/npm/releases/tag/v4.0.0 Lots of breaking changes. No talking about yarn, ahah "We're planning a major overhaul of shrinkwrap"
- http://hub.dyn.com/static/hub.dyn.com/dyn-blog/dyn-statement-on-10-21-2016-ddos-attack.html 10 millions of IPs
- http://urlex.org/ Unshorten bit.ly and other t.co shortlinks
- https://hostpresto.com/community/tutorials/netstat-command-line-tips-and-tricks/ a small sample of useful commands in netstat
- http://linux.w3clan.com/tutorial/164/deadly-commands   :(){ :|: & };:
- https://blog.imirhil.fr/2016/10/09/docker-container-hell.html Une critique des problèmes de sécurité induits par l'utilisation de Docker en production (firewall, log monitoring, updates de sécurité..)
- https://www.elie.net/blog/security/fuller-house-exposing-high-end-poker-cheating-devices Poker advanced cheating devices, impressive
- https://databricks.gitbooks.io/databricks-spark-reference-applications/content/index.html I had this bookmarked since ages. Beginner guide to Spark. In Java, erk.

# 23-10-2016

- http://unix.stackexchange.com/questions/113544/interpret-the-output-of-lstopo Nice answer about how interpret the lstopo output (create a drawing of the physical layout of the server)
- http://www.brendangregg.com/linuxperf.html A tons of good stuff about the performance in Linux
- http://beingindian.com/news/gurgaon-prisoner-techie/ a prisoner created a software in prison to help manage the prison. Woo.
- https://sites.google.com/site/steveyegge2/you-should-write-blogs The reasons why You Should Write Blogs
- http://danluu.com/hn-comments/ Useful HN comments (often barely unseen but containing useful intel) a guy curated
- http://www.economist.com/news/business/21709061-entrepreneurs-finances-are-jaw-dropping-inventive-and-combustible-his-space The situation of Musk's assets and company is a bit risky, debts.
- https://vimgifs.com/ ok, it's like a super useful website to have to know how to use vi. a command = an animated gif and desc.
- http://ctheu.com/2016/10/23/are-you-up-to-date/ I wrote that
- https://medium.com/@ChtefiD/are-you-up-to-date-7e4ebc10e61c And copied it here because.. medium.
- https://medium.freecodecamp.com/how-to-launch-an-effective-landing-page-for-your-project-f15bf3433d16 How to do a good Landing page? Landing page = converter. Marketing first before developing anything (except the landing page!). User registering? Do a MVP. Answer to a need, to a existing difficulty. Follow the given layout.
- https://github.com/coreos/etcd etcd is a distributed, consistent key-value store for shared configuration and service discovery. (Go,  gRPCn, Raft) Can be used instead of ZK for instance.
- https://github.com/osrg/namazu Namazu is like a Chaos Monkey, more low level. "permutes Java function calls, Ethernet packets, Filesystem events, and injected faults in various orders" .. OK !
- https://en.wikipedia.org/wiki/Spanner_(database) Spanner is Google's globally distributed NewSQL database. F1 is the DBMS on top.
- https://en.wikipedia.org/wiki/NewSQL Relational data model and use SQL. But are scalable like NoSQL db, shared-nothing nodes, sharded. (and still (multi-tables) ACID, consistency, transactional, indexes, joins, what missed in NoSQL). Spanner is one. CockroachDB is another. NuoDB too. TiDB also it seems.

# 22-10-2016

- https://en.wikipedia.org/wiki/Verilog A hardware description language used to model electronic system. Converted to circuit! "... 'wire' consists of both signal values (4-state: "1, 0, floating, undefined") and signal strengths (strong, weak, etc.)"
- https://krebsonsecurity.com/2016/10/hacked-cameras-dvrs-powered-todays-massive-internet-outage/ "... obscure, less user-friendly communications services called “Telnet” and “SSH.”" ahah! The malware "Mirai" source code has been released in september. Same that causes the DDDoS.
- https://medium.com/@martinopietropoli/archillect-the-elegance-of-the-algorithm-f346f50c9ca0 I've been following Archillect for months, it's an amazing intelligence.
- https://medium.com/google-cloud/analyzing-go-code-with-bigquery-485c70c3b451 A cool analysis of all go code on github using BigQuery
- https://github.com/facebook/jsx/issues/65 JSX2.0, breaking changes. Cool syntax oriented.
- https://blog.acolyer.org/2016/05/03/gorilla-a-fast-scalable-in-memory-time-series-database/ Facebook have created Gorilla, a timeseries database on top of hbase. Very compression centric.
- https://github.com/jgamblin/Mirai-Source-Code The famous source-code of the malware used to DDoS
- https://www.opendns.com/setupguide/ Nameservers of OpenDNS 208.67.222.222 208.67.220.220 (it's using a cache if dns resolver is not available, like in case of an attack)
- https://support.opendns.com/hc/en-us/articles/227988627 Clean you DNS cache (ipconfig, dscacheutil, nscd, network-manager..)
- http://distributedlog.incubator.apache.org/technical-review/2015/09/19/kafka-vs-distributedlog Kafka vS DistributedLog (incubating, from Twitter)
- https://aphyr.com/posts/293-jepsen-kafka Jepsen test on Kafka 0.7.x Too bad it's too old! Now we can disable the unclean leader partition

# 21-10-2016

- https://backchannel.com/how-the-web-became-unreadable-a781ddc711b6 designers replaced black by gray for years. Some said we should go back to black to make things more readable.
- https://open_nsfw.gitlab.io/ Testing the nsfw deep model Yahoo opens one month ago
- https://github.com/nodejs/node/commit/d0edabecbf this is so bs. so many test and tricks just to test if 0<=n<=65535. Thanks Javascript and your dynamic types and your coercion.
- https://octoverse.github.com/ ok it's like SUPER INTERESTING :)
- http://www.nextinpact.com/news/101857-dyn-attaque-ddos-perturbe-acces-a-sites-importants-aux-etats-unis.htm DDNS attack against Dyn, lots of websites slow to be resolved in the US east cost only it seems.
- https://github.com/FormidableLabs/spectacle Spectable is just an awesome presentation library (powerpoint) using reactjs
- https://www.hyper.sh/ Automatic docker hosting using a CLI, but... 2 cores + 2GB RAM + 10GB disk = 21$/m. VPS on OVH: 2 cores+8GB RAM+40GB GB 12€/m. Meh.
- http://www.theregister.co.uk/2016/10/21/dns_devastation_as_dyn_dies_under_denialofservice_attack/ A nice article explaining the dns ddos
- http://www.bitwizard.nl/mtr/ http://mtr.guru/ Combine traceroute and ping and its online website to use :)
- https://jakearchibald.com/2016/performance-benefits-of-rel-noopener/ I forgot about this attr, now in mind again!
- https://www.chromestatus.com/features/6691520493125632 So PNG has a format APNG which is animated. Supported in Firefox and Safari only for now. Lighter than gif.
- http://mkuthan.github.io/blog/2016/09/30/spark-streaming-on-yarn/ Nice tips when starting Spark Streaming jobs on YARN (+ add custom monitoring)
- https://www.youtube.com/watch?v=_MAD4Oly9yg "Paul O Shannessy - Building React From Scratch" I didn't watched the whole thing. 20min to understand a tiny React framework, with already perf shortcuts inside, meh.
- https://www.youtube.com/watch?v=SfWR3dKnFIo Very interesting simple js example to go from ugly imperative style to functional, with @drboolean
- https://github.com/lukaszx0/queues.io "Job queues, message queues and other queues. Almost all of them in one place."

# 20-10-2016 

- http://stackoverflow.com/questions/37528047/how-are-stages-split-into-tasks-in-spark Spark
- https://databricks.com/blog/2015/06/22/understanding-your-spark-application-through-visualization.html Spark again, interesting to understand the UI
- https://github.com/JohnLangford/vowpal_wabbit/blob/master/java/ vowpal has JNI wrappers
- http://www.lesnumeriques.com/vie-du-net/cnil-cdiscount-averti-mis-en-demeure-pour-manquements-graves-n56759.html Cdiscount is not protecting its bank user infos (stored plain!), and more crazy shit
- https://blog.filippo.io/how-the-new-gmail-image-proxy-works-and-what-this-means-for-you/ When gmail renders an image, it actually rewrite the link and you go through some google proxy that send less info to the server
- http://www.nintendo.com/switch The Nintendo Switch! That's some nice new gaming system! You know why it's called Switch.
- https://01.org/sites/default/files/documentation/intel-gfx-prm-osrc-skl-vol16-workarounds_0.pdf I dunno. Twitter. 41 pages about Intel CPUs workarounds
- http://www.confluent.io/blog/announcing-apache-kafka-0-10-1-0/ Nice new features in Kafka 0.10.1.0 Time-based Search / Replication Quotas
- http://www.confluent.io/blog/event-sourcing-cqrs-stream-processing-apache-kafka-whats-connection/ Nice (but long) explanation of what is CQRS, and how to do that with KafkaStreams
- https://github.com/jrudolph/fast-interpolator Replace the scala string interpolator because it's slow. I never think of that
- http://arstechnica.com/security/2016/10/most-serious-linux-privilege-escalation-bug-ever-is-under-active-exploit A bug in all linux kernels exploited since 2009
- http://motherboard.vice.com/read/how-hackers-broke-into-john-podesta-and-colin-powells-gmail-accounts High-level phising against some US politics
- https://bitwarden.com/ store and sync passwords (free). Can't publish their extension on Firefox but Angular 1.x is ban, LOL
- https://tech.polyconseil.fr/code-your-js-app-like-its-86.html 


# 19-10-2016

- http://jsipsum.lunarlogic.io/ After lorem ipsum, bacon ipsum, cupcake ipsum, hipster ipsum, here is.. javascript ipsum! Nice touch
- https://en.wikipedia.org/wiki/Undefined_behavior C is full of undefined behaviors! `int f(){}; int i = f(); // UB !` but it's in every compiler (the language spec does not define explicitely certain behavior that are unexpected)
- http://techblog.netflix.com/2016/10/netflix-chaos-monkey-upgraded.html Chaos Monkey 2 release with less features than the previous one (CM2 just terminates instances now, before it could connect into host and play with the cpu, hdd, networks..), with a platform called Spinnaker.
- https://github.com/Netflix/chaosmonkey The repo! 16 commits. In Go. I never used Go yet.
- http://json-schema.org/examples.html JSON Schema is a spec to define the type of a JSON payload. Like xsd.
- https://github.com/epoberezkin/ajv Seems to be the most popular and fast
- https://developers.google.com/web/updates/2016/10/nic54 New In Chrome 54: Custom elements (!), BroadcastChannel API (talk to other tabs opened from another), foreign fetch (a fetch that could install its service worker, what?!)
- https://html.spec.whatwg.org/multipage/scripting.html#custom-elements The spec of custom elements
- https://www.sitepoint.com/yarn-vs-npm/ Some points about the differences between yarn and npm. yarn.lock is like npm shrinkwrap but automatically generated and updated when installing/updating deps; for a reproductible environment and no surprise
- https://yarnpkg.com/en/docs/cli/ All the commands (most similar to npm's)
- https://github.com/yarnpkg/yarn/blob/master/src/util/filter.js I looked what was the heuristic they used for "yarn clean". Strings.
- https://github.com/typestyle/typestyle CSS in JS with Typescript static checks
- https://medium.com/@nodejs/node-js-v6-transitions-to-lts-be7f18c17159 I hope nobody is still on node 0.10 or 0.12, it's been a while :)
- https://github.com/auchenberg/volkswagen Ahah nice joke, 5k stars! "Volkswagen detects when your tests are being run in a CI server, and makes them pass."
- https://gist.github.com/jlongster/6e2af5bb3ae3ab229cafab06efc724fc @jlongster thinking about local db syncness. Cool, a bit like CRDT.
- https://blog.oldgeekjobs.com/from-google-form-to-1000-in-revenue-in-one-month-3f5cd75b6089 what the hell, i'm not an old programmer, come on :-(
- http://aseigneurin.github.io/2016/10/07/kafka-streams-scaling-up-or-down.html Demonstrate the consumer group auto-rebalancing of kafka when consumers are added/removed when using Kafka Streams. Nothing fancy but well written.
- http://www.grpc.io/docs/guides/wire.html gRPC become popular for communication client/server. Use HTTP/2 + Protobuf.

# 18-10-2016

- http://maxwellito.github.io/vivus/ awesome js lib to live draw a svg when in viewport (for instance)
- https://www.berriart.com/blog/2016/10/npm-yarn-benchmark/ yarn (javascript) is definitely faster to install crap
- https://github.com/donnemartin/gitsome Tried on Windows, the commands are failing, too bad. Will try on OSX later.
- http://io.livecode.ch/learn/namin/unsound/scala The Java/Scala types system is broken :-(
- https://www.akkadia.org/drepper/cpumemory.pdf "What Every Programmer Should Know About Memory" 114 pages. Seems very good. For later.
- https://en.wikipedia.org/wiki/Configuration_management_database A repository that acts as a data warehouse for information technology (IT) installations. Excel counts?
- https://blog.risingstack.com/node-js-at-scale-module-system-commonjs-require/ Read in 10s tops.
- https://marco.org/2016/10/17/shame-on-y-combinator A Y-combinator partner invested in Trump. Making waves among the community.
- https://github.com/airbnb/kafkat kafkat! a easier CLI for kafka
- https://scotthelme.co.uk/alexa-top-1-million-crawl-aug-2016/ God. so many security headers to handle nowadays..
- https://github.com/chtefi/making-a-website I did that!

# 17-10-2016

- https://en.wikipedia.org/wiki/Backtesting "...testing a predictive model using existing historic data. Backtesting is a kind of retrodiction, and a special type of cross-validation applied to time series data."
- https://docs.docker.com/swarm/discovery/ when you run some dockers here and there, and you want your external services to access to them, without hardcoding ip:port, you can use swarm, that uses zk/etcd/consul
- https://gist.github.com/djspiewak/cb72c41ac335a3a9b28b3307be04aa43 "Getting Started in Scala". I learned about sbt-extras and ammonite :)
- http://www.lihaoyi.com/Ammonite/ Forget bash and use a Scala Gave a try to Ammonite-REPL
- http://www.inc.com/salvador-rodriguez/devschool-coding-bootcamps.html They paid 5000$ to learn coding from a dude. He vanished. Oops.
- https://www.sitepen.com/blog/2016/10/17/announcing-the-js-foundation/ Cool. javascript = jquery :troll:
- https://github.com/paulp/sbt-extras A better sbt script with features more easily accessible. It should be coded with ammonite :)
- http://www.lihaoyi.com/scalatags/ HTML/CSS in Scala without a stupid XML dsl but just with clear functions
- https://github.com/scalaj/scalaj-http A nice and clean http wrapper to make some calls
- https://www.javacodegeeks.com/2016/10/apache-camel-2-18-released-whats-included.html Camel passed to Java8, more Spring Boot compat, a better doc, Hystrix, 
- http://johnzon.apache.org/ Didn't know this one. Implements JSR-353, for JSON processing ("can" replace Jackson).
- https://jsonp.java.net/ Details of the JSR-353 Java API for JSON Processing
- https://github.com/apache/camel/tree/master/examples Camel has a bunch of useful examples (not all camel components have an example)
- https://en.wikipedia.org/wiki/White-box_testing Use white box testing to test infra, pipelines (not business)

# 16-10-2016

- http://gun.js.org/ A resilient decentralized realtime graph database for the web (nice landing page!)
- https://github.com/attic-labs/noms A document graph git oriented database
- http://www.datomic.com/ "The fully transactional, cloud-ready, distributed database." used by Netflix, Facebook, should be nice no? Ensure immutability, versioning, history. 
- http://gun.js.org/ A resilient decentralized realtime graph database for the web (nice landing page!), but seems to have a lot of problems, and the js code looks crappy
- https://github.com/attic-labs/noms A document graph git oriented database
- http://www.datomic.com/ "The fully transactional, cloud-ready, distributed database." used by Netflix, Facebook, should be nice no? Ensure immutability, versioning, history. 
- https://fabiomsr.github.io/from-java-to-kotlin/ Didn't work with Kotlin yet. Nice slick syntax comparaison page with Java. I can feel a lot of Scala in there, love it :)
- https://en.wikipedia.org/wiki/X86_virtualization A lots of technical terms. AMD-V / VT-x (Intel) virtualization cpu instructions in all cpus now. IOMMU (PCI passthrough) (AMD-Vi/VT-d) allows the VMs to access host connected physical devices (input/output memory management unit)
- http://blog.scottlowe.org/2009/12/02/what-is-sr-iov/ SR-IOV Single-root input/output virtualization. Share the same physical PCIe device to multiple VMs
- http://www.vfrank.org/2013/09/18/understanding-vmware-ballooning/ VMware ballooning is when the host system wants to retrieve physical memory given to the vm (through the hypervisor). 
- https://github.com/datproject/dat easy p2p sharing of folder with a simple CLI (or desktop app), using webRTC. I like.
- https://shop.keyboard.io/ Maybe. Or not. ($300)
- https://vimeo.com/113707214 Railroad oriented programming: Error handling in functional languages. Basically, use Either\[Throwable, Result\] (2 tracks) and compose your functions. Really good analogy and talk.
- https://vimeo.com/113703576 Introduction to redis
- https://github.com/lihaoyi/scala.rx Like RxScala, less popular
- http://docs.scala-lang.org/tutorials/FAQ/breakout.html What is breakOut, and how does it work? It's a good thing to know it exists, saves you useless processing
- http://www.lihaoyi.com/post/BenchmarkingScalaCollections.html Memory and Performance of the Scala Collections. Very interesting. Arrays of primitive and Lists (linked list) are cool. Maps and Sets are damn slow.
- https://groups.google.com/forum/#!topic/scala-internals/r2GnzCFc3TY He raised good point. The Scala documentation / website cluster, could be clearly improved (Scala Native, ScalaJS, Scala Android..) and be more beginner friendly.
- http://scala-lang.org/blog/2016/10/14/dotty-errors.html Dotty is going to be a great Scala compiler. elm-ish compiler human error messages please.
- http://www.martinfowler.com/articles/injection.html An old post of Martin Fowler I've never read. IoC => Dependency Injection. An "assembler": the service that fulfill dependencies. 3 types of IoC: Interface Injection, Setter Injection, Constructor Injection. Another pattern is the Service Locator (basically, a class Registry (singleton or not) where you load or ask for an implementation). Both patterns can be mixed. With the Locator, every classes needs a reference to a Locator. With IoC, there is no such thing, it's completely invisible. XML sucks.
- http://www.martinfowler.com/articles/mocksArentStubs.html Dummy: just used to fulfill params. Fake: A fully functional alternative, not suitable for prod (eg: an in-memory db). Stub: just some methods are set to return something. Mock: used to verify methods have been called (.expected.to.be.called.once), and can set the result.
- https://www.youtube.com/watch?v=wgdBVIX9ifA Monolith: Simplicity, Consistency, Refactoring. Microservices: Partial Deployment, Availability, Preserve modularity, Multiple platform (languages) BUT need monitoring, CI/CD, devops culture

# 15-10-2016

- https://medium.com/@boennemann/avoid-yarn-for-packages-and-fully-enjoy-its-benefits-for-application-development-8bdd4deb33cf An example of why yarn can lead to unexpected behavior
- https://medium.com/@boennemann/questions-i-wish-yarn-had-answered-on-day-1-ec0db7458107 questions questions. why should we use yarn, what are the trade-offs, why is that so different of npm?
- https://www.briangilham.com/blog/2016/10/10/be-kind Short "novel" about being kind even when ppl messed up, to let the grow
- https://www.youtube.com/watch?v=sR76PfL2KRw Svetlana Kapanina aerobatics cockpit view. omg. Stunning.
- https://slack.engineering/taking-php-seriously-cf7a60065329 Hack on HHVM instead of plain ol' PHP is must better nowadays (Facebook, Wikipedia, Slack..)
- http://www.npr.org/sections/alltechconsidered/2016/10/13/497820170/the-man-who-stood-up-to-facebook A startup "Power Ventures", a third-party platform, collected user information from Facebook and displayed it on their own website. Facebook didn't like that.
- http://lemire.me/blog/2016/10/14/intel-will-add-deep-learning-instructions-to-its-processors/ People are using Nvidia graphics procs to run deep-learning nowadays. But Intel is coming with a special set of instructions for CPUs!
- https://github.com/naptha/tesseract.js OCR in Javascript. Pretty sure I will never use it but we never know.
- https://medium.com/walmartlabs/using-electrode-to-improve-react-server-side-render-performance-by-up-to-70-e43f9494eb8b Big React SSR speed enhancements using Electrode (noticeable optim: "above the fold only": render only what's visible to the user)
- https://medium.com/@lestrrat/wtf-was-wrong-with-my-go-code-a025fa7563c I find the Go syntax to suck sometimes.
- https://github.com/jsdnxx/graphql-schema-version this raises an important issue: backward and forward graphql schema compability
- http://zty.pe/ Why ppl are sharing this on Twitter ? Lost countless minutes playing at that game ;-)
- https://medium.com/swlh/how-our-app-went-from-20-000-day-to-2-day-in-revenue-d6892a2801bf I don't care at all about emojis keyboard FFS. Dumb crap. The best keyboard is Switfkey because it's really useful as virtual keyboard. That's it.
- https://medium.com/node-js-javascript/a-new-kind-of-open-source-2378d70cdb9d Using WebRTC to organize conf call very easily through any browser. Just using a simple HTML page. (well, there is a central server too behind the scene)
- https://medium.com/airbnb-engineering/unlocking-horizontal-scalability-in-our-web-serving-tier-d907449cdbcf AirBNB adding database proxies with connection pooling in front of their MySQL.
- https://github.com/airbnb/synapse Service Discovery by airbnb. Installed on every single machine, adn acts as a proxy to other services (the app on the server basically points to localhost:xxx instead of server:xxx). Combined to a local HAProxy.
- http://codegolf.stackexchange.com/questions/69189/build-a-compiler-bomb/69193 Goal: minimal source that compiles into some huge binaries. ie `main[-1u]={1};` (C) compiles to a 16GB program. Yeah.
- https://www.ibm.com/developerworks/library/j-zerocopy/ Awesome blogpost by ibm explaining how the zero-copy works. Something to definitely be aware of.
- https://community.risingstack.com/zeromq-node-js-cracking-jwt-tokens-1/ Focus on the JWT aspect and approch/architecture of the system. But need a part 2 for the interesting stuff.
- https://www.christianheilmann.com/2016/10/05/can-we-stop-bad-mouthing-css-in-developer-talks-please/ It's true that css is often the target of jokes, but can nonetheless do wonderful things when you know it well (and have the need..).
- https://www.linkedin.com/pulse/20140121122045-6526187-productivity-hacks-the-1-minute-trick the one minute trick. "Do, without delay, any task that can be finished in one minute. "
- https://en.wikipedia.org/wiki/Program_slicing Keep the code that affects a given variable. Remove the rest. Interesting to shrink js bundles or simply know WHAT affects a given variable. (recursively ofc)
- https://medium.com/net-magazine/web-performance-secrets-from-the-bbc-d4b01f869752 Minimise pauses, prioritise content. Basically: use caches (server, network, browser)
- https://www.youtube.com/watch?v=dSqLt8BgbRQ Nice Stange Loop talk about code slicing (static, dynamic, from tests..). Focusing on making code reading / bug fixing easier
- https://en.wikipedia.org/wiki/5_Whys Nice technique to find the cause of a problem. The best rule i find being "Never leave human error as the root cause."
- https://blog.archillect.com/archillect-faq-3b22342c352a What's behing this marvellous Archillect.
- https://www.youtube.com/watch?v=wf-BqAjZb8M Best practices for beautiful intelligible code. Refactor the code instead of just reformating it. Focus on the content, not the style.
- http://virtuslab.com/blog/arrows-monads-and-kleisli-part-i/ Kleislis definitely too complex for me right now

# 14-10-2016

- http://www.oracle.com/technetwork/articles/java/vmoptions-jsp-140102.html I was interesting by the -XX:+UseBiasedLocking option
- https://www.youtube.com/watch?v=fyUVjE4aUK4 Very french. Avez vous déja vu? Un mec qui se plaint tout le temps ?
- https://formidable.com/blog/2016/10/12/introducing-nodejs-dashboard/ A very basic monitoring system for node, meh
- http://spectrum.ieee.org/automaton/robotics/humanoids/this-robot-can-do-more-pushups-because-it-sweats This Robot Can Do More Push-Ups Because It Sweats. OK
- http://www.dataiku.com/ Beautiful SAS to play with your data (cleansing, ML, dataviz, worflows, scoring..)
- https://www.atomist.com/ Atomist has opened! Handle project templates easily
- https://shapeshed.com/thoughts-on-yarn/ Feedback on yarn, the js package manager, and why it has emerged (cause npm didn't "evolve" enough on the security and speed)
- https://github.com/JohnLangford/vowpal_wabbit ML anyone?

# 13-10-2016

- https://www.npmjs.com/package/pify a successful package to encapsule nodejs callback style (err, res) into a Promise
- http://highscalability.com/blog/2014/4/28/how-disqus-went-realtime-with-165k-messages-per-second-and-l.html Disqus architecture to handle the increasing load. Using Nginx Push Stream to push to customer, redis queue, python
- http://www.gwan.com/blog/20160405.html "Google's "Director of Engineering" Hiring Test" "0x02, 0x12, 0x10" "wrong, it's SYN, SYN-ACK and ACK" -_-
- http://bigocheatsheet.com/ Big O everywhere !
- https://news.ycombinator.com/item?id=12702651 Found 2 good channels
- https://www.washingtonpost.com/news/storyline/wp/2014/12/04/people-around-you-control-your-mind-the-latest-evidence/ Conclusion "All the people in your life influence you"
- https://styled-components.com/ Meh. const Title = styled.h1`background: orange; color: blue` &lt;Title /&gt;
- https://medium.com/@kentcdodds/an-argument-for-automation-fce8394c14e2 Sure, if you repeat 1000*10s, code in 1000s the automation.
- https://learnrelay.org/ Seems to be _the_ link to bookmark for relay
- http://www.jamesmonger.com/post/react-component-dependency-injection.htm Oohh, a Guice in Typescript, love it !!
- https://medium.com/the-hoard/how-kafkas-storage-internals-work-3a29b02e026 Never thought of the "segments" in the partition, good to know

# 12-10-2016

- http://blog.ploeh.dk/2015/08/17/when-x-y-and-z-are-great-variable-names/ Tiny scope ? Tiny variable name. f, x, y.
- http://techblog.netflix.com/2013/01/hadoop-platform-as-service-in-cloud.html Netflix is not using HDFS but S3 (more robust, flexible, elastic), and Amazon EMR (MapReduce). They created Genie (Hadoop Platform As A Service) that abstracts the cluster provisioning piece (to start a job), exposes a REST api
- http://techblog.netflix.com/2013/06/genie-is-out-of-bottle.html More focused on Genie itself
- https://github.com/Netflix/archaius to handle dynamic distributed centralized app configuration
- https://github.com/Netflix/eureka service discovery
- https://github.com/Netflix/genie start a task on any hadoop cluster
- https://github.com/Netflix/ribbon load-balanced rpc
- https://github.com/Netflix/governator application lifecycle (top of Guice)
- https://github.com/Netflix/servo application monitoring
- https://github.com/Netflix/Hystrix app failure is part of the job. Dashboards
- http://netflix.github.io/ Gosh, everything is there
- https://bitbucket.org/product/features/pipelines Bitbucket handles CI/CD pipelines now
- https://bitbucket.org/shah_jainish/project-examples example how to install a built artifact from the pipeline to a custom artifactory
- https://github.com/tidwall/summitdb In-memory NoSQL database with ACID transactions, Raft consensus, and Redis API
- http://stateofjs.com/2016/introduction/ some stats about JS community, what they are using to manage state, tests, css and so on
- https://github.com/perwendel/spark/ A micro framework for creating web applications in Java 8 with minimal effort (5k stars)
- https://medium.com/the-smyte-blog/rate-limiter-df3408325846 Smyte is nice and use nice techs. They open-sourced their rate limiter. It's using (some standard it seems) a token bucket (starts at 10, then decrease on "bad" action, and increase slowly only refill[Time|Amount])
- http://kamon.io/teamblog/2015/10/13/playing-with-streams-and-monitoring-docker/ Some akka-stream with Kamon to monitor Docker container stats
- http://blog.michaelhamrah.com/2015/01/a-gentle-introduction-to-akka-streams/ Really gentle intro about akka streams

# 11-10-2016

- http://degoes.net/articles/insufficiently-polymorphic Abstract all the things. def foo[F[_]: Foldable, A, R: Semigroup](fa: F[A], ar: A => R, r: R): R
- http://www.csharpstar.com/csharp7-pattern-matching/ Pattern Matching in C# 7.0. Not nicer than Scala's but it's getting there!
- http://loicdescotte.github.io/posts/play25-akka-streams/ How Play integrates with Akka Streams. Will reread that when i'll be more mature with Akka Streams.
- http://blog.scoutapp.com/articles/2015/04/10/understanding-page-faults-and-memory-swap-in-outs-when-should-you-worry nice recap of what page faults are
- http://developer.couchbase.com/documentation/server/current/architecture/core-data-access-vbuckets-bucket-partition.html vbucket?
- https://github.com/staltz/cycle-onionify didn't read the whole, Andre Staltz just twitted it. Talking about onions, source, sinks. I'm sold.
- https://modeshape.wordpress.com/category/presentation/ something
- https://github.com/Netflix/archaius Handle application configuration over some service (zk, dynamo, jmx, jdbc..)
- https://blog.risingstack.com/node-js-examples-what-companies-use-node-for/ OK microservices, at scale
- http://jlongster.com/Compiling-LLJS-to-asm.js,-Now-Available- lljs was something. once.
- https://code.facebook.com/posts/1840075619545360/yarn-a-new-package-manager-for-javascript/ YAY : Yet Another YARN. "Better" npm.
- http://yehudakatz.com/2016/10/11/im-excited-to-work-on-yarn-the-new-js-package-manager-2/ OK
- http://thereignn.ghost.io/in-the-defense-of-fatigue-and-how-to-overcome-it/ meh. There is no fatigue. Just learning and filtering stuff.
- https://medium.com/@kosamari/how-to-be-a-compiler-make-a-compiler-with-javascript-4a8a13d473b4 A nice little "compiler" to write svgs

# 10-10-2016

- https://www.playframework.com/documentation/2.5.x/JavaBodyParsers You know, working.
- http://www.reactive-streams.org/ A "spec" à la reactive manifesto defining _asynchronous_ stream processing with _non-blocking_ _back pressure_. Always good to reread. Some simple interfaces in org.reactivestreams package
- https://github.com/reactive-streams/reactive-streams-jvm The repo. More detailed.
- https://github.com/puffnfresh/bilby.js An interesting very functional js lib. But fantasyLand is the next.

# 09-10-2016

- https://github.com/jiahaog/nativefier Convert any website into an Electron App. Wonderful.
- https://medium.com/walmartlabs/make-your-react-components-pretty-a1ae4ec0f56e How to code "pretty" with React. Nothing new. Stateless comps, fat arrows and ES6 in general.
- https://medium.com/@zackbloom/how-planes-fly-into-hurricanes-380653acc6ba Those crazy dudes, inside Hurricane Matthew
- https://github.com/rgrove/dotfiles very interesting to look into complete dotfiles of another fellow developer
- https://docs.npmjs.com/cli/completion I've been using npm since years, never added the autocompletion. Seriously.
- https://www.theguardian.com/technology/2016/jun/28/us-customs-border-protection-social-media-accounts-facebook-twitter "US border control could start asking for your social media accounts" Wow.
- https://github.com/markerikson/react-redux-links A shitload of links about js/react/redux/nodejs/webpack, but if you know what to look for, you may find it in there
- https://github.com/reagent-project/reagent A minimalistic ClojureScript interface to React.js
- https://news.ycombinator.com/item?id=12637239 "Ask HN: What's your favorite tech talk?" I should not have been there
- https://www.youtube.com/watch?v=ji5_MqicxSo "The Last Lecture" A magnific talk by Randy Pausch. Inspirional, emotional. Talking a lot about VR.. in 1996.
- https://www.youtube.com/watch?v=UF8uR6Z6KLc "Steve Jobs' 2005 Stanford Commencement Address" Stay hungry, stay foolish.
- https://github.com/robinhouston/image-unshredding Reconstruct image from its shredding version, interesting (js, crypto)
- http://tutorials.jenkov.com/java-util-concurrent Java ConcurrentHashMap, ArrayBlockingQueue, SynchronousQueue (1 element), CountDownLatch(N), CyclicBarrier (a count down latch but unlocked by several distinct threads), Exchanger, Semaphore(N), ExecutorServices, FJP (fork a task, then join (merge)), Locks, Atomic* (using CAS)
- https://blog.heroku.com/fixing-kafka-memory-leak A memory leak in Kafka. They used JMX java.lang:type=Memory and sysdig. Leak was not on heap nor off heap, it was due to an non-closed Stream linked by a native C lib, zlib (hence not handled by Java at all).
- https://www.youtube.com/watch?v=oTugjssqOT0 Randy Pausch Lecture: Time Management. Learn to say No. Don't do every todo you've written down. Organize by importance. Do importants and hard tasks first. Reduce interruptions (emails, im, phone..). Batch things. Delegate. Thanks people.

# 08-10-2016

- http://blog.dlib.net/2016/10/hipsterize-your-dog-with-deep-learning.html deep learning to add glasses and mustache to dog pictures xD
- http://cen.acs.org/articles/94/web/2016/10/Silkworms-eat-carbon-nanotubes-graphene.html let silkworms eat carbon and titanium to make very resistant silk. uh
- https://research.googleblog.com/2016/10/graph-powered-machine-learning-at-google.html graph based "semi-supervised" ML. train labeled+unlabeled data at the same time (it's hard to have a huge quality labeled dataset for each domain). Multiple data types input (images, text..). Propagate labels using node weight and links, and multi-hops.
- http://www.recode.net/2016/10/7/13201832/apple-sued-ios-browser-limits Nexedi is suing Apple to open the iPhone to rival browsing engines (because Apple's Webkit sucks)
- https://medium.freecodecamp.com/manually-tuning-webpack-builds-284923f47f44 some tips to have a bundle without lib duplication
- http://www.dailymotion.com/video/x3s16hq_ascii-fluid-dynamics-ioccc2012-endoh1-c_fun ASCII fluid dynamics video, funny
- https://github.com/cakesolutions/scala-kafka-client a wrapper around Kafka java client (cons+prod), and an extension to provide some Kafka[Cons|Prod]Actors. But better use reactivekafka.
- http://datastrophic.io/data-processing-platforms-architectures-with-spark-mesos-akka-cassandra-and-kafka/ SMACK : Spark+Mesos+Akka+Cassandra+Kafka: collocate Spark workers on a Mesos slave with Cassandra nodes for data locality, using Marathon for long-running tasks and Chronos for scheduled jobs. Using Kafka and Spark Streaming to preprocess data.
- http://fr.slideshare.net/PatrickSenti/lessons-from-highly-scalable-architectures-at-social-networking-sites Scalability: Consistent hashing, sharding by user (not time), thrift, redis, Flexibility: Decoupling, Layering, Automation, Reliability: Replication
- http://phaser.io/news/2016/01/phaser-in-2015-and-beyond I played with Phaser (JS game framework) a while ago. It evolved a lot and it enfanted a child: Lazer.
- https://www.infoq.com/presentations/openjdk8-hotspot a bit too specialized for me right now. I won't remember anything.
- http://highscalability.com/blog/2015/1/26/paper-immutability-changes-everything-by-pat-helland.html immutability FTW. Leads to a paper by Pat Helland (Salesforce) http://cidrdb.org/cidr2015/Papers/CIDR15_Paper16.pdf
- https://github.com/mjackson/web-starter existed before create-react-app cli. With heroku integration.
- https://github.com/hartleybrody/public-amazon-crawler a nice and simple Amazon crawler in Python, using redis and postgresql. and socks5 proxies.
- https://www.citusdata.com/blog/2016/09/09/pgcron-run-periodic-jobs-in-postgres/ cron in postgres: `SELECT cron.schedule('0 10 * * *', 'VACUUM');`
- https://github.com/FallibleInc/security-guide-for-developers/blob/master/security-checklist.md A handsome general security checklist to bookmark and print
- https://github.com/chenglou/intro-to-reason-compilation/ Some steps to explain how Reason by Facebook compiles. It's basically a OCaml preprocessor, handling Reason AND Javascript dependencies. Then using BuckleScript to compile ocaml --> js.

# 07-10-2016

- https://digest.bps.org.uk/2016/10/07/brain-training-exercises-just-make-you-better-at-brain-training-exercises/ Brain training exercises are useless, they do not "extend" to the general performance
- https://fr.wikipedia.org/wiki/Propri%C3%A9t%C3%A9s_ACID : A quick reminder of the details!
- https://www.infoq.com/articles/Isolation-Levels : careful of the isolation level you're using (can cause dirty/double/phantom reads) + succinct presentation of the isolation levels in mysql/postgresql/sqlserver/oracle/db2/mongodb/couchdb/couchbase/cassandra (MyISAM no transaction (full table lock), mongodb no transaction (only single doc atomic, dirty reads), couchdb no -transaction but MVCC (multiversion concurrency control), cassandra: only read uncommitted max
- http://movingfulcrum.com/rethinkdb-failure-engineering-not-marketing/ : why rethinkdb fails ? letting java aside, focusing on cool features but forgetting important ones (failover, java..)
- https://github.com/kendricktan/suiron/ toy car moving using ML
- https://github.com/jlxw/geoip cloudflare automatically returns a header "cf-ipcountry"
- https://github.com/rwaldron/tc39-notes/blob/master/es7/2016-09/Observable-Use-Cases.pdf DOM events as Observables, with crappy awaits everywhere and CancellationTokens
- http://dbglass.web-pal.com/ : a pgadmin using electron. but that's useless, there is already the new pgadmin4 (on the web!)
- https://www.git-tower.com/windows/ a very good but paying git UI client
- http://v8project.blogspot.de/2016/10/fall-cleaning-optimizing-v8-memory.html Chrome does memory footprint benchmark regression tests now. They added a "low memory device" mode
- https://rainsoft.io/what-every-javascript-developer-should-know-about-unicode/ : Unicode 9: 128172 characters, Domain: Codepoint, Planes, Code unit, Character name, Astract Symbol, Surrogate Pairs, Encoding, Graphème, Symbol, Glyph, Combining Mark. In JS: .length = nb of code units (surrogate pairs = 2cu, so it's just wrong), "\u0020" in JS. For astral (>0xFFFF) use surrogate pairs = 2 code points (\u*2) or \u{12345} in ES6. String normalization (because multiple way to represent a same symbol, need a canonical form). JS: str.normalize(). [...str] or Array.from(str) (@@iterator) has the good length (deal with unicode and surrogates) (str.length = 5 but [...str].length = 4). str.codePointAt(index). String.fromCodePoint(cp). If used in regexes, use /.../u otherwise it sucks and fails.
- http://tudorzgureanu.com/demystifying-akka-extensions/ HOW TO do an Akka extension (autoloaded at startup). Nice and clean, using some Kafka config here.
- https://github.com/cakesolutions/scala-kafka-client Scala implementation of Kafka Client API + Akka module if needed
