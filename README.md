Her, I list every article, blog post, page, video I read or watch and find interesting. I add a little description for me to find it later, or as a TLDR.

> Note for my employer: this is stuff I'm reading mostly off work of course. :angel:

# 22-10-2016

Incoming...

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
- https://vimeo.com/113707214 Railroad oriented programming: Error handling in functional languages. Basically, use Either[Throwable, Result] (2 tracks) and compose your functions. Really good analogy and talk.
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
