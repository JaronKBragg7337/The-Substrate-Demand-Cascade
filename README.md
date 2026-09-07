# The Substrate Demand Cascade

### How automation may increase compute demand twice: once through machines, and again through humans

**Author:** Jaron K. Bragg  
**Status:** Shared openly as a working hypothesis. In progress — a framework to test, not a settled prediction.  
**Date started:** September 7, 2026  

---

## A note before the hypothesis

This document is not arguing that automation will definitely produce mass leisure, that every displaced worker will retain purchasing power, or that digital demand must rise without limit.

The narrower claim is structural:

> **If automation materially reduces the amount of human labor required while people retain enough purchasing power to use digital services, then automation can increase digital-infrastructure demand through two separate channels at the same time: direct machine compute and indirect human utilization.**

The first channel is already obvious and heavily discussed: AI models, agents, robots, autonomous systems, inference, training, simulation, logistics, and machine coordination require compute.

The second channel is easier to miss: changing how humans spend their time can change how heavily they use the entire digital economy that already exists — streaming, gaming, social platforms, content creation, cloud services, markets, AI systems, communications, and whatever new services emerge.

The hypothesis is about the **interaction between those two channels**.

It is also not a claim that rebound effects, Jevons paradox, time-use economics, or data-center demand are new subjects. They are not. The contribution here is the specific synthesis: **automation can alter the human time budget, which can alter subscription utilization and digital activity, creating a second-order infrastructure demand cascade on top of the compute automation itself consumes.**

---

## 1. The hypothesis in one paragraph

Automation is normally modeled as a direct source of compute demand: more AI and robotics require more servers, accelerators, networking, storage, and electricity. But sufficiently large automation may also reallocate human time away from labor. If purchasing power remains available, some portion of that released time will likely move into digitally mediated activity — watching, playing, creating, communicating, trading, building, learning, and using AI. That raises utilization of infrastructure that is not itself "AI infrastructure." The result is a **substrate demand cascade**: automation consumes compute directly while simultaneously changing human behavior in ways that can increase demand for the broader digital substrate on which modern services run.

---

## 2. The spark

The thought came from a separate discussion about structural change.

The useful distinction was between events that happen *on top of* a system and changes that alter the **substrate the events run on**.

That immediately created a second question:

If AI and robotics change something as basic as the amount of time humans spend working, why would the downstream effect stop at employment?

It would not only change jobs.

It could change:

- how many hours people stream video,
- how many hours they play games,
- how much content they produce,
- how often they interact with AI,
- how much cloud storage they generate,
- how much social and communications traffic they create,
- how many digital businesses they operate,
- how much autonomous software works on their behalf,
- and how many services are used concurrently rather than sequentially.

That is where the hypothesis began.

---

## 3. The two demand channels

### Channel A — Direct machine demand

Automation itself consumes digital infrastructure.

Examples include:

- model training,
- inference,
- autonomous agents,
- robotics perception and planning,
- simulation,
- machine-to-machine communication,
- digital twins,
- logistics optimization,
- autonomous vehicles,
- industrial control,
- synthetic media generation,
- monitoring and telemetry.

This is the demand most people mean when they say "AI will require more data centers."

### Channel B — Indirect human demand

Automation can also change the human time budget.

If a person works fewer hours, stops commuting, or no longer performs some classes of labor, those hours do not disappear. They are reallocated.

Some may go to offline life. Some may go to sleep, family, exercise, or physical hobbies.

But some portion can move toward digital activity:

- video streaming,
- gaming,
- social media,
- live streaming,
- content production,
- digital markets,
- education,
- communities,
- AI interaction,
- virtual worlds,
- software creation,
- cloud-backed personal tools.

The second channel therefore does not require a new technology.

It can arise from **greater utilization of technologies and subscriptions that already exist.**

---

## 4. The subscription-utilization problem

A fixed-price subscription does not require every subscriber to generate the same cost.

Two customers can pay the same monthly price while producing radically different infrastructure load.

One person might open a service twice a week.

Another might use it for hours every day.

A subscription business can support this distribution when light and moderate users make up enough of the population and when the provider has accurately modeled average utilization and peak concurrency.

