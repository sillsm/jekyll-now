---
layout: post
title: CLA Policy 2
---


# Model CLA Policy and Rationale

{:toc}

## Introduction

Technology companies frequently receive and use code from outsiders; this
outside code may be important to core products. Outside code can be a tremendous
resource, but it also carries responsibility. This document spells out corporate
best practices for accepting code contributed by third parties and explains the
basis for these practices in agency law. These best practices consist of three
components: an Apache-type Contributor License Agreement (CLA), a procedure for
accepting CLA signatures, and a procedure for accepting code submitted under the
agreement.

This document will summarize the legal framework around code ownership, laying
out the rationale for employing an Apache-type CLA, and then discuss the
specific laws and operational concerns attendant to each part of the CLA signing
and code acceptance process.

## Overview

Under international copyright law, copyright attaches automatically in the
creation of creative works, such as software. The moment a work of
sufficiently original software is fixed in a tangible medium, it is protected by
copyright. Domestic copyright laws often place copyright ownership in the hands
of a creator's employer. When a programmer submits code to a company, that
code may be owned by the programmer's employer. To ensure that a company is
granted the permissions necessary to utilize the code it receives, Contributor
License Agreements (CLAs) should generally be obtained from every organization
whose employees contribute code. The language of the Apache CLA, and the best
practices for accepting CLAs, serve two interrelated aims: First, to ensure that
the company is granted permission to use the code. Second, to ensure that the
CLA effectively binds the signee’s organization.

The language of the Apache CLA protects companies by clarifying the ownership
and permissions of intellectual property created and used in the course of the
code contribution relationship. Section 2 of the agreement grants the
receiving company a "perpetual, worldwide, non-exclusive, no-charge,
royalty-free, irrevocable copyright license" to the organization's
contributions. The "no-charge, royalty-free" language permits the receiving
company to use the code without incurring expense. The "non-exclusive" language
reserves the organization freedom to use the code itself, or to license the code
to others under different terms. Section 3 spells out patent license terms,
granting the receiving company and downstream users a perpetual license to any
patents implicated by the contributed software. Section 3 also incorporates a
litigation-deterring license-termination mechanism. Sections 4 and 8 require
the signee to certify that they wield the requisite authority to enter into the
CLA on behalf of their organization. These clauses alert the signee that proper
authority is required to enter into the agreement on behalf of their
organization. It also places the responsibility on the signee to ensure that
such authority is secured.

In addition to the terms of the CLA itself, an effective CLA acceptance
procedure consists of three protective measures to ensure that the CLA binds the
signee's organization. First, authentication, such as email verification through
a document signing service, should be used to verify the identity of the signee.
This provides assurance that the signee is a real person and a representative of
the contracting organization. Second, signees’ professional titles should be
reviewed, and submissions should be rejected if the signee's title is not one
that generally confers authority to contract on behalf of an organization.

For example, a software engineer usually does not have the authority to sign
documents for their company, though they may try. This is done to ensure that
the company’s reliance on the authority of these signees is reasonable.

Third, all employees of the contributing organization should be individually
appointed to contribute under the agreement by an established point of contact
before making contributions. Funnelling all contributors from a given
organization through a single point of contact prevents contributions from being
made without the contributing organization’s knowledge, and prevents
misunderstanding.

## Discussion

This discussion will first delve into the legal and operational considerations
underpinning the language of the Apache CLA, then lay out best practices for CLA
submission and code contribution acceptance procedures with an eye to the
particular fact patterns that may be relevant for receiving companies.

### CLA

#### Standard inbound license

Using one standard inbound license that grants the receiving company broad
permission to use contributed code in products is beneficial to the company and
downstream users alike.

Technology companies will of course want to make productive use of any code made
available to them. However, if all of the code being received by a company was
subject to various inbound licenses with conflicting terms, the bureaucracy for
authorizing use of any specific third-party code for any specific purpose would
be cumbersome. Whenever contributed code were to be used, the particular license
terms for every single file would need to be reviewed to ascertain whether the
application would be permitted under the terms of that code’s specific
license.[^7] This would require considerable human resources and would slow down
the engineers trying to utilize the code.

The benefits to the company under the standard inbound license pass to
downstream recipients as well. Explicit patent permissions and disclaimers of
obligations and warranties clarify the recipients rights and duties; the broad
grant of rights provides code recipients opportunities to make productive use of
the software; adherence to a single standard license promotes consistency and
common understanding for all participants.

#### Grant of patent license

Section 3 of the Apache CLA operates to clarify that the agreement controls all
aspects of the intellectual property interest in the software. Having patent
license terms clearly and explicitly stated protects all parties’ interests.

#### Origin of works

Sections 5 and 7 require the signee to represent that all contributions under
the agreement are the “original creations” of the contributing organization.
This is done to protect the receiving company (and downstream users), because
the CLA may not shield recipients from claims by owners of code that is
submitted to them by a third party. Requiring CLA signatories to certify that
their code contributions are their original creations - hence copyrighted works
that they actually own - gives recipients some recourse against those
signatories if their contributed code turns out to have been improperly obtained
from a third party.

#### Works made for hire

A benefit of the Corporate CLA is that it protects receiving companies from
termination of transfers. As works made for hire are ineligible for termination
of transfers,[^8] receiving companies are assured that their license to use the
code will not be threatened by termination if the code is contributed through
the engineer’s employer’s CLA, as this establishes that the code is a work made
for hire, which is subsequently properly licensed.

#### Individual CLA

For circumstances where the code being contributed is not done within the scope
of the contributor’s employment,[^9] contributors should be required to sign a
CLA in their individual capacity.

### Procedure

#### Signatures

As discussed in the overview, copyright ownership is a complex animal. Because
copyright ownership is complex, the execution of an agreement that licenses
rights to copyrighted material is a complex matter as well.

For instance, sometimes employees are not aware of the ramifications of
exectuing an agreement on behalf of their employer, which is why having clear
policies in place to account for such situations is essential.

This section will highlight the particular fact patterns that may be relevant to
a company employing a CLA, and then detail the legal framework underpinning the
issue of unauthorized signees.
