# Homework
Make a single plot

Create a plot, of whatever data (and models if you want) you choose from open data. The plot can be about anything relevant to this class or your research. 

You can make the plot in any coding language you want (e.g. python, javascript, R...), as long as you upload the code that generates the plot onto your repo (which means no tableau, or any other non reproducible).

If it is a redesign of a plot you already made (e.g. for your research) upload the original as well

The plot needs to be uploaded onto the HW9 folder in your github PUS2020 repo and be embedded in the README.md That means: when I click on the HW9 link the plot must be rendered in the front page of the repo. Your readme must contain the plot, and a brief caption. If it is an interactive graphic, upload a static image of it in the README and provide a link to the interactive version.

Think about all the considerations we have made about visualization in the last 3 classes.

# Watch
Jer Thorp TED-ex Vancuver talk. https://www.youtube.com/watch?v=Q9wcvFkWpsM&app=desktop


# Reading

1. How W.E.B. Du Bois Meticulously Visualized 20th-Century Black America
https://hyperallergic.com/476334/how-w-e-b-du-bois-meticulously-visualized-20th-century-black-america/

2. Pick one from the 7 papers listed in this article https://web.archive.org/web/20190226213626/http://fellinlovewithdata.com/guides/7-classic-foundational-vis-papers.  By Enrico Bertini (NYU) 

The content of the article is here: 
### 7 Classic Foundational Vis Papers You Might not Want to Publicly Confess you Don’t Know
Enrico Bertini, 2011

Even if I am definitely not a veteran of infovis research (far from it) I started reading my first papers around the year 2000 and since then I’ve never stopped. One thing I noticed is that some papers recur over and over and they really are (at least in part) the foundation of information visualization. Here is a list of those that:

- come from the very early days of infovis
- are foundational
- are cited over and over
- I like a lot
Of course this doesn’t mean these are the only ones you should read if you want to dig into this matter. Some other papers are foundational as well. For sure a side effect of the maturation of this field is that some newer papers are more solid and deep and I had to refrain myself to not include them in the list. But this is a collection of classics. A list of papers you just cannot avoid to know unless you want to risk a bad impression at VisWeek (ok ok it’s a joke … but there’s a pinch of truth in it). A retrospective. Definitely a must read. Call me nostalgic.

Advice: in order to really appreciate them you have to think they have all been written during the ’90s (some even in the ’80s!).

Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods. William S. Cleveland; Robert McGill (PDF)

Please don’t tell me you don’t know this one! This is the most classic of the classics. Cleveland is one of the fathers of statistical graphics and he wrote two groundbreaking books, The Elements of Graphing Data and Visualizing Data, based on the research carried out in this paper.

What’s in it? The paper describes a series of experimental user studies to understand how basic visual primitives like length, size, color, etc., compare in terms of visually carrying out quantitative information.
Why is it important? Cleveland with this paper introduced the idea and concept (quite vigorously) of visualization based on rigorous experimentation. People like Bertin many years before started ranking visual features but never before this ranking was validated with a scientific method.
What can you learn? The basics of data visualization. That visual encoding is hard stuff and you shouldn’t take it too lightly. And that visual primitives do have a ranking that you have to take into account if you want to design effective data visualizations.
The Structure of the Information Visualization Design Space. Stuart K. Card and Jock Mackinlay (PDF)

I suspect this is somewhat little known compared to the previous one. Card and Mackinlay are among the founders of information visualization and the content of this paper is repeated and reworked (maybe in a better shape) in the book Readings in Information Visualization.

What’s in it? The paper describes what are the basic components that build up a visualization and how to put them together to build a new design.
Why is it important? Because it is one of the first attempt to describe the visualization space in a systematic way.
What can you learn? You learn that in order to design innovative visualizations you have to know what the building blocks are and how to connect the. In my experience this is one of the most important, and often neglected, skills.
Visual Information Seeking: Tight Coupling of Dynamic Query Filters with Starfield Displays. Christopher Ahlberg and Ben Shneiderman (PDF)

Ok I am ready to accept you don’t know this paper yet, but please don’t tell me you’ve never heard of Ben Shneiderman and Christopher Ahlberg. If you didn’t, you’ve been leaving under a rock. Let me guess … you’ve heard of Ben Shneiderman but not of Christopher Ahlberg. Well, Christopher is the founder of Spotfire, probably the first commercial success of information visualization ever. And Spotfire was based on the research described in this paper.

