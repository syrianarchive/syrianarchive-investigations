---
layout: contentwithsiblings.html
title: Metadata schema
date: 2017-11-27
desc: Metadata Schema
image: /assets/technology/metadata-2.png
---

This page describes the metadata schema used by the Syrian Archive in it's digital content preservation, verification and investigative activities. The Syrian Archive recognised the need for a standardised metadata scheme for organising content, but also that any metadata scheme used would be a highly political choice. Given that there are no universally accepted legally admissible metadata standards as of the date of this publication, efforts were made to develop a framework in consultation with a variety of international investigative bodies. Among these include consultations with members of the International Criminal Court, with members of the United Nations Office for High Commissioner of Human Rights, with members of the International, Impartial and Independent Mechanism on international crimes committed in Syria (IIIM), with archival institutes like the NIOD Institute for War, Holocaust and Genocide Studies, with international human rights organisations like Amnesty International, Human Rights Watch, and Witness, and with research institutes like the Human Rights Center at UC Berkeley School of Law.

Establishing a standardised metadata schema is necessary in order to assist users in identifying and understanding when, where, and what happened in a specific incident. A review of practices by other war archival institutes, such as those of NIOD, found that additional information is helpful for contextualising raw visual evidence (e.g. location of video recording; date of video recording and upload; and the origin of the video). Metadata collected by the Syrian Archive project includes description of the visual object as given (e.g. Youtube title); the source of the visual evidence; the original link where footage was first published; specific landmarks able to be identified; weather (which may be useful for geolocation or time identification); specific languages or regional dialects spoken; clothes or uniforms able to be identified; weapons or munitions used; device used to record the footage; and media content type. The metadata is populated automatically and manually depending on how it was collected from e.g open source or closed source.

In categorising violations, the Syrian Archive has decided to use the violations categories used by the Office of United Nations High Commissioner for Human Rights (OHCHR). This was done because OHCHR is one of the groups in the unique position of being able to investigate incidents of human rights violations and war crimes. These categories consist of many often overlapping categories. Should potential investigations by international bodies not be pursued by the UN OHCHR and rather by another investigative body, it is anticipated that the Syrian Archive will modify violations categories to meet the needs of those investigating.

Various fields of the metadata schema are processed at various stages of the digital evidence workflow (e.g. collection, preservation, processing, verification, publication, analysis).

