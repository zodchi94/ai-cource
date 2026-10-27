# Лекция 1. Introduction to Artificial Intelligence

Текст лекции по слайдам: что написано на слайде и что говорит лектор. Слайды — в файле [slides.pdf](slides.pdf).

## Слайд 1. Introduction to Artificial Intelligence

### На слайде
Титульный слайд.

### Речь лектора
Hello everyone! My name is Nikita, and I will be your lecturer in this data science course. Let me introduce myself a bit more: I have been working in this field for the last eight years. My main area of work is the retail sector — sales forecasting, promo activity forecasting, price elasticity and so on. I hope this course will be useful for you and that I can share my experience with you.

Let's start and go deeper into artificial intelligence. The first thing we have to discuss is what artificial intelligence actually is. I want to introduce you to the world of AI, because data science and machine learning are just parts of this huge world. Today's lecture is about the general context: where we are and what the term "AI" means.

---

## Слайд 2. Contents

### На слайде
1. What is Artificial Intelligence
2. History of AI
3. Strong vs Weak AI
4. ML in AI
5. Data Science

### Речь лектора
Let's briefly go through the contents. First, we'll discuss what AI is and look at its history to see where we are now. After that, we'll discuss some core concepts, such as strong versus weak AI and the role machine learning plays in AI. Finally, I'll show you what data science is and how it connects to AI and machine learning.

---

## Слайд 3. Part 1 of 5 — What is Artificial Intelligence

### На слайде
Before we dive into the details of data science and AI development, let's first discuss a fundamental question - what is artificial intelligence?

### Речь лектора
Before we go further, we have to answer one big question: what is artificial intelligence? The question is tricky, mostly because it is hard to say what intelligence is in general — there are many different definitions.

---

## Слайд 4. What is Intelligence?

### На слайде
Many different terms and descriptions from different perspectives

- **General Definition:** Is the capacity to acquire, understand, and use knowledge and skills to adapt to new circumstances.
- **Cognitive Perspective:** Mental ability to reason, solve problems, comprehend complex ideas and learn from experience.
- **Emotional Intelligence:** Ability to recognize, understand, and manage emotions.
- **Social Intelligence:** Is the capability to navigate complex social environments, understanding social cues, and forming social bonds.
- **Biological Perspective:** Is a product of brain activity, enabling an organism to process information from the environment, make decisions, and engage in complex behaviors.
- **Philosophical View:** Is the ability to think critically, question assumptions, and shape the world in meaningful ways.
- **Practical Intelligence:** Intelligence is the ability to solve real-world problems, adapt to changing environments, and effectively navigate everyday challenges and opportunities.

\* All the terms are loosely quoted from various sources, shortened for slide simplification.

### Речь лектора
You can find these definitions all over the internet, and many of them don't suit our purposes. Here are some of them. You don't have to read them all — we'll just discuss them.

---

## Слайд 5. What is Intelligence? (три составляющие)

### На слайде
Те же определения, что на слайде 4. Ключевые слова выделены цветом по трём группам:

- **COMMUNICATION** — acquire, recognize, navigate, environment(s), question assumptions
- **UNDERSTANDING** — understand(ing), reason, process, think critically
- **ADAPTATION** — adapt, solve problems, manage, forming, make decisions, shape the world in meaningful ways

### Речь лектора
While preparing this lecture, I was looking for something these definitions have in common — something we could use as a starting point for the whole course. I decided to find the basic "pillars" of intelligence in them. If we try, we can see three basic things that appear in most (not all) of these definitions.

The first one — let's colour it blue — is everything connected to **communication**. We always acquire, recognise, navigate, question assumptions, work with the environment. It means that an intelligent object always interacts with its environment. Communication means obtaining information — data — from the environment and giving some feedback, some signal, back to it. That's the first part of intelligence.

The second part is **understanding**: understand, reason, process, think critically. This is about what you do with the data you got from the environment. You don't use it as it is — you process it to make it more usable for you or for the system you work with, to put it into a more proper form. This part will be quite important in our course.

The third part, and one of the most important, is **adaptation**. Intelligent objects adapt, solve problems, manage emotions, shape the world in a meaningful way — which is essentially the same thing as adaptation.

So in almost all of these definitions we have communication, understanding and adaptation, and this is what makes an object intelligent. I realised that these three pillars — three layers — are exactly what we build in AI during development. That's a good link between intelligence and artificial intelligence: if we view AI as a reproduction of these three pillars, we can see the whole picture of how such a system works.

---

## Слайд 6. Artificial Intelligence — Communication

### На слайде
COMMUNICATION: This part of AI addresses questions about how we сollect data, how we store it for AI purposes, what business logic underlies our decisions, and how they impact the world. This area overlaps with fields such as sensor engineering, big data management, ethics, and more.

### Речь лектора
A quick note before we continue: I'll use a few pictures throughout the course. The planet means communication with the environment — whenever our system or AI agent interacts with the environment, you'll see the planet. The robotic face is the processing layer — taking data and doing the usual operations, data preprocessing and so on. And the core part — machine learning, adaptation — is shown as this computer brain.

Back to the three pillars. The first is communication. In AI we put a lot of effort into this layer, because collecting data is one of the most important parts of AI. We don't just take information — we have to find it. Sometimes it's easy, for example from data warehouses or other computer systems; it can come in many forms — sounds, pictures and so on; and sometimes we have to deal with older formats, such as handwritten text.

This part of AI overlaps with sensor engineering, big data management, ethics (first of all AI ethics), IoT technologies and more. For example, there are smart sensors with edge processing that speed up computations, or data warehouses built for AI systems. It's a huge field, but we won't discuss it much, because it's more of an engineering area. You'll see how data is collected, but most of the data in your practical tasks will be pre-collected datasets, so we won't need to worry about this layer much.

---

## Слайд 7. Artificial Intelligence — Understanding

### На слайде
UNDERSTANDING: This area of AI can be conditionally designated for addressing issues related to data preprocessing, aimed at optimizing the data for subsequent processing by more advanced algorithms. Additionally, this section intersects with technical aspects of data delivery and ETL processes.

