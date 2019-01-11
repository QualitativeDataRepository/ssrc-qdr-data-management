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
 description: "How do you decide on the best venue for sharing your data?" 
 learningobjectives:
 -   How archiving professionals think about transforming data
 -   The various ways in which data can be “transformed” from one format to another
 -   How technology can assist with data transformation
 -   How different types of transformation augment the accessibility of your data
 -   The importance of documenting all data transformations in which you engage 
 initialquestions:
 -   What is the value of digitizing documents?
 -   What makes transcribing audio / video recordings from interactions with research subjects challenging?
 -   Do I have to translate my transcripts?
---

{% include _learningobjectivesandquestions.html %}


## An Archivist's View on Transformation
-------------------------------------

In this lesson you learn about different ways of transforming your data. Specialists at libraries, repositories and archives think about and do these kinds of things *for a living*. They’re available to help you, and you can learn lessons from their key practices.

After a scholar deposits a dataset in a data repository, the repository frequently transforms the data files that comprise the dataset in various ways. File formats are changed for better long-term storage,
information such as variable labels is added to files, files that are not suitable for sharing (e.g., due to sensitivity) are removed (in consultation with the depositor), etc. A repository engaging in these sorts of transformations enhances the integrity and usefulness of the data. Yet at the same time, transforming data makes archivists very nervous: mistakes can cause irreparable damage.

