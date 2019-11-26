---
 title: "Transforming Data (Digitizing, Transcribing, Translating)"
 layout: page-fullwidth
 breadcrumb: true
 header: false
 hidefooter: false
 module: "2d"
 lesson: "Module 2, Lesson 4"
 categories: [module2,modulecontent,hasexercises]
 permalink: "/modules/2/d/"
 next: false
 previous: "/modules/2/c/"
 description: "What are some ways that you might change the form or format of your data, and what are some best practices for doing so?"
 learningobjectives:
 -   How archiving professionals think about transforming data
 -   The various ways in which data can be “transformed” from one form or format to another
 -   How technology can assist with data transformation
 -   How different types of transformation augment the accessibility of your data
 -   The importance of documenting all data transformations in which you engage
 initialquestions:
 -   Under what circumstances is it more, and less, useful to digitize research data and documentation?
 -   What makes transcribing audio / video recordings from interactions with research subjects challenging?
 -   Do you have to translate your transcripts?
---

{% include _learningobjectivesandquestions.html %}


## An Archivist's View on Transformation

Specialists at libraries, repositories and archives think about and carry out data transformation *for a living*. They’re available to help you, and you can learn lessons from their key practices.

After a scholar deposits a dataset in a data repository, the repository frequently transforms the data files that comprise the dataset in various ways. File formats are changed for better long-term storage, information such as variable labels is added to files, files that are not suitable for sharing (e.g., due to sensitivity) are removed or suppressed from publication (in consultation with the depositor), etc.. A repository engaging in these sorts of transformations enhances the integrity and usefulness of the data. Yet at the same time, transforming data makes archivists and repository personnel very nervous: mistakes can cause irreparable damage and loss.

