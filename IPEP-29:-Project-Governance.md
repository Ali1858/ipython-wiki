The intent of this document is to formalize the governance process that the IPython/Jupyter project has used informally since its inception in 2001. This document clarifies how decisions are made and how the various elements of our community interact, including the relationship between open source collaborative development and work that may be funded by for-profit or non-for-profit entities.

The Project
===========

The Jupyter/IPython Project (The Project) is an open source software project affiliated with the 501c3 NumFocus Foundation. The goal of The Project is to develop open source software and deploy open and public websites and services for reproducible, exploratory and interactive computing. The Software developed by The Project is released under the BSD (or similar) open source license, developed openly and hosted on public GitHub repositories under the ipython and jupyter GitHub organizations. Examples of Project Software include the IPython Notebook, the IPython Terminal, IPython.parallel, the Jupyter Hub, etc. The Services run by the Project consist of public websites and web-services that are hosted under the jupyter.org or ipython.org domains. The Services Examples of Project Services include the Jupyter and IPython websites ([http://jupyter.org](http://www.google.com/url?q=http%3A%2F%2Fjupyter.org&sa=D&sntz=1&usg=AFQjCNHztfVQq8SN6qni-DVgmoaTYBVasg) and [http://ipython.org](http://www.google.com/url?q=http%3A%2F%2Fipython.org&sa=D&sntz=1&usg=AFQjCNGiroA4bzjI-kCsgV4YdTPbgyuyeA)), nbviewer ([https://nbviewer.ipython.org](https://www.google.com/url?q=https%3A%2F%2Fnbviewer.ipython.org&sa=D&sntz=1&usg=AFQjCNGB-iNba6jJiu1N9Oo4oMTWwFq3Aw)) and the Jupyter coLaboratory ([https://colaboratory.jupyter.org](https://www.google.com/url?q=https%3A%2F%2Fcolaboratory.jupyter.org&sa=D&sntz=1&usg=AFQjCNFBxEodelaV8P877UGqxrp7WU8Y3g)).

The Project is developed by a team of distributed developers, called Contributors. Contributors are individuals who have contributed code, documentation, designs or other work to one or more Project repositories. Anyone can be a Contributor. Contributors can be affiliated with any legal entity or none. Contributors participate in the project by submitting, reviewing and discussing GitHub Pull Requests and Issues and participating in open and public Project discussions on GitHub, Google+, Hackpad, Gitter chat rooms and mailing lists. The foundation of Project participation is openness and transparency.

Here is a list of the current Contributors to the main IPython repository:

[https://github.com/ipython/ipython/graphs/contributors](https://www.google.com/url?q=https%3A%2F%2Fgithub.com%2Fipython%2Fipython%2Fgraphs%2Fcontributors&sa=D&sntz=1&usg=AFQjCNFgTSocoNL5xEiFYrI4RYQ6VsZj4w)

The Project Community consists of all Contributors and Users of the Project. Contributors work on behalf of and are responsible to the larger Project Community and we strive to keep the barrier between Contributors and Users as low as possible.

The Project is formally affiliated with the 501c3 NumFOCUS Foundation ([http://numfocus.org](http://www.google.com/url?q=http%3A%2F%2Fnumfocus.org&sa=D&sntz=1&usg=AFQjCNFPopPpfGycF7UgwEfXNoFxlwluPA)), which serves as its fiscal sponsor, may hold project trademarks and other intellectual property, helps manage project donations and acts as a parent legal entity. NumFOCUS is the only legal entity that has a formal relationship with the project (see Institutional Partners section below).

Governance
==========

This section describes the governance and leadership model of The Project.

The foundations of Project governance are:

-   Openness & Transparency
-   Active Contribution
-   Institutional Neutrality

Traditionally, Project leadership was provided by a BDFL (Fernando Perez) and subset of Contributors, called Core Developers, whose active and consistent contributions have been recognized by their receiving “commit rights” to the Project GitHub repositories. In general all Project decisions are made through consensus among the Core Developers with input from the Community. The BDFL can, but rarely chooses to, override the Core Developers and make a final decision on a matter.

While this approach has served us well, as the Project grows and faces more legal and financial decisions and interacts with other institutions, we see a need for a more formal governance model. Moving forward The Project leadership will consist of a BDFL and Steering Council. We view this governance model as the formalization of what we are already doing, rather than a change in direction.

BDFL
----

The Project will have a BDFL (Benevolent Dictator for Life), who is currently Fernando Perez. As Dictator, the BDFL has the authority to make all final decisions for The Project. As Benevolent, the BDFL, in practice chooses to defer that authority to the consensus of the community discussion channels and the Steering Council (see below). It is expected, and in the past has been the case, that the BDFL will only rarely assert his/her final authority. Because rarely used, we refer to BDFL’s final authority as a “special” or  “overriding” vote. When it does occur, the BDFL override typically happens in situations where there is a deadlock in the Steering Council or if the Steering Council asks the BDFL to make a decision on a specific matter. To ensure the benevolence of the BDFL, The Project encourages others to fork the project if they disagree with the overall direction the BDFL is taking. The BDFL is chair of the Steering Council (see below) and may delegate his/her authority on a particular decision or set of decisions to any other Council member at his/her discretion. The BDFL is the only person capable of appointing his/her successor, but it is expected that the Steering Council would be consulted on this decision.

Steering Council
----------------

The Project will have a Steering Council that consists of Project Contributors who have produced contributions that are substantial in quality and quantity, and sustained over at least one year. The overall role of the Council is to ensure, through working with the BDFL and taking input from the Community, the long-term well-being of the project, both technically and as a community.

During the everyday project activities, council members participate in all discussions, code review and other project activities as peers with all other Contributors and the Community. In these everyday activities, Council Members do not have any special power or privilege through their membership on the Council. However, it is expected that because of the quality and quantity of their contributions and their expert knowledge of the Project Software and Services that Council Members will provide useful guidance, both technical and in terms of project direction, to potentially less experienced contributors.

The Steering Council and its Members play a special role in certain situations. In particular, the Council may:

-   Make decisions about the overall scope, vision and direction of the project.
-   Make decisions about strategic collaborations with other organizations or individuals.
-   Make decisions about specific technical issues, features, bugs and pull requests. They are the primary mechanism of guiding the code review process and merging pull requests.
-   Make decisions about the Services that are run by The Project and manage those Services for the benefit of the Project and Community.
-   Make decisions when regular community discussion doesn’t produce consensus on an issue in a reasonable time frame.

### Council membership

To become eligible for being a Steering Council Member an individual must be a Project Contributor who has produced contributions that are substantial in quality and quantity, and sustained over at least one year. Potential Council Members are nominated by existing Council members and voted upon by the existing Council after asking if the potential Member is interested and willing to serve in that capacity. The Council will be initially formed from the set of existing Core Developers who, as of late 2014, have been significantly active over the last year.

When considering potential Members, the Council will look at candidates with a comprehensive view of their contributions. This will include but is not limited to code, code review, infrastructure work, mailing list and chat participation, community help/building, education and outreach, design work, etc. We are deliberately not setting arbitrary quantitative metrics (like “100 commits in this repo”) to avoid encouraging behavior that plays to the metrics rather than the project’s overall well-being. We want to encourage a diverse array of backgrounds, viewpoints and talents in our team, which is why we explicitly do not define code as the sole metric on which council membership will be evaluated.

If a Council member becomes inactive in the project for a period of one year, they will be considered for removal from the Council. Before removal, inactive Member will be approached by the BDFL to see if they plan on returning to active participation. If not they will be removed immediately upon a Council vote. If they plan on returning to active participation soon, they will be given a grace period of one year. If they don’t return to active participation within that time period they will be removed by vote of the Council without further grace period. All former Council members can be considered for membership again at any time in the future, like any other Project Contributor.  Retired Council members will be listed on the project website, acknowledging the period during which they were active in the Council.

The Council reserves the right to eject current Members, other than the BDFL, if they are deemed to be actively harmful to the project’s well-being, and attempts at communication and conflict resolution have failed.

### Conflict of interest

It is expected that the BDFL and Council Members will be employed at a wide range of companies, universities and non-profit organizations. Because of this, it is possible that Members will have conflict of interests. Such conflict of interests include, but are not limited to:

-   Financial interests, such as investments, employment or contracting work, outside of The Project that may influence their work on The Project.
-   Access to proprietary information of their employer that could potentially leak into their work with the Project.

All members of the Council, BDFL included, shall disclose to the rest of the Council any conflict of interest they may have. Members with a conflict of interest in a particular issue may participate in Council discussions on that issue, but must recuse themselves from voting on the issue. If the BDFL has recused his/herself for a particular decision, they will appoint a substitute BDFL for that decision.

### Private communications of the Council

Unless specifically required, all Council discussions and activities will be public and done in collaboration and discussion with the Project Contributors and Community. The Council will have a private mailing list that will be used sparingly and only when a specific matter requires privacy.  When private communications and decisions are needed, the Council will do its best to summarize those to the Community after eliding personal/private/sensitive information that should not be posted to the public internet.

### Subcommittees

The Council can create subcommittees that provide leadership and guidance for specific aspects of the project. Like the Council as a whole, subcommittees should conduct their business in an open and public manner unless privacy is specifically called for. Private subcommittee communications should happen on the main private mailing list of the Council unless specifically called for.

Question: if the BDFL is not on a subcommittee, do they still have override authority?

Suggestion: they do, but they should appoint a delegate who plays that role most of the time, and explicit BDFL intervention is sought only if the committee disagrees with that delegate’s decision and no resolution is possible within the team. This is different from a BDFL delegate for a specific decision (or a recusal situation), where the BDFL is literally giving up his/her authority to someone else in full.  It’s more like what Linus T. uses with his “lieutenants” model.

### NumFOCUS Subcommittee

The Council will maintain one narrowly focused subcommittee to manage its interactions with NumFOCUS.

-   The NumFOCUS Subcommittee is comprised of 5 persons who manage project funding that comes through NumFOCUS. It is expected that these funds will be spent in a manner that is consistent with the non-profit mission of NumFOCUS and the direction of the Project as determined by the full Council.
-   This Subcommittee shall NOT make decisions about the direction, scope or technical direction of the Project.
-   This Subcommittee will have 5 members, 4 of whom will be current Council Members and 1 of whom will be external to the Steering Council. No more than 2 Subcommitee Members can report to one person through employment or contracting work (including the reportee, i.e. the reportee + 1 is the max). This avoids effective majorities resting on one person.

As of September 2014, the NumFOCUS Subcommittee is composed of: Fernando Perez, Brian Granger, Thomas Kluyver, Matthias Bussonnier and Stefan van der Walt.  Stefan is currently the non-council member.

Institutional Partners and Funding
==================================

The BDFL and Steering Council are the primary leadership for the project. No outside institution, individual or legal entity has the ability to own, control, usurp or influence the project other than by participating in the Project as Contributors and Council Members. However, because institutions are the primary funding mechanism for the project, it is important to formally acknowledge institutional participation in the project. These are Institutional Partners.

An Institutional Contributor is any individual Project Contributor who contributes to the project as part of their official duties at an Institutional Partner. Likewise, an Institutional Council Member is any Project Steering Council Member who contributes to the project as part of their official duties at an Institutional Partner.

With these definitions, an Institutional Partner is any recognized legal entity in the United States or elsewhere that employs at least 1 Institutional Contributor of Institutional Council Member. Institutional Partners can be for-profit or non-for-profit entities.

The most important point is that the only way of becoming an Institutional Partner is to employ individuals who actively contribute to The Project as part of their official duties. To state this another way, the only way for a Partner to influence the project is by actively contributing to the open development of the project, in equal terms to any other member of the community of Contributors and Council Members. Merely using Jupyter/IPython Software or Services in institutional context do not allow an entity to become an Institutional Partner. Financial gifts do not enable an entity to become an Institutional Partner.

An Institutional Partner is free to pursue funding for their work on The Project through any legal means. This could involve a non-profit organization raising money from private foundations and donors or a for-profit company building proprietary products and services that leverage Project Software and Services. Funding acquired by Institutional Partners to work on The Project is called Institutional Funding. However, no funding obtained by an Institutional Partner can override The Project BDFL and Steering Council. If a Partner has funding to do Jupyter/IPython work and the Council decides to not pursue that work as a project, the Partner is free to pursue it on their own. However in this situation, that part of the Partner’s work will not be under the Jupyter/IPython umbrella and cannot use the Project trademarks in a way that suggests a formal relationship.

To acknowledge institutional contributions there are two level of Institutional Partners, with associated benefits:

Gold = an institution with at least one Institutional Council Member

-   Acknowledged on the Jupyter/IPython websites, in talks and T-shirts.
-   Ability to acknowledge their own funding sources on the Jupyter/IPython websites, in talks and T-shirts.
-   Unlimited participation in the annual Institutional Partners Workshop, held during the (planned) annual Jupyter Project Retreat. This allows the Institutional Partner to invite as many of their own employees and funding sources and collaborators as they want, even if they are not project Contributors or Council Members.
-   Ability to influence the project through the participation of their Council Member.
-   Council Members invited to bi-annual Jupyter/IPython Developer Meeting.

Existing Gold level Institutional Partners:

-   UC Berkeley (Fernando Pérez, Min Ragan-Kelley, Thomas Kluyver)
-   Cal Poly (Brian Granger)
-   Rackspace (Kyle Kelley)

Silver = an institution with at least one Institutional Contributor

-   Same benefits as Gold level Partners, but:
-   Only Institutional Contributors are invited to the Institutional Partners Workshop and bi-annual Jupyter/IPython Developer Meeting.

Existing Silver Partners:

-   Bloomberg (Jason Grout, Sylvain Corlay)
-   Google (Kester Tong, Kayur Patel)