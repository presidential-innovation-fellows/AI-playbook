# The Artificial Intelligence Playbook

## A guide for assessment and buying

September 8, 2019

By [Justin Koufopoulos](mailto:justin.koufopoulos@gsa.gov), [Jeffrey Starr](mailto:jeffrey.starr@pif.gov), and [Gil Alterovitz](mailto:gil.alterovitz@va.gov)

Presidential Innovation Fellows, Technology Transformation Service, General Services Administration



## Table of contents

- [Introduction](#introduction)
- [Identifying your problem and evaluating the approach](#identifying-your-problem-and-evaluating-the-approach)
	- [Identify the problem](#identifying-the-problem)
	- [Bring experienced teams in-house](#bring-experienced-teams-in-house)
	- [Know your data](#know-your-data)
	- [Continuously test and evaluate prototypes](#continuously-test-and-evaluate-prototypes)
- [Culture and Education](#culture-and-education)
	- [Manage key risks, including resistance](#manage-key-risks-including-resistance)
	- [Assess and manage ethical concerns](#assess-and-manage-ethical-concerns)
	- [Build support and educate senior stakeholders](#build-support-and-educate-senior-stakeholders)
- [Run your pilot](#run-your-pilot)
	- [Have a clear plan](#have-a-clear-plan)
	- [Create standards for measuring the performance of models](#create-standards-for-measuring-the-performance-of-models)
	- [Know and follow the relevant laws to your project](#know-and-follow-the-relevant-laws-to-your-project)
- [Post pilot: Now what?](#post-pilot-now-what)
	- [Consider the long-term investment strategy](#consider-the-long-term-investment-strategy)
	- [Lay the seeds for future experimentation](#lay-the-seeds-for-future-experimentation)
- [Appendix](#appendix)
- [Case Study](#case-study)


## Introduction

[Artificial Intelligence](https://science.sciencemag.org/content/357/6346/19) (AI) has the potential to help government agencies. There are many different types of AI. Our playbook is mostly referring to machine learning, where algorithms find patterns in data without explicit instruction. AI can help agencies automate manual, labor intensive tasks. Searching databases, understanding language, labeling text and images, and identifying patterns that can be difficult for humans to do without considerable time and training are very common problems that AI may be able to help with.

This playbook is for government leaders considering AI as a solution to a technical problem they are facing. Our plays were derived from studying lessons learned from Federal agency AI IT projects. 

Readers will learn how to manage many of the key risks inherent to an AI project including:

- Identifying whether the problem really is a fit for AI
- Hiring and team-building
- How to run an AI pilot
- Steps to consider post-pilot

While we believe anyone can get value from this resource, we wrote this playbook specifically for senior government technology leadership and project managers beginning to consider AI as a potential solution. Our playbook is focused on piloting versus scaling to many users. Therefore we are less focused on addressing important issues like legacy technology and security.


### About the authors

We are [Presidential Innovation Fellows](https://pif.gov/), part of the Technology Transformation Services team at the [General Services Administration](https://www.gsa.gov/) (GSA). Collectively, the three of us have many years of experience in organizational design, software development, and artificial intelligence.

In work funded by GSA’s [10x](https://10x.gsa.gov/), we spent a year exploring the state of artificial intelligence in the federal government, what barriers to adoption existed, and the relationship between artificial intelligence and the federal workforce. During our research, we spoke with numerous statisticians, computer scientists, and data scientists trying to deliver better services, drive down the human cost of onerous tasks, and save lives. We also spoke with many leaders at the federal level including Chief Information, Technology, and Data Officers. We are extremely grateful to their help in creating this playbook.

## Identifying your problem and evaluating the approach

AI is not an all-purpose solution. AI is another tool to help agencies meet their missions. For designing any service, always begin with user needs. 

### Identify the problem

There are many methods to identifying these needs. It should involve interacting with end-users of a particular service. End-users are not just citizens or the public. Users are whomever will be using the technology. You may also wish to interview individuals impacted by the technology to understand and address potential concerns. For example, a tool which helps adjudicate benefits decisions may have an internal agency user-base, but also external stakeholder groups like individuals for applying for benefits that are extremely important to factor into design decisions.

It’s important agencies really take the time to understand their problems in a deep way. It may be worthwhile for Federal agencies to consider working with 18F or a vendor on a short project to validate the stated problem before going further in development. There are several key items to consider.

##### Checklist

- [ ] Identify user needs, especially how the solution fits within the users journey or workflow, like how they will make decisions based on this information, etc
- [ ] Work with senior leadership to understand how the problem statement fits with their priorities or mission
- [ ] Identify key metrics and outcomes for solving the problem
- [ ] Understand previous attempts to solve this problem and those projects’ outcomes

##### Key Questions

- Have you identified the user needs?
- Can you hire an experienced team of designers or use experience researchers to identify the problem to be solved before investing?
- Have you gathered relevant information on the problem and solution history?
- How will the world be measurably different once this problem is solved?
- Have you aligned with your project’s important stakeholders to validate your metrics, goals, and outcomes for the project?

### Bring experienced teams in-house

You will need to recruit a data scientist for at least a short period of time to validate AI is indeed viable solution. Testing and evaluation before committing to a given path should always happen before advancing further with a pilot. 

Here are a set of situations where AI could make sense, taken together.

- The problem to be solved is extremely tedious and repetitive
- The problem is narrowly scoped (for example, differentiating this kind of object/sound/image from something else)
- The problem cannot be solved at scale with human resources
- The problem is too expensive to be solved at scale with human resources
- The problem can be ethically solved with a machine
- The problem does not have a solution that is easily programmed by an engineer (if you don’t know, go ask one!)

If you don’t have experts who understand your data and the relationship to your use-case in house already, bringing in someone in-house to do this has several advantages over bringing in a vendor.

- Generally speaking, in-house data scientists have few barriers to speaking with data owners, and getting access to data
- It may be cheaper than hiring a vendor, as an in-house data scientist can quickly create experiments and build models to test the viability of AI
- It may be faster than hiring a vendor
- That employee can oversee a vendor if a contract is awarded, especially if there isn’t the technical expertise on staff to work the vendor
- Such experts, combined with domain data experts, can interact and evaluate various company tools and ideas via AI tech sprints.

##### Checklist

- [ ] Work with a data scientist to validate that AI is a sensible approach to solving a problem
- [ ] Integrate vendor teams closely with your agency’s teams so that there is good communication practices, a responsive culture, and strong understanding of the problem to be solved
- [ ] Consider other technical approaches which solves the user need and satisfies the problem statement before settling on one initial idea
- [ ] Work with government fellowships like the Presidential Innovation Fellows, AAAS Fellows, and Presidential Management STEM Fellows as well as academic institutions in computer science to bring hard-to-find skill sets in statistics, computer science, and artificial intelligence into your agency
- [ ] Consider using hackathons as means to engage industry on building tools, evaluating tools, and exchanging ideas/perspectives around open datasets and/or datasets that only need simple data use agreements.


##### Key Questions

- What is your justification for using AI to solve this problem, versus robotic process automation (RPA), or another tool?
- Do you have an experienced person on your hiring team to evaluate whether the people you are hiring have the appropriate skills?

### Know your data

You will need a large volume of data to train machine learning models. Sometimes you might need to look outside your agency for data, or the data you have may not be useful for the problem you are trying to solve.

AI does not reason like a human. AI needs a set of inputs in the form of data, and can only return an output. For this reason, knowing your data is not just about the size or the right kind of data, but also involves the quality of your data. 

- How your data is generated (data provenance) 
- Accuracy
- Laws governing that data
- Validity
- Reliability
- Completeness 

Developing a strong understanding of your data is the first step to laying the groundwork for an effective data management strategy -- and eventually better software, including AI. You will need to hire a data scientist to do this, and you may want to bring them in-house.  

For a pilot, you may be able to use synthetic data (or artificially created data) to test the viability of an AI solution meeting a user’s needs. If you find new data within your agency, in accordance with the Federal Data Strategy you should document it, and if non-sensitive, make it available in a machine readable format for data discovery (for example, on data.gov). 

##### Checklist

- [ ] Work closely with data owners, data scientists, statisticians, and subject matter experts within your agency to understand the state of your data including accuracy, validity, reliability, completeness, and more
- [ ] Consider where you might identify other sources of data both short-term and long-term -- can you buy the data, artificially create it, collect it from other places that haven’t been surfaced yet, add new means of collecting data like sensors
- [ ] Know where your data is physically located and points of contact
- [ ] Be sure data has links to provenance information to facilitate quality checks, reproducibility, and interpretability
- [ ] Keep your data clean as you collect and store it
- [ ] Understand data standards, ontologies, and terminologies that may be applicable to your data

###### Key Questions

- Do you have the data you need for your problem?
- Given where your agency is headed is there data you need in the long-term that you can begin to collect now or test in the form of a pilot?
- Do you have experts to help you evaluate whether your data is a fit for AI?

### Continuously test and evaluate prototypes

Developing AI solutions is an iterative process. Data scientists will run through a machine learning process - which includes creating training data, test data, and trying different approaches and parameters to get the most accurate and usable output. In addition, diverse teams will need to test prototypes - and typically many iterations before you have working software that can be piloted with a group of users.

Integrating these algorithms into a software application will probably involve more than a data scientist. You will likely need a diverse team including at least a designer, engineer, and possibly a product manager to work with the product owner on your team. They should be familiar with user-centered design and agile.

Look for the team to describe iterations based on user-provided feedback and findings. This iteration applies the data being used for training AI, the AI models applied, and the user experience.  During the iteration and prototyping process getting to real software that can be piloted, the team should be demoing their software on a regular cadence to leadership and the agency product owner.

##### Checklist

- [ ] Use experts for identifying good training and testing data
- [ ] Collaborate with training data owners and model developers in order to understand the scope and suitability for the specific application
- [ ] Recruit at least one designer, and possibly a front-end and back-end engineer to develop prototypes and ultimately build software that can meet user needs for a pilot
- [ ] Require the team to follow practices like the Digital Services Playbook, and the Defense Innovation Board’s Detecting Agile BS Guide
- [ ] Ensure that the team is well integrated with the problem and data experts so that there is regular, efficient communication without requiring additional oversight or layers of access
- [ ] Ensure that the team can interview end-users without running into barriers like the Paperwork Reduction Act

##### Questions

- Does the team have experience working in the government?
- Is the hired team really agile?
- Does the team have access to the original training data owners and model developers?
- What would the AI model be compared against (e.g. non-AI process) and  what are the proper accuracy metrics to use for such comparisons?
- What is the accuracy of the algorithm and is it sufficient given the user’s needs?
- How is user feedback factoring into the prototypes being developed by the team?
- Is the team demo’ing working software on a regular cadence?

## Culture and Education
 
AI involves different risks than just normal software. While there are all the risks of typical software development in government, there are a variety of different issues related to agency culture that can pose a risk to an AI project. Education is critical to managing stakeholder expectations and concerns. 

### Manage key risks, including resistance

Every software project has a certain amount of inherent risk. We use agile as project management philosophy because we can’t predict the future. Here are some risks that are especially important to AI.

- Legacy infrastructure where sharing data is not easy technically 
- Data which involves special protections
- Data which requires a substantial review period before any individual can access
- Ambiguity and uncertainty around the quality of the data
- Biased data
- No clear data owner, or person responsible for the quality of the data set
- The data owner being unaware of the project 
- Fear, uncertainty, and doubt over how an AI will fit with an existing workflow
- No communications plan with users about the impact of AI
- No communications plan with senior leadership about the purpose of the AI

The majority of these risks have a strong communications and culture change element so communications, especially with the users affected by AI tool, data owners, and leadership are all especially important. 

##### Checklist

- [ ] Work with a product manager to identify the risks in your project
- [ ] Proactively communicate with your projects’ stakeholders regarding risk
- [ ] Communicate regularly and proactively with users, senior leaders, data owners, and more
- [ ] Work with data owners and data science to understand the quality of data

##### Key Questions

- What will you need and from who?
- What are the most likely reasons this effort would fail?
- Have you identified everything you need to make this pilot a success?
- What is the minimum level of success this pilot needs?
- Who are the most important people to be communicating with?

## Assess and manage ethical concerns

The automation of government processes should not create a negative experience for citizens. This might include:

- Putting some groups at a disadvantage over others
- Making it harder to access or find important information
- Breaching the privacy of citizens
- Creating feelings of discomfort or a sense that they are being monitored

Machine learning approaches in AI are reliant on data to build predictive models. These models become part of decision-making pipelines which in turn become part of the software application with which users interact. If the data itself is biased, the software will reflect those biases. 

Biased software can mean that vulnerable populations are discriminated against, as vulnerable populations are oftentimes statistically under or overrepresented in data. Bias can also occur outside of the domain of classical discrimination categories with which we are familiar as citizens. Bias can also occur when underlying variables take on mathematical significance or weight in an algorithm. This kind of bias could well systematically skew decision-making related results of algorithms in ways that are hard to detect. Being cognizant of this possibility is important in order to test for and mitigate bias. 

##### Checklist

- [ ] Understand where your data comes from. Know the ramifications on how trustworthy and unbiased the dataset itself is by talking with individuals responsible for its collection and management
- [ ] Consider filling out an Algorithmic Impact Assessment to determine the potential algorithmic risk for citizen harm
- [ ] Identify indicators of citizen harm and construct a plan to measure and report on those indicators regularly
- [ ] Work with data scientists to understand what your model’s error rate means for your software’s performance and the ramifications on citizens
- [ ] Conduct user interviews with citizens to understand how current services work or don’t work for them, paying special attention to vulnerable populations. Use this information to better understand what your data for building a model might be leaving out
- [ ] Involve your agency’s privacy office in conversations around your plans for developing a new service. Work with them to identify privacy issues and have plans to mitigate them
- [ ] Be aware of the potential for the identification of citizens private information from the sharing of machine learning models, and consider partial sharing of code only

##### Key Questions

- Is a person very knowledgeable about the data and the subject matter on the team?
- Where does this data come from? 
- How reliable is the reporting and collection methods?
- What is the experiences currently of vulnerable populations interacting with us, and how would this new service impact them? 
- Is there appropriate human oversight and control of the system?
- Did you implement appropriate strategies to enhance privacy, such as training models on non-sensitive data, using encryption, etc.?
- Can a non-technical person on your team explain what your algorithm is doing?
- Did you take users’ preferences into account for accessing information, and ensuring that you have non-digital means to access the same information?

### Build support and educate senior stakeholders

AI is very much a new technology in the federal government. Very senior leaders are often unaware of the technical details of implementation. Furthermore, your leadership in legal, finance, operations, security and more will be unfamiliar with AI. Beginning a project with a strong cadence of communication with these leaders establishes trust and begins to set expectations on what the pilot will look like. 

Culture change is a team sport, and no pilot can accomplish this on its own. But by showing what is possible with AI and setting expectations, you can increase the organization’s chance of a good experience. This means that the second project will be more likely to succeed.


Checklist

- [ ] Know what data you need and get the data owners bought in early
- [ ] Map agency mission to AI/ML resource requirements in a way that meets leadership accountability mandates
- [ ] Be aware of trends in the market or academia where similar processes to your own have been advanced through new technology and use those as signposts for the future and to gain buy-in.
- [ ] Win over leadership to do a pilot, and build the pilot to demonstrate alignment and to win over leadership
- [ ] Share business problem findings with team and agency leadership

Key Questions

- Is the AI pilot structured to demonstrate unambiguously alignment with agency mission and data structures? 
- How is leadership invested in the AI pilot?
- Is the risk-of-loss tolerable to the agency should the AI prototype and/or pilot fail? 

## Run your pilot

Pilots take working software and tests it with typically a substantial user segment to give development teams and leadership a window into how well the software works as a solution. 

A pilot of AI should also involve live data, where the algorithm and the software is integrated into a user’s workflow. During a pilot phase, evaluate the success of the model to ensure that the outputs are understood by the users. Collect user feedback and ensure that the feedback is relayed to the entire team and used in the next iteration of the software. 

### Have a clear plan

Before actually running the pilot, have a clear plan. Running a pilot but having results that are not actionable is a tremendous waste of resources and time. Decide beforehand what the important metrics are for the software and algorithm you are piloting. Refer back to the original business problem and user needs you identified. 

Also, it’s important to consider how you’ve set up your system to collect feedback. For example, you may wish to conduct user interviews during the pilot to continuously collect user needs and new user stories. You may also place monitoring analytics to collect quantitative measures of user actions. Finally, continuously monitoring and evaluating the model during this phase is important so that you know if and when you need to retrain your model.

##### Checklist

- Know your important metrics for success, both technical (things like performance) and non-technical (the user needs)
- Have a clear plan in place for monitoring the performance of the algorithm and the usability of its outputs
- Document the results of the pilot for further learning and evaluation by the software team
- Continue to collect user needs and turn them into user stories during the pilot phase

###### Questions

- What are the hypotheses being tested in this pilot?
- What are the key metrics?
- How are key stakeholders being involved and informed of the pilot?
- What is the plan for documenting and sharing the results of this pilot?
- How will the pilot results inform future iterations?

### Create standards for measuring the performance of models

Training and testing datasets designed for AI with testing datasets tests enable models to be tested and trained. The evaluation process should be started as early as possible in the planning process. It can involve obtaining models from external organizations and testing them for accuracy on previously unseen data. Agencies may also build/leverage tools to serve as honest broker for testing. Alternatively, a trusted third party may take this role.  

Either way, the key is to have some data be kept for testing that is not used in the training process. Working with industry is useful to understand broader sets of use cases- and challenges/sprints can enable comparisons of different models for fit for purpose. Sometimes, data is located on different servers and cannot be combined into a central database due to privacy or other concerns. In such cases, federated approaches may be useful, whereby computing is done on local servers and then resulting analysis is shared with others.  This can  enable AI results to be combined from data across sites in ways that protect access of the individual servers’ data by outside users (e.g. for privacy).

##### Checklist

- [ ] Develop a model evaluation plan at the beginning of the design process
- [ ] Create a gold-standard data set annotated by experts that can serve as basis for measuring model performance
- [ ] Release only a subset of gold-standard dataset, if any, for training purposes by external parties/vendors, keeping some for testing of model performance
- [ ] For testing models, compare model predicted results against gold-standard
- [ ] Define accuracy metrics used in evaluation process
- [ ] Iterate on algorithms using human input to tweak performance on training datasets (always keeping testing data separate)
- [ ] Evaluate the relative weight of various features of the model for quick sanity check and explore explainability to see if follows human intuition
- [ ] Do sensitivity analysis to understand how data variations can affect predictions

##### Key Questions

- Are there standard training/testing datasets already available in the agency or externally?
- Is there a third party that can do independent model testing? (in which case gold-standard test data would be given to a third party)
- Is the model explainable?
- What accuracy metrics best represent user needs?

### Know and follow the relevant laws to your project

AI is software. It is code and data. AI and other types of automation (including Robotic Process Automation) are not an entity or an agent that has the rights of a human being. Agencies should expect to comply with all existing laws and policies with respect to data and software. Whether an agency create algorithms may depend on the consent and privacy laws governing the use of the data that was collected. 

##### Checklist

- [ ] Understand what data protection questions need to be answered before implementing a machine learning algorithm or building a dataset. For example, building a training set by extracting data programmatically from websites (a legally grey area)
- [ ] Identify any laws and policies implementing an algorithm will impact
- [ ] Consult early with Legal and Privacy Officers, and bring data owners to these early conversations in order to discuss protections around the information being collected and used
- [ ] The appropriate privacy, civil liberties, and/or legal advisor for the department or agency is a partner

###### Key Questions

- What are the roles and responsibilities for the pilot?
- What are the laws and policies that impact this algorithm?
- What are the key privacy issues?
- What information protection questions need to be answered?

## Post pilot: Now what?

You’ve run your pilot. You’ve collected valuable user feedback on how useful your tool is. Your tool is using live data. What do you do now?

### Consider the long-term investment strategy

In the short term, a pilot needs to test the foundational ideas and hypotheses discovered in the user research, as well as get a better sense of the technical feasibility of the path.  

However, long-term considerations are a bit different. Long-term you will need to 

- Have a sound plan for managing the data used by the AI model
- Have a plan for updating the software 
- Ensure the quality of the AI outputs

You may also need alternative infrastructures and services like a specialized chip (Graphics Processing Unit)-based cloud based environment for managing data and running the models. AI takes much more computing power than traditional software applications because the amount of the data being modelled continuously and at high speeds. Consider infrastructure needs based on the quantity of data that needs to be processed, stored, and speed of access/transfer required.  For computations, understand the computational complexity and ability for parallelization of the algorithms/models to determine the speed and quantity of processors needed as well as memory requirements.

AI may not be a possible solution if the infrastructure you are deploying it to can’t keep up with the requirements needed to provide a good user experience. Other investments in talent and education may also be needed.

##### Checklist

- [ ] Determine whether AI can be supported on your current infrastructure
- [ ] Understand if there will be resources for this project after the pilot ends if it is successful
- [ ] Roughly scope out the various needs (technical, data, human) if your pilot is successful

##### Questions

- What kind of resources can this project expect if the pilot is successful?
- How is your infrastructure suited for AI?
- What are you seeking to optimize in your long-term strategy- cost, building in-house technical capacity, agility to quickly implement new projects, performance on single large projects?
- Do you have a sustainable business model?

### Lay the seeds for future experimentation

In order to steward artificial intelligence in the government, we need professional data scientists, but we also need a trained non-data science workforce that is capable of identifying opportunities within their own workflow for automation, that can think ahead to the future, evaluate vendors, and manage teams that may include data scientists and software engineers. 

Developing in-house talent is about recognizing that automation, data, and software is changing the way government does its work. To be proactive, thoughtful, and effective stewards of this work, it is important that agencies look at how it can grow these skills within their own walls. AI is a discipline which includes statistics, computer science, and software engineering. Technical staff with a background in at least statistics are often capable of learning more computational approaches.

##### Checklist

- [ ] Identify individuals with experience conducting web analytics, doing statistical analyses or economic analyses using statistical processing methods, managing major databases, and working as data architects
- [ ] Give talented technical experts a few hours each week to explore problems that interest them outside of their day-to-day tasks. Ask them how they might solve those problems, and consider how you might provide them resources if they present a compelling business case
- [ ] Encourage technical experts to take online training courses like Coursera, MIT Opencourseware, Edx, and others to enhance their existing skill sets with new ones. 
- [ ] Encourage the use of open source packages and libraries like R, Python, Keras, Pytorch, and sci-kit learn to promote literacy in industry-standard tools, avoid blackbox tools where it is difficult to de-engineer how a given software tool made a decision, and get to prototype faster than traditional procurement
- [ ] Consider how internal classes taught by more experienced technical staff can enhance the skills of less experienced staff and promote greater data and artificial intelligence literacy and understanding
- [ ] Explore whether budgetary set-asides are permitted to fund innovation, experiments, and prototype development

##### Key Questions

- What skills do you have in your agency currently in statistics, informatics, analytics, mathematics, computer science, and software engineering? 
- Have you given your talented technical people time to experiment with new tools and grow? 
- Have you considered setting up data science guilds, classes, or workgroups taught by more experienced internal staff?
- Have you considered internal hackathons to give technical staff time to identify their own problems and solve them?
- Does your agency culture prioritize internal innovation or is it focused on acquiring market-driven solutions

## Appendix