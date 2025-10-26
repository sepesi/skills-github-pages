---
title: "Improving Scientific Integrity"
date: 2025-10-18
---
# 1. Introduction
[Richard Feynman](https://en.wikipedia.org/wiki/Richard_Feynman) received the Nobel Prize in Physics in 1965 for his contributions to the development of quantum electrodynamics. In 1974, he gave a Caltech [commencement address](ttps://faculty.sites.iastate.edu/tesfatsi/archive/tesfatsi/CargoCultScience.RichardFeynman1974.pdf) in which he told a story about a society that wanted the benefits of scientific progress, and did what it imagined were the necessary steps to get that progress, but progress never happened because they lacked “scientific integrity.” In his commencent address Feynman explains,
  
> It's a kind of scientific integrity,
a principle of scientific thought that corresponds to a kind of utter honesty--a kind of
leaning over backwards. For example, if you're doing an experiment, you should report
everything that you think might make it invalid--not only what you think is right about
it: other causes that could possibly explain your results; and things you thought of that
you've eliminated by some other experiment, and how they worked--to make sure the
other fellow can tell they have been eliminated.
>
> Details that could throw doubt on your interpretation must be given, if you know them.
You must do the best you can--if you know anything at all wrong, or possibly wrong--
to explain it. If you make a theory, for example, and advertise it, or put it out, then you
must also put down all the facts that disagree with it, as well as those that agree with it. [...]
>
> In summary, the idea is to give all of the information to help others to judge the value
of your contribution; not just the information that leads to judgement in one particular
direction or another. [...]
>
> But this long history of learning how to not fool ourselves--of having utter scientific
integrity--is, I'm sorry to say, something that we haven't specifically included in any
particular course that I know of. We just hope you've caught on by osmosis.

Going beyond the hope of learning scientific integrity through osmosis, this essay proposes that DeepMind's new [co-scientist](https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist) AI agent would teach scientific integrity, as Feynan had hoped. Scientific integrety is the cornerstone of the scientific method, one of humanity's most immpactful concepts, along with agriculture, writing, and the harnessing of electricity. The scientific method is the most effective process for humanity to correct its own errors, biases, and misconceptions. The job titles that currently employ the scientific method the most are
* medical scientist/research scientist,
* epidemiologist (i.e., disease detective),
* clinical research scientist,
* data scientists, and
* experimental psychologist.

However, this essay proposes expanding the use of the scientifc method by bringing DeepMind's co-scientist AI agent to nurses and technicians within kidney dialysis clinics.

# 2. Previous work
This Imprving Scientific Integrity proposal builds directly upon the following concepts and technologies.

## 2.1 The scientific method
The [scientific method](https://en.wikipedia.org/wiki/Scientific_method) is a set of core principles and values that guide inquiry.  It was slowly refined over millennia through contributions from multiple civilizations:

* A foundation based upon logic and [empiricism](https://en.wikipedia.org/wiki/Empiricism) first appeared in Ancient Greece.
* Systematic experimentation to test a [hypothesis](https://en.wikipedia.org/wiki/Hypothesis) was added by medieval Islamic scholars such as [Ibn al-Haytham](https://en.wikipedia.org/wiki/Ibn_al-Haytham) (Alhazen) in the 11th century. Other scholars of the era, like [Al-Biruni](https://en.wikipedia.org/wiki/Al-Biruni), recognized the need for replication.
* The method was formalized in 17th-century Europe. [Francis Bacon](https://en.wikipedia.org/wiki/Francis_Bacon) argued for [inductive reasoning](https://en.wikipedia.org/wiki/Inductive_reasoning) and systematic experimentation instead of assuming ancient authorities were correct. Contemporaries like [Galileo Galilei](https://en.wikipedia.org/wiki/Galileo_Galilei), [Johannes Kepler](https://en.wikipedia.org/wiki/Johannes_Kepler), and [Isaac Newton](https://en.wikipedia.org/wiki/Isaac_Newtonv) masterfully combined mathematical theory with empirical observation and experimentation, demonstrating the method's immense power.

## 2.2 Bundled payments for erythropoietin

## 2.3 Hemoglobin level guidelines

## 2.4 Edward Tufte's small multiple plot design
A typical health record plot shows a time series of measurements. If there are many time series, they can be difficult to compare. For example, the popular MyChart by Epic Systems Corporation shows approximately one time series per web browser page with excessive white space between plots. Therefore, comparing two or more time series in MyChart needlessly wastes the reader's working memory.

![image](https://cdn-images-1.medium.com/max/1000/1*AEnXFI8X55eReQWFTnDDKQ.png "MyChart plot")
Figure 2-1 Screenshot of MyChart by Epic Systems Corporation showing a time series of red blood cell count measurements and the normal range with a green background  


In contrast to the style of MyChart plots, Edward Tufte's small multiple plots increase data density and therefore use less of the reader's working memory.² For example, Figure 2–2 displays the same red blood cell count time series as shown in Figure 2-1 but right next to other time series related to kidney function.

![image](https://cdn-images-1.medium.com/max/1000/1*7ItYKCmFh9XYWzuCC86Y8g.png "small_multiple")
Figure 2-2 Small multiple plots in a dashboard about kidney function (plotted by Julia and Makie). The proposed dashboards are organized by organ (e.g., kidney, heart, liver) instead of by blood test (e.g., Complete Blood Count). Each dashboard contains up to 16 time series small multiple plots (i.e., up to eight calendar time plots alongside their corresponding clock time plots).  

## 2.5 Bayesian data analysis
The Reverend Thomas Bayes first described his innovative approach to calculating probabilities in 1763. In 1812, the French polymath Pierre-Simon Laplace further developed the Bayesian approach but these ideas were later challenged and largely forgotten until their rediscovered by the British geophysicist and statistician Sir Harold Jeffreys in his 1939 book, Theory of Probability.

Today, the healthcare perspective on probability is strangely bimodal:
evidence with very few examples (e.g., N<5) is downplayed as anecdotal evidence having little clinical value (although it is valuable enough for doctors to witness and discuss during their rounds), and
evidence with many examples (e.g., N>1000) in a randomized controlled trial is considered the gold standard of clinical value (although RCTs are rare because of their long duration and high cost).

In contrast, the proposed patient health dashboards use Bayesian data analysis³ to formalize the presentation of anecdotal evidence and continually improve the confidence in that data analysis as more clinical examples become available. In other words, the proposed Bayesian data analysis continually learns and is expected to help fill a significant void in the current patient decision support. 

## 2.6 The Julia programming language
Started in 2009 and first publicly released in 2012, Julia is a free high-level programming language that is fast and particularly well suited for data analysis. Makie (pronounced mah-key) is a modern plotting library for Julia.

## 2.7 Spreadsheet applications
Introduced in 1969, the spreadsheet is a computer application that helps analyze data in tabular form. Spreadsheets gained widespread adoption with Microsoft Excel introduced in 1985.

## 2.8 Smartphones
The currently popular form of the smartphone with a large touchscreen display was introduced in 2007. Today's smartphones are powerful mobile computing devices with built-in cameras, built-in GPS navigation, and a growing list of artificial intelligence capabilities.

## 2.9 "Private Space" encrypted data on smartphone


## 2.10 Artificial intelligence
The phrase "artificial intelligence" was coined in 1955 by John McCarthy who defined intelligence as "the computational part of the ability to achieve goals in the world." However, the field did not start its rapid growth until 2011, when GPUs were first programmed to accelerate the training of neural networks.

Today, the capabilities of the neural-network-trained Large Language Models (LLMs) might be best described as uneven across tasks. For example, Google's Gemini deep research model is the best proofreader of essays (e.g., this one) I've ever worked with, human or not. Yet, that same LLM is not currently capable of transforming an English description of a desired plot into Makie code to plot it. Empowering healthcare professionals to write "prompt to plot" specifications to get helpful views of patient data is so important to the proposed patient health dashboards that a significant portion of a grant-funded budget should go to supporting professional Makie developers working on that capability.

## 2.11 DeepMind's co-scientist

# 3. Previous misdirected work
The short-lived project before this Improvving Scientific Integrity proposal was the patient health dashboard proposal, which was misdirected work because I was mistakenly focused on tooling (the visualization of the health status of a wide variety of patients) instead of being focused on the solution of a specific hair-on-fire problem (i.e., stabilizing the hemoglobin levels of kidney disease patients).

# 4. Initial test case


# 5. Architecture


# 6. Other candidate test cases

# 7. Alternatives

# 8. Possible objections

# 9. Results

# 10. Conclusion

[Paul Buchheit](https://en.wikipedia.org/wiki/Paul_Buchheit) was an early engineer (i.e., employee #23) at [Google](https://en.wikipedia.org/wiki/Google) before leaving in 2006 to co-found FriendFeed with [Bret Taylor](https://en.wikipedia.org/wiki/Bret_Taylor), now the chairman of [OpenAI](https://en.wikipedia.org/wiki/OpenAI). In 2009, [Facebook](https://en.wikipedia.org/wiki/Facebook) acquired FriendFeed but Buchheit left Facebook in 2010 to become a partner at [Y Combinator](https://en.wikipedia.org/wiki/Y_Combinator). Buchheit is a thought-leader concerning technology's impact on society. For example, in this [YouTube interview](https://youtu.be/LSUviaN1eso?t=874) at Y Combinator, Buchheit talks about two possible outcomes of AI:
> When we think about what is
the long-term trajectory of AI, it's the most powerful technology we've ever
invented. So the question is like where does that power go? I think there's essentially two directions: you
either go towards centralization where all the power gets centralized in the government or in a small 
number of big tech companies or something like that and my feeling is that that's catastrophic for the human
species because you essentially minimize the agency and power of the individual, and I think the opposite
direction is towards freedom and, as much as possible, we should give this
power and these capabilities to every individual to be the best version of themselves.

In the news, the AI outcome that centralizes power has a lot of momentum. For example, most of the new compute capabilities are owned by a small number of big tech companies:
- _Groups including BlackRock, Microsoft, Nvidia, and xAI join forces to acquire Aligned Data Centers — $40B deal delivers 5GW of operational and planned data center capacity_, [Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/groups-including-blackrock-microsoft-nvidia-and-xai-join-forces-to-acquire-aligned-data-centers-usd40b-deal-delivers-5gw-of-operational-and-planned-data-center-capacity), 2025-10-14.
- _Pennsylvania’s $70 Billion Race for America’s Data Centers_, [Data Center Knowledge](https://www.datacenterknowledge.com/energy-power-supply/pennsylvania-s-70-billion-race-for-america-s-data-centers), 2025-10-16.
- _BlackRock’s $40 billion deal highlights the unstoppable AI data center gold rush, as CEO Larry Fink pushes back on AI bubble fears_, [Fortune](https://fortune.com/2025/10/15/blackrocks-40-billion-deal-highlights-the-unstoppable-ai-data-center-gold-rush-as-ceo-larry-fink-pushes-back-on-ai-bubble-fears/), 2025-10-15.

And the AI outcome that advances the capabilities of individuals has almost no momentumm. For example, AI is now taking entry level jobs that were a source of training for recent graduates:

# References
