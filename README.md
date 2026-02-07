## Hi there. I need a job with Pulsar!

**Email:** liusinan1998@gmail.com

**WeChat:** Denovo1998

<!--
**Denovo1998/Denovo1998** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

---

**Things to do:**

### Pulsar (apache/pulsar)

#### Features / PIPs
* [apache/pulsar#24928](https://github.com/apache/pulsar/pull/24928) `feat` `pip` — **PIP-448: Topic-level delayed message tracker (memory optimization)**
* [apache/pulsar#24927](https://github.com/apache/pulsar/pull/24927), [apache/pulsar#24922](https://github.com/apache/pulsar/pull/24922) `feat` `broker` — **Topic-level delayed delivery tracking (in-memory manager)**
* [apache/pulsar#24370](https://github.com/apache/pulsar/pull/24370), [apache/pulsar#23907](https://github.com/apache/pulsar/pull/23907) `improve` `pip` `broker` — **PIP-423: Admin API to acknowledge a single message**
* [apache/pulsar#23895](https://github.com/apache/pulsar/pull/23895), [apache/pulsar#23896](https://github.com/apache/pulsar/pull/23896) `improve` `pip` `client` — **PIP-405: Enhanced dynamic handling of selective consumers in MultiTopicConsumers**
* [apache/pulsar#23143](https://github.com/apache/pulsar/pull/23143), [apache/pulsar#23194](https://github.com/apache/pulsar/pull/23194) `improve` `pip` `broker` — **PIP-371: Support for request-reply model (RPC calls)**
* [apache/pulsar#19566](https://github.com/apache/pulsar/pull/19566) `improve` `broker` — **PIP-246: Improve PROTOBUF_NATIVE schema compatibility checks (no avro-protobuf)**
* [apache/pulsar#17449](https://github.com/apache/pulsar/pull/17449) `fix` `broker` — **PIP-236: Fix schema-based consumer creation failure after AUTO_CONSUME subscribe**

#### Broker / Managed Ledger
* [apache/pulsar#24739](https://github.com/apache/pulsar/pull/24739) `improve` `broker` — **Optimize fine-grained concurrency control for BucketDelayedDeliveryTracker**
* [apache/pulsar#24372](https://github.com/apache/pulsar/pull/24372) `improve` `broker` — **Support consumer-side delayed messages**
* [apache/pulsar#23609](https://github.com/apache/pulsar/pull/23609) `improve` `ml` — **Avoid repetitive nested lock for `isMessageDeleted` in `ManagedCursorImpl`**
* [apache/pulsar#20415](https://github.com/apache/pulsar/pull/20415) `improve` `broker` — **Supplement schema ledger if schema ledger is lost**
* [apache/pulsar#19753](https://github.com/apache/pulsar/pull/19753) `cleanup` `broker` — **Remove duplicate code in SchemaRegistryServiceImpl (schema checks)**
* [apache/pulsar#24770](https://github.com/apache/pulsar/pull/24770) `fix` `broker` — **Flaky-test: ExtensibleLoadManagerImplTest.testDisableBroker**

#### Stability / Tests / Build
* [apache/pulsar#24875](https://github.com/apache/pulsar/pull/24875) `fix` `test` — **Stabilize FunctionAssignmentTailerTest.testErrorNotifier (CountDownLatch sync)**
* [apache/pulsar#24865](https://github.com/apache/pulsar/pull/24865) `fix` `test` — **Fix flaky SubscriptionSeekTest.testSeekWillNotEncounteredFencedError (fenced counting after seek)**
* [apache/pulsar#24864](https://github.com/apache/pulsar/pull/24864) `fix` `test` — **Stabilize PublishRateLimiterOverconsumingTest (aligned measurement; adjacent 2s averages)**
* [apache/pulsar#24861](https://github.com/apache/pulsar/pull/24861) `fix` `test` — **Stabilize SequenceIdWithErrorTest (fence after first publish)**
* [apache/pulsar#24620](https://github.com/apache/pulsar/pull/24620) `fix` `test` — **Fix IllegalArgumentException in bucket range validation for delayed delivery**
* [apache/pulsar#22500](https://github.com/apache/pulsar/pull/22500) `fix` `test` — **Fix SchemaMap reuse in AutoConsumeSchema**
* [apache/pulsar#21979](https://github.com/apache/pulsar/pull/21979) `fix` `build` — **Remove duplicate mapping key in docker-compose yaml**
* [apache/pulsar#21634](https://github.com/apache/pulsar/pull/21634) `fix` `test` — **Fix unload topic + compaction task failure after task triggered**
* [apache/pulsar#25227](https://github.com/apache/pulsar/pull/25227) `fix` `test` — **Fix Mockito stubbing race in TopicListServiceTest**


### KoP (Denovo1998/starlight-for-kafka)
* [datastax/starlight-for-kafka#124](https://github.com/datastax/starlight-for-kafka/pull/124) `improve` `ci` `netty` — **Add Netty leak detection reporting to CI and local tests**
* [datastax/starlight-for-kafka#126](https://github.com/datastax/starlight-for-kafka/pull/126) `improve` `entryFormatter` — **Reduce allocations in PulsarEntryFormatter batch encoding**
* [datastax/starlight-for-kafka#127](https://github.com/datastax/starlight-for-kafka/pull/127) `fix` `bug` `netty` — **Complete ResponseCallbackWrapper on encoding failure**
* [datastax/starlight-for-kafka#128](https://github.com/datastax/starlight-for-kafka/pull/128) `improve` `protocol` — **Add Kafka client quotas support in KoP**


### pulsar-java-contrib (apache/pulsar-java-contrib)
* [apache/pulsar-java-contrib#6](https://github.com/apache/pulsar-java-contrib/pull/6) `improve` `pcip` — **PCIP-2: Distributed RPC framework implemented by the Pulsar client**
* [apache/pulsar-java-contrib#12](https://github.com/apache/pulsar-java-contrib/pull/12) `improve` `pcip` — **PCIP-4: Improve delayed RPC message handling in pulsar-rpc**


### pulsar-helm-chart (apache/pulsar-helm-chart)
* [apache/pulsar-helm-chart#645](https://github.com/apache/pulsar-helm-chart/pull/645) `feat` `helm` `bookkeeper` — **Add support for BookKeeper `indexDirectories` configuration**
