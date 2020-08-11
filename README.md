# 0.0 UCFD - Web CV & Work Samples Application Package

Project Process and Development Guidelines following 

## 0.1 The Five Planes of UX

> ###### Distribute content and feature development across five activity planes
> 
> ###### Methodology for taking product from conception to release

# 1.0 Strategy Plane

> ###### What we are trying to achieve
> 
> ###### For whom we are trying to achieve it

- The main goals of the site are:
  - To establish a personal brand for the owner and avatar for the owner's online presence
  - Attract and retain a following in the developer community
  - Attract recruiter reader software and analytics
  - Be up to a standard that is competitve with UX designed responsive web resumes 
  - Stand out to [Code Institute](https://codeinstitute.org/)'s qualification partners and potential employers
- The website is built for:
  - A young professional designer and architect (buildings) presently breaking into the tech industry 

- Their goals and needs are:
  - In addition to above (as the site is the owner is the business is the consumer), the ultimate goal is to transform a CV into an interactive, attractive and customisable experience that reflects the candidate's proficiency in the manner in which the content itself is presented.

## 1.1 Research

- Who else is building this?

  - Not all Software Developers care about UX. Equally, not all UX designers care about developers. They are more like consultants to each other, wher one "hands off" the design prototype to the developer for "developing." I learned this after using much of the software for UX designers. Wireframing for UX Designers does not start at low-resolution. Components designed on Adobe UX are directly exported as local _.svg_ files, ready to be animated. In the realm of UXD, points go to customization. Developers, on the other hand, just need bare bones of function when establishing wireframes. 
  - Nonetheless, everyone who knows how to write code has built some form of a custom resume.
  - The key difference is the degree to which one is branded or specific as opposed to *not* branded or generic.

- How are they doing it?

  - Most of them are generic (if the content is thorough) *or* designed (if the content is minimal). 
  - Some are templates purchased from web designers. And those are the most impressive ones. 

- What are the pros and cons of what they are doing?

  - Some of the pros of either fully or personally branded web resumes are the completeness of its graphic design and content availability. The cons, on te other hand, are the sacrifice of common "Laws of UX."  Things are not where you expect them to be. It is not easy to "find your way back." And its responsive features are for design, less for function. The ones that *are* mobile-first, otherwise tend to be straight out of Bootstrap and don't stand out as a thorough representation of professional brand unique to one's personality.

- What are they missing?

  - At either end of the spectrum, what most of them are missing is a graphic narrative. And an honest voice. There is no belief system that resonates, or speaks to a niche market. In other words, they're not aiming at a specific company; they're aiming at anyone at all who will hire them. And relying on their impressive GitHub profile to do much of the heavy lifting (and successfully so.)

  - In one article outlining [what companies really look for in your GitHub profile](https://www.builtinchicago.org/2018/05/08/what-companies-look-for-on-github), it's clear that companies value personality and shared values over one's GitHub "brand." That being said, they do look for something else in you GitHub -- an *influencer*

    > Engineers with a lot of activity on their profiles show me how involved they are as developers. I’m also interested to see how many followers they have, because a surplus is often a good indication of their role as a thought leader.
    >
    > [Source](Engineers with a lot of activity on their profiles show me how involved they are as developers. I'm also interested to see how many followers they have, because a surplus is often a good indication of their role as a thought leader.)

- What could they do better?

  - "Designed" resumes for web developers can benefit from using principles of UX and using the language speak for the content. Having the content be fold back in the way it is being told. So that it demonstrates thinking that is algorithmic, parametric. So that the the website itself showcases the very skill highligted in list of skills. 
  - They can also benefit from demonstrating interpersonal artistry. Activity in the feed, so to speak. 
  - A lot of them are missing skills that others don't already have. They are not capitalizing on what it is about them that stands out: *narrative*. And capitalizing on how their non-dev background  might  position them uniquely by virtue of being *different*.
  - In terms of providing an "application package," none of them have a page template for a cover letter. This would be for the event that the owner send the website link directly as an application.

a programmer should understand better than most how important muscle memory and shortcuts are to productivit

MO it's not just about "values of architects". They're a population that does cognitively demanding work (so polished UX is of fundamental importance) that tends to have more of a fine arts background than a software background (so right-to-modify does nothing for them).

FOSS is just ... a bad deal for them. They want someone they can call and yell at when they're on a deadline and the software isn't working, and they want tools that get out of their way.



UX design is done by designers and product managers. Developer just implemented ability to assign hot key X to function Y. How this ability used was not his/her concern.

## 1.2 Planning

- What relevant content should we deliver that fits our demographic?
- How can we make the content easily tracked and catalogued in an intuitive way?
- Is the technology appropriate? What are the tech considerations?

## 1.3 User Expectations

> #### What does the visitor expect? Consider that the visitor is asking themselves these questions when they come to the site for the first time:

- What is this? Is it what I expected to see?
- Does it look credible and trustworthy?
- Does it offer what I want?
- Does it look valuable enough for me to stay and return?
- What actions can I take now?
- How do I learn more?
- How do I contact someone?

### Why is this website special? Why would a visitor desire this (experience)?

- User Stories
  - Senior Developer (Back End)
    - As a leader in the industry, I won't spend much time here. What is it about this candidate/service/product that stands out and that I haven't already seen in others? 
      1. I want to *see* that without having to *find* that. Whatever that is.
      2. Now I recognize the need for someone with your background, which migt have been a problem I didn't even know I had.
  - Recruiter (External)
    - As a stakeholder in the hiring process, if you win, I win. I've already seen your LinkedIn. I landed here from the job-hunt database in our server which means you were already recommended by someone. Why would you choose us?
      1. I'd like to know where you are and give you a call.
      2. My goal is to schedule you at your convenience, learn enough about you to engage you and share you with my team.
  - Owner
    - As an evolving candidate in an evolving industry, I want to be be able to control and customize features and pages. 
      1. I want to be able to customize the website for a specific company when I send an application.
      2. The goal is to further expand my candidacy in the form of a cover letter page -- a custom link -- that reroutes to the main page after being read.

###### Note: All additions and improvements to the plan should always count towards the goals of the user and/or the business.

## 1.4 Strategy table

When using the strategy table there is always a trade-off between importance and viability. Can we build a solution given the limited time and resources available?

### Importance is driven by business goals and user needs.

| id    | Opportunity / Problem / Feature             | Importance | Viability |
| ----- | ------------------------------------------- | ---------- | --------- |
| A     | Create online presence for owner            |            |           |
| B     | Increase GitHub followers for owner         |            |           |
| C     | Showcase samples of owner's work            |            |           |
| D     | Feature recommendations written about owner |            |           |
| E     | Increase recruiter interaction              |            |           |
| F     | Showcase owner's contribution footprint     |            |           |
| G     | Showcase owner's awards and recognitions    |            |           |
| H     | Dashboard functionality                     |            |           |
| I     | Custom landing page cover letter            |            |           |
| Total |                                             |            |           |

If importance and viability are equal, then we are in a position to do it all. Draw out your own version of the graph below to work out what features you should drop.

## ![](RackMultipart20200720-4-1ia7tvm_html_50562dc698e130a6.gif)

# 2.0 Scope Plane

> ###### Features based on information gathered from Strategy to include in design
> 
> ###### Itemizes what's on the table for a production release and what isn't

- Which features, based on info from strategy plane, do we want to include in the site?

- What is included in production release and what is not (for now)?

- Keep goals in line with strategy goals.

- User **SPRINT** goals to keep on track. Don't allow scope-creep to happen (additional features not agreed on in strategy)

- Pack in MVP features up front, unfold new experiences over time.

## 2.1 Requirements and functional specifications

- What users say they need.
- What they actually need.
- What they don't know they need.

There is a difference between how you imagine something will be used and how it is actually used.

- [ ] Brainstorm and mind map on what things people might not know they need. 

- [ ] Research and discussion on needs of the demographic.

## 2.2 Content requirements

- What mixed content/media do we need to meet the needs of the user?

### Requirement types:

- Objective – what does the user want to accomplish?
- Functional – What does the user need to reach their objective?
- Non-functional – What constrains does the site or app have to perform within?
- Business Rules – What dynamic constrains do we have to meet? (calculations, definitions, legal etc)

## 2.3 Releases

What will be included in each release?

#### Release 1

#### Release 2

#### Release 3

# 3.0 Structure Plane

> ###### How the information is structured
> 
> ###### How information is logically grouped

- How is the information on the site structured?

- How the information is logically grouped?

- Consistency of elements and relationships

- Is it learnable and intuitive?

- Can the user understand and easily navigate through the system when using it for the first time?

## 3.1 Organisation of Functionality and Content

How will the user navigate in an intuitive way through content and features?

- How do we get to a location?

- Where do we go from there?

- Categories of information

- Way the information is presented

- Intuitive interaction

- How is the information organised?

- What kind of structure will we use? 
  
  - Complex
  - Simple
  - Linear narrative - Discernible but restrictive
  - Non-linear/Hyperlinked - Flexible but possibly confusing
  
  > ##### Which fits the demographic and goals best?

## 3.2 Interaction Design (IXD)

###### The Visual Vocabulary

- How will we __define structure and behaviour of interactive elements__?

- How will we __create meaningful relationships between elements, content and information__?

- How will we __communicate functionality and interactivity__?

- How will we reveal workflows?

- How to reduce risk of user error?

- How can we make users aware of state changes in the system?

### Consistent

> People develop an expectation of conventions

- Follow conventions – navbar, buttons etc located and behave the way users expect.
- Colouring and themes consistent.
- Scenario
  - Any transitions, rollovers, tooltips act consistently
  - Leverage the visitor's prior experience here and elsewhere
- Voice
  - Labels and terms used should match throughout
  - Imagery consistent style
- 

> Only be different when it makes something better

### Predictable

- All elements should be easy to find and use.
- Include things like content hinting.

### Visible/Discoverable

- No luck involved
- All elements should be easy to find and use.
- Include things like content hinting
  - Partially reveal elements of your page just above the fold

> Make sure content is visible wherever possible

### Learnable

> Intuitivie = Single-trial learning

- Provide a strong sense of place (pageation, indication of which page you are on in the navbar)
- Set correct expectations (sub-menus, sub-navigation)
- Make it possible for people to accurately predict the outcome of their interactions

### Feedback

```mermaid
graph LR
    id1(Start)-->id2(Stop)
    style id1 fill:#f9f,stroke:#333,stroke-width:4px
    style id2 fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff,stroke-dasharray: 5, 5
```

- System provides feedback to let users know something is happening (change of state) 
  - Color change after button is clicked
  - Makes them feel assured
- Provides feedback in case of an error
  - i.e. 404 Error
- Provide link that will take them back to safety

## 3.3 Information Architecture (IA)

----

###### Information Architecture

> **Creation and organisation of navigational schemas**
> 
> __Allows users to:__
> 
> > Efficiently move through content
> > 
> > Be easily educated and informed
> 
> __Allows oweners to:__
> 
> > Accommodate growth and change

__*Which IA  type suits our users needs?*__

### Hierarchical Tree Structure

> Home
> 
> > About
> > 
> > > Feature 1
> > > 
> > > Feature  2
> > 
> > Portfolio
> > 
> > > CV
> > > 
> > > Download
> > 
> > Contact
> > 
> > > Form

- Standard structure, not complex.

- Problematic on mobiles (navbars helpful here)

- Navigation collapsed into a single "Burger icon" 

> Anything over three clicks is cognitive overload

### Nested List (Linked List)

```mermaid
flowchart LR
    List --> Sub-list --> Nested-List --> Content
```

- Linear path to detail
- Good for mobiles
- Prevents exploring

### Hub and Spoke

| Spoke     |             | Spoke     |
|:---------:|:-----------:|:---------:|
|           | ****Hub**** |           |
| **Spoke** |             | **Spoke** |

- Popular on mobiles
- Central home with links to spokes containing sub-sections of information
- Works for multi-feature apps
- Cant navigate between spokes

### Dashboard

| Detail1     |                                                                                                  | Detail2     |
| ----------- | ------------------------------------------------------------------------------------------------ | ----------- |
|             | <u>**Dashboard**</u> <br/> <u>Summary1</u> <u>Summary2</u> <br/> <u>Summary3</u> <u>Summary4</u> |             |
| **Detail3** |                                                                                                  | **Detail4** |

- Great for at-a-glance key info
- Detail views of related content
- More suited to <u>desktops</u>

## 3.4 Principles of Organisation

----

```mermaid
graph TD
    B(Corporate Website);
    B--xC(Consumer);
    B-->D(Business);
    B-->E(Investor);
```

> Audience is the organizing principle

```mermaid
graph TD
    B(Travel Website);
    B--xC(N. America);
    B-->D(Europe);
    B-->E(Asia);
```

> Geography is the organizing principle

- Organisational principles used at the **highest levels** of the site should be the most closely tied to **user needs** and **business objectives**.

- Those used at lower levels are usually influenced by **feature specifications** and **content requirements**.

- Every collection of information has a **built-in conceptual structure**. In most cases more than one.

- <mark>Find the right structure for the objectives and user needs</mark>

# 4.0 Skeleton Plane

----

----

> ###### How information is represented
> 
> ###### How user navigates information and features
> 
> ###### Skeleton gives form to the functions established in Structure plane

What form will the application take? How will the information be represented? How will the user navigate to the information and features?

- Rapidly establish value in the users mind

- Lead user towards continuing the experience

- Introduce specific content at the most relevant and appropriate points in the experience

- Add immediate value with each click

- Add positivity to the overall experience

> ###### For most users, the UI is the system

Good UI Design:

- Allows *immediate* interaction -- first-time learning

- Audience appropriate

- Perfectly meets the needs of its intended audience

## 4.1 Features and Usefulness

----

> Give people what they need when and where they need it 
> 
> Provide it in a visual format that they can and what to access

- Usability improves when similar parts are expressed in similar ways
- No surprises for user. Content may differ, but general shape and perception remains consistent

### Progressive Disclosure

- Reveal information over time and across space

### Grouping, Order and Hierarchy

- Visually group elements in order of importance

- Priority one established at Stategy level becomes the first information to appear

- Navigation elements and menu items *move from left to right in order of priority* of information and features

> The more features on the screen, the less user-friendly the screen is.
> 
> As features inrease in number and complexity, usability decreases.
> 
> As features decrease, usability increases.

- Give the user easy decisions, do not overcomplicate things

> The more choices you present you users with, the longer it will take them to reach a decision
> 
> -Hick-Hyman Law

## 4.2 Navigation Design

---

Intuitive Navigation and Completion of Tasks

- Placement, Order, Hierarchy, Priorities

###### How do you find what you want?

1. **Browsing** via a navigation system
   
   1. Clear categories

2. **Searching** via keywords and phrases
   
   1. Keywords in search

3. Using **filters** to narrow large lists and sets of information

4. Using **pagination** controls to provide:
   
   1. Information architecture
   
   2. Sense of depth/breadth
      
      Breaks info into smaller chunks so user is not overwhelmed
      
      Use progress bars with pagination
- Keep ordering of navigation simple

### Representational Icons

- Clear meaning

- Familiar objects

### Reduce Cognitive Friction

- Ensure avigation elements are visible and easily findable

- Ensure they don't require time to decode

- Differentiate between navigational elements with **colour, icons and text**

### Consistent

- Same interactions and behaviors

- Don't rearrange the order

- Don't move expected elements to a different location

### Metaphors

Good Design is:

| Literal                        | Metaphor       |
| ------------------------------ | -------------- |
| Innovative                     | light bulb     |
| Make a Product Useful          | wrench         |
| Aesthetic                      | paint brush    |
| Makes a product understandable | speech bubbles |
| Unobtrusive                    | sun            |
| Honest                         | book           |
| Long Lasting                   | house          |
| Thorough                       | list           |
| Environmentally Friendly       | earth          |
| As little design as possible   | dot            |

### Visual Metaphors

- Provide shortcuts for use

- Are intuitive and obvious

- Are taken from everyday life

## 4.3 Information Design

----

Arrangement of the elements that contain the information

> Information deisng should be invisible

- Easy to complete **forms**

- Strong **instructions**

- Strong **educational materials**

- Strongly represented **scientific data**

- No dangerous manufacturing Uis

- Everything is **relevant**

> Too much information is worse than no information at all.

### Context and Order Matter

- Use **categorical ordering** when information is similar and clustered
  
  - Courses
  
  - Blog

- Usee **alphabetical ordering** when information is referential
  
  - Contacts List
  
  - Dictionary

- Use **location ordering** when waydinding and orientation is needed
  
  - Sports, Geography site

- Use **time ordering** when comparing fixed duration events
  
  - Timeline
  
  - Work History

Which icons will we use? Which are best to represent our needs?

## 4.4 Interface Design

----

The best arrangement and visual presentation of the elements

- Prototyping and wireframes

- Mockups using Balsamic

### Wireframes

2D model of the product that provides 

- form 

- information

- arrangement volume

Just a starting point (no colours, images or effects referred to).

- See how each screen fits into the whole site

- Determine which links and content is required to meet the needs of the user

- See how balanced elements are & how they relate to each other

- What gets included

- How it is organised

- What gets priority

- Where are elements located?

- Has anything been left out?

- Is the top priority content noticed first?

- Revisit strategy and goals – are we on track?

- Do the relationships work?

- Paper first, then Balsamic or Marvel app.

# 5.0 Surface Plane

----

----

> ###### What the product will look like
> 
> ###### What colors, typography, and design elements are used

- What can the user do?
- How will the user interact with the site?
- What effects will be on the site?
- What can the user click on?
- Where can the user go?
- What is the final version of the info appearing on the screen?

## Visual Language

----

Provides information and context

- color

- layout

- fonts

- images

- order/sequence

- identity

### Economy

The most important elements are easily recognized

### Readability

> Legible
> 
> Font contrast
> 
> Consistent patterns

### Fonts and Typography

- Should be visually distinct

- Indicate diferent information

- Should be consistent

> ### Good UX smells like value.

