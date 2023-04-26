---
layout: update
title: Creating a Digital History Project Using OHMS for <i>Soul of Reason</i>
author: jubilee
date: 2021-09-01
hero_sub: Project Updates
hero_height: is-fullwidth
show_sidebar: false
img: 'images/uploads/ohms-screenshot.png'
abstract: Tasked with creating a digital project using the Soul of Reason collection, I was excited to explore the diverse and interesting range of ways that other scholars have incorporated audio ...
---
<br>

{% include inline-figure.html
img='images/uploads/ohms-screenshot.png'
width='40%'
caption='Project screenshot with OHMS viewer.' %}

Tasked with creating a digital project using the *[Soul of Reason]({{ '/' | absolute_url }})* collection, I was excited to explore the diverse and interesting range of ways that other scholars have incorporated audio either as a component of their work or as a primary source in their research. Early into my survey I stumbled across the [Goin’ North: Stories from the Great Migration to Philadelphia](https://www.goinnorth.org) project, which blends oral history interviews and biographical and archival materials to explore the experiences of Black migrants to Philadelphia during the Great Migration.

I had already identified some Soul of Reason episodes that might yield compelling digital projects, and was particularly interested in [two episodes about Gateway National Recreation Area](https://jubilee.hosting.nyu.edu/omeka/episodes). Inspired by the Goin’ North project, I decided to use [OHMS (Oral History Metadata Synchronizer)](https://www.oralhistoryonline.org) to transcribe, synchronize, and index these episodes, which would allow researchers and other users to easily access and search the contents of the interviews. I also wanted to dive deeper into the topics discussed in the episodes themselves, providing immediate context and nuance by linking to informational articles directly in the index.

In order to do this, I first signed up for an OHMS repository and imported the necessary audio file links (ending in audio or video file extensions), hosted through [NYU Special Collections](https://dlib.nyu.edu/findingaids/html/archives/iaaa/dscaspace_ref3702.html#aspace_ref4424). The [“Raising the Volume”]({{ '/people' | absolute_url }}) team had already worked, in collaboration with [Konch AI](https://www.konch.ai) and through community Transcribe-a-Thons, to transcribe the episodes, so I simply corrected and formatted those existing documents. Within the OHMS repository, I followed the instructions of the [OHMS user guide](https://www.oralhistoryonline.org/wp-content/uploads/2020/11/@OHMS_user_guide_master_v3-8-3.pdf) and synchronized the transcripts to the audio, then indexed the episodes according to the Louie B. Nunn Center for Oral History’s [Level 3 approach](https://www.youtube.com/watch?v=yImE3m1zSf8) to indexing oral history interviews. This Level 3 approach, the most detailed version, allows users in-depth search options and also features the opportunity to link to outside sites within the OHMS Viewer interface.

At this stage, I also identified and researched eight areas of discussion in the interviews that I thought merited additional context or explanation, including discussion of the [Youth Conservation Corps](https://jubilee.hosting.nyu.edu/omeka/link7) and [Sandy Ground’s Black oystering community](https://jubilee.hosting.nyu.edu/omeka/link5). In order to link to articles on these topics within the index, I created an Omeka site on a Reclaim Hosting server using Installatron. (I chose Omeka because the team behind OHMS has already developed a [suite of plugins and themes to integrate OHMS with Omeka](https://www.oralhistoryonline.org/documentation/omeka/) and ensure that the OHMS Viewer interface would populate correctly on the Omeka webpage.) I used the Omeka plugin Simple Pages to create eight web pages that I would later populate with articles; in the meantime, I inserted these links into the index.

Once I had finished the indexing process, I returned to the cPanel on Reclaim Hosting and installed the OHMS Viewer using Installatron. After using the provided documentation to configure the Omeka [theme](https://www.oralhistoryonline.org/wp-content/uploads/2018/07/Philly-Theme-Documentation_v1.0.pdf) and [plugins](https://www.oralhistoryonline.org/wp-content/uploads/2018/07/OHMS-Plugin-Suite_v1-1-1.pdf), I used the OHMS Import plugin to import the episode indexes as zipped XML files. Then I completed and corrected the accompanying metadata as appropriate. Importantly, it’s necessary to fill out the OHMS Object field in the “Item Type Metadata” tab by linking to the XML file housed within the OHMS Viewer. To create this link, I used a File Transfer Protocol (FTP) to upload the non-zipped XML file versions of the indexes to the OHMS Viewer cache, and then constructed a link in [the correct format](https://www.oralhistoryonline.org/installing-the-ohms-viewer-on-a-third-party-webhost/) to enter into the OHMS object field.

Once the integration was complete, I continued using Omeka’s Simple Pages plugin to construct the website, including an introduction and about page. Then I finished the drafts of my explanatory articles and uploaded them to the Omeka site. The result is a [website](https://jubilee.hosting.nyu.edu/omeka/) where users can access and search through the Soul of Reason episodes about Gateway Recreation Area while also navigating directly from the OHMS Viewer to learn more about some of the topics the guests on the program discuss.

On the whole, this experience taught me a lot about the technical side of oral history work and about the challenges and possibilities of platforms like OHMS and Omeka. I became much more comfortable working on the back-end of digital projects and also enjoyed the satisfaction of seeing my work come to fruition in the form of the finished project website. I’m very grateful for the “Raising the Volume” team for giving me the opportunity to further these skills.
