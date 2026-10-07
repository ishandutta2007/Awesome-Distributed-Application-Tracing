# Awesome-Distributed-Application-Tracing

# Awesome-Distributed-Application-Tracing 🔍 📊



<p align="center">

  <img src="assets/banner.svg" alt="Awesome Distributed Application Tracing Banner" width="100%">

</p>



<p align="center">

  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>

  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>

  <a href="https://github.com/ishandutta2007/Awesome-Distributed-Application-Tracing"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Distributed-Application-Tracing?style=social" alt="GitHub_Stars"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-Distributed-Application-Tracing/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Distributed-Application-Tracing?style=social" alt="GitHub Forks"/></a>

  <a href="https://github.com/ishandutta2007/Awesome-Distributed-Application-Tracing/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Distributed-Application-Tracing?color=blue" alt="License"/></a>

  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

</p>



---



## 🌟 Top Distributed Application Tracing Ecosystem



**Curated List of Commercial Tracing Platforms & Open-Source Distributed Tracing Tools**  

*Focused on OpenTelemetry Instrumentation, Span Collection, Trace Storage, Service Graph Analysis, Root Cause Analysis & Self-Hosted Tracing Backends*



**Last updated: October 2026** 📅



---



### 📌 Overview & SEO Summary

Welcome to the ultimate curated directory of **distributed application tracing platforms**, **open-source tracing backends**, and **observability frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *Datadog APM*, *Dynatrace*, and *Honeycomb*), or self-hostable open-source alternatives (like *Jaeger*, *Grafana Tempo*, and *SigNoz*), this list covers category leaders, OpenTelemetry-native pipelines, and privacy-respecting trace analytics.



**Key Market Context:**

- **Jaeger** is the **most widely deployed open-source distributed tracing backend**, with **21K+ GitHub stars** and **CNCF Graduated** status, powering Uber's production tracing.

- **Grafana Tempo** provides **high-scale trace storage** with **object storage-only backend**, **TraceQL query language**, and **deep integration with Grafana, Loki, and Prometheus**.

- **SigNoz** is the **leading open-source Datadog alternative**, with **22K+ GitHub stars**, **unified traces, metrics, and logs**, and **ClickHouse-powered high-cardinality storage**.



---



## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)