### Речь лектора
The next layer is understanding, which refers to data processing. Here we discuss how to process data so that it works better for adaptation. It's not enough to take data from the environment and store it somewhere — we need to process it. We build connections and workflows between data storages, data lakes and so on. That's why this field deals, on the one hand, with ETL processes and data delivery, and on the other hand with data preprocessing — taking data, transforming it into another form, iterating over it. We'll discuss preprocessing much more in this course, because it's a really important topic.

---

## Слайд 8. Artificial Intelligence — Adaptation

### На слайде
ADAPTATION: This is a key part of AI that we will be focusing on and exploring. It includes questions about how to represent information, learn, and use accumulated knowledge to solve previously unseen problems. Specifically, in this section, we will be discussing machine learning extensively.

### Речь лектора
The third part is adaptation, and it's the core of AI today. Without adaptation, we would just have a system that takes data from the environment, stores it and runs some fixed algorithm. Adaptation makes it interesting and distinctive. This part is about how we store knowledge — not data, but knowledge, something we extracted from data — and how we use this knowledge to solve new tasks we've never seen before.

Machine learning is the core of this pillar, and we'll spend about 80% of our time on adaptation. But I wanted to show you that the field of AI is quite wide: it includes engineering tasks as well as machine learning tasks, and many different jobs work for it. Our focus will be adaptation and data preprocessing.

---

## Слайд 9. Part 2 of 5 — History of Artificial Intelligence

### На слайде
Now when we've explored the components of artificial intelligence, let's examine its origins and development process.

### Речь лектора
Now let's talk about the history of AI. Many of you may say that history is boring — every first lecture starts with it. I don't want you to memorise all the dates, faces and names. You may, because I really admire the people who built all this, but that's not my goal. The main idea is to show how the field has changed over time.

Today we live in a world where AI seems super cool, it's everywhere, and it looks like it has only just started to grow. But AI has about 80 years of history, and there were periods when people thought exactly the same — that we were very close to building real AI. I want you to see how that happened and when the first AI solutions appeared. So don't be afraid of all these dates — let's just go through them.

---

## Слайд 10. Origins of Artificial Intelligence — McCulloch & Pitts

### На слайде
Walter Pitts (mathematician)
Warren McCulloch (neurophysiologist)

1943: First formal Artificial NN.

Just before the AI was originated as a field of study.

**Подписи схемы (модель нейрона):** Inputs I1, I2, I3 … IN → Weights W1, W2, W3 … WN → Σ (Sum of inputs) → Threshold T (Yes or No ?) → Output y.

### Речь лектора
The first thing I want to mention is the first artificial neuron, developed in the early 1940s. In 1943, Walter Pitts and Warren McCulloch described the first artificial neuron, shown in the picture. This happened just before AI emerged as a separate field of study. Their model is not a distant ancestor of what we have now: the main principle they described is essentially what we still use today, apart from some mathematical improvements.

The idea is that our brain consists of small cells called neurons, and these two scientists decided to model how they work. Their work can be explained through the way we make decisions. Say you're deciding whether to talk to someone. You evaluate different aspects of that person — not mathematically, of course, but something similar happens in your head. Is the person funny? Are they dangerous to talk to? Everyone has their own criteria. And we know which features matter more and which matter less: for example, it's more interesting to talk to someone funny, and less interesting to talk to someone who is angry all the time. So we accumulate these weighted features: "10 out of 10 funny, 7 out of 10 angry". If the sum leans too far towards anger, I'd better step back. This is a toy example, but it shows how the neuron works.

A neuron is connected to a set of inputs. In our models they are features; in real cells they are signals. Some inputs are more important and some less — this importance is described by weights, just as when we make a decision. After weighting the inputs — bigger weights for important ones, smaller weights for less important ones — we sum them and get a value that shows how important this information is overall. If the number is small, the neuron shouldn't react; if it's large, it should. Then we apply a threshold, which activates the neuron when the sum reaches a certain level.

It's a very simple system, and you can play with it. But in our brain it is repeated billions of times, which creates more and more complex interconnections and decisions. As a simplified mathematical description inspired by the brain, it was a new idea at the time. It was the first work in this field, and it started the whole AI era and many later AI studies.

---

## Слайд 11. Origins of Artificial Intelligence — Alan Turing

### На слайде
Alan Turing (mathematician)
1950: «Computing Machinery and intelligence»

Alan Turing introduced the concept known as the “Turing Test,” although he did not intend to create a test. His goal was to explore whether a machine could exhibit behavior similar to human intelligence, using an imitation game to discuss the possibility of machine thinking.

Person (judge) communicates via text with two participants, one of whom is a human and the other a machine. If the judge cannot confidently determine which one is the machine, it is considered that the machine has successfully imitated human intelligence.

### Речь лектора
While McCulloch and Pitts' work was more mathematical and biological, another mathematician, Alan Turing — I believe you know him — published "Computing Machinery and Intelligence" in 1950. It was a very important paper: arguably the first serious philosophical (and partly technical) paper about artificial intelligence, written before the term "artificial intelligence" even existed.

Turing wanted to discuss a simple question: can a computer think? But he understood that "thinking" is a complex notion, and you can't just write a set of rules that decides whether a computer thinks or not. So he proposed the so-called imitation game — a thought experiment: if we can build a computer that fools a person into believing it's another human, should we consider it intelligent? This idea started many, many discussions.

Based on it, the Turing test appeared and has been applied in many areas. You can even find Turing tests for ChatGPT and see whether it passes. Personally, I'm a bit sceptical about the idea: whether a computer that passes the Turing test is actually intelligent is a much wider question.

Let's look at the test. We have a judge — a person or a group of people — and an interface to a "black box", a closed room. Inside there is either a person or a computer, and it talks to the judge. If, at the end of the conversation, the judge believes they were talking to a person, but it was actually a computer, we say the machine has passed the test. There are algorithms that have done this. But we still don't really believe they are intelligent and can think — we'll come back to this later. What matters now is that Turing raised this question, and it had a huge impact on the history of AI.

