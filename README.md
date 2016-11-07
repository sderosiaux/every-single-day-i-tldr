Here, I list every article, blog post, page, video I read or watch and find interesting. I add a little description for me to find it later, or as a TLDR.

> Note for my employer: this is stuff I'm reading mostly off work of course. :angel:

# 07-11-2016

- https://github.com/faergeek/remove-medium-hash Remove the ugly hash medium.com auto-adds at the end of the url :) it messes up with the bookmarks otherwise
- http://c2fo.io/c2fo/spark/aws/emr/2016/07/06/apache-spark-config-cheatsheet/ Spark excel (lol) cheatsheet to configure some props (cpu, mem, overhead..) according to a cluster typology
- https://www.lightbend.com/platform/production i was looking for intel about conductr, google drop me here, but no *visible* reference to conductr, BAD UX ;)
- https://conductr.lightbend.com/docs/1.1.x/Home I had to look at the source to find this link eheh "solution for managing Lightbend Reactive Platform applications across a cluster of machines. " Commercial only iiuc.
- https://www.youtube.com/watch?v=jHoIzOdUn4c 1h of Martin Odersky resuming what's going on with Scala and Dotty. Quick notes: 2.12: java8, 2.13: scala libraries/collections (with some Spark'y methods (reducebyKey and so on)); split Scala stdlib to: core (what the compiler always need) + platform (containing community efforts, like a common json serde thing); scala.js production ready; Scala Native on LLVM; Scala Center: education, package "manager" (to find a scala package doing x)
dotty: based on DOT. faster than nsc (scalac). New piece in Dotty: TASTY: T_AST_Y (optim AST). No more Macros.. but a replacement! (scala.meta) and more new features. ELM error messages incoming :). MVP Spring 2017. A new "pure" arrow function -> (=> would still exist). No null by default, need to "Object?". No more 22 :)) :heart:


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

- https://cors.now.sh/ Public reverse-proxy to add CORS on any url (https://cors.now.sh/<url>)
- https://www.microsoft.com/en-us/surface/devices/surface-studio/surface-studio this is some serious "PC" by Microsoft, for designers mostly. $2,999 at least.
- https://medium.freecodecamp.com/what-i-learned-from-reading-the-redux-source-code-836793a48768 Ultra basic. Basically, some tips to write better code.
- https://medium.freecodecamp.com/three-ways-to-return-largest-numbers-in-arrays-in-javascript-5d977baa80a1 for, reduce, or math.max. 
- https://github.com/staltz/comver semver without Patch. (ie: MAJOR.MINOR) to speak only about backward-compat. For some reasons, that does not interest me. It's for people that does not know how to use semver and determine what the version they should increase. Good for them. But clearly, that simplifies the versioning if you don't care about communication of fixes.
- http://slides.com/vanessayuenn/augury-ngeurope ok, angury is the equivalent of the react chrome extension.
- https://medium.com/@bartobri/applying-the-linus-tarvolds-good-taste-coding-requirement-99749f37684a good point: the less conditions, the better the code. BUT, good points in comments: beware of cache misses.
- http://seriot.ch/parsing_json.html As the title says: "parsing json is a minefield". Every parsers has its own set of "extensions" and does not respect the full json specs (because the specS themselves are messy and contradictory).
- https://ateev.in/react-js-achieving-20ms-server-response-time-with-server-side-rendering-1ea80e420d88 lol, ok, basically, put Redis for the API (and deal with cache invalidation)
- http://www.confluent.io/blog/unifying-stream-processing-and-interactive-queries-in-apache-kafka/ this is so great. kafka streams with querying logic. The example is a bit complex to handle. (https://github.com/confluentinc/examples/tree/master/kafka-streams/src/main/java/io/confluent/examples/streams/interactivequeries/kafkamusic) Using Jersey <3
- https://github.com/ogirardot/typesafe-kafka-streams Scala-like compatible KStreams <3
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