The structural question is what happens if the distribution itself shifts.

Today:

```text
large population
    ↓
some inactive users
many light/moderate users
fewer heavy users
very few extreme users
```

Possible automation-era shift:

```text
same or larger population
    ↓
fewer inactive users
more moderate users
many heavy users
many concurrent digital activities
```

The price of the subscription can remain unchanged while the **average cost-to-serve** changes.

That does not mean every service becomes unprofitable. Providers can respond through efficiency improvements, caching, price changes, tiering, quotas, advertising, local compute, better hardware, or new business models.

The point is simpler:

> **A subscription price is not a physical law. It is an economic arrangement built around an expected utilization distribution. Change the distribution enough and the arrangement has to adapt.**

---

## 5. COVID-19 as a partial natural experiment

COVID-19 was not automation, and it should not be treated as a direct forecast of an automated economy.

But it provides a useful test of one link in the chain:

> **Can a sudden change in how humans allocate their time materially change digital infrastructure demand?**

Yes.

Akamai reported that global Internet traffic increased by roughly **30% during March 2020**, describing it as approximately a year's normal growth compressed into a few weeks.

The OECD reported that some operators experienced Internet-traffic increases of **up to 60%** during the early COVID-19 crisis.

The mechanism was not "a new Internet was invented."

Human behavior changed abruptly:

- work moved online,
- school moved online,
- entertainment moved online,
- communication moved online,
- commerce moved online,
- creation and participation moved online.

The analogy has limits, but the supported part matters:

**time allocation and environment can move digital demand quickly.**

Sources:

- OECD — *Keeping the Internet up and running in times of crisis*  
  https://www.oecd.org/en/publications/keeping-the-internet-up-and-running-in-times-of-crisis_4017c4c9-en.html
- Akamai — *The Building Wave of Internet Traffic*  
  https://www.akamai.com/blog/security/the-building-wave-of-internet-traffic

---

## 6. Why Netflix is a useful example — and why it is not the same as AI

Different digital services have different marginal-cost structures.

Netflix is a useful example because watching more video clearly creates more delivery demand, but Netflix does not serve every stream by repeatedly performing an AI-scale computation in a central data center.

Its Open Connect system places caching appliances inside or near ISP networks, localizing substantial traffic and reducing long-haul transport.

Netflix states that it partners with more than a thousand ISPs and uses Open Connect Appliances both in ISP networks and in 60+ global data centers.

That means an additional hour of Netflix and an additional hour of frontier-model inference are **not equivalent units of compute**.

The correct principle is not:

> every extra digital hour costs the same.

It is:

> every major change in utilization changes some combination of compute, storage, delivery, network, edge, power, and capacity requirements — but the mixture depends on the service.

Source:

- Netflix Open Connect  
  https://openconnect.netflix.com/

---

## 7. The creator multiplier

Consumption is only one side of released human time.

People can also become producers.

A person watching a video primarily creates delivery demand.

A person producing digital media can trigger a much larger processing chain:

```text
capture
  ↓
upload
  ↓
transcode / process
  ↓
store
  ↓
moderate / classify
  ↓
recommend
  ↓
replicate / cache
  ↓
deliver to viewers
  ↓
collect analytics
  ↓
serve advertising / payments
```

Generative AI adds another layer.

One person can increasingly operate workflows that previously required a team:

- research,
- writing,
- code,
- graphics,
- video,
- audio,
- translation,
- customer interaction,
- analytics,
- distribution.

So greater free time does not only have the potential to increase **consumption**.

It can increase **production**, and production can create downstream workloads for many other users and systems.

---

## 8. The concurrency effect

There is another difference between a heavily automated future and earlier digital transitions.

Human activity and machine activity do not have to alternate.

They can run simultaneously.

A person can be:

- watching a stream,
- while an AI agent researches,
- while another agent writes code,
- while cloud storage synchronizes,
- while a robot performs a task,
- while a game or simulation maintains an online session,
- while background services continuously analyze data.

This creates a possible transition from:

> **one human → one foreground workload**

toward:

> **one human → multiple concurrent machine and digital workloads**

