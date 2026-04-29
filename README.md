# Process Consistency Maturity Model (PCMM)

The PCMM is a maturity model for assessing process consistency in 
event-driven microservice architectures. It evaluates seven capability 
categories across five maturity levels using 40 binary assessment questions. 
The output is four level-completion percentages (P2–P5) that indicate how 
far an architecture progresses through the maturity scale.

## Categories

1. Workflow Progression Guarantees (WPG)
2. Constraint Enforcement and Protocol Safety (CEPS)
3. Concurrency and Idempotency Control (CIC)
4. Fault Handling and Recovery (FHR)
5. Runtime Governance (RG)
6. Events Documentation (ED)
7. Microservices Documentation (MD)

## How to use

1. Download `PCMM_Assessment_Instrument.xlsx`
2. Read the **About This Model** sheet before starting
3. Answer Y or N in each of the seven category sheets
4. Open the **Dashboard** sheet to see aggregated results
5. Open the **Graphs** sheet to visualize the assessment output

## Scoring

For each level N in {2, 3, 4, 5}:

    P(N) = questions at Level N answered Y / total questions at Level N × 100%

Fixed denominators: L2 = 13 questions, L3 = 11, L4 = 10, L5 = 6.

## Citation

If you use the PCMM in your research or practice, please cite:

[Your name]. (2025). *Process Consistency Maturity Model for Event-Driven 
Microservice Architectures*. MSc thesis, Instituto Superior Técnico, 
Universidade de Lisboa. [link once published]

## License

This work is licensed under 
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
