# Airline Digital Maturity Framework & Interpretation Guide

**Industry:** Passenger airlines (network, low-cost and regional carriers)
**Framework Designer (Member A):** Alifya Saify

## Why airlines

Digital maturity varies visibly across airlines, and failures are public. In December 2022, Southwest Airlines cancelled close to 17,000 flights after its crew-scheduling process collapsed. Crews had to phone in for new assignments and waited hours on hold, and the U.S. Department of Transportation later fined the airline $140 million. Over the same years, Delta Air Lines rolled out RFID bag tracking (from 2016) and a facial-recognition "Digital ID" at major hubs (from 2021). Alaska Airlines put the AI route-planning tool Flyways into dispatch, American Airlines introduced its AI-assisted Hub Efficiency Analytics Tool (HEAT), and United Airlines introduced ConnectionSaver to hold flights for connecting passengers. Airlines all fly the same aircraft under the same safety rules, yet their digital capability differs sharply, and that is what makes the industry diagnosable.

## The five dimensions

| # | Dimension | Generic domain it calibrates | Description |
|---|-----------|------------------------------|-------------|
| 1 | **Passenger & Operations Data Integration** | Data infrastructure | Whether passenger, crew, aircraft and maintenance data are connected into one trusted, timely picture. |
| 2 | **Digital Passenger Journey** | Customer interaction channels | How much of booking, check-in, airport processing, service and disruption handling a passenger can complete digitally. |
| 3 | **Operations & Disruption Automation** | Operational automation | How far crew recovery, aircraft turns, baggage and compensation run on systems rather than phone calls, radios and paper. |
| 4 | **AI & Predictive Decisioning** | AI/ML deployment | Whether machine learning is in production for pricing, disruption prediction and customer communication, and governed once it is. |
| 5 | **Frontline Change Capacity** | Organizational change capacity | Whether pilots, flight attendants, gate and ramp staff shape, adopt and fully switch to new tools. |

**Independence test.** Each dimension can be high while another is low:
- **Journey high, Ops low:** in 2022 Southwest had a full-featured app while crew recovery still ran by phone.
- **Journey high, service channels thin:** Frontier Airlines dropped phone customer service in 2022 and moved support to digital channels. That shows a digital front end is a choice, independent of the operation behind it.
- **Data, Ops and AI high, Change low:** an airline can buy strong data, automation and AI tools and still see crews keep paper workarounds.

These are different root causes, not five labels for one capability.

## Stage 1–5 descriptions

Stages: **1 Initial · 2 Developing · 3 Defined · 4 Managed · 5 Optimizing.** Each stage describes an observable state, and each is a clear step up from the one before.

### 1. Passenger & Operations Data Integration
- **Stage 1:** Reservations, loyalty, crew and maintenance records sit in separate systems with no shared identifiers. During disruptions, teams coordinate by phone, radio and whiteboards, and technical logs are on paper.
- **Stage 2:** Records are matched by hand or in occasional batch jobs, and teams swap updates by email and spreadsheet. Paper tech logs are typed in after the flight, and IT runs the systems, but nobody owns the data.
- **Stage 3:** A central warehouse is loaded nightly, and a shared ops dashboard exists but is updated by hand. Electronic tech logs are used at main bases, and named owners hold documented definitions for each core data domain.
- **Stage 4:** A customer profile updated within minutes is visible to agents and the app, and an integrated ops platform receives automatic feeds from aircraft, crew and passenger systems. Electronic tech logs are fleet-wide, and data-quality metrics reach leadership monthly.
- **Stage 5:** The real-time data drives automated decisions: rebooking priority, network re-planning and maintenance alerts from in-flight sensor data. Automated monitoring catches data-quality breaks, and the metrics are tied to operational KPIs.

