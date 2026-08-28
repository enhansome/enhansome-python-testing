# Awesome Python Testing with stars

Collection of awesome Python resources for testing and generating test data.

## Contents

* [Assertions](#assertions)
* [Behavior-driven Development](#behavior-driven-development)
* [Code Coverage](#code-coverage)
* [Design by Contract](#design-by-contract)
* [Fake Data](#fake-data)
* [Fixtures](#fixtures)
* [LLM & MCP Testing](#llm--mcp-testing)
* [Load Testing](#load-testing)
* [Memory Management](#memory-management)
* [Mock and Stub](#mock-and-stub)
* [Mutation Testing](#mutation-testing)
* [Object Factories](#object-factories)
* [Penetration Testing](#penetration-testing)
* [Property Based Testing](#property-based-testing)
* [Reporting](#reporting)
* [Rest API Testing](#rest-api-testing)
* [Retrying Tests](#retrying-tests)
* [Snapshot Tests](#snapshot-tests)
* [Speed](#speed)
* [Static Checks](#static-checks)
* [Test Runners](#test-runners)
* [Testing Frameworks](#testing-frameworks)
* [Tools](#tools)
* [UI Testing](#ui-testing)
* [Resources](#resources)

## Assertions

* [dirty-equals](https://github.com/samuelcolvin/dirty-equals) ⭐ 1,004 | 🐛 27 | 🌐 Python | 📅 2026-08-10 - A python library that (mis)uses the `__eq__` method to make python code (generally unit tests) more declarative and therefore easier to read and write.
* [PyHamcrest](https://github.com/hamcrest/PyHamcrest) ⭐ 804 | 🐛 28 | 🌐 Python | 📅 2026-02-12 - A framework for writing matcher objects, allowing you to declaratively define "match" rules.
* [sure](https://github.com/gabrielfalcao/sure) ⭐ 700 | 🐛 25 | 🌐 Python | 📅 2025-03-01 - An idiomatic assertion toolkit with human-friendly failure messages, inspired by RSpec Expectations and should.js.
* [Precisely](https://github.com/mwilliamson/python-precisely) ⭐ 244 | 🐛 6 | 🌐 Python | 📅 2025-09-16 - Write precise assertions so you only test the behaviour you're really interested in.
* [expects](https://github.com/jaimegildesagredo/expects) ⭐ 222 | 🐛 19 | 🌐 Python | 📅 2025-02-17 - Expects is an expressive and extensible TDD/BDD assertion library for Python.
* [easycheck](https://github.com/nyggus/easycheck) ⭐ 25 | 🐛 22 | 🌐 Python | 📅 2026-01-29 - A collection of assertion-like functions to be used in code, where assertion themselves should be avoided; `easycheck` includes also function aliases to be used in unit testing.
* [expycted](https://github.com/bdsoha/expycted) ⭐ 6 | 🐛 14 | 🌐 Python | 📅 2023-03-01 - Another Python expect pattern implementation. Simple, intuitive and approachable, with ability to plug in to any testing framework that relies on assertions.
* [believe](https://github.com/pkyosx/believe) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2024-04-08 - A python package for json/dictionary validation.
* [pytest\_cache\_assert](https://github.com/kyleking/pytest_cache_assert) ⚠️ Archived - Cache assertion data to simplify regression testing of complex serializable data.

## Behavior-driven Development

* [behave](https://github.com/behave/behave) ⭐ 3,521 | 🐛 78 | 🌐 Python | 📅 2026-08-26 - is behavior-driven development, Python style.
* [lettuce](https://github.com/gabrielfalcao/lettuce) ⭐ 1,276 | 🐛 101 | 🌐 Python | 📅 2020-12-29 - Behavior-driven-development tool for python, inspired by Cucumber for Ruby.
* [pytest-pyspec](https://github.com/felipecrp/pytest-pyspec) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-11-18 - Transforms pytest output into a beautiful, readable format similar to RSpec. It provides semantic meaning to your tests by organizing them into descriptive hierarchies.
* [mamba](http://nestorsalceda.github.io/mamba) - The definitive testing tool for Python. Born under the banner of BDD.

## Code Coverage

* [Coverage.py](https://github.com/nedbat/coveragepy) ⭐ 3,406 | 🐛 307 | 🌐 Python | 📅 2026-08-26 - is a tool for measuring code coverage of Python programs.
* [diff\_cover](https://github.com/Bachmann1234/diff_cover) ⭐ 841 | 🐛 61 | 🌐 Python | 📅 2026-08-16 - Automatically find diff lines that need test coverage.
* [slipcover](https://github.com/plasma-umass/slipcover) ⭐ 585 | 🐛 5 | 🌐 Python | 📅 2026-08-14 - Near Zero-Overhead Python Code Coverage.
* [coverage-conditional-plugin](https://github.com/wemake-services/coverage-conditional-plugin) ⭐ 80 | 🐛 15 | 🌐 Python | 📅 2025-01-03 - Conditional coverage based on any rules you define.

## Design by Contract

* [deal](https://github.com/life4/deal) ⭐ 904 | 🐛 8 | 🌐 Python | 📅 2025-11-30 - Design by contract for Python with static checker and test generation.
* [pact-python](https://github.com/pact-foundation/pact-python) ⭐ 681 | 🐛 21 | 🌐 Python | 📅 2026-08-27 - Python version of Pact. Enables consumer driven contract testing, providing a mock service and DSL for the consumer project, and interaction playback and verification for the service provider project.
* [icontract](https://github.com/Parquery/icontract) ⭐ 413 | 🐛 2 | 🌐 Python | 📅 2026-01-29 - Design-by-contract in Python3 with informative violation messages and inheritance.

## Fake Data

* [faker](https://github.com/joke2k/faker) ⭐ 19,382 | 🐛 33 | 🌐 Python | 📅 2026-08-21 - A Python package that generates fake data.
* [mimesis](https://github.com/lk-geimfari/mimesis) ⭐ 4,839 | 🐛 14 | 🌐 Python | 📅 2026-08-23 - A Python library that helps you generate fake data.
* [fake2db](https://github.com/emirozer/fake2db) ⭐ 2,347 | 🐛 7 | 🌐 Python | 📅 2019-11-25 - Fake database generator.
* [autofaker](https://github.com/christianhelle/autofaker) ⭐ 8 | 🐛 7 | 🌐 Python | 📅 2026-08-25 - designed to minimize the setup/arrange phase of your unit tests by removing the need to manually write code to create anonymous variables as part of a test cases setup/arrange phase.
* [genuine-fake](https://github.com/xeroxzen/genuine-fake) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-08-20 - Genuine Fake means an imitation of a (usually) valuable object that is so good that it is, to all intents and purposes, identical.
* [radar](https://pypi.org/project/radar) - Generate random datetime / time.

## Fixtures

* [pytest-deadfixtures](https://github.com/jllorencetti/pytest-deadfixtures) ⭐ 166 | 🐛 16 | 🌐 Python | 📅 2026-01-15 - A simple plugin to list unused or duplicated fixtures in a pytest suite.
* [pytest-mysql](https://github.com/ClearcodeHQ/pytest-mysql) ⭐ 58 | 🐛 20 | 🌐 Python | 📅 2026-08-24 - A pytest plugin, that enables you to test your code that relies on a running MySQL Database. It allows you to specify fixtures for MySQL process and client.
* [pytest-rabbitmq](https://github.com/ClearcodeHQ/pytest-rabbitmq) ⭐ 51 | 🐛 20 | 🌐 Python | 📅 2026-08-24 - A pytest plugin, that enables you to test your code that relies on a running RabbitMQ server. It allows you to specify fixtures for RabbitMQ server and client.
* [protestr](https://github.com/Grimmscorpp/protestr) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2025-01-08 - A simple, powerful fixture provider for Python tests. Protestr's intuitive API lets you generate versatile fixtures for your test cases and inject them as dependencies on demand.

## LLM & MCP Testing

* [mcp-server-fuzzer](https://github.com/Agent-Hellboy/mcp-server-fuzzer) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2026-08-08 - A comprehensive fuzzing tool designed specifically for testing Model Context Protocol (MCP) servers. It supports both tool argument fuzzing and protocol type fuzzing across multiple transport protocols.
* [Tenro](https://github.com/tenro-ai/tenro-python) ⭐ 7 | 🐛 1 | 🌐 Python | 📅 2026-06-09 - An open-source, provider-agnostic testing framework for AI agents that integrates with pytest. It simulates LLM and tool calls to test edge cases, failure paths, and agent logic without live API calls.
* [Sabot](https://github.com/Jott2121/sabot) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-07-25 - Plants controlled faults inside running multi-agent pipelines (LangGraph, CrewAI, AutoGen) and scores whether each pipeline's own reviewer and guardrail stages detect them. Pre-registered spec, deterministic adjudication, published raw traces.

## Load Testing

* [Locust](https://github.com/locustio/locust) ⭐ 28,109 | 🐛 3 | 🌐 Python | 📅 2026-08-26 - Scalable user load testing tool written in Python.
* [Grasshopper](https://github.com/alteryx/locust-grasshopper) ⭐ 195 | 🐛 1 | 🌐 Python | 📅 2026-08-05 - A lightweight framework for performing load tests against an environment, primarily against an API. Grasshopper glues Locust, Pytest, some plugins (namely Locust InfluxDBListener ) and some custom code to provide a package that makes authoring load tests simple with very little boilerplate needed.
* [pynonymizer](https://github.com/jerometwell/pynonymizer) ⭐ 116 | 🐛 6 | 🌐 Python | 📅 2026-05-07 - is a universal tool for translating sensitive production database dumps into anonymized copies.
* [Grizzly](https://github.com/biometria-se/grizzly) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2026-08-18 - is a framework to be able to easily define load scenarios, and is mainly built on-top of Locust and Behave.
* [Dynamic Workload Model](https://github.com/hseera/dynamic-workload-model) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2021-09-16 - Code to generate dynamic workload model. Useful for testing autoscaling in cloud or mimicking different load profile for different scenario.
* [pywrkr](https://github.com/kurok/pywrkr) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-19 - HTTP benchmarking CLI inspired by wrk and ApacheBench (ab), with latency percentiles, virtual-user simulation, constant-rate and traffic-profile load shaping, HAR import, and pass/fail SLO thresholds for CI.

## Memory Management

* [Pympler](https://github.com/pympler/pympler) ⭐ 1,410 | 🐛 70 | 🌐 Python | 📅 2025-06-07 - is a development tool to measure, monitor and analyze the memory behavior of Python objects in a running Python application.
* [filprofiler](https://github.com/pythonspeed/filprofiler) ⭐ 906 | 🐛 105 | 🌐 Rust | 📅 2026-05-03 - A Python memory profiler for data processing and scientific computing applications.
* [Guppy 3](https://github.com/zhuyifei1999/guppy3) ⭐ 431 | 🐛 5 | 🌐 Python | 📅 2026-05-18 - a Python programming environment & heap analysis toolset.
* [mem\_top](https://github.com/denis-ryzhkov/mem_top) ⭐ 82 | 🐛 0 | 🌐 Python | 📅 2022-07-13 - shows top suspects for memory leaks in your Python program.
* [tracemalloc](https://docs.python.org/3/library/tracemalloc.html) - is a debug tool to trace memory blocks allocated by Python.

## Mock and Stub

* [moto](https://github.com/spulec/moto) ⭐ 8,628 | 🐛 62 | 🌐 Python | 📅 2026-08-27 - allows you to easily mock out tests based on AWS infrastructure.
* [freezegun](https://github.com/spulec/freezegun) ⭐ 4,525 | 🐛 167 | 🌐 Python | 📅 2025-08-19 - Travel through time by mocking the datetime module.
* [responses](https://github.com/getsentry/responses) ⭐ 4,345 | 🐛 40 | 🌐 Python | 📅 2026-08-26 - A utility library for mocking out the requests Python library.
* [httpretty](https://github.com/gabrielfalcao/HTTPretty) ⭐ 2,159 | 🐛 130 | 🌐 Python | 📅 2024-06-09 - HTTP request mock tool for Python.
* [time-machine](https://github.com/adamchainz/time-machine) ⭐ 994 | 🐛 7 | 🌐 Python | 📅 2026-08-25 - Travel through time in your tests.
* [pyfakefs](https://github.com/pytest-dev/pyfakefs) ⭐ 750 | 🐛 14 | 🌐 Python | 📅 2026-08-28 - A fake file system that mocks the Python file system modules.
* [trustme](https://github.com/python-trio/trustme) ⭐ 606 | 🐛 5 | 🌐 Python | 📅 2026-08-05 - gives you a fake certificate authority (CA) that you can use to generate fake TLS certs to use in your tests.
* [Aioresponses](https://github.com/pnuckowski/aioresponses) ⭐ 557 | 🐛 65 | 🌐 Python | 📅 2026-06-23 - is a helper for mock/fake web requests in python aiohttp package.
* [httmock](https://github.com/patrys/httmock) ⭐ 472 | 🐛 15 | 🌐 Python | 📅 2023-09-29 - A mocking library for requests for Python 2.6+ and 3.2+.
* [Pretend](https://github.com/alex/pretend) ⭐ 318 | 🐛 4 | 🌐 Python | 📅 2024-06-22 - is a library to make stubbing with Python easier.
* [mocket](https://github.com/mindflayer/python-mocket) ⭐ 311 | 🐛 6 | 🌐 Python | 📅 2026-08-26 - A socket mock framework with gevent/asyncio/SSL support.
* [Mockintosh](https://github.com/up9inc/mockintosh) ⭐ 178 | 🐛 23 | 🌐 Python | 📅 2022-09-20 - aims to provide usual HTTP mock service functionality with small resource footprint, making it friendly for microservice applications.
* [Cornell](https://github.com/hiredscorelabs/cornell) ⭐ 144 | 🐛 1 | 🌐 Python | 📅 2026-07-06 - record & replay mock server.
* [Mockafka](https://github.com/alm0ra/mockafka-py) ⭐ 66 | 🐛 19 | 🌐 Python | 📅 2026-07-20 - Python library designed for mocking Kafka in a testing environment. It simplifies testing Kafka-integrated applications by providing an in-memory mock for aiokafka and confluent-kafka-python.
* [Flexmock](https://github.com/flexmock/flexmock) ⭐ 65 | 🐛 29 | 🌐 Python | 📅 2026-08-09 - is a testing library for Python that makes it easy to create mocks, stubs and fakes.
* [D-MemFS](https://github.com/nightmarewalker/D-MemFS) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-03-22 - Zero-dependency in-memory virtual filesystem with hard quotas. Provides an explicit, isolated instance instead of patching global state.
* [Kesha](https://github.com/NUTtech/Kesha) ⭐ 16 | 🐛 29 | 🌐 Python | 📅 2023-03-06 - A web service with a user interface for testing http requests and web hooks.
* [pytest-tripwire](https://github.com/axiomantic/pytest-tripwire) ⭐ 1 | 🐛 18 | 🌐 Python | 📅 2026-08-07 - Pytest plugin for full-certainty test mocking, every recorded interaction must be explicitly asserted.
* [doublex](https://pypi.org/project/doublex) - Powerful test doubles framework for Python.
* [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.

## Mutation Testing

* [Mutmut](https://github.com/boxed/mutmut) ⭐ 1,407 | 🐛 49 | 🌐 Python | 📅 2026-08-17 - is a mutation testing system for Python, with a strong focus on ease of use.
* [Cosmic Ray](https://github.com/sixty-north/cosmic-ray) ⭐ 654 | 🐛 52 | 🌐 Python | 📅 2026-08-09 - makes small changes to your source code, running your test suite for each one.
* [MutPy](https://github.com/mutpy/mutpy) ⭐ 367 | 🐛 36 | 🌐 Python | 📅 2024-04-23 - MutPy is a mutation testing tool for Python 3.x source code
* [Mutatest](https://github.com/EvanKepner/mutatest) ⭐ 101 | 🐛 7 | 🌐 Python | 📅 2023-02-17 - Python mutation testing.
* [xmutant.py](https://github.com/vrthra/xmutant.py) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2018-11-18 - Python 3.6 bytecode based mutation analysis framework
* [bough](https://github.com/CodeEnPlace/bough) ⭐ 1 | 🐛 33 | 🌐 Rust | 📅 2026-04-10 - Bough is a polyglot incremental mutation tester.
* [Crucible](https://github.com/Jott2121/crucible) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2026-08-03 - Adversarial test-hardening for AI-written code, built on mutmut. A Tester agent writes tests, mutation testing names the survivors, and a Critic agent kills exactly those.

## Object Factories

* [factory\_boy](https://github.com/FactoryBoy/factory_boy) ⭐ 3,805 | 🐛 210 | 🌐 Python | 📅 2026-01-01 - A test fixtures replacement for Python.
* [polyfactory](https://github.com/litestar-org/polyfactory) ⭐ 1,501 | 🐛 74 | 🌐 Python | 📅 2026-08-24 - A simple and powerful mock data generation library, based around type hints and supporting dataclasses, typed-dicts, pydantic models, msgspec structs and more.
* [Model Bakery](https://github.com/model-bakers/model_bakery) ⭐ 1,002 | 🐛 12 | 🌐 Python | 📅 2026-08-24 - offers you a smart way to create fixtures for testing in Django.
* [mixer](https://github.com/klen/mixer) ⭐ 954 | 🐛 49 | 🌐 Python | 📅 2024-03-08 - Another fixtures replacement. Supports Django, Flask, SQLAlchemy, Peewee and etc.

## Penetration Testing

* [python-pentest-tools](https://github.com/dloss/python-pentest-tools) ⭐ 2,883 | 🐛 2 | 📅 2026-07-22 - Python tools for penetration testers.
* [fsociety](https://github.com/fsociety-team/fsociety) ⭐ 1,818 | 🐛 21 | 🌐 Python | 📅 2026-08-17 - A Modular Penetration Testing Framework.
* [fencer](https://github.com/abunuwas/fencer) ⭐ 91 | 🐛 4 | 🌐 Python | 📅 2024-08-02 - Fencer is an automated API security testing tool. It's an experimental project to see how much of the API security testing process can be automated.

## Property Based Testing

* [Hypothesis](https://github.com/HypothesisWorks/hypothesis) ⭐ 8,915 | 🐛 50 | 🌐 Python | 📅 2026-08-25 - is an advanced Quickcheck style property based testing library.
* [Atheris](https://github.com/google/atheris) ⭐ 1,667 | 🐛 40 | 🌐 Python | 📅 2026-06-17 - is a coverage-guided Python fuzzing engine. It supports fuzzing of Python code, but also native extensions written for CPython.
* [hypothesis-auto](https://github.com/timothycrosley/hypothesis-auto/) ⭐ 355 | 🐛 6 | 🌐 Python | 📅 2023-09-23 - An extensions for Hypothesis that provides fully automatic testing for type hinted functions.
* [hypofuzz](https://github.com/Zac-HD/hypofuzz) ⭐ 123 | 🐛 30 | 🌐 Python | 📅 2026-05-15 - Adaptive fuzzing of Hypothesis tests.
* [icontract-hypothesis](https://github.com/mristin/icontract-hypothesis) ⭐ 91 | 🐛 2 | 🌐 Python | 📅 2022-06-05 - Instead of writing manually the Hypothesis search strategies for a function, `icontract-hypothesis` infers them based on the function's precondition.
* [hypothesis-crosshair](https://github.com/pschanely/hypothesis-crosshair) ⭐ 27 | 🐛 5 | 🌐 Python | 📅 2026-08-22 - Add the power of solver-based symbolic execution to your Hypothesis tests with CrossHair.

## Reporting

* [pytest-html-plus](https://github.com/reporterplus/pytest-html-plus) ⭐ 72 | 🐛 4 | 🌐 Python | 📅 2026-08-15 - Get a self-contained, actionable, easy-to-read single page HTML unified reports summarizing all your test results. Detect flaky tests.
* [pytest-cloudreport](https://github.com/ahmad212o/pytest-cloudreport) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-04 - A pytest plugin that automatically detects flaky tests, tracks CI stability over time, and generates a self-contained HTML report with an optional cloud dashboard for team visibility.

## Rest API Testing

* [HttpRunner](https://github.com/httprunner/httprunner) ⭐ 4,295 | 🐛 502 | 🌐 Go | 📅 2025-12-11 - is a simple & elegant, yet powerful HTTP(S) testing framework.
* [Dredd](https://github.com/apiaryio/dredd) ⚠️ Archived - is a language-agnostic command-line tool for validating API description document against backend implementation of the API.
* [Schemathesis](https://github.com/kiwicom/schemathesis) ⭐ 3,563 | 🐛 9 | 🌐 Python | 📅 2026-08-27 - A tool for automatic property-based testing of web applications built with Open API / Swagger specifications.
* [RESTler](https://github.com/microsoft/restler-fuzzer) ⭐ 2,938 | 🐛 299 | 🌐 Python | 📅 2026-06-10 - is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services.
* [cherrybomb](https://github.com/blst-security/cherrybomb) ⭐ 1,234 | 🐛 38 | 🌐 Rust | 📅 2024-10-25 - CLI tool that helps you avoid undefined user behaviour by auditing your API specifications, validating them and running API security tests.
* [Tavern](https://github.com/taverntesting/tavern) ⭐ 1,153 | 🐛 21 | 🌐 Python | 📅 2026-08-25 - is a pytest plugin, command-line tool and Python library for automated testing of APIs, with a simple, concise and flexible YAML-based syntax.
* [playback](https://github.com/Optibus/playback) ⭐ 107 | 🐛 4 | 🌐 Python | 📅 2026-08-27 - A Python decorator-based framework that lets you "record" and "replay" operations (e.g. API requests, workers consuming jobs from queues).
* [behave-restful](https://github.com/behave-restful/behave-restful) ⭐ 67 | 🐛 4 | 🌐 Python | 📅 2026-08-17 - BDD Framework to Test REST Services and APIs.
* [hypothesis-graphql](https://github.com/Stranger6667/hypothesis-graphql) ⭐ 48 | 🐛 4 | 🌐 Python | 📅 2026-08-23 - Hypothesis strategies for GraphQL schemas, queries and data.
* [postman2pytest](https://github.com/golikovichev/postman2pytest) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2026-08-24 - A CLI tool to convert Postman Collection v2.1 JSON files into runnable pytest suites, supporting environment variable substitution, folder filtering, and stress-test generation.

## Retrying Tests

* [pytest-rerunfailures](https://github.com/pytest-dev/pytest-rerunfailures) ⭐ 472 | 🐛 44 | 🌐 Python | 📅 2026-08-27 - A pytest plugin that re-runs failed tests up to -n times to eliminate flakey failures.
* [pytest-check](https://github.com/okken/pytest-check) ⭐ 426 | 🐛 2 | 🌐 Python | 📅 2026-08-01 - A pytest plugin that allows multiple failed assertions per test function, so you can see the whole picture of what's going wrong.
* [pytest-retry](https://github.com/str0zzapreti/pytest-retry) ⭐ 41 | 🐛 11 | 🌐 Python | 📅 2025-01-19 - A simple plugin for retrying flaky tests in CI environments.
* [pytest-leak-finder](https://github.com/mgaitan/pytest-leak-finder) ⭐ 40 | 🐛 4 | 🌐 Python | 📅 2025-12-19 - You have a test that passes when executed alone but fails when running its suite. What's happening? My two cents that some previous test keeps the things dirty. But which one/s, maybe the previous are a lot, right?
* [pytest-cleanslate](https://github.com/plasma-umass/pytest-cleanslate) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-04-10 - work around or find test state pollution by giving each test module a "clean slate" to execute.

## Snapshot Tests

* [VCR.py](https://github.com/kevin1024/vcrpy) ⭐ 2,986 | 🐛 161 | 🌐 Python | 📅 2026-08-25 - Record and replay HTTP interactions on your tests.
* [syrupy](https://github.com/tophat/syrupy) ⭐ 875 | 🐛 6 | 🌐 Python | 📅 2026-08-26 - is a zero-dependency pytest snapshot plugin. It enables developers to write tests which assert immutability of computed results.
* [inline-snapshot](https://github.com/15r10nk/inline-snapshot/) ⭐ 749 | 🐛 24 | 🌐 Python | 📅 2026-08-14 - a pytest plugin that boosts efficiency when writing tests by generating code with the expected values and simplifies snapshot tests with pytest.
* [SnapshotTest](https://github.com/syrusakbary/snapshottest) ⭐ 549 | 🐛 54 | 🌐 Python | 📅 2024-08-01 - is a way to test your APIs without writing actual test cases.
* [ApprovalTests](https://github.com/approvals/ApprovalTests.Python) ⭐ 210 | 🐛 13 | 🌐 Python | 📅 2026-08-23 - work by comparing the test results to a golden master.

## Speed

* [pytest-testmon](https://github.com/tarpas/pytest-testmon) ⭐ 1,009 | 🐛 37 | 🌐 Python | 📅 2025-12-01 - Selects tests affected by changed files. Continuous test runner when used with pytest-watch.
* [pytest-picked](https://github.com/anapaulagomes/pytest-picked) ⭐ 409 | 🐛 8 | 🌐 Python | 📅 2026-07-01 - Run only tests from modified test files, or run tests from modified test files first, followed by all unmodified tests
* [Awesome pytest speedup](https://github.com/zupo/awesome-pytest-speedup) ⭐ 370 | 🐛 5 | 📅 2025-06-13 - A checklist of best practices to speed up your pytest suite.
* [Django-Mercury-Performance-Testing](https://github.com/smattymatty/Django-Mercury-Performance-Testing) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2025-12-11 - Quickly & Ergonomically transform your Django Tests to track performance statistics like response time, queries, memory usage, and more!
* [pytest-deltatest](https://github.com/deltatest-org/pytest-deltatest) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-07-22 - Run only the tests affected by your code changes using SQLite-based coverage mappings, optimized for local pre-commit workflows.

## Static Checks

* [ruff](https://github.com/charliermarsh/ruff) ⭐ 49,361 | 🐛 2,164 | 🌐 Rust | 📅 2026-08-28 - An extremely fast Python linter, written in Rust.
* [Bandit](https://github.com/PyCQA/bandit) ⭐ 8,243 | 🐛 260 | 🌐 Python | 📅 2026-08-24 - is a tool designed to find common security issues in Python code.
* [Pylint](https://github.com/PyCQA/pylint) ⭐ 5,718 | 🐛 1,078 | 🌐 Python | 📅 2026-08-27 - A Python static code analysis tool which looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions.
* [typos](https://github.com/crate-ci/typos) ⭐ 4,113 | 🐛 155 | 🌐 Rust | 📅 2026-08-27 - A Source code spell checker that finds and corrects spelling mistakes in source code.
* [Refurb](https://github.com/dosisod/refurb) ⭐ 2,532 | 🐛 33 | 🌐 Python | 📅 2026-04-03 - A tool for refurbishing and modernizing Python codebases.
* [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) ⭐ 1,980 | 🐛 7 | 📅 2026-06-19 - Collection of awesome Python types, stubs, plugins, and tools to work with them.
* [pyflakes](https://github.com/PyCQA/pyflakes) ⭐ 1,456 | 🐛 60 | 🌐 Python | 📅 2025-06-20 - A simple program which checks Python source files for errors.
* [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) ⭐ 1,278 | 🐛 1 | 📅 2026-07-21 - A curated list of awesome flake8 extensions.
* [complexipy](https://github.com/rohaquinlop/complexipy) ⭐ 818 | 🐛 10 | 🌐 Rust | 📅 2026-08-27 - An extremely fast Python library to calculate the cognitive complexity of Python files, written in Rust.
* [pyanalyze](https://github.com/quora/pyanalyze) ⭐ 386 | 🐛 61 | 🌐 Python | 📅 2026-01-27 - A tool for programmatically detecting common mistakes in Python code, such as references to undefined variables and some categories of type mismatches.
* [slotscheck](https://github.com/ariebovenberg/slotscheck) ⭐ 127 | 🐛 12 | 🌐 Python | 📅 2026-08-25 - Find mistakes in your `__slots__` definitions.
* [Typecheckers](https://github.com/ethanhs/python-typecheckers) ⭐ 74 | 🐛 1 | 📅 2026-03-19 - A list of Python type checkers.
* [flake8](https://gitlab.com/pycqa/flake8) - is a python tool that glues together pep8, pyflakes, mccabe, and third-party plugins to check the style and quality of python code.

## Test Runners

* [Nox](https://github.com/theacodes/nox) ⭐ 1,552 | 🐛 71 | 🌐 Python | 📅 2026-08-18 - is a command-line tool that automates testing in multiple Python environments, similar to tox. Unlike tox, Nox uses a standard Python file for configuration.
* [green](https://github.com/CleanCut/green) ⭐ 805 | 🐛 8 | 🌐 Python | 📅 2024-11-12 - A clean, colorful test runner.
* [tox](https://tox.readthedocs.io/en/latest) - Auto builds and tests distributions in multiple Python versions.

## Testing Frameworks

* [Robot Framework](https://github.com/robotframework/robotframework) ⭐ 11,847 | 🐛 300 | 🌐 Python | 📅 2026-08-26 - A generic test automation framework.
* [pytest-django](https://github.com/pytest-dev/pytest-django) ⭐ 1,544 | 🐛 185 | 🌐 Python | 📅 2026-08-10 - A pytest plugin for Django applications.
* [Ward](https://github.com/darrenburns/ward) ⚠️ Archived - is a modern test framework for Python with a focus on productivity and readability.
* [nose2](https://github.com/nose-devs/nose2) ⭐ 826 | 🐛 45 | 🌐 Python | 📅 2026-08-24 - The successor to `nose`, based on `unittest2`.
* [maelstrom](https://github.com/maelstrom-software/maelstrom) ⭐ 733 | 🐛 190 | 🌐 Rust | 📅 2025-04-23 - Maelstrom is a fast Rust and Python test runner that runs every test in its own container. Tests are either run locally or distributed to a clustered job runner.
* [awesome-pytest](https://github.com/augustogoulart/awesome-pytest) ⭐ 574 | 🐛 5 | 📅 2026-06-24 - A curated list of awesome pytest resources.
* [promptimize](https://github.com/preset-io/promptimize) ⭐ 498 | 🐛 17 | 🌐 Python | 📅 2026-05-25 - a prompt engineering evaluation and testing toolkit. It accelerates and provides structure around prompt engineering at scale with confidence, bringing some of the ideas behind test-driven development (TDD) to engineering prompts.
* [testbook](https://github.com/nteract/testbook) ⭐ 434 | 🐛 46 | 🌐 Python | 📅 2024-08-25 - A unit testing framework extension for testing code in Jupyter Notebooks.
* [xdoctest](https://github.com/Erotemic/xdoctest) ⭐ 222 | 🐛 28 | 🌐 Python | 📅 2026-07-14 - A rewrite of Python's builtin doctest module (with pytest plugin integration) with AST instead of REGEX.
* [async-asgi-testclient](https://github.com/vinissimus/async-asgi-testclient) ⭐ 161 | 🐛 15 | 🌐 Python | 📅 2023-06-29 - A framework-agnostic library for testing ASGI web applications.
* [hammett](https://github.com/boxed/hammett) ⭐ 97 | 🐛 7 | 🌐 Python | 📅 2024-09-23 - Fast python test runner, compatible with a subset of pytest.
* [vedro](https://github.com/vedro-universe/vedro) ⭐ 45 | 🐛 22 | 🌐 Python | 📅 2026-07-24 - Pragmatic testing framework for Python
* [perftester](https://github.com/nyggus/perftester) ⭐ 43 | 🐛 12 | 🌐 Python | 📅 2026-02-04 - A lightweight framework for performance testing of Python functions; allows for testing of performance in terms of execution time and memory usage.
* [tryke](https://github.com/thejchap/tryke) ⭐ 41 | 🐛 17 | 🌐 Rust | 📅 2026-08-01 - A Rust-based Python test runner with a Jest-style API
* [rut](https://github.com/schettino72/rut) ⭐ 13 | 🐛 2 | 🌐 Python | 📅 2026-07-30 - A modern and fully-featured test runner for Python's unittest framework (not `pytest`), with simplicity as a core design goal.
* [sundew](https://github.com/devenjarvis/sundew/) ⚠️ Archived - Sundew is a testing framework for Python, implementing a new approach to testing. One that combines functional programming concepts and the general best practices for writing tests that we already know, and enforces them in a way that enables some really powerful features that make testing easier, enjoyable, and more effective.
* [Sphinx-testify](https://github.com/BasicWolf/sphinx-testify) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2026-08-28 - Testified documentation means that the documentation source references test results, and these references are verified during the build process. As a result, we can keep every paragraph even every sentence of the documentation aligned with the code, as long as there is a test that "testifies" the described behaviour.
* [pytest-conversational](https://github.com/golikovichev/pytest-conversational) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - A pytest plugin for testing rule-based chatbots and conversational UIs through multi-turn dialogue assertions, with no LLM dependency.
* [doctest](https://docs.python.org/3/library/doctest.html) - (Python standard library) The doctest module searches for pieces of text that look like interactive Python sessions, and then executes those sessions to verify that they work exactly as shown.
* [pytest](https://docs.pytest.org/en/latest) - A mature full-featured Python testing tool.
* [unittest](https://docs.python.org/3/library/unittest.html) - (Python standard library) Unit testing framework.

## Tools

* [Pynguin](https://github.com/se2p/pynguin) ⭐ 1,384 | 🐛 8 | 🌐 Python | 📅 2026-08-27 - A tool that allows developers to generate unit tests automatically.
* [CrossHair](https://github.com/pschanely/CrossHair) ⭐ 1,318 | 🐛 76 | 🌐 Python | 📅 2026-08-19 - An analysis tool for Python that blurs the line between testing and type systems.
* [Klara](https://github.com/usagitoneko97/klara) ⭐ 268 | 🐛 3 | 🌐 Python | 📅 2022-03-28 - Static analysis tools to automatic generate test case, based on SMT (z3) solver, with a powerful ast level inference system.
* [Pifpaf](https://github.com/jd/pifpaf) ⭐ 204 | 🐛 16 | 🌐 Python | 📅 2026-08-03 - A suite of fixtures and a command-line tool that allows to start and stop daemons for a quick throw-away usage. This is typically useful when needing these daemons to run integration testing.
* [importlab](https://github.com/google/importlab) ⚠️ Archived - A library that automatically infers dependencies for Python files. Importlab's main use case is to work with static analysis tools that process one file at a time, ensuring that a file's dependencies are analysed before it is.
* [logot](https://github.com/etianen/logot) ⭐ 127 | 🐛 12 | 🌐 Python | 📅 2026-06-22 - Test whether your code is logging correctly.
* [teyit](https://github.com/isidentical/teyit) ⭐ 106 | 🐛 11 | 🌐 Python | 📅 2022-10-29 - A static analyzer and a refactoring tool to rewrite your unittest assertions in the right way.
* [pytestify](https://github.com/dannysepler/pytestify) ⭐ 59 | 🐛 10 | 🌐 Python | 📅 2026-08-17 - Automatically convert unittests to pytest.
* [pytest-databases](https://github.com/litestar-org/pytest-databases) ⭐ 58 | 🐛 16 | 🌐 Python | 📅 2026-07-22 - Reusable database fixtures for any and all databases.
* [pytest-mock-generator](https://github.com/pksol/pytest-mock-generator) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2024-06-02 - A pytest fixture wrapper for `mock_autogen`.
* [ttsproof](https://github.com/Mormolykos/ttsproof) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-08-25 - Automated failure-mode QA for text-to-speech systems. Structural audio checks, equivalence-aware WER/CER, and ASR-uncertainty quarantine so transcription noise is not reported as a synthesis defect.
* [pytest-test-observer](https://github.com/shakhov-dmitrii/pytest-test-observer) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2026-08-12 - A pytest plugin that ships per-test results to ClickHouse for trend analysis, flakiness tracking, and CI observability.
* [secure-log2test](https://github.com/golikovichev/secure-log2test) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-08-24 - A CLI tool that converts Kibana JSON log exports into runnable pytest regression suites, with Pydantic-based redaction of authorization headers and other secrets at parse time.
* [greenproof](https://github.com/zxyasfas/greenproof) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-07-31 - Checks whether a coding agent's green pytest run was earned, not manufactured by editing the tests. Snapshots the original tests, then reruns the agent's current code against them to see if it still passes.
* [quick-gate-python](https://github.com/hermes-labs-ai/quick-gate-python) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2026-08-25 - A deterministic CI quality gate that normalizes Ruff, Pyright, and pytest results into one fail-fast decision, attempts bounded auto-repair, and escalates with machine-readable evidence when it can't finish safely. PyPI: `pygate-ci`.
* [ghostwriter](https://hypothesis.readthedocs.io/en/latest/ghostwriter.html) - Writing tests with Hypothesis frees you from the tedium of deciding on and writing out specific inputs to test.

## UI Testing

* [SeleniumBase](https://github.com/seleniumbase/SeleniumBase) ⭐ 12,961 | 🐛 14 | 🌐 Python | 📅 2026-08-26 - is an all-in-one Python framework for automated browser testing. Tests are run with "pytest", and use WebDriver APIs for web-page interaction.
* [PyAutoGUI](https://github.com/asweigart/pyautogui) ⭐ 12,669 | 🐛 584 | 🌐 Python | 📅 2024-08-20 - is a cross-platform GUI automation Python module for human beings.
* [helium](https://github.com/mherrmann/selenium-python-helium) ⭐ 8,323 | 🐛 55 | 🌐 Python | 📅 2026-08-10 - is great for web automation. Helium makes it easier to use.
* [splinter](https://github.com/cobrateam/splinter) ⭐ 2,753 | 🐛 58 | 🌐 Python | 📅 2025-08-16 - Open source tool for testing web applications.
* [sixpack](https://github.com/seatgeek/sixpack) ⭐ 1,754 | 🐛 89 | 🌐 Python | 📅 2022-08-21 - A language-agnostic A/B Testing framework.
* [Lost Pixel](https://github.com/lost-pixel/lost-pixel) ⚠️ Archived - is an open source visual regression testing tool. Run visual regression tests on your Storybook and Ladle stories and on your application pages.
* [Flybirds](https://github.com/ctripcorp/flybirds) ⭐ 915 | 🐛 35 | 🌐 Python | 📅 2025-08-27 - is a front-end UI automation test framework based on BDD mode, providing a series of out-of-the-box tools and complete documentation.
* [Agent QA](https://github.com/vostride/agent-qa) ⭐ 869 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - A Node-based, open-source, self-improving QA agent that can exercise Python web applications externally through natural-language browser tests, persistent testing context, and self-healing tests.
* [selene](https://github.com/yashaka/selene) ⭐ 733 | 🐛 123 | 🌐 Python | 📅 2026-08-09 - User-oriented Web UI browser tests in Python (Selenide port).
* [Golem](https://github.com/golemhq/golem) ⚠️ Archived - is a test framework and a complete tool for browser automation. Tests can be written with code in Python, codeless using the web IDE, or both.
* [pytest-ui-automatic](https://github.com/moyu6027/pytest-ui-automatic) ⭐ 18 | 🐛 1 | 🌐 Python | 📅 2022-10-16 - Playwright Python tool practice pytest pytest-bdd screen-play page-object allure cucumber-report.
* [pomcorn](https://github.com/saritasa-nest/pomcorn) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2026-08-27 - is an open source Python package that contains base classes to create systems based on Selenium framework and Page Object Model pattern
* [HMNextAuto](https://github.com/ziguiway/hmnextauto) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2026-08-26 - Python-based UI automation framework for HarmonyOS NEXT. API compatible with uiautomator2, supports XPath, image recognition, performance monitoring and notification management.
* [LuluTest](https://github.com/erik-whiting/LuluTest) ⭐ 16 | 🐛 6 | 🌐 Python | 📅 2024-06-18 - is an open source browser automation framework using Python and Selenium.
* [squape](https://github.com/CyberAlpaca/squish-api-python-extension) ⭐ 7 | 🐛 2 | 🌐 Python | 📅 2024-07-05 - is a package that extends Squish API providing convenience tools for everyday automated test cases development.
* [aria-testing](https://github.com/t-strings/aria-testing) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-12-11 - Accessibility-focused DOM testing library for tdom, built with modern Python 3.14+.
* [Selenium](https://pypi.org/project/selenium) - Python bindings for [Selenium](http://www.seleniumhq.org/) WebDriver.

## Resources

### Articles

* [Anna-Lena Popkes: "Mocking in Python"](https://alpopkes.com/posts/python/mocking/) - Mocking might seem confusing in the beginning but once you understand the basics it can be very helpful.
* [async test patterns for Pytest](https://tonybaloney.github.io/posts/async-test-patterns-for-pytest-and-unittest.html) - Learn some handy async examples and patterns for testing in Pytest.
* [Getting Started With Property-Based Testing in Python With Hypothesis and Pytest](https://semaphore.io/blog/property-based-testing-python-hypothesis-pytest)
* [How not to footgun yourself when writing tests](https://www.marwansarieddine.com/posts/flaky_tests) - a showcase of flaky tests
* [Stargirl Flowers: “My Python testing style guide”](https://blog.thea.codes/my-python-testing-style-guide) - An attempt to catalog some practices around testing Python projects. It's not meant to be treated as dogma.
* [Test & Code: Python Testing](https://testandcode.com/) - Test & Code is a weekly podcast hosted by Brian Okken. The show covers a wide array of topics including software engineering, development, testing, Python programming, and many related topics.
* [Testing your Python Code with Hypothesis](https://www.inspiredpython.com/course/testing-with-hypothesis/testing-your-python-code-with-hypothesis) - A look at how Hypothesis can help you discover errors in your code.
* [Patterns of flakey Python tests](https://tech.octopus.energy/news/2022/05/23/flakey-python-tests.html) - This post details several patterns that cause flakey Python tests. Being aware of these common causes can help when investigating your own flakey tests.
* [Unit testing Python code in Jupyter notebooks](https://www.wrighters.io/unit-testing-python-code-in-jupyter-notebooks) - This article covers several options for unit testing Python code in a Jupyter notebook.
* [30 best practices for software development and testing](https://opensource.com/article/17/5/30-best-practices-software-development-and-testing) - These software engineering rules and testing best practices might help save you time and headaches.

### Books

* [Architecture Patterns with Python](https://www.oreilly.com/library/view/architecture-patterns-with/9781492052197) (O'Reilly)
* [Crafting Test-Driven Software with Python](https://www.packtpub.com/product/crafting-test-driven-software-with-python/9781838642655) (Packt)
* [pytest Quick Start Guide](https://www.packtpub.com/product/pytest-quick-start-guide/9781789347562) (Packt)
* [Python Testing with pytest](https://pragprog.com/titles/bopytest2/python-testing-with-pytest-second-edition) (Pragmatic Bookshelf)
* [Python Testing with Selenium](https://link.springer.com/book/10.1007/978-1-4842-6249-8) (Apress)
* [Python Unit Test Automation](https://www.oreilly.com/library/view/python-unit-test/9781484226766) (O'Reilly)
* [Testing In Python](https://www.amazon.com/Testing-Python-Robust-Professionals/dp/B0857CFM17) (Independently published)
* [Testing Python](https://www.amazon.com/Testing-Python-Applying-Unit-Acceptance/dp/1118901223) (Wiley)
* [Test-Driven Development with Python](https://www.oreilly.com/library/view/test-driven-development-with/9781491958698) (O'Reilly)

### Videos

* [PyCascades 2023 - Talk - Brian Okken: "Sharing is Caring - Sharing pytest Fixtures"](https://youtu.be/kevcz8NRcQU)
* [PyCon US 2023 - Talk - Dan Craig: Testing Spacecraft with Pytest](https://youtu.be/spCOYV4KyPA)
* [PyCon US 2023 - Talk - Dave Aronson: Kill All Mutants! (Intro to Mutation Testing)](https://youtu.be/G0MbITvWfgY)
* [PyCon US 2023 - Talk - Shai Geva: 10 Ways To Shoot Yourself In The Foot With Tests](https://youtu.be/Ub31Ae6S1BY)
* [PyCon US 2023 - Tutorial - Zac Hatfield-Dodds, Ryan Soklaski: Introduction to Property-Based Testing](https://youtu.be/YwYIDpze52s)

### Related

* [Awesome Python](https://github.com/vinta/awesome-python/blob/master/README.md#testing) ⭐ 316,549 | 🐛 16 | 🌐 Python | 📅 2026-08-25 - A curated list of awesome Python frameworks, libraries, software and resources.
* [Python test automation](https://github.com/atinfo/awesome-test-automation/blob/master/python-test-automation.md) ⭐ 7,147 | 🐛 134 | 📅 2025-11-28 - A comprehensive curated list of python test automation frameworks, tools, libraries and software to help software engineers easily bootstrap test automation on python.
* [Awesome PyTest](https://github.com/augustogoulart/awesome-pytest) ⭐ 574 | 🐛 5 | 📅 2026-06-24 - Focused on pytest.
* [Awesome Mutation testing](https://github.com/theofidry/awesome-mutation-testing) ⭐ 469 | 🐛 2 | 📅 2026-08-27 - Mutation testing resources: how to make better code by introducing bugs
* [commit-check](https://github.com/commit-check/commit-check) ⭐ 71 | 🐛 4 | 🌐 Python | 📅 2026-08-26 - Check commit message formatting, branch naming, commit author, email, and more.
* [Awesome Behave](https://github.com/MathiasPaulenko/awesome-behave#readme) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - A curated list of Behave resources, tools, and libraries for Python BDD.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