What’s in it? It describes one of the first attempts to make visualization dynamics and controlled by the user through interactive queries.
Why is it important? The whole idea of dynamic filtering had a huge impact on the way data is visualized interactively. We can see the effect of this idea everywhere. Before that, there where queries in a database. After that, it was clear how powerful interactive visualization could be.
What can you learn? You learn how powerful data visualization can be when interactive capabilities are added to static representations. After more than 10 years we are still learning this lesson.
High-Speed Visual Estimation Using Preattentive Processing. C. G. Healey, K. S. Booth and J. T. Enns (PDF)

I fell in love with Chris Healey‘s work very early in my journey into visualization. It always struck me how innovative and intriguing his research was. His specialty is what he calls “Perceptual Visualization”: the study of visualization based on core human vision principles. His page about perception in visualization is a real classic.

What’s in it? It describes how the concept of preattentive processing can help in guiding the design of visualization and user interfaces. It contains several experimental studies.
Why is it important? Nobody before the work of Healey (maybe Colin Ware?) pushed the limits of perception applied to visualization so far. I bet many of the results of his studies have yet to be exploited.
What can you learn? You learn what preattentive processing is and how to apply it to the design of information visualizations. (As a byproduct you might also learn how tough this stuff is!)
Automating the Design of Graphical Presentations of Relational Information. Jock Mackinlay (PDF)

I mentioned Jock already in one of the papers above. Jock is not only behind some of the fundamental research in visualization and human-computer interaction but he is also one of the minds behind Tableau Software. This paper can be considered a very early draft of what became through several other steps Tableau today. In some sense it can still be considered visionary today since the dream of a tool that automatically adapts to data is very far to come (if it will ever come).

What’s in it? Jock presents a system called APT (A Presentation Tool) whose purpose is to automatically design effective visualizations automatically by matching data features with visual features through the use of logic rules.
Why is it important? It is not only important because it contains some visionary perspective in visualization but also because part of the work was focussed on the definition of visual primitives (starting from the work of Bertin) and on the way data features should match visual features.
What can you learn? Knowing how to match data features to visual features is one of the most important skills of knowledgeable data visualization experts.
How NOT to Lie with Visualization. Bernice E. Rogowitz, Lloyd A. Treinish (PDF).

How can you not love a paper with a title like this? I’d give it a prize for best marketing in the research papers design. This work is fully focussed on color use and perception but its implications extend beyond the scope of color mapping. This work was part of the development of one of the earlier data visualization systems called OpenDX developed by IBM which included a module called PRAVDA for assisted color mapping.

What’s in it? A detailed explanation of how the visual eye can be mislead if the wrong (color) mapping is used. Plus a thorough discussion of how to build effective color scales that take into account data distribution.
Why is it important? I still see a lot of people using color badly. By reading this I hope this number will get smaller and smaller. It is also an early example of how automatic computation and interaction can go happily together.
What can you learn? This paper will give you solid arguments about why mapping color badly is bad. Plus you will learn how to build effective color scales. On a side note, the same is true for every other visual feature you want to use.
The Eyes Have It: A Task by Data Type Taxonomy for Information Visualizations. Ben Shneiderman (PDF).

This is a funny paper. Ben has the ability to write a paper with absolute nonchalance and make it massively popular. It’s not too technical, neither too elaborated. He straightforwardly proposed a classification and the famous infovis mantra and it became one of the biggest classics of infovis. If I remember well I’ve heard him talking about this paper once and explaining how unexpected this success was.

What’s in it? A classification of information visualization techniques according to data type. More importantly the explanation of the visual information seeking mantra: “overview first, zoom and filter, details on demand”.
Why is it important? The visual information seeking mantra has been the reference model for interactive visualization for 15 years. Hundreds of systems have been developed under this paradigm.
What can you learn? The classification by data type will help you mentally organize visual designs into classes (even if I must admit I am not a big fan of this classification). The visual information seeking mantra will guide you in designing and evaluating interactive visualizations: do you have an overview? zoom and filter capabilities? details on demand? tools to relate things? history facilities?
That’s all guys. Pufff … it’s been a marathon to write such a long and detailed list. That’s the best I could think of and I really really hope this will be tremendously helpful to you. Go on read them and feel free to expand the list. Please remember:

Let me know if something is not clear. I’d really love to help you.
Let me know if you don’t agree on something. I’d be happy to hear and learn from you.
If you have other papers to suggest, please do it!
Thanks a lot guys. Have fun with it.