---

## Слайд 12. Timeline of AI

### На слайде
**Подписи схемы.**

Эпохи по оси 1940–2020: AI origins → Inflated interest → 1st AI Winter → Expert systems → 2nd AI Winter → Explosive growth → Generative AI.

События по порядку:

- 1st neuron model
- Can machines think?
- First ANN device
- First AI program
- AI term was coined
- PERCEPTRON
- ADALINE
- DENDRAL
- ELIZA
- Artificial Intelligence: A General Survey
- Lack of computational power
- XCON Expert System
- Fifth Generation Computer Project — FAILED
- LISP machines market collapse
- Deep blue vs. Kasparov
- LSTM
- GPU for NN
- AlexNet
- AlphaGo vs Lee Sedol
- Transformers
- GPT-3
- Image prompts: Midjourney, DALL·E
- GPT-4

### Речь лектора
Now let's look at the whole history in one picture. At the bottom there is a timeline with the periods we'll discuss. Above it are points of interest — we've already covered the first neuron model and Turing's work, and we'll briefly go over the rest.

The curve shows, on the one hand, interest in AI, and on the other, how much research was done in each period — let's simply call it hype. When the curve goes up, we're in a period of inflated interest and growth, when everything was going well in AI. The two winter periods — the AI winters — were bad times for the field: they slowed progress down. Let's split the picture into pieces and go through them one by one. You don't have to read all the text on the following slides — it's there for you to read after the lecture; I'll explain everything now.

---

## Слайд 13. AI origins → Inflated interest

### На слайде
На слайде остались первые (фактические) предложения каждого пункта. Полный текст:

- **First ANN Device** - “Stochastic Neural Analog Reinforcement Computer” or SNARC. It was developed in 1951 by Marvin Minsky and Dean Edmonds. SNARC was designed to simulate a rat running through a maze, using a neural network model to learn from experience.
- **First AI Program** - The first AI program is generally recognized as the “Logic Theorist,” developed by Allen Newell and Herbert A. Simon in 1955. The Logic Theorist was designed to mimic human problem-solving skills. It was capable of proving mathematical theorems by representing them as symbolic logic expressions and searching for proofs using a heuristic search process.
- **AI Term Was Coined:** Dartmouth conference of Artificial Intelligence in 1956. The goal of the conference was to explore the idea that human intelligence could be precisely described and simulated by a machine.
- **Perceptron:** Is one of the earliest models of a neural network and plays a significant role in the history of artificial intelligence and machine learning. It was developed in 1957 by Frank Rosenblatt.
- **ADALINE:** Another significant ANN precursor - single-layer artificial neural network that uses a linear activation function. It is similar to the Perceptron but differs in how it updates its weights during the learning process.
- **DENDRAL and ELIZA:** programs that contributed to the excitement. DENDRAL was an expert system for chemical analysis, and ELIZA was an early natural language processing program.

Вне слайда: SNARC simulated a rat in a maze; the Logic Theorist proved theorems by heuristic search; the goal of the Dartmouth conference; how ADALINE differs from the Perceptron.

### Речь лектора
Around 1950 we had Turing's work — a huge philosophical step — and McCulloch and Pitts' mathematical neuron model. There were a few other works before AI officially started, and we call this period **AI origins**.

During this period, in 1951, Marvin Minsky built the first artificial neural network device, the Stochastic Neural Analog Reinforcement Computer (SNARC). It was a machine based on vacuum tubes, designed to simulate a rat running through a maze using ideas of neural networks. So even then, the first basic ideas of neural networks were already in use.

Around the same time, in 1955, the first AI program appeared — the Logic Theorist. It was designed to mimic human problem-solving skills and could do things like proving mathematical theorems by representing them as symbolic logic expressions. The whole symbolic approach to AI was born at that time.

So by 1955 we already had not just ideas about AI but some applications. That's why, in 1956, the Dartmouth conference took place. It gathered many of the brightest minds of that time, and they spent a lot of time discussing the ideas they had already developed. They didn't build any AI, robots or intelligent machines there, and the conference had no specific mathematical or engineering results. But they coined the term "artificial intelligence", which we still use today, so we treat 1956 as the year the term was born. It was a great collaboration, and after it many applications and ideas appeared during the late 1950s and early 1960s.

One of them was the **Perceptron**, which you can still find in some libraries. It was one of the earliest neural networks, and it worked — it could solve some tasks. At the same time there was **ADALINE**, which is similar but has a slightly different mathematical background: it's another artificial neural network with a linear activation, and it improved on the perceptron in the way it learned. These two models are quite close to what we use in this century — you can still find the perceptron in scikit-learn, slightly different, but the idea is still in use.

Another line of work was expert systems. **DENDRAL** was a program based on expert knowledge: its authors tried to put expert knowledge into a compact form and use it. We'll see how important these ideas became. And **ELIZA** was an early natural language processing program — again, something closely connected to what we have today.

---

## Слайд 14. 1st AI Winter → Expert systems → 2nd AI Winter

### На слайде
- **1st AI Winter.** After the Lighthill, J. Artificial Intelligence: A General Survey. Lighthill was commissioned by the UK government to evaluate the state of AI research. His report delivered a critical assessment of the field, raising doubts about the feasibility and practicality of many AI projects. Plus, lack of computational power to do anything substantial. Disappointment with researchers led to closing of funding for AI projects.
- **Expert Systems.** New idea opened a new era of AI solutions. ES-based solutions had its own market, and had many applications for real-world problems.
- **The 2nd AI Winter** was characterized by a decline in funding, interest, and overall progress in artificial intelligence research, similar to the 1st one. It occurred due to a combination of overhyped expectations, technical limitations, and economic factors.
  - Desktop computers become faster and more powerful than LISP machines. ⇒ An entire half a billion dollars industry was demolished overnight.
  - Japan's Fifth Generation Computer Project (create advanced AI-driven computers that could perform tasks like natural language understanding and logical reasoning) outcomes. ⇒ The impressive list of goals had not been met

