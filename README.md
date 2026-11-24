# A Note to the CoU AI Hackathon 2026 Evaluators

We, Team NSTU Winterfell, built **GasLine**: a working, offline, machine-learning system that predicts which garment export orders a gas-pressure crisis will make late, tells a merchandiser which ship date is safe to promise before signing, and prices the cheapest rescue against air freight. It came with a live demo, automated tests (56/56 passing), and full documentation.

In our view, it was not evaluated properly.

## On the evaluation process

Our team was assigned a single evaluator. In our experience, that review did not engage with the technical substance of the work: the cascaded ML models, the conformal prediction, the uncertainty-aware optimizer, or the two on-site challenges we implemented. A project that combines machine learning, operations research, and domain-specific manufacturing economics cannot be fairly judged by one reviewer who isn't equipped to assess it. Hackathons that claim to reward "meaningful use of AI" should assign reviewers with the technical background to tell a real system from a wrapper, or at least use more than one.

## What we'd ask of evaluators

If you judge a project, please do these things:

1. **Run the code.** Open the repo, install it, and click through it. A README is a claim, not a result.
2. **Check "meaningful AI" against the code.** Read the models, the conformal prediction, and the optimizer before deciding whether something is a prompt wrapper.
3. **Give feedback.** Teams that spend days building should be told why they ranked where they did.
4. **Be consistent.** Apply the rubric you published to every team, the same way.

This repository has been cleared by its maintainers, which the hackathon license (Section 5) allows. The full commit history is still available in the git log.

The complete project lives here: **https://github.com/sovon1/Gasline**

Team NSTU Winterfell, Noakhali Science and Technology University
