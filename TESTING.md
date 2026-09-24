# Simulation Test Log

The tool was run in headless Chromium with Chart.js 4. Each scenario filled every question at the listed answer values (one value per dimension, in dimension order, or per-question values for the mixed runs), then submitted.

| Scenario | Answers (CRI, FDE, OA, PAI, OCC) | Dimension scores | Two lowest shown | Profile shown |
|----------|-----------------------------------|------------------|------------------|---------------|
| Stage 2 organization (mixed) | varied 1–3 | 2.25, 2.25, 1.75, 1.5, 2.25 | Predictive & AI Deployment, Operational Automation | The Traditional Home |
| Stage 4 organization (mixed) | varied 3–5 | 4.25, 4.25, 3.75, 3.75, 4.25 | Operational Automation & Predictive & AI Deployment (tied) | Digital-Native Network |
| Uniform Stage 2 | 2,2,2,2,2 | all 2.0 | none: all level | The Traditional Home |
| Uniform Stage 4 | 4,4,4,4,4 | all 4.0 | none: all level | Digital-Native Network |
| Records gap | 1,4,4,3,4 | 1, 4, 4, 3, 4 | Case & Records Infrastructure, Predictive & AI Deployment | Elegant Front, Broken Back Office |
| Digitalized, not predictive | 3,4,3,2,3 | 3, 4, 3, 2, 3 | Predictive & AI Deployment, then three tied at 3.0 | Digitalized but Not Predictive |
| Execution gap | 4,4,4,3,2 | 4, 4, 4, 3, 2 | Organizational Change Capacity, Predictive & AI Deployment | Technology Nobody Asked For |
| No pattern | 3,3,2,3,4 | 3, 3, 2, 3, 4 | Operational Automation, then three tied at 3.0 | No Dominant Pattern |
| Tie for lowest | 2,4,4,2,4 | 2, 4, 4, 2, 4 | Case & Records Infrastructure & Predictive & AI Deployment (tied) | Elegant Front, Broken Back Office (records outranks AI on the industry tie-break) |

Other checks:
- Submitting with one question answered keeps results hidden and shows the "every question needs an answer" message.
- No console errors in any run.
- Every profile's name, pattern, description and action in `framework.md` matches the `PROFILES` data in `index.html` exactly (checked by script).
- The Stage 2 and Stage 4 radar shapes are visibly different: a small pentagon inside ring 2 versus a large pentagon near ring 4.