Вне слайда: who commissioned the Lighthill report and what it concluded; the causes of the 2nd AI Winter (overhyped expectations, technical limitations, economic factors).

### Речь лектора
So at that time we had several working solutions, but you can already see the curve going down. Why, if it looked like we were at the top and solving real problems?

There were several reasons. The first, and the most real one, was this: the mathematical foundations and even some of the solutions were fine, but we didn't have enough computational power to build real-world applications. All those applications were toy examples. If I remember correctly, there were even experiments with reading text and recognising handwritten digits. But nothing could be used in practice or bring a lot of money. So the basic problem was computation.

At the same time, the UK government asked James Lighthill, an expert, to write a survey, "Artificial Intelligence: A General Survey", to evaluate AI research in the UK. His report was quite pessimistic. He said there were a few works and ideas that could be applied in narrower settings, but most research was far from practice and couldn't be applied, and he recommended not investing in AI research any further. So the UK government stopped funding, and most of the world followed. That's how the first period of AI hype ended badly for the field, and we entered the **first AI winter**, starting in the early 1970s. Many neural network papers were put on the shelf.

But not expert systems. After less than a decade, people remembered expert systems. That's when the XCON expert system was created. In general, we found another way to implement artificial intelligence, and it was much more practical. After this winter we set neural networks and perceptrons aside, focused on expert systems and created a huge market for them. During the period shown here there were many real solutions based on expert systems: they were integrated with databases and solved real-world problems. It was the period of the first real-world AI solutions that made money.

But again, problems led us to the **second AI winter** — as you can see, expert systems didn't stay on the market for long. One core problem was this: riding the wave of hype, Japan decided we were ready to build a truly intelligent computer and launched a programme. There were many programmes like this around the world, but this was one of the biggest, and it started right during the hype. It was a huge investment in creating an AI-driven computer that could perform most tasks — natural language understanding, logical reasoning and so on. They planned to build it in ten years, but in ten years this impressive list of goals had not been met. That was one of the triggers of the second AI winter: this programme failed, other programmes failed too.

Another problem was, again, computation: desktop computers became faster than LISP machines, which were tightly connected to expert systems. The whole market of expert systems and LISP machines collapsed very quickly, and investment left the field. Today we still have a few expert systems, but they are niche solutions, and there aren't many of them.

As you can see, both times people were happy with what they had in AI. Some governments believed we would soon build an AI-driven solution — and, going back to the Dartmouth conference, scientists of that time thought they were close to general AI, some huge AI-driven supercomputer. Twice we were wrong, and that's why we had two AI winters. But as you can see, today we have a lot of AI solutions — the winters didn't stop progress. Let's see why.

---

## Слайд 15. Explosive growth → Generative AI

### На слайде
Deep Blue vs. Kasparov (1997): IBM's Deep Blue defeats world chess champion Garry Kasparov, marking a significant AI milestone.

Explosive Growth (2000s - 2010s):

- GPU for Neural Networks: GPUs revolutionize deep learning by providing the computational power needed for training complex models.
- AlexNet (2012): AlexNet's victory in the ImageNet challenge brings deep learning to the forefront of computer vision.
- AlphaGo vs. Lee Sedol (2016): AlphaGo's win over Lee Sedol demonstrates the power of reinforcement learning and deep neural networks.

Generative AI Era (2010s - 2020s):

- Transformers (2017): The Transformer architecture revolutionizes natural language processing.
- GPT-3 (2020): OpenAI's GPT-3 sets new standards in text generation with 175 billion parameters.
- Image Prompts: Models like DALL·E and Midjourney enable the creation of images from text prompts, opening new creative possibilities.

### Речь лектора
After the second AI winter, some scientists kept working, and everything changed with a huge milestone: chess. In 1997, IBM's Deep Blue — not a neural network in today's sense, but a program — beat Garry Kasparov, the world chess champion. That was unbelievable. Today it may sound like "so what?", but back then chess was considered *the* intelligent game. It still is, but our idea of "intelligent" has changed. It seemed impossible that a computer could win, because only humans could play chess. It was a milestone that showed we had found something worth investing in, and that's when the field started to grow again.

Not immediately, of course, but after this match many new ideas came up. For example, LSTM — a neural network architecture we'll see later. Many other smaller algorithms appeared too; I won't list them now so as not to overload you. What really boosted the field was the use of **GPUs for neural networks**, around 2010. We realised we could train neural networks much faster and get better quality. That was another important milestone.

Another one was **AlexNet** — a milestone in computer vision. Its victory in the ImageNet challenge, an image classification competition, showed that deep learning works especially well in computer vision. Many other algorithms not related to neural networks — tree-based models, random forests and so on — also developed then, but they're not important for the story I'm telling. The main point is that during this explosive growth, many AI and machine learning solutions entered our everyday lives — they're in our smartphones, laptops and so on. Here you can see the most important milestones.

So now we live in a world where AI is everywhere and at the top of the hype. But we've entered a new era, the **generative AI era**. Here I'm speaking more from my own point of view, because it's not a generally accepted term — we don't really know whether this era exists; time will tell. What we can say is that after 2017, when the core algorithm behind LLMs (the Transformer) was developed, the way we build AI solutions in computer vision and NLP changed drastically. We no longer use many of the old algorithms, and generative AI plays a huge role. Whether this change is really that drastic is debatable — we'll discuss it in the lecture on generative AI. For now, it's enough to say that we don't know whether we'll keep growing, go down again, or grow explosively. We'll come back to this when we get closer to LLMs in our lectures and practice sessions.

---

## Слайд 16. Hype Cycle for AI in 2023

### На слайде
На слайде теперь большой график и справа пять пар «фаза → ключевая технология». Полный текст пояснений:

