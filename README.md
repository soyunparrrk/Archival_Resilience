![Computational%20Women/the_computing_girls_today.gif](The%20Computing%20Girls%20Today/the_computing_girls_today.gif)

# **The Computing Girls Today**

### **Table of Contents**

1. Artefact
    1. Metadata
2. Research
3. Transcoding
    1. Transcoding No. 1
    2. Transcoding Tool
4. Reflection
5. Outcome
6. Conclusion
7. Bibliography

# **Artefact**

Taken in 1952 June, the Artefact is a photograph depicting a woman investigating data coming out of ARRA, the oldest computer known in The Netherlands. 

## **Metadata**

[Untitled](The%20Computing%20Girls%20Today/Untitled%20Database.csv)

# **Research**

---

## The History of Women in Coding

When one of the first computers in the human history were being operated during World War II, coding and programming were known as the work for people who possesses 'picky and precise' mentality. [#] Unlike the stereotypes of programmers in the current society, back then these people were assumed to be women. While it wasn't high-status work yet, the women were involved in mathematical calculations to execute instructions which we can define it as 'programming' in these current times. 

In 1960, the proportion of women in computing and mathematical professions was 27 percent in the United States. It reached the peak to 35 percent in 1990, but the numbers fell to 26 percent in 2013 which is below the percentage in 1960. Not only the number figures but also the culture and the societal view have been dramatically changed. Even now in 2020, programming is assumed to be 'men's job — as it needs precision, mathematical abilities, problem-solving skills which are not considered as women's major characteristics. 

### "Computing Girls"

Eddy Alleda, Dineke Botterweg, Ria Debets, Marijke de Jong, Bertha Haanappel, Emmy Hagenaar, Truus Hurts, Loes Kaarsenmaker, Corrie Langereis, Reina Mulder, Diny Postema and Trees Scheffer formed a group called the Computing Girls in the Netherlands. [#] As they had completed high school with high grades in mathematics, they were considered suitable for computation works.

![Computational%20Women/computinggirls-1986.jpg](The%20Computing%20Girls%20Today/computinggirls-1986.jpg)

Some of the Computing Girls at a reunion in 1986. From left to right: Truus Hurts, Dineke Botterweg, Bertha Haanappel, Eddy Alleda

They worked at the Mathematical centre programming early Dutch computers such as ARRA and ARRA II from 1954, guided by Van Wijngaarden who contracted them. Even though they were one of the pioneers of the present computer situation, due to their family forming and to devote to it they didn't use their knowledge in computer science anymore, except Eddy Alleda who worked as a math teacher later on. 

### Important Women Programmers and Their Forgotten History

Throughout the history, there are many legendary women mathematicians and programmers who highly contributed in development of technology. Ada Lovelace, Grace Hopper, Evelyn Boyd Granville, Sister Mary Kenneth Keller, Radia Perlman are a few examples from them. 

![Computational%20Women/grace_hopper.png](The%20Computing%20Girls%20Today/grace_hopper.png)

Grace Hopper, an American computer scientist born in New York in 1906. She was one of the first programmers of the Harvard Mark 1 computer. She also popularised the idea of machine-independent programming languages such as COBOL, an early programming language we still use today.

![Computational%20Women/17mag-coders-pics-slide-LN0P-superJumbo.png](The%20Computing%20Girls%20Today/17mag-coders-pics-slide-LN0P-superJumbo.png)

A mathematician Ada Lovelace from England is known as the first coder in history. In 1833, she wrote an algorithm with which the Analytical engine, a design to execute if/then commands invented by Charles Babbage, would calculate the Bernoulli sequence of numbers. 

Even though women were the pioneers in programming for machines, the industry became much dominated by men over time. Not only the perspective for the characteristic of 'women' culturally didn't fit into computing anymore, but also women had less chances to be exposed to it for decades in normal households as 'programming' became a high-status job.

## Technical Research for Photography: its Digital Translation and Reproduction

Since the artefact is a little sheet of physical photograph, first I looked into the technical aspect of photography. 

**From the questions of the physical side:** How was the reality captured through an analogue camera? How does the image translate on a negative film during that process? How is that image printed on a light-sensitive photographic paper? 

**To digital:** What kind of technology has been used for scanning the piece of paper? How is it saved in a digital space? What kind of compression methods have been used? How do we see them in our eyes?

**And back to the physical world again:** What kind of methods are available for digital printing? What does it mean to re-print the original photograph? What kind of decisions are made during that process — The paper size? Which printing method (Inkjet? Laser? Gelatine Silver? Photogravure?...)? Colour or B&W(even though the original is B&W)? Fill or centre the image? What kind of paper? 

![Computational%20Women/5FE08566-F7BC-4F1C-900D-0E50EAE6C6D3.jpeg](The%20Computing%20Girls%20Today/5FE08566-F7BC-4F1C-900D-0E50EAE6C6D3.jpeg)

A sketch for understanding the process of taking photographs and turning them into digital files.

# **Transcoding**

My transcoding project has been ongoing through the question of 'how do I translate this historical photograph relating to this current time?'. 

## **Transcoding 1: Lossless Compression**

### **Description**

This photograph is not only capturing a historical memory but also cultural discourses around it. I was looking for a way to preserve this image with persistence. During the research about image compression methods, I've found turning images into a lossless format fascinating. 

### **Methods**

In image compression, there are several methods for lossless compression.

![Computational%20Women/Untitled.png](The%20Computing%20Girls%20Today/Untitled.png)

The demonstration of RLE compression in real life [https://classic.csunplugged.org/image-representation/](https://classic.csunplugged.org/image-representation/)

### **Tools**

I've used two existing tools for this, the first one is Image → Binary, the other one is Binary → Image.

![Computational%20Women/Untitled%201.png](The%20Computing%20Girls%20Today/Untitled%201.png)

(1) [https://www.dcode.fr/binary-image](https://www.dcode.fr/binary-image)

![Computational%20Women/Untitled%202.png](The%20Computing%20Girls%20Today/Untitled%202.png)

(2) [https://onlinebinarytools.com/convert-binary-to-image](https://onlinebinarytools.com/convert-binary-to-image)

Several personal decisions had been made in this process.

1. Since the image is large I had to specify the customised resolution. 
2. 50% threshold was recommended as default.
3. Binary characters to display.

### **Results**

1. **Image to Binary**

    The original text can be found below.

    [Image to Binary](The%20Computing%20Girls%20Today/Image%20to%20Binary.md)

2. **Binary to Image**

![Computational%20Women/Untitled%203.png](The%20Computing%20Girls%20Today/Untitled%203.png)

## **Transcoding 2: Node-based Tool Sorting the Image**

### **Description**

Short description here. You can structure the information and documentation for each transcoding, design research or coding tool as you like. It's important that you make clear the aims & goals of the transcoding, what methods and tools you use. If this is often the same across different transcodings, consider making a standardised table at the beginning of each.

You should include well-formatted documentation of your experiments and developments below. Someone without previous knowledge about your work should be able to follow along the steps, aims and results of your developments from this structure. Make sure all media used is correctly linked or embedded (images, PDFs, Videos, etc).

### **Methods**

Description of your methods, documentation of behind-the-scenes processes can go here. Think of the photos and videos you made when visiting the IISG or during captures of your artefact. You can use tools such as [Gifs.com](https://gifs.com/) to generate moving-image thumbnail to link to short videos.Just enough to give a clear overview, before getting into details.

With some HTML tags you can do simple styling in markdown, for example:

```
<width="50%">

```

Remember to include the url link to jump to the full media, of course!

### **Tools**

Mention the tools that you used or made (if and when relevant).

### **Results**

Some of your transcoding experiments may have smaller outcome sketches like images or short video tests. They can go directly within this section. Or maybe this transcoding became a part of the final outcome format. When that is the case, you can simply include a [hyperlink](https://github.com/IMD-Y3-2020/Example#) to the final outcomes in the **Transcoding** section. In the final outcome section below you can embed or explain the final format outcome in detail.

## **Transcoding Tool**

### **Description**

You might have made multiple coding tools during the semester. Or the transcoding tool might be part of a specific transcoding experiment itself. It's up to you to define the linear flow of the Readme. Just like the transcoding of media itself, the coding tool should be well documented. So if you are using a coding tool in your first experiment, include the documentation of the coding tool **before** you include the results, etc.

### **Aims**

Include the main aims or intentions behind making the tool, and what it is used for.

### **Methods**

This includes the coding languages, coding frameworks or libraries, and any platforms or webtools for example.

### **Results**

The coding tool will vary a lot between different students. So depending on the use and type, you may include more or less documentation here.

### **Source Links**

Please include links to the tools, sources etc used during the coding. E.g. the resources used for making your coding tool.

# **Reflection**

You might want to include a section about reflecting on the results of your coding and IMD experiments this semester. It can give additional context before reading the final outcomes below.

# **Outcomes**

This section will be different for each student, depending on how and what is formatted as a final result for the semester assignment. Nevertheless a clear written and documented outcomes is important. So give the appropriate subsections or formats to make this as thorough as possible.

### **Outcome Links**

Here you link to your final assignment outcomes. This could be a website, a video, etc etc. Please include links to the appropriate GitHub folder on your repository where your coding tool is stored.

This is the main way to access your IMD + Coding outcomes for the semester. So its very important that you check for bugs, troubleshoot hyperlink issues, embedded media issues etc. Please make sure you KNOW where each file you use is stored. E.g. If you migrated from Notion markdown into GitHub, its **VERY IMPORTANT** to know that Notion randomly stores images on an Amazon server. It changes those locations all the time. So if your main outcome or documentation is still grabbing those links, **its very likely** they might disappear before collectives. So please have all media and necessary files managed well in your own locations (online or github etc).

# **Conclusion**

You might have a nice conclusive observation to share at the end :)

## **Bibliography**

**[1]**: “Unsung Heroes in Dutch Computing History.” "Computing Girls" | Unsung Heroes in Dutch Computing History, [www-set.win.tue.nl/UnsungHeroes/heroes/computing-girls.html](http://www-set.win.tue.nl/UnsungHeroes/heroes/computing-girls.html).