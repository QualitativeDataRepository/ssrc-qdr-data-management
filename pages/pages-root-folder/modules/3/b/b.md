---
title: "Sharing Human Participants Data"
layout: page-fullwidth
breadcrumb: true
header: false
hidefooter: false
module: "3b"
lesson: "Module 3, Lesson 2"
categories: [module3,modulecontent,hasexercises]
permalink: "/modules/3/b/"
next: "/modules/3/c/"
previous: "/modules/3/a/"
description: "Protecting human participants is an ethical imperative for researchers. How can you make sure to do so when sharing your data?"
learningobjectives:
-   How you can (often) share data involving human participants
-   When you should and should not de-identify data
-   Best practices in de-identifying data garnered through interacting with human participants
-   What to do when you cannot de-identify human participants data
-   When and why you might control access to your shared data
-   What options for access controls there are   
initialquestions:
-   What are some of the particular challenges of sharing qualitative data involving human participants?
-   Can you envision situations in which a researcher might not need to de-identify data from human participants before sharing them?
---
{% include _learningobjectivesandquestions.html %}

## Ethics of Sharing Qualitative Data

Qualitative researchers often work closely with human participants, conducting in-depth interviews, focus groups, and oral histories, or engaging in participant observation and ethnography. Most social scientists feel a profound ethical obligation to their participants, and  responsibility for ensuring that their research does not negatively impact these individuals. Sharing data generated through human participants research can expose your participants to additional risk, however. As a result, you need to take special care when you share such data to be sure that you do so ethically and legally.