- **Innovation Trigger (Beginning of Innovation):** Neuro-Symbolic AI is a popular technology at this stage, currently in the early research and concept phase.
- **Peak of Inflated Expectations:** Generative AI is the most popular technology at this stage, with high expectations for its potential.
- **Trough of Disillusionment:** Synthetic Data is the most discussed technology at the stage of declining interest, as its results have not yet met expectations.
- **Slope of Enlightenment:** Cloud AI Services is a technology that is starting to gain wide recognition and application.
- **Plateau of Productivity:** Computer Vision is a technology that has already reached the productivity stage and is widely used in various fields.

**Подписи схемы.** Plateau will be reached: less than 2 years / 2 to 5 years / 5 to 10 years / more than 10 years. Технологии на кривой, слева направо:

- Automatic Systems, First-Principles AI, Multiagent Systems, Neuro-Symbolic AI
- Causal AI, AI Simulation, AI Engineering, Data-Centric AI, Composite AI, Operational AI Systems
- AI TRiSM, Decision Intelligence, Artificial General Intelligence
- Prompt Engineering, Neuromorphic Computing, Responsible AI, Smart Robots, Generative AI, Foundation Models
- Synthetic Data, ModelOps, EdgeAI, Knowledge Graphs, AI Maker and Teaching Kits
- Autonomous Vehicles, Intelligent Applications, Cloud AI Services, Data Labeling and Annotation, Computer Vision

Source: Gartner, Hype Cycle for Artificial Intelligence, July 2023.

### Речь лектора
That was a big part about history. Let's finish it with the current situation. Here you can see the Gartner Hype Cycle for AI, 2023, which is quite close to what we have today. If you haven't seen this kind of chart before: it's a survey of how much hype surrounds technologies in a particular field.

The chart has several zones. The **innovation trigger** contains technologies that are just starting to grow. The **peak of inflated expectations** contains technologies that are everywhere right now, with a lot of hype around them. Then comes the **trough of disillusionment**: after the peak and a lot of investment, people start using these technologies, the hype goes down, and we understand where the real limits of applicability are. Because of this disillusionment, we become more sceptical. If the technology is good, we move up the **slope of enlightenment** and start to see real profit, not just hype. Over time we reach the **plateau of productivity**, where the solution just works, is integrated everywhere and becomes an ordinary application.

You can see that generative AI is now the most hyped technology, together with prompt engineering, which is closely connected to generative AI and LLMs. So we may soon see generative AI slide down into the trough of disillusionment, and then we'll find out how good it really is and in how many areas it can be applied. On the other hand, computer vision is a relatively old part of AI, widely used in many applications — that's why it's on the plateau. You can go through the chart yourself if you're interested in this kind of analysis.

One more thing: you can see artificial general intelligence here — the thing we've been trying to build since the very beginning of AI. Now there is a new wave in this area, but it's still at the innovation trigger stage, and we'll see how it develops over time.

---

## Слайд 17. Part 3 of 5 — Strong vs Weak AI

### На слайде
In fact, the entire history of AI development can be viewed through the lens of trying to understand what kind of AI we want to create. Over time, two main concepts have emerged: strong AI and weak AI.

### Речь лектора
Now that we've discussed the history and its main points, let's generalise. You saw this curve I drew: AI went through winters, the hype went down, and sometimes it went up, as with expert systems. But there's another point of view: maybe these weren't really big drops and rises in the value of AI — we were just on our way to understanding what we actually need. And that's where we face the question of **strong versus weak AI**. The idea is that the whole historical path may have been a move from developing strong AI to developing weak AI. Only now are we starting to think about strong AI again, and there are still many questions to answer.

---

## Слайд 18. Strong (General) AI

### На слайде
Strong AI, also known as Artificial General Intelligence (AGI), refers to the concept of a machine that possesses the ability to understand, learn, and apply intelligence across a broad range of tasks at a level comparable to or exceeding human capabilities.

The ideas of creating strong AI were most developed in the 1950s and 1960s.

However, by the 1970s and 1980s focus shifted to the development of narrow AI.

Nowadays, discussions about strong artificial intelligence are gaining new momentum due to the success of large language models.

### Речь лектора
What's the difference? Strong, or general, AI is the idea that the machine we want to build should be capable of a huge range of work — from playing chess to reading texts, communicating and so on. It's about creating human-like algorithms and systems. Today we're not close to that, and we don't even know whether it's needed — there are several schools of thought, which we'll discuss.

The only candidate we have is large language models. They're not unique, but they are "stronger" than other weak models — though still far from strong AI. Maybe that's the path, and we'll get there.

---

## Слайд 19. Weak (Nerrow) AI

### На слайде
Narrow AI, also known as Weak AI, refers to the concept of a machine designed to perform a specific task or a narrow range of tasks with high efficiency, without possessing general intelligence or the ability to perform tasks outside its programmed domain.

Since 80s, narrow AI has seen significant advancements, becoming integral to various industries through applications like speech recognition, image processing, and recommendation systems.

Now we live in the world which use narrow AI much, I this is exactly the one AI we will learn in our next lectures.

### Речь лектора
The difference between general AI, which we still don't have, and the AI we use now — the one we'll spend about 80% of the course on — is this. Over time, we decided that we don't need one huge brain to solve all tasks. We need many small artificial intelligences, each good at its own specific task. So we came to the idea of training models, including neural networks, for specific tasks — and that's what we have now.

The idea of weak AI was really important. Today these small, weak, narrow AIs live in our laptops, smartphones and so on, and they solve many tasks: forecasting, driving cars, classification and more. So we live in a world of narrow AI.

And now the question is: do we need to create strong AI at all? Maybe strong AI is just a huge narrow AI — or is there a task that cannot be solved by weak AI? We used to think chess could not be solved without intelligence, and now it's solved. We thought car driving would never be solved, and now we have it. So there are many open questions here, and even very strong scientists don't share one common understanding.

---

## Слайд 20. Different schools of thoughts

### На слайде
Таблица (✓ — да, ✗ — нет):

| | Dan Dennett & David Chalmers | John Searle | Roger Penrose |
|---|---|---|---|
| **Strong AI** — Can a computer fully simulate consciousness? | ✓ | ✗ | ✗ |
| **Weak AI** — Can a computer fully emulate consciousness? | ✓ | ✓ | ✗ |

