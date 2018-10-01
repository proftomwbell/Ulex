# Change Log

## Introduction to [Version 1.1](1.1/)

Field tests of Ulex 1.0, while largely positive, suggested that few edits might improve
the performance of the system. Version 1.1 of Ulex thus duplicates version 1.0 but for these
four changes:

* Procedural rules trimmed and rearranged;
* A firewall against judicial excess added;
* Meta-rules amended and rearranged to add run-time stability; and
* Optional module offered for enactment by host sovereigns.

Explanations follow in order, below.

**Procedural rules trimmed and rearranged**. Version 1.1 does away with the
detailed procedural rules that version 1.0 had offered in Rule 1.3, which incorporated by
reference the American Arbitration Association's _Commercial Arbitration Rules and
Mediation Procedures_ (2010).^ Unsurprisingly, in retrospect, those rules defaulted to the
Association's preferred judges and procedures a bit too forcefully for some users.
Furthermore, to use the Association's rules would raise especially troubling copyright
complications. Ulex 1.1 thus relies on ALI & International Institute for the Unification of
Law's _Principles of Transnational Civil Procedure_ (2004). 
Those rules provide enough detail to get the dispute resolution process started, 
and often to finish it, leaving parties to choose other and more detailed rules if and when they see fit.

Another change in the procedural section: the order of the rules. Whereas version
1.0 put Ulex's basic triad of default rules before the _Principles of Transnational Civil_

_Procedure_ , version 1.1 reverses that order. Why? Because Ulex users want to trust that
those defaults will apply unless and until they expressly change them, and because the meta-
rule against conflicts (Rule 3.1 in version 1.0; Rule 3.3 in version 1.1) provides that later
rules prevail over earlier ones. Reversing the order of the rules in the procedural section thus
ensured that the default triad will prevail over anything in the _Principles of Transnational
Civil Procedure_ to the contrary. Users who want other procedures can, of course, adopt them
by separate agreement.

**A firewall against judicial excess added.** Ulex 1.1's new Rule 2.9 would apply in
those rare instances when the judges chosen under Ulex's procedural rules face a question not
resolvable by Ulex's extensive collection of other substantive rules. Rule 2.9 would then
contain the crisis, saving the larger system from failure. Even if never put to use, this legal
firewall would quietly give users greater confidence in Ulex.

Rule 2.9 is not the only or even necessarily the best way to deal with questions arising
outside the substantive rules of Ulex. Claims not founded in the rules should face sufficient
discouragement in the prospect of a motion to dismiss and the fact that a losing party must
pay the prevailing party's costs. It is not inconceivable, however, that parties to an otherwise
rule-based dispute might invite the court to decide a relatively minor issue, one related to
their dispute but not decided by any other rule.

For example, co-owners disputing their rights to a jointly owned house might invite
the court to decide what color they should paint it. Rule 2.9 would in the event require that
the court to decide the question in accord with common practice, the general tenor of the
rules, and a decent respect for human dignity. Tan or blue would probably suit nicely for the
house in question; puke green presumably would not.

**Meta-rules amended and rearranged to add run-time stability.** For reasons more
theoretical than practical, version 1.1 introduces two subtle changes to Ulex's meta-rules.
Both aim to protect the system from internal contradictions. In computer code, those kinds
of errors can cause a system to freeze up or shut down. In legal code, they would doubtless
have similarly unwelcome effects.

Version 1.0 already had a rule against such conflicts — Rule 3.1. Because it was not at
the very end of the rules listed in the index, though, there remained the possibility that some
later rule might contradict it. Version 1.1 fixes that bug by moving the rule against conflicts
to the very end of the meta-rules, to Rule 3.3.

Ulex 1.1 also changes the wording of this safeguard against conflicts, adding at the
end, "but no rule can prevail over this one." That additional clause bars the later addition of a
rule that contradicts the rule against contradiction. Perhaps that is over cautious. Those who
issue new versions of Ulex could instead simply always list the meta-rules last. If a
jurisdiction adopted the optional criminal law or integration modules, for instance, it could
rearrange and renumber the rules to ensure that the rule against contradiction comes at the
very end of the index. It is impossible to ensure that future Ulex editors will take that
precaution, though, so the newly added clause writes the anti-contradiction rule into the code
itself, protecting Ulex against run-time errors.

