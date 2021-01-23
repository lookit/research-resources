The researcher running an individual study supplies the text in brackets, to be substituted into a standard template. At the top of the form is a link to download a copy of the form. The fields starting `study.` are taken directly from the study definition, rather than being defined in the consent frame.

This shows the content of template 5 if `prompt_only_adults` is set to `true` - some language is changed slightly to accommodate a single adult participant.

# Consent to participate in research: [`study.name`]

Researchers led by [`PIName`] at [`institution`] are running this study, "[`study.name`]," on Lookit. [`summary_statement`: optional overview - please leave this blank unless your IRB specifically requires something to be at the very top of the form]

## Why we are running this study [or custom `purpose_header`]

[`purpose`: brief description of purpose of study]

## What happens during this study [or custom `procedures_header`]

This study takes about [`study.duration`] to complete. [`procedures`: brief description of study procedures. Do not include duration or risk information here.]

## Participation is voluntary [or custom `participation_header`]

You are free to choose whether to be in this study. If you do choose to participate, it's okay to stop at any point during the session.

[`voluntary_participation`: Optional: any additional information about voluntary nature of participation, e.g. "There are two sessions in this study; you will be invited to complete another session next month. It is okay not to do both sessions!"]

## What are the risks? [or custom `risk_header`]

[`risk_statement`: brief statement of any risks to participation, or a statement that there are no expected risks. This section is omitted if no `risk_statement` is provided.]

## What are the benefits? [or custom `benefits_header`]

[`payment`: statement about any payment or other compensation AND any other benefits, including a statement that there are no additional benefits anticipated to the participant. Information about compensation should include (a) any conditions (e.g. child needing to be in the age range and visible at some point, compensation only once per child), (b) the expected timeframe for receiving compensation, and (c) a statement that 
compensation does not depend on finishing the whole study.]

## Data collection and webcam recording

During the session, you will be recorded by your computer's webcam and microphone. These webcam recordings, and other data like answers you enter in forms, are sent securely to the Lookit platform. You can view your past recordings on Lookit under "Studies" -> "Your past studies" at any time.

Data are stored securely on Lookit servers and by researchers, and are only shared as described in this document. However, there is always a small risk that data transmitted over the internet may be intercepted or that the security of stored data may be compromised.
    
## Who will be able to see your webcam recordings?

We will first check that you really agreed to participate by watching your consent recording. If we cannot confirm that you agreed to participate, no one will view any other recordings from this session.

At the end of the session, you will choose a privacy level for your webcam recordings. You can choose one of the following privacy levels for your videos:

* "Private": Researchers with access to your recordings will not share them with anyone else.
* "Scientific": Researchers with access to your recordings may share them for scientific or educational purposes, for instance showing an example in a class or during a scientific conference.
* "Publicity": Researchers with access to your recordings may also share them for publicity, for instance in a news segment about the research or to recruit more participants.

You will also have the option to withdraw your recordings. If you do, only your consent recording will be kept and all other recordings will be deleted.
   
[Optional paragraph, if `include_databrary` is true:] Separately, you can opt in to give access to your recordings and other data to authorized users of the secure data library Databrary. This means that other researchers besides the ones running this study will
have access to your recordings, and may be able to use them to answer other questions about child development. Data sharing can lead to faster progress in research on human development and behavior. Authorized Databrary researchers have to agree to maintain confidentiality and not use the data for commercial purposes.  If you have any questions about this data-sharing library, visit [Databrary](https://nyu.databrary.org/) or email ethics@databrary.org.
       
[`additional_video_privacy_statement`: Optional: any additional information about webcam recording sharing. For cases where researchers ask for other specific permission to share videos, separate from the exit survey, or want to provide more detail or different language about Databrary sharing.]

## How we use your data

If you participate in this study, we (the research group led by {{PIName}} at {{institution}}) will have access to:

* webcam recordings and other data collected during this session
* your account profile and demographic survey
* the profile for the family member who is participating

This includes changes you make in the future to any of this information. We may put different types of information together to learn more about child development. For instance, if you participate in multiple studies from our group, we may look at how your responses compare across studies, or we may look at how your responses relate to other family members'. We may also study connections between your responses and family demographic survey data.

[`datause`: Optional study-specific data use statement. You may want to note what measures you will generally be coding for (looking time, parent-child interaction, etc.). If your IRB prefers, you can also note here that you are subject to the Lookit Terms of Use.]

## How Lookit uses your data

The Lookit core team at MIT will also have access to the data collected during this session, in addition to your account data. They use this data to run and improve Lookit, for instance to provide technical support, check how well data collection is working, or see whether Lookit is reaching a diverse group of families. Lookit stores data indefinitely unless you withdraw your recordings at the end of the study.

## Publishing the results of this study

The results of this study may be presented at scientific meetings or published in scientific journals. We may publish individual responses that cannot identify you, like looking times or sequences of button presses. We never publish birthdates or names. Even if you choose to share your recordings, we never publish information that would make it possible to link recordings with your demographic data.
    
## [Any additional segments here]

if `additional_segments` is provided, each element of that list will be included under its own heading here.

## Your rights as a participant

[`research_rights_statement`: Statement of rights of research subjects, e.g. including IRB contact info]

## General Data Protection Regulation (GDPR) information [optional section, included if `gdpr` is true]

As part of your participation, we will collect certain personal information about you, including: [`gdpr_personal_data`: list of types of personal information]. In addition, we will collect special category data, your personal information that is especially sensitive: [`gdpr_sensitive_data`: list of types of sensitive personal information]

Your personal information will be transferred to the United States. The data protection and privacy laws of the United States may not offer you the same level of protection as those in your country of origin.

## How to reach us
This study is run by [`PIName`] at [`institution`]. If you have any questions or concerns about this study, or in the very unlikely event of a research-related injury, please contact [`PIContact`]. 

If you have any questions or concerns about the Lookit platform, please contact Kim Scott at lookit@mit.edu.

---

To participate, a participant presses "Start consent recording" reads the statement below out loud (or in ASL):
"I have read and understand the consent document. I agree to participate in this study."
