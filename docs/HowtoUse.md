---
layout: default
title: How to Use AVAnnotate
nav_order: 2
has_children: true
---

This guide walks you through what you need to build an AVAnnotate project for your research or teaching. These features--tags, annotations, and events--are the base-level components of an AVAnnotate project, and will help you begin marking up your audio and visual artifacts. 

# **Events**
## [AVAnnotate_Event_Template.xlsx]
This template organizes the events in a project and associates the AV files with that event. An “event” might be an interview, an oral history, a performance, a speech, a reading, or a conference that takes place over multiple days. (This list is not exhaustive, and the audiovisual material you’re working with may or may not fall into one of these “event” categories.)   
Each row in the Event template corresponds to one recording, though events can span multiple rows (e.g., the event “Interview 2” may be found on Tapes 2 and 3, so “Interview 2” will appear in two separate rows in the template). 

Remember: 
If an event is associated with one AV file (audio or video), it will occupy one line on the spreadsheet. 
If an event has been recorded over multiple AV files (and you’re intending to include them in your AVAnnotate project), the event should appear in multiple lines of the spreadsheet. 

**Header**
Column A: Event Label (“Interview 1”)

Column B: Event Item Type (“Audio” or “Video”) 

Column C: AV File Label (name for the file; create a name even if there is not an AV URL)

Column D: AV File URL (optional)

Column E: Event Citation (optional)

Column F: Event Description (optional) 



# **Annotations**
## [AVAnnotate_Event_Annotation_Template.xlsx]
This template includes project annotations. Annotations correspond to a given start and end point in the audio or visual artifact, and contain information about the media. The nature of this information is entirely up to the user. For example, annotations might include a transcript; captions; information about formal features of the media, like shot sequence, volume, or lighting; historical or cultural context; environmental noises such as fans or car horns; or conceptual notes or themes. 
Annotations are linked to an event as part of the upload process. 

**Note:** Annotations may overlap in time and will appear in sequence in the interface according to the earliest start time.

Column A: Start Time (annotation’s start time in minutes and seconds)

Column B: End Time (annotation’s end time, may be the same as start time for a point in time)

Column C: Annotation (transcription, notes on environmental sounds, formal features, etc.)

Column D: Tags (comma separated; if a tag belongs to multiple categories, the category is included “category: tag”)

Column E: AV Label (optional if there is only one AV recording; mandatory if there is more than one AV recording) 

# **Tag** 
## [AVAnnotate_Tag_Template.xlsx]
This template contains tags and tag categories used in a project. Tags are labels used in the interface to index, organize, and discover topics in the annotations. Categories can be used to organize the tags in groups. For instance, tags might contain the names of speakers featured on the recording(s), which could be organized via the category “speaker.” This would allow end users to easily find all annotations that relate to a given speaker or all speakers. 
Tags could also be used to organize concepts, themes, or features that appear across several recordings (e.g., “Shouting” as a tag and “Tone of Voice” as a category). Consistency with the spelling and capitalization of tags is imperative, as AVAnnotate will read each tag individually and cannot control for differences in case or spelling. 

Note: A tag can belong to multiple categories. For example, the tag “Zora Neale Hurston” may be found in the categories “Speaker” and “Topic” (depending on the event context) or may not be categorized at all. 

Column A: Tag (one tag per cell) 

Column B: Category 