### Речь лектора
There are different schools of thought. Dan Dennett and David Chalmers believe in the distinction between strong and weak AI. It doesn't really matter here who exactly these people are — I just picked respected thinkers who believe in this distinction. That's the optimistic view.

On the other hand, there's Roger Penrose, a Nobel laureate, who is sceptical about the whole idea of strong and weak AI. He believes "AI" is just the name for tasks we can't solve yet: once we solve them, we no longer see them as AI. We'll discuss this a bit later.

But now I want to focus on John Searle's idea that we cannot create strong AI the way we want to, and we can only work with weak AI. I really like this idea — it's quite close to my own view. I'm not saying it's the ground truth; you can make your own decisions. But it describes the context of the AI field well and points to a real problem: people invest in AI thinking it's something magical, while it's just mathematics. I want you to feel this and maybe use it in your future work.

---

## Слайд 21. Chinese room argument

### На слайде
John Searle (philosopher)
1980: «Minds, Brains, and Programs»

Thought experiment proposed by philosopher to challenge the notion of “strong AI” which claims that a computer running a program can have a “mind” and “understand” in the same way humans do.

In the experiment, a person who doesn't know Chinese uses a rule book to match Chinese symbols to produce responses, without understanding the language. Searle argues that, similarly, even if a computer can process language and provide appropriate outputs, it doesn't mean it actually understands the content.

**Подписи на иллюстрации:** Program instruction · Hello · 你好

### Речь лектора
This idea is called the **Chinese room argument**. John Searle is a well-known critic of strong AI. He says that we can only create weak AI, and strong AI is not something a computer can run, because we cannot represent minds — we cannot even check whether a computer understands something or not. He doesn't say we shouldn't work on it; his point is rather: we don't know what general AI is, so let's continue with weak AI.

He invented a great thought experiment, somewhat similar to Turing's test. Let's walk through it. Imagine a kind of imitation game. Outside there is a person who speaks Chinese. They pass a message written in Chinese into a room, and someone inside the room has to answer it in Chinese. From the outside, it looks like whoever is in the room understands Chinese and gives correct answers.

But imagine that inside there isn't a Chinese speaker, but a person with a huge book of program instructions: which symbols to output for which symbols — say, how "hello" maps to this character. This person does the job mechanically, without understanding anything they do: they just take instructions from the book and follow them.

So we can get a perfect imitation without any work of a mind. If we build a system that reproduces any sentence we like, and even convinces us it's human, we still can't say what's inside — something like a human mind, or just a set of instructions. That's the problem — not a technical one, but a question of where to go further. I really love this thought experiment, because it makes you think about the whole strong versus weak AI problem. I hope you'll find it interesting too.

---

## Слайд 22. “AI Effect”

### На слайде
Only humans can play chess → Deep Blue beats Garry Kasparov (Major milestone in AI development) → Was it even an intelligent task?

The “AI Effect” refers to the phenomenon where, as AI technology becomes more commonplace and its capabilities are better understood, people tend to dismiss the accomplishments of AI as simple or “not real AI.” Essentially, once an AI system can do something that was previously thought to require human intelligence, that task is no longer considered a benchmark of AI.

### Речь лектора
The last thing in this part is not exactly strong versus weak AI, but the so-called **AI effect**. It's close to the ideas of Roger Penrose — he didn't invent it, but it's close to what he writes — and I think it's even more important than the Chinese room.

Let's start with an example — Garry Kasparov and Deep Blue. Before the match, we thought: only humans can play chess, humans are intelligent, only they can solve this task, we can't program it. Then Deep Blue beats Kasparov — a major milestone in AI development. But a few years later we start thinking: was it even an intelligent task? Maybe it wasn't that intelligent after all, since we solved it. Deep Blue wasn't truly intelligent: it was a lot of rules, without modern approaches.

From this perspective, the AI effect is the phenomenon where, as AI technology becomes more commonplace and its capabilities better understood, people dismiss its accomplishments as simple or "not real AI". That's what we usually do. Car driving, again: we thought it was a real general AI task; now we have it, and it's solved without general AI. Same with AlphaGo. And that's the trick: we don't really know whether the tasks we now consider intelligent really are. Maybe we'll build a completely human-like robot that does everything we need intellectually, and after a while we'll say: "That's not intelligence. We're intelligent, but this — now we know how it works, it's just mathematics."

I don't want you to think I have strange theories that someone is trying to fool us — absolutely not. I want you to be realistic and not follow the hype: AI terms and names can sound beautiful, but inside there are many things you can argue with and think about. That's why we have different schools of thought. Even the AI effect can be interpreted differently: some people say "AI doesn't exist at all", others say "it exists, but we overestimate it and overthink it". It's up to you.

---

## Слайд 23. Part 4 of 5 — Machine learning in AI

### На слайде
Machine learning has become a cornerstone in the realm of artificial intelligence today. Let’s dive deeper into what it entails. But first, let’s strip away all the extraneous elements.

### Речь лектора
We're done with the half-philosophical part, and now we're ready to talk about machine learning, data science and more practical things — how we actually solve AI tasks. Machine learning is the core of AI, and as I said at the beginning, it's what we'll discuss the most.

---

## Слайд 24. AI structure

### На слайде
**Подписи схемы.** AI → ML (ядро). Вокруг ядра — другие области AI: Expert systems · Devices engineering · Data Processing · Robotics · AI Ethics · AI Philosophy · Non ML CV · Non ML NLP.

### Речь лектора
Before we go deeper, I want to clarify the role machine learning plays in AI, because many sources put an equals sign between AI and machine learning. In general, you can do that: because of the hype, nobody really thinks about AI as a whole now, and most people are looking for machine learning specifically.