According to the [1979 Belmont Report](https://www.hhs.gov/ohrp/regulations-and-policy/belmont-report/index.html){:target="_blank"}, three key principles create the conditions for ethical research:

-   *Respect* – Showing respect for the personal autonomy and agency of your research participants.
-   *Beneficence* – Seeking a balance between minimizing potential risks to individual participants and to society while maximizing benefits to both.
-   *Justice* – Being fair to individual participants, neither exploiting nor ignoring one group to benefit another.

If you are based in the US, the Institutional Review Board (IRB) at your home institution is best-placed to help you put those principles into practice – i.e., to collect, use, and share data from human participants in a legal and ethical way. (Most other countries have similar organizations to ensure ethical research practices, though they operate under different, if typically similar, rules). IRBs are administrative entities established to protect the rights and welfare of individuals who become involved in research activities conducted under the auspices of the institution with which the IRB is associated. If your research will involve human subjects directly or indirectly, as defined in federal regulation, you need to submit it for review and approval by the IRB at your institution before you advertise the project, or recruit or interact with any human participants.

Social scientists and information scientists are developing strategies, tools, and technologies to make it easier for you to share the information garnered from your human participants in your research in an ethical way. In module 1 you learned how to obtain consent from your human participants – how to help them to understand how you would like to use the information they provided, how you would like to share that information, to what uses it might be put, and what potential risks and benefits these actions present. Below we discuss two other steps you can take to keep your human participants safe.

## De-identifying Data

As part of obtaining informed consent, we frequently assure interview respondents or focus group participants that their identities will not be revealed, and that others will not be able to link them to their answers. In order to keep these promises even when planning to share the data, you can “de-identify” their responses, that is, seek to remove identifying information.

### Direct and Indirect Identifiers

- All de-identification begins with removing “**direct identifiers**” (i.e., pieces of information that are sufficient, on their own, to disclose an identity), such as proper names, addresses, and phone numbers. This is typically straightforward.
- “**Indirect identifiers**” consist of contextual information that can be used, often combined with other information, to identify a participant. For example, [*in a seminal paper*](https://dataprivacylab.org/projects/identifiability/){:target="_blank"}, Latanya Sweeney showed that almost 90% of the US population could be identified based on their zip code, date of birth, and gender; even using place (like city or municipality) instead of zip code still allows more than 50% of the population to be uniquely identified. Such indirect identifiers are often found throughout rich, qualitative data and need to be handled with great care.

### De-identification Practices

Some good practices will make de-identifying responses from your human participants easier and more reliable.

-   **Do not** collect identifying information if you do not need it. For instance, you will typically not need full names and contact information for focus group participants. Be mindful, though, that not collecting such information will prevent you from going back to participants with follow-up questions.
-   **Do** plan on engaging in de-identification soon after your interactions with your human participants, marking up elements that require redaction during transcription and/or analysis.
-   **Do** clearly and consistently indicate any changes you make to the original file, e.g., by placing square brackets around passages that have been changed.
-   **Do not** redact xxxxxx or remove \[...\] names and locations. Instead, you could use pseudonyms. Alternatively, you could use  aggregate nouns (e.g., refer to the state in which an individual  lives rather than the town or county) or categories (e.g., “...  was born in \[1975-1980\]” instead of 1977). **Do** keep linkages  in your data intact by applying pseudonyms, aggregate nouns, and  categories consistently.
-   **Do** keep a list of de-identification rules, both for yourself, or  for your team should you collaborate. This list serves as  important documentation when you share your data. See for example  the [protocol used by Thad Dunning and Edward Camp](https://doi.org/10.5064/F6Z60KZB/0NR0VZ){:target="_blank"} to de-identify data deposited with the Qualitative Data Repository. This document is  separate from the actual key that links de-identified entries to  the original individuals or entities, which should not be included  when you share your data.
-   **Do** check the document properties of files, which may contain identifiers such as original file names identifying interview respondents.
-   Finally, **do** strike a balance between keeping your participants’ information confidential and unnecessarily reducing the analytic value of the data by removing too much information.

### When not to De-identify

Not all qualitative data garnered from human participants need to be de-identified.

-   When interviews were conducted “on the record,” the resulting notes or transcripts can be shared using the respondent’s name. This may be the case for elites, who are accustomed to journalistic  interviews. Be mindful, however, of local practices: in some  countries, it is expected that interviewees will have an  opportunity to review the written record of the interaction before  it is made public or published.
-   Data that are already part of the public record (e.g., public  statements by politicians) don’t need to be de-identified.

### Limits of De-identification

Not everything can be de-identified. If you interview a US Supreme Court justice, say, no reasonable amount of redaction is going to allow you to keep their identity confidential. You may also not be able to protect the identity of interview respondents from absolutely *everyone*. For example, if you interview people in a small village, you can often mask their identities from other researchers and most everyone else, but their neighbor, knowing that you talked to them, would likely be able to recognize them from shared data. In those cases, controlling access to data can be a useful complement to (or replacement for) de-identification.

{% include _exercise.html exerciseid="17" %}


## Access Controls
As we note above, complete de-identification is often impossible. As such, de-identification, on its own, might be insufficient to protect the identity of human participants. In order to share their contributions to your research project more broadly in an ethical way, additional steps are needed, such as controlling *who* can access the data, *how* they can do so, and *when*. When you store your data in a trusted digital repository, you can request that various types of restrictions be placed on their access (unless a funder specifically and strictly prohibits this). Access controls are sometimes mistakenly viewed negatively as restrictions. In reality, they allow you to share data that would otherwise remain entirely inaccessible. That is, they allow research to be 
>as open as possible, as closed as necessary 

(as the European Union’s [*Horizon2020 guidelines*](https://ec.europa.eu/research/openscience/pdf/openaccess/ord_extension_faqs.pdf){:target="_blank"} for research aptly put it).

### Types of Access Controls

Access controls can be placed in three broad categories:

1.  **Who** can access your data? Access to your data might be  restricted, e.g., to researchers with a legitimate interest in the  data (as proven by a research proposal) or anyone who wishes to  access the data may be required to secure approval from their IRB.

    *Note:* While it seems counterintuitive, we generally recommend  that you allow repository personnel to guide decisions on data  access. If your permission were required, for instance, the  data may become inaccessible if the repository is unable to  contact you at some point in the future.

2.  **How** can others access your data? They may have to use special  secure internet connections to download the data and sign  agreements about the safe storage and eventual destruction of  their copy of the data. In special cases, you may even require  that researchers access the data in person at a repository or  other location using a computer disconnected from the internet. Some repositories offer hybrid solutions between these two  options, such as ICPSR’s “virtual enclave,” which allows remote  viewing of data which never leave the server.

3.  **When** can others access your data? So called embargos (i.e., periods when your data are absolutely inaccessible to anyone) can  sometimes be used as an additional protection for human  participants. Most often, they are relatively short and oriented  toward ensuring the ability of the researcher to publish on the  data prior to making them accessible to others. In some cases, however, embargos can make valuable data available in the long run  by setting a “lifting date” when human participants will be  deceased, for instance. Historical archives often have such rules  for personal papers.

### Using Access Controls

As with engaging in the de-identification of data, using access controls always entails a trade-off: the more stringent the controls, the less likely the misuse of the data, but the harder it is for others to access, and thus use, the data. While access controls are a powerful (and in our opinion, underutilized) tool for data sharing, they should not be used gratuitously for data that pose no risk.

Choosing access controls should typically be done in consultation with a specialist at a repository. Based on your in-depth knowledge of your data and its context and the repository’s understanding of technical options and best practices, you will be able to arrive at a safe – and thus ethical – solution.

## Resources

-   Mosley, Layna. 2013. [*Interview Research in Political Science*](http://www.cornellpress.cornell.edu/book/?GCOI=80140100891800){:target="_blank"}. Cornell University Press.
-   Further [guidance on de-identifying data](https://qdr.syr.edu/guidance/human-participants/deidentification){:target="_blank"} on QDR.
-   Guidance on [de-identifying qualitative data](https://www.ukdataservice.ac.uk/manage-data/legal-ethical/anonymisation/qualitative){:target="_blank"} by the UK Data Archive.
-   ICPSR’s [guidance on data sharing](https://www.icpsr.umich.edu/icpsrweb/content/deposit/guide/chapter5.html){:target="_blank"}
). Note in particular the section on data enclaves at the end.
