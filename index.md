---
layout: page
menubar: about_menu
hero_height: is-fullwidth
title: Home
progress:
  total: 183.0
  bars:
  - label: 'corrected outside events'
    num: 30
    color: '#474b24'
  - label: 'completed during events'
    num: 63
    color: '#5fbb97'
    text: black
  - label: 'partially corrected during events'
    num: 10
    color: '#dcf763'
    text: black
  - label: 'remaining'
    striped: true
    color: '#a2a2a3'
    num: 80
---
## About the *Soul of Reason* Collection

{% include inline-figure.html
  img='images/uploads/roscoe-brown-IAAA.jpg'
  width='30%'
  caption='Portrait of Dr. Roscoe C. Brown, Jr.'
  alt='black and white image showing Dr. Roscoe C. Brown, Jr. seated and smiling' %}

The Records of NYU’s Institute for Afro-American (now African American) Affairs (IAAA), housed in NYU's University Archives, contain a series of **well over a hundred recordings of *Soul of Reason***, a half-hour radio show that aired from 1971-1986 on both the commercial radio station WNBC and the University’s radio station, WNYU.

The show’s host, **Dr. Roscoe C. Brown, Jr.**, was Director of the IAAA at the time. *Soul of Reason* showcased unique and vital conversations with leaders, politicians, writers, activists, and artists of African descent in New York City during the civil rights and Black Power and Arts movements that spanned nearly two decades. The program’s mission, according to its founding documents, was to be

> "a showcase for Black scholarship...
> to examine the foundations of African-American thought from a variety of areas.”[^1]


*Soul of Reason* covered theater, film, music, art, business, literature, publishing, sports, academia, community programs, social programs, law, dentistry, mental health, and politics, with a focus on African American, Puerto Rican, and African communities. Additionally, participants on the show discuss organizations such as the Harlem Writers Guild, Black Theater Alliance, La MaMa Experimental Theatre Club, and the Nuyorican Poets Cafe; social initiatives including the Congress on Racial Equality, or CORE; and seminal works of literature and theater.

## About the Project

### Background
The *Soul of Reason* recordings have already been digitized and uploaded to NYU Libraries’ preservation repository. This preservation was inspired by Tanisha Jones' 2003 NYU Moving Image and Preservation (MIAP) Masters thesis, *Getting to the soul of Soul of Reason: A Case for Preservation*. Streaming copies of most of the audio files are embedded in the online description of the collection, available [via digital library finding aid](http://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424). NYU’s Digital Library Technology Services (DLTS) has begun automated audio captioning and transcription using services from [Konch AI](https://www.konch.ai/), a company with both Web interface and APIs and tools for automation.

### Plan
Thanks to a [Digital Humanities Seed Grant](https://nyuhumanities.org/funded-activities/digital-humanities-seed-grant/) from the [NYU Center for the Humanities](https://nyuhumanities.org/) and the support of [DS3](https://cds.nyu.edu/ds3/) at the [NYU Center for Data Science](https://cds.nyu.edu/), we will be able to move beyond the important digitization and preservation work we have done and begin working collaboratively with researchers to shape their use of the **_Soul of Reason_ collection as data**. We’ll do this primarily by holding a series of community engagement events that will help us connect with interested scholars, collaboratively create and curate data, and jointly develop their research questions and methods.

Our DH Seed Grant funding will support a graduate student digital humanities project using this material, and DS3 funding and guidance will support a data science graduate student’s work with tools and workflows for applying natural language processing (NLP), named entity recognition (NER), and/or topic modeling to the transcripts.

### Progress

So far, we have hosted two [community transcription events]({{ '/events' | absolute_url }}) in July and October of 2020. In total, 41 volunteers contributed their time and expertise to correcting 63+ collection transcripts, which represent roughly 32 hours of recordings!

__Total transcripts:__ {{ page.progress.total | round }}  
{% include progress.html progress=page.progress %}

We also worked with Nyla Ennels (Junior Data Scientist, NYU Data Science and Software Services) to extract entities from the transcripts. You can read more about her work [here]({{ 'updates/creating-a-named-entity-recognition-pipeline/' | absolute_url }}).


----

[^1]: Historical note, Records of the Institute of Afro-American Affairs; RG 9.8; New York University Archives, New York University Libraries, [http://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424](http://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424)