But if we cut pieces off AI until only machine learning is left, we'd cut off: expert systems — still AI, a sphere that's not so big now, but still exists; parts of device engineering, which intersect with AI; data processing, which we'll cover; robotics; AI ethics, a huge part of AI, which we may touch on later; non-ML NLP and computer vision solutions — they exist, though there aren't many of them now, because ML-based solutions are better in many ways; and AI philosophy, which also intersects with machine learning.

It's hard to say exactly which of these parts are inside AI and which only intersect with it — that's partly my opinion. But AI is not just machine learning: there are many other solutions that can be called AI. If you want to be an AI expert, it's good to know some of them, even if you never use them. Still, machine learning is the core thing we use in most applications today, and it's what we'll mostly talk about in our lectures and practice sessions.

---

## Слайд 25. ML vs Programming

### На слайде
- INPUT + PROGRAM / MODEL / ALGORITHM = OUTPUT
- INPUT + OUTPUT / GOAL = PROGRAM / MODEL / ALGORITHM

Programming - Program some predefined dependency between input and output. Understanding of the process comes before the realization and coding.

Machine Learning - Develop the algorithm which will define dependency between input and output. In such approach we usually do not understand process before modeling.

### Речь лектора
We'll talk a lot about machine learning in the next lecture, but today I want to give a brief introduction to help you see where we are. What's the difference between machine learning and programming? It's a big question, and it's good to clarify it from the start.

Think of how you create a program as a developer. Usually there's an algorithm — written by you, a customer or an analyst — and you implement it in code based on what's written down. Sometimes not everything is specified precisely: you can choose which library or which sorting algorithm to use. But you still know what the algorithm should do. Once you've built this blue box, you put input values in and get output values out.

In machine learning, the problem is that you usually don't know the algorithm — you can't just sit down and program it; you need to obtain it somehow. But in such tasks we have a lot of data: we know the inputs and outputs of the task we want to solve. So we combine inputs and outputs — or inputs and a goal, if we're talking about unsupervised learning — and from them we derive the algorithm, the program. Sometimes you can't solve a task with programming simply because you don't have a description of what you want to solve. The hard work is combining inputs and outputs in a way that gives you a good model. In the next lecture we'll dive into the mathematics and see how this problem can be described and solved.

---

## Слайд 26. Main concept

### На слайде
- **FIT** — Model learns from data by identifying patterns during training. This phase builds the model's ability to understand and represent the data.
- **PREDICT** — Trained model applies its learned patterns to new data, generating insights or making decisions based on its training.

### Речь лектора
Another important concept is **fit and predict**. The models we'll work with have two modes. The first is fitting, or training. It's exactly what it sounds like: you fill your model with knowledge — we'll learn how — by feeding it a lot of data, and the model becomes smarter.

Then, once the model is "full" — not a real term, but let's play with it — you can use this trained model on new inputs to get new results. We'll learn how to do this, what a trained model is, how to evaluate whether it's trained well, and so on. The next two lectures will be mostly about this process — how we go from nothing to some intelligence.

---

## Слайд 27. Black box problem

### На слайде
Refers to the lack of transparency in how complex models, especially deep learning algorithms, make decisions.

While these models can achieve high accuracy, they often do so without providing clear explanations for their outputs, making it difficult for users to understand or trust the results.

This opacity raises concerns about accountability, bias, and fairness, especially in critical applications like healthcare or finance, where understanding the decision-making process is crucial. Addressing the black box problem involves developing methods for interpretability and explainability without sacrificing model performance.

Вне слайда: последний абзац (accountability, bias, fairness; interpretability и explainability).

### Речь лектора
There's a lot of text here, but as usual you don't have to read it — I'll explain. The black box problem is one of the most widespread problems in machine learning. You can build an algorithm — this brain — but when you open it, you often can't understand how it solves your task. There's no transparency: in complex models you just see a set of numbers that somehow gives you a good solution.

There are ways to deal with this, such as SHAP values and feature importance, and we'll learn them. But the problem remains. Going back to the previous slide: after training, you often don't know the algorithm. You only have a program that, when you open it, just multiplies some numbers by others and gives you an answer — like an LLM. And you think: "I have no idea how it works." That's a problem for business, which sometimes can't use such knowledge. For a manufacturer, for example, it's important to understand why values are predicted the way they are. We'll learn how to work with this.

---

## Слайд 28. ML Structure

### На слайде
**Machine Learning**

- **Supervised Learning**
  - Classification: Image Classification, Customer Retention, Diagnostics, Fraud Detection
  - Regression: Forecasting, Predictions, Process Optimization, New Insights
- **Unsupervised Learning**
  - Dimensionality Reduction: Structure Discovery, Feature Elicitation, Meaningful Compression, Big Data Visualisation
  - Clustering: Recommended Systems, Targeted Marketing, Customer Segmentation
- **Reinforcement Learning**: Real-Time Decisions, Robot Navigation, Game AI, Skill Acquisition, Learning Tasks

### Речь лектора
This whole part is a kind of pre-read for the machine learning lecture. I just want to give you some points of interest to remember and link to future lessons. In machine learning there are different types of learning — supervised, unsupervised and reinforcement — and we'll see how they differ; don't dive deep yet.

One thing I want to say now, so I don't have to come back to it: on the internet you'll find articles about "11 types of machine learning" or even more. I'd say there are only three. Even generative AI is a kind of subtype that combines all of them in some balance. All those "11 types" are combinations of these three. So don't be fooled: if you master these three, which we'll try to do, that's enough. We'll see a more detailed description of each next time.

---

## Слайд 29. Place of Generative AI — Discriminative vs Generative

### На слайде
**Подписи схемы:** Discriminative AI · Generative AI.

### Речь лектора
One last thing: there's a difference between generative and discriminative AI, and you can see it intuitively in the picture. Of course, it takes more than one picture to explain, but in short: discriminative AI gives you an algorithm that separates data, while generative AI creates new points from the distribution it has learned. They may look very different, but at the core they're quite close to each other. And, as I said, generative AI combines the others — supervised, unsupervised and reinforcement learning.

---

## Слайд 30. Place of Generative AI — learning paradigms