### 2. Digital Passenger Journey
- **Stage 1:** There is no app. Cancelled passengers queue at the counter or call, service is by phone and counter only, and documents are checked by hand twice.
- **Stage 2:** The app shows bookings and status only, and rebooking happens by call-back. Email help takes days, and kiosks exist but bags go to a staffed counter.
- **Stage 3:** Passengers check in, get mobile boarding passes, change seats and rebook themselves online. Live chat runs in business hours, and self bag drop is available at most hubs.
- **Stage 4:** Passengers are rebooked automatically and accept in the app, which also tracks bags live and sells extras. Messaging runs 24/7 and is linked to the booking, and some hubs offer a biometric or digital-ID option.
- **Stage 5:** The same app flow issues vouchers and reroutes bags, and a personalized trip timeline adapts as the day changes. A virtual assistant completes routine requests end to end, and biometric processing covers all major hubs.

### 3. Operations & Disruption Automation
- **Stage 1:** Crews are reassigned by phone and wait on hold, and aircraft turns run on radios and paper checklists. Bags carry paper tags and are traced by phone, and compensation claims arrive by letter.
- **Stage 2:** Crew software is used for planning but not for disruption recovery, and turn tasks are logged after the fact. Bags are scanned only at check-in and loading, and online claims are all reviewed by hand.
- **Stage 3:** Optimization software proposes crew reassignments for schedulers to approve, and ramp staff log turn milestones on tablets. Bags are scanned at every handover, and common claims are checked for eligibility automatically.
- **Stage 4:** Most crew reassignments are generated automatically and accepted in an app, and turn milestones are captured by sensors with late alerts. Bags are tracked continuously with misconnect alerts, and cancellation refunds trigger without a claim.
- **Stage 5:** Crew, aircraft and passenger plans are re-optimized together in real time, and staff are moved before a turn runs late. Misconnected bags are rerouted in advance, and all eligible compensation is paid automatically.

### 4. AI & Predictive Decisioning
- **Stage 1:** Fares come from fixed tables changed by hand, and the airline reacts to delays once they happen. There is no AI in customer communication and no model monitoring.
- **Stage 2:** A traditional revenue-management system is adjusted by analysts, and controllers check weather by hand. A scripted FAQ bot answers fixed questions, and problems with any model are caught only by chance.
- **Stage 3:** Revenue management uses demand forecasts, and dashboards show historical delay patterns. An AI assistant handles one defined task, and data scientists review models from time to time.
- **Stage 4:** Machine learning sets continuous prices across most of the network, and a model predicts delays or misconnects hours ahead and triggers action. Generative AI drafts passenger messages within guidelines, and models are monitored automatically by named owners.
- **Stage 5:** Personalized offers are built per customer and continuously A/B tested, and predictions drive automated network decisions with measured accuracy. Several AI assistants are monitored for accuracy and satisfaction under formal model governance.

### 5. Frontline Change Capacity
- **Stage 1:** Headquarters picks tools and staff hear at go-live, training is a memo, and the old paper or phone process runs on indefinitely. Nobody manages the people side of change.
- **Stage 2:** Staff are told in advance and asked for feedback after launch, and there is one training session. Old processes fade unevenly, and the project lead handles change work.
- **Stage 3:** Frontline and union representatives help select and test tools, and training is hands-on with station super-users. The old process gets a formal retirement date, and a change-management role exists for major projects.
- **Stage 4:** Frontline staff co-design tools, which are piloted at one station first, and champions at every base support ongoing training with usage tracked. Retirement of the old process is a measured success criterion.
- **Stage 5:** A standing frontline innovation program exists, leaders' goals include adoption results, and training adapts from usage data. Past rollouts have fully retired old processes on schedule, and adoption is reported network-wide.

## Dimension calibration test

Real organizations at the low and high ends of each dimension, based on public reporting:

