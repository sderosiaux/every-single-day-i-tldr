# *Almost* every single day I TLDR!

Here, I list every article, blog post, page, video I read or watch and find interesting. I add a little description for me to find it later, or as a TLDR.

> Note for my employer: this is stuff I'm reading mostly off work of course. :angel:

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
