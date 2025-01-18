---
layout: infolab-toplevel
title: Join Us
permalink: /joinus/
header:
  overlay_image: /assets/images/banner_small.jpg
  overlay_filter: "0.4"
toc: true
---

# Open positions

[//]: # (At our lab we host a limited number of thesis projects, listed below. Those working on these projects become temporary members of the lab, are expected to complete the project under the agreed time constraints (typically 2.5 months for bachelors and 5 months for masters) and to actively participate in the lab activities, so that they can contribute to information sharing and knowledge development. Bachelor/Master students are expected to work full time on the project, that is, around 40 hours per week. A high degree of independence, ambition and linguistic skills (English) are necessary, as all projects are part of the research activities of the lab and are expected to contribute to it with new knowledge, algorithms, code, etc. If you are interested, please send an email to the person responsible for the project incuding your transcript, a CV, and a short motivation.)


{% for poslist in site.data.positions %}
## {{ poslist.level }}

{% if poslist.status == "open" %}

{% for pos in poslist.positions %}
{% if pos.status == "open" %}
### {{ pos.title }}

**Description:** {{ pos.description }}<br/>
**Requirements:** {{ pos.requirements }}<br/>
**Contact:** {{ pos.contact }}<br/>
{% if pos.url != nil %}<a href="{{ pos.url }}">More info</a>{% endif %}
{% endif %}

{% endfor %}
{% else %}No open positions
{% endif %}

{% endfor %}

# Before joining

This section collects some information about life in Sweden and about how we work, that can be useful if you are interested in joining the lab as a PhD student or postdoc.

## Working and living in Sweden

Sweden is a fantastic place for living and working. Swedes are friendly and speak excellent English.  The quality of life is high, with a strong emphasis on outdoor activities.  The Swedish working climate emphasises an open atmosphere, with active discussions involving both junior and senior staff.  Spouses of employees are entitled to work permits. Healthcare is free after a small co-pay and the university subsidises athletic costs, such as a gym membership.  The parental benefits in Sweden are among the best in the world, including extensive parental leave (for both parents), paid time off to care for sick children, and affordable daycare.  For more information, be sure to read <a href="https://www.uu.se/en/about-uu/join-us/advantages" target="_new">Why choose Sweden?</a> and <a href="https://www.uu.se/en/about-uu/join-us/why-uppsala-university" target="_new">Why choose Uppsala University?</a>.

## Start-up checklist

When joining the lab:

1. If you are not already in Uppsala, make sure you start looking for an accommodation well in advance, this can take time.
1. A current faculty member will register you to our internal systems.
    * Slack (we do not normally use email for communication).
    * Group storage space.
1. Follow the LinkedIn, X, and Facebook accounts of the lab, if you use these social media for work.

# Expectations from members of the InfoLab 

Being part of a lab comes with many advantages, for example in terms of access to knowledge and information, but requires everyone to make a (small) effort to contribute to the lab environment. The following are some guidelines for the InfoLab. 

## Expected availability

Given the creative nature of part of our work, Infolab members are generally free to work when and where it best fits them, compatibly with tasks requiring presence (e.g., teaching) and regulations that may be enforced by the Department or University.

At the same time, everyone is expected to contribute to the lab, which implies being available to give feedback, sharing their current research with other members (see below), and participating in lab meetings. While respecting other people's right to focus on their work, InfoLab members should feel welcome to knock on each other's doors to ask questions and discuss work-related issues. If one is working from home one day, it is good practice to inform the others, because someone else might also have planned to work from home on the same day, but decided to go to the office specifically because they thought they could talk to you about something without needing to set up a formal meeting. 

Lab members are free to take time to work offline. In particular, it is not necessary to be continuously online on our Slack space. Checking the Slack at least once a day is however expected, and if one cannot be online for a few days for any reason (e.g. holidays) it is good practice to inform the other lab members.

The information above concerns our lab. However, you are not employeed by the lab but by the division, and your contract is probably one expecting that you work at your office. Currently, our head of division is normally ok with us working at home some days, as long as this does not prevent us from performing our duties (which include being available if people need to talk to us). Therefore, if you plan to regularly work part of the time from home make sure that your immediate manager approves that.

## Research quality at the Infolab

While "quality" is a subjective term, and we expect lab members to reflect about this concept and adopt their own definitions of quality, we also have some guidelines to ensure that some common ground is established. In particular, we want our research to be based on appropriate methods, clearly and transparently communicated, developed with ethical and societal awareness, replicable (when possible), and usable by others.

To achieve this, research at Infolab is organised into *research activities*. A research activity is anything leading to a published article, a grant proposal, a PhD dissertation, an undergraduate thesis, research software, etc. Each research activity is led by a member of the lab, who is the *contact author* and is responsible for the research to advance and for its quality. Under normal circumstances, the contact author should be available to answer questions about the activity and its outcomes for at least two years after the outcome has been made public, even in case of a change of affiliation.

Members of the lab should feel a responsibility of getting and receiving feedback from other members. At the beginning of a new research activity, the (contact) author(s) is _encouraged_ to pitch the idea to other lab members, who should be available to provide constructive feedback. We trust each other not to share this information outside the lab, and we have no expectations that our feedback will be acknowledged in the resulting publications - we just do this to help each other. 

At submission time, for all products containing experiments the code to replicate the experiments should be made available in a repository, in an easy-to-execute format (with exceptions, for example double-blind review processes).

## Authorship

Each research activity must have a clear list of authors. At the Infolab we define authors as in: "each author is expected to have made substantial contributions to the conception or design of the work; or the acquisition, analysis, or interpretation of data; or the creation of new software used in the work; or have drafted the work or substantively revised it; AND to have approved the submitted version (and any substantially modified version that involves the author’s contribution to the study); AND to have agreed both to be personally accountable for the author’s own contributions and to ensure that questions related to the accuracy or integrity of any part of the work, even ones in which the author was not personally involved, are appropriately investigated, resolved, and the resolution documented in the literature."[^1]

[^1]: Transparency in authors’ contributions and responsibilities to promote integrity in scientific publication. Marcia K. McNutt, Monica Bradford, Jeffrey M. Drazen, Brooks Hanson, BobHoward, Kathleen Hall Jamieson, Véronique Kiermer, Emilie Marcus, Barbara Kline Pope, Randy Schekman, Sowmya Swaminathan, Peter J. Stang, Inder M. Verma. Proceedings of the National Academy of Sciences Mar 2018, 115 (11) 2557-2560; DOI:10.1073/pnas.1715374115

# PhD supervision policy

## Courses

In our PhD programme, every PhD student must obtain 60 credits from "courses". While sometimes called "courses", these can be very different from Master-level courses (which, in Uppsala, typically consist of multiple weekly lectures, labs, assignments, etc. over around 10 or 20 weeks). In some cases, a PhD course is just about individual readings and a written or oral presentation of the studied content. In other cases, courses involve lectures and interactions with other students, with either intensive meetings over a few consecutive days or less frequent meetings spread along the academic year. Some of the courses can however be actual Master's courses, upon agreement with the supervisors and the course responsible teacher.

Courses are a fundamental part of the education, which (as indicated in the ISP goals) is not just about writing research papers but also about acquiring broad knowledge beyond the specific topic of the PhD and other soft and hard skills. "Research introduction for PhD students" is strongly recommended. "Research ethics" (at least 2 credits) and "Academic teacher training course" (7.5 credits, for those involved in teaching which is the default except for industrial PhD students) are mandatory and given by the Faculty. Some courses are given by InfoLab teachers and provide basic knowledge and skills in the general research field of the lab. Our students are expected to take these courses if they do not already have the corresponding knowledge or other pressing tasks to perform. Examples of courses given by Infolab members that are in the general research field of the lab can be found on our webpage.

Courses must always be agreed _in advance_ with the main supervisor, as this is part of the PhD planning and because the number of credits that can be registered and used for the PhD is typically not pre-defined. For example, when reading a Master's course: (1) as credits correspond to study time, it can sometimes be assumed that a PhD student will use less than the expected study time of an average Master's student. (2) Some parts of the course may not be relevant for the PhD education. Some parts of a course can even be skipped, or replaced with more useful tasks, such as a custom project.

While your supervisor typically decides how many credits to assign to each course, these are general guidelines:

- For PhD-level courses given at our Faculty and open to all PhD students at the Faculty, e.g. teacher training, the number of credits is normally the one proposed by the teacher of the course.

- You may, in special cases, get credits if you teach MSc courses that you had not previously studied. The part of your employment devoted to teaching assistantships (TA) is paid by State funding for UGA (undergraduate education). Normally, part of your TA time is already allocated for you to prepare. If you teach a course that you have not taken in your previous studies, and the time allocated for preparation is not sufficient, your supervisors can decide to assign [alpha] x [credits of the theory part of the course] credits. The rationale is that at the end of the course you will have also learned part of the course content as if you had read the course. Alpha is decided by the supervisor based on content and duties for each course. No specific examination is needed to obtain these credits beyond being a TA.

- PhD students are welcome and encouraged to propose reading courses that can be of common interest for people in the lab and/or other PhD students at the Department. Feel free to discuss this with your fellow PhD students, and make a proposal to your supervisor.

- Credits for summer schools typically correspond to 1.5 for a week-long school, plus additional credits if additional work is needed for the examination. It happens that external summer schools promise unreasonable amounts of credits, so remember that the actual credits are decided by your supervisor.

- Participating in conferences is part of the PhD education, so in general this does not correspond to credits. Individual supervisors may have different arrangements.

## Funding sources

Every PhD student is funded by a combination of different sources. Most of the time, this does not have an immediate impact on the student's activities, and it is mainly a matter of interest for the supervisor. However, there are some obligations and opportunities associated with funding sources. These are the most typical:

- For externally funded projects, there is always a (more or less constraining) project proposal, sometimes in the form of formal contracts between the Department and the funding agency. Students funded by external projects can be expected to deliver specific (types of) results. Your supervisor is typically in charge of the funding (although it is always the Department being financially responsible and having to approve all expenses).

- For (partly) internally funded students, the Professor responsible for the Research Programme (PAP) is in charge of the funding. So any expenses beyond the salary have to be approved by the PAP. See the details about traveling below.

## Travelling

**For internally funded students**, you have to follow the Division's policy for travelling (which is the same for all research personnel, from PhD students to professors). While the details can be found in the original document and may change in time, a practical summary is that:

- Travelling expenses are normally covered if you travel to a conference to present your research.

- For PhD students, "normally" can be interpreted as: "the presentation must be important for the development of the PhD plan". Your supervisor will make sure that this is the case when possible publication venues are discussed.

- In any case, a budget must be approved by the person responsible for the funding _before the trip is booked_.

- It is important to use these resources wisely, e.g. by looking for modest accommodation and travelling. This is (in most cases) money coming from tax-payers, taken from the same (limited) source used to fund the salary of other PhD students, etc.

**The following guidelines complement the ones at division level:**

- A typical (although in no way constraining) case is that each PhD student presents one work at a conference every year. This is important to train presentation skills and to build your network. For conferences without proceedings, the work is then submitted as a journal article. During the first year, when research results may not yet be ready for submission, a summer school in the area of the PhD can be considered as an alternative to a conference participation.

- When possible, climate-friendly travelling alternatives should be preferred. - Given that conferences travel around the world and each major conference will be in Europe at least once and normally multiple times during a PhD education, _when we submit our papers we try to favour conferences planned in Europe_. We will still be able to be present at the important venues in our area, while also having a low environmental impact.

- During the PhD it can be good to participate in a PhD school (e.g. a summer school), as mentioned above. This can be done at the beginning, to get in touch with other relevant PhD students in your area, or later, to deepen your knowledge and network on a specific advanced topic that is important for your studies. The relevance of the school for your studies has to be argued in advance with the PAP (if to be covered with State funding), but participation in a PhD school during your studies is encouraged and will be supported by your supervisor.

- The fact that relevant and important travelling is generally covered by the Department means that you do not have to worry about this. At the same time, we expect our students to apply for external funding. This is part of your education (writing grant requests), it is good for your CV, it is common for our PhD students to indeed obtain funding, and this is funding you are in charge of, so in principle you can participate to as many conferences/schools/etc. as long as you can acquire those resources.

During the PhD studies, we expect all students to spend some time (normally a few months) at a different research centre, usually abroad. This is important for many reasons - including experiencing different ways of doing research, different supervision styles, networking, access to resources, etc. You keep receiving your salary during this stay, but often there are additional expenses (e.g. having to rent a new apartment while you may not be able to rent out yours in Uppsala), so it is particularly important to look for external funding. Various sources are available.

## Papers and co-authorship

When you start working on a new research task as part of your PhD, you must always involve your supervisor(s). This is not intended as a way to control you - in fact, at the end of your PhD you should be able to design and write a paper without the need for your supervisor's input. However, especially at the beginning of your studies there is a risk that you are missing some information or questions that you have not thought about (e.g. You are using the Department's and lab affiliations - what does this imply? Is this research topic compatible with the sources funding it?). This is also the case for side-research-projects that are intended to be done in your spare time - as these, by experience, have a high chance of interacting with your PhD work, and should thus be planned jointly.

When you write papers related to your PhD, your supervisors will also typically be your co-authors. At the lab we follow international guidelines about co-authorship (see above), but ultimately the rules and meaning of being a co-author is something discipline-specific. Even explicitly specifying the contribution of each author in the paper (which is recommended in general) can send different messages depending on the discipline. For example, in most areas of computer science your supervisor is expected to be specified, and an additional note specifying that the contribution of the person has been "supervision" can be interpreted as suggesting a lower involvement than one would otherwise assume. Not having your supervisor as a co-author might even suggest to future prospective employers that there has been some conflict. On the contrary, in other areas, having your supervisor as a co-author is not expected, and would raise questions about your role and independence. This is an important and challenging topic for our lab, being part of several interdisciplinary collaborations. The default behaviour is that (1) your supervisor(s) _who meet our general co-authorship criteria_ will appear as co-authors; (2) for venues where this is expected or useful, the contributions of each co-author will be explicitly mentioned in the paper, and (3) individual special cases must always be discussed in advance.