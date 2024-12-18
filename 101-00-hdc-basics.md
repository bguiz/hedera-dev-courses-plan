# Course 101 - Hedera Developer Course Basics

## Course modules

- 101-01 - Hedera TLDR
- 101-02 - Querying Hedera Network State
- 101-03 - Setting up a Hedera Development Environment
- 101-04 - Hedera Accounts

## Learning Objectives

At the end of the programme, students will:

1. Appreciate Hedera's similarities and differences with other DLTs
1. Appreciate Hedera's mix of native and and EVM services
1. Query network state using a variety of different methods
    - Includes: Mirror Node API, JSON-RPC, Hashscan, HAPI via SDK
    - Excludes: HAPI without SDK
1. Set up, and work in development environments to build on Hedera
    - Includes: Pre-configured cloud development environment, and on local computer
1. Generate new accounts on Hedera, and fund them using a variety of different methods
    - For generating new accounts, includes: BIP-39 seed phrase, SDK, Portal
    - For funding accounts, includes: Faucet, Portal, SDK
1. Transfer cryptocurrency from one account to another

## Method of delivery

- Online course
    - Accessed through a web browser
    - Available through LMS software
- Course content is accessible on-demand (no cohorts)
- Graded assessments are accessible in cohorts

## Pedagogy

- As this is a basic course, students are expected to attain a beginner to intermediate skill level in developing on Hedera.
- This maps to the first four levels of this taxonomy: Fink's Domains of Learning:
    - **Learning how to learn, foundational knowledge, application, caring**, human dimension, and integration
- This also maps to the first four levels of this taxonomy: Bloom's Levels of Learning:
    - **Remember, understand, apply**, analyse, evaluate, create
- Note that students may acquire skills in areas exceeding the indicated levels within each taxonomy, even though the course does not expect these within the course.
- These additional levels are expected to be acquired in the Advanced Hedera Developer Courses (30x series), for which this course, along with the 20x series are prerequisites.

Teaching style

- This course is primarily technical and hands-on in nature.
- As such, in each module the materials are provided to students in the following sequence:
    1. Read student guide (document)
    1. Watch explanation of the theory for the module (video)
    1. Read slides used in theory explanation (document)
    1. Complete quiz (interactive web app)
    1. Watch explanation of answers to quiz (video)
    1. Lab session to demonstrate
        1. Watch a fast demonstration without explanations (video)
        1. Watch a slow demonstration with explanations (video)
        1. Obtain copy of code starting point for lab (git repository + document)
        1. Replicate demonstration (git repository)
    1. Complete self-assessment questions in student guide (document)
    1. Check own answers for self-assessment questions in student guide (document)
    1. Watch recap of the module (video)
    1. Obtain copy of code starting point for graded assessment (git repository + document)
    1. Complete and submit graded assessment (git repository)
- The above teaching style is derivative of two pedagogical methods: The DEDICT learning model, and Kolb's experiential learning model.
    - These are better suited to the hands-on learning style that is needed in a practical, hands-on course, such as this one.
    - Other pedagogical methods are better suited to academic/ theoretical learning styles.
    - The DEDICT learning model is explicitly seen in action here with the fast-then-slow approach for the lab videos.
    - Note that the term pedagogy is used here, even though what is really intended in *andragogy* as it will be adapted to adult learning styles.
- Adaptations for course delivery mode
    - This course is going to be delivered online, through a web browser, using LMS software.
    - As such, components of the pedagogical approach which are only possible when executed in-person or synchronously are simply not possible.
    - In lieu of these, these component are dropped or adapted out of necessity.

## Materials

The course will *primarily* be delivered via **video**.
These videos will be *complemented* with a suite of **supporting materials**.
These materials are designed to specifically aid student learning
and retention of the course content.

### Student Materials

- Explainer videos
    - Presentation using a simple slide deck
    - Covers theoretical concepts
- MCQ videos
    - Explanations for the answers encountered in the MCQ interactive
- Lab videos
    - A fast with no explanations version of the video
    - A slow with explanations version of the video
    - As per the DEDICT pedagogical method
- Student guides
    - Overview
    - Learning outcomes checklist
    - Self-assessment questions
        - Cloze, open-ended, infographics, etc
    - Definitions
    - Resources
    - Code snippets
    - Self-assessment answers
- Slide decks
    - A document export of the slide deck that was used in the explainer videos
- MCQ interactives
    - Interactive web app within the LMS
    - Student is asked to pick from a set of options for each question
- Lab initial code repositories
    - An incomplete version of the code, which matches the start point in the lab video
    - Instructions document containing a step-by-step walkthrough of the lab
