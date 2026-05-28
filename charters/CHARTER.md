# Web3 Alliance Charter

**Version:** 1.0
**Effective Date:** 2026-05-27
**Custodian:** Office of the General Counsel, Web3 Alliance

---

## 1. Name and Purpose

The Web3 Alliance (the "**Alliance**" or "**W3A**") is a coordinated
federation of legally independent businesses ("**Members**") operating
under shared post-quantum-secure infrastructure, shared intellectual-
property licensing, shared distribution rails, shared capital pool, and
a single coordination layer (the "**Coordination Layer**").

The Alliance's purpose is to control the full value chain of digital
economies — infrastructure, intellectual property, distribution,
liquidity, banking access, and capital — through a deliberately
engineered network of independent businesses, each retaining
operational independence while sharing the substrate, IP, distribution,
and capital that the Coordination Layer maintains.

## 2. Members

### 2.1 Categories

The Alliance admits four categories of Member:

- **Chain Members** — operators of L1 / L2 / L3 chains that adopt the
  Alliance substrate and operate Authorized Networks per the LEL
  Descending-Chain criterion.
- **Regulated Financial Entity Members** — banks, money transmitters,
  acquirers, issuers, broker-dealers, alternative trading systems,
  transfer agents, fund managers, and crypto-asset service providers
  in any jurisdiction.
- **Infrastructure Members** — operators of substrate-adjacent
  infrastructure (custody, identity, compute, data, oracle, AI,
  privacy primitives).
- **Capital Members** — strategic investors and family offices
  participating in the Alliance Layer-1 capital pool.

### 2.2 Founding members

- **Chain**: Lux Network, Zoo Network (Zoo Labs Foundation), Hanzo,
  Pars Foundation, Osage Network.
- **Regulated Financial Entity**: North Capital Private Securities
  Corp. (NCPS), SF Private Bank, AvaTrade Ltd., Atmen Ltd., Salaam
  Somali Bank (SSB), Creatrust, CDAX Limited.

The founding-member roster is open to additional admissions on the
same terms as any other applicant (Section 4).

### 2.3 Member rights

Each Member has the right to:

- Access the licensed substrate at the executed licensing terms.
- Access the Alliance distribution surface and cross-routing layer.
- Access the Alliance capital pool at documented terms.
- A seat in the Member-Coordination Forum (quarterly cadence).
- Standard contractual representations and warranties on substrate
  title, Alliance IP, and partner-ecosystem performance.

### 2.4 Member obligations

Each Member agrees to:

- Operate under the executed license terms (LEL / LRL-PR / SCLA);
  respect the Authorized Network and Descending-Chain criteria.
- Maintain the brand-via-env-override discipline so substrate
  upgrades flow cleanly across the network.
- Maintain SOC 2 sub-service-organisation complementary controls
  where the Member is a regulated counterparty in any jurisdiction.
- Contribute distribution into the cross-Member routing layer at the
  standard 50/50-above-documented-costs commercial terms.
- Respect the Clean-Room Engineering Protocol for any work that
  extends substrate modules.
- Report quarterly into the Member-Coordination Forum.

## 3. Coordination Layer

### 3.1 Scope

The Coordination Layer holds (and only holds):

- All Tier-2 (LEL) and Tier-3 (LRL-PR) licensing authority.
- All Alliance-owned patent ownership.
- All Alliance-owned trade-secret records.
- The Alliance brand registry and brand-policy enforcement.
- The Alliance treasury (Layer-1 capital).
- The substrate engineering team's coordination.
- The compliance posture (Clean-Room Protocol, SOC 2 sub-service
  organisation responsibility, vendor management).

The Coordination Layer **does not hold**:

- Member operations.
- Member-level customer relationships.
- Member-level product roadmaps.
- Member-level hiring decisions.

### 3.2 Structure

The Coordination Layer is administered by:

- **Board of Directors** — three (3) Member-elected director seats +
  one (1) Coordination-Layer-appointed director seat + three (3)
  independent director seats.
- **Office of the General Counsel** — substrate licensing, dispute
  resolution, Member-admission review, regulatory liaison.
- **Office of the Chief Economist** — capital allocation, fee
  schedule, Member-stabilisation distribution criteria, partnership-
  template commercial baseline.
- **Office of the Chief Architect** — substrate engineering
  coordination, Clean-Room Protocol enforcement, patent prosecution.

### 3.3 Intervention triggers

The Coordination Layer intervenes in a Member's operations only when:

- The Member is in material breach of its license terms.
- The Member is in material breach of the Clean-Room Protocol.
- The Member's compliance posture has deteriorated to the point of
  creating regulatory risk to other Members in the same jurisdiction.
