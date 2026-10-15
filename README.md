# Awesome-Web-Animation-Libraries

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Web-Animation-Libraries

# Top Web Animation Libraries Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Timeline Animation, Motion Design, Lottie/Rive Playback, UI Transitions & SVG Animation on the Web*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Web Animation Libraries**. These tools power UI motion, scroll storytelling, SVG morphing, and designer-exported animations in the browser.

**Examples** include GreenSock (GSAP), LottieFiles, Framer Motion / Motion, Anime.js, Jitter, SVGator, Mo.js, Rive, Animate.css, Bannerbear, and community CSS animation frameworks.

**Open-source emphasis**: Runtime animation libraries are largely open. **Motion** (formerly Framer Motion), **Anime.js**, **Lottie**, **Animate.css**, **Popmotion**, and **Auto-Animate** are MIT/open options. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[LottieFiles, Rive (editor/cloud), SVGator, Jitter](https://lottiefiles.com/)**  
  Design-to-web animation platforms—create, host, and export Lottie, Rive, or SVG animations for products and marketing sites.

- **[Bannerbear, other programmatic image/video motion APIs](https://www.bannerbear.com/)**  
  Automated creative and motion generation services for personalized banners and social assets.

- **[GSAP (Webflow-backed distribution)](https://gsap.com/)**  
  Industry-standard timeline animation library—free to use under its license terms; closed-source core with extensive plugin ecosystem.

- **[Other commercial motion tools](https://rive.app/)**  
  Additional editor SaaS and animation marketplaces.

## Open-Source GitHub Projects

### JavaScript / Framework Motion Libraries

- **[Motion (formerly Framer Motion)](https://github.com/motiondivision/motion)**  
  Leading open-source animation library for React, JavaScript, and Vue—springs, gestures, layout animations, and hybrid WAAPI engine (MIT).

- **[Anime.js](https://github.com/juliangarnier/anime)**  
  Lightweight open JavaScript animation library—CSS, SVG, DOM, and JavaScript object timelines with a small footprint.

- **[Popmotion / Pose lineage](https://github.com/Popmotion/popmotion)**  
  Open low-level animation primitives used by higher-level motion libraries.

- **[React Spring](https://github.com/pmndrs/react-spring)**  
  Open spring-physics animation library for React—natural motion and strong 3D/React Three Fiber integration.

- **[Auto-Animate](https://github.com/formkit/auto-animate)**  
  Open zero-config animation utility for smooth list and layout transitions with minimal code.

- **[Motion One](https://github.com/motiondivision/motion)**  
  Related open WAAPI-first animation toolkit in the Motion family.

### Lottie, Vector & CSS

- **[Lottie (lottie-web)](https://github.com/airbnb/lottie-web)**  
  Open runtime for playing After Effects animations exported as JSON—standard for designer-to-dev motion on the web.

- **[dotLottie / community players](https://github.com/dotlottie)**  
  Open next-generation Lottie packaging and players—smaller files and extended features.

- **[Animate.css](https://github.com/animate-css/animate.css)**  
  Cross-browser open CSS animation library—ready-made utility classes for common effects.

- **[Mo.js](https://github.com/mojs/mojs)**  
  Open motion graphics library for the web—declarative shapes, timelines, and burst effects.

- **[Rive runtimes (open players)](https://github.com/rive-app/rive-react)**  
  Open runtime libraries for playing Rive files on web and other platforms (editor remains commercial).

- **[GSAP community plugins / wrappers](https://github.com/search?q=gsap)**  
  Community integrations; note GSAP core licensing differs from fully open MIT libraries.

- **[CSS animation frameworks & utilities](https://github.com/search?q=css+animation+framework)**  
  Community CSS-first animation kits and Tailwind motion plugins.

### Additional Strong Open-Source Options

- **React UI motion**: Motion (`motion/react`).
- **Lightweight timelines**: Anime.js.
- **Designer-exported motion**: Lottie / dotLottie players.
- **CSS-only**: Animate.css or custom `@keyframes` + WAAPI.
- **Physics springs**: React Spring.
- **Composable stacks**: Design in LottieFiles/Rive → open player; or code timelines in Motion/Anime/GSAP.
- Commercial editors still lead for visual motion design workflows and asset marketplaces.

**Frameworks for building custom systems**:  
**Motion** for React/Vue UI; **Anime.js** for general JS timelines; **lottie-web** for After Effects exports; **Animate.css** for quick CSS effects.  
Prefer open runtimes when license predictability matters; check GSAP’s current license for commercial products that compete with its owner’s tools.  
Fully open animation stacks are production-ready for most product UIs and marketing sites.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Respect `prefers-reduced-motion` and provide non-animated fallbacks. Heavy animation can harm performance and accessibility. Verify license terms (especially GSAP) for your use case.
- Open-source libraries offer transparent licensing and community maintenance. Design SaaS platforms shift authoring UX to the vendor. Neither replaces thoughtful motion design and performance budgets.

---

**Made for frontend engineers, motion designers, and teams who make interfaces feel alive.**  
Let's expand open web animation while recognizing the design tooling that commercial motion platforms deliver.
