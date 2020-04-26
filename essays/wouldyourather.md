---
layout: essay
type: essay
title: Ethical Would You Rather...
# All dates must be YYYY-MM-DD format!
date: 2020-04-25
labels:
  - Software Engineering
  - Ethics
  - Philosophy
---

<img class="ui medium centered image" src="/images/ethics.jpg">
<hr>
## The Moral Dilemma

Imagine this: You are at a restaurant and you notice your friend’s wife on what seems like a date. 
Should you tell your friend and possibly ruin his marriage? Or, should you turn a blind eye?

While considering how you would react, it may help to imagine the ripple effect your decision may make.
In [Schrodinger's cat thought experiment](https://news.berkeley.edu/2014/07/30/watching-schrodingers-cat-die/),
the cat is both dead and alive at the same time while it is in the box, but when you open the box, you kill the cat.
Following the same logic, since you don’t know if your friend's wife being unfaithful or not, you may “kill the cat” by telling your friend. But what if not telling your friend leads to worse heartache down the line? Perhaps there is hubris in the idea that something does not exist if you don't profess it. 

Nevertheless, this is a very sticky moral dilemma; there are pros and cons for each choice. The choice and reasoning you ultimately decide on demonstrates your sense of ethics. If you follow the Association for Computing Machinery 
[Code of Ethics](https://www.acm.org/code-of-ethics), you may decide to tell your friend because you value
honesty and trustworthiness.
If you are a moral realist that believes there are moral facts, any moral proposition is either true or false. The [universal modus ponens](https://en.wikipedia.org/wiki/Modus_ponens)
rule of inference can be used to demonstrate the proposition below

- Lying is wrong. 
- If you omit the truth, then you are lying.
- Therefore;
- Omitting the truth is wrong. 

<hr>
## The Ethical Software Engineer

I would argue that being ethical and following morals is important in nearly all decisions a person will have to make, but personal ethics are highly subjective. So, a universal code of ethics must be used 
professionally, in software engineering this is the [Software Engineering Code of Ethics and Professional 
Practice](https://www.computer.org/education/code-of-ethics). This isn’t necessarily a set of commandments,
it is more so a guide to help you make ethical professional decisions. 

Ethics usually means the same thing
no matter the context, ethics are moral principles that govern a person's behavior or the conduct of an activity.
Some moral principles of an ethical software engineer are to; never advertently or inadvertently cause harm to the public, their clients, colleagues, and employers, and always create products of the best possible standards.
This code of ethics is created for software engineers, but it can be used in other places in your life as well; as was demonstrated in the thought experiment above.

<hr>


## Ethical Analysis of a Hypothetical Situation

For the sake of this analysis, I am a software engineer on a team that is tasked with developing the 
navigation algorithm for a self-driving car, and I want to follow the standards of the [ACM Code](https://www.acm.org/code-of-ethics) and the [SE Code](https://www.computer.org/education/code-of-ethics). First, I consider all the possible negative impacts of
my computing. My navigation algorithm will take in a lot of sensitive data; photographs and video recorded may contain sensitive information of bystanders or my client,  and location information of the car may reveal my clients' “usual” routes. If my navigation algorithm is accessed by someone unauthorized, they could potentially take control of the vehicle and cause a great deal of unjust harm to my client, the public, and property.
A vehicle can be a destructive weapon in the wrong hands, it must be extremely secure. To minimize death or injury in an unavoidable accident, I must follow the generally accepted best practices, unless there is a compelling ethical reason to change it. 

<hr>

## What would I do?
My personal opinion as to the ethical stance to be taken is a bit complicated.
Storing the sensitive data would be necessary, that data could be used to assist the passenger, and improve the safety and efficiency of the algorithm. As long as the correct precautions are implemented to maintain complete confidentiality of all sensitive data, and only collect the minimum amount of personal information necessary, I would be respecting privacy and maintaining morality. 

### The Unavoidable Accident
<img class="ui large centered image" src="/images/Trolley_problem.png">
There is no “right” answer for the question of handling an unavoidable accident. 
Vehicles are often marketed by how safe they keep the people inside the vehicle, not how little 
damage they will do to people outside of the vehicle. But thankfully it is not my job to market the vehicle in this hypothetical.  The [Trolley Problem](https://en.wikipedia.org/wiki/Trolley_problem) thought experiment models a very similar ethical dilemma as the vehicle model. In the Trolley Problem, there are two options, you either interfere or don't interfere. According to the [Utilitarian view](https://www.britannica.com/topic/utilitarianism-philosophy) you must interfere to save the five people, it is not only obligatory but the most moral option. On the other hand, the [deontological ethics](https://www.britannica.com/topic/deontological-ethics) is of the view that action itself must be judged based on being right or wrong alone, without consideration for consequences, so if you interfere you caused the man to die. 

<img class="ui large centered image" src="/images/AIdiagram.png">

The unavoidable accident that my algorithm has to face has no option to not interfere. The algorithm created by my team must make a decision and I believe the most ethical decision is to cause the least amount of harm possible, even if this means killing the passenger. The vehicle can be made as safe as possible to protect the passenger, but pedestrians and bystanders have nothing to protect them. There is an idea stated in [this](https://arxiv.org/pdf/1510.03346v1.pdf) study that the public participates in a survey and the method most favored by the public is the one that will be implemented. I think this is an ethical choice as it acknowledges that the people are all stakeholders in computing, but to be perfected it must take the needs of the less privileged into account. The idea that the vehicle makes a different decision based on whether a passenger is young or old is EXTREMELY unethical, it is discriminatory and it implies some lives are worth more than others.
	
<hr>