- Assessment initial code repositories
    - An incomplete version of the code
    - Instructions document detailing the tasks expecting, submission instructions, and optionally some hints
- Feedback forms
    - For students to provide feedback about the module
    - Uses a standard questionnaire

### Instructor Materials

- Instructor guides
    - Key takeaways for students
    - Additional resources
    - Explanations/ FAQs
- Lab completed code repositories
    - A complete version of the code, which matches the end point in the lab video
- Assessment completed code repositories
    - A complete version of the code, which serves as a model answer for submissions
- Automated grading scripts
    - Code scripts which verify and assess student submissions for graded assessment
    - Similar to unit tests, but adapted for grading

### Custom Software

- PDF renderer
    - Used to convert from markdown to PDF
    - Features custom headers and footers
    - Student guides, instructor guides, lab sheets, and assessment sheets
- MCQ renderer
    - Used to convert from JSON to LMS-specific required formats for MCQ uploads
- Assessment grader
    - Retrieves student submissions from private Github repos that have been shared with our Github account using Github APIs
    - Validates the status and metadata of the submitted repository
    - Uses a sandboxed environment to execute and run specified files within the student submission
    - Runs the automated grading scripts against these and computes scores for the students

## Qualification prerequisites & assessments

- No other courses are needed
- Proficient in written and spoken English
- Proficient is programming using Javascript
- Able to execute command line instructions in a shell/ terminal

## Assessment structure

Each module carries the following components that are assessed:

- One set of self assessment questions
- One or more sets MCQs
- One graded assessment

## Grading rubrics

Criteria for each type of assessment:

- MCQs
    - 60% to pass
    - Automatically graded by the LMS
    - Unlimited retries
    - May not proceed to the next module without passing
    - Easy level of difficulty
- Self assessments
    - Both questions and their answers are provided in student materials
    - Students are expected to attempt the questions without looking at the answers
    - Subsequently, students are expected to grade their own answers
    - Honesty system to pass, this is not verified
    - Harder/ trickier than the MCQs
- Graded assessments
    - Grade bands
        - A: 90%
        - B: 80%
        - C: 70%
        - D: 60%
        - F: 0%
    - Manually graded by instructors
    - Instructors are to make use of the assessment grader to automate assessments
    - May retry only upon next "review period"
        - TODO determine duration of review periods
        - TODO determine resourcing for reviews
    - May proceed to next module after submission, no need to wait for the grade

## Certification

To qualify for the course certificate, students must:

- Attain a minimum "D" grade for the graded assessment
- Attain a pass in MCQs
- Complete the self-assessment questions

Certificate

- Upon meeting all requirements for the course successfully,
  students will be awarded a certificate
- Format: NFT
    - TODO details
- Format: PDF
    - Will bear a logo, title of the course, name of the students, date awarded, a unique serial number, and QR code hyperlinks
    - The serial number will correspond to the ID of the NFT
    - The hyperlinks will be to (1) the NFT, and (2) the verification DApp
- Verification DApp
    - TODO details

## Course structure and duration

- Number of modules: 4
- Duration of video lessons: TODO_VALUE
- Duration of supplementary materials (estimated): TODO_VALUE
- Duration of assessments (estimated): TODO_VALUE
- Forms of study:
    - Online on-demand self-directed learning
    - Independent study
    - Cohort based instructor assessments

Estimated durations breakdown

- Module 101-01 - Hedera TLDR
    - Student guide: TODO
    - Explainer: TODO
    - Lab: TODO
    - Self assessment: TODO
    - Graded assessment: TODO
    - Feedback: TODO
    - Total: TODO
- Module 101-02 - Querying Hedera Network State
    - Student guide: TODO
    - Explainer: TODO
    - Lab: TODO
    - Self assessment: TODO
    - Graded assessment: TODO
    - Feedback: TODO
    - Total: TODO
- Module 101-03 - Setting up a Hedera Development Environment
    - Student guide: TODO
    - Explainer: TODO
    - Lab: TODO
    - Self assessment: TODO
    - Graded assessment: TODO
    - Feedback: TODO
    - Total: TODO
- Module 101-04 - Hedera Accounts
    - Student guide: TODO
    - Explainer: TODO
    - Lab: TODO
    - Self assessment: TODO
    - Graded assessment: TODO
    - Feedback: TODO
    - Total: TODO
- Total:
    - Student guide: TODO
    - Explainer: TODO
    - Lab: TODO
    - Self assessment: TODO
    - Graded assessment: TODO
    - Feedback: TODO
    - Total: TODO