| Dimension | Low end (Stage 1–2) | High end (Stage 4–5) |
|-----------|---------------------|----------------------|
| Passenger & Operations Data Integration | Southwest Airlines, Dec 2022: crew locations and assignments could not be matched to aircraft, so schedulers worked by phone | Delta Air Lines: bag, passenger and identity data connected across the app, RFID tracking and Digital ID |
| Digital Passenger Journey | Carriers without an app or self bag drop (typical of small regional operators) | Delta Air Lines: in-app bag tracking and biometric Digital ID from bag drop to boarding at major hubs |
| Operations & Disruption Automation | Southwest Airlines, Dec 2022: crew recovery by phone, with hours-long hold times | Delta Air Lines: RFID bag tracking since 2016; American Airlines: automated gate and hub tools (Smart Gating, HEAT) |
| AI & Predictive Decisioning | Carriers using fixed fare tables and reactive delay handling | Alaska Airlines (Flyways AI route planning), United Airlines (ConnectionSaver; AI-drafted delay messages) |
| Frontline Change Capacity | Southwest Airlines: pilot and flight-attendant unions had publicly warned about the scheduling system before the 2022 collapse | *Team to verify a named example; the Stage 4–5 criteria above define what to look for* |

---

# Interpretation Guide

**How the tool scores.** Every answer carries an integer value from 1 to 5. A dimension score is the average of its four answers, so scores move in steps of 0.25. The results always name the two lowest dimensions. If two or more tie for lowest, all tied dimensions are shown, and a tie is never broken by list order.

**Which profile is shown**
1. **Uniform shapes first.** If every dimension is ≤ 2.5, show *Grounded Legacy Carrier*. If every dimension is ≥ 3.5, show *Digitally Airborne Network*.
2. **Otherwise, pattern profiles.** The candidates are *Siloed Flight Deck*, *Tools the Frontline Won't Fly* and *Slick App, Legacy Brain*. The one whose key dimension scores lowest wins.
3. **If tied, the airline priority decides.** *Data* comes first, because every recovery tool depends on it. *Change* comes second, because unionized, safety-critical crews route around imposed tools. *Customer vs AI gap* comes third.
4. **If no archetype matches,** the tool says so and lists concrete next steps for the lowest dimensions.

The names, patterns, descriptions and actions below match the tool's `PROFILES` data word for word.

### 1. Grounded Legacy Carrier: uniformly low
**Pattern:** Every dimension scores 2.5 or below.

The airline still runs on phones, paper and disconnected systems, so a single storm can cascade into days of recovery. Investing in AI or a flashier app now would sit on foundations that cannot feed it.

**Next action:** Fund an integrated operations-and-crew data platform first, with crew recovery moved off the phone as its first use case.

### 2. Digitally Airborne Network: uniformly high
**Pattern:** Every dimension scores 3.5 or above.

Capability is strong across the board; the gap to close is no longer technology but speed of learning. The next frontier is closing the loop: using predictions to re-plan the whole network automatically and personalizing every passenger's day of travel.

**Next action:** Set a network-wide target for disruptions resolved without a human touch, and track it alongside on-time performance and satisfaction.

### 3. Siloed Flight Deck: data lags everything else
**Pattern:** Passenger & Operations Data Integration is the lowest dimension (ties allowed) and at least 1.0 point below the average of the other four.

Good tools sit on top of data that does not connect: ops control, crew scheduling and customer service each see a different version of the day. This is the pattern behind cascading meltdowns, and it caps what any AI or app can do.

**Next action:** Stop adding new front-end or AI projects until reservation, crew and aircraft-status data flow into one shared, near-real-time operational picture.

### 4. Slick App, Legacy Brain: digitalized but not transforming
**Pattern:** Digital Passenger Journey scores 3.5 or above while AI & Predictive Decisioning scores 2.5 or below.

Passengers see a modern airline, but decisions behind the app are still made by hand and after the fact. The airline is digitalized, not transformed: the app reports a disruption well but cannot prevent one.

**Next action:** Pilot a disruption-prediction model that triggers proactive rebooking in the existing app, and measure misconnects avoided.

### 5. Tools the Frontline Won't Fly: the execution gap
**Pattern:** Frontline Change Capacity is the lowest dimension (ties allowed) and at least 1.0 point below the average of the other four.

The airline buys capable systems, but crews and agents keep the old workarounds. In a unionized, safety-critical workforce, tools imposed without frontline ownership are routed around, and the capability on paper never shows up on the ramp.

**Next action:** Before the next rollout, name frontline and union co-sponsors, pilot at one station, and make retiring the old process a go-live criterion.