**Optional module offered for enactment by host sovereign.** This new and brief
collection of rules, offered in a new section 5, regulates the process through which a host
sovereign's courts review and reject or adopt the judgments of Ulex courts. In form and
effect, the Integration Module reflects the core provisions of the long-lived and widely
respected United States Federal Arbitration Act (FAA).<sup>[1](#fn1.1.1)</sup>
Subject to scrutiny for inherently unfair adjudications, 
the FFA gives private arbitrations force of law, allowing the prevailing
private party to invoke public powers to enforce the private judgment. Module 5 does
likewise for decisions rendered under Ulex and presented for enforcement in the courts of a
host jurisdiction. In this way, special jurisdictions running Ulex can integrate more fully
with other legal systems.

<a name="fn1.1.1"><sup>1</sup></a> 9 U.S.C. § 1-ff.

## Introduction to [Version 1.0](1.0/base.txt)

This document makes Ulex, an open source legal operating system, available for public use. 
Like all software, the formal algorithms of Ulex generate desired results in a
regular, predictable, programmable manner. Like the operating system that makes a
computer or smartphone user-friendly, Ulex provides a legal platform for running everything
from a business pursuing profit, to an individual seeking work, to a family seeking happiness. 
To all these and more, Ulex offers a fair and efficient legal system. 
And like any open source program, Ulex is not doled out by the dime but instead free for anyone to
download, use, and modify. 
They need only adopt and implement by mutual express consent the procedural, substantive, 
and meta-rules that follow this brief introduction.<sup>[1](#fn1.0.1)</sup>

Ulex does not so much create the law as curate it, combining specialized rule sets
from trusted sources into a simple but comprehensive legal system. 
It covers _civil law_ in the sense of _private law_ — not in the sense of _Roman_ law 
and not in contrast to _common law_.<sup>[2](#fn1.0.2)</sup> 
As such, Ulex by default does not include criminal law, which concerns not purely private
matters, but instead offenses against the public at large. Ulex 1.0 instead offers criminal law
as an optional module.

With regard to all areas of law, Ulex offers both _procedural_ rules, which define how parties 
resolve their disputes, and _substantive_ rules, which describe their legal rights and remedies. 
A few _meta-rules_ protect the system against the functional equivalent of what
computer programmers rue as "run-time" errors. Ulex merely sets default rules in most
cases, leaving users free to run other legal systems "on top of" it.<sup>[3](#fn1.0.3)</sup>

The default rules of Ulex 1.0 come from the _Restatements of the Common Law_ , the
_Uniform Commercial Code_, and other select sources. 
To specify the rules is not to replicate them, however. 
Some of the rule sets used in Ulex remain subject to copyright claims. 
Most such copyright claimants nonetheless make their materials publicly available. 
Uniquely, however, the American Law Institute (ALI) both claims copyrights in the black-letter rules of
the _Restatements_ and declines to make them publicly available.<sup>[4](#fn1.0.4)</sup> 
Given that the Restatements constitute binding public law in the United States, 
and that copyright cannot restrict public access to public laws, the ALI's claim looks suspect. 
But resolution of that question must wait. 
It would at all events prove taxing to duplicate every rule of Ulex 1.0 in this document,
which instead incorporates most of its constituent rules by reference, leaving users to access
specific provisions as the occasion requires and as they see fit.

<a name="fn1.0.1"><sup>1</sup></a> For more about Ulex, see, Tom W. Bell, YOUR NEXT GOVERNMENT? FROM THE NATION STATE TO
STATELESS NATIONS (Cambridge University Press, 2017).

<a name="fn1.0.2"><sup>2</sup></a> In fact, scholarly summations of common law rules — the various RESTATEMENTS — constitute the
greatest part of Ulex's substantive rules.

<a name="fn1.0.3"><sup>3</sup></a> See AMERICAN LAW INSTITUTE, RESTATEMENT (SECOND) OF CONFLICT OF LAWS § 187 (1971),
allowing parties to specify what law controls matters within the scope of their agreement, which Ulex
incorporates by reference at rule 2.4.1.

<a name="fn1.0.44"><sup>4</sup></a> Access to the _Restatements_ can be purchased in a variety of ways and formats: 
from [ALI](https://web.archive.org/web/20160430/https://www.ali.org/publications/#publication-type-restatements), 
for bound versions of its publications; from Thompson Reuters, for purchase or lease of bound or e-books, at 
[Restatements of the Law](https://web.archive.org/web/20160430/http://legalsolutions.thomsonreuters.com/law-products/Publication-Types/Restatements-of-the-Law/c/20194); 
or via online databases offered by 
[Westlaw](https://web.archive.org/web/20160430/http://www.westlaw.com/), 
[Lexis](https://web.archive.org/web/20160430/http://www.lexis.com/), or 
[HeinOnline](https://web.archive.org/web/20160430/http://home.heinonline.org/). (All sites visited April 30, 2016).