<div class="pagebody">
                <table>
  <tbody><tr>
    <td><b>Field Description</b></td>
    <td><b>Workflow</b></td>
    <td><b>Field Type</b></td>
    <td><b>Population Method</b></td>
    <td><b>Purpose</b></td>
  </tr>
  <tr>
    <td>Reference Code</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To uniquely identify the item</td>
  </tr>
  <tr>
    <td>Upload Date</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>DATE</td>
    <td>Automated</td>
    <td>To identify the upload of the content  to social media platforms YYYY-MM-DD format.</td>
  </tr>
  <tr>
  <td>Incident Date</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>TEXT</td>
    <td>Manual</td>
    <td>To identify the date of the incident YYYY-MM-DD format.</td>
  </tr>
  <tr>
  <td>Incident time</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To identify the time of the incident</td>
  </tr>
  <tr>
  <td>Creator</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>TEXT</td>
    <td>Manual</td>
    <td>To identify the creator (or creators) of the item using standard names. Maintain directory of standard names to ensure consistency.  </td>
  </tr>
  <tr>
   <td>Acquired from</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To identify the online account that uploaded the content using standard names. Maintain directory of standard names to ensure consistency</td>
  </tr>
  <tr>
   <td>File Name</td>
    <td>COLLECTION,
            PRESERVATION,
            PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>The directory or location of the downloaded or acquired content on the storage servers</td>
  </tr>
  <tr>
   <td>Location</td>
    <td>VERIFICATION</td>
    <td>TAG</td>
    <td>Manual</td>
    <td>To identify where the item was captured as specifically as possible using format province (city), town, district. We maintain directory of Syrian locations including standard transliterations of place names to ensure consistency.</td>
  </tr>
  <tr>
   <td>Coordinates</td>
    <td>VERIFICATION</td>
    <td>TAG</td>
    <td>Manual</td>
    <td>To identify where the item was captured using the exact coordinates if available (Latitude, Longitude)</td>
  </tr>
  <tr>
   <td>Summary</td>
    <td>VERIFICATION</td>
    <td>MEMO</td>
    <td>Manual</td>
    <td>Free text describing what is happening in the video/picture/recording, who is depicted, why it was recorded so it enables the verification team and reviewers to judge the potential relevance of the item.</td>
  </tr>
  <tr>
   <td>Generation</td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if the file is the original or a copy</td>
  </tr>
  <tr>
   <td>Existence of original</td>
    <td>VERIFICATION</td>
    <td>MEMO</td>
    <td>Manual</td>
    <td>To indicate if the Syrian Archive knows of where and who has the original copy of the file.</td>
  </tr>
  <tr>
   <td>Edited?</td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if the item has been edited from a longer version</td>
  </tr>
  <tr>
   <td>Is this footage online? </td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if there is an online copy of the item or not.</td>
  </tr>
  <tr>
   <td>Online title</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To indicate what the online copy is called while the original is kept archived.</td>
  </tr>
  <tr>
   <td>Online link</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To indicate what the original link URL of the online copy</td>
  </tr>
  <tr>
   <td>Online description</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To indicate the original description of the online copy. e.g: YouTube video description. </td>
  </tr>
  <tr>
   <td>Uploader ID</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To indicate what the online ID for the content uploader. It’s the "channel_id" in the case of YouTube. </td>
  </tr>
  <tr>
   <td>View count</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To indicate the number of views the online item has when was collected. For example: How many views this video has got since it was uploaded and then preserved by the Syrian Archive</td>
  </tr>
   <tr>
   <td>File Size</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>FLOAT</td>
    <td>Automated</td>
    <td>To identify the size of the item in KB</td>
  </tr>
  <tr>
   <td>Duration</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To identify the duration of the item using format hh:mm:ss</td>
  </tr>
  <tr>
   <td>Date of Acquisition</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>DATE</td>
    <td>Automated</td>
    <td>To identify the date of acquisition of the item using YYYY-MM-DD format</td>
  </tr>
  <tr>
   <td>Chain of Custody Notes</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>MEMO</td>
    <td>Manual</td>
    <td>Free text to provide information on the history of the item that is significant for its authenticity, integrity and interpretation</td>
  </tr>
  <tr>
   <td>Date of fixity check</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>DATE</td>
    <td>Automated</td>
    <td>The date of MD5 hash value creation using YYYY-MM-DD format</td>
  </tr>
  <tr>
   <td>MD5 hash value</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>TEXT</td>
    <td>Automated</td>
    <td>To enable checks to ensure the file is intact and unaltered since last fixity check.</td>
  </tr>
  <tr>
   <td>Content Type</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>PICK</td>
    <td>Automated</td>
    <td>To identify the genre of the item using DCMI TYPE vocabulary. e.g. Image, sound, text.</td>
  </tr>
  <tr>
   <td>Language(s)</td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To identify the language(s), script(s) and symbol systems employed in the item. Include the appropriate ISO codes for language(s) (ISO 639-1, ISO 639-2 and ISO 15924)</td>
  </tr>
  <tr>
   <td>Finding Aids</td>
    <td>ANALYSIS</td>
    <td>TEXT</td>
    <td>Manual</td>
    <td>To give information about any finding aids to the item (e.g. Contents list, transcripts etc.)</td>
  </tr>
  <tr>
   <td>Is there graphic content?</td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate violent or gruesome content in the item.</td>
  </tr>
  <tr>
   <td>Security  Restriction Status</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if there are any restrictions on access to the item because of security concerns. e.g. uncovered faces of activists at risk</td>
  </tr>
  <tr>
   <td>Rights owner</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>DATE</td>
    <td>Automated</td>
    <td>To indicate who holds the rights over the item (Usually the creator)</td>
  </tr>
  <tr>
   <td>Rights declaration</td>
    <td>COLLECTION, PRESERVATION,
PROCESSING</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>Has the owner given consent to the use of their work?</td>
  </tr>
  <tr>
   <td>Creator willing to be a witness in case footage is used as evidence for a legal case?</td>
    <td>PROCESSING</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if the creator is willing to cooperate with human rights investigators and lawyers in the future</td>
  </tr>
  <tr>
   <td>Relevant?</td>
    <td>PROCESSING</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if the visual evidence is useful to be verified by the Syrian Archive team</td>
  </tr>
  <tr>
   <td>Verified? </td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if the visual evidence has been verified by the Syrian Archive team</td>
  </tr>
  <tr>
   <td>Public?</td>
    <td>PUBLICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate if the visual evidence is publicly available on the Syrian Archive database. </td>
  </tr>  
   <tr>
   <td>Priority</td>
    <td>ANALYSIS</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate the priority of the footage based on the information the Syrian Archive have about the incident as well as other Syrian human rights organisations.</td>
  </tr>  <tr>
   <td>Keywords</td>
    <td>ANALYSIS</td>
    <td>TAG</td>
    <td>Manual</td>
    <td>Keywords and tags to help in content searches</td>
  </tr>  <tr>
   <td>Notes</td>
    <td>ANALYSIS</td>
    <td>MEMO</td>
    <td>Manual</td>
    <td>To provide information that cannot be accommodated in any of the other areas</td>
  </tr>  <tr>
   <td>Device used</td>
   <td>COLLECTION, PRESERVATION,