### На слайде
**Подписи схемы:** Supervised learning · Unsupervised learning · Reinforcement learning · Generative AI (на пересечении).

### Речь лектора
To show the balance between these types of learning: the biggest one, maybe 70% or more of the market, is supervised learning. Reinforcement learning is just a tiny piece, because it's a very specific field. Generative AI and unsupervised learning are about the same size, but generative AI is growing faster because of the hype.

I forgot to mention: the inner circle shows the market for each technology, and the outer circle shows how much it has grown in recent years, since generative AI started to grow. Supervised learning keeps growing as before, generative AI grows faster, unsupervised learning keeps working, and reinforcement learning stays tiny, at the same level as it has been for a few years.

---

## Слайд 31. Part 5 of 5 — Data Science

### На слайде
Ok, but you can ask, why do we speak about AI all this time, but not about Data Science? To clarify this, let’s generalise all the information we have gained and point out the similarity and difference between AI and DS

### Речь лектора
Finally, we come to data science. You may ask: why have we been talking about AI all this time, and not about data science, which is the topic of our course? Let's generalise what we've learned and point out the similarities and differences between AI and data science. It's important, because there are three terms — AI, machine learning and data science — and I don't want you to treat them as the same thing.

---

## Слайд 32. AI-adjacent fields

### На слайде
**Подписи схемы:** Data Science (в центре) · Big Data · Statistics · Math · Programming · Business Logic · Data Analysis.

### Речь лектора
Here you can see the structure of AI-adjacent fields. As I said, AI includes a layer of tasks for data processing, robotics and so on, and the core part — machine learning. Neural networks are one of the subtypes of machine learning algorithms, and we'll study them specifically.

Two fields intersect strongly with AI: data science and big data. Big data is about how we work with huge amounts of data, which is crucial for today's LLMs and AI in general. Data science is a different field: it intersects with AI mostly through *using* it. Data scientists usually don't create new AI algorithms; they need to understand how AI works, how to use it and in which situations. They also need to know how to work with big data — but again, they don't create new big data technologies.

So a data scientist has a more applied role: you apply a broad skill set — AI, big data, statistics, maths, programming, business logic and data analysis — to solve tasks. That's what data scientists really do. Not all of it is as modern and exciting as AI, and AI and machine learning are especially helpful — that's why people sometimes equate data science with machine learning. But for a data scientist it's really important to have data preprocessing and analysis skills, so we'll show you some of that in this course. Still, we'll focus mostly on machine learning, because today you can't be a data scientist without it.

---

## Слайд 33. DS vs ML

### На слайде
**Data Science**
Field that determines the processes, systems, and tools needed to transform data into insights to be applied to various industries.
Skills needed: Statistics · Data visualization · Coding skills (Python/R) · Machine learning · SQL/NoSQL · Data wrangling

**Overlap**
Machine learning is part of data science. Its algorithms train on data delivered by data science to “learn.”
Skills needed: Math, statistics, and probability · Comfortable working with data · Programming skills

**Machine Learning**
Field of artificial intelligence (AI) that gives machines the human-like capability to learn and adapt through statistical models and algorithms.
Skills needed: Programming skills (Python, SQL, Java) · Statistics and probability · Prototyping · Data modeling

### Речь лектора
Another question: what exactly is the difference between data science and machine learning in terms of what we do at work? As you see, they intersect, as on the previous picture. Data science is the field that determines the processes, systems and tools needed to transform data into insights applied in various industries — we apply ML-based tools, and not only them. Machine learning is the field of AI that gives machines a human-like ability to learn and adapt through statistical models and algorithms. I don't really like the "human-like" part — as we discussed, we don't really know whether it's human-like or not.

Here, machine learning is shown as a part of data science — its applied part: its algorithms train on data delivered by data science. Data scientists are people who use machine learning algorithms to build systems and find insights. There's another role — the machine learning engineer — and these people create new machine learning algorithms. That's a narrower role: there are fewer ML engineers than data scientists, especially in my field, because we mostly use existing models. But it differs a lot between companies, because employers name these roles differently.

---

## Слайд 34. DS Stack

### На слайде
Группы инструментов (логотипы):

- Big data stack — Spark, Hadoop
- Data Operations — NumPy, SQL, pandas
- ML Algorithms — PyTorch, CatBoost, XGBoost, LightGBM
- Neural networks — TensorFlow, Keras
- Visualisation — Matplotlib, Plotly
- Languages — R, Python
- ML general — scikit-learn

### Речь лектора
Finally, here's the stack of technologies data scientists use when working with data. It relates to what you'll see in your first practical task — you'll work with some of these libraries. I want this slide to be a cheat sheet you can come back to, to remember which technology belongs to which area of data science and ML.

You'll mostly use **scikit-learn**, a general machine learning library with lots of useful approaches. We'll mostly write in **Python**; **R** is used more for analysis, but in our practice sessions we'll use Python. For visualisation, the basic library is **Matplotlib**, and **Plotly** is a more advanced one. For neural networks — **TensorFlow, Keras or PyTorch**. Specific machine learning algorithms, such as **CatBoost, LightGBM and XGBoost**, are non-neural-network algorithms. The big data stack is **Spark** or **Hadoop**; Spark is the usual choice. And the core thing you'll start with in the next practice session is **pandas**, along with **NumPy** and **SQL** as a query language — data operation tools.

That's the skill set you need to start — maybe even a bit less. As you see, you use big data technologies, data operations, statistics and mathematics, neural networks, machine learning algorithms and general ML tools. All of this is the skill set of a data scientist. Our goal is to improve your skills in AI — mostly in machine learning — to enrich your data scientist skill set, and maybe give you some ideas about technologies like big data. We'll talk about all of this in our lectures.

---

## Слайд 35. Финал

### На слайде
That's all for today, thank you for your attention.

### Речь лектора
That's all from my side for today. Thank you for your attention — I hope it was useful and the history part wasn't too boring. Good luck! Next time we'll discuss machine learning, and it will be a more mathematical lecture, so be prepared. See you!