The Library of Congress (LoC) clearly and succinctly lays out its
[*principles for reformatting*](https://www.loc.gov/preservation/about/prd/presdig/presprinciple.html)
(an aspect of what we call transformation here), describing the quintessential archival view. An ironclad principle of digital archiving is *to never change or destroy the original files or documents*. You can follow this principle in your own work as well:
-   If you convert your images to PDF files and run character recognition on them, *store the original images*, even if you may never consult them again.
-   If you want to convert your interviews to take up less disk space on your laptop, *store the original files on an external hard disk*.
-   If you need to convert videos you have taken on your iPhone from Quicktime (.mov) to MPEG (.mp4) to use in a tool, *do not delete the original videos*.

## Digitizing Archival (and Other) Documents

In your research -- especially if you work in archives -- you will encounter lots of useful documents that you can’t just take along with you. Often, though, you will be able to “capture” them digitally -- create a digital image of them. The LoC recommends that you “Capture the highest quality digital image technically possible and economically feasible”. In particular for social science researchers with limited budgets, the second part of this exhortation is crucial -- no one expects you to pay for or drag around professional digitization equipment. At the same time, you will regret making poor quality images (and other recordings): text recognition may not work properly, individual images may be unreadable, outputs will be less valuable for other researchers, etc.. Here we offer some tips on effective digitizing.

### Planning Ahead

Many archives allow you to bring a camera and take pictures of documents you consult. This is *not* true for all archives though, and some archives that generally permit cameras will impose additional conditions (no tripod, no flash, daily fee for camera usage). Make sure to look for information about what is permissible before you go to an archive, and inquire if you cannot find the rules on the archive’s website.

Based on what are you able to learn about the archive and its rules, *test your setup before going to the archive,* making sure that you are easily able to produce high-quality images.

### Equipment

Begin with a good tripod or table mount that allows you to stabilize your camera. In the archive, mark the picture field of the camera on the table where you are working so that you can quickly take pictures without checking the camera screen. A remote control for the camera will greatly facilitate your work. High quality images take up significant space and the number of mages you take in a typical day in the archives will drain a camera’s battery. Make sure to bring additional storage cards and batteries.

#### Phone vs. Camera

Cell phone cameras can be excellent replacements for digital cameras, and the quality of cell phone cameras is constantly improving. Moreover, dedicated scanner apps on your phone allow you to convert images into multi-page PDFs on the fly, reducing storage space and the time you will later need to assemble PDFs. These advantages do come at a cost in quality, especially if you’re photographing faded documents and/or have to operate in poor lighting conditions. See [*this discussion by Cornell University Library*](https://guides.library.cornell.edu/c.php?g=31776&p=1375333) for more. Still, most social scientists find using a phone the most practical solution.

#### PDF and Optical Character Recognition (OCR)

If you saved individual images from your camera, you will likely want to assemble them into PDF documents (with all the images from a particular archival document in one PDF). Doing so will make it easier for you to manage the images, and allow you to annotate them, and possibly OCR them, down the line. If you have access to Adobe Acrobat Pro, you can easily select any number of images and convert them into a single PDF. Alternatively, there are numerous free online tools as well as the
“[*Image Magick*](https://imagemagick.org/script/convert.php)” commandline utility that provide the same functionality.

Optical Character Recognition (OCR) turns a scanned image file into computer-readable (and thus searchable, and copyable) text. Especially if you are working with large amounts of archival documents, being able to search for terms across all of them is invaluable. [*OCR tools*](https://www.techradar.com/news/best-ocr-software) rely on high-quality images to allow them to properly recognize characters. Available tools also vary in quality. We recommend you test several OCR solutions before settling on the one you’ll integrate into your toolchain.

{% include _exercise.html exerciseid="13" %}

## Transcribing Audio / Video from Interactive Data Collection

If your research involves certain types of interactions with human beings (e.g., conducting surveys, interviews, focus groups; doing oral histories), you may choose to create an audio or video recording of those interactions. If you do so, you may then chose to “transform” those recordings into text. The process of doing so is called “transcribing.” 

### Why Transcribe?

There are two overarching reasons why you might transcribe the recordings (audio or video) of your interactions with human participants.

You may do so for your own purposes, as in these examples:
-   You plan to use long, exact quotes as evidence in the article or book for which you did the research;
-   You plan to engage in content or discourse analysis and the precise language and wording that your human participants employed are integral to your study;
-   You plan to analyze your data using Computer-Assisted Qualitative Data Analysis Software (CAQDAS), which requires textual inputs.

Alternatively, you may transcribe your audio / video recordings because the data are more accessible to other scholars -- indexable, searchable -- when they are in textual rather than audio or video form. Transcribed data can be more readily [*de-identified*](http://link) than audio or video, further facilitating sharing. Transcripts are thus easier for other scholars to use to evaluate the findings in your written products,
or to pursue their own intellectual objectives.

Transcribing is resource intensive, however, no matter how you go about it. You may wish to consider alternatives to transcribing. For instance,
you might create a “table of contents” of your audio or video recordings, writing a light summary of the content and tenor of the conversation at two or three minute intervals. Alternatively, you might generate a brief summary of the interaction, highlighting particularly important moments or the “juiciest” quotes (noting the hour/minute of the exchange at which each occurred). Of course, none of these alternatives is as rich, accurate, or high-fidelity a data source as a transcript.

### How to Transcribe

If you decide to transcribe your audio or video recordings, you have several choices with regard to how to do so.

#### DIY: Technology-Assisted Transcription

You may decide to transcribe your audio / video recordings yourself. Doing so allows you to remain as close to the data as possible and have maximum control over the resulting product. If you transcribe your recordings, you will likely use some kind of software to assist you. Before deciding to do your own transcriptions, try your hand at transcribing -- perhaps with a free version of the type of technology you would most likely use -- to get a sense of the process, keeping in mind how many exchanges need to be transcribed.

There are three main types of software you might employ:
-   Dictation (“speech to text”) software (such as “Dragon Naturally Speaking”), which allows you to “re-speak” the exchanges from your audio or video recording, leading to a text transcript (the re-speaking is necessary because you train the software to understand your voice and diction)
-   Transcription software, which allows you to upload audio / video recordings onto your computer and play them back (with easy stop / pause functionality) while you simultaneously type what you hear into a text document.
-   Automatic transcription tools [that allow you to post audio or video recordings to a web site that converts them into text.](https://www.poynter.org/tech-tools/2017/the-best-automatic-transcription-tools-for-journalists/)

There are many products of each type. Here are some criteria to keep in mind as you consider different options:
-   Which version of the software / tool has the functionality that you need (the “free trial” or “basic version” may not)?
-   Is the software proficient in the language in your audio / video recordings were made?
-   How much does the version of the software / tool that would be useful for your purposes cost?
-   Does the software work on your computer’s operating system?
-   Does the software / tool import audio / video files in the format in which you have them?
-   In what format is the transcript produced (and can it be transformed into the format that you want it in)?
-   How does the software handle timestamps?

No matter which option you choose, you should establish a set of rules to follow when transcribing. Doing so will make you more efficient (as you will not need to re-consider / re-make decisions), and will help your transcripts to be consistent. These rules might include:
-   A file-naming convention for transcript files (considering how this aligns with the file names of audio and video files)
-   How important it is that the transcript is word-for-word
-   How timestamps will be inserted in the transcripts
-   How who is speaking will be indicated
-   How transcribers should indicate extraneous noise and events (e.g., sighs, sneezes, others entering the space in which the exchange is occurring)
-   How pauses, and unintelligible words and phrases will be indicated

#### Outsourcing Transcription Services

Another option is to outsource transcription. You might formally contract a freelance transcriber or transcription firm; you should identify and talk with a few clients of the firm to make sure that they have done good work and to solicit tips on working with them. Alternatively, you might proceed more informally, hiring one or more individuals, perhaps with specialized knowledge, to assist you. Depending upon whom you choose, your transcribers may serve as “research assistants” to the project, offering useful intellectual input in addition to transcribing. Before hiring transcribers, you should interview several candidates to ensure that they are reliable and detail-oriented and understand the tedious nature of the work.

No matter which option you choose, it will be useful to write and sign a contract outlining the main parameters or your arrangement. (A firm will likely require this; it is a good idea for you to develop a non-legally binding contract when you hire transcribers informally as well.) At a minimum, that contract should detail four items:
-   The estimated size and timeline for the project (including the timing of transcript delivery, with intermediary milestones and a final due date)
-   The process for exchanging files with transcribers
    -   If your recordings of your interactions with human participants include sensitive data, you may want your transcriber(s) to sign a non-disclosure agreement (NDA), and you will need to think of secure ways to transmit the data and resulting transcripts between you and your transcribers.
-   Your rules / instructions for transcribing (as described above)
-   Payment structure -- there are many metrics
    -   You could establish an hourly rate based on number of hours of recorded material, or based on number of hours spent transcribing
    -   You may establish a rate for each page transcribed.
    -   Consider how each option incentivizes your transcribers.

Your transcribers need to understand and be willing to follow your rules. Once they start working, you should check the first few transcriptions carefully to make sure transcribers are adhering to your rules. Thereafter you should give at least a cursory look to each transcription as it is submitted for light quality assurance.

### Documenting Transcriptions

While transcribing audio and video recordings has significant analytic benefits, recordings cannot faithfully reflect any human interaction. There are always unspoken dynamics, facial expressions, hand gestures, and other nuances that are not reflected in recordings. Textual transcripts are then another step removed from the original interaction: intonation, tone, and other details cannot be perfectly reflected in a transcript. While this impoverishing of the data is unavoidable, you can mitigate it by writing excellent documentation, as discussed in the “Documenting Data and Creating Metadata” lesson. Documentation will prove useful both to the “future you” employing these data later in time, and to other scholars who wish to re-use them.

{% include _exercise.html exerciseid="14" %}

### Translating Transcriptions

You may wish to translate your transcripts from the language in which the recorded exchange actually occurred into another language. It may seem inefficient to transcribe your audio recordings first *and then*
translate the transcripts. However, you will generally end up with better transcriptions and translations if the processes are carried out separately. Also, if you are using software to assist you with these transformations, or contracting others to perform these services, most software and services specialize in one or the other service.

Typically you’ll translate into your native language and/or the language in which you’re writing the article or book resulting from the research. You might want to translate because:
-   you had proxies engage in your interactive data collection because you don't speak the language in which the exchange occurred
-   having translations of your transcripts will make them easier for you to use as the evidentiary base for your research product.
-   you want to expand the population of potential secondary users for the fruits of your data-collection efforts if you translate those fruits into an additional language.

Keep in mind that it may not be necessary for you to translate completely all of your transcripts even if you are creating your research products in a different language from your transcripts. If you are fully proficient in the languages in which you conducted data collection, you may be able to interact efficiently with the transcripts -- read, recall, and analyze -- without translating them. Alternatively, you may translate only a subset of the transcripts, or possibly simply translate the excerpts that you ultimately use in your research product. You should proceed in whatever way will allow you to maximize the utility and evidentiary potential of your exchanges with human participants while being mindful of the time translation will take you.

If you do decide to translate a good number of your transcripts, you’ll face choices similar to those associated with transcribing your recorded exchanges. Our suggestions for making those choices, and our recommendations for carrying out the tasks your choices imply, are analogous to those we offered with respect to transcription; we reprise them very briefly here.

If you choose to translate your transcripts yourself, you may choose to employ technology to assist you. You might just use “Google translate” or a similar automated translation service, or other options for technologically assisted translation; you can use the criteria we suggested above to choose among the various possibilities. If you outsource translation to a freelancer or firm, engage in the due-diligence, and write the type of contract, that we suggested in the previous section, and carefully review the initial products from the freelancer or firm to assure quality. No matter which option you choose, you should establish a set of rules to follow when translating, along the lines suggested above.

{% include _exercise.html exerciseid="15" %}

## Further Resources

- University of Illinois Library: Digital Historian Series: Using Digital Tools for Archival Research,
[*https://guides.library.illinois.edu/c.php?g=348155&p=2346513*](https://guides.library.illinois.edu/c.php?g=348155&p=2346513)
- The Best Automatic Transcription Tools for Journalists [*https://www.poynter.org/tech-tools/2017/the-best-automatic-transcription-tools-for-journalists/*](https://www.poynter.org/tech-tools/2017/the-best-automatic-transcription-tools-for-journalists/)
