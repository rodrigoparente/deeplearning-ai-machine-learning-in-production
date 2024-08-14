# Common Deployment Strategies
 
 - **New Product Deployment:** used when introducing a new service or capability;
 - **Automation of Existing Human Tasks:** applicable when automating tasks that were previously performed by humans;
 - **Upgrading Existing AI Systems:** used when replacing an older machine learning system with a new one.

# Deployment Patterns and Techniques

 - **Shadow Mode Deployment:**
    - AI operates alongside human decision-makers but does not influence outcomes;
    - Useful for gathering performance data and ensuring the AI system's reliability before allowing it to make decisions.

 - **Canary Deployment:**
    - The new system handles a small fraction of traffic initially;
    - Gradual traffic increase allows monitoring for potential issues, minimizing the impact of errors;
    - Inspired by the "canary in a coal mine" concept, used to detect problems early.

 - **Blue-Green Deployment:**
    - Involves running both the old (blue) and new (green) versions of a system;
    - Traffic is switched entirely from the blue to the green system once the new system is deemed reliable;
    - Provides an easy rollback option if the new system fails.

# Degrees of Automation

 - Can range from full human operation (no automation) to full AI-driven decisions.
 - The levels of automation are:
    - **Human Only:** no automation, human does all the decision;
    - **Shadow Mode:** AI provides outputs but does not influence decisions;
    - **AI Assistance:** AI highlights or assists, but humans make final decisions;
    - **Partial Automation:** AI makes confident decisions, but uncertain cases are referred to humans;
    - **Full Automation:** AI makes all decisions without human intervention.

# How to Choose the Appropriate Approach

 - Depends on the application's needs and the AI system's performance;
 - In some contexts, human-in-the-loop systems (AI Assistance or Partial Automation) may be preferable over full automation;
 - Full automation is often necessary in consumer Internet applications, like search engines, where human intervention isn't feasible.

# Implementation Considerations

 - Implementing these deployment strategies requires sophisticated software and possibly MLOps tools;
 - Deployment should not be viewed as a binary decision (deploy or not deploy), but rather as finding the appropriate level of automation that meets the specific needs of the application.