The important variable may therefore become not only **hours online per person**, but **active digital processes per person**.

---

## 9. A minimal formal model

Let:

- \(C_m\) = compute consumed directly by automated machines and AI systems
- \(T_f\) = discretionary human time released by automation
- \(p_d\) = fraction of released time allocated to digital activity
- \(c_d\) = average infrastructure cost per hour of that digital activity
- \(C_p\) = additional compute induced by digital production and downstream audiences
- \(E\) = efficiency gains that reduce infrastructure required per unit of activity
- \(B\) = bottlenecks or constraints that prevent demand from being served

A deliberately simplified representation is:

\[
\Delta C_{total}
=
\Delta C_m
+
(T_f \cdot p_d \cdot c_d)
+
\Delta C_p
-
E
-
B
\]

This is not intended as a predictive equation yet.

Its purpose is to force the complete causal structure onto the page.

The most common discussion includes only:

\[
\Delta C_{total} \approx \Delta C_m
\]

The Substrate Demand Cascade hypothesis says that this may omit a material indirect term.

---

## 10. Purchasing power is the load-bearing economic condition

More free time does **not** automatically mean more paid digital consumption.

If automation removes income faster than it removes the need for income, discretionary spending can fall.

That could reduce subscriptions even while people have more nominal free time.

So the strong version of this hypothesis requires some mechanism that preserves enough purchasing power:

- continued employment with fewer hours,
- falling prices,
- ownership of automated production,
- redistribution,
- public benefits,
- new labor categories,
- creator income,
- capital income,
- or another economic arrangement.

The hypothesis therefore has a boundary condition:

> **Released time becomes a strong digital-demand multiplier only when people retain the economic ability to use the resulting services.**

This is one of the most important ways the hypothesis could fail.

---

## 11. Current infrastructure evidence

The broader data-center buildout is already large before adding the full indirect mechanism proposed here.

The International Energy Agency's current outlook projects global data-center electricity consumption at roughly **950 TWh by 2030**, approximately double the 2025 level.

The IEA also expects electricity consumption from AI-focused data centers to **triple from 2025 to 2030** in its central projection.

Earlier IEA analysis explicitly described AI as the most important driver of data-center electricity-demand growth **alongside growing demand for other digital services**.

This matters because the hypothesis is not proposing that every future data center becomes an AI facility.

It proposes that automation can increase pressure across multiple infrastructure classes at once:

- accelerated AI servers,
- conventional servers,
- storage,
- CDNs,
- edge infrastructure,
- networking,
- fiber,
- cooling,
- power generation,
- transmission,
- substations,
- data-center construction.

Sources:

- IEA — *Key Questions on Energy and AI*  
  https://www.iea.org/reports/key-questions-on-energy-and-ai/executive-summary
- IEA — *Energy and AI: Executive summary*  
  https://www.iea.org/reports/energy-and-ai/executive-summary
- IEA — *Energy demand from AI*  
  https://www.iea.org/reports/energy-and-ai/energy-demand-from-ai

---

## 12. Relation to Jevons paradox and rebound effects

This hypothesis has clear relatives.

**Jevons paradox** describes situations where improvements in efficiency reduce the cost of using a resource enough that total consumption eventually increases rather than decreases.

**Rebound effects** more broadly describe cases where some of the expected savings from efficiency are offset by behavioral or economic responses.

Researchers are already applying this family of ideas to digitalization and AI infrastructure. A 2025 *Nature Cities* correspondence explicitly used the phrase **"digital Jevons paradox"** for data-center energy systems.

The Substrate Demand Cascade is not a replacement for those concepts.

Its narrower addition is the **human-time pathway**:

```text
automation
    ↓
less required human labor
    ↓
reallocated human time
    ↓
greater utilization / production in digital systems
    ↓
additional infrastructure demand
```

This can coexist with a traditional efficiency rebound:

```text
compute becomes cheaper
    ↓
more compute-intensive products become viable
    ↓
usage expands
    ↓
total compute demand rises
```

If both pathways occur, they can compound.

Sources:

- Wu, J. (2025), *Digital Jevons paradox in urban data center energy systems*, Nature Cities  
  https://www.nature.com/articles/s44284-025-00289-9
