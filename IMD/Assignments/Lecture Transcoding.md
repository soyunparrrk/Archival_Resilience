# [Lecture] Transcoding

Created: Mar 16, 2020 10:32 AM

IMD & Coding semester 2 assignment — Martijn de Heer & Hannes Bernard

# Briefing

Research, design and develop a long-term archival solution for a single digital cultural commodity. This requires both resilient hardware and software, digital tools and analogue strategies. Select one artefact from the physical archives of the IISG archive which you will be working with to transcode.

During this project the process, research and documentation on the artefact, the transcoding tool(s) and topics will have to be logged in **[Markdown](https://www.markdownguide.org/basic-syntax)** (a lightweight markup language with plain text formatting syntax). This document will function as the repository for all the work and all Markdown documents will be eventually compiled into one big collective repository of transcoding tools and research on how to create resilient archives.

# Transcoding Definitions

## ⚙️ **Technical Definition**

Transcoding is the direct conversion of one encoding to another, such as with image files (PNG/JPG) or movie files (MP4/MOV). This is usually done for maintaining file support, when the target environment has limited storage capacity that mandates a reduced file size or converting incompatible or obsolete data to a better-supported format.

**Input, process and target format**

Transcoding is a two-step process in which the original data is decoded to an intermediate uncompressed format, which is then encoded into the target format. Simply described as having some input data which is being processed and then outputted to the target format.

**Process of Transcoding**
**Input** (original data)**→Decoded** (intermediate) **→Encoded** (target format) **=** **Transcoding** 

All three variables **input, process** and **target** **format** are important to do research on in relation to your artefact, its topic and your concept. How do you capture your artefact, what is the input for your transcoding tool? A video feed, set of images or spoken word can all be types of input depending on how you want to archive the artefact.

The **target format** (the format that is archived and will represent the artefact in your archive) is what will determine your process: the process of transcoding your **input** to the **target format**. The target format should be a format that creates a resilient archive. How, what or why your artefact and its cultural meaning and message has a long-term archival potential. 

The process where the actual transcoding happens will depend on the type of input and the type of target format. You will explore different strategies of processing and reflect on the results during the assignment. 

## 🖼 Transcoding in Art & Culture

In the context of art & culture the scope of 'transcoding' is broader than only technical processes, formats, hardware systems or software. The transition from one encoding to another can have a huge effect on fundamental aspects of an artwork or cultural artefact, for example:

⚬ **meaning** (what is interpreted or communicated by target format vs input)
⚬ **experience** (how target format is read or how it engages with viewer, user or audience)
⚬ **context** (the milieu in which the input format is encountered vs target format) 
⚬ **mediation** (artefact in relation to the other works, concepts, histories surrounding it)
⚬ **aesthetic & framing** (how formal aspects change in transcoding: think of colour, texture, scale)

What does the process of transcoding do to something we look at?
What are the benefits, sacrifices or limitations when transcoding from one format, platform, medium or system to another? 

### Conceptual Example: *A Blank Piece of Paper*

![Lecture%20Transcoding/blank-paper-mockup-design-vector-14515143.jpg](Lecture%20Transcoding/blank-paper-mockup-design-vector-14515143.jpg)

1. This is a blank piece of paper.
2. Actually it's a photograph of a blank piece of paper (with a grey background)
3. Actually it's a photograph of blank piece of paper, captured by a digital camera sensor that converts light information into data, which was stored in .jpg encoding format on a remote computer server accessed by a laptop through the internet.
4. Actually it's a digital photograph of a blank piece of paper, stored as .jpg on a remote server, which was embedded in a **.md** (markdown) document stored on a different server, read by a laptop via the internet and then displayed through millions of tiny lights on a digital display ... at the same time converted into a video signal & sent via an HDMI cable to a beamer, where a different tiny display converts the original image data into millions of tiny, physical dots as a powerful light bulb shines light through it, which then travels through the air and reflects off a wall ... producing a very similar representation of a blank page with roughly the same formal, colour and tonal qualities as a digital photograph of a blank page.
5. Yet 99.9% of its viewers will only see & register the image of 'a blank piece of paper'.

On the technical (or technological) as well as conceptual level, this 'Blank Page' rapidly moves through a number of encoding formats, hardware systems, communication networks and both digital and analogue processes. But since the outcome of this complex transaction does not attempt to alter or remove any meaning, intention or formal qualities of the original input data, the entire process practically becomes **invisible or irrelevant** to us as viewers. It happens seamlessly, almost by magic. 

In this case its pretty useful that the whole process is hidden, since we don't care to change the medium, format or meaning, but simply want a reproduction of the original input data at a different scale (size of wall) and within in a different context (the classroom, not inside a laptop) using a different hardware tool (projector instead of display).

On a daily basis, most transcoding takes place in this fashion and primarily seeks to address practical concerns, such as storage limitations, accessibility of media across different systems, transmitting content across great distances, etc. This digital 'magic' is what makes the rich media environment of the current internet functional across the world using all kinds of different hardware, networks, devices and languages. 

![Lecture%20Transcoding/magritte_ceci_nest_pas_un_epipe_1024_epa.jpeg](Lecture%20Transcoding/magritte_ceci_nest_pas_un_epipe_1024_epa.jpeg)

This is not '*This is not a pipe*' by Magritte. This is a transcoding of a digital photograph which documents a process of transcoding in action (of a conceptual artwork about transcoding). 

### A Closer look at 'Input' formats

In order to look underneath some of these hidden processes, its good to investigate different elements of digital encoding, such as the **metadata**, to get insights into either the **input format** or **target format**. Here we see some 'hidden' characteristics, such as the date of creation, the digital resolution in pixels, and other technical aspects such as transparency, the given file name and size. This information is specific to this one instance. Once this files is uploaded to another place or platform (for example, Google Photos) the file might be transcoded once again, without us even being aware of it.

As designers, wanting to control or direct the process of transcoding with specific intentions, it is therefore important to become familiar with the different characteristics, descriptors and roles of encoded data formats. This is true for pictures, moving images, audio and text.

In the 'Blank Page' example, we could also peek behind the context in which the artefact was encountered, such as the 'hidden' code. In this case, a web-page on VectorStock.com. When Analysing the 'input' of your artefact what is there and clearly apparent is **just as important** as what is **missing or hidden**.  

![Lecture%20Transcoding/Screenshot_2020-03-08_at_14.25.24.png](Lecture%20Transcoding/Screenshot_2020-03-08_at_14.25.24.png)

![Lecture%20Transcoding/Screenshot_2020-03-08_at_14.26.32.png](Lecture%20Transcoding/Screenshot_2020-03-08_at_14.26.32.png)

### Critical Meta-Data

Think about the metadata of a file in relation to the metadata of the IISG catalogue entry.
What and how does it contribute to the current definition (input) of your artefact?  

As many students already realised, the IISG catalogue is incomplete, prone to errors and produced with all kinds of biases — including individual, societal, historic or random — just like all archives ultimately are. It is therefore important to think carefully and critically about these aspects, and whether they are inherent or missing in your **input** and ******whether your process of transcoding takes this into account or even directly addresses it.

The question of **Categories** (or **taxonomies**, the 'system of categories') is one important area of definition within the archive to pay attention to. Think about the 'subject' that is included in the metadata of a catalog entry. Remember that some categories might be inherited from an early time, or are produced in the interest of scientific research which has its own objectives. As designers, you are invited to think about aspects of **resilience** in this assignment. So elements such as metadata, description, classification and organization of your cultural artefact are therefore open for design input and critical intervention.

### Why Categories Matter: *Brancusi vs. the United States*

![Lecture%20Transcoding/bird_in_space.jpg](Lecture%20Transcoding/bird_in_space.jpg)

Brancusi. *Bird in Space.* 

Romanian sculptor Constantin Brancusi (1876–1957) was preoccupied by the theme of the bird. Under the title *Bird in Space* he produced 15 versions of a sculpture in marble, bronze and plaster casts. Brancusi sought to convey the essential nature of a bird, elegantly soaring upward in flight, without the need for **traditional representational forms**. In 1926, Brancusi sent one of the bronzes from Paris to New York for an exhibition of his work (curated by his friend and advocate Marcel Duchamp). 
Although the law permitted artworks, including sculpture, to enter the U.S. free from import taxes, when the work arrived, officials refused to let it enter as art. To qualify as 'sculpture', works had to be “**reproductions by carving or casting, imitations of natural objects, chiefly the human form**”. Because *Bird in Space* did not look much like a bird at all, officials classified it as a utilitarian object (“Kitchen Utensils and Hospital Supplies”) and levied an import tax against it (40% of the work’s value). 

Bewildered and exasperated by this assessment, Brancusi went to court in defence of *Bird in Space*. Despite the varied opinions on what qualifies as art presented to the court, in November 1928 Judges Young and Waite ruled in favour of the artist. This was the first court decision that accepted that non-representational sculpture could be considered art.

Would this scenario have presented itself if the sculpture of a bird in flight *looked* more like the figure of a bird? Would the question of import tax have come up had Brancusi sent a plaster cast, instead of a bronze? Bronze was a mass material at the time, often imported for industrial applications and more heavily taxed. Thus both the technical aspects of encoding (material) and categorical definition (art *must be* representation) played a role in this case, which eventually lead to a legal redefinition for importing non-representational art. Consider how formal aspects of media relate to meaning, especially the differences between **representative** versus **interpretative** aspects of encoding. 

### Transcoding Meaning

**How does meaning change via a process of transcoding?**
What can this process make possible for you as a designer?
How would you harness the power of transcoding to change both the technical aspects of a cultural artefact as well as its meaning, communication or inherent value? 

When we think about **Cultural Information**, technical encoding exists side-by-side with **social encoding**. Meanings and Values are highly dependent on the personal, historic, geographic, political, formal & aesthetic characteristics when encountering any given medium, or when changing from one type of media to another. You can think about objective aspects of encoding (technical & internal) in relation to subjective effects (social & external). 

![Lecture%20Transcoding/blank-paper-mockup-design-vector-14515143.jpg](Lecture%20Transcoding/blank-paper-mockup-design-vector-14515143.jpg)

![Lecture%20Transcoding/Expanding-Brain.jpg](Lecture%20Transcoding/Expanding-Brain.jpg)

The same textual descriptions of 'A Blank Piece of Paper' used above have a totally different interpretation & characteristic when it comes into contact with a wider social context, network of meaning and formats. As a meme, its **interpretative encoding** outperforms its **representative meaning**. When thinking about the act of transcoding, critically consider the differences between the **representation** (a literal placeholder) of an artefact, versus the **interpretative** (social signification of the artefact). 

While many archives place a high value on maintaining original artefacts in hermetically-sealed rooms, away from light, more often than not, access to such materials now takes place only through digital proxies (digital photographs in a catalogue and descriptions). By reducing access to cultural commodities to purely representational digital formats, what do we loose? Do those sterile photographs maintain the social and experiential resonance of the original input? Will both representative digital images or originals artefacts become obscure without public access? One form of ensuring archival resilience is the continuing prominence and role of a cultural artefact within popular, mass media. The Mona Lisa lives in the minds of millions of people today in part because of its mass-media reproductions: thousands of mugs, t-shirts, shower curtains, memes, etc. 

### Side-Effects of Encoding

Even within the same medium, different encoding formats can radically influence framing, intention and meaning. For example, a 3 minute video of a news-broadcast from a war **vs** a 3 minute trailer for a fictional film about the same war will have both vastly different **cultural meaning** as well as **technical** **values**.

![Lecture%20Transcoding/Screenshot_2020-03-08_at_15.14.48.png](Lecture%20Transcoding/Screenshot_2020-03-08_at_15.14.48.png)

![Lecture%20Transcoding/Screenshot_2020-03-08_at_15.16.31.png](Lecture%20Transcoding/Screenshot_2020-03-08_at_15.16.31.png)

While the pixelation seen here is a result of high levels of video compression during encoding, it also represents a visual language that now denotes 'realism'. The interpretation of the same scene through a Hollywood film, with uncompressed super-high definition video, can denote fiction, manipulation or staging. The different side-effects of encoding formats (heavy compression, small file sizes, soft pixel video) also generate their own aesthetic and formal meanings over time.  

## **Artifacts**

The key drawback of transcoding in lossy formats is decreased quality. Compression artifacts are cumulative, so transcoding causes a progressive loss of quality with each successive generation, known as digital generation loss.

**Transcoding === storage**

Transcoding happens on all our devices all the time. Very few devices output raw uncompressed footage. In the same omnipresent way tools/software for transcoding are everywhere such as Quicktime, Adobe Media Encoder, Photoshop, etc. Transcoding is happening when you upload your video to YouTube or Vimeo in order to make sure videos are stored correctly on their servers. Web clients and servers request a different format then cinema or printers. That's why transcoding is a process our storage obsessed society can't live without.

## Programming languages and environments

Unlike the scraping assignment I encourage to explore other programming options than Web-based programming (HTML, CSS and JavaScript). Depending on what kind of transcoding tool(s) and type of archive you want to develop you can choose from a wide variety of languages, environments and libraries. Think about this in terms of concept, outcome but don't forget the practicality that using a completely new language can come with additional learning curve.

Some examples of possible tools, environments and languages to use to create your transcoding tools:

1. **Javascript**
    - Plain web stack (including HTML, CSS)
    - NodeJS
    - P5.js
    - Three.js (3D oriented)
2. **Java**
    - Processing
    - Arduino
3. **C#** (feels familiar to Java and hence *Processing*)
    - Unity (scripting inside Unity)
4. **C++** (feels familiar to Java and hence *Processing*)
    - openFrameworks

Each of these come with their own speciality. Processing is great in certain things and NodeJS or Arduino in others. Decide based on how you want to build your resilient archive and the types of formats/data you are dealing with.

## Markdown

Markdown a mark-up language as is HTML. It's very easy to use and write. In all of the GitHub repo's you've created this year you were already using it in the [README.md](http://readme.md) file as `.md` stands for Markdown.

The documentation will also happen in the [README.md](http://readme.md) file so as always ceate a GitHub repo for this project and start writing in the README.md file your research, process and documentation for your tool(s).

Here's a the basic syntax of Markdown: [https://www.markdownguide.org/basic-syntax](https://www.markdownguide.org/basic-syntax)

### Documentation

The documentation of your tool should consist of the following:

1. Your perspective, concept and approach of the archive, the artifact and transcoding
2. Research related to the artifact and tool
3. Process of creating the tool
4. Your findings when transcoding and how does this reflect on the artifact
5. The documentation on how to access, install and use your tool

Important to note is that since this all will be writtin in one file is that you have to keep in mind that it can't have multiple pages but should read and flow like a single long document. Think of the structure of this document, how does it fit within your concept, how does it complement the tool and possibly the artifact? How do you create a resilient documentation?

## Deliverables

**Coding class specific deliverable**

- Digital transcoding tool(s)

**IMD class specific deliverable**

- A number of transcodings (using the digital tools and more) of a physical artefact into diverse and resilient media.

**Deliverable for both classes**

- The documentation document in Markdown (including concept, research, process, reflection and documentation of tool)

## **Outcome**

A digital, screen-based ***Collection of Archival Resilience***, featuring:

- 40 Physical Artefacts from the IISG transcoded into diverse media (multiple transcodings for each)
- A repository of 40 transcoding tools (including documentation & instructions)

The outcomes (including both analog transcodings and the digital repository of tools) will be exhibited at the IISG. Students will also present or give a reading of their processes, transcoding tools and research. **NB: Your Markdown document is therefor your primary design format for all outcomes.** 

## Works using various ways of transcoding

### ***The SKOR Codex* by La Société Anonyme**

[The SKOR Codex](http://societeanonyme.la/#codex) is a printed book which will be sent to different locations on earth in the year 2012. It contains binary transcoded image and sound files selected to portray the diversity of life and culture at the Foundation for Art and Public Domain (SKOR), and is intended for any intelligent terrestrial life form, or for future humans, who may find it. It comes with instructions on how to 'read' or 'decode' the binary sheets.

![http://societeanonyme.la/images/codex-open-4.jpg](http://societeanonyme.la/images/codex-open-4.jpg)

![http://societeanonyme.la/images/codex-open-2.jpg](http://societeanonyme.la/images/codex-open-2.jpg)

### ***Deleted City* by Richard Vijgen**

The Deleted City is a digital archaeology of the world wide web as it exploded into the 21st century. At that time the web was often described as an enormous digital library that you could visit or contribute to by building a homepage. The early citizens of the net (or netizens) took their netizenship serious, and built homepages about themselves and subjects they were experts in.

[https://vimeo.com/280524012](https://vimeo.com/280524012)

### *Vacant NL* and *Dutch Atlas of Vacancy* by RAAAF

For the Venice Architecture Biennale 2010, curator RAAAF was invited by the Netherlands Architecture Institute (NAI) to make a statement about the potential of landscape architecture to contribute to resolving the complex challenges that our society faces today. These challenges call for innovation; for a culture centered on design skills and cooperation between scientists and creative pioneers. 

The archive and atlas ‘Vacant NL’ calls upon the Dutch government to make use of the enormous potential of inspiring, unoccupied buildings from the 17th, 18th, 19th, 20th and 21st centuries for innovation within the creative knowledge economy. By recording several properties, surroundings and spatial dimensions they've created a large map of vacancy in the Netherlands.

![https://images.dezwijger.nl/unsafe/1500x999/smart/https%3A%2F%2Fadmin.dezwijger.nl%2Fwp-content%2Fuploads%2F2015%2F12%2FRAAAF-Rietveld-Architecture-Art-Affordances-Vacant-NL-000477image.jpg](https://images.dezwijger.nl/unsafe/1500x999/smart/https%3A%2F%2Fadmin.dezwijger.nl%2Fwp-content%2Fuploads%2F2015%2F12%2FRAAAF-Rietveld-Architecture-Art-Affordances-Vacant-NL-000477image.jpg)

[https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.raaaf.nl%2Fimages%2FRAAAF-Rietveld-Architecture-Art-Affordances-DutchAtlasofVacancy-000541image.jpg%3Fw%3D2880&f=1&nofb=1](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.raaaf.nl%2Fimages%2FRAAAF-Rietveld-Architecture-Art-Affordances-DutchAtlasofVacancy-000541image.jpg%3Fw%3D2880&f=1&nofb=1)

[https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.raaaf.nl%2Fimages%2FRAAAF-Rietveld-Architecture-Art-Affordances-DutchAtlasofVacancy-000542image.jpg%3Fw%3D2880&f=1&nofb=1](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.raaaf.nl%2Fimages%2FRAAAF-Rietveld-Architecture-Art-Affordances-DutchAtlasofVacancy-000542image.jpg%3Fw%3D2880&f=1&nofb=1)

### ***Timeline* by Thomas Hirschhorn**

Although less to do with transcoding of formats the ways of how Hirschhorn builds his archival works as altars, kiosks, and monuments do require a set of methods. Timeline, a large-scale collage of images, written statements, and text excerpts, is an example of using collage, linking and cross-media narrative building as methods to build an archive. 

![https://www.diaart.org/media/w1050h700/webimages/hir-timeline-install-02-sm.jpg](https://www.diaart.org/media/w1050h700/webimages/hir-timeline-install-02-sm.jpg)

### ***No Ghost Just a Shell* by Philippe Parreno and Pierre Huyghe**

No Ghost Just a Shell was initiated by Philippe Parreno and Pierre Huyghe in 1999. They acquired the copyright for a figure called 'Annlee' and her original image from the Japanese agency 'Kworks', which develops figures (almost actors) for cartoons, comic strips, advertising and video games of the booming Japanese Manga industry. 'Annlee' was a cheap model: the price of a Manga figure relates to the complexity of its character traits and thus its ability to adapt to a story-line and 'survive' several episodes. 'Annlee' had no particular qualities, and so she would have disappeared from the scene very quickly. "True heroes are rare and extremely expensive …" (Parreno) Buying 'Annlee' rescued her from an industry that had condemned her to death.

Parreno and Huyghe have created several works with 'Annlee' including posters, animation and texts.

![https://www.mmparis.com/noghost/trickster.jpg](https://www.mmparis.com/noghost/trickster.jpg)

![https://live.staticflickr.com/2581/4175353342_6359d2885c_h.jpg](https://live.staticflickr.com/2581/4175353342_6359d2885c_h.jpg)

[No Ghost Just A Shell](https://www.mmparis.com/noghost.html)

### *Voyager Golden Record*

The Voyager Golden Records are two phonograph records that were included aboard both Voyager spacecrafts launched in 1977. The records contain sounds and images selected to portray the diversity of life and culture on Earth, and are intended for any intelligent extraterrestrial life form who may find them. The records are a sort of time capsule. On the cover instructions were added on how to play the recorded sounds. You can see the record attached to the Voyager spacecraft in the middle-bottom-left.

![https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/The_Sounds_of_Earth_-_GPN-2000-001976.jpg/1200px-The_Sounds_of_Earth_-_GPN-2000-001976.jpg](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/The_Sounds_of_Earth_-_GPN-2000-001976.jpg/1200px-The_Sounds_of_Earth_-_GPN-2000-001976.jpg)

![https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/The_Sounds_of_Earth_Record_Cover_-_GPN-2000-001978.jpg/1200px-The_Sounds_of_Earth_Record_Cover_-_GPN-2000-001978.jpg](https://upload.wikimedia.org/wikipedia/commons/thumb/5/56/The_Sounds_of_Earth_Record_Cover_-_GPN-2000-001978.jpg/1200px-The_Sounds_of_Earth_Record_Cover_-_GPN-2000-001978.jpg)

![https://upload.wikimedia.org/wikipedia/commons/d/d2/Voyager.jpg](https://upload.wikimedia.org/wikipedia/commons/d/d2/Voyager.jpg)

### *The Stench of World War I* by Sissel Tolaas

![https://www.deutschland.de/sites/default/files/styles/crop_page/public/article_images/pimg_187450_Sissel_Tolaas_Duft_Expertin_Gerueche_A.jpg?itok=ojcUI3N_](https://www.deutschland.de/sites/default/files/styles/crop_page/public/article_images/pimg_187450_Sissel_Tolaas_Duft_Expertin_Gerueche_A.jpg?itok=ojcUI3N_)

At Dresden’s Military Museum, visitors can open a small box and take in a powerful whiff of trenches from World War I—a smell that’s been described as a mixture of earth, gun powder, and death. “I replicated the smells through chemistry,” says the exhibit’s creator Sissel Tolaas, a Norwegian chemist and artist. “I had to rely on my knowledge in doing extreme projects and the description from army officers.”

Tolaas is one of the most respected smell experts in the world. Her research is funded by the perfumery corporation International Flavors and Fragrances (IFF) in New York. Out of her Wilmersdorfer lab in Berlin, Tolaas designs smell experiments and branding studies for corporate clients like Adidas and Mercedes Benz. She’s also created a number of provocative art installations in Germany and throughout the world.

In Tolaas’s 2006 exhibit titled the FEAR of Smell: the Smell of FEAR, she collected the smells of nine paranoid men and painted their odor on to walls using micro-capsulation. When museum visitors rubbed the walls, the men’s body odor was released into the air. Some visitors found the smells repulsive; others were fascinated.

### *One and Three Chairs* by Joseph Kosuth

In *One and Three Chairs*, Joseph Kosuth represents one chair three ways: as a manufactured chair, as a photograph, and as a copy of a dictionary entry for the word “chair.” The installation is thus composed of an object, an image, and words.

Kosuth didn’t make the chair, take the photograph, or write the definition; he selected and assembled them together. Which representation of the chair is most “accurate”? These open-ended questions are exactly what Kosuth wanted us to think about when he said that “art is making meaning.” By assembling these three alternative representation, Kosuth turns a simple wooden chair into an object of debate and even consternation, a platform for exploring new meanings.

![https://www.moma.org/learn/moma_learning/_assets/www.moma.org/wp/moma_learning/wp-content/uploads/2012/07/Joseph-Kosuth.-One-and-Three-Chairs-469x353.jpg](https://www.moma.org/learn/moma_learning/_assets/www.moma.org/wp/moma_learning/wp-content/uploads/2012/07/Joseph-Kosuth.-One-and-Three-Chairs-469x353.jpg)

### The Next Rembrandt

[https://youtu.be/IuygOYZ1Ngo](https://youtu.be/IuygOYZ1Ngo)

### Short Story: Playing Metal Gear Solid V by Jamil Jan Kochai

[Jamil Jan Kochai Reads "Playing Metal Gear Solid V: The Phantom Pain" - The New Yorker: The Writer's Voice - New Fiction from The New Yorker](https://pca.st/episode/0ceed82e-4085-43a2-8416-e19c08dc7541)

### Podcast: Everything Is Alive

[Everything is Alive](https://pca.st/podcast/65f25c00-41cb-0136-fa7c-0fe84b59566d)

### Friends on Netflix

![https://i.ytimg.com/vi/iRh3jQufzCk/maxresdefault.jpg](https://i.ytimg.com/vi/iRh3jQufzCk/maxresdefault.jpg)

### Others working with/on/by archiving

- Tacita Dean
- Mark Dion and Renée Green
- Stan Douglas
- Sam Durant
- Douglas Gordon
- Liam Gillick
- Gerard Richter