- [📊 Star History](#-star-history)

- [🤝 Support & Sponsorship](#-support--sponsorship)

- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)



---



## 🏢 SaaS / Commercial Platforms



The distributed tracing market spans **full-stack observability platforms** (Datadog, Dynatrace, New Relic) that bundle **APM, tracing, logs, and metrics**, **specialized tracing platforms** (Honeycomb, Lightstep) that focus on **high-cardinality trace analysis and debugging**, and **cloud provider tracing services** (AWS X-Ray) that provide **native integration with cloud infrastructure**. **AWS X-Ray** charges **$5.00 per million traces recorded** and **$0.50 per million traces retrieved** . **Datadog APM** charges **$31/host/month** for APM, with **indexed spans at $1.70/million after 5M included** . **Honeycomb** charges **$3.00 per million events** on the Pro tier . **Lightstep** uses **custom pricing** based on trace volume. **Lumigo** starts at **$99/month** for 100K spans. **Coralogix** uses **usage-based pricing** starting at **$0.20/GB for data ingestion**.



| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |

| :--- | :--- | :--- | :--- | :--- | :--- |

| **[AWS X-Ray](https://aws.amazon.com/xray/)** ☁️ | Amazon | ~$2.0 Trillion | **$5.00/million traces recorded**; **$0.50/million retrieved**  | **Free tier: 100,000 traces recorded + 1M retrieved/month**  | **AWS-native distributed tracing** — **Trace requests across AWS services** including Lambda, API Gateway, ECS, and EC2 . **Service map visualization** for dependency analysis . **Deep integration with CloudWatch and ServiceLens** . **The simplest tracing for AWS-native applications** . |

| **[Datadog APM](https://www.datadoghq.com/product/apm/)** 🐶 | Datadog Inc. | ~$40 Billion | **$31/host/month** (APM); **$35** (Pro); **$40** (Enterprise) | **14-day free trial**; no permanent free tier | **Full-stack observability with APM** — **Distributed tracing, code profiling, and continuous profiler** . **Indexed spans: $1.70/million after 5M included** . **Ingested spans: $0.10/GB after 750 GB included** . **The most widely deployed commercial APM** . |

| **[Dynatrace](https://www.dynatrace.com/)** 🔮 | Dynatrace | ~$15 Billion | **$0.04/hour per host** (Infrastructure); **$0.01/memory-GiB-hour** (Full-Stack) | **15-day free trial**; no permanent free tier | **Causal AI for root cause** — **Davis AI combines topology graph with causal analysis** . **PurePath technology** for code-level tracing without sampling . **Agentic remediation layer** for automated fixes . **The most advanced causal AI tracing platform** . |

| **[New Relic Trace](https://newrelic.com/)** 🚀 | New Relic Inc. | ~$5 Billion | **$99/user/month** (Standard); **$349/user/month** (Pro) | **Free tier: 100 GB/month ingest + 1 full platform user**  | **Consumption-based full-stack** — **$0.40/GB standard, $0.60/GB Data Plus** . **Distributed tracing with Infinite Tracing** for tail-based sampling . **25+ language agents, 700+ integrations** . **No per-host fees** . |

| **[Honeycomb](https://www.honeycomb.io/)** 🍯 | Honeycomb.io | Private | **Pro: from $130/month** (1.5B events); **$3.00/million events**  | **Free: up to 20M events/month, 100M metrics data points**  | **Event-based observability** — **High-cardinality debugging, BubbleUp analysis** . **OpenTelemetry-native** . **The best tool for debugging complex distributed systems** . |

| **[Lightstep (ServiceNow)](https://lightstep.com/)** 💡 | ServiceNow | ~$150 Billion | **Custom pricing** (trace volume) | **Free: 100M spans/month**  | **Distributed tracing with change intelligence** . **OpenTelemetry-native** . **The most developer-friendly commercial tracing platform** . |

| **[Lumigo](https://lumigo.io/)** 🔬 | Lumigo | Private | **$99/month** (100K spans)  | **Free tier: 100K spans/month**  | **Serverless-first observability** — **Distributed tracing for Lambda and containers** . **Automatic root cause analysis** . **The most serverless-optimized tracing platform** . |

| **[Coralogix](https://coralogix.com/)** 🔵 | Coralogix | Private | **Usage-based** from **$0.20/GB** (ingestion)  | **Free tier: 1 GB/day**  | **Full-stack observability** — **Tracing, logging, and metrics** in one platform . **Data streaming for long-term retention** . **The most cost-effective commercial tracing platform** . |

| **[Grafana Cloud Traces](https://grafana.com/products/cloud/traces/)** 🟠 | Grafana Labs | ~$3 Billion | **Free: 50 GB traces/month**; **Paid from $0.05/GB**  | **Free: 50 GB traces/month, 14-day retention**  | **Managed Grafana Tempo** — **Object storage-based trace storage** . **TraceQL query language** . **Deep integration with Grafana, Loki, and Prometheus** . |



---



## 🔓 Open-Source GitHub Projects



*Sorted by GitHub_Stars_Count (Descending)* 🌟



- **[Jaeger](https://github.com/jaegertracing/jaeger)** [![Stars](https://img.shields.io/github/stars/jaegertracing/jaeger?style=social&color=white)](https://github.com/jaegertracing/jaeger/stargazers)  

  **Distributed tracing platform by Uber**, Apache-2.0 licensed. **21K+ GitHub stars** — **the most widely deployed open-source tracing backend** . **End-to-end distributed tracing, root cause analysis, service dependency analysis** . **OpenTelemetry-native** . **CNCF Graduated project** . **The definitive open-source distributed tracing platform** — battle-tested at Uber's scale. 🕵️



- **[Grafana Tempo](https://github.com/grafana/tempo)** [![Stars](https://img.shields.io/github/stars/grafana/tempo?style=social&color=white)](https://github.com/grafana/tempo/stargazers)  

  **High-scale distributed tracing backend**, AGPL-3.0 licensed. **5K+ GitHub stars** — **cost-efficient trace storage** that only requires **object storage** . **TraceQL query language** for trace analysis . **Deep integration with Grafana, Loki, and Prometheus** . **The most cost-effective open-source tracing backend** . 📈



- **[SigNoz](https://github.com/SigNoz/signoz)** [![Stars](https://img.shields.io/github/stars/SigNoz/signoz?style=social&color=white)](https://github.com/SigNoz/signoz/stargazers)  

  **Open-source Datadog alternative with OpenTelemetry-native APM**, Apache-2.0 licensed. **22K+ GitHub stars** — **unified logs, traces, and metrics** in a single pane . **ClickHouse-powered for high-cardinality data** . **Built-in dashboards, alerts, and exception tracking** . **Thoughtworks Technology Radar: Trial** . **The most complete open-source observability platform** . 📊



- **[Apache SkyWalking](https://github.com/apache/skywalking)** [![Stars](https://img.shields.io/github/stars/apache/skywalking?style=social&color=white)](https://github.com/apache/skywalking/stargazers)  

  **Observability platform for distributed systems**, Apache-2.0 licensed. **24K+ GitHub stars** — **APM, service mesh telemetry, eBPF profiling, and metrics aggregation** . **Designed for cloud-native, microservices, and containerized architectures** . **CNCF Graduated project** . 🌌



- **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)** [![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector?style=social&color=white)](https://github.com/open-telemetry/opentelemetry-collector/stargazers)  

  **Vendor-neutral observability framework**, Apache-2.0 licensed. **The emerging standard for telemetry collection** — **100+ instrumentation libraries across languages** . **Supported natively by Datadog, New Relic, Dynatrace, Elastic, Splunk, Honeycomb, and Instana** . **The foundation of modern tracing pipelines** . 🔭



- **[OpenObserve](https://github.com/openobserve/openobserve)** [![Stars](https://img.shields.io/github/stars/openobserve/openobserve?style=social&color=white)](https://github.com/openobserve/openobserve/stargazers)  

  **Cloud-native observability platform**, Apache-2.0 licensed. **12K+ GitHub stars** — **logs, metrics, traces, and RUM** in one platform . **140x lower storage costs than Elasticsearch** . **Rust-based, single binary** . **The most storage-efficient open-source tracing backend** . 🌊



- **[Uptrace](https://github.com/uptrace/uptrace)** [![Stars](https://img.shields.io/github/stars/uptrace/uptrace?style=social&color=white)](https://github.com/uptrace/uptrace/stargazers)  

  **Open-source APM with OpenTelemetry**, BSD-2-Clause licensed. **3K+ GitHub stars** — **distributed tracing, metrics, and logs** in a unified platform . **ClickHouse-based** — **processes billions of spans on a single server at 10x lower cost** . **50+ pre-built dashboards, Grafana compatibility** . 📉



- **[Hypertrace](https://github.com/hypertrace/hypertrace)** [![Stars](https://img.shields.io/github/stars/hypertrace/hypertrace?style=social&color=white)](https://github.com/hypertrace/hypertrace/stargazers)  

  **Observability platform for cloud-native apps**, Apache-2.0 licensed. **1.5K+ GitHub stars** — **distributed tracing, service graph, and trace-to-log correlation** . **Built on OpenTelemetry and Jaeger** . **The most complete open-source tracing platform** . 🔗



- **[Pinpoint](https://github.com/pinpoint-apm/pinpoint)** [![Stars](https://img.shields.io/github/stars/pinpoint-apm/pinpoint?style=social&color=white)](https://github.com/pinpoint-apm/pinpoint/stargazers)  

  **APM for large-scale distributed systems**, Apache-2.0 licensed. **13K+ GitHub stars** — **Java/PHP/Python agent-based monitoring** . **Call stack visualization, server map, and real-time active thread monitoring** . **The most mature Java tracing platform** . 📍



- **[Coroot](https://github.com/coroot/coroot)** [![Stars](https://img.shields.io/github/stars/coroot/coroot?style=social&color=white)](https://github.com/coroot/coroot/stargazers)  

  **Open-source observability with zero instrumentation**, Apache-2.0 licensed. **5K+ GitHub stars** — **eBPF-based metrics, logs, traces, profiles, and continuous profiling** . **Automatically detects anomalies and root causes** . **The only open-source tool combining all observability signals** . 🎯



---



## 🛠️ How to Contribute



Contributions are welcome! Follow these steps to submit new tracing platforms or open-source distributed tracing software:



1. 🍴 **Fork** the repository.

2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.

3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.

4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.



---



## 📊 Star History



[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Distributed-Application-Tracing&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Distributed-Application-Tracing&type=date&legend=top-left)



---



## 🤝 Support & Sponsorship



If you find this distributed tracing repository useful, please consider supporting the project:



- ⭐ **Star** this repository to increase visibility!

- 🔀 **Fork** and share with fellow SREs, platform engineers, and open-source advocates.

- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).



---



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️

- **AWS X-Ray charges $5.00 per million traces recorded** — **model your trace volume** before committing. **Datadog APM charges $31/host/month plus indexed span overages** at **$1.70/million after 5M included** . **Honeycomb charges $3.00 per million events** on Pro .

- **Jaeger is the most widely deployed open-source tracing backend** with **21K+ GitHub stars** and **CNCF Graduated** status. **Grafana Tempo provides the most cost-effective trace storage** with **object storage-only backend** . **SigNoz offers the most complete unified observability platform** .

- **Open-source tracing tools are not turnkey** — they require **deployment, storage configuration, and ongoing maintenance** . **Jaeger requires Cassandra or Elasticsearch** . **Tempo requires object storage** . **Always validate trace collection and query performance with a proof-of-concept** before production deployment . 🔍



---



<p align="center">

  <b>Made with ❤️ for SREs, platform engineers, and open-source distributed tracing advocates.</b>

</p>