- Lange et al. / rebound-effect typology, *Energy Research & Social Science*  
  https://www.sciencedirect.com/science/article/pii/S221462962100075X

---

## 13. The cascade

The complete hypothesis can be represented as two interacting branches:

```text
                         AUTOMATION
                             │
              ┌──────────────┴──────────────┐
              │                             │
              ▼                             ▼
      DIRECT MACHINE LOAD            HUMAN TIME REALLOCATION
              │                             │
      AI inference                    less required labor
      robotics                        less commuting
      autonomous agents               changed daily routines
      simulation                            │
      machine coordination                  ▼
              │                       DIGITAL ACTIVITY
              │                             │
              │                 ┌───────────┼───────────┐
              │                 ▼           ▼           ▼
              │             consume       create       delegate
              │                 │           │           │
              │                 │           │        AI agents
              │                 │           │        autonomous
              │                 │           │        services
              │                 └─────┬─────┴─────┬─────┘
              │                       │           │
              └───────────────────────┴───────────┘
                                      │
                                      ▼
                         DIGITAL SUBSTRATE DEMAND
                                      │
                  ┌───────────────────┼───────────────────┐
                  ▼                   ▼                   ▼
             compute/storage       network/CDN        electricity
                  │                   │                   │
                  └───────────────────┼───────────────────┘
                                      ▼
                         PHYSICAL INFRASTRUCTURE
                                      │
                       chips • fiber • cooling
                       substations • generation
                       buildings • maintenance
```

The core proposition is therefore:

> **Automation can create a double demand shock: machines consume more digital infrastructure while the human behavioral changes caused by automation can increase utilization of the rest of the digital economy.**

---

## 14. What would make this stronger

This document currently establishes a plausible mechanism and identifies supporting observations.

It does **not** yet quantify the magnitude.

The next serious step would be to build a model using:

1. time-use data by employment status,
2. digital-media usage by available leisure time,
3. household disposable income,
4. subscription penetration and churn,
5. per-hour infrastructure intensity by service category,
6. creator-versus-consumer activity,
7. AI-agent concurrency per user,
8. efficiency improvement curves,
9. local versus cloud compute,
10. peak concurrency rather than only average consumption.

A useful output would be several scenarios rather than one forecast:

- **Income-loss case** — automation releases time but purchasing power falls.
- **Shorter-workweek case** — purchasing power mostly survives and leisure rises.
- **High-automation / high-income-support case** — large time release plus persistent digital purchasing power.
- **Local-compute case** — much of the new demand shifts from centralized data centers to personal/edge hardware.
- **Efficiency-dominant case** — hardware and software improvements outrun utilization growth.
- **Rebound-dominant case** — falling cost per unit creates enough new activity to overwhelm efficiency gains.

---

## 15. What could falsify or weaken the hypothesis

A useful hypothesis needs failure conditions.

The indirect cascade would be weaker than proposed if:

- displaced labor loses purchasing power and paid digital demand contracts;
- humans allocate most released time to offline activity;
- digital usage is already near saturation and extra free time adds little;
- local/on-device compute absorbs most new workloads;
- compression, caching, hardware efficiency, and software efficiency outpace demand growth;
- subscription providers aggressively meter or cap heavy usage;
- autonomous systems reduce rather than increase total digital activity;
- energy, grid, chip, water, permitting, or construction bottlenecks prevent latent demand from becoming actual consumption;
- demographic change reduces the number of high-utilization users;
- the relationship between free time and digital activity is substantially weaker than the COVID-era analogy suggests.

Any serious test of the hypothesis should look for these outcomes, not only evidence that confirms it.

---

## 16. Confidence tiers

### Solid

- AI and automation create direct compute demand.
- Non-AI digital services also depend on data-center, edge, storage, networking, and delivery infrastructure.
- Human behavioral shifts can rapidly alter Internet traffic; the COVID-19 period demonstrated this at large scale.
- Different subscribers generate very different utilization.
- Different digital workloads have different marginal infrastructure costs.
- Current data-center electricity demand is rising rapidly, with AI and other digital services both contributing.

