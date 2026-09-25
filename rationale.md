# Question Design Rationale: Airline Digital Maturity Assessment

| Team member | Role |
|-------------|------|
| Alifya Saify | Member A: Framework Designer |
| Disha Reddy | Member B: Question Author |
| Rishit Mathur | Member C: Tool Builder |
| Shima Kananiazari | *[Role to confirm]* |

<!-- RATIONALE-START -->
Our goal was inter-rater reliability: two people assessing the same airline should pick the same answer. Every question therefore asks about something an outsider could verify by watching one disrupted day (a system, a process step or who is involved), never about intent or effort. Each answer ladder follows the same five steps: manual, partly digital but siloed, standardized, integrated and measured network-wide, then predictive or automatic. The instruction "choose the highest option that is fully true today" stops respondents from scoring pilots or plans. We also avoided questions every airline would answer the same way. Almost every carrier sells tickets online, so we never ask whether it has a website.

**Passenger & Operations Data Integration.** An airline's data problem shows up during disruptions, when ops control, crew scheduling and customer service each need the same facts. We ask how passenger records are linked, how the three teams see one flight picture, how technical logs are captured, and who owns data quality. The Southwest Airlines collapse of December 2022 is the calibration point for the bottom of the scale: schedulers could not see where crews were. The top of the scale means the data itself triggers decisions.

**Digital Passenger Journey.** Instead of "is there an app," we ask what a passenger can actually do in it. The strongest question is cancellation rebooking, because it separates airlines where passengers queue at a counter from those that rebook automatically and reroute bags in the same flow. Service channels and airport processing complete the journey. Biometric boarding at major hubs, as Delta offers, marks Stage 5.

**Operations & Disruption Automation.** We chose four workflows specific to airlines: crew recovery, aircraft turnaround, baggage tracking and compensation. Crew recovery is the sharpest test in the industry, from crews waiting on hold to real-time re-optimization. Bag tracking has well-known levels: barcode scans at two points, scans at every handover, then continuous RFID tracking as Delta introduced. Compensation separates hand-reviewed claims from refunds issued automatically.

**AI & Predictive Decisioning.** Pricing is where airline machine learning usually starts, so it anchors the dimension, running from fixed fare tables to personalized offers. Disruption prediction marks the move from reporting to prevention; Alaska's Flyways and United's ConnectionSaver are the high-end examples. Because a model in production is not the same as a governed one, the last question asks how models are monitored after launch.

**Frontline Change Capacity.** Airline technology succeeds or fails with pilots, flight attendants and ramp crews, who are largely unionized and work under safety rules. We avoided "is leadership committed to change," which measures attitude. Instead we ask who is involved in choosing tools, how staff are trained, who manages change, and the most visible signal of all: whether the old paper or phone process is actually retired.

**Testing.** We simulated a Stage 2 airline and a Stage 4 airline. The Stage 2 persona scored 1.5–2.25 and showed *Grounded Legacy Carrier*. The Stage 4 persona scored 3.75–4.25 and showed *Digitally Airborne Network*. The two radar shapes are visibly different. We also reproduced each of the three gap profiles on purpose.
<!-- RATIONALE-END -->