- The Member is failing financially and has drawn on Member-
  stabilisation distribution; the Coordination Layer attaches
  operational conditions to that distribution.
- A material dispute between two or more Members requires
  Coordination-Layer adjudication.

Each intervention is documented, time-bounded, and subject to the
dispute-resolution mechanism in the underlying SPA.

## 4. Membership Admission

Membership applications are submitted via `w3a.foundation/join` and
processed by the onboarding service at `api.w3a.foundation`. The
admission lifecycle:

```
SUBMITTED → UNDER_REVIEW → REVIEW_COMPLETE → COMMITTEE_VOTING
   → APPROVED → ONBOARDING → ACTIVE
                 ↓
            REJECTED (terminal)
            WITHDRAWN (applicant-initiated; terminal)
```

Decision criteria:

- **Material contribution** to one or more of the six value-chain
  layers (infrastructure / IP / distribution / liquidity / banking
  access / capital).
- **Regulatory standing** appropriate to the Member's category and
  jurisdiction.
- **Compliance with Clean-Room Protocol** baseline.
- **No material conflict** with another Member's mandate.
- **Acceptance of Member obligations** (Section 2.4).

Approved Members execute the standard Strategic Partnership Agreement
(SPA, see [`legal/mou-templates/`](../mou-templates/)) plus any
category-specific addenda (chain-substrate licence, regulated-financial-
entity addendum, etc.).

## 5. Capital Architecture

The Alliance operates a three-layer capital architecture:

- **Layer 1 (Substrate + Coordination)** — strategic investor capital
  with a 10-year minimum horizon, funding substrate development,
  patent prosecution, Coordination Layer operating cost, and reserve
  runway against any Member's shortfall.
- **Layer 2 (Member Operating)** — Member-level rounds underwritten
  primarily by the Alliance treasury, supplemented by external
  venture or strategic capital where appropriate.
- **Layer 3 (Acquisition + Spawn)** — operating cash flow from
  Layer-2 Member revenue, plus structured-debt facilities
  collateralised against the Alliance IP estate, funding the
  acquisition + spawn programme.

Cross-layer rules, treasury policy, and IRR targets per layer are
specified in `papers/Web3_Alliance.pdf` §9.

## 6. Intellectual Property

The Alliance licences substrate IP under a three-tier model:

- **Tier 1 (BSD-3-Clause)** — commodity infrastructure.
- **Tier 2 (LEL)** — source-available, patent-protected; commercial
  rights to Authorised Networks only.
- **Tier 3 (LRL-PR)** — research-only; commercial use requires SCLA.

Plus a closed **Private Moat tier** (`luxcpp/`-equivalent GPU + crypto
code) licensed only to top-tier settlement counterparties.

Bifurcated licensor posture: Lux Industries Inc. licenses Lux-branded
modules; Hanzo, Inc. licenses Hanzo-branded modules. Member admission
is a contracted IP-licensing event.

## 7. Governance and Dispute Resolution

- **Governing law**: Delaware (for the Coordination Layer's parent
  holding); each Member's SPA carries its own governing-law clause
  matched to the Member's jurisdiction.
- **Dispute resolution**: AAA Commercial Rules, Wilmington seat for
  the Coordination Layer; bilateral SPAs may specify alternate seats
  by mutual agreement.
- **Voting at the Coordination Layer**: simple majority on routine
  matters; super-majority (2/3) on changes to the Charter,
  capital-pool allocation rules, or admission criteria; unanimous
  consent on dissolution.

## 8. Amendment

This Charter is amended by super-majority vote of the Board of
Directors, with notice to all Members at least thirty (30) days in
advance of the vote.

## 9. Companion Documents

- `papers/Web3_Alliance.pdf` — operative thesis paper
- `legal/mou-templates/STRATEGIC_PARTNERSHIP_AGREEMENT_TEMPLATE.md`
- `legal/mou-templates/MEMBER_ADDENDUM_CHAIN.md`
- `legal/mou-templates/MEMBER_ADDENDUM_REGULATED_FINANCIAL_ENTITY.md`
- `members/REGISTRY.md` — current Member roster + status
- `docs/governance.mdx` — public-facing governance summary
- `INDEPENDENT-IMPLEMENTATION-CLEAN-ROOM-PROTOCOL.md` (in
  `lux-private/legal/` for substrate-engineering hygiene baseline;
  the Alliance maintains the equivalent reference for Member
  engineering)

---

**Office of the General Counsel · Web3 Alliance**
