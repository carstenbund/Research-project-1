# Persistence, Surplus, and Responsibility — Bridge Between Two Research Programs

**Date:** October 25, 2026  
**Status:** Working synthesis and research proposal; not a validated general theory  
**Source discussion:** Symbolic recursion, consciousness as navigation, accumulated coherence, and the surplus model  
**Companion research:** [Symbolic Recursion, Intension, Consciousness, and Responsibility](2026-10-25-symbolic-recursion-intension-consciousness-digest.md)

## Purpose

This note connects two independently developed research directions without merging their definitions:

1. **Symbolic-entity and accumulated-coherence research** asks how stabilized structure can survive across carriers, be enacted by compatible mechanisms, and participate at higher scales through operational compression.
2. **Surplus Simulation Research** asks how actual systems maintain the capabilities and shared conditions on which their continued functioning depends; how this costs resources; and how valuation, examination, constraints, and delayed consequences shape their trajectories.

The connection was prompted by an earlier hypothesis that **consciousness functions as a navigation device and seems to exhibit a drive toward persistence**, followed by the observation that **enactment has a cost and responsibility arises from participation**.

The proposed bridge is not that all stable organizations are conscious, or that maintenance alone creates moral obligations. It is that a common *organizational dependency* can be examined abstractly in symbolic recursion and concretely in the surplus model.

## 1. Two complementary views of persistence

The symbolic-recursion model describes how lower-level coherent relationships can become a **stable, reusable unit**. At the next scale, a compressed, load-bearing interface makes interaction possible without reconstructing every internal relationship.

The surplus model asks the question that follows from any actual participation:

**How are those interfaces, compatible mechanisms, and enabling conditions sustained over time?**

This is the difference between *structural availability* and *continued operational availability*.

An inherited structure may be preserved as a definition or a symbolic pattern, while its ability to produce effects depends on a maintained incarnation and compatible mechanism. A society may retain the memory of a capability while losing the people, institutions, or resources needed to exercise it.

The research programs therefore meet at the transition:

> **Coherent structure → compatible participation → costly enactment → upkeep and reproduction → continued or altered coherent structure.**

This should not be interpreted as a mandatory linear sequence. Maintenance, reproduction, participation, and restructuring can overlap.

## 2. Surplus makes the cost explicit