### Strongly plausible but not yet quantified here

- A large increase in discretionary human time would change the utilization distribution of many digital services.
- More creator activity would produce downstream compute, storage, moderation, recommendation, and delivery demand.
- One person increasingly operating multiple concurrent agents and services can raise active workloads per person.

### Conditional

- Large-scale automation will substantially reduce required human work hours.
- Purchasing power will remain high enough for released time to translate into greater paid digital activity.
- The indirect human-utilization channel will be large relative to direct AI demand.

### Unknown

- The magnitude of the indirect effect.
- Which service categories would absorb the most released time.
- Whether centralized data centers, edge systems, or personal hardware would capture most of the resulting compute.
- Whether efficiency gains would dominate the utilization increase.
- Whether this effect is already incorporated adequately into long-term infrastructure forecasts.

---

## 17. The principle underneath

The deeper principle is broader than data centers:

> **When a technology changes the allocation of human time, forecasting only the technology's direct resource use can miss the resource demand created by the new behavior that fills the released time.**

AI is therefore not only a workload.

At sufficient scale, it can become a variable that changes the **behavior of the users of every other workload**.

That is why the relevant unit of analysis may not be:

> "How much compute does AI require?"

It may eventually have to become:

> **"How does automation change the total pattern of machine activity and human digital activity that the infrastructure must support?"**

---

## 18. Why this matters

The practical implication is not merely that more GPUs may be needed.

If the cascade is real at meaningful scale, demand can propagate into:

- semiconductor manufacturing,
- conventional servers,
- AI accelerators,
- memory and storage,
- cloud platforms,
- CDNs,
- edge caches,
- fiber,
- routers and switches,
- data-center land,
- cooling systems,
- water systems,
- substations,
- grid transmission,
- power generation,
- construction,
- roofing,
- coatings,
- maintenance,
- and eventually replacement cycles for all of the above.

The second-order demand may therefore appear in industries that do not look like "AI companies" at all.

---

## 19. The shortest version

**AI may increase data-center demand twice.**

First, because AI and robots require compute.

Second, because if automation changes how humans spend their time, humans may use far more of the digital infrastructure that already exists.

The first effect is a machine-compute problem.

The second is a human-behavior problem.

The infrastructure has to serve both.

---

## 20. Open questions

- How strongly does discretionary time predict digital-service use after controlling for income?
- Does unemployment behave differently from voluntary shorter workweeks?
- Which services show the highest utilization elasticity with respect to free time?
- How much heavier is the infrastructure footprint of creators than passive consumers?
- How many concurrent AI agents will an average person run?
- How quickly will inference move onto devices?
- Will fixed subscriptions survive extremely heavy average usage, or move toward metering?
- Can the effect be observed already among retirees, remote workers, creators, or populations with shorter workweeks?
- Do current data-center forecasts model behavioral changes from automation, or mostly direct workload growth?
- What happens when digital leisure demand and autonomous machine demand peak at the same time?

These are testable questions.

That is where this should go next.

---

## 21. Provenance and attribution

The synthesis in this document originated from Jaron K. Bragg's observation that discussions of AI infrastructure often count the compute used **by automation** without separately examining the compute induced when automation changes **human time allocation and utilization of other digital services**.

The surrounding concepts are not claimed as original:

- data-center demand forecasting is an established field;
- rebound effects and Jevons paradox are established concepts;
- time-use economics is established;
- subscription utilization modeling is standard business practice;
- Internet traffic changes during COVID-19 are documented;
- the direct compute demands of AI are extensively studied.

The proposed contribution is the bridge between them:

**automation → time reallocation → digital utilization shift → infrastructure demand, operating simultaneously with direct machine compute.**

---

## 22. A note on how this was written

The originating connection and hypothesis came from Jaron K. Bragg.

ChatGPT was used to help formalize the mechanism, separate supported claims from conditional ones, identify related research, structure the argument, and locate public sources.

The purpose of stating that plainly is provenance, not credentialing.

The hypothesis should stand or fail on whether the mechanism is coherent, measurable, and supported by evidence.

---

*End of Version 0.1 — September 7, 2026.*
