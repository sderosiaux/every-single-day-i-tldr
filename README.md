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