The [surplus research](https://github.com/carstenbund/surplus-sim1) distinguishes durable capability, present availability, and the portion of present deployment capacity already claimed by necessity and commitments.

Its current operationalization is:

\[
S_i(t)=C_i(t)\,A_i(t)\,[1-U_i(t)].
\]

Where:

- \(C_i\): durable, heterogeneous capability of participant \(i\);
- \(A_i\): present availability to deploy it;
- \(U_i\): necessity/commitment share;
- \(S_i\): presently available surplus capacity.

This is not simply money or a stock of spare energy. It is a model of *capacity available beyond immediate obligations*. Enactment may additionally require time, tools, attention, access, coordination, permission, or other enabling resources.

The underlying maintenance principle is the farmer's rule:

> **Do not consume the conditions of the next harvest.**

The harvest must support present activity **and** preserve the productive conditions needed for future activity. At other scales, the maintained substrate may be bodily capacity, skill, shared infrastructure, trust, interpretive conventions, archives, institutions, or mechanisms that reproduce symbolic structures.

**Connection to accumulated coherence:** Stable organization can reduce repeated constructive work and release capacity for higher-order action. That released capacity may be used for exploration and new organization, but some must be returned to the conditions enabling persistence. The reduction of immediate work does not eliminate upkeep.

Primary source: [Manager Theory and origin of surplus](https://github.com/carstenbund/surplus-sim1/blob/main/research/01-manager-surplus.md) and [Upkeep, Self-Preservation, Grace, and Leap](https://github.com/carstenbund/surplus-sim1/blob/main/research/06-upkeep-grace.md).

## 3. Maintenance is an endogenous feedback loop

The surplus simulation represents a shared enabling substrate as \(K\): infrastructure, institutions, knowledge, trust, environmental and other collective supports.

One modeled feedback is:

\[
U_i = U_i^0 + k_{\mathrm{load}}(1-K)+\mathrm{shock}_i.
\]

When shared capacity \(K\) deteriorates, obligations previously handled by a common structure return to individual participants. Their necessity share rises and their available surplus falls. That loss of surplus can, in turn, reduce capacity to maintain or restore \(K\).

The computational implementation also updates \(K\) through decay, wear, possible damage, and restoration by maintenance activity. Hence the direction of system change is not assumed to be benign.

**Illustrative feedback:**

1. The shared substrate deteriorates.
2. More maintenance work is pushed onto participants.
3. Less surplus remains for repair, examination, or adaptation.
4. The shared substrate becomes harder to sustain.
5. The system may enter further deterioration even while some outputs remain visible.

This is a possible regime, not an inevitable fate of all networks.

The mechanism appears in [grace_net.py](https://github.com/carstenbund/surplus-sim1/blob/main/grace_net.py) and the account in [Grace reconnected to the network model](https://github.com/carstenbund/surplus-sim1/blob/main/research/08-grace-net-integration.md).

## 4. Delayed Gravity: the hidden price of compressed interfaces

Operational compression lets a higher layer use an established capability without directly managing all its internal maintenance. This increases efficiency but may conceal dependency.

The surplus theory calls a particular consequence **Delayed Gravity**: a causal deterioration occurs now, but the resulting constraint becomes binding later. Visible output can remain nearly normal while common enabling capacity, inherited skills, redundancy, or future productive conditions decline.

An organization may therefore **consume previously accumulated coherence while still appearing productive**.

This is not a moral conclusion yet. It is a causal distinction between present observable output and future viability. Costs can also be externalized to other participants, domains, or times; they need not all return to the original actor.

A key common proposition follows:

> **Scaling can conceal the cost of maintaining the interfaces that make scaling possible.**

See [Shortcuts and Delayed Gravity](https://github.com/carstenbund/surplus-sim1/blob/main/research/04-shortcuts-delayed-gravity.md).

## 5. Consciousness: persistence as a navigational intension

The symbolic research previously proposed **consciousness as a navigation device**, possibly developed in connection with the persistence of living systems. The extension here is more precise:

- Living systems require upkeep for continuation; many achieve regulation without consciousness.
- A conscious navigator may *represent* its dependence on future conditions, compare alternative trajectories, and direct resources toward continued viability.
- Persistence may thereby become an explicit **intension**, rather than only an outcome of homeostatic or adaptive processes.
- That intension can extend beyond the individual body: offspring, projects, institutions, knowledge, or symbolic structures may be maintained by a participant who will not live to see their future enactment.

The statement **“consciousness seems to have a drive to persist”** remains a research hypothesis. The existence of maintenance requirements does not establish that every conscious system intrinsically seeks survival, nor does it establish consciousness in every self-maintaining system.

The potentially investigable contribution of conscious navigation is the **recognition and prospective management of dependencies**, including imagined alternatives and deferred maintenance.

## 6. Grace and the staging ground for reality

The earlier symbolic-recursion discussion described intension, imagination, science, and models of unrealized possibilities as a **staging ground for reality**.

The surplus theory offers a way to distinguish three things that this staging ground contains:

- \(G_\ell\): trajectories **actually reachable** under the constraints binding a given layer (Grace);
- \(H_\ell\): the subset of those trajectories **visible to that layer** (possibility horizon);
- **Enactment/Leap:** a transition that is visible, actually feasible, and affordable to undertake.

A formulation used in the surplus project is:

\[
H_\ell = L_\ell^G(G_\ell),
\qquad H_\ell \subseteq G_\ell.
\]

Examination can improve the legibility \(L_\ell^G\), but it **costs surplus**. A system under shock may lose the very surplus required to discover alternative paths.

An important negative result has already been documented by the surplus project: in exploratory Stage 9 simulations, *pre-shock examination* improved sight and was better than comparable post-shock examination, **but did not necessarily outperform no examination**. When the cost of entering alternatives was binding, paying for additional sight could leave too little surplus to enact them. This finding depends on simulated parameter choices, not empirical estimates.

This corrects any easy equation of *more imagination = more viability*. Recognizing alternatives, financing examination, and affording enactment are distinct.

See [Layered Grace and legibility](https://github.com/carstenbund/surplus-sim1/blob/main/research/07-grace-legibility.md) and [Stage 9 results](https://github.com/carstenbund/surplus-sim1/blob/main/research/08-grace-net-integration.md).

## 7. From participation to recognized responsibility

The key conceptual move was:

> **Enactment has a cost. Participation creates dependencies. Continued organization requires maintenance. Responsibility arises from participation where those dependencies can be recognized and answered for.**

The bridge must preserve two distinct senses of responsibility:

1. **Causal contribution/dependency:** An actor's behavior can maintain, degrade, or transfer the conditions of system viability, whether the actor recognizes this or not.
2. **Normative responsibility:** Assigning obligations, praise, or blame requires additional consideration of agency, knowledge, capabilities, power, alternatives, and commitments.

The surplus project's methodological rule—**model causal consequences before normative evaluation**—is therefore compatible with, and strengthens, the abstract account of responsibility.

The project also shows why recognition is not automatic. Valuation and translation filters can make an actor's contribution, the actor's borne cost, or the actor's imagined alternative invisible to the group. Responsibility may be causally distributed while socially unrecognized.

The system needs to investigate:

- whose contribution counts;
- whose maintenance cost counts;
- whose imagined alternative counts.

These are also questions about which portions of a higher-level organization's dependence remain legible to its conscious participants.

## 8. Quantifying a participant's contribution to viability

A first *causal* measure, separate from moral judgment, could compare trajectories under matched initial conditions:

\[
\Delta V_i(T)
=
V_T(\text{with contribution }i)
-
V_T(\text{without contribution }i),
\]

where \(V_T\) is an explicitly specified viability outcome at horizon \(T\). Possible operational targets include continued required functions, retained \(K\), deployable capability and surplus, survival under specified shocks, and reachable alternatives.

**Limitations:** The counterfactual depends on model choices; participants may substitute for one another; interactions can make attribution nonadditive; and the result is time-horizon-dependent. A positive effect on one viability measure is not a universal moral score.

Candidate model comparisons:

1. **Maintenance legibility:** same resources, different visibility or valuation of hidden upkeep; examine later \(K\), \(U\), \(S\), and breakdown regimes.
2. **Cost transfer:** compare genuine coordination that reduces total cost with shortcuts that relocate maintenance to less-visible actors or the future.
3. **Responsibility and agency:** allow some agents to recognize long-range dependencies and allocate surplus toward upkeep; compare with otherwise matched reactive agents.
4. **Examination timing:** invest before and after shocks while tracking what can actually be enacted, not merely what can be seen.
5. **Persistence of inherited symbolic mechanisms:** represent a maintained interface or convention explicitly; test whether its loss reduces coordination or increases the cost of rebuilding higher-order organization.
6. **Scale and visibility:** examine whether greater organizational compression reduces the local legibility of the maintenance work underlying aggregate output.

The current numeric parameters in surplus-sim1 are exploratory unless specifically documented otherwise; none of these proposed measures should be treated as empirically calibrated by default.

## 9. Consolidated bridge proposition

> **Persistence, surplus, and responsibility**
>
> Coherent relationships can become reusable through compressed, load-bearing interfaces, enabling compatible structures to participate in further organization across category and scale.
>
> Their continued enactment requires maintained carriers, mechanisms, resources, and shared enabling conditions. Participation consumes capacity and creates dependencies; neglect can remain hidden while an organization spends the coherence inherited from earlier maintenance.
>
> A conscious navigational system may recognize those dependencies, represent future consequences and alternatives, and direct available surplus toward upkeep, adaptation, or the construction of future navigational systems.
>
> Responsibility becomes relevant when participating agents can recognize and answer for their contribution to the persistence or deterioration of the conditions on which they and others depend.
>
> **Symbolic recursion investigates the persistence and reuse of organization; surplus theory investigates the costs, incentives, visibility, and viability of its realized continuation.**

This is a bridge between **an organizational abstraction** and **an exploratory causal model**. It does not require universal consciousness, a privileged foundational scale, or a proof that organizational persistence entails subjective experience.

## Research boundaries and next step

The original definition of a [symbolic entity](symbolic-entity-definition.md) requires **actual instantiation** and **compatibility-dependent causal effects**. A mere intention toward a possibility does not, without further qualification, instantiate that intended entity.

The [accumulated-coherence working definition](scaling-and-accumulated-coherence-working-definition.md) provides the compression hypothesis. The [surplus research's term registry](https://github.com/carstenbund/surplus-sim1/blob/main/docs/native-terms.md) provides the operational distinctions for actual systems. Neither vocabulary should silently overwrite the other.

**Proposed next research step:** define a small experiment where a reusable interface produces savings in constructive work, its maintenance consumes measurable surplus, the cost becomes partially invisible to higher-level actors, and different levels of maintenance recognition lead to different future viable trajectories. Make collapse, repair, and recovery emerge from dependencies rather than from predetermined thresholds.

---

*Provenance: Analytical synthesis of the October 25, 2026 conversation and the then-current documentation and exploratory code in [surplus-sim1](https://github.com/carstenbund/surplus-sim1). This document is not a verbatim transcript, and its theoretical connections are hypotheses rather than empirical findings.* 
