---
layout: default
progress:
  total: 183.0
  bars:
  - label: 'corrected outside event'
    num: 30
    color: '#00EDB2'
  - label: 'completed during event'
    num: 28
    color: '#FCA17D'
  - label: 'partially corrected during event'
    num: 11
    color: '#e3c19f'
  - label: 'remaining'
    striped: true
    color: '#a2a2a3'
    num: 125
---
## About the *Soul of Reason* Collection

<figure style="width:30%;float:left;margin: 0 30px 10px 0">
  <img alt="Portrait of Dr. Roscoe C. Brown, Jr." src="{{ 'assets/roscoe-brown-IAAA.jpg' | absolute_url }}" width="100%"/>
  <figcaption style="margin: 0px;font-size:.8rem">Portrait of Dr. Roscoe C. Brown, Jr.</figcaption>
</figure>

The Records of NYU’s Institute for Afro-American (now African American) Affairs (IAAA), housed in NYU's University Archives, contain a series of **266 recordings of *Soul of Reason***, a half-hour radio show that aired from 1971-1986 on both the commercial radio station WNBC and the University’s radio station, WNYU.

The show’s host, **Dr. Roscoe C. Brown, Jr.**, was Director of the IAAA at the time. *Soul of Reason* showcased unique and vital conversations with leaders, politicians, writers, activists, and artists of African descent in New York City during the civil rights and Black Power and Arts movements that spanned nearly two decades. The program’s mission, according to its founding documents, was to be

> "a showcase for Black scholarship...
> to examine the foundations of African-American thought from a variety of areas.”[^1]


*Soul of Reason* covered theater, film, music, art, business, literature, publishing, sports, academia, community programs, social programs, law, dentistry, mental health, and politics, with a focus on African American, Puerto Rican, and African communities. Additionally, participants on the show discuss organizations such as the Harlem Writers Guild, Black Theater Alliance, La MaMa Experimental Theatre Club, and the Nuyorican Poets Cafe; social initiatives including the Congress on Racial Equality, or CORE; and seminal works of literature and theater.

## About the Project

### Background
The *Soul of Reason* recordings have already been digitized and uploaded to NYU Libraries’ preservation repository. Streaming copies of most of the audio files are embedded in the online description of the collection, available [via digital library finding aid](http://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424). NYU’s Digital Library Technology Services (DLTS) has begun automated audio captioning and transcription using services from [Konch AI](https://www.konch.ai/), a company with both Web interface and APIs and tools for automation.

### Upcoming
Thanks to a [Digital Humanities Seed Grant](https://nyuhumanities.org/funded-activities/digital-humanities-seed-grant/) from the [NYU Center for the Humanities](https://nyuhumanities.org/) and the support of [DS3](https://cds.nyu.edu/ds3/) at the [NYU Center for Data Science](https://cds.nyu.edu/), we will be able to move beyond the important digitization and preservation work we have done and begin working collaboratively with researchers to shape their use of the **_Soul of Reason_ collection as data**. We’ll do this primarily by holding a series of community engagement events that will help us connect with interested scholars, collaboratively create and curate data, and jointly develop their research questions and methods.

Our DH Seed Grant funding will support a graduate student digital humanities project using this material, and DS3 funding and guidance will support a data science graduate student’s work with tools and workflows for applying natural language processing (NLP), named entity recognition (NER), and/or topic modeling to the transcripts.

### Progress

So far, we have hosted one [community transcription event]({% link virtual-transcription-events.md %}) that spanned 4 days in July 2020. In total, 37 volunteers contributed their time and expertise to correcting 28+ collection transcripts, which represent roughly 14 hours of recordings!

__Total transcripts:__ {{ page.progress.total | round }}

{% include progress.html progress=page.progress %}

## Project Team

(In alphabetical order)

**Janet Bunde**  
University Archivist, NYU Special Collections  

**Zach Coble**  
Head, Digital Scholarship Services  

**Steven G. Fullwood**  
Project Director of the Center for Black Visual Culture, Institute for African American Affairs  

**Carol Kassel**  
Senior Manager, Digital Library Infrastructure, Digital Library Technology Services  

**Don Mennerich**  
Digital Archivist, Digital Library Technology Services and Archival Collections Management

**Marii Nyrop**  
Digital Humanities Technology Specialist, Digital Scholarship Services

**Alexandra Provo**  
Metadata Librarian, Knowledge Access & Resource Management Services (KARMS)

**Michael Stasiak**  
Digital Content Manager, Digital Library Technology Services

**Jasmine Sykes-Kunk**  
Reference Associate, NYU Special Collections

**Kimberly Tarr**  
Media Preservation Unit Head, Barbara Goldsmith Preservation & Conservation Department

**Deb Verhoff**  
Digital Collections Manager, Digital Library Technology Services  

**Deborah Willis**  
University Professor and Chair of the Department of Photography & Imaging at the Tisch School of the Arts and Director, Institute for African American Affairs   

## Contact

Get in touch by emailing us at **{{ site.email }}**.


<br>
<br>
<br>
<br>

----

[^1]: Historical note, Records of the Institute of Afro-American Affairs; RG 9.8; New York University Archives, New York University Libraries, [http://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424](http://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424)