PROCESSING
</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>What kind of device used to record the incident?</td>
  </tr>  <tr>
   <td>Weapons used</td>
    <td>ANALYSIS</td>
    <td>TAG</td>
    <td>Manual</td>
    <td>What kind of weapon used in the video?</td>
  </tr>  <tr>
   <td>Landmarks</td>
    <td>ANALYSIS</td>
    <td>TAG</td>
    <td>Manual</td>
    <td>To indicate if landmarks that help geolocate an item such as schools, churches, mosques, bridges, stadiums, etc</td>
  </tr>  <tr>
   <td>Weather</td>
    <td>VERIFICATION</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>Condition of the weather in the date when the video was recorded.</td>
  </tr>  <tr>
   <td>Type of violation</td>
    <td>ANALYSIS</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To indicate the type of violation after verifying the footage. The Syrian Archive uses the categories identified by the UN OHCHR Inquiry on Syria and used by the Syrian Archive project include: &nbsp;
    <li>Massacres and other unlawful killing;</li>
    <li>Arbitrary arrest and unlawful detention;</li>
    <li>Hostage-taking;</li>
    <li>Enforced disappearance;</li>
    <li>Torture and ill-treatment of detainees;</li>
    <li>Sexual and gender-based violence;</li>
    <li>Violations of children’s rights;</li>
    <li>Unlawful attacks;</li>
    <li>Violations against specifically protected persons and objects;</li>
    <li>Use of illegal weapons;</li>
    <li>Sieges and violations of economic, social and cultural rights;</li>
    <li>Arbitrary and forcible displacement.</li>
</td>
  </tr>  <tr>
   <td>Collection</td>
    <td>ANALYSIS</td>
    <td>TAG</td>
    <td>Manual</td>
    <td>To indicate the collection after verifying the footage. Collections include:
    <li>Attacks against hospitals;</li>
    <li>Attacks against schools;</li>
    <li>Attacks against bakeries;</li>
    <li>Attacks against journalists;</li>
    <li>Attacks against markets;</li>
    <li>Attacks against cultural property;</li>
    <li>Attacks against mosques;</li>
    <li>Attacks against civilians;</li>
    <li>Attacks against water sources;</li>
    <li>Attacks against humanitarian relief personnel and objects</li>
    <li>Civilian casualties as a result of alleged Russian attacks;</li>
    <li>Civilian casualties as a result of alleged coalition attacks</li>
    <li>Civilian casualties as a result of alleged attacks by armed groups</li>
    <li>Civilian casualties as a result of alleged attacks by Syrian government forces</li>
    <li>Civilian casualties as a result of alleged attacks by pro-Syrian government forces</li>
    <li>Plunder and theft</li>
    <li>Coalition airstrikes in Syria</li>
    <li>Russian airstrikes in Syria</li>
    <li>Other</li>
</td>
  </tr>
<tr>
   <td>Armed group</td>
    <td>ANALYSIS</td>
    <td>PICK</td>
    <td>Manual</td>
    <td>To provide the name of the armed group that is shown in the video or reported to be responsible for committing human rights violations in Syria</td>
  </tr>
</tbody></table>



<style>
table {
    font-family: arial, sans-serif;
    border-collapse: collapse;
    width: 100%;
}

td {
    border: 1px solid #dddddd;
    text-align: left;
    padding: 0.9rem;
}

td:nth-child(1) { background: hsl(0, 0%, 68%); }
td:nth-child(2) { background: hsl(0, 0%, 70%); }
td:nth-child(3) { background: hsl(0, 0%, 70%); }
td:nth-child(4) { background: hsl(0, 0%, 70%); }
td:nth-child(5) { background: hsl(0, 0%, 80%); }

}

tr:nth-child(even) {
    background-color: #dddddd;
}
</style>
            </div>
