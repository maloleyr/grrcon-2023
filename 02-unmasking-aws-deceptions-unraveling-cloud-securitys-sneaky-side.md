# Thursday - Track Peppermint - 10am

## Unmasking AWS Deceptions: Unraveling Cloud Security's Sneaky Side

> Yossi Tamarov | Proofpoint

---

## Raw Notes

What is a "Deception" in this context? 

- Attempt to manipulate the beliefs of others
- Exploit cognitive biases
- Influence to the benefit of the planner/defender

A fake digital resource that mimcs some characteristics of real resources. AKA a Honeypot or Canary (in the coalmine).

**Proactive security and defense tactic.**

A security resource whose value lies in being probed or attacked.

Goal: Enhance threat detection, gather intelligence, delay attack, and serve as a deterrent.

"hunnyPOT" or "honeypot"

- Honeypot
	- Disadvantages: Not scalable, much maintenance, lack of plausible traffic, and can be abused.
- Honeytokens
	- Advantages: Simple, ease of use, quietness, polymorphinism, and omnipresence.

IAM: Identity and Access Management

- Account User = AWS ROOT
- IAM User = User in IAM
- Federated User: Other authentication
- Groups and roles
- Roles grant permission + access

How to access resources

- Console password
- Access key for API
- SSH Key

IAM Policies: Allow/Deny Permission for an Action on a Resource by an Identity.

- Resource: An object that exists within a service.
- Perimeter Honeytokens: Notify when the perimeter is probed.
- Lateral Movement Honeytokens: Detect and Deter. "You've been breached."

Alert via Amazon CloudTrail. Beacon files.

Trust policy -> IAM: PassRole


## Thoughts/Observations

I had high hopes for this talk. I was really hoping to learn some new tech and how to apply/use it. Unfortunately this seemed like two short talks combined into a longer talk without achieving the goal for both talks. I was really hoping to learn more about honeytokens (and I assume CanaryTokens and the like) however the speaker did not really address the available options and how to use them. 