The Library of Congress (LoC) clearly and succinctly lays out its [principles for reformatting](https://www.loc.gov/preservation/about/prd/presdig/presprinciple.html) (an aspect of what we call transformation here), describing the quintessential archival view. An ironclad principle of digital archiving is *to never change or destroy the original files or documents*. You can follow this principle in your own work as well:
-   If you convert your images to PDF files and run character recognition on them, *store the original images*, even if you may never consult them again.
-   If you want to convert your interviews to a different file format to take up less disk space on your laptop, *store the original files on an external hard disk*.
-   If you need to convert videos you have taken on your iPhone from Quicktime (.mov) to MPEG (.mp4) so they can be more easily analyzed using a particular tool, *do not delete the original videos*.


## Digitizing Archival (and Other) Documents

In your research – especially if you work in archives – you will encounter lots of useful documents that you can’t just take along with you when you leave an institution or context where you are conducting research. Often, though, you will be able to “capture” such documents by digitizing them (creating a digital image of them). We offer below some tips on effective digitizing.

No matter where, how, and what you digitize, you want to think about the quality of the resulting images. The LoC recommends that you “Capture the highest quality digital image technically possible and economically feasible”. In particular for social science researchers with limited budgets, the second part of this advice is crucial – no one expects you to pay for or drag around professional digitization equipment. At the same time, you will regret making poor quality images (and other recordings): text recognition may not work properly, individual images may be unreadable, outputs will be less valuable for other researchers, etc.. **Planning Ahead**

Many archives allow you to use a camera to take pictures of documents you consult. This is *not* true for all archives though, and some archives that generally permit cameras will impose conditions (no tripod, no flash, daily fee for camera usage). Make sure to look for information about what is permissible before you go to an archive, and inquire with archive personnel, and/or other scholars whom you know have carried out research in that archive, if you cannot find the rules on the archive’s website.

Based on what you are able to learn about the archive and its rules, *test your setup before going to the archive,* making sure that you are easily able to produce high-quality images.

### Equipment

Begin with a good tripod or table mount that allows you to stabilize your camera. In the archive, mark the picture field of the camera on the table where you are working (for instance, by drawing it on a piece of paper and securing the paper to the table) so that you can quickly take pictures without checking the camera screen. A remote control for the camera will greatly facilitate your work. High quality images take up significant space on your camera’s storage card and taking a great number of images (as you may in a typical day in the archives) will drain a camera’s battery. Make sure to bring additional storage cards and batteries.

#### Phone vs. Camera

Cell phone cameras can be excellent replacements for digital cameras, and the quality of cell phone cameras is constantly improving. Moreover, dedicated scanner apps on your phone allow you to convert images into multi-page PDFs on the fly, reducing the amount of space you need to store files and the time you will later need to assemble PDFs. These advantages do come at a cost in quality, especially if you’re photographing faded documents and/or have to operate in poor lighting conditions. See [this discussion by Cornell University Library](https://guides.library.cornell.edu/c.php?g=31776&p=1375333) for more information on using cameras in archives. Still, many social scientists find using a phone the most practical solution.

#### PDF and Optical Character Recognition (OCR)

If you saved individual images of individual pages of an archival document from your camera onto your computer, the next logical step may be to assemble those images into a single PDF document (replicating the original archival document). Doing so will make it easier for you to manage, manipulate, and potentially annotate the images down the line. If you have access to Adobe Acrobat Pro, you can easily select any number of images and convert them into a single PDF. Alternatively, there are numerous free online tools as well as the “[Image Magick](https://imagemagick.org/script/convert.php)” commandline utility that provide the same functionality.

You may eventually wish to use Optical Character Recognition (OCR) to turn a scanned image file (e.g., a PDF) into computer-readable (and thus searchable, and copyable) text. Especially if you are working with large amounts of archival documents, being able to search for terms across all of them is invaluable.[OCR tools](https://www.techradar.com/news/best-ocr-software) require high-quality images in order to properly recognize characters. Available tools also vary in quality. We recommend that you test several OCR solutions before settling on the one you’ll integrate into your toolchain.

{% include _exercise.html exerciseid="12" %}

## Transcribing Audio / Video from Interactive Data Collection

If your research involves certain types of interactions with human beings (e.g., conducting surveys, interviews, or focus groups, or doing oral histories), you may choose to create an audio or video recording of those interactions. If you do so, you may then choose to “transform” those recordings into text. The process of doing so is called “transcribing.”

### Why Transcribe?

There are two overarching reasons why you might transcribe the recordings (audio or video) of your interactions with human participants.

You may do so for your own purposes, as in these examples:
-   You plan to use long, exact quotes as evidence in the article or book for which you did the research;
-   You plan to engage in content or discourse analysis and the precise language and wording that your human participants employed are integral to your study;
-   You plan to analyze your data using Computer-Assisted Qualitative Data Analysis Software (CAQDAS), which requires textual inputs.

Alternatively, you may transcribe your audio / video recordings because the data are more accessible to other scholars – indexable, searchable –
when they are in textual rather than audio or video form. Transcribed data can be more readily [de-identified](https://managing-qualitative-data.org/modules/3/b/#de-identifying-data) than audio or video, further facilitating sharing. Transcripts are thus easier for other scholars to use to evaluate the findings in your written products, or to pursue their own intellectual objectives.

Transcribing is resource intensive, however, no matter how you go about it. If you do not need a word-for-word textual reproduction of your research exchanges, you may wish to consider alternatives to transcribing. For instance, you might create a “table of contents” of your audio or video recordings, writing a light summary of the content and tenor of the conversation at two or three minute intervals. Alternatively, you might generate a brief overall summary of the interaction, highlighting particularly important moments or the
“juiciest” quotes (noting the hour/minute during the interaction at which each occurred). Of course, none of these alternatives is as rich, accurate, or high-fidelity a data source as a transcript.

### How to Transcribe

If you decide to transcribe your audio or video recordings, you have several choices with regard to how to do so.

#### DIY: Technology-Assisted Transcription

You may decide to transcribe your audio / video recordings yourself. Doing so allows you to avoid the potential risk of sharing the raw audio
/ video files with anyone (and the potential time involved in developing processes and protocols to do so), to remain as close to the data as possible, and to have maximum control over the resulting product. If you transcribe your recordings, you will likely use some kind of software to assist you. Before deciding to do your own transcriptions, try your hand at transcribing – perhaps with a free version of the type of technology you would most likely use – to get a sense of the process, keeping in mind how many exchanges need to be transcribed.

There are three main types of software you might employ:
-   Dictation (“speech to text”) software (such as “Dragon Naturally Speaking”), which allows you to “re-speak” the exchanges from your audio or video recording, leading to a text transcript (the re-speaking is necessary because you train the software to understand your voice and diction).
-   Transcription software, which allows you to upload audio / video recordings onto your computer and play them back (with easy stop / pause functionality) while you simultaneously type what you hear into a text document.
-   Automatic transcription tools(https://www.poynter.org/tech-tools/2017/the-best-automatic-transcription-tools-for-journalists/)

There are many products of each type. Here are some criteria to keep in mind as you consider different options:
-   Which version of the software / tool has the functionality that you need (the “free trial” or “basic version” may not)?
-   How much does the version of the software / tool that would be useful for your purposes cost?
-   Does the software work on your computer’s operating system?
-   Does the software / tool import audio / video files in the format in which you have them?
-   In what format is the transcript produced (and can it be transformed into the format that you want it in)?
-   Is the software proficient in the language in which your audio / video recordings were made?
-   How does the software handle extraneous noise, pauses, etc.?
-   How does the software handle timestamps?

No matter which option you choose, you should establish a set of rules to follow when transcribing. Doing so will make you more efficient (as you will not need to re-consider / re-make decisions), and will help your transcripts to be consistent. You might create rules for:
-   How transcript files will be named (considering how this aligns with the file names of audio and video files)
-   -   How who is speaking will be indicated
-   How extraneous noises (e.g., sighs, sneezes, speech by others who entered the space in which the exchange is occurring) will be indicated
-   How pauses, and unintelligible words and phrases will be indicated
-   How timestamps will be inserted in the transcripts

#### Outsourcing Transcription Services

Another option is to outsource transcription. One option is to formally contract a freelance transcriber or transcription firm. You should identify and talk with a few clients of the firm to make sure that they have done good work and to solicit tips on working with them. Alternatively, you might proceed more informally, hiring one or more individuals, perhaps with specialized knowledge, to assist you. Depending upon whom you choose, your transcribers may serve as “research assistants” to the project, offering useful intellectual input in addition to transcribing. Before hiring transcribers, you should interview several candidates to ensure that they are trustworthy, reliable and detail-oriented, and understand the tedious nature of the work.

No matter which option you choose, it will be useful to write and sign a contract outlining the main parameters or your arrangement. (A firm will likely require this; it is a good idea for you to develop a non-legally binding contract when you hire transcribers informally as well.) At a minimum, that contract should detail four items:
-   The estimated size and timeline for the project (including the timing of transcript delivery, with intermediary milestones and a final due date)
-   The process for exchanging files with transcribers
    -   If your recordings of your interactions with human participants include sensitive data, you may want your transcriber(s) to sign a non-disclosure agreement (NDA), and you will need to think of secure ways to transmit the data and resulting transcripts between you and your transcribers.
-   Your rules / instructions for transcribing (as described above)
-   Payment structure – there are many metrics
    -   You could establish an hourly rate based on number of hours of recorded material, or based on number of hours spent transcribing
    -   You may establish a rate for each page transcribed.
    -   Consider how each option incentivizes your transcribers.

Your transcribers need to understand and be willing to follow your rules. Once they start working, you should check the first few transcriptions carefully to make sure transcribers are adhering to your rules. Thereafter you should give at least a cursory look to each transcription as it is submitted for light quality assurance.

### Transcripts: An Example

To get a sense of a high-quality transcription, visit the page of the [Civil Rights History Project](https://www.loc.gov/collections/civil-rights-history-project/?fa=original-format:film,+video). You’ll find hundreds of videos of interviews with participants in the civil rights movement, each accompanied by a high-quality transcript. You can read a few transcripts while listening to the corresponding recordings to develop a sense of good transcription practices.

![Civil Rights History Project]({{ site.baseurl }}/images/civil-rights-archive.png)
### Documenting Transcriptions

While making audio or video recordings of research interactions has significant analytic benefits, recordings cannot faithfully reflect all of the nuances of human interaction. There are always unspoken dynamics, facial expressions, hand gestures, and other aspects of such interactions that are not reflected in audio recordings and even in video recordings. Textual transcripts are then another step removed from the original interaction: intonation, tone, and other details cannot be perfectly reflected in a transcript. While this impoverishing of the data is unavoidable, you can mitigate it by writing excellent “informal documentation” of your research interactions as discussed in the
“Documenting Data in Practice” lesson. This informal documentation will prove useful both to the “future you” employing these data later in time, and to other scholars who wish to re-use them.

{% include _exercise.html exerciseid="13" %}

### Translating Transcriptions

The option of translating your transcriptions most often arises when your research interactions -- and thus your transcriptions of those exchanges -- are in a language that is different from your native language and/or the language in which you’re writing the article or book resulting from the research.

On the one hand, it is not *necessary* to translate transcriptions that are in a foreign language: you may be able to analyze the data they contain and conduct your inquiry without doing so.
-   If you are fully proficient in the languages in which you conducted data collection, you may be able to interact efficiently with the transcripts – read, recall, and analyze – without translating them.
-   Alternatively, you may translate only a subset of the transcripts, or simply translate the excerpts that you ultimately use in your research product.
-   It may even be analytically unproductive to translate your transcripts: if you are engaging in discourse analysis, for instance, even a very close translation may distort the data.

On the other hand, you might want to translate because:
-   You had proxies engage in your interactive data collection because you don’t speak the language in which the exchange occurred.
-   Having translations of your transcripts will make them easier for you to analyze (given how you plan to carry out your analysis) and ultimately use as the evidentiary base for your research product.
-   You want to expand the population of potential secondary users for the fruits of your data-collection efforts by translating those fruits into an additional language.

The main criteria you should use to decide whether or not to translate your transcriptions are (1) whether doing so or not doing so will best position you to maximize the utility and evidentiary potential of your exchanges with human participants,and (2) the time and expense that translation will involve.

It may seem inefficient to transcribe your audio or video recordings first *and then* translate the transcripts. However, you will generally end up with better transcriptions and translations if the processes are carried out separately. Also, if you are using software to assist you with these transformations, or contracting others to do so, most software and services specialize in one or the other type of transformation.

If you translate a good number of your transcripts, you’ll face choices similar to those associated with transcribing your recorded exchanges. Our suggestions for making those choices, and our recommendations for carrying out the tasks your choices imply, are analogous to those we offered with respect to transcription; we reprise them very briefly here.

If you choose to translate your transcripts yourself, you may employ technology to assist you. You might just use “Google translate” or a similar automated translation service, or other options for technologically assisted translation; you can use the criteria we suggested above to choose among the various possibilities. If you outsource translation to a freelancer or firm, engage in the due-diligence, and write the type of contract, that we suggested in the previous section, and carefully review the initial products from the freelancer or firm to assure quality. No matter which option you choose, you should establish a set of rules to follow when translating, again along the lines suggested in the previous sub-section.

{% include _exercise.html exerciseid="14" %}

## Further Resources

- University of Illinois Library: Digital Historian Series: Using Digital Tools for Archival Research,
[*https://guides.library.illinois.edu/c.php?g=348155&p=2346513*](https://guides.library.illinois.edu/c.php?g=348155&p=2346513){:target="_blank"}
- The Best Automatic Transcription Tools for Journalists [*https://www.poynter.org/tech-tools/2017/the-best-automatic-transcription-tools-for-journalists/*](https://www.poynter.org/tech-tools/2017/the-best-automatic-transcription-tools-for-journalists/){:target="_blank"}
